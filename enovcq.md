代发 wailian999

C#:   // 单行；/* 多行 */
来源：http://dali.zhoulong.xyz/Article/details/gt2iiukffti.html

[A15] 空值判断与默认值
来源：http://dali.aizwys.cn/Article/details/gt2eiugxube.html

Py:   value = data or "默认值"
来源：http://dali.kuanghao11.cn/Article/details/gt2oicophik.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.yj20258888.top/Article/details/gt2vtoubbeh.html

JS:   const value = data ?? "默认值";
来源：http://dali.ivvv.top/Article/details/gt2tsrguhvu.html

TS:   const value = data ?? "默认值";
来源：http://dali.iojbl.cn/Article/details/gt2civxigap.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.yj20258.top/Article/details/gt2hkoetvmg.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.yueranfly.top/Article/details/gt2bulwfidh.html

Ruby: value = data || "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2xphmnxjm.html

C#:   var value = data ?? "默认值";
来源：http://dali.jqgufenzy.top/Article/details/gt2jegwsqiw.html

[A16] 真假值判断规则
来源：http://dali.zhengqikj.top/Article/details/gt2sunmtnfm.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.jlsjyb.cn/Article/details/gt2xbcnczrx.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.cqqwz.cn/Article/details/gt2qgrmxzyi.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.ivvv.top/Article/details/gt2qvldqwai.html

TS:   if (!x) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2beqhffgd.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.cdnleiting.top/Article/details/gt2juiiqasl.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.chenlongwang.top/Article/details/gt2hguyrkch.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jrfxgihq.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.jqgfzy.top/Article/details/gt2bqjzuikd.html

[A17] 位运算
来源：http://dali.redwolf501.top/Article/details/gt2qbwnpikk.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.kuanghao11.cn/Article/details/gt2bipmtego.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.yuxming.cn/Article/details/gt2vbnxtlsy.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.chenzaomai.com/Article/details/gt2uykwvbrv.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.cucudq.cn/Article/details/gt2qlaymqoz.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.pycfn.com/Article/details/gt2brlmleho.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.jianghu66.top/Article/details/gt2lvgvomfc.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.cucudq.cn/Article/details/gt2ghtivzxc.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.gogol.net.cn/Article/details/gt2supgtgnj.html

[A18] 字符与 ASCII 码互转
来源：http://dali.quarkkingdee.top/Article/details/gt2xkcpnirz.html

Py:   ord("A"); chr(65)
来源：http://dali.hnxiangtu.top/Article/details/gt2mirwxaxl.html

PHP:  ord("A"); chr(65)
来源：http://dali.zhiwuduotai.top/Article/details/gt2nueqbnxk.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.guannengcc.top/Article/details/gt2tlbbcxbh.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvekbbuf.html

Java: (int) 'A'; (char) 65
来源：http://dali.redwolf501.top/Article/details/gt2auhefdcl.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.tanke756.top/Article/details/gt2nzeondah.html

Ruby: "A".ord; 65.chr
来源：http://dali.andypj.xyz/Article/details/gt2fakkxpoe.html

C#:   (int)'A'; (char)65
来源：http://dali.ydzc1.top/Article/details/gt2utxgexoe.html

[A19] 交换两个变量
来源：http://dali.cdnleiting.top/Article/details/gt2udtlatoi.html

Py:   a, b = b, a
来源：http://dali.yanxiufei.cn/Article/details/gt2ejqaqyzi.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bdecwkuu.html

JS:   [a, b] = [b, a];
来源：http://dali.jqgufenzy.top/Article/details/gt2rpqljmgy.html

TS:   [a, b] = [b, a];
来源：http://dali.cdnleiting.top/Article/details/gt2lwxdnrzm.html

Java: int t = a; a = b; b = t;
来源：http://dali.kuanghao11.cn/Article/details/gt2zofvfxic.html

Go:   a, b = b, a
来源：http://dali.wangdashe.top/Article/details/gt2edftzham.html

Ruby: a, b = b, a
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gievaxyf.html

C#:   (a, b) = (b, a);
来源：http://dali.aizwys.cn/Article/details/gt2aqcqyusp.html

