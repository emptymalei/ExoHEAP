Astrophysics
===============


Wave Bands
-------------------------


A table of wavebands in astronomy is something like this.



Doppler Shift
--------------------------

The special relativistic doppler shift can be derived using the fact that 4-momentum is a vector thus it transforms under Lorentz transformation.



.. image:: astrophysics/assets/dopplerRedshift.png
   :align: center


The observer is fixed in O' frame and source is in O frame. Emitting angle in O frame is :math:`\theta`.

Since momentum is a vector, we have the Lorentz transformation which transfrom it in to O' frame,

.. math::
   \frac{E'}{c} = \gamma \left(\frac{E}{c} - \beta p_x\right),

where we also have

.. math::
   p_x &= p\cos\theta,
   p = E/c.

Combining these equations, the energy of the photons in O' frame is

.. math::
   E' = E \gamma (1 - \beta \cos\theta).

In quantum mechanics, energy is related to angular frequency,

.. math::
   E = \hbar \omega.

The angular frequency in O' frame is

.. math::
   \omega ' = \omega \gamma (1-\beta \cos\theta).

Redshift is define as

.. math::
   z &= \frac{\nu_e - \nu_o}{\nu_o} \\
   & = \frac{\omega_e - \omega_o}{\omega_o} \\
   & = \frac{1/\gamma - 1 + \beta\cos\theta}{1-\beta \cos\theta}.


.. admonition:: Non-relativistic Doppler Shift

   To understand the effect of relativity, we would first recall the non-relativistic doppler shift.

   .. math::
      \omega'_{non-rel} = \omega_{non-rel}(1-v/c \cos\theta).

   where no :math:`\gamma` is relavent. It's obvious that we have only two kinds of shift, redshift due to the source is closing, or blueshift due to the fact that the source is moving away.


Here we have three different kinds, the additional one is the transverse redshift due to the :math:`\gamma` factor or the contraction of time.


An gif from wikipedia shows this explicitly,

.. figure:: astrophysics/assets/XYCoordinates.gif
   :align: center

   Image Source: `File:XYCoordinates.gif <https://en.wikipedia.org/wiki/File:XYCoordinates.gif>`_












Refs & Notes
-------------------
