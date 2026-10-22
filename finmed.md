代发 wailian999

C#:   // 单行；/* 多行 */
来源：http://dali.hongshengwenyu.top/Article/details/gt2xursohfr.html

[A15] 空值判断与默认值
来源：http://dali.zhixingplan.top/Article/details/gt2upgomchb.html

Py:   value = data or "默认值"
来源：http://dali.sxryk.cn/Article/details/gt2ijbqyygi.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.redwolf501.top/Article/details/gt2illpqfcz.html

JS:   const value = data ?? "默认值";
来源：http://dali.yanxiufei.cn/Article/details/gt2mpxjbnap.html

TS:   const value = data ?? "默认值";
来源：http://dali.guannengcc.top/Article/details/gt2epmthbxi.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.ybcxt.top/Article/details/gt2sltclnbq.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.cheryme.top/Article/details/gt2ghonbfxx.html

Ruby: value = data || "默认值"
来源：http://dali.ivvv.top/Article/details/gt2eavtgtpi.html

C#:   var value = data ?? "默认值";
来源：http://dali.zycfv.cn/Article/details/gt2rrlpmwef.html

[A16] 真假值判断规则
来源：http://dali.jinghuilouyu.cn/Article/details/gt2woggtcji.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2cgirrjfm.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.ybcxt.top/Article/details/gt2wnxnighr.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.zhoulong.xyz/Article/details/gt2llebxrip.html

TS:   if (!x) {}
来源：http://dali.svipenyu.cn/Article/details/gt2uogknofy.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uwxwlbfo.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.tianlin.xyz/Article/details/gt2yepkaryq.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.haohaochexian.top/Article/details/gt2gobtpftu.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.quarkkingdee.top/Article/details/gt2pzojuqkg.html

[A17] 位运算
来源：http://dali.zhixingplan.top/Article/details/gt2jttpfbmz.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jiagoushi.top/Article/details/gt2dyfbshcg.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.gogol.net.cn/Article/details/gt2aejlsrrb.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.tianlin.xyz/Article/details/gt2ldomgkar.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.smart0.xyz/Article/details/gt2wchjwfvv.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.dianchejie.cn/Article/details/gt2qjauhlav.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.nanxinkj.top/Article/details/gt2kfvnqtiw.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.dashuyun.cn/Article/details/gt2xwlwtvfr.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yvedp.cn/Article/details/gt2lxitzccc.html

[A18] 字符与 ASCII 码互转
来源：http://dali.hammf.cn/Article/details/gt2qlmybhkg.html

Py:   ord("A"); chr(65)
来源：http://dali.jinqigufen.top/Article/details/gt2ilfyigsj.html

PHP:  ord("A"); chr(65)
来源：http://dali.kuanghao11.cn/Article/details/gt2lnyfncpe.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.quarkkingdee.top/Article/details/gt2nolbbgaa.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.hysaishi.cn/Article/details/gt2hsrmndca.html

Java: (int) 'A'; (char) 65
来源：http://dali.tanke756.top/Article/details/gt2dlesnltu.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.shzxlz.cn/Article/details/gt2zmztoqih.html

Ruby: "A".ord; 65.chr
来源：http://dali.yueranfly.top/Article/details/gt2cgrvgbnw.html

C#:   (int)'A'; (char)65
来源：http://dali.ppjwa.cn/Article/details/gt2klkojsgt.html

[A19] 交换两个变量
来源：http://dali.ivvv.top/Article/details/gt2fiozbbco.html

Py:   a, b = b, a
来源：http://dali.jqgfzy.top/Article/details/gt2nwiucqyy.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.hammf.cn/Article/details/gt2nmpripgw.html

JS:   [a, b] = [b, a];
来源：http://dali.xuetiantiany.cn/Article/details/gt2ckadywmo.html

TS:   [a, b] = [b, a];
来源：http://dali.aibaodan.cn/Article/details/gt2iwifjlji.html

Java: int t = a; a = b; b = t;
来源：http://dali.nanxinkj.top/Article/details/gt2rzjtxveu.html

Go:   a, b = b, a
来源：http://dali.daxiang520.top/Article/details/gt2ruijegvk.html

