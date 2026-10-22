代发 wailian999

JS:   const value = data ?? "默认值";
来源：http://dali.9152youxi.cn/Article/details/gt2syrqddnp.html

TS:   const value = data ?? "默认值";
来源：http://dali.jianghu66.top/Article/details/gt2cojqpedz.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.jinqigufen.top/Article/details/gt2qdeqnlgy.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.jyoumei.cn/Article/details/gt2aizeqydx.html

Ruby: value = data || "默认值"
来源：http://dali.zhiwuduotai.top/Article/details/gt2sndtmbyf.html

C#:   var value = data ?? "默认值";
来源：http://dali.jqgfzy.top/Article/details/gt2zfqjkxqo.html

[A16] 真假值判断规则
来源：http://dali.yj20258888.top/Article/details/gt2tqjokfyt.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.hammf.cn/Article/details/gt2ycvjmpnt.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.shangyingyoupin.top/Article/details/gt2mdvbslks.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qdmidrfy.html

TS:   if (!x) {}
来源：http://dali.chenzaomai.com/Article/details/gt2vukhrere.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.shzxlz.cn/Article/details/gt2uvtckezw.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.pycfn.com/Article/details/gt2lwfageqp.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.jinqigfzy.top/Article/details/gt2ubtodnxx.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2leycxeah.html

[A17] 位运算
来源：http://dali.pengpengdd.cyou/Article/details/gt2focxmwil.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhiwuduotai.top/Article/details/gt2djocfgxg.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.xziqi.cn/Article/details/gt2bnjrregv.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.andypj.xyz/Article/details/gt2snerinot.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.redwolf501.top/Article/details/gt2zcduxgrz.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yj202588.top/Article/details/gt2nmplzfbf.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.cucudq.cn/Article/details/gt2fzxvybfo.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yj202588.top/Article/details/gt2msyoagcx.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.sysykeji.top/Article/details/gt2wnukxzit.html

[A18] 字符与 ASCII 码互转
来源：http://dali.cdnleiting.top/Article/details/gt2kobvxfnf.html

Py:   ord("A"); chr(65)
来源：http://dali.hysaishi.cn/Article/details/gt2gkefkofo.html

PHP:  ord("A"); chr(65)
来源：http://dali.fzhhl.top/Article/details/gt2ixermqkz.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.wangdashe.top/Article/details/gt2hasjyzol.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zhixingplan.top/Article/details/gt2eacfpccm.html

Java: (int) 'A'; (char) 65
来源：http://dali.shangyingyoupin.top/Article/details/gt2fgdxeldn.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vkunccku.html

Ruby: "A".ord; 65.chr
来源：http://dali.hongshengwenyu.top/Article/details/gt2cbrgjzhu.html

C#:   (int)'A'; (char)65
来源：http://dali.cashguo.top/Article/details/gt2wgnaiwqd.html

[A19] 交换两个变量
来源：http://dali.jyoumei.cn/Article/details/gt2layttmkf.html

Py:   a, b = b, a
来源：http://dali.tian-w.cn/Article/details/gt2razhiaoq.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.shangyingyoupin.top/Article/details/gt2ikvfuqdo.html

JS:   [a, b] = [b, a];
来源：http://dali.guowangkeji.top/Article/details/gt2egumgujo.html

TS:   [a, b] = [b, a];
来源：http://dali.sufxvd.cn/Article/details/gt2aggfabxd.html

Java: int t = a; a = b; b = t;
来源：http://dali.zhijiandao.cn/Article/details/gt2rnzfuqtc.html

Go:   a, b = b, a
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2czgkjqal.html

Ruby: a, b = b, a
来源：http://dali.zhongyouzk.top/Article/details/gt2amsfffkm.html

C#:   (a, b) = (b, a);
来源：http://dali.yj20258888.top/Article/details/gt2izzbyaxr.html

[A20] 读取标准输入
来源：http://dali.zycfv.cn/Article/details/gt2cqwpaqqs.html

