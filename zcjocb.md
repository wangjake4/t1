代发 wailian999

[A14] 注释写法
来源：http://dali.shanyushiyangtech.top/Article/details/gtfiuhdexk.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.nanxinkj.top/Article/details/gtjiactwws.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.yongpay.top/Article/details/gtthjvpibr.html

JS:   // 单行；/* 多行 */
来源：http://dali.haohaochexian.top/Article/details/gtipzvnted.html

TS:   // 单行；/* 多行 */
来源：http://dali.xziqi.cn/Article/details/gtaivwkduu.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.aizwys.cn/Article/details/gtcjcuzpmp.html

Go:   // 单行；/* 多行 */
来源：http://dali.pycfn.com/Article/details/gtbbramwdu.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.meibo888.top/Article/details/gtnwrclsgq.html

C#:   // 单行；/* 多行 */
来源：http://dali.chenjidiqi.icu/Article/details/gtvufffeog.html

[A15] 空值判断与默认值
来源：http://dali.ehwqpu.com/Article/details/gtdznhpyss.html

Py:   value = data or "默认值"
来源：http://dali.cdnleiting.top/Article/details/gtraihbhuw.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zycfv.cn/Article/details/gtrxmwknfm.html

JS:   const value = data ?? "默认值";
来源：http://dali.xuanzx.com/Article/details/gtddbydduo.html

TS:   const value = data ?? "默认值";
来源：http://dali.jinghuilouyu.cn/Article/details/gtlgyycdhf.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyapgpnbp.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.yj202588.top/Article/details/gtybyuzbhm.html

Ruby: value = data || "默认值"
来源：http://dali.hfpthk.cn/Article/details/gthgbvhdqr.html

C#:   var value = data ?? "默认值";
来源：http://dali.daxiang520.top/Article/details/gtvekhfdmd.html

[A16] 真假值判断规则
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsdkcafdh.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.fzhhl.top/Article/details/gtxuavkejh.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.shanyushiyangtech.top/Article/details/gtsxchdede.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.yonumen.top/Article/details/gtvquhahql.html

TS:   if (!x) {}
来源：http://dali.dianchejie.cn/Article/details/gtaiuugykb.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.yuxming.cn/Article/details/gtmdpnaxmh.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.havefunace.top/Article/details/gtghorqbhy.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoilfqymv.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.ydzc1.top/Article/details/gtadqhwsvg.html

[A17] 位运算
来源：http://dali.hammf.cn/Article/details/gtvypfliia.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.fzhhl.top/Article/details/gtmhtkwspk.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.jqgfzy.top/Article/details/gtntprrycc.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.gzhubu.top/Article/details/gtfxixizpy.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.jinghuilouyu.cn/Article/details/gtimqjpeuw.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhengqikj.top/Article/details/gtiygirggo.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.yj20258.top/Article/details/gtdcvgoxpb.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.cashguo.top/Article/details/gtbrvhzics.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.daxiang520.top/Article/details/gtktnnaztl.html

[A18] 字符与 ASCII 码互转
来源：http://dali.sweek.top/Article/details/gttmrsgeoy.html

Py:   ord("A"); chr(65)
来源：http://dali.birdmap.top/Article/details/gtzpucyfnc.html

PHP:  ord("A"); chr(65)
来源：http://dali.meibo888.top/Article/details/gtjrgizbyl.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.gotoacloud.top/Article/details/gtpbvbsann.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.sxryk.cn/Article/details/gtsiqzpwyo.html

Java: (int) 'A'; (char) 65
来源：http://dali.sysykeji.top/Article/details/gtxegqllun.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.cashguo.top/Article/details/gtidkttwhi.html

Ruby: "A".ord; 65.chr
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnnikpvph.html

C#:   (int)'A'; (char)65
来源：http://dali.sweek.top/Article/details/gtycykudvr.html

[A19] 交换两个变量
来源：http://dali.yuxming.cn/Article/details/gtwdbugghs.html

Py:   a, b = b, a
来源：http://dali.nwbrower.top/Article/details/gtaijruuzt.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.tian-w.cn/Article/details/gtorsrceov.html