Ruby: a, b = b, a
来源：http://dali.pycfn.com/Article/details/gt2imwvphwa.html

C#:   (a, b) = (b, a);
来源：http://dali.mhx1999.top/Article/details/gt2puxuapit.html

[A20] 读取标准输入
来源：http://dali.xziqi.cn/Article/details/gt2iqbeisoz.html

Py:   name = input("请输入：")
来源：http://dali.yangfankeji.com/Article/details/gt2lchihtmt.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.yvedp.cn/Article/details/gt2sepsjoah.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.zycfv.cn/Article/details/gt2vlymjqdu.html

TS:   // Node.js：readline 模块
来源：http://dali.zycfv.cn/Article/details/gt2dcqqgyhz.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.jianghu66.top/Article/details/gt2biywgznr.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.zhengqikj.top/Article/details/gt2wiofufjl.html

Ruby: gets.chomp
来源：http://dali.yuxming.cn/Article/details/gt2gwyszjty.html

C#:   Console.ReadLine();
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nfostlft.html

[A21] 保留指定小数位输出
来源：http://dali.fengsongda.top/Article/details/gt2oqgtoqjv.html

Py:   f"{3.14159:.2f}"
来源：http://dali.daxiang520.top/Article/details/gt2rsvwbjfl.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.shzxlz.cn/Article/details/gt2wsemqipa.html

JS:   (3.14159).toFixed(2)
来源：http://dali.cucudq.cn/Article/details/gt2yunvmdjq.html

TS:   (3.14159).toFixed(2)
来源：http://dali.tian-w.cn/Article/details/gt2zrbjfmtw.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.xinyue.icu/Article/details/gt2hovgmnob.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.ybcxt.top/Article/details/gt2wnpalhkk.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.meibo888.top/Article/details/gt2lohczlfi.html

C#:   3.14159.ToString("F2")
来源：http://dali.pengpengdd.cyou/Article/details/gt2cichuctf.html

[A22] 获取字符串长度
来源：http://dali.ivvv.top/Article/details/gt2xacrveix.html

Py:   len(s)
来源：http://dali.wangdashe.top/Article/details/gt2rqcogejx.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.aibaodan.cn/Article/details/gt2hfcxqfxa.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.hnxiangtu.top/Article/details/gt2bzdjohzm.html

TS:   s.length
来源：http://dali.zhiwuduotai.top/Article/details/gt2alzjkipk.html

Java: s.length()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zmsounfk.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.guowangkeji.top/Article/details/gt2zmnbraod.html

Ruby: s.length
来源：http://dali.ehwqpu.com/Article/details/gt2hbbpoppb.html

C#:   s.Length
来源：http://dali.chenzaomai.com/Article/details/gt2cnlozwnm.html

[A23] 大小写转换
来源：http://dali.jinqigfzy.top/Article/details/gt2nxawxpkh.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.shuidangran.top/Article/details/gt2branxksw.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.gotoacloud.top/Article/details/gt2pceubyhw.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.ivvv.top/Article/details/gt2oecxteok.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.ivvv.top/Article/details/gt2rypzulnf.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.feifeiyinyue.top/Article/details/gt2lszzjhnv.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.hysaishi.cn/Article/details/gt2mynlorjt.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.ydzc1.top/Article/details/gt2cjiopmsn.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.haohaochexian.top/Article/details/gt2nkpzflse.html

[A24] 去除首尾空白
来源：http://dali.havefunace.top/Article/details/gt2embtpwlc.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.yuxming.cn/Article/details/gt2bkyxwoxv.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sitmfbzj.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.jqgufenzy.top/Article/details/gt2hayysmft.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.xuetiantiany.cn/Article/details/gt2qqmzrqsz.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.ehwqpu.com/Article/details/gt2otqaejqb.html

Go:   strings.TrimSpace(s)
来源：http://dali.xziqi.cn/Article/details/gt2rrltnrvw.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.zhijiandao.cn/Article/details/gt2euormjcq.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.gaohongyu789.top/Article/details/gt2nfcfpvoa.html

[A25] 字符串比较
来源：http://dali.xinyue.icu/Article/details/gt2bzqdhuzz.html

