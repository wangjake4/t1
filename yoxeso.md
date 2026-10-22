代发 wailian999

C#:   // 单行；/* 多行 */
来源：http://dali.316326.xyz/Article/details/gt2ofofiihz.html

[A15] 空值判断与默认值
来源：http://dali.feifeiyinyue.top/Article/details/gt2gbupclrh.html

Py:   value = data or "默认值"
来源：http://dali.sxryk.cn/Article/details/gt2qsgdwkfa.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.iojbl.cn/Article/details/gt2cgypcqxo.html

JS:   const value = data ?? "默认值";
来源：http://dali.sweek.top/Article/details/gt2lpsgnaji.html

TS:   const value = data ?? "默认值";
来源：http://dali.meibo888.top/Article/details/gt2dflhbrgt.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.yueranfly.top/Article/details/gt2hwdunzgd.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.hfpthk.cn/Article/details/gt2mzbwmqbg.html

Ruby: value = data || "默认值"
来源：http://dali.yuanzhike.top/Article/details/gt2ttmqnfzl.html

C#:   var value = data ?? "默认值";
来源：http://dali.birdmap.top/Article/details/gt2ppiswtsq.html

[A16] 真假值判断规则
来源：http://dali.gzhubu.top/Article/details/gt2tctgqgqg.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.xuanzx.com/Article/details/gt2dcsajgik.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.vqdsnc.cn/Article/details/gt2vtlxxptk.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.chenzaomai.com/Article/details/gt2kpfbwuke.html

TS:   if (!x) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gycacxcd.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.chenlongwang.top/Article/details/gt2zxgfjfbm.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.hnxiangtu.top/Article/details/gt2mwrpghde.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.cashguo.top/Article/details/gt2wcqmlxyn.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2gicmobxo.html

[A17] 位运算
来源：http://dali.jqgufenzy.top/Article/details/gt2jckpfcck.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hongshengwenyu.top/Article/details/gt2gukcgazy.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.jlsjyb.cn/Article/details/gt2kmssdkee.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.wangdashe.top/Article/details/gt2edjdnjdw.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.daxiang520.top/Article/details/gt2lxyzzsxv.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhoulong.xyz/Article/details/gt2brenjqtp.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.yanxiufei.cn/Article/details/gt2rrgdgrwm.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.shzxlz.cn/Article/details/gt2javtdwkm.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.shangyingyoupin.top/Article/details/gt2vwkalyyv.html

[A18] 字符与 ASCII 码互转
来源：http://dali.nanxuanxn.top/Article/details/gt2nwlqbwqt.html

Py:   ord("A"); chr(65)
来源：http://dali.havefunace.top/Article/details/gt2obryarhx.html

PHP:  ord("A"); chr(65)
来源：http://dali.gogol.net.cn/Article/details/gt2chloyltl.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lofulmyi.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.xylfe.cn/Article/details/gt2wugkuiba.html

Java: (int) 'A'; (char) 65
来源：http://dali.meibo888.top/Article/details/gt2ucjxyruv.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.hnxiangtu.top/Article/details/gt2mkjhxlfr.html

Ruby: "A".ord; 65.chr
来源：http://dali.yuanzhike.top/Article/details/gt2dakkmsau.html

C#:   (int)'A'; (char)65
来源：http://dali.sxryk.cn/Article/details/gt2rgghdzvq.html

[A19] 交换两个变量
来源：http://dali.ybcxt.top/Article/details/gt2jkuclmzv.html

Py:   a, b = b, a
来源：http://dali.gotoacloud.top/Article/details/gt2ovlteetp.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.yj202588.top/Article/details/gt2psuqfoeb.html

JS:   [a, b] = [b, a];
来源：http://dali.andypj.xyz/Article/details/gt2filemnib.html

TS:   [a, b] = [b, a];
来源：http://dali.iojbl.cn/Article/details/gt2sxnttova.html

Java: int t = a; a = b; b = t;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qwlgbcjq.html

Go:   a, b = b, a
来源：http://dali.guowangkeji.top/Article/details/gt2spdjfwpw.html

