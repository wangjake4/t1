代发 wailian999

C#:   // 单行；/* 多行 */
来源：http://dali.pycfn.com/Article/details/gt2yknvdeec.html

[A15] 空值判断与默认值
来源：http://dali.xylfe.cn/Article/details/gt2stjvgxjr.html

Py:   value = data or "默认值"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hycijabd.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhengqikj.top/Article/details/gt2zbqqhnnn.html

JS:   const value = data ?? "默认值";
来源：http://dali.chenjidiqi.icu/Article/details/gt2npjzusqk.html

TS:   const value = data ?? "默认值";
来源：http://dali.jiagoushi.top/Article/details/gt2lbbgavtz.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.xziqi.cn/Article/details/gt2tmrlhxxa.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ebjuwjdo.html

Ruby: value = data || "默认值"
来源：http://dali.chenjidiqi.icu/Article/details/gt2xhmaqgut.html

C#:   var value = data ?? "默认值";
来源：http://dali.jianghu66.top/Article/details/gt2zmagnade.html

[A16] 真假值判断规则
来源：http://dali.tanke756.top/Article/details/gt2ffxaqhbz.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.gogol.net.cn/Article/details/gt2zlaasyec.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.mhx1999.top/Article/details/gt2fvwgcsxt.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.gotoacloud.top/Article/details/gt2vmmuzioa.html

TS:   if (!x) {}
来源：http://dali.shuidangran.top/Article/details/gt2jzltzxnj.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.quarkkingdee.top/Article/details/gt2wglvjrxa.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.aibaodan.cn/Article/details/gt2fyxlwggq.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.jianghu66.top/Article/details/gt2kjnktlmn.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.zycfv.cn/Article/details/gt2mupdocqs.html

[A17] 位运算
来源：http://dali.cdnleiting.top/Article/details/gt2xvepoyhx.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ydzc1.top/Article/details/gt2qzpbcgag.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.c1oappe.top/Article/details/gt2eovdnwtm.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.sweek.top/Article/details/gt2gjgnufpn.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.guannengcc.top/Article/details/gt2iwlcdgae.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.wangshuangyany.cn/Article/details/gt2cojxbhxt.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.wangdashe.top/Article/details/gt2aykbaxvj.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.kuanghao11.cn/Article/details/gt2glipvcld.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhoulong.xyz/Article/details/gt2kccbclzo.html

[A18] 字符与 ASCII 码互转
来源：http://dali.xylfe.cn/Article/details/gt2uxtcuafq.html

Py:   ord("A"); chr(65)
来源：http://dali.bjfxy.top/Article/details/gt2qhegmeth.html

PHP:  ord("A"); chr(65)
来源：http://dali.zhengqikj.top/Article/details/gt2cggfqtbm.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.guowangkeji.top/Article/details/gt2vraereaf.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zhengqikj.top/Article/details/gt2xegvgtdh.html

Java: (int) 'A'; (char) 65
来源：http://dali.wangshuangyany.cn/Article/details/gt2pkzalpsx.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.hammf.cn/Article/details/gt2trvzxfoc.html

Ruby: "A".ord; 65.chr
来源：http://dali.xuanzx.com/Article/details/gt2qqtymnof.html

C#:   (int)'A'; (char)65
来源：http://dali.chenlongwang.top/Article/details/gt2twryjgoi.html

[A19] 交换两个变量
来源：http://dali.cheryme.top/Article/details/gt2lniqbvye.html

Py:   a, b = b, a
来源：http://dali.c1oappe.top/Article/details/gt2aebjgsrg.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jpznpano.html

JS:   [a, b] = [b, a];
来源：http://dali.pycfn.com/Article/details/gt2dpmxefag.html

TS:   [a, b] = [b, a];
来源：http://dali.haohaochexian.top/Article/details/gt2hgrvqyyo.html

Java: int t = a; a = b; b = t;
来源：http://dali.iojbl.cn/Article/details/gt2awmugwki.html

Go:   a, b = b, a
来源：http://dali.hywenlv.cn/Article/details/gt2velfqgrh.html

Ruby: a, b = b, a
来源：http://dali.gogol.net.cn/Article/details/gt2krdupvne.html