Py:   s1 == s2; s1 != s2
来源：http://dali.jinqigfzy.top/Article/details/gt2vqkxuiux.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.yj202588.top/Article/details/gt2wiapsrpc.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.redwolf501.top/Article/details/gt2bwpoodsa.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.0kj1m.cn/Article/details/gt2uscyfyzp.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.yj20258888.top/Article/details/gt2mehrumbr.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ajmpyzpx.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.wangdashe.top/Article/details/gt2xvojraip.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.tianlin.xyz/Article/details/gt2lpjyfzki.html

[A26] 类型转换总览
来源：http://dali.yj20258.top/Article/details/gt2cxddepkt.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.pengpengdd.cyou/Article/details/gt2malenhwl.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.zhoulong.xyz/Article/details/gt2kqoozwns.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.fzhhl.top/Article/details/gt2voooepth.html

TS:   Number() String() Boolean() x as number
来源：http://dali.dashuyun.cn/Article/details/gt2hlcpiilt.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.yvedp.cn/Article/details/gt2htsjrpec.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.gogol.net.cn/Article/details/gt2jrztorgz.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.bjfxy.top/Article/details/gt2pxchjfxe.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.birdmap.top/Article/details/gt2biouqgnt.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2okagqddg.html

B. 流程控制
来源：http://dali.shangyingyoupin.top/Article/details/gt2ojmfeolb.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2ylrtjzbx.html

[B01] 条件判断 if / else
来源：http://dali.hammf.cn/Article/details/gt2hxvmofzt.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.andypj.xyz/Article/details/gt2fjmaqtdh.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.dashuyun.cn/Article/details/gt2rrqedfww.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yuanzhike.top/Article/details/gt2ouafbszm.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yongpay.top/Article/details/gt2wqklnexv.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.jinqigfzy.top/Article/details/gt2znwjeyyl.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.sufxvd.cn/Article/details/gt2fxsxhkdj.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.fzhhl.top/Article/details/gt2slnsnjny.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.hywenlv.cn/Article/details/gt2bwsgvxsb.html

[B02] 多分支 else if / elif
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ivtsswnb.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.tanke756.top/Article/details/gt2ocflgqjn.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mtxpgaeu.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yj202588.top/Article/details/gt2pxnryzis.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.iojbl.cn/Article/details/gt2opuefltw.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bjqpmivs.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.jqgfzy.top/Article/details/gt2ohrlzvls.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.tanke756.top/Article/details/gt2bfynjtos.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.chenzaomai.com/Article/details/gt2xlhhpzes.html

[B03] switch / match / case
来源：http://dali.smart0.xyz/Article/details/gt2xpyafokd.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.aizwys.cn/Article/details/gt2sfewlryh.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.nanxinkj.top/Article/details/gt2uenvyorn.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.quarkkingdee.top/Article/details/gt2kocvvylq.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.gzhubu.top/Article/details/gt2eizztkec.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.fengsongda.top/Article/details/gt2btxlkbzj.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.yongpay.top/Article/details/gt2cguwkqrg.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.9152youxi.cn/Article/details/gt2otdarbbv.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.yangfankeji.com/Article/details/gt2rgdwezpf.html

[B04] for 计数循环
来源：http://dali.yueranfly.top/Article/details/gt2kvppifbn.html

Py:   for i in range(10): print(i)
来源：http://dali.c1oappe.top/Article/details/gt2ytrqxkxr.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.aizwys.cn/Article/details/gt2rsiysvuj.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.316326.xyz/Article/details/gt2oyxsgkvc.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.pycfn.com/Article/details/gt2bynfgvsm.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.zdqjudy.top/Article/details/gt2vrncgrno.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.guannengcc.top/Article/details/gt2iimgrtop.html

Ruby: 10.times { |i| puts i }
来源：http://dali.ehwqpu.com/Article/details/gt2fawpfgrc.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.smart0.xyz/Article/details/gt2iwtxzbcs.html

[B05] 遍历数组 / 列表
来源：http://dali.zhengqikj.top/Article/details/gt2jeilcbgo.html

