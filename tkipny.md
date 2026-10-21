代发 wailian999

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.cucudq.cn/Article/details/gtltbnuobl.html

Ruby: "Hello, #{name}!"
来源：http://dali.sysykeji.top/Article/details/gtqgylpehd.html

C#:   $"Hello, {name}!"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdhvzzfgf.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.fengsongda.top/Article/details/gtulmcmfxx.html

Py:   "第一行\n第二行"
来源：http://dali.jlsjyb.cn/Article/details/gteyyusqhc.html

PHP:  "第一行\n第二行"
来源：http://dali.ybcxt.top/Article/details/gtfdcugost.html

JS:   "第一行\n第二行"
来源：http://dali.zhiwuduotai.top/Article/details/gtajcevtzm.html

TS:   "第一行\n第二行"
来源：http://dali.quarkkingdee.top/Article/details/gtxiookqxi.html

Java: "第一行\n第二行"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpdefazig.html

Go:   "第一行\n第二行"
来源：http://dali.ppjwa.cn/Article/details/gtnlcndfxp.html

Ruby: "第一行\n第二行"
来源：http://dali.sxryk.cn/Article/details/gtliybinkm.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gtxvajnxbt.html

[A14] 注释写法
来源：http://dali.hnqzz.top/Article/details/gtuyudadlk.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.fzhhl.top/Article/details/gtkbryyoxo.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.shzxlz.cn/Article/details/gtgpdsoxbw.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhaomingkeji.xyz/Article/details/gtorlrmolu.html

TS:   // 单行；/* 多行 */
来源：http://dali.cdnleiting.top/Article/details/gtyedwzxbp.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.dianchejie.cn/Article/details/gtcjcfowjb.html

Go:   // 单行；/* 多行 */
来源：http://dali.daxiang520.top/Article/details/gthwmyznnf.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.hnxiangtu.top/Article/details/gtrlhlgjoy.html

C#:   // 单行；/* 多行 */
来源：http://dali.jinghuilouyu.cn/Article/details/gteymgulso.html

[A15] 空值判断与默认值
来源：http://dali.yanxiufei.cn/Article/details/gtmtpghszz.html

Py:   value = data or "默认值"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnkjojfwk.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.fzhhl.top/Article/details/gtwpmmcwyd.html

JS:   const value = data ?? "默认值";
来源：http://dali.smart0.xyz/Article/details/gthsfjfvis.html

TS:   const value = data ?? "默认值";
来源：http://dali.svipenyu.cn/Article/details/gtwocogbsb.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.pengpengdd.cyou/Article/details/gtchormsdh.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.sufxvd.cn/Article/details/gtvcdxarma.html

Ruby: value = data || "默认值"
来源：http://dali.wangdashe.top/Article/details/gtlfvvuqpu.html

C#:   var value = data ?? "默认值";
来源：http://dali.nanxinkj.top/Article/details/gtmetvtcmy.html

[A16] 真假值判断规则
来源：http://dali.ybcxt.top/Article/details/gtzmhjdvme.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.pengpengdd.cyou/Article/details/gtmofliccc.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.redwolf501.top/Article/details/gtiwplgfdw.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.redwolf501.top/Article/details/gtvtyybymr.html

TS:   if (!x) {}
来源：http://dali.jinqigufen.top/Article/details/gtcxtacats.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.yvedp.cn/Article/details/gtictxkfnk.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyeqdxanz.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.vqdsnc.cn/Article/details/gtduapcfvt.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.daxiang520.top/Article/details/gtptllyelu.html

[A17] 位运算
来源：http://dali.pycfn.com/Article/details/gtzhfpeajy.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.9152youxi.cn/Article/details/gtqucqjkgi.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.sufxvd.cn/Article/details/gtrlkwdeeg.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yuxming.cn/Article/details/gtvpulqesm.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.yongpay.top/Article/details/gtuqfdcola.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.smart0.xyz/Article/details/gtlyoqgrpb.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.dashuyun.cn/Article/details/gtsgfderrc.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.316326.xyz/Article/details/gtcotwbrvk.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hongshengwenyu.top/Article/details/gtybihjjxr.html