JS:   [a, b] = [b, a];
来源：http://dali.cdnleiting.top/Article/details/gtvdosdvew.html

TS:   [a, b] = [b, a];
来源：http://dali.jinqigfzy.top/Article/details/gtpggrmbrx.html

Java: int t = a; a = b; b = t;
来源：http://dali.gogol.net.cn/Article/details/gtdipexfax.html

Go:   a, b = b, a
来源：http://dali.cashguo.top/Article/details/gtuzkvryfu.html

Ruby: a, b = b, a
来源：http://dali.yj20258888.top/Article/details/gtennbxqjq.html

C#:   (a, b) = (b, a);
来源：http://dali.hysaishi.cn/Article/details/gtymvfxsjm.html

[A20] 读取标准输入
来源：http://dali.guowangkeji.top/Article/details/gtcjwwmwxy.html

Py:   name = input("请输入：")
来源：http://dali.andypj.xyz/Article/details/gtyxgjwyvt.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.zhoulong.xyz/Article/details/gtrhmfdlgk.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.jqgufenzy.top/Article/details/gtngenmckx.html

TS:   // Node.js：readline 模块
来源：http://dali.shzxlz.cn/Article/details/gtgpadfazs.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.zhixingplan.top/Article/details/gtgcalyngg.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.tanke756.top/Article/details/gtkmyhmqjw.html

Ruby: gets.chomp
来源：http://dali.9152youxi.cn/Article/details/gtbyqvtatc.html

C#:   Console.ReadLine();
来源：http://dali.guowangkeji.top/Article/details/gtuftcxznf.html

[A21] 保留指定小数位输出
来源：http://dali.xziqi.cn/Article/details/gtpbvhljso.html

Py:   f"{3.14159:.2f}"
来源：http://dali.zycfv.cn/Article/details/gtnzcbcjpg.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.hfpthk.cn/Article/details/gtasxprzyr.html

JS:   (3.14159).toFixed(2)
来源：http://dali.vqdsnc.cn/Article/details/gtlbmfeijc.html

TS:   (3.14159).toFixed(2)
来源：http://dali.gzhubu.top/Article/details/gtsivvrnzp.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.zhiwuduotai.top/Article/details/gtrfyogvla.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.daxiang520.top/Article/details/gtarsnkust.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.ehwqpu.com/Article/details/gtidohnxoa.html

C#:   3.14159.ToString("F2")
来源：http://dali.zhongyouzk.top/Article/details/gtepmqydca.html

[A22] 获取字符串长度
来源：http://dali.feifeiyinyue.top/Article/details/gtsvjqeuej.html

