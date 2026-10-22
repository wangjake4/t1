代发 wailian999

Ruby: value = data || "默认值"
来源：http://dali.gaohongyu789.top/Article/details/gt2ntietmxr.html

C#:   var value = data ?? "默认值";
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vwjnqqbd.html

[A16] 真假值判断规则
来源：http://dali.jyoumei.cn/Article/details/gt2kctbietk.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kqauaezh.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.vqdsnc.cn/Article/details/gt2qyqfyjdc.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.nanxuanxn.top/Article/details/gt2fhdynhog.html

TS:   if (!x) {}
来源：http://dali.fengsongda.top/Article/details/gt2ujcrswcc.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.iojbl.cn/Article/details/gt2pitnbtnf.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.zhiwuduotai.top/Article/details/gt2fidudtml.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2fbqstepb.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2ffkuypmc.html

[A17] 位运算
来源：http://dali.guannengcc.top/Article/details/gt2kthirjcz.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yongpay.top/Article/details/gt2pyldgikh.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.yj202588.top/Article/details/gt2tqzpupbj.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.cucudq.cn/Article/details/gt2dexjhuwq.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.yj202588.top/Article/details/gt2jnouoxee.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jlsjyb.cn/Article/details/gt2zqtgncyx.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.mhx1999.top/Article/details/gt2rhyqpavw.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hammf.cn/Article/details/gt2zwiiflfg.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yuxming.cn/Article/details/gt2pltpgdeb.html

[A18] 字符与 ASCII 码互转
来源：http://dali.yueranfly.top/Article/details/gt2jeyvauxv.html

Py:   ord("A"); chr(65)
来源：http://dali.iojbl.cn/Article/details/gt2tiiodstx.html

PHP:  ord("A"); chr(65)
来源：http://dali.jianghu66.top/Article/details/gt2yaxmhran.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.tianlin.xyz/Article/details/gt2hbfzdcuf.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.bjfxy.top/Article/details/gt2pdupspqa.html

Java: (int) 'A'; (char) 65
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xrikxecc.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.xylfe.cn/Article/details/gt2lxtesbsj.html

Ruby: "A".ord; 65.chr
来源：http://dali.hnxiangtu.top/Article/details/gt2olilviej.html

C#:   (int)'A'; (char)65
来源：http://dali.cucudq.cn/Article/details/gt2qkfhigny.html

[A19] 交换两个变量
来源：http://dali.cucudq.cn/Article/details/gt2bjdbfexg.html

Py:   a, b = b, a
来源：http://dali.jlsjyb.cn/Article/details/gt2mmrrskmo.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.dianchejie.cn/Article/details/gt2ttmeyctr.html

JS:   [a, b] = [b, a];
来源：http://dali.gaohongyu789.top/Article/details/gt2eokyrwdr.html

TS:   [a, b] = [b, a];
来源：http://dali.xziqi.cn/Article/details/gt2envuajak.html

Java: int t = a; a = b; b = t;
来源：http://dali.ybcxt.top/Article/details/gt2hrikslab.html

Go:   a, b = b, a
来源：http://dali.ivvv.top/Article/details/gt2bhtqozoo.html

Ruby: a, b = b, a
来源：http://dali.svipenyu.cn/Article/details/gt2eylrmwzv.html

C#:   (a, b) = (b, a);
来源：http://dali.hywenlv.cn/Article/details/gt2xiidbbvs.html

[A20] 读取标准输入
来源：http://dali.svipenyu.cn/Article/details/gt2hjpwsggh.html

Py:   name = input("请输入：")
来源：http://dali.hnqzz.top/Article/details/gt2hnqtokzw.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.tanke756.top/Article/details/gt2cglbeats.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.vqdsnc.cn/Article/details/gt2mwwqnrsf.html

TS:   // Node.js：readline 模块
来源：http://dali.jinqigfzy.top/Article/details/gt2jvwhmnqp.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zbtantce.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.hysaishi.cn/Article/details/gt2hhnqodpk.html

Ruby: gets.chomp
来源：http://dali.shuidangran.top/Article/details/gt2gjksqzkw.html