[A18] 字符与 ASCII 码互转
来源：http://dali.daxiang520.top/Article/details/gtkgrsholt.html

Py:   ord("A"); chr(65)
来源：http://dali.jinghuilouyu.cn/Article/details/gtggpyslxl.html

PHP:  ord("A"); chr(65)
来源：http://dali.vqdsnc.cn/Article/details/gtppprdjym.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.chenjidiqi.icu/Article/details/gtotjkteoj.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.tian-w.cn/Article/details/gtlxkqjqbu.html

Java: (int) 'A'; (char) 65
来源：http://dali.sysykeji.top/Article/details/gtdoyiztgv.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.0kj1m.cn/Article/details/gtgckakeku.html

Ruby: "A".ord; 65.chr
来源：http://dali.fzhhl.top/Article/details/gtcnduoipu.html

C#:   (int)'A'; (char)65
来源：http://dali.c1oappe.top/Article/details/gtlzkkudxq.html

[A19] 交换两个变量
来源：http://dali.hnxiangtu.top/Article/details/gtnhikxyha.html

Py:   a, b = b, a
来源：http://dali.haohaochexian.top/Article/details/gtiwnziycz.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.0kj1m.cn/Article/details/gtaudkqsfx.html

JS:   [a, b] = [b, a];
来源：http://dali.yj20258.top/Article/details/gtmnpausny.html

TS:   [a, b] = [b, a];
来源：http://dali.andypj.xyz/Article/details/gtsrdmkwdx.html

Java: int t = a; a = b; b = t;
来源：http://dali.tian-w.cn/Article/details/gtvxcxmoxw.html

Go:   a, b = b, a
来源：http://dali.wangshuangyany.cn/Article/details/gtrqklfayb.html

Ruby: a, b = b, a
来源：http://dali.hfpthk.cn/Article/details/gtnvxqiwwr.html

C#:   (a, b) = (b, a);
来源：http://dali.chenlongwang.top/Article/details/gtggodjmzy.html

[A20] 读取标准输入
来源：http://dali.shanyushiyangtech.top/Article/details/gtkarwnuth.html

Py:   name = input("请输入：")
来源：http://dali.daxiang520.top/Article/details/gtdrrqblbv.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.kuanghao11.cn/Article/details/gtaqbkaxwu.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.shzxlz.cn/Article/details/gtbpvmyooz.html

TS:   // Node.js：readline 模块
来源：http://dali.jlsjyb.cn/Article/details/gtzrieojbm.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.xziqi.cn/Article/details/gtzkcscmjt.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttlomsnil.html

Ruby: gets.chomp
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxvktnuxz.html

C#:   Console.ReadLine();
来源：http://dali.tian-w.cn/Article/details/gtnwewgoim.html

[A21] 保留指定小数位输出
来源：http://dali.cqqwz.cn/Article/details/gtstqmgyws.html

Py:   f"{3.14159:.2f}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtmhybussl.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.ehwqpu.com/Article/details/gtezqcmwme.html

JS:   (3.14159).toFixed(2)
来源：http://dali.chenjidiqi.icu/Article/details/gtgydicwal.html

TS:   (3.14159).toFixed(2)
来源：http://dali.jinqigfzy.top/Article/details/gtomdcmhih.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.chenzaomai.com/Article/details/gtbiidgdhj.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.cheryme.top/Article/details/gtavxxewia.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.guannengcc.top/Article/details/gtwfklxusr.html

C#:   3.14159.ToString("F2")
来源：http://dali.pengpengdd.cyou/Article/details/gtqmttptgq.html

[A22] 获取字符串长度
来源：http://dali.zycfv.cn/Article/details/gtsuxidlfn.html

Py:   len(s)
来源：http://dali.aizwys.cn/Article/details/gtwqbqxjhz.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.jqgfzy.top/Article/details/gtbtupplqc.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.daxiang520.top/Article/details/gtrwdpnkyv.html

TS:   s.length
来源：http://dali.jqgfzy.top/Article/details/gtrggperaj.html