Py:   len(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtshrypflj.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyuwonavh.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.yj20258888.top/Article/details/gtgqnuayoq.html

TS:   s.length
来源：http://dali.jianghu66.top/Article/details/gttrbrzzxv.html

Java: s.length()
来源：http://dali.jinqigufen.top/Article/details/gthtkhbuvp.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.zhixingplan.top/Article/details/gtjgkgmppm.html

Ruby: s.length
来源：http://dali.yj20258888.top/Article/details/gtagceikqm.html

C#:   s.Length
来源：http://dali.shuidangran.top/Article/details/gtmznxoatu.html

[A23] 大小写转换
来源：http://dali.dianchejie.cn/Article/details/gtkhhexhsw.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.hfpthk.cn/Article/details/gtcmufevrd.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.xziqi.cn/Article/details/gtnqjpkrnf.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnuypmpwh.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.yangfankeji.com/Article/details/gtbviglcwk.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.daria6918.cn/Article/details/gtrtiipwhx.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.iojbl.cn/Article/details/gtajvwkyjn.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.gogol.net.cn/Article/details/gtbfkcjomj.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.daxiang520.top/Article/details/gtyjatlmgk.html

[A24] 去除首尾空白
来源：http://dali.wangshuangyany.cn/Article/details/gtdfwbsgla.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.cqqwz.cn/Article/details/gtkksdwaht.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.cucudq.cn/Article/details/gttgfgvxyw.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.mhx1999.top/Article/details/gtukdxhtiz.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.mhx1999.top/Article/details/gtoelogenq.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.c1oappe.top/Article/details/gtfzfrscec.html

Go:   strings.TrimSpace(s)
来源：http://dali.c1oappe.top/Article/details/gtlqrgvvrv.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.daxiang520.top/Article/details/gtvtictiyv.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.9152youxi.cn/Article/details/gtrdghadey.html

[A25] 字符串比较
来源：http://dali.hnxiangtu.top/Article/details/gtyhpcxewf.html

Py:   s1 == s2; s1 != s2
来源：http://dali.yvedp.cn/Article/details/gtkmwogfhx.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.zhiwuduotai.top/Article/details/gtmvlwyxux.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yuxming.cn/Article/details/gtgrywdpqg.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.xuetiantiany.cn/Article/details/gtktstyowo.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.chenjidiqi.icu/Article/details/gtninumjhd.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.vqdsnc.cn/Article/details/gttmufpdck.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkljmekbc.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtptlbwnzl.html

[A26] 类型转换总览
来源：http://dali.zhongyouzk.top/Article/details/gtuuniwinh.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.birdmap.top/Article/details/gtfyzqdjkj.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.meibo888.top/Article/details/gtitlngpcs.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.redwolf501.top/Article/details/gtsvbwruay.html

TS:   Number() String() Boolean() x as number
来源：http://dali.svipenyu.cn/Article/details/gtxwijjdyx.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.jqgufenzy.top/Article/details/gthvievojr.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.gaohongyu789.top/Article/details/gtvkjkzkcx.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.ppjwa.cn/Article/details/gtzfexwney.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.sysykeji.top/Article/details/gtzniaqoys.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwkriuhgi.html

B. 流程控制
来源：http://dali.cqqwz.cn/Article/details/gtkgrbjcaw.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtgfqokedy.html

[B01] 条件判断 if / else
来源：http://dali.andypj.xyz/Article/details/gthgxvyebv.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.9152youxi.cn/Article/details/gtosetdbox.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.xuanzx.com/Article/details/gtvafpgdap.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.xylfe.cn/Article/details/gtnbymhxrn.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.cdnleiting.top/Article/details/gthyivsjpn.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.dianchejie.cn/Article/details/gtysxceekk.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.nanxuanxn.top/Article/details/gtcpwgrxfu.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.yonumen.top/Article/details/gtlnsdsydu.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.iojbl.cn/Article/details/gtehwbkshd.html

[B02] 多分支 else if / elif
来源：http://dali.guowangkeji.top/Article/details/gtbklgrymk.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.yanxiufei.cn/Article/details/gtshmrkzhy.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.hywenlv.cn/Article/details/gtwuxrdoup.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shanyushiyangkeji.top/Article/details/gthmmjxsay.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xziqi.cn/Article/details/gturhltnuo.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jqgfzy.top/Article/details/gtiycfnvry.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.jyoumei.cn/Article/details/gtcdoifhxu.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.pengpengdd.cyou/Article/details/gtdjppeech.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.chenjidiqi.icu/Article/details/gthyjzokti.html

[B03] switch / match / case
来源：http://dali.havefunace.top/Article/details/gttnofjujf.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.0kj1m.cn/Article/details/gtidmmawpf.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.xziqi.cn/Article/details/gtrrfkydcr.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yj20258.top/Article/details/gtkqsnrthn.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.daxiang520.top/Article/details/gtsbqrlzjl.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.vqdsnc.cn/Article/details/gtfwhsmskf.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.zhiwuduotai.top/Article/details/gtvdmuxhzn.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.nanxinkj.top/Article/details/gtkwjtupgl.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.jinghuilouyu.cn/Article/details/gtnqjovdox.html

[B04] for 计数循环
来源：http://dali.chenjidiqi.icu/Article/details/gtvaaghgwk.html

Py:   for i in range(10): print(i)
来源：http://dali.cdnleiting.top/Article/details/gtzylcxhfk.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.fzhhl.top/Article/details/gtwqyqhelw.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.chenjidiqi.icu/Article/details/gtomwsulrs.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.aibaodan.cn/Article/details/gtsuxmijmp.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.hammf.cn/Article/details/gtlxckolxd.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.yj20258888.top/Article/details/gtwaellyhp.html

Ruby: 10.times { |i| puts i }
来源：http://dali.iojbl.cn/Article/details/gtnsljtqju.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.yueranfly.top/Article/details/gtjgnwmmbg.html

[B05] 遍历数组 / 列表
来源：http://dali.316326.xyz/Article/details/gtqoaeaegf.html

Py:   for item in arr: print(item)
来源：http://dali.dashuyun.cn/Article/details/gtzsftlrsl.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.nanxinkj.top/Article/details/gtasjtlmrt.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.meibo888.top/Article/details/gtvlobjsnb.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.yonumen.top/Article/details/gtfxdvzxvu.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.zhongyouzk.top/Article/details/gtvqoqdrfi.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.zhoulong.xyz/Article/details/gtdrkkhfcn.html

Ruby: arr.each { |item| puts item }
来源：http://dali.xylfe.cn/Article/details/gtrisidwbd.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.chenjidiqi.icu/Article/details/gtzkfovhsn.html

[B06] 遍历字典 / 对象
来源：http://dali.ybcxt.top/Article/details/gtodajrxnf.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.quarkkingdee.top/Article/details/gtqnomsipb.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.ivvv.top/Article/details/gtnbmtzeat.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.xylfe.cn/Article/details/gtnmrukict.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.316326.xyz/Article/details/gtpippcyfm.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.dashuyun.cn/Article/details/gtynflhaey.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.tian-w.cn/Article/details/gtjopkfhvf.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.aibaodan.cn/Article/details/gtcwjuaruh.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.yj20258.top/Article/details/gtjmmklogm.html

[B07] while 循环
来源：http://dali.316326.xyz/Article/details/gtzabwbpir.html

Py:   while i < 10: i += 1
来源：http://dali.feifeiyinyue.top/Article/details/gtkhgtphxz.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.yuanzhike.top/Article/details/gtijslgehz.html

JS:   while (i < 10) { i++; }
来源：http://dali.hongshengwenyu.top/Article/details/gtevhnyhqo.html

TS:   while (i < 10) { i++; }
来源：http://dali.sufxvd.cn/Article/details/gtolyfmtid.html

Java: while (i < 10) { i++; }
来源：http://dali.feifeiyinyue.top/Article/details/gtxsevvyir.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.gotoacloud.top/Article/details/gtzbubrzam.html

Ruby: while i < 10; i += 1; end
来源：http://dali.cdnleiting.top/Article/details/gtrnnqhino.html

C#:   while (i < 10) { i++; }
来源：http://dali.jiagoushi.top/Article/details/gtjyhbnpfe.html

[B08] do-while（至少执行一次）
来源：http://dali.wangshuangyany.cn/Article/details/gtzpkgfnqk.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.hfpthk.cn/Article/details/gtiyigrqpa.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.wangdashe.top/Article/details/gtzuxvpwaa.html

JS:   do { i++; } while (i < 10);
来源：http://dali.smart0.xyz/Article/details/gtgvrimwae.html

TS:   do { i++; } while (i < 10);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfbdtqqup.html

Java: do { i++; } while (i < 10);
来源：http://dali.birdmap.top/Article/details/gtyqgxplny.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.shanyushiyangtech.top/Article/details/gtsmjqepry.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.shuidangran.top/Article/details/gtailfiici.html

C#:   do { i++; } while (i < 10);
来源：http://dali.pycfn.com/Article/details/gtztesyicy.html

[B09] break 与 continue
来源：http://dali.wangdashe.top/Article/details/gtmihtfwyz.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.shangyingyoupin.top/Article/details/gtjzjajuwx.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.xinyue.icu/Article/details/gtwaiykvbg.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.havefunace.top/Article/details/gtoxwoamoo.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhengqikj.top/Article/details/gtwkqnjgrh.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.guowangkeji.top/Article/details/gtsiurguue.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.yangfankeji.com/Article/details/gtqpvpwxut.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.jinqigfzy.top/Article/details/gtumxqkwhr.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.mhx1999.top/Article/details/gtdlrtupbz.html

[B10] 遍历同时拿索引
来源：http://dali.yuanzhike.top/Article/details/gtbdgnjkhu.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.gotoacloud.top/Article/details/gtrqdwxtyd.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.xziqi.cn/Article/details/gtuvbkwnsn.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.gzhubu.top/Article/details/gtejaxmdts.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jinqigfzy.top/Article/details/gtybadmtwf.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.xziqi.cn/Article/details/gtldgweqfm.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.cheryme.top/Article/details/gtzrzcghzs.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.ehwqpu.com/Article/details/gtvtjqzxst.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.daria6918.cn/Article/details/gtzdyoqqrg.html

[B11] 生成数字序列 / 区间
来源：http://dali.svipenyu.cn/Article/details/gtuwhrgmug.html

Py:   list(range(0, 10, 2))
来源：http://dali.shzxlz.cn/Article/details/gtnstniqzq.html

PHP:  range(0, 10, 2);
来源：http://dali.c1oappe.top/Article/details/gtjwzonbrc.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.0kj1m.cn/Article/details/gtjgzapiui.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtefdavctg.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.nanxinkj.top/Article/details/gtniqxzkte.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.cashguo.top/Article/details/gtmzbqeuyw.html

Ruby: (0...10).step(2).to_a
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvtprbmpx.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwyzxvwde.html

[B12] 跳出多层循环
来源：http://dali.daria6918.cn/Article/details/gthrckmdax.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.aibaodan.cn/Article/details/gtmppvuxml.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.0kj1m.cn/Article/details/gtxflaxhhb.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yueranfly.top/Article/details/gtzyrmrzbt.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.aizwys.cn/Article/details/gtlkscjoxb.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhoulong.xyz/Article/details/gtaysuhswl.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtocrhmdjm.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.c1oappe.top/Article/details/gtrcxgstuv.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.gogol.net.cn/Article/details/gtvywaiwnu.html

[B13] 判断是否为数字
来源：http://dali.sweek.top/Article/details/gtmrquafte.html

Py:   isinstance(x, (int, float))
来源：http://dali.yvedp.cn/Article/details/gtcomeaywm.html

PHP:  is_numeric($x)
来源：http://dali.andypj.xyz/Article/details/gtpkoidgva.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ppjwa.cn/Article/details/gteddynmpq.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.quarkkingdee.top/Article/details/gtflemagwe.html

Java: x instanceof Number
来源：http://dali.cheryme.top/Article/details/gtdgwpfebg.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.jqgufenzy.top/Article/details/gthryiytst.html

Ruby: x.is_a?(Numeric)
来源：http://dali.ydzc1.top/Article/details/gtmertwldx.html

C#:   x is int or double or decimal
来源：http://dali.gogol.net.cn/Article/details/gtqisajkeb.html

[B14] 判断值是否在集合内
来源：http://dali.sxryk.cn/Article/details/gtfininxgj.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.cucudq.cn/Article/details/gtnjoyrrxb.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.chenzaomai.com/Article/details/gtaefetqsd.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.smart0.xyz/Article/details/gtzbmhjpfe.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.hnqzz.top/Article/details/gtccswihzr.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtehmsbwqg.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.svipenyu.cn/Article/details/gtkoxupeqs.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jqgfzy.top/Article/details/gtfawefssc.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.smart0.xyz/Article/details/gtwyhgvcqy.html

[B15] 布尔运算与取反
来源：http://dali.yanxiufei.cn/Article/details/gtkkuqswss.html

Py:   a and b or not c
来源：http://dali.nanxinkj.top/Article/details/gtmwhbywkw.html

PHP:  $a && $b || !$c
来源：http://dali.jiagoushi.top/Article/details/gtpnakhitb.html

JS:   a && b || !c
来源：http://dali.zhoulong.xyz/Article/details/gtwoxszpju.html

TS:   a && b || !c
来源：http://dali.pycfn.com/Article/details/gtrpfxrdsv.html

Java: a && b || !c
来源：http://dali.ppjwa.cn/Article/details/gtrqtryybr.html

Go:   a && b || !c
来源：http://dali.ybcxt.top/Article/details/gtkqryzthv.html

Ruby: a && b || !c
来源：http://dali.sweek.top/Article/details/gttvtxrcme.html

C#:   a && b || !c
来源：http://dali.316326.xyz/Article/details/gtzdhhxapz.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yueranfly.top/Article/details/gtctoqgnvw.html

Py:   if not data: return
来源：http://dali.daxiang520.top/Article/details/gtzzcvxcku.html

PHP:  if (!$data) { return; }
来源：http://dali.xinyue.icu/Article/details/gtykcnfiap.html

JS:   if (!data) return;
来源：http://dali.sxryk.cn/Article/details/gtfprngadv.html

TS:   if (!data) return;
来源：http://dali.cheryme.top/Article/details/gtbarcitbl.html

Java: if (data == null) return;
来源：http://dali.tanke756.top/Article/details/gtsumvqifq.html

Go:   if data == nil { return }
来源：http://dali.aibaodan.cn/Article/details/gteibyvtzq.html

Ruby: return if data.nil?
来源：http://dali.chenzaomai.com/Article/details/gtynnfsexp.html

C#:   if (data == null) return;
来源：http://dali.kuanghao11.cn/Article/details/gtormaljgh.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtwiayczrk.html

C. 函数与作用域
来源：http://dali.yvedp.cn/Article/details/gtuhnxyzio.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtvsdacpsw.html

[C01] 定义函数
来源：http://dali.zhoulong.xyz/Article/details/gtjlzwjnxe.html

Py:   def add(a, b): return a + b
来源：http://dali.yuxming.cn/Article/details/gtdksgusud.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.pycfn.com/Article/details/gtlpjnuuee.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.smart0.xyz/Article/details/gtzgifrwba.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zycfv.cn/Article/details/gtvjotgsku.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.shzxlz.cn/Article/details/gtyffbtjau.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.tian-w.cn/Article/details/gtsypdwjoc.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yangfankeji.com/Article/details/gtgitasqtx.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yanxiufei.cn/Article/details/gtcjkngzqr.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gtvwyvutgd.html

Py:   def greet(name="World"): return name
来源：http://dali.jinqigufen.top/Article/details/gtredvpljs.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.havefunace.top/Article/details/gtedcufeiy.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.hnqzz.top/Article/details/gtpgnmqriq.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.tian-w.cn/Article/details/gtyjrhzygh.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zycfv.cn/Article/details/gtdtvndncc.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhixingplan.top/Article/details/gtmnrfdvcc.html

Ruby: def greet(name = "World") = name
来源：http://dali.yj202588.top/Article/details/gtfgmseaus.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.ppjwa.cn/Article/details/gtlgqcjwsk.html

[C03] 可变参数
来源：http://dali.ppjwa.cn/Article/details/gtvhyvvypc.html

Py:   def total(*args): return sum(args)
来源：http://dali.xinyue.icu/Article/details/gtsfejoubo.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.svipenyu.cn/Article/details/gtapfbkrem.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.iojbl.cn/Article/details/gtlowxzxou.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.andypj.xyz/Article/details/gtwlhstwes.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.c1oappe.top/Article/details/gtemyzxqot.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhongyouzk.top/Article/details/gtdzhiefyu.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.xylfe.cn/Article/details/gtkxkuaojw.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdjenzrtq.html

[C04] 命名参数 / 关键字参数
来源：http://dali.haohaochexian.top/Article/details/gtqsgvxeor.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yongpay.top/Article/details/gttufsbiyd.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.nanxinkj.top/Article/details/gtjgdohhoo.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.cucudq.cn/Article/details/gttagoyilg.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yj20258888.top/Article/details/gtfdewdvum.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jyoumei.cn/Article/details/gtmedxbcpx.html


<!-- 参考信息 -->