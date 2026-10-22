代发 wailian999

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.cashguo.top/Article/details/gtjwnujayi.html

JS:   `Hello, ${name}!`
来源：http://dali.cqqwz.cn/Article/details/gtrzkodsyz.html

TS:   `Hello, ${name}!`
来源：http://dali.gotoacloud.top/Article/details/gtfmdgqaxv.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.yueranfly.top/Article/details/gtrzdbhvfu.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.tian-w.cn/Article/details/gtgsukygkp.html

Ruby: "Hello, #{name}!"
来源：http://dali.kuanghao11.cn/Article/details/gtkwdgghsn.html

C#:   $"Hello, {name}!"
来源：http://dali.cheryme.top/Article/details/gtzamvntuu.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.sxryk.cn/Article/details/gtpcorzktr.html

Py:   "第一行\n第二行"
来源：http://dali.dianchejie.cn/Article/details/gtawfuwohw.html

PHP:  "第一行\n第二行"
来源：http://dali.xuetiantiany.cn/Article/details/gtokekezdk.html

JS:   "第一行\n第二行"
来源：http://dali.jinqigfzy.top/Article/details/gtcbfwntej.html

TS:   "第一行\n第二行"
来源：http://dali.redwolf501.top/Article/details/gtnzjfzezp.html

Java: "第一行\n第二行"
来源：http://dali.yj20258.top/Article/details/gtwdfihclr.html

Go:   "第一行\n第二行"
来源：http://dali.chenjidiqi.icu/Article/details/gtgzuiibwh.html

Ruby: "第一行\n第二行"
来源：http://dali.hammf.cn/Article/details/gtrxoinjzh.html

C#:   "第一行\n第二行"
来源：http://dali.dashuyun.cn/Article/details/gtgmmmpnck.html

[A14] 注释写法
来源：http://dali.cheryme.top/Article/details/gtbykigyro.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.yj202588.top/Article/details/gtodpmputt.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.jiagoushi.top/Article/details/gtdzxinwjr.html

JS:   // 单行；/* 多行 */
来源：http://dali.iojbl.cn/Article/details/gttiqcubpi.html

TS:   // 单行；/* 多行 */
来源：http://dali.aibaodan.cn/Article/details/gtzhbkidsz.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.aibaodan.cn/Article/details/gtbrgobiex.html

Go:   // 单行；/* 多行 */
来源：http://dali.cdnleiting.top/Article/details/gtzahkhhgk.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.smart0.xyz/Article/details/gtgqrnvdxc.html

C#:   // 单行；/* 多行 */
来源：http://dali.guannengcc.top/Article/details/gtbchqldbo.html

[A15] 空值判断与默认值
来源：http://dali.smart0.xyz/Article/details/gtakkxjhfd.html

Py:   value = data or "默认值"
来源：http://dali.jiagoushi.top/Article/details/gtdetjgjjm.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.sysykeji.top/Article/details/gtzpfmylou.html

JS:   const value = data ?? "默认值";
来源：http://dali.fzhhl.top/Article/details/gthizhyxak.html

TS:   const value = data ?? "默认值";
来源：http://dali.ivvv.top/Article/details/gtaikqoyjf.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.jinqigfzy.top/Article/details/gtvtzwdiog.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhengqikj.top/Article/details/gtygkiehyx.html

Ruby: value = data || "默认值"
来源：http://dali.jinqigfzy.top/Article/details/gtdbxkoafn.html

C#:   var value = data ?? "默认值";
来源：http://dali.birdmap.top/Article/details/gtgaxtgzbo.html

[A16] 真假值判断规则
来源：http://dali.tian-w.cn/Article/details/gtqwxjvqyv.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.jyoumei.cn/Article/details/gtpympnyjg.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.gzhubu.top/Article/details/gtrcbuybjm.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.hysaishi.cn/Article/details/gtatvgnrew.html

TS:   if (!x) {}
来源：http://dali.zhixingplan.top/Article/details/gtqxlrazgo.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.fengsongda.top/Article/details/gtcajyymap.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.zhiwuduotai.top/Article/details/gttawueuwz.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.jyoumei.cn/Article/details/gtdpnjzoqh.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.daxiang520.top/Article/details/gtfhakmqjc.html