Java: s.length()
来源：http://dali.xuanzx.com/Article/details/gtzinugejw.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.hfpthk.cn/Article/details/gtzwohntjp.html

Ruby: s.length
来源：http://dali.yueranfly.top/Article/details/gtvouyxbiz.html

C#:   s.Length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxyhkuzrt.html

[A23] 大小写转换
来源：http://dali.cheryme.top/Article/details/gtljkykjyh.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.gaohongyu789.top/Article/details/gtmtjdoimv.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.guannengcc.top/Article/details/gthakzmkxk.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.yongpay.top/Article/details/gtarmjxqsi.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkfrzomhd.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.quarkkingdee.top/Article/details/gtxlotzpkp.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.aibaodan.cn/Article/details/gtqxvwirdd.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.havefunace.top/Article/details/gtifeqfcjm.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.ybcxt.top/Article/details/gtthuzyxje.html

[A24] 去除首尾空白
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcrqsnltd.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.zycfv.cn/Article/details/gtefnfepxf.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.jianghu66.top/Article/details/gtaowmyiwm.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.sysykeji.top/Article/details/gthwbwsppe.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yueranfly.top/Article/details/gthclfcrow.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.316326.xyz/Article/details/gtfpndifwf.html

Go:   strings.TrimSpace(s)
来源：http://dali.vqdsnc.cn/Article/details/gtduldcxvq.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.hfpthk.cn/Article/details/gtwqyeaupy.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.yueranfly.top/Article/details/gtjhbriyil.html

[A25] 字符串比较
来源：http://dali.hfpthk.cn/Article/details/gtujofylms.html

Py:   s1 == s2; s1 != s2
来源：http://dali.wangshuangyany.cn/Article/details/gterpzitic.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.jinqigfzy.top/Article/details/gtktdoclam.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.smart0.xyz/Article/details/gthwlfrmcb.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.sufxvd.cn/Article/details/gthoepbgzw.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.gaohongyu789.top/Article/details/gtcprskvgr.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.sysykeji.top/Article/details/gtujcwbkhn.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.yuxming.cn/Article/details/gtebdmoous.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.nanxinkj.top/Article/details/gtswxemrkd.html

[A26] 类型转换总览
来源：http://dali.dianchejie.cn/Article/details/gtwpiapywd.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.ppjwa.cn/Article/details/gtpujreuul.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.316326.xyz/Article/details/gtgzubopmg.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.ywan-chungtsiang.top/Article/details/gteyuqhcct.html

TS:   Number() String() Boolean() x as number
来源：http://dali.zycfv.cn/Article/details/gtlyissirg.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.tianlin.xyz/Article/details/gtqhxuwabz.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.hongshengwenyu.top/Article/details/gtvxnqtvtx.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.yangfankeji.com/Article/details/gtbynpelnq.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.yueranfly.top/Article/details/gtjftrylbw.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtonctppgd.html

B. 流程控制
来源：http://dali.yvedp.cn/Article/details/gtealqidtg.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtfdmowuvf.html

[B01] 条件判断 if / else
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtadooszgd.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzqeiykuq.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.pycfn.com/Article/details/gtfkaeppsv.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.xinyue.icu/Article/details/gthqcyqkdz.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.aibaodan.cn/Article/details/gthkiwcuqr.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.pycfn.com/Article/details/gtgalmkmwe.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.sxryk.cn/Article/details/gtthamiwjy.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.xuanzx.com/Article/details/gtrnurcnkv.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.yvedp.cn/Article/details/gtcvwfrlns.html

[B02] 多分支 else if / elif
来源：http://dali.cdnleiting.top/Article/details/gtxvwsnstk.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.zhengqikj.top/Article/details/gtotfyujys.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.xziqi.cn/Article/details/gtcjspuyay.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jqgfzy.top/Article/details/gtxktbazxa.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hnqzz.top/Article/details/gtfhoalczp.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.aizwys.cn/Article/details/gtipsrghpe.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.zhengqikj.top/Article/details/gtgnmojxff.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.zhiwuduotai.top/Article/details/gtbrgfobgi.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.smart0.xyz/Article/details/gtgxvoqogl.html