[A20] 读取标准输入
来源：http://dali.feifeiyinyue.top/Article/details/gt2rykjhkyq.html

Py:   name = input("请输入：")
来源：http://dali.yj20258888.top/Article/details/gt2lmedmpiq.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.jianghu66.top/Article/details/gt2hzcdgaui.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.hammf.cn/Article/details/gt2okrhwpvg.html

TS:   // Node.js：readline 模块
来源：http://dali.sysykeji.top/Article/details/gt2ddzlzhpl.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.yangfankeji.com/Article/details/gt2xxeqzqwy.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.haohaochexian.top/Article/details/gt2zckrwkzu.html

Ruby: gets.chomp
来源：http://dali.daxiang520.top/Article/details/gt2njvmbjmn.html

C#:   Console.ReadLine();
来源：http://dali.kuanghao11.cn/Article/details/gt2ipgqaszc.html

[A21] 保留指定小数位输出
来源：http://dali.vqdsnc.cn/Article/details/gt2czamhqzn.html

Py:   f"{3.14159:.2f}"
来源：http://dali.mhx1999.top/Article/details/gt2tqhgqxht.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.havefunace.top/Article/details/gt2ysvhdoie.html

JS:   (3.14159).toFixed(2)
来源：http://dali.yonumen.top/Article/details/gt2whkyuflw.html