[A17] 位运算
来源：http://dali.snrcjt.cn/Article/details/gtrhjlxojt.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhixingplan.top/Article/details/gtrgrukiru.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.zycfv.cn/Article/details/gtptbsnhar.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.wangdashe.top/Article/details/gtelqgcsvb.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.xinyue.icu/Article/details/gtzyntrtmu.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.gogol.net.cn/Article/details/gtyudqkvtd.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.redwolf501.top/Article/details/gtjycmhvru.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.aibaodan.cn/Article/details/gtsdabiwyu.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.iojbl.cn/Article/details/gtbjrcqiqd.html

[A18] 字符与 ASCII 码互转
来源：http://dali.iojbl.cn/Article/details/gtqggghxke.html

Py:   ord("A"); chr(65)
来源：http://dali.yuxming.cn/Article/details/gtbtznkhpw.html

PHP:  ord("A"); chr(65)
来源：http://dali.ybcxt.top/Article/details/gttueajmvu.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zhiwuduotai.top/Article/details/gthkaieruz.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.fzhhl.top/Article/details/gtawiogxiv.html

Java: (int) 'A'; (char) 65
来源：http://dali.sufxvd.cn/Article/details/gthxykowkp.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.yuanzhike.top/Article/details/gtjqelcvrr.html

Ruby: "A".ord; 65.chr
来源：http://dali.cucudq.cn/Article/details/gtkvlnyfbj.html

C#:   (int)'A'; (char)65
来源：http://dali.yongpay.top/Article/details/gttojftlmk.html

[A19] 交换两个变量
来源：http://dali.havefunace.top/Article/details/gtwmxxclng.html

Py:   a, b = b, a
来源：http://dali.xuetiantiany.cn/Article/details/gtelirxvnh.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.yuanzhike.top/Article/details/gtcxdfhdzy.html

JS:   [a, b] = [b, a];
来源：http://dali.yongpay.top/Article/details/gtyxxhnfau.html

TS:   [a, b] = [b, a];
来源：http://dali.yj202588.top/Article/details/gtincawhsb.html

Java: int t = a; a = b; b = t;
来源：http://dali.ivvv.top/Article/details/gtutwmydez.html

Go:   a, b = b, a
来源：http://dali.daxiang520.top/Article/details/gtqdapyeuh.html

Ruby: a, b = b, a
来源：http://dali.nanxuanxn.top/Article/details/gtpbuvccmb.html

C#:   (a, b) = (b, a);
来源：http://dali.hywenlv.cn/Article/details/gtoqjoehjd.html

[A20] 读取标准输入
来源：http://dali.yj20258.top/Article/details/gtrlsxwqqk.html

Py:   name = input("请输入：")
来源：http://dali.bjfxy.top/Article/details/gtwkeluecz.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.snrcjt.cn/Article/details/gtvsjuuzpy.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.yanxiufei.cn/Article/details/gtbaqmmbak.html

TS:   // Node.js：readline 模块
来源：http://dali.jqgfzy.top/Article/details/gtgnefssys.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.wangdashe.top/Article/details/gthgcwutep.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwlqgttfz.html

Ruby: gets.chomp
来源：http://dali.chenlongwang.top/Article/details/gtlpdfawpk.html

C#:   Console.ReadLine();
来源：http://dali.tian-w.cn/Article/details/gtqzwrveer.html

[A21] 保留指定小数位输出
来源：http://dali.tianlin.xyz/Article/details/gtaoiqtabw.html

Py:   f"{3.14159:.2f}"
来源：http://dali.chenlongwang.top/Article/details/gtzegodhlw.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.yj20258.top/Article/details/gtocnmsryk.html

JS:   (3.14159).toFixed(2)
来源：http://dali.xuetiantiany.cn/Article/details/gtibrzdipi.html

TS:   (3.14159).toFixed(2)
来源：http://dali.chenlongwang.top/Article/details/gtkwxzhvji.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.xziqi.cn/Article/details/gthejnkdhh.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.shangyingyoupin.top/Article/details/gtklqaznox.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.guannengcc.top/Article/details/gtphbhaetv.html