[B03] switch / match / case
来源：http://dali.nwbrower.top/Article/details/gtqbnwlepz.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.jiagoushi.top/Article/details/gtlmpwulzc.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.hfpthk.cn/Article/details/gtryxwtcpt.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zhoulong.xyz/Article/details/gtvwzsjuvg.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.nanxinkj.top/Article/details/gtlseoqisv.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.cucudq.cn/Article/details/gtgkdngvgt.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.xinyue.icu/Article/details/gtfscybqin.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.jinqigfzy.top/Article/details/gtledqbvsu.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.tanke756.top/Article/details/gtyptffbue.html

[B04] for 计数循环
来源：http://dali.fzhhl.top/Article/details/gtjyfbaliz.html

Py:   for i in range(10): print(i)
来源：http://dali.jinqigfzy.top/Article/details/gtavdraaqi.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.xinyue.icu/Article/details/gtcegbhfqv.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.sweek.top/Article/details/gtrtspczxd.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yj202588.top/Article/details/gtwqealdxa.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.zhixingplan.top/Article/details/gtwnuorsha.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtklbsfajt.html

Ruby: 10.times { |i| puts i }
来源：http://dali.yj20258.top/Article/details/gtytmzqmbr.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.hysaishi.cn/Article/details/gtpnnhwuci.html

[B05] 遍历数组 / 列表
来源：http://dali.kuanghao11.cn/Article/details/gtiiwznxlr.html

Py:   for item in arr: print(item)
来源：http://dali.xinyue.icu/Article/details/gtkalqpaui.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.tianlin.xyz/Article/details/gtwwmyvtsh.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.jyoumei.cn/Article/details/gtxqnkcedj.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.316326.xyz/Article/details/gtssbalaat.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.hongshengwenyu.top/Article/details/gtbrykjfbj.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.zhaomingkeji.xyz/Article/details/gteephaqcb.html

Ruby: arr.each { |item| puts item }
来源：http://dali.redwolf501.top/Article/details/gtcufhtzcz.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.zhijiandao.cn/Article/details/gtblibkduc.html

[B06] 遍历字典 / 对象
来源：http://dali.ivvv.top/Article/details/gtoixlvtyg.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.yangfankeji.com/Article/details/gtmqrdgehx.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.guowangkeji.top/Article/details/gtsclvhwmz.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.hammf.cn/Article/details/gtlasfykcg.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.xinyue.icu/Article/details/gtplbcgiou.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.gzhubu.top/Article/details/gtxciqtywp.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkiamqsfz.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.jinqigfzy.top/Article/details/gtxmhgdxvo.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.cashguo.top/Article/details/gtuvmvdbha.html

[B07] while 循环
来源：http://dali.0kj1m.cn/Article/details/gtobqxvpjo.html

Py:   while i < 10: i += 1
来源：http://dali.yj20258888.top/Article/details/gtbozaqipk.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.dianchejie.cn/Article/details/gtnmbhgclg.html

JS:   while (i < 10) { i++; }
来源：http://dali.sxryk.cn/Article/details/gtblkjhhvr.html

