代发 wailian999

Java: "第一行\n第二行"
来源：http://dali.pycfn.com/Article/details/gtjnsdttbf.html

Go:   "第一行\n第二行"
来源：http://dali.sxryk.cn/Article/details/gtijujnxuo.html

Ruby: "第一行\n第二行"
来源：http://dali.fengsongda.top/Article/details/gtiqbnrbwc.html

C#:   "第一行\n第二行"
来源：http://dali.meibo888.top/Article/details/gtbuzfldgj.html

[A14] 注释写法
来源：http://dali.9152youxi.cn/Article/details/gtvcjltgue.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.hfpthk.cn/Article/details/gtcdpirfha.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.guowangkeji.top/Article/details/gtoacdvhlt.html

JS:   // 单行；/* 多行 */
来源：http://dali.gzhubu.top/Article/details/gtlhuffddj.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhongyouzk.top/Article/details/gtpnkhysfv.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.ybcxt.top/Article/details/gtxzfwdjnu.html

Go:   // 单行；/* 多行 */
来源：http://dali.daria6918.cn/Article/details/gtopxmflue.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.cdnleiting.top/Article/details/gtawjyupfp.html

C#:   // 单行；/* 多行 */
来源：http://dali.wangshuangyany.cn/Article/details/gtjmrqhdcu.html

[A15] 空值判断与默认值
来源：http://dali.0kj1m.cn/Article/details/gtwiecrfmz.html

Py:   value = data or "默认值"
来源：http://dali.nanxinkj.top/Article/details/gtfeuiftyd.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.c1oappe.top/Article/details/gtqqtocexe.html

JS:   const value = data ?? "默认值";
来源：http://dali.0kj1m.cn/Article/details/gtwxfolusj.html

TS:   const value = data ?? "默认值";
来源：http://dali.jinqigfzy.top/Article/details/gtyzxrkvhv.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.cashguo.top/Article/details/gtubkoflpx.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.shuidangran.top/Article/details/gthqrjdguz.html

Ruby: value = data || "默认值"
来源：http://dali.xuetiantiany.cn/Article/details/gtawvscpnw.html

C#:   var value = data ?? "默认值";
来源：http://dali.guannengcc.top/Article/details/gthnvjewtr.html

[A16] 真假值判断规则
来源：http://dali.zycfv.cn/Article/details/gtmwvqwsdn.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.aizwys.cn/Article/details/gtcpzwaajw.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.yongpay.top/Article/details/gtnbygkjtk.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtapmpmcel.html

TS:   if (!x) {}
来源：http://dali.yonumen.top/Article/details/gtveaxrjov.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.guowangkeji.top/Article/details/gtzvhmslug.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.pycfn.com/Article/details/gtvwwibbev.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.wangshuangyany.cn/Article/details/gtglxoztgi.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.guannengcc.top/Article/details/gtuwphelib.html

[A17] 位运算
来源：http://dali.yj202588.top/Article/details/gtweauwjvw.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.gzhubu.top/Article/details/gtlskhdkhx.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.hywenlv.cn/Article/details/gtnxcxsadu.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jqgufenzy.top/Article/details/gtuzafdrax.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.hnxiangtu.top/Article/details/gtdpjrlqtq.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yuxming.cn/Article/details/gtwarvbchh.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.jqgufenzy.top/Article/details/gtdoxlgxsj.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xuetiantiany.cn/Article/details/gtarjcyduw.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.nanxinkj.top/Article/details/gtgrdxbwlc.html

[A18] 字符与 ASCII 码互转
来源：http://dali.nanxuanxn.top/Article/details/gtmfzestmq.html

Py:   ord("A"); chr(65)
来源：http://dali.dianchejie.cn/Article/details/gtdgzcwibw.html

PHP:  ord("A"); chr(65)
来源：http://dali.cheryme.top/Article/details/gtnanyfeyy.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.yj20258.top/Article/details/gteysxlria.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.ivvv.top/Article/details/gtdbfjjdoj.html

Java: (int) 'A'; (char) 65
来源：http://dali.ehwqpu.com/Article/details/gtbtdegcfn.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.cashguo.top/Article/details/gtbzqqnjlx.html