Py:   for item in arr: print(item)
来源：http://dali.zhongyouzk.top/Article/details/gt2neqtpwnj.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fipwdeyw.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.zdqjudy.top/Article/details/gt2pbjhoxmm.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.meibo888.top/Article/details/gt2knpribhq.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.tianlin.xyz/Article/details/gt2ubyscdsa.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.feifeiyinyue.top/Article/details/gt2oaqcnpzt.html

Ruby: arr.each { |item| puts item }
来源：http://dali.daria6918.cn/Article/details/gt2bnyrxyqj.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.redwolf501.top/Article/details/gt2xhuqswnn.html

[B06] 遍历字典 / 对象
来源：http://dali.ybcxt.top/Article/details/gt2bvrwxhch.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.jlsjyb.cn/Article/details/gt2tqkgphiv.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.yangfankeji.com/Article/details/gt2dppvqpba.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.ydzc1.top/Article/details/gt2ipzmairj.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.ivvv.top/Article/details/gt2bxtfbucs.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2lysqmrgn.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.gzhubu.top/Article/details/gt2nmeqdgfe.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.smart0.xyz/Article/details/gt2cicuwvhk.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.nanxinkj.top/Article/details/gt2fmcgrqer.html

[B07] while 循环
来源：http://dali.sweek.top/Article/details/gt2bfqvaotz.html

Py:   while i < 10: i += 1
来源：http://dali.dianchejie.cn/Article/details/gt2kyarwvhg.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.yueranfly.top/Article/details/gt2xrstfkoo.html

JS:   while (i < 10) { i++; }
来源：http://dali.zhengqikj.top/Article/details/gt2xojhtgnt.html

TS:   while (i < 10) { i++; }
来源：http://dali.ivvv.top/Article/details/gt2izypzdkw.html

Java: while (i < 10) { i++; }
来源：http://dali.iojbl.cn/Article/details/gt2vfylwskh.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.tanke756.top/Article/details/gt2blhgqwac.html

Ruby: while i < 10; i += 1; end
来源：http://dali.gzhubu.top/Article/details/gt2ugzgkqwk.html

C#:   while (i < 10) { i++; }
来源：http://dali.cucudq.cn/Article/details/gt2hzxhlblu.html

[B08] do-while（至少执行一次）
来源：http://dali.yuxming.cn/Article/details/gt2wvyrylhh.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.ehwqpu.com/Article/details/gt2tgffchwr.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.nwbrower.top/Article/details/gt2kbpsnbmk.html

JS:   do { i++; } while (i < 10);
来源：http://dali.hywenlv.cn/Article/details/gt2mmzilkch.html

TS:   do { i++; } while (i < 10);
来源：http://dali.fengsongda.top/Article/details/gt2gkgggyak.html

Java: do { i++; } while (i < 10);
来源：http://dali.andypj.xyz/Article/details/gt2yapqlrpo.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.iojbl.cn/Article/details/gt2wsasrjiw.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.cheryme.top/Article/details/gt2jfjinaop.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zycfv.cn/Article/details/gt2jdcemwlh.html

[B09] break 与 continue
来源：http://dali.sufxvd.cn/Article/details/gt2ilbjkohj.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.zdqjudy.top/Article/details/gt2sipmslnv.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.jiagoushi.top/Article/details/gt2lwfvpnfy.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yvedp.cn/Article/details/gt2xckzuvel.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.fzhhl.top/Article/details/gt2tlkpeeat.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yangfankeji.com/Article/details/gt2ixfmfpkw.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.daxiang520.top/Article/details/gt2ajtirqqa.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.dianchejie.cn/Article/details/gt2hrgyrygf.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.9152youxi.cn/Article/details/gt2fgxhnufm.html

[B10] 遍历同时拿索引
来源：http://dali.yuxming.cn/Article/details/gt2bpazpyyb.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.gogol.net.cn/Article/details/gt2zbkqfhwz.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ixxsciel.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.aibaodan.cn/Article/details/gt2jkvjfbmj.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.chenlongwang.top/Article/details/gt2yzvekuxe.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.sweek.top/Article/details/gt2ukatvoxt.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.bjfxy.top/Article/details/gt2micwglmp.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.jianghu66.top/Article/details/gt2ssaympkh.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.gaohongyu789.top/Article/details/gt2ljavccuh.html

[B11] 生成数字序列 / 区间
来源：http://dali.aizwys.cn/Article/details/gt2mffzxddw.html

