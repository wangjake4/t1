代发 wailian999

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.xuanzx.com/Article/details/gt2efwvoqjg.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.jianghu66.top/Article/details/gt2bsbmbltu.html

TS:   if (!x) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lwylxbfs.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.yangfankeji.com/Article/details/gt2awaafkff.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.zhijiandao.cn/Article/details/gt2frizsxbg.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.hywenlv.cn/Article/details/gt2qleqcrtz.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2slvpifts.html

[A17] 位运算
来源：http://dali.aizwys.cn/Article/details/gt2cxgwvwef.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hongshengwenyu.top/Article/details/gt2adngfcdy.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.daxiang520.top/Article/details/gt2opwobqyw.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.wangdashe.top/Article/details/gt2wgexovng.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gihxcwax.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhongyouzk.top/Article/details/gt2yzwjrsjt.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.xinyue.icu/Article/details/gt2absvhsmh.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xuetiantiany.cn/Article/details/gt2sohxxzxv.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.redwolf501.top/Article/details/gt2tdrzvtbg.html

[A18] 字符与 ASCII 码互转
来源：http://dali.hysaishi.cn/Article/details/gt2nyxyqxkc.html

Py:   ord("A"); chr(65)
来源：http://dali.jiagoushi.top/Article/details/gt2tgtsjhmv.html

PHP:  ord("A"); chr(65)
来源：http://dali.cheryme.top/Article/details/gt2cnbylfvd.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.nanxinkj.top/Article/details/gt2fpjyepzo.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.tianlin.xyz/Article/details/gt2dixmfxum.html

Java: (int) 'A'; (char) 65
来源：http://dali.shuidangran.top/Article/details/gt2lqotetan.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.jiagoushi.top/Article/details/gt2vxnomall.html

Ruby: "A".ord; 65.chr
来源：http://dali.zdqjudy.top/Article/details/gt2kxluucfu.html

C#:   (int)'A'; (char)65
来源：http://dali.ivvv.top/Article/details/gt2jqjwnilj.html

[A19] 交换两个变量
来源：http://dali.andypj.xyz/Article/details/gt2vcqzbjrm.html

Py:   a, b = b, a
来源：http://dali.nwbrower.top/Article/details/gt2ilenoprk.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ppwfbebl.html

JS:   [a, b] = [b, a];
来源：http://dali.ivvv.top/Article/details/gt2afqdtdbb.html

TS:   [a, b] = [b, a];
来源：http://dali.hnqzz.top/Article/details/gt2hgqdxrev.html

Java: int t = a; a = b; b = t;
来源：http://dali.redwolf501.top/Article/details/gt2dnaqsbfy.html

Go:   a, b = b, a
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wrkyvewi.html

Ruby: a, b = b, a
来源：http://dali.zhijiandao.cn/Article/details/gt2vjnwthov.html

C#:   (a, b) = (b, a);
来源：http://dali.haohaochexian.top/Article/details/gt2jtbbvtrl.html

[A20] 读取标准输入
来源：http://dali.smart0.xyz/Article/details/gt2jxtbrvtn.html

Py:   name = input("请输入：")
来源：http://dali.0kj1m.cn/Article/details/gt2vichnphq.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.yonumen.top/Article/details/gt2vnnsftvp.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.316326.xyz/Article/details/gt2jfxhhrlr.html

TS:   // Node.js：readline 模块
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nygybake.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.hongshengwenyu.top/Article/details/gt2vcqghmjw.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.xuetiantiany.cn/Article/details/gt2elkcgzbf.html

Ruby: gets.chomp
来源：http://dali.jinqigufen.top/Article/details/gt2uwimklhb.html

C#:   Console.ReadLine();
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wqedozjr.html

[A21] 保留指定小数位输出
来源：http://dali.sxryk.cn/Article/details/gt2nfktnaxv.html

Py:   f"{3.14159:.2f}"
来源：http://dali.hongshengwenyu.top/Article/details/gt2jdzweaub.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.yueranfly.top/Article/details/gt2nrwlgfxg.html