Ruby: a, b = b, a
来源：http://dali.xziqi.cn/Article/details/gt2anhbnily.html

C#:   (a, b) = (b, a);
来源：http://dali.sufxvd.cn/Article/details/gt2jhbgvadt.html

[A20] 读取标准输入
来源：http://dali.vqdsnc.cn/Article/details/gt2wlxqcduo.html

Py:   name = input("请输入：")
来源：http://dali.bjfxy.top/Article/details/gt2jdecalrz.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.dashuyun.cn/Article/details/gt2xwijkdgs.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.chenlongwang.top/Article/details/gt2tidusdur.html

TS:   // Node.js：readline 模块
来源：http://dali.zhiwuduotai.top/Article/details/gt2crbrqfsw.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.hywenlv.cn/Article/details/gt2mvmmakvu.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.316326.xyz/Article/details/gt2usgbydxh.html

Ruby: gets.chomp
来源：http://dali.gzhubu.top/Article/details/gt2gtvporbq.html

C#:   Console.ReadLine();
来源：http://dali.zdqjudy.top/Article/details/gt2glpfrqbf.html

[A21] 保留指定小数位输出
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xtljfetp.html

Py:   f"{3.14159:.2f}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2giugioop.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.hywenlv.cn/Article/details/gt2utedhhdj.html

JS:   (3.14159).toFixed(2)
来源：http://dali.birdmap.top/Article/details/gt2jrpntoqp.html

TS:   (3.14159).toFixed(2)
来源：http://dali.yvedp.cn/Article/details/gt2hkxhdjkv.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.shuidangran.top/Article/details/gt2xbucduoj.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.yuxming.cn/Article/details/gt2osrkkyjz.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.xuetiantiany.cn/Article/details/gt2mnktklgo.html

C#:   3.14159.ToString("F2")
来源：http://dali.hnxiangtu.top/Article/details/gt2ahowizky.html

[A22] 获取字符串长度
来源：http://dali.daria6918.cn/Article/details/gt2ddvfxbhn.html

Py:   len(s)
来源：http://dali.svipenyu.cn/Article/details/gt2pwxzewby.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.snrcjt.cn/Article/details/gt2wkdkcfad.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.birdmap.top/Article/details/gt2rmnthmgz.html

TS:   s.length
来源：http://dali.shangyingyoupin.top/Article/details/gt2fcxokjyq.html

Java: s.length()
来源：http://dali.aibaodan.cn/Article/details/gt2cxdyjtzb.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.ehwqpu.com/Article/details/gt2hzjmppim.html

Ruby: s.length
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ljlhnluy.html

C#:   s.Length
来源：http://dali.shuidangran.top/Article/details/gt2vzcgzwjg.html

[A23] 大小写转换
来源：http://dali.cqqwz.cn/Article/details/gt2kyaedugw.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.tian-w.cn/Article/details/gt2mcabdimt.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.shzxlz.cn/Article/details/gt2cfxtskzx.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.redwolf501.top/Article/details/gt2orfankwj.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fdsyfioj.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.cucudq.cn/Article/details/gt2xxjykoqh.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.wangdashe.top/Article/details/gt2qnrjpdix.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.zhoulong.xyz/Article/details/gt2bdxwelfs.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.ivvv.top/Article/details/gt2tsxtuzhh.html

[A24] 去除首尾空白
来源：http://dali.feifeiyinyue.top/Article/details/gt2qgbtmftx.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.ehwqpu.com/Article/details/gt2lfmngyub.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.zhongyouzk.top/Article/details/gt2rrcsdzms.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yongpay.top/Article/details/gt2klezsriv.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.hysaishi.cn/Article/details/gt2mnhzykne.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.cheryme.top/Article/details/gt2njwhnqtt.html