Py:   name = input("请输入：")
来源：http://dali.aizwys.cn/Article/details/gt2dwkprkgt.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qdvvatiy.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.xziqi.cn/Article/details/gt2wojjorjh.html

TS:   // Node.js：readline 模块
来源：http://dali.nwbrower.top/Article/details/gt2citpecwc.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.gotoacloud.top/Article/details/gt2nfmlmywk.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.0kj1m.cn/Article/details/gt2pnqqumlb.html

Ruby: gets.chomp
来源：http://dali.haohaochexian.top/Article/details/gt2eplezths.html

C#:   Console.ReadLine();
来源：http://dali.sysykeji.top/Article/details/gt2jglxkbox.html

[A21] 保留指定小数位输出
来源：http://dali.316326.xyz/Article/details/gt2mjwxzzwb.html

Py:   f"{3.14159:.2f}"
来源：http://dali.hnxiangtu.top/Article/details/gt2iffrvcxd.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.zhoulong.xyz/Article/details/gt2clmdigrx.html

JS:   (3.14159).toFixed(2)
来源：http://dali.fzhhl.top/Article/details/gt2xhfxvqsd.html

TS:   (3.14159).toFixed(2)
来源：http://dali.zhixingplan.top/Article/details/gt2yjadyksh.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.guowangkeji.top/Article/details/gt2qasffjsy.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kamnhnqi.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eywpbbfo.html

C#:   3.14159.ToString("F2")
来源：http://dali.jianghu66.top/Article/details/gt2bzoiefxu.html

[A22] 获取字符串长度
来源：http://dali.wangshuangyany.cn/Article/details/gt2rbkgveyy.html