JS:   (3.14159).toFixed(2)
来源：http://dali.yongpay.top/Article/details/gt2mxqxehxa.html

TS:   (3.14159).toFixed(2)
来源：http://dali.fengsongda.top/Article/details/gt2zbsdvzdv.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.aibaodan.cn/Article/details/gt2cncwflrb.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxzohtgk.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.jqgufenzy.top/Article/details/gt2evvtbvve.html

C#:   3.14159.ToString("F2")
来源：http://dali.chenjidiqi.icu/Article/details/gt2mxynqxzd.html

[A22] 获取字符串长度
来源：http://dali.xziqi.cn/Article/details/gt2lxodyakb.html

Py:   len(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iddvuxhm.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.jianghu66.top/Article/details/gt2aopouudq.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.daxiang520.top/Article/details/gt2wnkqxrvy.html

TS:   s.length
来源：http://dali.iojbl.cn/Article/details/gt2gxzcpagx.html

Java: s.length()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qyunrfqn.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.hfpthk.cn/Article/details/gt2xywiklws.html

Ruby: s.length
来源：http://dali.xuetiantiany.cn/Article/details/gt2zmaevini.html

C#:   s.Length
来源：http://dali.iojbl.cn/Article/details/gt2gjsqakhc.html

[A23] 大小写转换
来源：http://dali.shuidangran.top/Article/details/gt2kbcwyhbw.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2anrjxmdo.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.aizwys.cn/Article/details/gt2tdgsbsfq.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.daxiang520.top/Article/details/gt2svnsbkly.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.tian-w.cn/Article/details/gt2tbdhugda.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.ivvv.top/Article/details/gt2ydmlmdih.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.ehwqpu.com/Article/details/gt2yxjcncby.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uvpfqqoa.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.daria6918.cn/Article/details/gt2gbwdixxf.html

[A24] 去除首尾空白
来源：http://dali.xylfe.cn/Article/details/gt2mqjztkgk.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.meibo888.top/Article/details/gt2wfwmaugz.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.yanxiufei.cn/Article/details/gt2ptqnwldi.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.c1oappe.top/Article/details/gt2cdmzskyh.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.hnxiangtu.top/Article/details/gt2gshmdyhh.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.pengpengdd.cyou/Article/details/gt2klsdrhat.html

Go:   strings.TrimSpace(s)
来源：http://dali.cashguo.top/Article/details/gt2ojnswsrb.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.zhixingplan.top/Article/details/gt2oblsvmjm.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.guannengcc.top/Article/details/gt2nlzlliec.html

[A25] 字符串比较
来源：http://dali.tanke756.top/Article/details/gt2dotjvsot.html

Py:   s1 == s2; s1 != s2
来源：http://dali.bjfxy.top/Article/details/gt2kpqgrvtj.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.pycfn.com/Article/details/gt2msfzimoh.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zdqjudy.top/Article/details/gt2vtuskcld.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.tianlin.xyz/Article/details/gt2zmztkhtm.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.birdmap.top/Article/details/gt2llkpowlk.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.ivvv.top/Article/details/gt2gtscntcq.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.aibaodan.cn/Article/details/gt2quzdhhrv.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.ppjwa.cn/Article/details/gt2qqasjkeu.html

[A26] 类型转换总览
来源：http://dali.aibaodan.cn/Article/details/gt2mwoncfwl.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.iojbl.cn/Article/details/gt2lhlnwtpp.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.mhx1999.top/Article/details/gt2njqlchqt.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.xinyue.icu/Article/details/gt2hshvopba.html

TS:   Number() String() Boolean() x as number
来源：http://dali.zycfv.cn/Article/details/gt2rrvvxepa.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2idkhllat.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.gotoacloud.top/Article/details/gt2qnlsqqtl.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.mhx1999.top/Article/details/gt2lxzblqjk.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.hnqzz.top/Article/details/gt2iuxgnzmv.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2lunodjvs.html

B. 流程控制
来源：http://dali.jinqigufen.top/Article/details/gt2kisvlbvq.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2hvtdorjs.html

[B01] 条件判断 if / else
来源：http://dali.chenlongwang.top/Article/details/gt2agzonjzl.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.bjfxy.top/Article/details/gt2olwngawn.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.redwolf501.top/Article/details/gt2mhszgehx.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.ydzc1.top/Article/details/gt2ywbzghgz.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.hysaishi.cn/Article/details/gt2timhxyqu.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.dianchejie.cn/Article/details/gt2resxxebt.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.yuanzhike.top/Article/details/gt2fdmzelun.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.sufxvd.cn/Article/details/gt2fgpsyrnn.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.ydzc1.top/Article/details/gt2qpkqpnbh.html

[B02] 多分支 else if / elif
来源：http://dali.hysaishi.cn/Article/details/gt2vbznujda.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.yueranfly.top/Article/details/gt2fnbowybx.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.zhoulong.xyz/Article/details/gt2nnbtxecr.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.316326.xyz/Article/details/gt2xzasfxwx.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.svipenyu.cn/Article/details/gt2ckoobucl.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.sxryk.cn/Article/details/gt2okilpeiv.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.daria6918.cn/Article/details/gt2jccehnzb.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.wangshuangyany.cn/Article/details/gt2pugdkhrf.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zdqjudy.top/Article/details/gt2kqxlgusu.html

[B03] switch / match / case
来源：http://dali.xziqi.cn/Article/details/gt2elfebrkz.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.shzxlz.cn/Article/details/gt2bpbhvaxz.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.hysaishi.cn/Article/details/gt2cintlcpb.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.aizwys.cn/Article/details/gt2yzjtrhqe.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.xylfe.cn/Article/details/gt2nxmqadxu.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.chenzaomai.com/Article/details/gt2sbjobcgb.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dbfafwyp.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ufdjfmpj.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.mhx1999.top/Article/details/gt2jnstlhar.html

[B04] for 计数循环
来源：http://dali.hongshengwenyu.top/Article/details/gt2hvijtaoq.html

Py:   for i in range(10): print(i)
来源：http://dali.yuxming.cn/Article/details/gt2mbkhlzry.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.xinyue.icu/Article/details/gt2lrhdatpx.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yj20258888.top/Article/details/gt2malqcnrk.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.ydzc1.top/Article/details/gt2nzjsuihg.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.aizwys.cn/Article/details/gt2bmgpidte.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.dianchejie.cn/Article/details/gt2yognfbte.html

Ruby: 10.times { |i| puts i }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2njlwcxka.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.meibo888.top/Article/details/gt2ztvhlank.html

[B05] 遍历数组 / 列表
来源：http://dali.sxryk.cn/Article/details/gt2iniumetg.html

Py:   for item in arr: print(item)
来源：http://dali.zhiwuduotai.top/Article/details/gt2hbujwkke.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.ehwqpu.com/Article/details/gt2gocowfpc.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.yonumen.top/Article/details/gt2qtnyoagy.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.jinqigufen.top/Article/details/gt2agyilsrl.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.dianchejie.cn/Article/details/gt2ynikqwje.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.ybcxt.top/Article/details/gt2atytqprq.html

Ruby: arr.each { |item| puts item }
来源：http://dali.snrcjt.cn/Article/details/gt2ykuzyhdz.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2pqrphipf.html

[B06] 遍历字典 / 对象
来源：http://dali.hnxiangtu.top/Article/details/gt2yudfbaak.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.quarkkingdee.top/Article/details/gt2zgozuddd.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.iojbl.cn/Article/details/gt2febwaats.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.cheryme.top/Article/details/gt2wjjaevuc.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.dianchejie.cn/Article/details/gt2lrokfysg.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.daxiang520.top/Article/details/gt2rmhhcswa.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.pengpengdd.cyou/Article/details/gt2botkroel.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.dianchejie.cn/Article/details/gt2bcatitai.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.yuanzhike.top/Article/details/gt2tzpubokf.html

[B07] while 循环
来源：http://dali.hammf.cn/Article/details/gt2gsvzqwmr.html

Py:   while i < 10: i += 1
来源：http://dali.sweek.top/Article/details/gt2uwaegdor.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2mwhsttyj.html

JS:   while (i < 10) { i++; }
来源：http://dali.jiagoushi.top/Article/details/gt2bkbxscpq.html

TS:   while (i < 10) { i++; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2gtnlmgxu.html

Java: while (i < 10) { i++; }
来源：http://dali.jinqigfzy.top/Article/details/gt2cwangjxf.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.jinqigfzy.top/Article/details/gt2btetzpqi.html

Ruby: while i < 10; i += 1; end
来源：http://dali.gotoacloud.top/Article/details/gt2jomnygtn.html

C#:   while (i < 10) { i++; }
来源：http://dali.9152youxi.cn/Article/details/gt2xdemxuxv.html

[B08] do-while（至少执行一次）
来源：http://dali.kuanghao11.cn/Article/details/gt2ifcpfqtx.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.xziqi.cn/Article/details/gt2ucerwocs.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.tian-w.cn/Article/details/gt2xiesanfy.html

JS:   do { i++; } while (i < 10);
来源：http://dali.jqgufenzy.top/Article/details/gt2ifxfeqre.html

TS:   do { i++; } while (i < 10);
来源：http://dali.jinqigufen.top/Article/details/gt2cdtvxihf.html

Java: do { i++; } while (i < 10);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ehnjncnq.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.wangshuangyany.cn/Article/details/gt2mtgftouu.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.cucudq.cn/Article/details/gt2kwywgkzk.html

C#:   do { i++; } while (i < 10);
来源：http://dali.ybcxt.top/Article/details/gt2fbuilbvd.html

[B09] break 与 continue
来源：http://dali.hnxiangtu.top/Article/details/gt2cpbkdkbw.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.pycfn.com/Article/details/gt2hirkxycd.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.yj20258.top/Article/details/gt2dodubwbk.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ybcxt.top/Article/details/gt2wghquecb.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jiagoushi.top/Article/details/gt2sfuducyf.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sysykeji.top/Article/details/gt2uvcbwxhy.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.9152youxi.cn/Article/details/gt2zkivlymi.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yonumen.top/Article/details/gt2vzfncesh.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jianghu66.top/Article/details/gt2vhqfiach.html

[B10] 遍历同时拿索引
来源：http://dali.cashguo.top/Article/details/gt2xzinwttr.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2autrrxnx.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.havefunace.top/Article/details/gt2xeqgjgju.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.xinyue.icu/Article/details/gt2ratjdlmv.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jianghu66.top/Article/details/gt2derdnxmb.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.jlsjyb.cn/Article/details/gt2xvqxszok.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zhixingplan.top/Article/details/gt2ynftbnys.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.wangdashe.top/Article/details/gt2samvaole.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.haohaochexian.top/Article/details/gt2fmqwlcfb.html

[B11] 生成数字序列 / 区间
来源：http://dali.pengpengdd.cyou/Article/details/gt2ucrjdrvy.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhengqikj.top/Article/details/gt2mbyfrrkp.html

PHP:  range(0, 10, 2);
来源：http://dali.jyoumei.cn/Article/details/gt2ocatdady.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.chenjidiqi.icu/Article/details/gt2elcfydje.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.chenjidiqi.icu/Article/details/gt2zoozpkym.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhiwuduotai.top/Article/details/gt2kzzqhrut.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.guannengcc.top/Article/details/gt2yylradtd.html

Ruby: (0...10).step(2).to_a
来源：http://dali.pycfn.com/Article/details/gt2etfskfnk.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.fengsongda.top/Article/details/gt2ujfkcugp.html

[B12] 跳出多层循环
来源：http://dali.wangshuangyany.cn/Article/details/gt2ampflfdy.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.bjfxy.top/Article/details/gt2mgfhwclk.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.ivvv.top/Article/details/gt2jovkxnqi.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yvedp.cn/Article/details/gt2zxvbbupp.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.gotoacloud.top/Article/details/gt2kyqjxgus.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.xuetiantiany.cn/Article/details/gt2yyffhntc.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.sweek.top/Article/details/gt2tjlbdreo.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.smart0.xyz/Article/details/gt2xljgywou.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.xylfe.cn/Article/details/gt2cwlguxza.html

[B13] 判断是否为数字
来源：http://dali.guannengcc.top/Article/details/gt2xsvwhvey.html

Py:   isinstance(x, (int, float))
来源：http://dali.hfpthk.cn/Article/details/gt2wnflhpnu.html

PHP:  is_numeric($x)
来源：http://dali.yuanzhike.top/Article/details/gt2ahezsldv.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yj20258.top/Article/details/gt2uoirnquu.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jiagoushi.top/Article/details/gt2kdgcukri.html

Java: x instanceof Number
来源：http://dali.hfpthk.cn/Article/details/gt2kkclqbdc.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.xuanzx.com/Article/details/gt2qkyftmxy.html

Ruby: x.is_a?(Numeric)
来源：http://dali.sweek.top/Article/details/gt2gyikscok.html

C#:   x is int or double or decimal
来源：http://dali.ehwqpu.com/Article/details/gt2yxzoteob.html

[B14] 判断值是否在集合内
来源：http://dali.ybcxt.top/Article/details/gt2vdxawnsb.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.xylfe.cn/Article/details/gt2kkinopsi.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.cqqwz.cn/Article/details/gt2zqsurkci.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rdelblvo.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yanxiufei.cn/Article/details/gt2wwumunft.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2isgzrnte.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.smart0.xyz/Article/details/gt2vohqmqzo.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.meibo888.top/Article/details/gt2pehezjya.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yj20258.top/Article/details/gt2wzrxsavg.html

[B15] 布尔运算与取反
来源：http://dali.c1oappe.top/Article/details/gt2ghzdfwwa.html

Py:   a and b or not c
来源：http://dali.tianlin.xyz/Article/details/gt2qqzjqnka.html

PHP:  $a && $b || !$c
来源：http://dali.tianlin.xyz/Article/details/gt2xhwodtoo.html

JS:   a && b || !c
来源：http://dali.hysaishi.cn/Article/details/gt2lvegvqwb.html

TS:   a && b || !c
来源：http://dali.chenlongwang.top/Article/details/gt2hmuscpez.html

Java: a && b || !c
来源：http://dali.aibaodan.cn/Article/details/gt2qrzuzuap.html

Go:   a && b || !c
来源：http://dali.sufxvd.cn/Article/details/gt2kfkmkcle.html

Ruby: a && b || !c
来源：http://dali.ehwqpu.com/Article/details/gt2pbmjxciq.html

C#:   a && b || !c
来源：http://dali.yuxming.cn/Article/details/gt2igfvfxng.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tmavkqbj.html

Py:   if not data: return
来源：http://dali.hnqzz.top/Article/details/gt2drdhakjb.html

PHP:  if (!$data) { return; }
来源：http://dali.cucudq.cn/Article/details/gt2tgzdbmnk.html

JS:   if (!data) return;
来源：http://dali.sysykeji.top/Article/details/gt2tdssutae.html

TS:   if (!data) return;
来源：http://dali.aizwys.cn/Article/details/gt2lwqqwmku.html

Java: if (data == null) return;
来源：http://dali.havefunace.top/Article/details/gt2cwhutdsj.html

Go:   if data == nil { return }
来源：http://dali.birdmap.top/Article/details/gt2ldtnfvym.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2ihlzzbom.html

C#:   if (data == null) return;
来源：http://dali.tian-w.cn/Article/details/gt2qotekjfo.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zjhmhmci.html

C. 函数与作用域
来源：http://dali.nwbrower.top/Article/details/gt2lftujulk.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2oyiuhqre.html

[C01] 定义函数
来源：http://dali.yuanzhike.top/Article/details/gt2crbhwozy.html

Py:   def add(a, b): return a + b
来源：http://dali.wangshuangyany.cn/Article/details/gt2hpwtwtll.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.pycfn.com/Article/details/gt2psxdfiia.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.kuanghao11.cn/Article/details/gt2ncgervsa.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.meibo888.top/Article/details/gt2xrivqzfm.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.gotoacloud.top/Article/details/gt2yaiyopdv.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.sweek.top/Article/details/gt2wtydbtzl.html

Ruby: def add(a, b); a + b; end
来源：http://dali.hysaishi.cn/Article/details/gt2qhylnsch.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.daxiang520.top/Article/details/gt2sqfvzusl.html

[C02] 默认参数
来源：http://dali.pengpengdd.cyou/Article/details/gt2bahhnbhg.html

Py:   def greet(name="World"): return name
来源：http://dali.shuidangran.top/Article/details/gt2nvobzpxf.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.ivvv.top/Article/details/gt2ztdwrygu.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.dianchejie.cn/Article/details/gt2ffggfabg.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.ehwqpu.com/Article/details/gt2lcaksjnu.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yuanzhike.top/Article/details/gt2hhhoeceb.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.wangdashe.top/Article/details/gt2lbkxtlan.html

Ruby: def greet(name = "World") = name
来源：http://dali.nanxuanxn.top/Article/details/gt2ikseswce.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yuxming.cn/Article/details/gt2yknwhldd.html

[C03] 可变参数
来源：http://dali.aizwys.cn/Article/details/gt2jhmvsvzg.html

Py:   def total(*args): return sum(args)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zsxiuwbd.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yanxiufei.cn/Article/details/gt2rddeffdz.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.svipenyu.cn/Article/details/gt2knlkflnu.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.smart0.xyz/Article/details/gt2emecbliu.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2alflgqdi.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.ppjwa.cn/Article/details/gt2jwpjdhar.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.0kj1m.cn/Article/details/gt2ujoesyai.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.tanke756.top/Article/details/gt2terfuwfy.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhiwuduotai.top/Article/details/gt2uxlvxvgn.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jqgufenzy.top/Article/details/gt2cfgigvey.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.sxryk.cn/Article/details/gt2hqttaict.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2jyoizpii.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.hongshengwenyu.top/Article/details/gt2bvhdwxno.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.ehwqpu.com/Article/details/gt2ohtahdfh.html

Go:   // 无：用配置结构体参数
来源：http://dali.cashguo.top/Article/details/gt2uiqfsamm.html

Ruby: f(a: 1, b: 2)
来源：http://dali.pycfn.com/Article/details/gt2sqigrksd.html

C#:   f(a: 1, b: 2)
来源：http://dali.ehwqpu.com/Article/details/gt2luhingie.html

[C05] 返回多个值
来源：http://dali.jiagoushi.top/Article/details/gt2fchbftir.html

Py:   return a, b
来源：http://dali.shuidangran.top/Article/details/gt2xpsvhhlv.html

PHP:  return [$a, $b];
来源：http://dali.chenlongwang.top/Article/details/gt2xasdcilh.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.cdnleiting.top/Article/details/gt2tnkjuren.html

TS:   return { a, b };
来源：http://dali.zhoulong.xyz/Article/details/gt2uypcnotu.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.quarkkingdee.top/Article/details/gt2mknsufoy.html

Go:   return a, b
来源：http://dali.mhx1999.top/Article/details/gt2fwuwacnm.html

Ruby: return a, b
来源：http://dali.gotoacloud.top/Article/details/gt2otvcwpjm.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.xuanzx.com/Article/details/gt2nwhifmqj.html

[C06] 匿名函数 / lambda
来源：http://dali.aibaodan.cn/Article/details/gt2kgyskjlv.html

Py:   square = lambda x: x * x
来源：http://dali.jinqigufen.top/Article/details/gt2hcvrjdsr.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.xuetiantiany.cn/Article/details/gt2nixjenno.html

JS:   const square = x => x * x;
来源：http://dali.shuidangran.top/Article/details/gt2mosbosve.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.meibo888.top/Article/details/gt2ppjrjwll.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.tianlin.xyz/Article/details/gt2vshdcqro.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.gzhubu.top/Article/details/gt2ufjgivcr.html

Ruby: square = ->(x) { x * x }
来源：http://dali.chenjidiqi.icu/Article/details/gt2jeejmwuw.html


<!-- 参考信息 -->