C#:   3.14159.ToString("F2")
来源：http://dali.jinqigufen.top/Article/details/gtbznzzlvo.html

[A22] 获取字符串长度
来源：http://dali.xziqi.cn/Article/details/gtmsldnbbi.html

Py:   len(s)
来源：http://dali.dianchejie.cn/Article/details/gtbpvezijd.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.dashuyun.cn/Article/details/gtnnhgdert.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.yuxming.cn/Article/details/gtbxpjyliq.html

TS:   s.length
来源：http://dali.kuanghao11.cn/Article/details/gtfyvfbxug.html

Java: s.length()
来源：http://dali.jinqigufen.top/Article/details/gtbovpllov.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.9152youxi.cn/Article/details/gtwwfuzffm.html

Ruby: s.length
来源：http://dali.xziqi.cn/Article/details/gttxllbrkk.html

C#:   s.Length
来源：http://dali.xinyue.icu/Article/details/gtlparclnt.html

[A23] 大小写转换
来源：http://dali.wangdashe.top/Article/details/gtztpwyrps.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.hysaishi.cn/Article/details/gtiwezzzpv.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.tian-w.cn/Article/details/gtofnfcabl.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.jyoumei.cn/Article/details/gtaxmjelho.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhengqikj.top/Article/details/gtopsfdnpd.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.cashguo.top/Article/details/gtmhlhzjds.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.yuanzhike.top/Article/details/gtpjcksuzl.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.yj20258888.top/Article/details/gtdgedoffh.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.birdmap.top/Article/details/gtqcycrshv.html

[A24] 去除首尾空白
来源：http://dali.jqgufenzy.top/Article/details/gtfutwfnal.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtccvpadvj.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.zdqjudy.top/Article/details/gthnpmorbu.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.hywenlv.cn/Article/details/gtpttkmvgx.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.smart0.xyz/Article/details/gtjfkiaqdm.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.jiagoushi.top/Article/details/gtboaywbdu.html

Go:   strings.TrimSpace(s)
来源：http://dali.meibo888.top/Article/details/gtfalruxeb.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.jinqigfzy.top/Article/details/gtdgewtpog.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzrxkzjbl.html

[A25] 字符串比较
来源：http://dali.svipenyu.cn/Article/details/gtctpvogku.html

Py:   s1 == s2; s1 != s2
来源：http://dali.jinqigufen.top/Article/details/gtdtdkidsx.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.sweek.top/Article/details/gtpjojtuay.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.sweek.top/Article/details/gtgasqaban.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.daria6918.cn/Article/details/gtywavygyp.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.snrcjt.cn/Article/details/gtwmwwhisz.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.ydzc1.top/Article/details/gtrjxdqvqj.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.ybcxt.top/Article/details/gtkhloanbc.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.aibaodan.cn/Article/details/gthfbzvtlu.html

[A26] 类型转换总览
来源：http://dali.yj202588.top/Article/details/gtofiejqks.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.meibo888.top/Article/details/gtzywpytcf.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.zycfv.cn/Article/details/gtdjipuqiu.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.jqgfzy.top/Article/details/gtcyuzdxob.html

TS:   Number() String() Boolean() x as number
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpxvhlfcr.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.fzhhl.top/Article/details/gtnuyjnjot.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.cdnleiting.top/Article/details/gtdqrblhsg.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.c1oappe.top/Article/details/gtigcelyum.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.redwolf501.top/Article/details/gthmaefyrb.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gttnnffgpk.html

B. 流程控制
来源：http://dali.yangfankeji.com/Article/details/gtuvlkcmpt.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtghhtmoqc.html

[B01] 条件判断 if / else
来源：http://dali.chenjidiqi.icu/Article/details/gtczghapgp.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.yj20258.top/Article/details/gtsvgklcan.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.nanxinkj.top/Article/details/gtykdasfkc.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.daxiang520.top/Article/details/gtvezvbmet.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.c1oappe.top/Article/details/gtkjbqbxbg.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.wangdashe.top/Article/details/gtqcfpgdwr.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.zycfv.cn/Article/details/gttsokfdis.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.zhongyouzk.top/Article/details/gtcvibtmha.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.cheryme.top/Article/details/gtzwccghfm.html