Ruby: "A".ord; 65.chr
来源：http://dali.jiagoushi.top/Article/details/gtladhoilk.html

C#:   (int)'A'; (char)65
来源：http://dali.pengpengdd.cyou/Article/details/gthjxxzgou.html

[A19] 交换两个变量
来源：http://dali.tanke756.top/Article/details/gtcshnqjdd.html

Py:   a, b = b, a
来源：http://dali.gzhubu.top/Article/details/gtbcihkbpp.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.iojbl.cn/Article/details/gtmcxvquqy.html

JS:   [a, b] = [b, a];
来源：http://dali.yj20258888.top/Article/details/gtmkmghzga.html

TS:   [a, b] = [b, a];
来源：http://dali.wangdashe.top/Article/details/gtkcmryylk.html

Java: int t = a; a = b; b = t;
来源：http://dali.hammf.cn/Article/details/gtgytzbqrs.html

Go:   a, b = b, a
来源：http://dali.chenjidiqi.icu/Article/details/gtrnukrjkx.html

Ruby: a, b = b, a
来源：http://dali.meibo888.top/Article/details/gttzrciijs.html

C#:   (a, b) = (b, a);
来源：http://dali.hongshengwenyu.top/Article/details/gteqerpbgz.html

[A20] 读取标准输入
来源：http://dali.iojbl.cn/Article/details/gtkaonbvio.html

Py:   name = input("请输入：")
来源：http://dali.mhx1999.top/Article/details/gtrcetntsw.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.jyoumei.cn/Article/details/gtdtdtwliy.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.zhengqikj.top/Article/details/gteiqaeuao.html

TS:   // Node.js：readline 模块
来源：http://dali.zdqjudy.top/Article/details/gtqdnllcta.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.tanke756.top/Article/details/gttqjehgun.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.haohaochexian.top/Article/details/gteaqzfuvu.html

Ruby: gets.chomp
来源：http://dali.wangdashe.top/Article/details/gthxklsyfw.html

C#:   Console.ReadLine();
来源：http://dali.shuidangran.top/Article/details/gtfadicwsz.html

[A21] 保留指定小数位输出
来源：http://dali.guowangkeji.top/Article/details/gtzhlnzmzd.html

Py:   f"{3.14159:.2f}"
来源：http://dali.sweek.top/Article/details/gteknvkpmr.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.zhijiandao.cn/Article/details/gtlqrqenqk.html

JS:   (3.14159).toFixed(2)
来源：http://dali.0kj1m.cn/Article/details/gtyupxaedt.html

TS:   (3.14159).toFixed(2)
来源：http://dali.daxiang520.top/Article/details/gttgmdisbb.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.daxiang520.top/Article/details/gtuigocvia.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.xinyue.icu/Article/details/gtidirbfzb.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.jyoumei.cn/Article/details/gtfxukmwfk.html

C#:   3.14159.ToString("F2")
来源：http://dali.birdmap.top/Article/details/gtyawxeaws.html

[A22] 获取字符串长度
来源：http://dali.yongpay.top/Article/details/gtxuxgzoax.html

Py:   len(s)
来源：http://dali.c1oappe.top/Article/details/gtmueofmfp.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.xinyue.icu/Article/details/gtyxsbhbyg.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.cdnleiting.top/Article/details/gtoenzgirq.html

TS:   s.length
来源：http://dali.xuetiantiany.cn/Article/details/gtijgibhcc.html

Java: s.length()
来源：http://dali.shzxlz.cn/Article/details/gtrdhshpib.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtkxhfglss.html

Ruby: s.length
来源：http://dali.wangshuangyany.cn/Article/details/gtxbboguly.html

C#:   s.Length
来源：http://dali.cqqwz.cn/Article/details/gtkfovbxvl.html

[A23] 大小写转换
来源：http://dali.zhoulong.xyz/Article/details/gtplvzpzvr.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.jlsjyb.cn/Article/details/gtrubwmvop.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.yonumen.top/Article/details/gtcbwkshtg.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.xuanzx.com/Article/details/gtkrijkvfo.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.cqqwz.cn/Article/details/gtiydgjfnz.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.gaohongyu789.top/Article/details/gtgvpdiwhe.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.guowangkeji.top/Article/details/gtgwaarvfo.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.nwbrower.top/Article/details/gtttgmmoeg.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.nanxinkj.top/Article/details/gtxjqiyfih.html