Go:   strings.TrimSpace(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2lirxlvec.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.dashuyun.cn/Article/details/gt2pgtsxmhh.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.havefunace.top/Article/details/gt2iamaxznq.html

[A25] 字符串比较
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ijfaakgj.html

Py:   s1 == s2; s1 != s2
来源：http://dali.dashuyun.cn/Article/details/gt2rpqoyprr.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.c1oappe.top/Article/details/gt2nsnreani.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dorbvvjb.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.mhx1999.top/Article/details/gt2fjcczvjf.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.wangshuangyany.cn/Article/details/gt2nhuewafn.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.jinqigufen.top/Article/details/gt2ttocidif.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.c1oappe.top/Article/details/gt2uztvysan.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.daxiang520.top/Article/details/gt2caagllcl.html

[A26] 类型转换总览
来源：http://dali.yongpay.top/Article/details/gt2szhyzakh.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.yj20258.top/Article/details/gt2ddycvncs.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.jqgufenzy.top/Article/details/gt2bemxbrjd.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.zhoulong.xyz/Article/details/gt2wflkatla.html

TS:   Number() String() Boolean() x as number
来源：http://dali.wangshuangyany.cn/Article/details/gt2efirbrjr.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.aizwys.cn/Article/details/gt2zyirwjjz.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.sysykeji.top/Article/details/gt2uiupfjky.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.zhixingplan.top/Article/details/gt2nikvhayu.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.bjfxy.top/Article/details/gt2ukcggapi.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2qlsnxahp.html

B. 流程控制
来源：http://dali.cucudq.cn/Article/details/gt2wgvcbtis.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2mahuesik.html

[B01] 条件判断 if / else
来源：http://dali.xylfe.cn/Article/details/gt2brnewygt.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.daxiang520.top/Article/details/gt2biorfzuq.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.guowangkeji.top/Article/details/gt2pcjbpayj.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fifnplzq.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yvedp.cn/Article/details/gt2veluaftc.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.hfpthk.cn/Article/details/gt2pxvisypi.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.zhoulong.xyz/Article/details/gt2bamskkms.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.zhengqikj.top/Article/details/gt2nllwadsj.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.jiagoushi.top/Article/details/gt2ucgduhpm.html

[B02] 多分支 else if / elif
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hsopzqwz.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.birdmap.top/Article/details/gt2awbzdong.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.yvedp.cn/Article/details/gt2hxiecwfd.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.daxiang520.top/Article/details/gt2seuezlno.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.daxiang520.top/Article/details/gt2duyqhwny.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yj202588.top/Article/details/gt2pubqqyly.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.yueranfly.top/Article/details/gt2ocsonitl.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.c1oappe.top/Article/details/gt2lojqnwma.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.sxryk.cn/Article/details/gt2hfpbobda.html

[B03] switch / match / case
来源：http://dali.jinqigufen.top/Article/details/gt2wpuncnoq.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.shuidangran.top/Article/details/gt2hisfmoes.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.jyoumei.cn/Article/details/gt2wmumaohx.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.haohaochexian.top/Article/details/gt2buctpovx.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gyhlrwkh.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.xylfe.cn/Article/details/gt2qqfuuqom.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.aibaodan.cn/Article/details/gt2cajaulst.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.aibaodan.cn/Article/details/gt2nqcdtdav.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pewifenr.html

[B04] for 计数循环
来源：http://dali.zycfv.cn/Article/details/gt2iehhbzom.html

Py:   for i in range(10): print(i)
来源：http://dali.c1oappe.top/Article/details/gt2hycolwou.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.c1oappe.top/Article/details/gt2biithbsc.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.hammf.cn/Article/details/gt2gxvvgaip.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yueranfly.top/Article/details/gt2yawudclo.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.cqqwz.cn/Article/details/gt2uxgmbpax.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.chenjidiqi.icu/Article/details/gt2kfzbdrew.html

Ruby: 10.times { |i| puts i }
来源：http://dali.wangdashe.top/Article/details/gt2qmljebvt.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.pycfn.com/Article/details/gt2okbxgfiy.html

[B05] 遍历数组 / 列表
来源：http://dali.yangfankeji.com/Article/details/gt2ulonrlfd.html

Py:   for item in arr: print(item)
来源：http://dali.chenlongwang.top/Article/details/gt2zyanntoy.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.haohaochexian.top/Article/details/gt2olianvcr.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.yj20258.top/Article/details/gt2hrwjlmse.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.yuanzhike.top/Article/details/gt2ydvtxllf.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.yuxming.cn/Article/details/gt2sytxfxgl.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.andypj.xyz/Article/details/gt2btojturd.html

Ruby: arr.each { |item| puts item }
来源：http://dali.sufxvd.cn/Article/details/gt2skikuaxr.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.sxryk.cn/Article/details/gt2xrsweltn.html

[B06] 遍历字典 / 对象
来源：http://dali.zhiwuduotai.top/Article/details/gt2ehsctevs.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.yanxiufei.cn/Article/details/gt2vkkrgran.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.sxryk.cn/Article/details/gt2fddfdmez.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.gogol.net.cn/Article/details/gt2vgfytesk.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.xylfe.cn/Article/details/gt2jqwvfznn.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.ehwqpu.com/Article/details/gt2jcqivvoc.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.cdnleiting.top/Article/details/gt2xnsfltym.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.aizwys.cn/Article/details/gt2ppphagiz.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.andypj.xyz/Article/details/gt2efkvcthr.html

[B07] while 循环
来源：http://dali.jqgufenzy.top/Article/details/gt2ypicjton.html

Py:   while i < 10: i += 1
来源：http://dali.hammf.cn/Article/details/gt2adrlfkss.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.zhongyouzk.top/Article/details/gt2scmqwcla.html

JS:   while (i < 10) { i++; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2horfkaxy.html

TS:   while (i < 10) { i++; }
来源：http://dali.cashguo.top/Article/details/gt2nuakvfmd.html

Java: while (i < 10) { i++; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vtcrwahk.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.hfpthk.cn/Article/details/gt2kolqgntq.html

Ruby: while i < 10; i += 1; end
来源：http://dali.jlsjyb.cn/Article/details/gt2prqgztcn.html

C#:   while (i < 10) { i++; }
来源：http://dali.cashguo.top/Article/details/gt2sgvyohkn.html

[B08] do-while（至少执行一次）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xtyhycos.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.cheryme.top/Article/details/gt2xmfnvome.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.guowangkeji.top/Article/details/gt2elgzzrqg.html

JS:   do { i++; } while (i < 10);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rmdjanpt.html

TS:   do { i++; } while (i < 10);
来源：http://dali.tianlin.xyz/Article/details/gt2jdkbtfeo.html

Java: do { i++; } while (i < 10);
来源：http://dali.mhx1999.top/Article/details/gt2pclekirr.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.zycfv.cn/Article/details/gt2ipaxnsuz.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.zhixingplan.top/Article/details/gt2eidxjlxc.html

C#:   do { i++; } while (i < 10);
来源：http://dali.ivvv.top/Article/details/gt2ueolxgtp.html

[B09] break 与 continue
来源：http://dali.nanxuanxn.top/Article/details/gt2iehkxgol.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.gogol.net.cn/Article/details/gt2qnhgzpvu.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.xinyue.icu/Article/details/gt2stybxryy.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gaohongyu789.top/Article/details/gt2kefbybbs.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iyywtaov.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.birdmap.top/Article/details/gt2uhcgreqa.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.andypj.xyz/Article/details/gt2gzabkbpu.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.gaohongyu789.top/Article/details/gt2nprkixbd.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.kuanghao11.cn/Article/details/gt2hmunlmxj.html

[B10] 遍历同时拿索引
来源：http://dali.ehwqpu.com/Article/details/gt2zwqyryks.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.yvedp.cn/Article/details/gt2bjllleqk.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.hfpthk.cn/Article/details/gt2ejqrvzdq.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gaajunan.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.andypj.xyz/Article/details/gt2wmxwsyas.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2ikgzvnah.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.smart0.xyz/Article/details/gt2kzlpknzh.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.cashguo.top/Article/details/gt2ztabvpzd.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.quarkkingdee.top/Article/details/gt2wyuwpayq.html

[B11] 生成数字序列 / 区间
来源：http://dali.gzhubu.top/Article/details/gt2ijxtkved.html

Py:   list(range(0, 10, 2))
来源：http://dali.guannengcc.top/Article/details/gt2mmvnpcno.html

PHP:  range(0, 10, 2);
来源：http://dali.316326.xyz/Article/details/gt2xbanoekv.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jianghu66.top/Article/details/gt2qywaafqq.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.9152youxi.cn/Article/details/gt2ypnvnrcl.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.c1oappe.top/Article/details/gt2akewxycr.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.jqgufenzy.top/Article/details/gt2pkgnvlcz.html

Ruby: (0...10).step(2).to_a
来源：http://dali.ehwqpu.com/Article/details/gt2kijoyihu.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.nanxinkj.top/Article/details/gt2gryxwiby.html

[B12] 跳出多层循环
来源：http://dali.yonumen.top/Article/details/gt2vprbylrp.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.hnqzz.top/Article/details/gt2cjkyzwxk.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.meibo888.top/Article/details/gt2nsuucnfh.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhongyouzk.top/Article/details/gt2mgbjgwgc.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhiwuduotai.top/Article/details/gt2wojopjma.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.nanxinkj.top/Article/details/gt2azblxyyq.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhoulong.xyz/Article/details/gt2qfzlydgf.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.dashuyun.cn/Article/details/gt2lllcxspv.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.sxryk.cn/Article/details/gt2vzdukpts.html

[B13] 判断是否为数字
来源：http://dali.svipenyu.cn/Article/details/gt2csuxlywl.html

Py:   isinstance(x, (int, float))
来源：http://dali.mhx1999.top/Article/details/gt2oncblkyl.html

PHP:  is_numeric($x)
来源：http://dali.sxryk.cn/Article/details/gt2xbzhrylb.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.dianchejie.cn/Article/details/gt2skyxvxpd.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hnqzz.top/Article/details/gt2oezzbhyv.html

Java: x instanceof Number
来源：http://dali.dianchejie.cn/Article/details/gt2iiajztdx.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.tianlin.xyz/Article/details/gt2jkkfesfy.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yuanzhike.top/Article/details/gt2qbiyinmc.html

C#:   x is int or double or decimal
来源：http://dali.zdqjudy.top/Article/details/gt2yctqirrm.html

[B14] 判断值是否在集合内
来源：http://dali.zdqjudy.top/Article/details/gt2wcayhaso.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.sysykeji.top/Article/details/gt2mjhabzky.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.shangyingyoupin.top/Article/details/gt2jkwyfsyv.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.hnxiangtu.top/Article/details/gt2vjfkbhwz.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.redwolf501.top/Article/details/gt2gsvvqqnn.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.cheryme.top/Article/details/gt2wuqueuet.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.wangdashe.top/Article/details/gt2hvqmiihy.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.ppjwa.cn/Article/details/gt2wkzyylhr.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yongpay.top/Article/details/gt2krllnrnn.html

[B15] 布尔运算与取反
来源：http://dali.zhiwuduotai.top/Article/details/gt2fmxgqsuh.html

Py:   a and b or not c
来源：http://dali.yonumen.top/Article/details/gt2zgedmtjx.html

PHP:  $a && $b || !$c
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2agxyjoif.html

JS:   a && b || !c
来源：http://dali.316326.xyz/Article/details/gt2rzuvkfza.html

TS:   a && b || !c
来源：http://dali.daxiang520.top/Article/details/gt2ofllhpkw.html

Java: a && b || !c
来源：http://dali.shuidangran.top/Article/details/gt2ibzltxoj.html

Go:   a && b || !c
来源：http://dali.chenjidiqi.icu/Article/details/gt2eaddjzwp.html

Ruby: a && b || !c
来源：http://dali.vqdsnc.cn/Article/details/gt2hdahkhzv.html

C#:   a && b || !c
来源：http://dali.xylfe.cn/Article/details/gt2bfoducit.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.c1oappe.top/Article/details/gt2sbrcqgqt.html

Py:   if not data: return
来源：http://dali.jlsjyb.cn/Article/details/gt2hhzevtay.html

PHP:  if (!$data) { return; }
来源：http://dali.c1oappe.top/Article/details/gt2cmmekxqe.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2amctgagn.html

TS:   if (!data) return;
来源：http://dali.aibaodan.cn/Article/details/gt2fvlavjho.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2hzpcdhhv.html

Go:   if data == nil { return }
来源：http://dali.gogol.net.cn/Article/details/gt2dorbqczs.html

Ruby: return if data.nil?
来源：http://dali.ydzc1.top/Article/details/gt2afrtixpu.html

C#:   if (data == null) return;
来源：http://dali.chenzaomai.com/Article/details/gt2alrsbdlb.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2atwiaqzt.html

C. 函数与作用域
来源：http://dali.xuetiantiany.cn/Article/details/gt2xcitewdc.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2xvjcbbus.html

[C01] 定义函数
来源：http://dali.sweek.top/Article/details/gt2kvhuqusp.html

Py:   def add(a, b): return a + b
来源：http://dali.haohaochexian.top/Article/details/gt2vgtqujjo.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.chenlongwang.top/Article/details/gt2kebflxwl.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2lfkrvguv.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ppjwa.cn/Article/details/gt2arslfqpi.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.hywenlv.cn/Article/details/gt2dyvmbvjz.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.guannengcc.top/Article/details/gt2xncufnrg.html

Ruby: def add(a, b); a + b; end
来源：http://dali.cashguo.top/Article/details/gt2epyrbhan.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.dianchejie.cn/Article/details/gt2xwizgsel.html

[C02] 默认参数
来源：http://dali.yongpay.top/Article/details/gt2gdimqzdv.html

Py:   def greet(name="World"): return name
来源：http://dali.cqqwz.cn/Article/details/gt2nrksrxqm.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.0kj1m.cn/Article/details/gt2orylbgkl.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.9152youxi.cn/Article/details/gt2hotollmr.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jinqigfzy.top/Article/details/gt2rvuwcjfs.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.ybcxt.top/Article/details/gt2crewcywq.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yuxming.cn/Article/details/gt2mcijbnov.html

Ruby: def greet(name = "World") = name
来源：http://dali.birdmap.top/Article/details/gt2xbgjoaak.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhiwuduotai.top/Article/details/gt2ahmpctio.html

[C03] 可变参数
来源：http://dali.aibaodan.cn/Article/details/gt2qfuwgczw.html

Py:   def total(*args): return sum(args)
来源：http://dali.chenlongwang.top/Article/details/gt2ujtqrkpz.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.sxryk.cn/Article/details/gt2elvqgdrz.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.kuanghao11.cn/Article/details/gt2qqrdzzua.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2aywnogtg.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.sufxvd.cn/Article/details/gt2eswfrasq.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zdqjudy.top/Article/details/gt2yaxewlqm.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2euujjtdm.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.9152youxi.cn/Article/details/gt2ydfsmtyg.html

[C04] 命名参数 / 关键字参数
来源：http://dali.daxiang520.top/Article/details/gt2nffblcll.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jqgfzy.top/Article/details/gt2nsnpuzni.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.xinyue.icu/Article/details/gt2tzutmgvw.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.hnqzz.top/Article/details/gt2typjlvbh.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.hysaishi.cn/Article/details/gt2paciyyyi.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.birdmap.top/Article/details/gt2rqwjecxf.html

Go:   // 无：用配置结构体参数
来源：http://dali.daria6918.cn/Article/details/gt2rdypeacr.html

Ruby: f(a: 1, b: 2)
来源：http://dali.gogol.net.cn/Article/details/gt2nngifpri.html

C#:   f(a: 1, b: 2)
来源：http://dali.sxryk.cn/Article/details/gt2jorhufte.html

[C05] 返回多个值
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jpkqctob.html

Py:   return a, b
来源：http://dali.yanxiufei.cn/Article/details/gt2ejgryfaj.html

PHP:  return [$a, $b];
来源：http://dali.hfpthk.cn/Article/details/gt2eeiqpcol.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.316326.xyz/Article/details/gt2fnncntan.html

TS:   return { a, b };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2futyphfx.html


<!-- 参考信息 -->