C#:   (a, b) = (b, a);
来源：http://dali.bjfxy.top/Article/details/gt2cnytnjdt.html

[A20] 读取标准输入
来源：http://dali.chenlongwang.top/Article/details/gt2bkailhkx.html

Py:   name = input("请输入：")
来源：http://dali.gaohongyu789.top/Article/details/gt2eoyjyncr.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.shzxlz.cn/Article/details/gt2ebsflhio.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.jqgfzy.top/Article/details/gt2gplxuqcv.html

TS:   // Node.js：readline 模块
来源：http://dali.yangfankeji.com/Article/details/gt2znhditwt.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.zhiwuduotai.top/Article/details/gt2vhdfibvv.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.gzhubu.top/Article/details/gt2hpkimcai.html

Ruby: gets.chomp
来源：http://dali.zhijiandao.cn/Article/details/gt2mcsasmaz.html

C#:   Console.ReadLine();
来源：http://dali.cqqwz.cn/Article/details/gt2uhicthqh.html

[A21] 保留指定小数位输出
来源：http://dali.guannengcc.top/Article/details/gt2pxebnbfo.html

Py:   f"{3.14159:.2f}"
来源：http://dali.cashguo.top/Article/details/gt2zkdidvyg.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.ehwqpu.com/Article/details/gt2thgqkjij.html

JS:   (3.14159).toFixed(2)
来源：http://dali.fzhhl.top/Article/details/gt2trokwpvi.html

TS:   (3.14159).toFixed(2)
来源：http://dali.0kj1m.cn/Article/details/gt2rmvhsltj.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.ehwqpu.com/Article/details/gt2rwimngmi.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.shuidangran.top/Article/details/gt2fzgeiief.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kkyzrpvi.html

C#:   3.14159.ToString("F2")
来源：http://dali.sxryk.cn/Article/details/gt2wwenmihn.html

[A22] 获取字符串长度
来源：http://dali.cqqwz.cn/Article/details/gt2ylzgwuek.html

Py:   len(s)
来源：http://dali.dashuyun.cn/Article/details/gt2pqmclyhk.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.hywenlv.cn/Article/details/gt2nibengwx.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.dianchejie.cn/Article/details/gt2cydqailk.html

TS:   s.length
来源：http://dali.chenlongwang.top/Article/details/gt2wjiptzvh.html

Java: s.length()
来源：http://dali.jyoumei.cn/Article/details/gt2gkktwozw.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.zhixingplan.top/Article/details/gt2znsjthqg.html

Ruby: s.length
来源：http://dali.chenlongwang.top/Article/details/gt2gmckhvbh.html

C#:   s.Length
来源：http://dali.dianchejie.cn/Article/details/gt2pbsvyicf.html

[A23] 大小写转换
来源：http://dali.jiagoushi.top/Article/details/gt2rvsaexdc.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.haohaochexian.top/Article/details/gt2soavhkum.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.fzhhl.top/Article/details/gt2setvaphs.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.sweek.top/Article/details/gt2fjgakxye.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.quarkkingdee.top/Article/details/gt2mohzauhs.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.quarkkingdee.top/Article/details/gt2jlvtzqbt.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2obdevcqa.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.pycfn.com/Article/details/gt2dvebivvo.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ayffknrn.html

[A24] 去除首尾空白
来源：http://dali.wangdashe.top/Article/details/gt2mqgxdbjt.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.ybcxt.top/Article/details/gt2zcstmdcy.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.zhixingplan.top/Article/details/gt2tiyexapr.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.pengpengdd.cyou/Article/details/gt2lfvbsffa.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.gzhubu.top/Article/details/gt2vxkbgnli.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.zhongyouzk.top/Article/details/gt2vuccyscd.html

Go:   strings.TrimSpace(s)
来源：http://dali.shuidangran.top/Article/details/gt2igakfzsn.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.guowangkeji.top/Article/details/gt2nmxrkqzh.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.hongshengwenyu.top/Article/details/gt2mqickaqg.html

[A25] 字符串比较
来源：http://dali.mhx1999.top/Article/details/gt2lvifnlqw.html