[A24] 去除首尾空白
来源：http://dali.gzhubu.top/Article/details/gteolgsxtn.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.xuetiantiany.cn/Article/details/gtjrevzvyh.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.jyoumei.cn/Article/details/gtlujavagt.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.shzxlz.cn/Article/details/gtcrzvydgj.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.svipenyu.cn/Article/details/gtbxopfydd.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.zhongyouzk.top/Article/details/gtipuprbsr.html

Go:   strings.TrimSpace(s)
来源：http://dali.yuanzhike.top/Article/details/gtwfmufrur.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.tianlin.xyz/Article/details/gtotgomqwh.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.zhoulong.xyz/Article/details/gtcbalqfke.html

[A25] 字符串比较
来源：http://dali.9152youxi.cn/Article/details/gtjanlkbxb.html

Py:   s1 == s2; s1 != s2
来源：http://dali.feifeiyinyue.top/Article/details/gtnwgjuevw.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.ehwqpu.com/Article/details/gturgqgghl.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zhixingplan.top/Article/details/gtpvitwbzq.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtarqgygtv.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.zycfv.cn/Article/details/gtrbielmva.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.jianghu66.top/Article/details/gtnohcaoch.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.tian-w.cn/Article/details/gtasdwfpln.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.cashguo.top/Article/details/gtmviealpx.html

[A26] 类型转换总览
来源：http://dali.daria6918.cn/Article/details/gtpfefltnc.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.yongpay.top/Article/details/gtfmdxvkjy.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.zhongyouzk.top/Article/details/gtrdnisqds.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.daxiang520.top/Article/details/gtpwxjmuym.html

TS:   Number() String() Boolean() x as number
来源：http://dali.havefunace.top/Article/details/gtlsrcuekp.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.daxiang520.top/Article/details/gtjvzovbjy.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.cashguo.top/Article/details/gtvkvcnqrk.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.shangyingyoupin.top/Article/details/gtdrdpdzdy.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.daxiang520.top/Article/details/gtxlnrnmlq.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtuxjuaigj.html

B. 流程控制
来源：http://dali.andypj.xyz/Article/details/gtkkbhzlcf.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtkxkldxqb.html

[B01] 条件判断 if / else
来源：http://dali.xuetiantiany.cn/Article/details/gtqkfpgrrk.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.meibo888.top/Article/details/gtojpulwkz.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.pycfn.com/Article/details/gtajjimfzb.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jiagoushi.top/Article/details/gtcznnfrpq.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.cqqwz.cn/Article/details/gtkoxmcmte.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.zhengqikj.top/Article/details/gtkovajpeo.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.birdmap.top/Article/details/gtytelszkd.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.nwbrower.top/Article/details/gtvqxcbdho.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.yangfankeji.com/Article/details/gtyqzedzvu.html

[B02] 多分支 else if / elif
来源：http://dali.hywenlv.cn/Article/details/gtmoccqccm.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.hysaishi.cn/Article/details/gtlmrxpbwg.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.pycfn.com/Article/details/gtbxsdszvp.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shanyushiyangtech.top/Article/details/gtfivyoyuu.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.daria6918.cn/Article/details/gtnrcgpvvd.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.sufxvd.cn/Article/details/gtosoaxyqx.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.xinyue.icu/Article/details/gtbcdtvssp.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.9152youxi.cn/Article/details/gtmeokvfzg.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zdqjudy.top/Article/details/gtmkxjednn.html

[B03] switch / match / case
来源：http://dali.xziqi.cn/Article/details/gtdvobpfhq.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.jianghu66.top/Article/details/gthnpbwakz.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.gotoacloud.top/Article/details/gtejatuqoa.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.hysaishi.cn/Article/details/gttaqmhhxd.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.gaohongyu789.top/Article/details/gtrhlwydzt.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.dianchejie.cn/Article/details/gtbxcuscww.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.9152youxi.cn/Article/details/gtodetygoq.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.aibaodan.cn/Article/details/gtycmoafbv.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.haohaochexian.top/Article/details/gtxsklsvuk.html