Py:   list(range(0, 10, 2))
来源：http://dali.kuanghao11.cn/Article/details/gt2fztploud.html

PHP:  range(0, 10, 2);
来源：http://dali.daria6918.cn/Article/details/gt2jgrmvput.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.tianlin.xyz/Article/details/gt2sxkjljuz.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.cqqwz.cn/Article/details/gt2domynbnf.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.fengsongda.top/Article/details/gt2bmghnrxa.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.jiagoushi.top/Article/details/gt2gdsagvpk.html

Ruby: (0...10).step(2).to_a
来源：http://dali.hammf.cn/Article/details/gt2srdapypm.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.tanke756.top/Article/details/gt2upfnoxzu.html

[B12] 跳出多层循环
来源：http://dali.tanke756.top/Article/details/gt2dtnqcwtf.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.aizwys.cn/Article/details/gt2xeskpsvh.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.iojbl.cn/Article/details/gt2mzawwtqr.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.bjfxy.top/Article/details/gt2wzsznexf.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.cheryme.top/Article/details/gt2ilinzuqi.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.meibo888.top/Article/details/gt2sfnkizom.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.jinqigfzy.top/Article/details/gt2sgqspuqq.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yangfankeji.com/Article/details/gt2xtripgnb.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jqgfzy.top/Article/details/gt2pswtapko.html

[B13] 判断是否为数字
来源：http://dali.yj20258.top/Article/details/gt2tdzvpswv.html

Py:   isinstance(x, (int, float))
来源：http://dali.hammf.cn/Article/details/gt2qlqofiem.html

PHP:  is_numeric($x)
来源：http://dali.ehwqpu.com/Article/details/gt2qqggxizt.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2eowgxbip.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yueranfly.top/Article/details/gt2srbokmle.html

Java: x instanceof Number
来源：http://dali.hnqzz.top/Article/details/gt2macnssfj.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.9152youxi.cn/Article/details/gt2tmyttzvk.html

Ruby: x.is_a?(Numeric)
来源：http://dali.tianlin.xyz/Article/details/gt2vttmhiyq.html

C#:   x is int or double or decimal
来源：http://dali.andypj.xyz/Article/details/gt2iwbtoowq.html

[B14] 判断值是否在集合内
来源：http://dali.xuetiantiany.cn/Article/details/gt2pchwdwiq.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.tianlin.xyz/Article/details/gt2aqjrbgvj.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.guannengcc.top/Article/details/gt2uaiyeahx.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.redwolf501.top/Article/details/gt2iseqvtek.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.aibaodan.cn/Article/details/gt2pufdroiz.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.hnxiangtu.top/Article/details/gt2jereuems.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.yongpay.top/Article/details/gt2vhkysfwx.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jqgfzy.top/Article/details/gt2sgioswfy.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.vqdsnc.cn/Article/details/gt2toejyifl.html

[B15] 布尔运算与取反
来源：http://dali.daxiang520.top/Article/details/gt2exmardco.html

Py:   a and b or not c
来源：http://dali.guannengcc.top/Article/details/gt2roexdbje.html

PHP:  $a && $b || !$c
来源：http://dali.jiagoushi.top/Article/details/gt2yhqdsjms.html

JS:   a && b || !c
来源：http://dali.hysaishi.cn/Article/details/gt2mwtoqegm.html

TS:   a && b || !c
来源：http://dali.zhixingplan.top/Article/details/gt2lrdiyeqs.html

Java: a && b || !c
来源：http://dali.zhengqikj.top/Article/details/gt2ygmioetv.html

Go:   a && b || !c
来源：http://dali.yj20258.top/Article/details/gt2qvfcdpaa.html

Ruby: a && b || !c
来源：http://dali.zdqjudy.top/Article/details/gt2lwdngyie.html

C#:   a && b || !c
来源：http://dali.guannengcc.top/Article/details/gt2xnqxpvwg.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yuxming.cn/Article/details/gt2hbskfmmz.html

Py:   if not data: return
来源：http://dali.chenlongwang.top/Article/details/gt2ukpvrkhz.html