Py:   s1 == s2; s1 != s2
来源：http://dali.hywenlv.cn/Article/details/gt2anddflpm.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.hfpthk.cn/Article/details/gt2qiurnqfc.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.haohaochexian.top/Article/details/gt2fifcreyx.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ulaxkluj.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.quarkkingdee.top/Article/details/gt2zwdceits.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.yonumen.top/Article/details/gt2gjogyuad.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.havefunace.top/Article/details/gt2cyotqubj.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.hnqzz.top/Article/details/gt2mqrlhovp.html

[A26] 类型转换总览
来源：http://dali.xuanzx.com/Article/details/gt2sccapwif.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.jiagoushi.top/Article/details/gt2jurmmyeq.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mrpniybj.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.haohaochexian.top/Article/details/gt2zamzipii.html

TS:   Number() String() Boolean() x as number
来源：http://dali.sxryk.cn/Article/details/gt2ydemlzzh.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.tanke756.top/Article/details/gt2xgagrrqn.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.cqqwz.cn/Article/details/gt2bjtoxqwq.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.zhiwuduotai.top/Article/details/gt2npoftylx.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.0kj1m.cn/Article/details/gt2mczibdhn.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2gcrctdoo.html

B. 流程控制
来源：http://dali.daxiang520.top/Article/details/gt2qmdabbkq.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zufwgpto.html

[B01] 条件判断 if / else
来源：http://dali.nanxuanxn.top/Article/details/gt2nvooxggb.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.redwolf501.top/Article/details/gt2jdeecihm.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.havefunace.top/Article/details/gt2hpgjafdi.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.gzhubu.top/Article/details/gt2cwqnnqfn.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yj20258.top/Article/details/gt2xhzfbxgx.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kliuzlqr.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.hongshengwenyu.top/Article/details/gt2rnzewjpi.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.shuidangran.top/Article/details/gt2eeygoipg.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.shangyingyoupin.top/Article/details/gt2wunhzgvj.html

[B02] 多分支 else if / elif
来源：http://dali.dianchejie.cn/Article/details/gt2atraywsj.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.aibaodan.cn/Article/details/gt2eoxiptts.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.sufxvd.cn/Article/details/gt2mvrzmhff.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.meibo888.top/Article/details/gt2spbjscgh.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.dianchejie.cn/Article/details/gt2hyopgyhx.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yueranfly.top/Article/details/gt2nrvekzsl.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.xuanzx.com/Article/details/gt2fyzyacic.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.tanke756.top/Article/details/gt2xylncrcg.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.fzhhl.top/Article/details/gt2wbhwnkrj.html

[B03] switch / match / case
来源：http://dali.tian-w.cn/Article/details/gt2gtzeioif.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.aizwys.cn/Article/details/gt2pmbvhbts.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.ehwqpu.com/Article/details/gt2dpawkccy.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jlsjyb.cn/Article/details/gt2bnkofgsy.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.xinyue.icu/Article/details/gt2qqxhzkjv.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.birdmap.top/Article/details/gt2ozxacixl.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.pycfn.com/Article/details/gt2ccvqpbhr.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.xylfe.cn/Article/details/gt2eisefnan.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.guowangkeji.top/Article/details/gt2fdhtintv.html

[B04] for 计数循环
来源：http://dali.yvedp.cn/Article/details/gt2iiprwcpn.html

Py:   for i in range(10): print(i)
来源：http://dali.sweek.top/Article/details/gt2yudgnpvo.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.svipenyu.cn/Article/details/gt2ssbetwjm.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.aizwys.cn/Article/details/gt2zlijlioi.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2drqsajyb.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.bjfxy.top/Article/details/gt2bgyrjkfy.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xfroegxr.html

Ruby: 10.times { |i| puts i }
来源：http://dali.jinqigfzy.top/Article/details/gt2hanilurb.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.jianghu66.top/Article/details/gt2ihavkuxj.html

[B05] 遍历数组 / 列表
来源：http://dali.daxiang520.top/Article/details/gt2avebjwji.html