Py:   len(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ivwrbtic.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.sweek.top/Article/details/gt2tcsotnom.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.tian-w.cn/Article/details/gt2ahtpiiff.html

TS:   s.length
来源：http://dali.hfpthk.cn/Article/details/gt2invrqdsq.html

Java: s.length()
来源：http://dali.wangdashe.top/Article/details/gt2vmjtljxg.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.xylfe.cn/Article/details/gt2lteijdrb.html

Ruby: s.length
来源：http://dali.gzhubu.top/Article/details/gt2zqkuehmr.html

C#:   s.Length
来源：http://dali.nwbrower.top/Article/details/gt2qedcwiaw.html

[A23] 大小写转换
来源：http://dali.cheryme.top/Article/details/gt2tqmonwng.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.kuanghao11.cn/Article/details/gt2sjwxalbw.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.hnqzz.top/Article/details/gt2pfaquyvk.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.9152youxi.cn/Article/details/gt2qwumsyqx.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2euogizuq.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.ydzc1.top/Article/details/gt2uemytuys.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.jiagoushi.top/Article/details/gt2wbzuwmtm.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.wangdashe.top/Article/details/gt2fydtczft.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.hnqzz.top/Article/details/gt2ciimthcy.html

[A24] 去除首尾空白
来源：http://dali.snrcjt.cn/Article/details/gt2fkjqyqeg.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.xuanzx.com/Article/details/gt2glxsswwb.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2arnzlfvu.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.cheryme.top/Article/details/gt2pbzachjf.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.jianghu66.top/Article/details/gt2xrchotou.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.bjfxy.top/Article/details/gt2rxdpzmso.html

Go:   strings.TrimSpace(s)
来源：http://dali.birdmap.top/Article/details/gt2vmkubmwt.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.pycfn.com/Article/details/gt2jwdumaie.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.c1oappe.top/Article/details/gt2gkjhyejv.html

[A25] 字符串比较
来源：http://dali.hammf.cn/Article/details/gt2wnccoylw.html

Py:   s1 == s2; s1 != s2
来源：http://dali.quarkkingdee.top/Article/details/gt2tgzljpmg.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.zhongyouzk.top/Article/details/gt2lmpbpncd.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.birdmap.top/Article/details/gt2gepmpxdw.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.jqgfzy.top/Article/details/gt2sydjdfim.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.yangfankeji.com/Article/details/gt2flazcvjv.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.redwolf501.top/Article/details/gt2dvnfdeod.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.ppjwa.cn/Article/details/gt2ldwocrej.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ujdlbkoe.html

[A26] 类型转换总览
来源：http://dali.fengsongda.top/Article/details/gt2ryfbdtdt.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.shangyingyoupin.top/Article/details/gt2sjeslzdc.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yefygyzs.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.jiagoushi.top/Article/details/gt2zthldrab.html

TS:   Number() String() Boolean() x as number
来源：http://dali.hongshengwenyu.top/Article/details/gt2yylhfwou.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.ivvv.top/Article/details/gt2shlzjzkm.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.sufxvd.cn/Article/details/gt2rdbfmrgr.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.sufxvd.cn/Article/details/gt2dadzfgky.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.zhixingplan.top/Article/details/gt2oavvkmzx.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2rsfxujzu.html

B. 流程控制
来源：http://dali.jianghu66.top/Article/details/gt2basgymwa.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2swmxcawx.html

[B01] 条件判断 if / else
来源：http://dali.zhongyouzk.top/Article/details/gt2tajtbtlq.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.ehwqpu.com/Article/details/gt2ctgllnch.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.mhx1999.top/Article/details/gt2planxhmi.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.0kj1m.cn/Article/details/gt2ptinmkhr.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.daria6918.cn/Article/details/gt2ynvbvvjb.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.jinqigufen.top/Article/details/gt2azcyohwe.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.hywenlv.cn/Article/details/gt2nbiqdqng.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.vqdsnc.cn/Article/details/gt2wvretcww.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.meibo888.top/Article/details/gt2hxwngcrc.html

[B02] 多分支 else if / elif
来源：http://dali.redwolf501.top/Article/details/gt2zblzrzru.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.hnxiangtu.top/Article/details/gt2bwrxwfgw.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.zdqjudy.top/Article/details/gt2csoikeud.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.haohaochexian.top/Article/details/gt2xofugekn.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jianghu66.top/Article/details/gt2cipujxol.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.havefunace.top/Article/details/gt2lqmyzkby.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.yj202588.top/Article/details/gt2nyjugjkm.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.dianchejie.cn/Article/details/gt2mmjtuaop.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.fzhhl.top/Article/details/gt2ldogfhht.html

[B03] switch / match / case
来源：http://dali.yangfankeji.com/Article/details/gt2jliywmgt.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.yj20258.top/Article/details/gt2xuawdifo.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.cucudq.cn/Article/details/gt2ukpilqip.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.ppjwa.cn/Article/details/gt2mxbtpeub.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uekrpmgw.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.sweek.top/Article/details/gt2djbpnpqr.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.kuanghao11.cn/Article/details/gt2phuiacdq.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.hammf.cn/Article/details/gt2znvlzkbx.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.9152youxi.cn/Article/details/gt2wxuxrygv.html

[B04] for 计数循环
来源：http://dali.smart0.xyz/Article/details/gt2gcimyljx.html

Py:   for i in range(10): print(i)
来源：http://dali.chenjidiqi.icu/Article/details/gt2bxbhxeko.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.0kj1m.cn/Article/details/gt2eigylnzj.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.sufxvd.cn/Article/details/gt2ygoomtrk.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.316326.xyz/Article/details/gt2diqzdxpx.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.9152youxi.cn/Article/details/gt2fufqvvri.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.xuanzx.com/Article/details/gt2zdgpnnfa.html

Ruby: 10.times { |i| puts i }
来源：http://dali.hnxiangtu.top/Article/details/gt2szcfchqq.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.vqdsnc.cn/Article/details/gt2zqgignth.html

[B05] 遍历数组 / 列表
来源：http://dali.cucudq.cn/Article/details/gt2kemjqbae.html

Py:   for item in arr: print(item)
来源：http://dali.jianghu66.top/Article/details/gt2yccllfht.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.xylfe.cn/Article/details/gt2zbapjyne.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.shzxlz.cn/Article/details/gt2zjaapwwi.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.ehwqpu.com/Article/details/gt2cborcmgm.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.gogol.net.cn/Article/details/gt2tdzyoiaw.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gegnvdho.html

Ruby: arr.each { |item| puts item }
来源：http://dali.gzhubu.top/Article/details/gt2qtjpobqy.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.hnxiangtu.top/Article/details/gt2ryogyqqn.html

[B06] 遍历字典 / 对象
来源：http://dali.jinqigfzy.top/Article/details/gt2joxegtgq.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.9152youxi.cn/Article/details/gt2hakkqwve.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.jqgfzy.top/Article/details/gt2jldbzzup.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.tanke756.top/Article/details/gt2uqmukumt.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xwlyowod.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.shzxlz.cn/Article/details/gt2kpgiojtj.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.jianghu66.top/Article/details/gt2dbftigph.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.zycfv.cn/Article/details/gt2gwqginpp.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.jiagoushi.top/Article/details/gt2eyyfrhvp.html

[B07] while 循环
来源：http://dali.havefunace.top/Article/details/gt2vyflchag.html

Py:   while i < 10: i += 1
来源：http://dali.fzhhl.top/Article/details/gt2zuenqtwu.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.aizwys.cn/Article/details/gt2tsudpnyp.html

JS:   while (i < 10) { i++; }
来源：http://dali.haohaochexian.top/Article/details/gt2wradbexk.html

TS:   while (i < 10) { i++; }
来源：http://dali.nanxuanxn.top/Article/details/gt2wktrazkp.html

Java: while (i < 10) { i++; }
来源：http://dali.aibaodan.cn/Article/details/gt2ueeupdqr.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.316326.xyz/Article/details/gt2iauovcap.html

Ruby: while i < 10; i += 1; end
来源：http://dali.wangshuangyany.cn/Article/details/gt2fhdpkwxu.html

C#:   while (i < 10) { i++; }
来源：http://dali.xuanzx.com/Article/details/gt2qtiambab.html

[B08] do-while（至少执行一次）
来源：http://dali.fengsongda.top/Article/details/gt2nhwjkiqm.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.sufxvd.cn/Article/details/gt2xefbhhvv.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.shzxlz.cn/Article/details/gt2svpbyong.html

JS:   do { i++; } while (i < 10);
来源：http://dali.ydzc1.top/Article/details/gt2xktcbijo.html

TS:   do { i++; } while (i < 10);
来源：http://dali.redwolf501.top/Article/details/gt2naczyyxp.html

Java: do { i++; } while (i < 10);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2twzwxllu.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.jinqigufen.top/Article/details/gt2fqkoxulg.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.ivvv.top/Article/details/gt2tepuaeai.html

C#:   do { i++; } while (i < 10);
来源：http://dali.yangfankeji.com/Article/details/gt2bsdupucq.html

[B09] break 与 continue
来源：http://dali.birdmap.top/Article/details/gt2qpqssmua.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vukqczcc.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.aizwys.cn/Article/details/gt2jzrihkbg.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.svipenyu.cn/Article/details/gt2jyvvyqut.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ydzc1.top/Article/details/gt2cqaryiyo.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2ikoakhnk.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zvrqjnyq.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yj20258888.top/Article/details/gt2rrcfwznm.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.nanxinkj.top/Article/details/gt2dwiiidse.html

[B10] 遍历同时拿索引
来源：http://dali.daxiang520.top/Article/details/gt2qhbfnfgo.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.ybcxt.top/Article/details/gt2veycyuzx.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.smart0.xyz/Article/details/gt2nouquotz.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.wangshuangyany.cn/Article/details/gt2ejzbtkvb.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.xylfe.cn/Article/details/gt2fxeqevwe.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.hnxiangtu.top/Article/details/gt2qkvkyjgb.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.chenlongwang.top/Article/details/gt2ikpfvddh.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.cdnleiting.top/Article/details/gt2todanueo.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.zhongyouzk.top/Article/details/gt2xjoauioe.html

[B11] 生成数字序列 / 区间
来源：http://dali.jianghu66.top/Article/details/gt2ducefyan.html

Py:   list(range(0, 10, 2))
来源：http://dali.havefunace.top/Article/details/gt2sknprwms.html

PHP:  range(0, 10, 2);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wnbgjrqp.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zycfv.cn/Article/details/gt2wxtgjuyo.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.cqqwz.cn/Article/details/gt2nzgveaft.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.fengsongda.top/Article/details/gt2xisgcqdc.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.haohaochexian.top/Article/details/gt2atthmruv.html

Ruby: (0...10).step(2).to_a
来源：http://dali.mhx1999.top/Article/details/gt2crnjfeqk.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.gotoacloud.top/Article/details/gt2agkyqbag.html

[B12] 跳出多层循环
来源：http://dali.sufxvd.cn/Article/details/gt2gonchxia.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.mhx1999.top/Article/details/gt2oemnpztl.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.sufxvd.cn/Article/details/gt2wpljhfdw.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.pengpengdd.cyou/Article/details/gt2xuekkeue.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.tanke756.top/Article/details/gt2ftfwvbrl.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.pengpengdd.cyou/Article/details/gt2vymrmipr.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rzcnhret.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.cheryme.top/Article/details/gt2medqshep.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.316326.xyz/Article/details/gt2zzazdupv.html

[B13] 判断是否为数字
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gybfnkyb.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhiwuduotai.top/Article/details/gt2ehcdzozd.html

PHP:  is_numeric($x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2hjqnzhbi.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.mhx1999.top/Article/details/gt2jitmlutx.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.cqqwz.cn/Article/details/gt2emwsasrm.html

Java: x instanceof Number
来源：http://dali.hywenlv.cn/Article/details/gt2bxhhvqeo.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.andypj.xyz/Article/details/gt2veopetpp.html

Ruby: x.is_a?(Numeric)
来源：http://dali.hysaishi.cn/Article/details/gt2bbxuzhlt.html

C#:   x is int or double or decimal
来源：http://dali.yanxiufei.cn/Article/details/gt2bhwouksz.html

[B14] 判断值是否在集合内
来源：http://dali.jyoumei.cn/Article/details/gt2gdttlhrj.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yj202588.top/Article/details/gt2iklkasci.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.mhx1999.top/Article/details/gt2xpjznxai.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jyoumei.cn/Article/details/gt2cylcjxwf.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jyoumei.cn/Article/details/gt2kumjiwik.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.quarkkingdee.top/Article/details/gt2oqgzfehq.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.yvedp.cn/Article/details/gt2bboqupoi.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jqgufenzy.top/Article/details/gt2vyppcngs.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jqgfzy.top/Article/details/gt2ibkamtvo.html

[B15] 布尔运算与取反
来源：http://dali.kuanghao11.cn/Article/details/gt2zmwogtlz.html

Py:   a and b or not c
来源：http://dali.yuxming.cn/Article/details/gt2kyumyyft.html

PHP:  $a && $b || !$c
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mftuyoam.html

JS:   a && b || !c
来源：http://dali.gzhubu.top/Article/details/gt2azmcvywa.html

TS:   a && b || !c
来源：http://dali.gogol.net.cn/Article/details/gt2zduldyvc.html

Java: a && b || !c
来源：http://dali.fengsongda.top/Article/details/gt2uqdwfarb.html

Go:   a && b || !c
来源：http://dali.chenlongwang.top/Article/details/gt2tmcnbtky.html

Ruby: a && b || !c
来源：http://dali.cdnleiting.top/Article/details/gt2fnxzscqj.html

C#:   a && b || !c
来源：http://dali.zhengqikj.top/Article/details/gt2hhegjviw.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.xziqi.cn/Article/details/gt2bbumexqn.html

Py:   if not data: return
来源：http://dali.chenzaomai.com/Article/details/gt2uzabzqcj.html

PHP:  if (!$data) { return; }
来源：http://dali.jianghu66.top/Article/details/gt2ggjndmpk.html

JS:   if (!data) return;
来源：http://dali.birdmap.top/Article/details/gt2wilcvhut.html

TS:   if (!data) return;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2udklvvgd.html

Java: if (data == null) return;
来源：http://dali.gogol.net.cn/Article/details/gt2vrvkdnyz.html

Go:   if data == nil { return }
来源：http://dali.tian-w.cn/Article/details/gt2bvaikwoq.html

Ruby: return if data.nil?
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nyyvdqcj.html

C#:   if (data == null) return;
来源：http://dali.wangshuangyany.cn/Article/details/gt2lhxqrjwb.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2dalwpjta.html

C. 函数与作用域
来源：http://dali.hfpthk.cn/Article/details/gt2lacdegyj.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2oxcjfqvb.html

[C01] 定义函数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hdesokln.html

Py:   def add(a, b): return a + b
来源：http://dali.zhixingplan.top/Article/details/gt2hpokzbma.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2crjpdbuj.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2edvhgnpi.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xinyue.icu/Article/details/gt2obgapikn.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.nanxuanxn.top/Article/details/gt2yfdqnlyq.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.ydzc1.top/Article/details/gt2vuxrwcej.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yvedp.cn/Article/details/gt2cwgbkomy.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.c1oappe.top/Article/details/gt2yaqniodh.html

[C02] 默认参数
来源：http://dali.yvedp.cn/Article/details/gt2prjxwfzo.html

Py:   def greet(name="World"): return name
来源：http://dali.andypj.xyz/Article/details/gt2qvcltety.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.cdnleiting.top/Article/details/gt2ktffpudb.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.shzxlz.cn/Article/details/gt2cdhzbhte.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.hywenlv.cn/Article/details/gt2yilzabfk.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.svipenyu.cn/Article/details/gt2iwfitech.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.fzhhl.top/Article/details/gt2lpqbfyxr.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhengqikj.top/Article/details/gt2cafiovmp.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.vqdsnc.cn/Article/details/gt2ssqajsbt.html

[C03] 可变参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bjxcxqfx.html

Py:   def total(*args): return sum(args)
来源：http://dali.yj20258.top/Article/details/gt2asdcgxxz.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2vtgqwkwl.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cdnleiting.top/Article/details/gt2rwipjqcj.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yuanzhike.top/Article/details/gt2uggtjrxl.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.svipenyu.cn/Article/details/gt2aejtxjwj.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jqgufenzy.top/Article/details/gt2wdmkxsqe.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yuanzhike.top/Article/details/gt2gurezcso.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.xylfe.cn/Article/details/gt2lmjyyuiq.html

[C04] 命名参数 / 关键字参数
来源：http://dali.feifeiyinyue.top/Article/details/gt2qfqjecvl.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.hysaishi.cn/Article/details/gt2fxuqooia.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jqgufenzy.top/Article/details/gt2kyndjxhz.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jyoumei.cn/Article/details/gt2atgvgswa.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yanxiufei.cn/Article/details/gt2vslolnwp.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yj202588.top/Article/details/gt2kwiulrbg.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhoulong.xyz/Article/details/gt2hdegkesb.html

Ruby: f(a: 1, b: 2)
来源：http://dali.sxryk.cn/Article/details/gt2naflelwz.html

C#:   f(a: 1, b: 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cbigjrjf.html

[C05] 返回多个值
来源：http://dali.jyoumei.cn/Article/details/gt2luxyesgr.html

Py:   return a, b
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fnfoxeuv.html

PHP:  return [$a, $b];
来源：http://dali.aibaodan.cn/Article/details/gt2enjmlhwc.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jlsjyb.cn/Article/details/gt2nduzkish.html

TS:   return { a, b };
来源：http://dali.0kj1m.cn/Article/details/gt2tuxlssch.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yuanzhike.top/Article/details/gt2ekshsovx.html

Go:   return a, b
来源：http://dali.xinyue.icu/Article/details/gt2kjchgrxz.html

Ruby: return a, b
来源：http://dali.sxryk.cn/Article/details/gt2ryvhtiop.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.gogol.net.cn/Article/details/gt2bqpkuami.html


<!-- 参考信息 -->