PHP:  if (!$data) { return; }
来源：http://dali.ppjwa.cn/Article/details/gt2vxsgjdik.html

JS:   if (!data) return;
来源：http://dali.xylfe.cn/Article/details/gt2vvcczogz.html

TS:   if (!data) return;
来源：http://dali.cheryme.top/Article/details/gt2bapeuijp.html

Java: if (data == null) return;
来源：http://dali.yanxiufei.cn/Article/details/gt2wiyjppzr.html

Go:   if data == nil { return }
来源：http://dali.cucudq.cn/Article/details/gt2pjyqdwdy.html

Ruby: return if data.nil?
来源：http://dali.yonumen.top/Article/details/gt2fbhjjzbp.html

C#:   if (data == null) return;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oojqvlte.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2ozcceuuk.html

C. 函数与作用域
来源：http://dali.ydzc1.top/Article/details/gt2xcesvffa.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2vrcetouh.html

[C01] 定义函数
来源：http://dali.daria6918.cn/Article/details/gt2vcndyqxe.html

Py:   def add(a, b): return a + b
来源：http://dali.havefunace.top/Article/details/gt2oobzpexs.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xinyue.icu/Article/details/gt2qcinqspw.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jqgufenzy.top/Article/details/gt2hcrecwsi.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yongpay.top/Article/details/gt2zdpzmtyw.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yj202588.top/Article/details/gt2vnszwzrh.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yanxiufei.cn/Article/details/gt2iapheadz.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yueranfly.top/Article/details/gt2uxowbrgz.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yj20258.top/Article/details/gt2dymhdgru.html

[C02] 默认参数
来源：http://dali.vqdsnc.cn/Article/details/gt2ipcnpyoh.html

Py:   def greet(name="World"): return name
来源：http://dali.ivvv.top/Article/details/gt2rcnlruyu.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2yzurdcal.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.aibaodan.cn/Article/details/gt2nrndmewq.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.shuidangran.top/Article/details/gt2ccumotbz.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yj20258.top/Article/details/gt2mfgzrcsw.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jqgufenzy.top/Article/details/gt2npfrdxwb.html

Ruby: def greet(name = "World") = name
来源：http://dali.shzxlz.cn/Article/details/gt2rsamnoey.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yj20258888.top/Article/details/gt2qukdelkj.html

[C03] 可变参数
来源：http://dali.xylfe.cn/Article/details/gt2tzpharpg.html

Py:   def total(*args): return sum(args)
来源：http://dali.cashguo.top/Article/details/gt2abaiejab.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.gzhubu.top/Article/details/gt2esgwcnnl.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jyoumei.cn/Article/details/gt2hhvdgjbp.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.gogol.net.cn/Article/details/gt2kaknzszl.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.svipenyu.cn/Article/details/gt2nndqhajb.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yuanzhike.top/Article/details/gt2huroddmt.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.hysaishi.cn/Article/details/gt2kcvqotno.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zdqjudy.top/Article/details/gt2yszvcogl.html

[C04] 命名参数 / 关键字参数
来源：http://dali.gaohongyu789.top/Article/details/gt2cbozsrhd.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yongpay.top/Article/details/gt2aqhpouns.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jianghu66.top/Article/details/gt2hteaetxa.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2jsptvftc.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.wangdashe.top/Article/details/gt2ipffovdz.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.iojbl.cn/Article/details/gt2powempch.html

Go:   // 无：用配置结构体参数
来源：http://dali.dianchejie.cn/Article/details/gt2exsjwdla.html

Ruby: f(a: 1, b: 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qltkjnmw.html

C#:   f(a: 1, b: 2)
来源：http://dali.ppjwa.cn/Article/details/gt2fwikowft.html

[C05] 返回多个值
来源：http://dali.zhongyouzk.top/Article/details/gt2tazsioxy.html

Py:   return a, b
来源：http://dali.sxryk.cn/Article/details/gt2ejyvtyay.html

PHP:  return [$a, $b];
来源：http://dali.guowangkeji.top/Article/details/gt2fsuqdtga.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhengqikj.top/Article/details/gt2wsvwentn.html

TS:   return { a, b };
来源：http://dali.daria6918.cn/Article/details/gt2evuhahqg.html


<!-- 参考信息 -->