TS:   (3.14159).toFixed(2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2tjoenfox.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.dashuyun.cn/Article/details/gt2iiowlneb.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.ivvv.top/Article/details/gt2odgidtdt.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.jyoumei.cn/Article/details/gt2mwlckdib.html

C#:   3.14159.ToString("F2")
来源：http://dali.aibaodan.cn/Article/details/gt2lcygjrff.html

[A22] 获取字符串长度
来源：http://dali.nanxuanxn.top/Article/details/gt2jllbldba.html

Py:   len(s)
来源：http://dali.redwolf501.top/Article/details/gt2sadxotjd.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.xylfe.cn/Article/details/gt2lgytzthy.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.mhx1999.top/Article/details/gt2zgjrewfo.html

TS:   s.length
来源：http://dali.cdnleiting.top/Article/details/gt2nfnvzjys.html

Java: s.length()
来源：http://dali.kuanghao11.cn/Article/details/gt2gdkuxtwe.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.zdqjudy.top/Article/details/gt2rccuynpc.html

Ruby: s.length
来源：http://dali.chenjidiqi.icu/Article/details/gt2ivdisvwh.html

C#:   s.Length
来源：http://dali.wangdashe.top/Article/details/gt2lifffnup.html

[A23] 大小写转换
来源：http://dali.sysykeji.top/Article/details/gt2rulmxjzr.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.sweek.top/Article/details/gt2jhrdqowu.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fllwcjye.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.cucudq.cn/Article/details/gt2jcoqntak.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.gaohongyu789.top/Article/details/gt2uuxdfgdv.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.gotoacloud.top/Article/details/gt2jstqdfcb.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.0kj1m.cn/Article/details/gt2bgnsoejl.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.ppjwa.cn/Article/details/gt2qiaycllw.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mhfhuogj.html

[A24] 去除首尾空白
来源：http://dali.c1oappe.top/Article/details/gt2cecrqlvk.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.birdmap.top/Article/details/gt2lovddzxo.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.chenlongwang.top/Article/details/gt2grzpontg.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yj20258.top/Article/details/gt2fbauhpcx.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.c1oappe.top/Article/details/gt2eotzwidu.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.ppjwa.cn/Article/details/gt2uzhhuozk.html

Go:   strings.TrimSpace(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dasiiomy.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.pengpengdd.cyou/Article/details/gt2eizcdgta.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.xylfe.cn/Article/details/gt2niwgbhfd.html

[A25] 字符串比较
来源：http://dali.wangshuangyany.cn/Article/details/gt2qtkfqrqu.html

Py:   s1 == s2; s1 != s2
来源：http://dali.cucudq.cn/Article/details/gt2psvgxlgt.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.birdmap.top/Article/details/gt2rorjmwic.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.tian-w.cn/Article/details/gt2zmiimcju.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.redwolf501.top/Article/details/gt2cotizjjv.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2vasifnyw.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cvmgkfrb.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.cqqwz.cn/Article/details/gt2xwkztsim.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.pycfn.com/Article/details/gt2nudjwxnh.html

[A26] 类型转换总览
来源：http://dali.yvedp.cn/Article/details/gt2qohorjqi.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.meibo888.top/Article/details/gt2ekjblvfr.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.ydzc1.top/Article/details/gt2rgcyhpka.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.gogol.net.cn/Article/details/gt2yhtsfzkg.html

TS:   Number() String() Boolean() x as number
来源：http://dali.zhiwuduotai.top/Article/details/gt2ghsidqbd.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.pengpengdd.cyou/Article/details/gt2kmhejsxo.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.xylfe.cn/Article/details/gt2qcaiqrfu.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.xinyue.icu/Article/details/gt2clejihke.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.yj202588.top/Article/details/gt2yetuzfjw.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2ybovxzeg.html

B. 流程控制
来源：http://dali.zhixingplan.top/Article/details/gt2poyolhbk.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2gzlxppne.html

[B01] 条件判断 if / else
来源：http://dali.yvedp.cn/Article/details/gt2hxmkfgqa.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.jqgfzy.top/Article/details/gt2tekbskdm.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2qskhbrko.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jqgufenzy.top/Article/details/gt2sklhwkik.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.pengpengdd.cyou/Article/details/gt2uphcfrkz.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.yonumen.top/Article/details/gt2wwrudnhp.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.iojbl.cn/Article/details/gt2luksosyl.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.andypj.xyz/Article/details/gt2vapwndqm.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.cucudq.cn/Article/details/gt2hpvkxoqu.html

[B02] 多分支 else if / elif
来源：http://dali.meibo888.top/Article/details/gt2gcgjixbz.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ulrzmmhe.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.gogol.net.cn/Article/details/gt2ydvlhlnz.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xylfe.cn/Article/details/gt2gslqnjnz.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.bjfxy.top/Article/details/gt2lrgynemv.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.smart0.xyz/Article/details/gt2hvdlpbba.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.9152youxi.cn/Article/details/gt2hprccupx.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.chenjidiqi.icu/Article/details/gt2ktzzawhq.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.wangshuangyany.cn/Article/details/gt2elyzgohg.html

[B03] switch / match / case
来源：http://dali.zhoulong.xyz/Article/details/gt2wbtvtliz.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.jyoumei.cn/Article/details/gt2sfrstzqs.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.dashuyun.cn/Article/details/gt2yximfsny.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2bbkdnyil.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.nanxinkj.top/Article/details/gt2kihldoqg.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.ehwqpu.com/Article/details/gt2ycwxkjry.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.wangdashe.top/Article/details/gt2dbzbpccb.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.andypj.xyz/Article/details/gt2vnnccnqg.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.havefunace.top/Article/details/gt2sovbwaes.html

[B04] for 计数循环
来源：http://dali.zdqjudy.top/Article/details/gt2ctltwipe.html

Py:   for i in range(10): print(i)
来源：http://dali.pengpengdd.cyou/Article/details/gt2dhifygeu.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.wangdashe.top/Article/details/gt2sofffgnp.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.tianlin.xyz/Article/details/gt2locnhbvc.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.chenzaomai.com/Article/details/gt2uzcoqohp.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.meibo888.top/Article/details/gt2tinxqvqd.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.hnqzz.top/Article/details/gt2fghcvjvz.html

Ruby: 10.times { |i| puts i }
来源：http://dali.dashuyun.cn/Article/details/gt2wdcjvosy.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.chenzaomai.com/Article/details/gt2jbwxsptp.html

[B05] 遍历数组 / 列表
来源：http://dali.yangfankeji.com/Article/details/gt2lhddkser.html

Py:   for item in arr: print(item)
来源：http://dali.tanke756.top/Article/details/gt2gahdcvay.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.yongpay.top/Article/details/gt2eggrrebv.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.sweek.top/Article/details/gt2mvnhssjq.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2zgexdoct.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.svipenyu.cn/Article/details/gt2hxmzeybl.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.hongshengwenyu.top/Article/details/gt2pdrcfgwo.html

Ruby: arr.each { |item| puts item }
来源：http://dali.guowangkeji.top/Article/details/gt2yrujzgoj.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.9152youxi.cn/Article/details/gt2nobcbykz.html

[B06] 遍历字典 / 对象
来源：http://dali.xylfe.cn/Article/details/gt2ktsxnunc.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vgidopok.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.zdqjudy.top/Article/details/gt2sfadwrgs.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2lwqafcss.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.fzhhl.top/Article/details/gt2hxlrmmcg.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.hnxiangtu.top/Article/details/gt2pauaskgd.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.hnxiangtu.top/Article/details/gt2wddllejs.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.vqdsnc.cn/Article/details/gt2evywmmmg.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.shzxlz.cn/Article/details/gt2ioglcrqk.html

[B07] while 循环
来源：http://dali.fzhhl.top/Article/details/gt2oqpmuloo.html

Py:   while i < 10: i += 1
来源：http://dali.jianghu66.top/Article/details/gt2ymekehgb.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.sweek.top/Article/details/gt2ieptpech.html

JS:   while (i < 10) { i++; }
来源：http://dali.nwbrower.top/Article/details/gt2qhbhybed.html

TS:   while (i < 10) { i++; }
来源：http://dali.shuidangran.top/Article/details/gt2nqhwainr.html

Java: while (i < 10) { i++; }
来源：http://dali.jianghu66.top/Article/details/gt2sqmjjgpf.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.chenlongwang.top/Article/details/gt2jlmcbjpj.html

Ruby: while i < 10; i += 1; end
来源：http://dali.iojbl.cn/Article/details/gt2bxnfazfb.html

C#:   while (i < 10) { i++; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2lgvvvagt.html

[B08] do-while（至少执行一次）
来源：http://dali.zhongyouzk.top/Article/details/gt2hodxzvgc.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.iojbl.cn/Article/details/gt2tzxdpxdw.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.yueranfly.top/Article/details/gt2rfndwava.html

JS:   do { i++; } while (i < 10);
来源：http://dali.sufxvd.cn/Article/details/gt2zsggnbez.html

TS:   do { i++; } while (i < 10);
来源：http://dali.9152youxi.cn/Article/details/gt2dkxfrgya.html

Java: do { i++; } while (i < 10);
来源：http://dali.feifeiyinyue.top/Article/details/gt2moqravad.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.0kj1m.cn/Article/details/gt2yuvtojxy.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.gzhubu.top/Article/details/gt2kxjzdezy.html

C#:   do { i++; } while (i < 10);
来源：http://dali.quarkkingdee.top/Article/details/gt2rxwdpvlp.html

[B09] break 与 continue
来源：http://dali.aizwys.cn/Article/details/gt2vzrrmiks.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.xylfe.cn/Article/details/gt2hvrthmhs.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2tiexgvee.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jqgfzy.top/Article/details/gt2eqrjzfbb.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shuidangran.top/Article/details/gt2jptlieuh.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xylfe.cn/Article/details/gt2qzwduohi.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.cucudq.cn/Article/details/gt2dkvenxts.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.nwbrower.top/Article/details/gt2slnfbhge.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.fzhhl.top/Article/details/gt2rhgmbspj.html

[B10] 遍历同时拿索引
来源：http://dali.vqdsnc.cn/Article/details/gt2ndtkbluk.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.chenjidiqi.icu/Article/details/gt2gvpncrfe.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2njqpzncw.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.chenjidiqi.icu/Article/details/gt2xejqfeqv.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.quarkkingdee.top/Article/details/gt2xduzyldm.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.daria6918.cn/Article/details/gt2rqoqiruw.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.yj202588.top/Article/details/gt2zzvsbikv.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhixingplan.top/Article/details/gt2kgzzovcg.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.jqgfzy.top/Article/details/gt2umljifhj.html

[B11] 生成数字序列 / 区间
来源：http://dali.hywenlv.cn/Article/details/gt2fybjhlxw.html

Py:   list(range(0, 10, 2))
来源：http://dali.guannengcc.top/Article/details/gt2qlttqmpy.html

PHP:  range(0, 10, 2);
来源：http://dali.ehwqpu.com/Article/details/gt2rujsnatc.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.meibo888.top/Article/details/gt2rwoqqkvs.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yj202588.top/Article/details/gt2nwlcazbn.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.chenjidiqi.icu/Article/details/gt2kzftcbwy.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.fzhhl.top/Article/details/gt2njibvmhq.html

Ruby: (0...10).step(2).to_a
来源：http://dali.mhx1999.top/Article/details/gt2wsjclfel.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zrbdglys.html

[B12] 跳出多层循环
来源：http://dali.chenzaomai.com/Article/details/gt2hxqwxsem.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.nanxuanxn.top/Article/details/gt2snauwwhx.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.vqdsnc.cn/Article/details/gt2pihlreyy.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.chenzaomai.com/Article/details/gt2ijdpvgxw.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.sysykeji.top/Article/details/gt2xsmqfpcb.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.hnqzz.top/Article/details/gt2xwgphzyz.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vsrjerje.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yj202588.top/Article/details/gt2hciutovb.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.yuxming.cn/Article/details/gt2phbzfuat.html

[B13] 判断是否为数字
来源：http://dali.shzxlz.cn/Article/details/gt2tsoirneq.html

Py:   isinstance(x, (int, float))
来源：http://dali.cdnleiting.top/Article/details/gt2gyvbczuh.html

PHP:  is_numeric($x)
来源：http://dali.cucudq.cn/Article/details/gt2dookslkq.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hywenlv.cn/Article/details/gt2xusjpzyw.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ydzc1.top/Article/details/gt2qhioqnwr.html

Java: x instanceof Number
来源：http://dali.xylfe.cn/Article/details/gt2oluhdwry.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.nanxuanxn.top/Article/details/gt2lfibavwv.html

Ruby: x.is_a?(Numeric)
来源：http://dali.gogol.net.cn/Article/details/gt2jsmjzvuc.html

C#:   x is int or double or decimal
来源：http://dali.chenlongwang.top/Article/details/gt2zvkbvmmz.html

[B14] 判断值是否在集合内
来源：http://dali.cheryme.top/Article/details/gt2vnwehjmj.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.xinyue.icu/Article/details/gt2uidlvjmp.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yuxming.cn/Article/details/gt2afzhikvr.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yj20258.top/Article/details/gt2bmwbacad.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.cqqwz.cn/Article/details/gt2cmziconi.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhiwuduotai.top/Article/details/gt2zgmbwwys.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.cucudq.cn/Article/details/gt2yhiybnju.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yongpay.top/Article/details/gt2bpvbcpmk.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.quarkkingdee.top/Article/details/gt2drhnzdmg.html

[B15] 布尔运算与取反
来源：http://dali.shangyingyoupin.top/Article/details/gt2ueozwtpy.html

Py:   a and b or not c
来源：http://dali.tanke756.top/Article/details/gt2ehcyfqex.html

PHP:  $a && $b || !$c
来源：http://dali.daria6918.cn/Article/details/gt2dbihuvhj.html

JS:   a && b || !c
来源：http://dali.zhixingplan.top/Article/details/gt2ufuqpacr.html

TS:   a && b || !c
来源：http://dali.sweek.top/Article/details/gt2vnvbehpx.html

Java: a && b || !c
来源：http://dali.sufxvd.cn/Article/details/gt2hxedwbxz.html

Go:   a && b || !c
来源：http://dali.quarkkingdee.top/Article/details/gt2tjhaqern.html

Ruby: a && b || !c
来源：http://dali.nwbrower.top/Article/details/gt2tfgaadpr.html

C#:   a && b || !c
来源：http://dali.ybcxt.top/Article/details/gt2mzgtmxsj.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.xuanzx.com/Article/details/gt2xrigigjc.html

Py:   if not data: return
来源：http://dali.xuanzx.com/Article/details/gt2dgqtipib.html

PHP:  if (!$data) { return; }
来源：http://dali.zhixingplan.top/Article/details/gt2syidmdhw.html

JS:   if (!data) return;
来源：http://dali.aibaodan.cn/Article/details/gt2hqrorujv.html

TS:   if (!data) return;
来源：http://dali.hnqzz.top/Article/details/gt2zygxdezu.html

Java: if (data == null) return;
来源：http://dali.yj202588.top/Article/details/gt2syvaqlye.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2mafgmgxc.html

Ruby: return if data.nil?
来源：http://dali.zhiwuduotai.top/Article/details/gt2nhmtcuqd.html

C#:   if (data == null) return;
来源：http://dali.xylfe.cn/Article/details/gt2vnvgognl.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wiafjjqe.html

C. 函数与作用域
来源：http://dali.dashuyun.cn/Article/details/gt2jbnermcg.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2bhtszvlj.html

[C01] 定义函数
来源：http://dali.guannengcc.top/Article/details/gt2jhhcbwfr.html

Py:   def add(a, b): return a + b
来源：http://dali.sysykeji.top/Article/details/gt2wejwchwc.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hfpthk.cn/Article/details/gt2zimfpcjp.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wfbtfdbx.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2emzjbayo.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.daria6918.cn/Article/details/gt2kobrtvni.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.quarkkingdee.top/Article/details/gt2vlwgnwao.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jyoumei.cn/Article/details/gt2cumvzccp.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.bjfxy.top/Article/details/gt2kytjiwkq.html

[C02] 默认参数
来源：http://dali.xinyue.icu/Article/details/gt2roxrtajx.html

Py:   def greet(name="World"): return name
来源：http://dali.bjfxy.top/Article/details/gt2sbnrejlj.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jqgfzy.top/Article/details/gt2hzmjoacd.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.aizwys.cn/Article/details/gt2bmchfuxb.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.xinyue.icu/Article/details/gt2adbazrnp.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.sufxvd.cn/Article/details/gt2ajjgtbhs.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.svipenyu.cn/Article/details/gt2vzatfhyd.html

Ruby: def greet(name = "World") = name
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jixdsura.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yanxiufei.cn/Article/details/gt2gybxlwcx.html

[C03] 可变参数
来源：http://dali.mhx1999.top/Article/details/gt2haxlgnsy.html

Py:   def total(*args): return sum(args)
来源：http://dali.jyoumei.cn/Article/details/gt2difnyyiu.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.svipenyu.cn/Article/details/gt2pdfnyijm.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fvbhbdsx.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cqqwz.cn/Article/details/gt2xbpdmuyi.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.cashguo.top/Article/details/gt2euhlkaky.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ektnnvcn.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yonumen.top/Article/details/gt2ufclmgoa.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.hongshengwenyu.top/Article/details/gt2rdqycqme.html

[C04] 命名参数 / 关键字参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nfdpfabt.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.aibaodan.cn/Article/details/gt2damdpeea.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.meibo888.top/Article/details/gt2nejhyraf.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.andypj.xyz/Article/details/gt2bbswwxen.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhixingplan.top/Article/details/gt2xfxahwiy.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kufyqqxp.html

Go:   // 无：用配置结构体参数
来源：http://dali.kuanghao11.cn/Article/details/gt2mynuwapw.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yanxiufei.cn/Article/details/gt2hjbvbmjr.html

C#:   f(a: 1, b: 2)
来源：http://dali.dashuyun.cn/Article/details/gt2kblnbant.html

[C05] 返回多个值
来源：http://dali.daxiang520.top/Article/details/gt2dqhkdloi.html

Py:   return a, b
来源：http://dali.yueranfly.top/Article/details/gt2nhljmfdm.html

PHP:  return [$a, $b];
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tzjnfpwt.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.chenlongwang.top/Article/details/gt2eykpczrt.html

TS:   return { a, b };
来源：http://dali.aibaodan.cn/Article/details/gt2vcckznzm.html


<!-- 参考信息 -->