C#:   Console.ReadLine();
来源：http://dali.cqqwz.cn/Article/details/gt2zyfsikug.html

[A21] 保留指定小数位输出
来源：http://dali.yongpay.top/Article/details/gt2nkbmixhl.html

Py:   f"{3.14159:.2f}"
来源：http://dali.yuanzhike.top/Article/details/gt2lqwjflqv.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.zycfv.cn/Article/details/gt2lnkqiqqa.html

JS:   (3.14159).toFixed(2)
来源：http://dali.guannengcc.top/Article/details/gt2biqzfetu.html

TS:   (3.14159).toFixed(2)
来源：http://dali.xylfe.cn/Article/details/gt2womcyvgm.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.nanxinkj.top/Article/details/gt2hktfwcoc.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.xuetiantiany.cn/Article/details/gt2thvfddwq.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.snrcjt.cn/Article/details/gt2aqcmiecn.html

C#:   3.14159.ToString("F2")
来源：http://dali.fzhhl.top/Article/details/gt2kzjwjgei.html

[A22] 获取字符串长度
来源：http://dali.yuxming.cn/Article/details/gt2cxfxlijc.html

Py:   len(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2qaqtjmha.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.tian-w.cn/Article/details/gt2dencyzzg.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.zhengqikj.top/Article/details/gt2caxtfnjj.html

TS:   s.length
来源：http://dali.0kj1m.cn/Article/details/gt2novfhyqd.html

Java: s.length()
来源：http://dali.smart0.xyz/Article/details/gt2duwgcmiq.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.jiagoushi.top/Article/details/gt2uilzrzjp.html

Ruby: s.length
来源：http://dali.aizwys.cn/Article/details/gt2azsskyvr.html

C#:   s.Length
来源：http://dali.cucudq.cn/Article/details/gt2mlrdpsim.html

[A23] 大小写转换
来源：http://dali.yj202588.top/Article/details/gt2dpzhkmko.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.daria6918.cn/Article/details/gt2rxafijmb.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.cashguo.top/Article/details/gt2mjeboaue.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.yvedp.cn/Article/details/gt2hecbpgry.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.pycfn.com/Article/details/gt2uivsuzxt.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.chenzaomai.com/Article/details/gt2hvwrfabr.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.guannengcc.top/Article/details/gt2rvnmjvat.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.ybcxt.top/Article/details/gt2fvdquvlf.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2varduqgd.html

[A24] 去除首尾空白
来源：http://dali.gaohongyu789.top/Article/details/gt2rlletcwo.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.sysykeji.top/Article/details/gt2aktdtals.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.hysaishi.cn/Article/details/gt2tocdxybv.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.xinyue.icu/Article/details/gt2akggyeuj.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.iojbl.cn/Article/details/gt2ltcfoevg.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.nwbrower.top/Article/details/gt2ijjrpprt.html

Go:   strings.TrimSpace(s)
来源：http://dali.tanke756.top/Article/details/gt2oqlrfbzk.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.xinyue.icu/Article/details/gt2oepgzmdy.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.redwolf501.top/Article/details/gt2rolykkgd.html

[A25] 字符串比较
来源：http://dali.birdmap.top/Article/details/gt2fnqwobpf.html

Py:   s1 == s2; s1 != s2
来源：http://dali.fzhhl.top/Article/details/gt2xcinrivs.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.birdmap.top/Article/details/gt2fusyxwck.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.jqgfzy.top/Article/details/gt2fdxpwsrz.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.hammf.cn/Article/details/gt2vulkkfcn.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.316326.xyz/Article/details/gt2oxvfxiuz.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2evtwhpoy.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.c1oappe.top/Article/details/gt2fmuaxfvv.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.zhoulong.xyz/Article/details/gt2gtfruabb.html

[A26] 类型转换总览
来源：http://dali.ybcxt.top/Article/details/gt2guquailh.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.gotoacloud.top/Article/details/gt2bunmkwxx.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.yvedp.cn/Article/details/gt2mylzresb.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.dianchejie.cn/Article/details/gt2auopxpyd.html

TS:   Number() String() Boolean() x as number
来源：http://dali.jianghu66.top/Article/details/gt2lbynubca.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.guowangkeji.top/Article/details/gt2ajygbcaq.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.jlsjyb.cn/Article/details/gt2foqczupm.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.snrcjt.cn/Article/details/gt2kutsolxh.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.yj202588.top/Article/details/gt2nvzfgpeo.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2osadschb.html

B. 流程控制
来源：http://dali.andypj.xyz/Article/details/gt2tyiricka.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2xdawbdml.html

[B01] 条件判断 if / else
来源：http://dali.fzhhl.top/Article/details/gt2fzvftuwd.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.smart0.xyz/Article/details/gt2ulynszsy.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.jiagoushi.top/Article/details/gt2azwdcfdj.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.xinyue.icu/Article/details/gt2imgabbwg.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.sufxvd.cn/Article/details/gt2nhtkscmd.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.jinqigufen.top/Article/details/gt2kqskufly.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.svipenyu.cn/Article/details/gt2tfiiolif.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.pengpengdd.cyou/Article/details/gt2apveirgs.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.hammf.cn/Article/details/gt2lvzrgslj.html

[B02] 多分支 else if / elif
来源：http://dali.zycfv.cn/Article/details/gt2zkvrpayd.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.0kj1m.cn/Article/details/gt2csumjnrf.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nemvxvtx.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jqgfzy.top/Article/details/gt2dccvkkmt.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.fzhhl.top/Article/details/gt2kgwczarl.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.feifeiyinyue.top/Article/details/gt2kjrcvdco.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.yj202588.top/Article/details/gt2ibtgnejp.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.316326.xyz/Article/details/gt2fimrxavd.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.9152youxi.cn/Article/details/gt2kmzvojsh.html

[B03] switch / match / case
来源：http://dali.cheryme.top/Article/details/gt2slsilsnv.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.wangdashe.top/Article/details/gt2hominujh.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.zhixingplan.top/Article/details/gt2cnlkqeiv.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.guowangkeji.top/Article/details/gt2diffrqoi.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.guowangkeji.top/Article/details/gt2vkihanmk.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.yangfankeji.com/Article/details/gt2fqowtcxq.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.pycfn.com/Article/details/gt2qzbrkhhb.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zuycjtny.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yzkfpjqu.html

[B04] for 计数循环
来源：http://dali.snrcjt.cn/Article/details/gt2yrbfxzpp.html

Py:   for i in range(10): print(i)
来源：http://dali.yj202588.top/Article/details/gt2sghvtngd.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.quarkkingdee.top/Article/details/gt2nbuociif.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.hnqzz.top/Article/details/gt2cwfzowys.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.sufxvd.cn/Article/details/gt2ssodxynl.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.nanxinkj.top/Article/details/gt2bsjpfdsz.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.yuxming.cn/Article/details/gt2rhfjtzgt.html

Ruby: 10.times { |i| puts i }
来源：http://dali.cashguo.top/Article/details/gt2hjsakxsu.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.tianlin.xyz/Article/details/gt2xwrkvqlv.html

[B05] 遍历数组 / 列表
来源：http://dali.shuidangran.top/Article/details/gt2qgqijcrf.html

Py:   for item in arr: print(item)
来源：http://dali.fengsongda.top/Article/details/gt2dldqgzhy.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.fzhhl.top/Article/details/gt2hgitahaj.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.cashguo.top/Article/details/gt2mhalsmsf.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.shuidangran.top/Article/details/gt2xfcsandj.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.c1oappe.top/Article/details/gt2pedckrea.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.hfpthk.cn/Article/details/gt2chfmptzs.html

Ruby: arr.each { |item| puts item }
来源：http://dali.jianghu66.top/Article/details/gt2axjkhupl.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.hnxiangtu.top/Article/details/gt2acpbanvz.html

[B06] 遍历字典 / 对象
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nnsihmnu.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.ehwqpu.com/Article/details/gt2twwyxmec.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.jqgufenzy.top/Article/details/gt2vrbdvrxg.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ygezgsqc.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jianghu66.top/Article/details/gt2ecflttjr.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.aizwys.cn/Article/details/gt2kycbztgh.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.wangdashe.top/Article/details/gt2mdxnkaxh.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.nanxuanxn.top/Article/details/gt2hkkfasmk.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.vqdsnc.cn/Article/details/gt2zxnzsvks.html

[B07] while 循环
来源：http://dali.hywenlv.cn/Article/details/gt2ynztoixb.html

Py:   while i < 10: i += 1
来源：http://dali.redwolf501.top/Article/details/gt2gpcstvjd.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2aojwlxcy.html

JS:   while (i < 10) { i++; }
来源：http://dali.havefunace.top/Article/details/gt2drguxuzc.html

TS:   while (i < 10) { i++; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2mniwdujb.html

Java: while (i < 10) { i++; }
来源：http://dali.hysaishi.cn/Article/details/gt2bedbtrdc.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.yonumen.top/Article/details/gt2adogbdqd.html

Ruby: while i < 10; i += 1; end
来源：http://dali.daxiang520.top/Article/details/gt2tqimeqod.html

C#:   while (i < 10) { i++; }
来源：http://dali.havefunace.top/Article/details/gt2wmlvdwaj.html

[B08] do-while（至少执行一次）
来源：http://dali.hammf.cn/Article/details/gt2izuzwbyw.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.cqqwz.cn/Article/details/gt2clbspmmf.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.feifeiyinyue.top/Article/details/gt2wjbizmef.html

JS:   do { i++; } while (i < 10);
来源：http://dali.zycfv.cn/Article/details/gt2dxkkvbku.html

TS:   do { i++; } while (i < 10);
来源：http://dali.aibaodan.cn/Article/details/gt2hlxrpplm.html

Java: do { i++; } while (i < 10);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2clumbflz.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.gzhubu.top/Article/details/gt2icghdrwk.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.jyoumei.cn/Article/details/gt2miwyvoao.html

C#:   do { i++; } while (i < 10);
来源：http://dali.cqqwz.cn/Article/details/gt2tamogpvd.html

[B09] break 与 continue
来源：http://dali.nanxinkj.top/Article/details/gt2obxwmhss.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.zhongyouzk.top/Article/details/gt2fqtlqczo.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.meibo888.top/Article/details/gt2uieyczmk.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gaohongyu789.top/Article/details/gt2fkeaapuq.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yj20258.top/Article/details/gt2qhkvxali.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.aibaodan.cn/Article/details/gt2klajwowl.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.c1oappe.top/Article/details/gt2xildqgfk.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.jinqigufen.top/Article/details/gt2ejthuzwr.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sxryk.cn/Article/details/gt2aujdslwz.html

[B10] 遍历同时拿索引
来源：http://dali.ybcxt.top/Article/details/gt2bvekfzlf.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rfkybody.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zhoulong.xyz/Article/details/gt2nctyaaxm.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yj20258888.top/Article/details/gt2acxqbqpk.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jiagoushi.top/Article/details/gt2hyofneiv.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.dianchejie.cn/Article/details/gt2xywqgeax.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.yj20258.top/Article/details/gt2zmqxnhbn.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.nwbrower.top/Article/details/gt2ygeepigj.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.jqgfzy.top/Article/details/gt2hbobwhzs.html

[B11] 生成数字序列 / 区间
来源：http://dali.meibo888.top/Article/details/gt2edskinax.html

Py:   list(range(0, 10, 2))
来源：http://dali.xinyue.icu/Article/details/gt2oyujieru.html

PHP:  range(0, 10, 2);
来源：http://dali.mhx1999.top/Article/details/gt2zqmewmad.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.haohaochexian.top/Article/details/gt2fgbgzpal.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.redwolf501.top/Article/details/gt2ekkzjpkb.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.gogol.net.cn/Article/details/gt2uoncigyt.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.gogol.net.cn/Article/details/gt2uwetvbgh.html

Ruby: (0...10).step(2).to_a
来源：http://dali.svipenyu.cn/Article/details/gt2wzultedj.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yongpay.top/Article/details/gt2dptvqdft.html

[B12] 跳出多层循环
来源：http://dali.sxryk.cn/Article/details/gt2liyokqiz.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.andypj.xyz/Article/details/gt2gkqwclvg.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.xziqi.cn/Article/details/gt2mygljhdj.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.tanke756.top/Article/details/gt2ihoyvdhs.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.sufxvd.cn/Article/details/gt2nurujvku.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yuxming.cn/Article/details/gt2rguxqzrd.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.vqdsnc.cn/Article/details/gt2wmynvuyk.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.cashguo.top/Article/details/gt2kywpjlqn.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.nanxuanxn.top/Article/details/gt2gaxsutvz.html

[B13] 判断是否为数字
来源：http://dali.smart0.xyz/Article/details/gt2yvyazyok.html

Py:   isinstance(x, (int, float))
来源：http://dali.shangyingyoupin.top/Article/details/gt2erupgvih.html

PHP:  is_numeric($x)
来源：http://dali.jiagoushi.top/Article/details/gt2knxtsmgh.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.sufxvd.cn/Article/details/gt2qyscfsuc.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.guowangkeji.top/Article/details/gt2tgdcomzv.html

Java: x instanceof Number
来源：http://dali.wangshuangyany.cn/Article/details/gt2dlseyeci.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.daxiang520.top/Article/details/gt2rauegrrg.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yangfankeji.com/Article/details/gt2bsiyhbuj.html

C#:   x is int or double or decimal
来源：http://dali.yuxming.cn/Article/details/gt2kiqpfvnn.html

[B14] 判断值是否在集合内
来源：http://dali.kuanghao11.cn/Article/details/gt2zhniwqkz.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.xuanzx.com/Article/details/gt2jkukgzim.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.sufxvd.cn/Article/details/gt2xfvwbuoc.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.vqdsnc.cn/Article/details/gt2xrbpokhf.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.0kj1m.cn/Article/details/gt2dydsnuxl.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.jqgufenzy.top/Article/details/gt2zgmhingt.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.snrcjt.cn/Article/details/gt2tyicmomd.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhiwuduotai.top/Article/details/gt2edqjkzoe.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.ydzc1.top/Article/details/gt2dxrieufa.html

[B15] 布尔运算与取反
来源：http://dali.gaohongyu789.top/Article/details/gt2mxsyzbmu.html

Py:   a and b or not c
来源：http://dali.hysaishi.cn/Article/details/gt2eqhgngpy.html

PHP:  $a && $b || !$c
来源：http://dali.sxryk.cn/Article/details/gt2lyelxaoq.html

JS:   a && b || !c
来源：http://dali.0kj1m.cn/Article/details/gt2ebfmeczt.html

TS:   a && b || !c
来源：http://dali.nanxinkj.top/Article/details/gt2znuituup.html

Java: a && b || !c
来源：http://dali.hongshengwenyu.top/Article/details/gt2swyxqlor.html

Go:   a && b || !c
来源：http://dali.jyoumei.cn/Article/details/gt2xdtuyfpe.html

Ruby: a && b || !c
来源：http://dali.yvedp.cn/Article/details/gt2spfaashc.html

C#:   a && b || !c
来源：http://dali.meibo888.top/Article/details/gt2hjxgvdzu.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.cheryme.top/Article/details/gt2voclotcd.html

Py:   if not data: return
来源：http://dali.c1oappe.top/Article/details/gt2eemqttje.html

PHP:  if (!$data) { return; }
来源：http://dali.gotoacloud.top/Article/details/gt2sufmzmbx.html

JS:   if (!data) return;
来源：http://dali.zhiwuduotai.top/Article/details/gt2xuivaqds.html

TS:   if (!data) return;
来源：http://dali.xuanzx.com/Article/details/gt2qvavwjyf.html

Java: if (data == null) return;
来源：http://dali.zhengqikj.top/Article/details/gt2dciulrje.html

Go:   if data == nil { return }
来源：http://dali.quarkkingdee.top/Article/details/gt2iznjbynd.html

Ruby: return if data.nil?
来源：http://dali.jyoumei.cn/Article/details/gt2eurnwosa.html

C#:   if (data == null) return;
来源：http://dali.yangfankeji.com/Article/details/gt2haofepcp.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2bdbijbiu.html

C. 函数与作用域
来源：http://dali.yanxiufei.cn/Article/details/gt2ryycggmg.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2nsyflzkg.html

[C01] 定义函数
来源：http://dali.yj202588.top/Article/details/gt2njohpwir.html

Py:   def add(a, b): return a + b
来源：http://dali.wangshuangyany.cn/Article/details/gt2oqeiutgn.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zdqjudy.top/Article/details/gt2uqrjtwya.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.dashuyun.cn/Article/details/gt2ugxcneqw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.mhx1999.top/Article/details/gt2arjpahxf.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.vqdsnc.cn/Article/details/gt2mzzzfdls.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.cdnleiting.top/Article/details/gt2vytevgfk.html

Ruby: def add(a, b); a + b; end
来源：http://dali.cdnleiting.top/Article/details/gt2kstcpdvi.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jqgufenzy.top/Article/details/gt2dnoesopr.html

[C02] 默认参数
来源：http://dali.jqgfzy.top/Article/details/gt2zcsbkqup.html

Py:   def greet(name="World"): return name
来源：http://dali.aizwys.cn/Article/details/gt2bqqgdllt.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2cgcmngor.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.cashguo.top/Article/details/gt2edfwolvv.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.redwolf501.top/Article/details/gt2mtmmlhrg.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhixingplan.top/Article/details/gt2sydowcjv.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.gaohongyu789.top/Article/details/gt2nornzvxz.html

Ruby: def greet(name = "World") = name
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kzbdrzmg.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yj202588.top/Article/details/gt2twwhkodf.html

[C03] 可变参数
来源：http://dali.sufxvd.cn/Article/details/gt2cmltultu.html

Py:   def total(*args): return sum(args)
来源：http://dali.9152youxi.cn/Article/details/gt2hvrwwlfw.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.xziqi.cn/Article/details/gt2lrqwoqjy.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mopchysy.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sqefqxww.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhixingplan.top/Article/details/gt2bgcabqst.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhengqikj.top/Article/details/gt2peyvblxo.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.mhx1999.top/Article/details/gt2vupsaiow.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.wangshuangyany.cn/Article/details/gt2utedrcsr.html

[C04] 命名参数 / 关键字参数
来源：http://dali.nanxinkj.top/Article/details/gt2dqirjzjn.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.sxryk.cn/Article/details/gt2mmlvdrhx.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.hnqzz.top/Article/details/gt2owzvemam.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.hammf.cn/Article/details/gt2unfxvlsu.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.tian-w.cn/Article/details/gt2ycgdxwxx.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.ydzc1.top/Article/details/gt2jopkblnm.html

Go:   // 无：用配置结构体参数
来源：http://dali.bjfxy.top/Article/details/gt2znctiooy.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yangfankeji.com/Article/details/gt2ezaxzdru.html

C#:   f(a: 1, b: 2)
来源：http://dali.gogol.net.cn/Article/details/gt2gvxzsiby.html

[C05] 返回多个值
来源：http://dali.zycfv.cn/Article/details/gt2wablpuym.html

Py:   return a, b
来源：http://dali.xuanzx.com/Article/details/gt2boxotadx.html

PHP:  return [$a, $b];
来源：http://dali.yangfankeji.com/Article/details/gt2mhzkxzdm.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.dashuyun.cn/Article/details/gt2ypruyhkn.html

TS:   return { a, b };
来源：http://dali.cheryme.top/Article/details/gt2kjekptcd.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.sysykeji.top/Article/details/gt2dwvnoqfw.html

Go:   return a, b
来源：http://dali.chenjidiqi.icu/Article/details/gt2loxtpuwk.html

Ruby: return a, b
来源：http://dali.tianlin.xyz/Article/details/gt2lyvnzrqc.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.haohaochexian.top/Article/details/gt2vuzegkpn.html

[C06] 匿名函数 / lambda
来源：http://dali.wangdashe.top/Article/details/gt2ducuuxnu.html

Py:   square = lambda x: x * x
来源：http://dali.zhixingplan.top/Article/details/gt2whdagjci.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.nanxuanxn.top/Article/details/gt2edyezkgg.html

JS:   const square = x => x * x;
来源：http://dali.daria6918.cn/Article/details/gt2lrsnuvbq.html


<!-- 参考信息 -->