[B02] 多分支 else if / elif
来源：http://dali.mhx1999.top/Article/details/gtjvhqrctk.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.shuidangran.top/Article/details/gtarpvlebx.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.hysaishi.cn/Article/details/gtmrraowpm.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.sysykeji.top/Article/details/gtxcxqcwbm.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpbqjslzw.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ivvv.top/Article/details/gtgnoavjvf.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.xinyue.icu/Article/details/gtkocledfl.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.cheryme.top/Article/details/gtomiagjtt.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shangyingyoupin.top/Article/details/gtyubmufee.html

[B03] switch / match / case
来源：http://dali.guowangkeji.top/Article/details/gtkpxnnbne.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.jyoumei.cn/Article/details/gtahyvpiis.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.xinyue.icu/Article/details/gtrkprjbic.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yj202588.top/Article/details/gtctmrwfmp.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jqgfzy.top/Article/details/gtndmnohee.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.yueranfly.top/Article/details/gtvweerwkv.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.hnqzz.top/Article/details/gtbuxyszsv.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.sysykeji.top/Article/details/gtbglyzlnq.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyukhnslq.html

[B04] for 计数循环
来源：http://dali.xuanzx.com/Article/details/gtgpdvmpbs.html

Py:   for i in range(10): print(i)
来源：http://dali.zhijiandao.cn/Article/details/gthzbwktna.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.shangyingyoupin.top/Article/details/gtuplmynxp.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yueranfly.top/Article/details/gtfmiadrpy.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.redwolf501.top/Article/details/gtqzjsoyzo.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.xuetiantiany.cn/Article/details/gtnssfnwhy.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.jinqigufen.top/Article/details/gtzfwoftzn.html

Ruby: 10.times { |i| puts i }
来源：http://dali.fengsongda.top/Article/details/gtsjzcliwl.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.yj20258.top/Article/details/gtfgjplcxf.html

[B05] 遍历数组 / 列表
来源：http://dali.c1oappe.top/Article/details/gtoewosyxd.html

Py:   for item in arr: print(item)
来源：http://dali.tian-w.cn/Article/details/gtqgviyrdd.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.shzxlz.cn/Article/details/gtjrqbnevp.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.xuanzx.com/Article/details/gtnztmndag.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.fzhhl.top/Article/details/gtoaojvegr.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.jyoumei.cn/Article/details/gtutceyafs.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.tian-w.cn/Article/details/gtdbedhdqv.html

Ruby: arr.each { |item| puts item }
来源：http://dali.xuetiantiany.cn/Article/details/gtjmkfhfmz.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.cqqwz.cn/Article/details/gtemsgajlg.html

[B06] 遍历字典 / 对象
来源：http://dali.hnqzz.top/Article/details/gtkcstiwkt.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.svipenyu.cn/Article/details/gtiukwqbbs.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.jyoumei.cn/Article/details/gtqxledotc.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.cashguo.top/Article/details/gtaipylhsf.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.hysaishi.cn/Article/details/gtbzdvoono.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.smart0.xyz/Article/details/gtgrghvqqb.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtupsuqvce.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.zhijiandao.cn/Article/details/gtbezcpawi.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.xuanzx.com/Article/details/gthqgpudoc.html

[B07] while 循环
来源：http://dali.smart0.xyz/Article/details/gtqqpdkalu.html

Py:   while i < 10: i += 1
来源：http://dali.vqdsnc.cn/Article/details/gtapecdoxf.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.mhx1999.top/Article/details/gtbrxzfxgg.html

JS:   while (i < 10) { i++; }
来源：http://dali.cheryme.top/Article/details/gtbzfookjz.html

TS:   while (i < 10) { i++; }
来源：http://dali.chenlongwang.top/Article/details/gtepiaycbs.html

Java: while (i < 10) { i++; }
来源：http://dali.redwolf501.top/Article/details/gtdxgtgtqu.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.zdqjudy.top/Article/details/gtjcjligti.html

Ruby: while i < 10; i += 1; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtszcevdjs.html

C#:   while (i < 10) { i++; }
来源：http://dali.hywenlv.cn/Article/details/gtmbammcif.html