TS:   while (i < 10) { i++; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gttntutdal.html

Java: while (i < 10) { i++; }
来源：http://dali.jinqigufen.top/Article/details/gtkekfewbq.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.hnxiangtu.top/Article/details/gtvvwnjwmd.html

Ruby: while i < 10; i += 1; end
来源：http://dali.ivvv.top/Article/details/gtcitcozqv.html

C#:   while (i < 10) { i++; }
来源：http://dali.yj202588.top/Article/details/gtnidqlcoi.html

[B08] do-while（至少执行一次）
来源：http://dali.feifeiyinyue.top/Article/details/gtifujrllq.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.xylfe.cn/Article/details/gtutovtuzw.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.meibo888.top/Article/details/gtugrsiiqa.html

JS:   do { i++; } while (i < 10);
来源：http://dali.svipenyu.cn/Article/details/gtkzdqzqoj.html

TS:   do { i++; } while (i < 10);
来源：http://dali.tanke756.top/Article/details/gtrtxnycgx.html

Java: do { i++; } while (i < 10);
来源：http://dali.tian-w.cn/Article/details/gtrymviehd.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.tianlin.xyz/Article/details/gtndmpqfmr.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.jlsjyb.cn/Article/details/gtsagqriuk.html

C#:   do { i++; } while (i < 10);
来源：http://dali.wangshuangyany.cn/Article/details/gtjmvweftj.html

[B09] break 与 continue
来源：http://dali.jiagoushi.top/Article/details/gtdxtpitgw.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.vqdsnc.cn/Article/details/gtlvtltbxi.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.jianghu66.top/Article/details/gttucrsgxu.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.quarkkingdee.top/Article/details/gtffbnwysw.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ehwqpu.com/Article/details/gtmpqypvri.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.mhx1999.top/Article/details/gtllviejwc.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.svipenyu.cn/Article/details/gtsidonjak.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.gaohongyu789.top/Article/details/gtvwasxlpf.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinqigufen.top/Article/details/gtkwlcmdli.html

[B10] 遍历同时拿索引
来源：http://dali.smart0.xyz/Article/details/gtufxfevjw.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.snrcjt.cn/Article/details/gtklflarpm.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.hysaishi.cn/Article/details/gtegndadvb.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yonumen.top/Article/details/gtixhlfgqf.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.cdnleiting.top/Article/details/gtbtcsynqy.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.0kj1m.cn/Article/details/gtkyucjonk.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.shzxlz.cn/Article/details/gtcrntmlwe.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.hongshengwenyu.top/Article/details/gtxyggfzau.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.gotoacloud.top/Article/details/gthrqjjadp.html

[B11] 生成数字序列 / 区间
来源：http://dali.fengsongda.top/Article/details/gtwbuwuopg.html

Py:   list(range(0, 10, 2))
来源：http://dali.0kj1m.cn/Article/details/gttvtiqwma.html

PHP:  range(0, 10, 2);
来源：http://dali.daxiang520.top/Article/details/gtujqpekyv.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xylfe.cn/Article/details/gtqlkgsvzr.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gtdzulsvds.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.meibo888.top/Article/details/gtggudhvet.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.xuetiantiany.cn/Article/details/gtybmjeorf.html

Ruby: (0...10).step(2).to_a
来源：http://dali.hnxiangtu.top/Article/details/gtcsdmybat.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.hfpthk.cn/Article/details/gtbvvscdjm.html

[B12] 跳出多层循环
来源：http://dali.meibo888.top/Article/details/gtjtrurdlo.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.dashuyun.cn/Article/details/gtjlfjaope.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.tian-w.cn/Article/details/gtdhbvyqee.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jqgfzy.top/Article/details/gttnoejdbh.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jiagoushi.top/Article/details/gtywinoqml.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.iojbl.cn/Article/details/gtkmlxgfpb.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.andypj.xyz/Article/details/gtcllsawyn.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.xuetiantiany.cn/Article/details/gttjhxsalb.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.sweek.top/Article/details/gtrlowxxos.html

[B13] 判断是否为数字
来源：http://dali.svipenyu.cn/Article/details/gtjlwmyool.html

Py:   isinstance(x, (int, float))
来源：http://dali.shanyushiyangkeji.top/Article/details/gthatsbzzt.html

PHP:  is_numeric($x)
来源：http://dali.feifeiyinyue.top/Article/details/gtjvzwslgc.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xuanzx.com/Article/details/gtnbvnjffh.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.smart0.xyz/Article/details/gtojrwmyju.html

Java: x instanceof Number
来源：http://dali.fzhhl.top/Article/details/gtcjzkwefg.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.yuxming.cn/Article/details/gtbqnhbcme.html

Ruby: x.is_a?(Numeric)
来源：http://dali.316326.xyz/Article/details/gtotpfeffp.html

C#:   x is int or double or decimal
来源：http://dali.hnqzz.top/Article/details/gtphbcoard.html

[B14] 判断值是否在集合内
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrcoebmwp.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.jlsjyb.cn/Article/details/gtxexyealt.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.redwolf501.top/Article/details/gtubrssggo.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.cqqwz.cn/Article/details/gtizimsebd.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtpmyucfqu.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.wangdashe.top/Article/details/gtttuzuxkk.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.shuidangran.top/Article/details/gttuisoptb.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.svipenyu.cn/Article/details/gtqhsyioll.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.nanxinkj.top/Article/details/gteyqnxazs.html

[B15] 布尔运算与取反
来源：http://dali.dianchejie.cn/Article/details/gtrfzgtasr.html

Py:   a and b or not c
来源：http://dali.chenzaomai.com/Article/details/gtteypoztn.html

PHP:  $a && $b || !$c
来源：http://dali.jinqigufen.top/Article/details/gtzwxbiffg.html

JS:   a && b || !c
来源：http://dali.aizwys.cn/Article/details/gtoyoojaqq.html

TS:   a && b || !c
来源：http://dali.zdqjudy.top/Article/details/gtgejtydto.html

Java: a && b || !c
来源：http://dali.shangyingyoupin.top/Article/details/gtbvvkqyge.html

Go:   a && b || !c
来源：http://dali.316326.xyz/Article/details/gthxcaxjnp.html

Ruby: a && b || !c
来源：http://dali.hywenlv.cn/Article/details/gtsggjrnfm.html

C#:   a && b || !c
来源：http://dali.hongshengwenyu.top/Article/details/gtxndhwdfo.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjqwphdec.html

Py:   if not data: return
来源：http://dali.zhiwuduotai.top/Article/details/gtpubimzrq.html

PHP:  if (!$data) { return; }
来源：http://dali.hammf.cn/Article/details/gtetgwvqak.html

JS:   if (!data) return;
来源：http://dali.fengsongda.top/Article/details/gtchrmuzua.html

TS:   if (!data) return;
来源：http://dali.jianghu66.top/Article/details/gtdlmfcyrn.html

Java: if (data == null) return;
来源：http://dali.snrcjt.cn/Article/details/gtarqdmjky.html

Go:   if data == nil { return }
来源：http://dali.yongpay.top/Article/details/gtxucdnkae.html

Ruby: return if data.nil?
来源：http://dali.xuetiantiany.cn/Article/details/gtxaseyxbb.html

C#:   if (data == null) return;
来源：http://dali.fengsongda.top/Article/details/gttcsaknlx.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gthdzxdbxi.html

C. 函数与作用域
来源：http://dali.wangshuangyany.cn/Article/details/gtcrupgrqg.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtdqvapkek.html

[C01] 定义函数
来源：http://dali.cheryme.top/Article/details/gtmtwvltcl.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gtaepivrls.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gotoacloud.top/Article/details/gttosykwjq.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.cucudq.cn/Article/details/gtiskicxhr.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.quarkkingdee.top/Article/details/gtzeicsbev.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yangfankeji.com/Article/details/gtusxsnhhf.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.sweek.top/Article/details/gtmflejqxb.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhoulong.xyz/Article/details/gtmivwdvqe.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtuvdyovnt.html

[C02] 默认参数
来源：http://dali.yuanzhike.top/Article/details/gtsjkjniic.html

Py:   def greet(name="World"): return name
来源：http://dali.cucudq.cn/Article/details/gtynyprqbo.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtobljqsng.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.tianlin.xyz/Article/details/gtsihdkhhj.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.hammf.cn/Article/details/gtbcxjceud.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.fengsongda.top/Article/details/gtkiwivlkn.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.svipenyu.cn/Article/details/gtsvkwlrqi.html

Ruby: def greet(name = "World") = name
来源：http://dali.hongshengwenyu.top/Article/details/gtweolahlq.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jqgfzy.top/Article/details/gthfaxqdji.html

[C03] 可变参数
来源：http://dali.hfpthk.cn/Article/details/gtvwsxebaw.html

Py:   def total(*args): return sum(args)
来源：http://dali.yangfankeji.com/Article/details/gtbrtqzjzu.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.tian-w.cn/Article/details/gtlekwcyok.html


<!-- 参考信息 -->