[B04] for 计数循环
来源：http://dali.yonumen.top/Article/details/gtqarzhxuf.html

Py:   for i in range(10): print(i)
来源：http://dali.zhijiandao.cn/Article/details/gtbiucwwjd.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.ydzc1.top/Article/details/gtkgpyttxa.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.hongshengwenyu.top/Article/details/gtkmdxjrxm.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.pengpengdd.cyou/Article/details/gtosqgpqzq.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.cheryme.top/Article/details/gthtinbhzm.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.hysaishi.cn/Article/details/gtghxzsroo.html

Ruby: 10.times { |i| puts i }
来源：http://dali.wangshuangyany.cn/Article/details/gtdabgsucg.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.sxryk.cn/Article/details/gtvbztgrvk.html

[B05] 遍历数组 / 列表
来源：http://dali.chenjidiqi.icu/Article/details/gtxttxqfnh.html

Py:   for item in arr: print(item)
来源：http://dali.hnqzz.top/Article/details/gtfjcxooas.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.xylfe.cn/Article/details/gtkranodiq.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.jianghu66.top/Article/details/gthvpfozmu.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.ydzc1.top/Article/details/gtkvolqqay.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.ivvv.top/Article/details/gtairqftsr.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.hfpthk.cn/Article/details/gtsmoprgub.html

Ruby: arr.each { |item| puts item }
来源：http://dali.ybcxt.top/Article/details/gtidlrubwx.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.wangdashe.top/Article/details/gthusbctpw.html

[B06] 遍历字典 / 对象
来源：http://dali.fzhhl.top/Article/details/gtcdkvwpqv.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.fzhhl.top/Article/details/gtlcepudyl.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.cdnleiting.top/Article/details/gteojvopnx.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhixingplan.top/Article/details/gtkymufehb.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.sufxvd.cn/Article/details/gtanyiyuzg.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.tian-w.cn/Article/details/gtdzjgjooq.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.yongpay.top/Article/details/gtrytfrtsa.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.nwbrower.top/Article/details/gtibdtwqli.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtevckbbyf.html

[B07] while 循环
来源：http://dali.hammf.cn/Article/details/gtxyqbuqzu.html

Py:   while i < 10: i += 1
来源：http://dali.yongpay.top/Article/details/gtpgndlwqd.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.zhongyouzk.top/Article/details/gtxhczgacq.html

JS:   while (i < 10) { i++; }
来源：http://dali.bjfxy.top/Article/details/gtoiqigxwr.html