[B08] do-while（至少执行一次）
来源：http://dali.sweek.top/Article/details/gtyfjvzycu.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.yangfankeji.com/Article/details/gtbcvpvhfb.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.9152youxi.cn/Article/details/gtugnondkx.html

JS:   do { i++; } while (i < 10);
来源：http://dali.sysykeji.top/Article/details/gtyxeqekhl.html

TS:   do { i++; } while (i < 10);
来源：http://dali.zhiwuduotai.top/Article/details/gtummsrpwi.html

Java: do { i++; } while (i < 10);
来源：http://dali.cdnleiting.top/Article/details/gtqvyxhayr.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.vqdsnc.cn/Article/details/gtbabmkimq.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.jyoumei.cn/Article/details/gtvdnhgqcj.html

C#:   do { i++; } while (i < 10);
来源：http://dali.yonumen.top/Article/details/gtbgqqresj.html

[B09] break 与 continue
来源：http://dali.dashuyun.cn/Article/details/gtqyemaerd.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.chenzaomai.com/Article/details/gtbxplxfjl.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.gogol.net.cn/Article/details/gtoebladxi.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnrlqcbfx.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jlsjyb.cn/Article/details/gtesnfpqhf.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.haohaochexian.top/Article/details/gtuorgbpom.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.yongpay.top/Article/details/gtgxkzndeu.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.tian-w.cn/Article/details/gtquifhcmj.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yuanzhike.top/Article/details/gtxwwtkryz.html

[B10] 遍历同时拿索引
来源：http://dali.zhixingplan.top/Article/details/gtpgnyjuqt.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.xinyue.icu/Article/details/gtjccalczu.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.havefunace.top/Article/details/gtanwxysnf.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yonumen.top/Article/details/gtdvvbkuou.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.gogol.net.cn/Article/details/gtbazwayfl.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.birdmap.top/Article/details/gtxkegfkdw.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.hfpthk.cn/Article/details/gtcrbwiamo.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.ydzc1.top/Article/details/gtzvmjhpsd.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.wangdashe.top/Article/details/gtdnoytmfb.html

[B11] 生成数字序列 / 区间
来源：http://dali.ydzc1.top/Article/details/gtzofaarvd.html

Py:   list(range(0, 10, 2))
来源：http://dali.haohaochexian.top/Article/details/gtpeqiwozs.html

PHP:  range(0, 10, 2);
来源：http://dali.guowangkeji.top/Article/details/gtdkuqgrvd.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcwimvbyv.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yuanzhike.top/Article/details/gtbyzfzoen.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.redwolf501.top/Article/details/gtozjytcoe.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhengqikj.top/Article/details/gtktstrbft.html

Ruby: (0...10).step(2).to_a
来源：http://dali.pycfn.com/Article/details/gtautwibsg.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.xziqi.cn/Article/details/gttxcdobtr.html

[B12] 跳出多层循环
来源：http://dali.birdmap.top/Article/details/gtgwpuvuzq.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.redwolf501.top/Article/details/gtmbwituxw.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.hfpthk.cn/Article/details/gtfkbnodmb.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hnxiangtu.top/Article/details/gtiawzvkyv.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.aibaodan.cn/Article/details/gtbyhdmryt.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.dashuyun.cn/Article/details/gtlcmfrbjk.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.haohaochexian.top/Article/details/gttjbftcpz.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.guowangkeji.top/Article/details/gtypxhnakd.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.nanxinkj.top/Article/details/gthhuqllio.html

[B13] 判断是否为数字
来源：http://dali.aizwys.cn/Article/details/gtoysvkpaz.html

Py:   isinstance(x, (int, float))
来源：http://dali.havefunace.top/Article/details/gtaxkgkugp.html

PHP:  is_numeric($x)
来源：http://dali.vqdsnc.cn/Article/details/gtfrsvcnha.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.birdmap.top/Article/details/gtuduhilkv.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ivvv.top/Article/details/gthizapbxi.html

Java: x instanceof Number
来源：http://dali.sysykeji.top/Article/details/gthbhcprle.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.pycfn.com/Article/details/gtapjhduhp.html

Ruby: x.is_a?(Numeric)
来源：http://dali.0kj1m.cn/Article/details/gtibolzhmp.html