Py:   for item in arr: print(item)
来源：http://dali.gotoacloud.top/Article/details/gt2lbgmpess.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.cheryme.top/Article/details/gt2fwkxmavp.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.jyoumei.cn/Article/details/gt2znzwtifg.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.dianchejie.cn/Article/details/gt2vbcsclaj.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.andypj.xyz/Article/details/gt2ipdzsgyp.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.jqgufenzy.top/Article/details/gt2dnfnqtye.html

Ruby: arr.each { |item| puts item }
来源：http://dali.ydzc1.top/Article/details/gt2ukddubld.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.ybcxt.top/Article/details/gt2xzhwikhm.html

[B06] 遍历字典 / 对象
来源：http://dali.xylfe.cn/Article/details/gt2rctikolr.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.cashguo.top/Article/details/gt2aamjdfnr.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.c1oappe.top/Article/details/gt2tkeaciiv.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zdqjudy.top/Article/details/gt2iwgcdtpi.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.guowangkeji.top/Article/details/gt2mdqshqii.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.cqqwz.cn/Article/details/gt2yveznlhj.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.pengpengdd.cyou/Article/details/gt2cuteipzw.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.jyoumei.cn/Article/details/gt2xpecblmd.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.jqgfzy.top/Article/details/gt2yrynydbe.html

[B07] while 循环
来源：http://dali.gotoacloud.top/Article/details/gt2uyaoxjtm.html

Py:   while i < 10: i += 1
来源：http://dali.chenjidiqi.icu/Article/details/gt2wikswrmd.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2guqptmwr.html

JS:   while (i < 10) { i++; }
来源：http://dali.sweek.top/Article/details/gt2jpczqrsj.html

TS:   while (i < 10) { i++; }
来源：http://dali.cashguo.top/Article/details/gt2uoomazdy.html

Java: while (i < 10) { i++; }
来源：http://dali.zhixingplan.top/Article/details/gt2kwzfebur.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.yvedp.cn/Article/details/gt2xvlcodnh.html

Ruby: while i < 10; i += 1; end
来源：http://dali.pengpengdd.cyou/Article/details/gt2kuejkgfz.html

C#:   while (i < 10) { i++; }
来源：http://dali.jyoumei.cn/Article/details/gt2yjtcknlg.html

[B08] do-while（至少执行一次）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ycrtbegt.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.sxryk.cn/Article/details/gt2wdfdlxsr.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.hywenlv.cn/Article/details/gt2vrvagdgk.html

JS:   do { i++; } while (i < 10);
来源：http://dali.svipenyu.cn/Article/details/gt2vcdvyplp.html

TS:   do { i++; } while (i < 10);
来源：http://dali.fzhhl.top/Article/details/gt2lkjpclcf.html

Java: do { i++; } while (i < 10);
来源：http://dali.pycfn.com/Article/details/gt2oyovplhu.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.hnqzz.top/Article/details/gt2eqdlniby.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.guannengcc.top/Article/details/gt2xzyzpndv.html

C#:   do { i++; } while (i < 10);
来源：http://dali.snrcjt.cn/Article/details/gt2pvxhohad.html

[B09] break 与 continue
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hbrblfjp.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.quarkkingdee.top/Article/details/gt2dgcqvjeb.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.yueranfly.top/Article/details/gt2vtnojdmb.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.iojbl.cn/Article/details/gt2kgmyntwo.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2veifdovl.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ppjwa.cn/Article/details/gt2mkcawzmm.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.gotoacloud.top/Article/details/gt2owoapues.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.bjfxy.top/Article/details/gt2rxefqwty.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gzhubu.top/Article/details/gt2hxctbfra.html

[B10] 遍历同时拿索引
来源：http://dali.tian-w.cn/Article/details/gt2vwlqgbfm.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.hywenlv.cn/Article/details/gt2lyijxnwg.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.shzxlz.cn/Article/details/gt2xcnbdisr.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.meibo888.top/Article/details/gt2plcsxgvy.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.redwolf501.top/Article/details/gt2agceutwk.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.jinqigfzy.top/Article/details/gt2kzuspnyi.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.jianghu66.top/Article/details/gt2qrhxcpmx.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.aizwys.cn/Article/details/gt2mpuqktqj.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.iojbl.cn/Article/details/gt2fkbmhxun.html

