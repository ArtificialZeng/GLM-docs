API
===

.. autosummary::
   :toctree: generated

   lumache
-  `/model/ <./model/>`__

   -  `modeling_glm.py </model/modeling_glm.py>`__

      -  class EncoderDecoder(nn.Module):

-  `/mpu/ <./mpu/>`__ 并行处理单元

   -  `\__init__.py </mpu/__init__.py>`__
   -  `transformer.py </mpu/transformer.py>`__

      -  class PositionalEmbedding(torch.nn.Module):
      -  class ParallelCrossAttention(torch.nn.Module):
      -  class ParallelSelfAttention(torch.nn.Module):
      -  class ParallelMLP(torch.nn.Module):
      -  class ParallelDecoderLayer(torch.nn.Module):
      -  class ParallelTransformerLayer(torch.nn.Module):
      -  class GPT2ParallelTransformer(torch.nn.Module):