C#:   x is int or double or decimal
来源：http://dali.feifeiyinyue.top/Article/details/gtphxwlcbs.html

[B14] 判断值是否在集合内
来源：http://dali.zhongyouzk.top/Article/details/gtikmjojvh.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.andypj.xyz/Article/details/gtztnedxhh.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.cqqwz.cn/Article/details/gtsgsdzees.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jianghu66.top/Article/details/gtswtuhbxc.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.cashguo.top/Article/details/gtmuzloovs.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.shuidangran.top/Article/details/gtgslqhphq.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.yj202588.top/Article/details/gtuseevzup.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.fengsongda.top/Article/details/gtvaunkkrv.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yangfankeji.com/Article/details/gtxlojudra.html

[B15] 布尔运算与取反
来源：http://dali.cashguo.top/Article/details/gthuvceiex.html

Py:   a and b or not c
来源：http://dali.jianghu66.top/Article/details/gtpmlytoht.html

PHP:  $a && $b || !$c
来源：http://dali.mhx1999.top/Article/details/gtbncrypjy.html

JS:   a && b || !c
来源：http://dali.chenjidiqi.icu/Article/details/gtrqbrfnfs.html

TS:   a && b || !c
来源：http://dali.guowangkeji.top/Article/details/gthbbriecr.html

Java: a && b || !c
来源：http://dali.quarkkingdee.top/Article/details/gtozswxwfo.html

Go:   a && b || !c
来源：http://dali.havefunace.top/Article/details/gtgorkaxfa.html

Ruby: a && b || !c
来源：http://dali.sufxvd.cn/Article/details/gtvzsdknog.html

C#:   a && b || !c
来源：http://dali.xziqi.cn/Article/details/gtwhlcbbtb.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.feifeiyinyue.top/Article/details/gtisqwkuyp.html

Py:   if not data: return
来源：http://dali.aibaodan.cn/Article/details/gtnmgqrqko.html

PHP:  if (!$data) { return; }
来源：http://dali.yangfankeji.com/Article/details/gtrwsyzzbo.html

JS:   if (!data) return;
来源：http://dali.jlsjyb.cn/Article/details/gtodeautjt.html

TS:   if (!data) return;
来源：http://dali.hongshengwenyu.top/Article/details/gteaokzklo.html

Java: if (data == null) return;
来源：http://dali.gogol.net.cn/Article/details/gtzrydpwuh.html

Go:   if data == nil { return }
来源：http://dali.hfpthk.cn/Article/details/gtycihxumf.html

Ruby: return if data.nil?
来源：http://dali.iojbl.cn/Article/details/gtxrphdbfi.html

C#:   if (data == null) return;
来源：http://dali.daxiang520.top/Article/details/gtqtuydwfc.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtdffekwua.html

C. 函数与作用域
来源：http://dali.smart0.xyz/Article/details/gtiamxabni.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtdpcxvhav.html

[C01] 定义函数
来源：http://dali.tian-w.cn/Article/details/gtzcgwxntn.html

Py:   def add(a, b): return a + b
来源：http://dali.smart0.xyz/Article/details/gtselsocmb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.9152youxi.cn/Article/details/gtcwhmmilk.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.guannengcc.top/Article/details/gtabxepdde.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.pycfn.com/Article/details/gtcrbtzisn.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.quarkkingdee.top/Article/details/gtuofmdggl.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.ppjwa.cn/Article/details/gtbpdrtrky.html

Ruby: def add(a, b); a + b; end
来源：http://dali.birdmap.top/Article/details/gtutsfdcgd.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtdauxbypz.html

[C02] 默认参数
来源：http://dali.nanxuanxn.top/Article/details/gtxajkggly.html

Py:   def greet(name="World"): return name
来源：http://dali.fengsongda.top/Article/details/gtpdgplilh.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jianghu66.top/Article/details/gteetapirp.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.c1oappe.top/Article/details/gtvutdwzho.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtygrexgel.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.hammf.cn/Article/details/gtmwdptfpp.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gtvxypcwtp.html

Ruby: def greet(name = "World") = name
来源：http://dali.quarkkingdee.top/Article/details/gtzcbijcht.html


<!-- 参考信息 -->