[B11] 生成数字序列 / 区间
来源：http://dali.smart0.xyz/Article/details/gt2woajkeyl.html

Py:   list(range(0, 10, 2))
来源：http://dali.gogol.net.cn/Article/details/gt2solotmtd.html

PHP:  range(0, 10, 2);
来源：http://dali.hfpthk.cn/Article/details/gt2odkosgad.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yongpay.top/Article/details/gt2hnwovjce.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.sufxvd.cn/Article/details/gt2oanwwtvs.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.hnxiangtu.top/Article/details/gt2cazndxsk.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.chenzaomai.com/Article/details/gt2yfxbdewa.html

Ruby: (0...10).step(2).to_a
来源：http://dali.mhx1999.top/Article/details/gt2hixouqdg.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.xziqi.cn/Article/details/gt2pxjwtvyd.html

[B12] 跳出多层循环
来源：http://dali.ybcxt.top/Article/details/gt2okqrwfdi.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.jqgfzy.top/Article/details/gt2xmrapodc.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.hywenlv.cn/Article/details/gt2tyvtuvjs.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.dianchejie.cn/Article/details/gt2uyaroqol.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yueranfly.top/Article/details/gt2ttybhugr.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2htdmitia.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhixingplan.top/Article/details/gt2svakymcc.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.sweek.top/Article/details/gt2wsjpkeun.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jiagoushi.top/Article/details/gt2ilgnkvgo.html

[B13] 判断是否为数字
来源：http://dali.zhixingplan.top/Article/details/gt2tvkywrou.html

Py:   isinstance(x, (int, float))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zpxpslfv.html

PHP:  is_numeric($x)
来源：http://dali.ydzc1.top/Article/details/gt2oqutahhp.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.pycfn.com/Article/details/gt2joledwgg.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hysaishi.cn/Article/details/gt2ntpkfynf.html

Java: x instanceof Number
来源：http://dali.chenjidiqi.icu/Article/details/gt2innjvnwq.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gt2gsynkfcv.html

Ruby: x.is_a?(Numeric)
来源：http://dali.guowangkeji.top/Article/details/gt2pudtmjhw.html

C#:   x is int or double or decimal
来源：http://dali.yueranfly.top/Article/details/gt2ehgksxor.html

[B14] 判断值是否在集合内
来源：http://dali.daxiang520.top/Article/details/gt2rrfbyrev.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.vqdsnc.cn/Article/details/gt2lpknplve.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.316326.xyz/Article/details/gt2vjcqhrho.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.9152youxi.cn/Article/details/gt2mmhjmzyx.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ycfwtixy.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.hfpthk.cn/Article/details/gt2gcgwsoqu.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wgcizxzg.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jiagoushi.top/Article/details/gt2ofmumgel.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tiehpdtr.html

[B15] 布尔运算与取反
来源：http://dali.zdqjudy.top/Article/details/gt2ucgxzzbr.html

Py:   a and b or not c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lisznhvu.html

PHP:  $a && $b || !$c
来源：http://dali.zhengqikj.top/Article/details/gt2pwjxejgp.html

JS:   a && b || !c
来源：http://dali.zhengqikj.top/Article/details/gt2ajyburzr.html

TS:   a && b || !c
来源：http://dali.chenjidiqi.icu/Article/details/gt2beljihmt.html

Java: a && b || !c
来源：http://dali.hnxiangtu.top/Article/details/gt2ftbtdjgb.html

Go:   a && b || !c
来源：http://dali.zhixingplan.top/Article/details/gt2ojzxatwb.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2tbffsgsy.html

C#:   a && b || !c
来源：http://dali.cucudq.cn/Article/details/gt2owuwlefj.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.feifeiyinyue.top/Article/details/gt2hhuriwcf.html

Py:   if not data: return
来源：http://dali.ivvv.top/Article/details/gt2ztibmyid.html

PHP:  if (!$data) { return; }
来源：http://dali.zhengqikj.top/Article/details/gt2jfnjiwai.html

JS:   if (!data) return;
来源：http://dali.jinqigfzy.top/Article/details/gt2fvqvbeqk.html