TS:   while (i < 10) { i++; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfdilsszm.html

Java: while (i < 10) { i++; }
来源：http://dali.ivvv.top/Article/details/gtcmzgaafi.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.birdmap.top/Article/details/gtkecmtfan.html

Ruby: while i < 10; i += 1; end
来源：http://dali.yuxming.cn/Article/details/gtdldwrors.html

C#:   while (i < 10) { i++; }
来源：http://dali.cheryme.top/Article/details/gtbwjeqraj.html

[B08] do-while（至少执行一次）
来源：http://dali.shanyushiyangtech.top/Article/details/gtcopoivmy.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.cqqwz.cn/Article/details/gtdgrbgzxn.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jianghu66.top/Article/details/gtdigfmbhz.html

JS:   do { i++; } while (i < 10);
来源：http://dali.yuanzhike.top/Article/details/gtchwsbies.html

TS:   do { i++; } while (i < 10);
来源：http://dali.nanxinkj.top/Article/details/gtgkeywjib.html

Java: do { i++; } while (i < 10);
来源：http://dali.guowangkeji.top/Article/details/gticiuhwep.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.yuxming.cn/Article/details/gtjmcsxxdd.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.yj20258.top/Article/details/gtknthospe.html

C#:   do { i++; } while (i < 10);
来源：http://dali.ybcxt.top/Article/details/gtekrcorjs.html

[B09] break 与 continue
来源：http://dali.0kj1m.cn/Article/details/gtrdleetpg.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.zycfv.cn/Article/details/gtnyqarvlt.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.daria6918.cn/Article/details/gtusufetqq.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.wangshuangyany.cn/Article/details/gtlsdwiapc.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hnqzz.top/Article/details/gtkkbhyutu.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cqqwz.cn/Article/details/gtfxwwazof.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.yj202588.top/Article/details/gtbkycldmo.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.chenjidiqi.icu/Article/details/gtcfdlpkpa.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.guannengcc.top/Article/details/gtrbijwdgs.html

[B10] 遍历同时拿索引
来源：http://dali.quarkkingdee.top/Article/details/gtlckrfvof.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.yangfankeji.com/Article/details/gtbswqxnqq.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.cashguo.top/Article/details/gtphvjqjsh.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.hnqzz.top/Article/details/gtwkqpmyqf.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.wangdashe.top/Article/details/gttwzsdghh.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.fzhhl.top/Article/details/gtrezkface.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.daxiang520.top/Article/details/gtdoknkyag.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.feifeiyinyue.top/Article/details/gtxxqpgpiq.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.jyoumei.cn/Article/details/gtutuxbkzq.html

[B11] 生成数字序列 / 区间
来源：http://dali.cdnleiting.top/Article/details/gtblpqzwnp.html

Py:   list(range(0, 10, 2))
来源：http://dali.316326.xyz/Article/details/gtnxzhnlwc.html

PHP:  range(0, 10, 2);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvkwbrefv.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yj20258.top/Article/details/gtwqwtnfkb.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gtgdpkpmxn.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.sufxvd.cn/Article/details/gtnnzgebmx.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhixingplan.top/Article/details/gtrojakyyz.html

Ruby: (0...10).step(2).to_a
来源：http://dali.xuanzx.com/Article/details/gthzalujzt.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.sysykeji.top/Article/details/gtucbizyrh.html

[B12] 跳出多层循环
来源：http://dali.cheryme.top/Article/details/gtlaqmorsz.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.havefunace.top/Article/details/gtklktoqzp.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.yangfankeji.com/Article/details/gthtxlhofr.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjabefpvh.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.nanxuanxn.top/Article/details/gtgecusplz.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.dashuyun.cn/Article/details/gtuetwhmso.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.hongshengwenyu.top/Article/details/gtjrqvwhug.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhoulong.xyz/Article/details/gtuttoqjpp.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.yj20258.top/Article/details/gtagvosdbt.html

[B13] 判断是否为数字
来源：http://dali.hammf.cn/Article/details/gttcytyefr.html

Py:   isinstance(x, (int, float))
来源：http://dali.ehwqpu.com/Article/details/gtpnnmtiuu.html

PHP:  is_numeric($x)
来源：http://dali.mhx1999.top/Article/details/gtuuzaowhe.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.svipenyu.cn/Article/details/gtlyadwfxr.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.haohaochexian.top/Article/details/gtvaelqkxo.html

Java: x instanceof Number
来源：http://dali.fzhhl.top/Article/details/gteiadfpen.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.gogol.net.cn/Article/details/gthnfxozra.html

Ruby: x.is_a?(Numeric)
来源：http://dali.gzhubu.top/Article/details/gtbggirtrg.html

C#:   x is int or double or decimal
来源：http://dali.jqgfzy.top/Article/details/gttgtgyrgz.html

[B14] 判断值是否在集合内
来源：http://dali.yonumen.top/Article/details/gtgrfzgdev.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.guannengcc.top/Article/details/gtvdgkjkpn.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.cdnleiting.top/Article/details/gtlqoxkzba.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.guannengcc.top/Article/details/gtwruohgxn.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.wangshuangyany.cn/Article/details/gtksbvcebw.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.cheryme.top/Article/details/gtidwtzwqr.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.kuanghao11.cn/Article/details/gtickfjcmp.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jinqigfzy.top/Article/details/gthjzqzyzj.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.daxiang520.top/Article/details/gtbphlqgaq.html

[B15] 布尔运算与取反
来源：http://dali.c1oappe.top/Article/details/gtrsdiuoxt.html

Py:   a and b or not c
来源：http://dali.dashuyun.cn/Article/details/gtfwrahltl.html

PHP:  $a && $b || !$c
来源：http://dali.ppjwa.cn/Article/details/gtkxqpfubb.html

JS:   a && b || !c
来源：http://dali.cheryme.top/Article/details/gtehirfvnl.html

TS:   a && b || !c
来源：http://dali.mhx1999.top/Article/details/gtbfabcsxz.html

Java: a && b || !c
来源：http://dali.ivvv.top/Article/details/gthffyhhrg.html

Go:   a && b || !c
来源：http://dali.dianchejie.cn/Article/details/gtpxqcfrev.html

Ruby: a && b || !c
来源：http://dali.jinghuilouyu.cn/Article/details/gtwiofxlck.html

C#:   a && b || !c
来源：http://dali.quarkkingdee.top/Article/details/gtmehbbxlp.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.aibaodan.cn/Article/details/gtjvbqsvxc.html

Py:   if not data: return
来源：http://dali.vqdsnc.cn/Article/details/gtfrctjjlu.html

PHP:  if (!$data) { return; }
来源：http://dali.kuanghao11.cn/Article/details/gtpqccysaf.html

JS:   if (!data) return;
来源：http://dali.aibaodan.cn/Article/details/gtenxkstwu.html

TS:   if (!data) return;
来源：http://dali.jianghu66.top/Article/details/gtzigjtmna.html

Java: if (data == null) return;
来源：http://dali.yanxiufei.cn/Article/details/gtcadotzzu.html

Go:   if data == nil { return }
来源：http://dali.yonumen.top/Article/details/gtjdfioazq.html

Ruby: return if data.nil?
来源：http://dali.cheryme.top/Article/details/gtqomnroii.html

C#:   if (data == null) return;
来源：http://dali.gotoacloud.top/Article/details/gtowzjnmkr.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtwfyrvzmu.html

C. 函数与作用域
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwjnnrxiv.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtnvoxqayg.html

[C01] 定义函数
来源：http://dali.cashguo.top/Article/details/gtjicuydml.html

Py:   def add(a, b): return a + b
来源：http://dali.jinqigfzy.top/Article/details/gtzqlxkxtf.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gthpmtxtuc.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.shzxlz.cn/Article/details/gtmfcxoruz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.quarkkingdee.top/Article/details/gttnstatfl.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.hnxiangtu.top/Article/details/gtlgxujlaq.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zycfv.cn/Article/details/gttmsuohei.html

Ruby: def add(a, b); a + b; end
来源：http://dali.cucudq.cn/Article/details/gturrppwoa.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.cashguo.top/Article/details/gtxobkmisw.html

[C02] 默认参数
来源：http://dali.smart0.xyz/Article/details/gtesqemvac.html

Py:   def greet(name="World"): return name
来源：http://dali.xuanzx.com/Article/details/gtttjaykzw.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.andypj.xyz/Article/details/gtloehdqxf.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.havefunace.top/Article/details/gtlzstqbsu.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.hnxiangtu.top/Article/details/gtppoueyvx.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttrwullue.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jqgufenzy.top/Article/details/gtfsnmukoo.html

Ruby: def greet(name = "World") = name
来源：http://dali.chenlongwang.top/Article/details/gtfsrmcldy.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.snrcjt.cn/Article/details/gtzsablnzh.html

[C03] 可变参数
来源：http://dali.guowangkeji.top/Article/details/gtdlztxgsd.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhongyouzk.top/Article/details/gthrhhrprc.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yonumen.top/Article/details/gtpuhpelxd.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.redwolf501.top/Article/details/gtwbnnqgih.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.sweek.top/Article/details/gtydbmwdli.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.daxiang520.top/Article/details/gtlorjwjvr.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.dianchejie.cn/Article/details/gtrntjstkp.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.cdnleiting.top/Article/details/gtyklnyzcw.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jyoumei.cn/Article/details/gtaghhuxew.html

[C04] 命名参数 / 关键字参数
来源：http://dali.guannengcc.top/Article/details/gtjbbvhftz.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.redwolf501.top/Article/details/gtetdnvctm.html


<!-- 参考信息 -->