TS:   if (!data) return;
来源：http://dali.hnqzz.top/Article/details/gt2vqmfoaci.html

Java: if (data == null) return;
来源：http://dali.havefunace.top/Article/details/gt2xqblnbub.html

Go:   if data == nil { return }
来源：http://dali.zhiwuduotai.top/Article/details/gt2attflxme.html

Ruby: return if data.nil?
来源：http://dali.chenlongwang.top/Article/details/gt2bwxjvqcb.html

C#:   if (data == null) return;
来源：http://dali.fengsongda.top/Article/details/gt2xjmicwkj.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2rhlvpsxe.html

C. 函数与作用域
来源：http://dali.cashguo.top/Article/details/gt2uaiqlcns.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2ybunrkrh.html

[C01] 定义函数
来源：http://dali.yj20258888.top/Article/details/gt2lktpkmcx.html

Py:   def add(a, b): return a + b
来源：http://dali.zhengqikj.top/Article/details/gt2uflvctcr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2ohbzvkqp.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.havefunace.top/Article/details/gt2zmmnhymh.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.sxryk.cn/Article/details/gt2uexxbrsb.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yj20258.top/Article/details/gt2olsuzptr.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yongpay.top/Article/details/gt2oaetjdzp.html

Ruby: def add(a, b); a + b; end
来源：http://dali.daria6918.cn/Article/details/gt2odzlqhwq.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.ydzc1.top/Article/details/gt2neapubep.html

[C02] 默认参数
来源：http://dali.zhoulong.xyz/Article/details/gt2cuijnvwq.html

Py:   def greet(name="World"): return name
来源：http://dali.feifeiyinyue.top/Article/details/gt2lrghzzgj.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.9152youxi.cn/Article/details/gt2kcmbooeu.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.haohaochexian.top/Article/details/gt2wqgtmzyn.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.andypj.xyz/Article/details/gt2sciutywb.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.redwolf501.top/Article/details/gt2yarhrkrb.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.gzhubu.top/Article/details/gt2fzwgiqzl.html

Ruby: def greet(name = "World") = name
来源：http://dali.snrcjt.cn/Article/details/gt2exdxrokr.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.wangdashe.top/Article/details/gt2hclmwgfc.html

[C03] 可变参数
来源：http://dali.sufxvd.cn/Article/details/gt2iyvboyax.html

Py:   def total(*args): return sum(args)
来源：http://dali.tanke756.top/Article/details/gt2pjydvrve.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2dcovymrq.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.birdmap.top/Article/details/gt2nhxawfya.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cdnleiting.top/Article/details/gt2nywukmlh.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.nanxuanxn.top/Article/details/gt2eyqtxttu.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.xuanzx.com/Article/details/gt2bxtstkiw.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jinqigfzy.top/Article/details/gt2phnwfgrb.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.sysykeji.top/Article/details/gt2tpiprubg.html

[C04] 命名参数 / 关键字参数
来源：http://dali.guannengcc.top/Article/details/gt2wziawcaw.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.gogol.net.cn/Article/details/gt2yfcgktyw.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.cheryme.top/Article/details/gt2yjironur.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.hywenlv.cn/Article/details/gt2yravwaxn.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.xziqi.cn/Article/details/gt2qetkfljz.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yueranfly.top/Article/details/gt2onihztdm.html

Go:   // 无：用配置结构体参数
来源：http://dali.cucudq.cn/Article/details/gt2lkcwrzfj.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yanxiufei.cn/Article/details/gt2haatktdb.html

C#:   f(a: 1, b: 2)
来源：http://dali.andypj.xyz/Article/details/gt2biirfvzs.html

[C05] 返回多个值
来源：http://dali.jqgufenzy.top/Article/details/gt2unaqnreq.html

Py:   return a, b
来源：http://dali.birdmap.top/Article/details/gt2mdctacbh.html

PHP:  return [$a, $b];
来源：http://dali.nanxinkj.top/Article/details/gt2vtvitsrj.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.quarkkingdee.top/Article/details/gt2tvqagnji.html

TS:   return { a, b };
来源：http://dali.hfpthk.cn/Article/details/gt2upfivfcq.html


<!-- 参考信息 -->