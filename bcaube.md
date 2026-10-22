代发 wailian999

JS:   const value = data ?? "默认值";
来源：http://dali.sweek.top/Article/details/gt2qzkyuura.html

TS:   const value = data ?? "默认值";
来源：http://dali.guowangkeji.top/Article/details/gt2mhnychtm.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.ivvv.top/Article/details/gt2ummmvvhk.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.9152youxi.cn/Article/details/gt2axeyhwsu.html

Ruby: value = data || "默认值"
来源：http://dali.hysaishi.cn/Article/details/gt2kduskkmi.html

C#:   var value = data ?? "默认值";
来源：http://dali.shzxlz.cn/Article/details/gt2temzjgiy.html

[A16] 真假值判断规则
来源：http://dali.hfpthk.cn/Article/details/gt2sjnuxphb.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhiwuduotai.top/Article/details/gt2llulgpzg.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.zhengqikj.top/Article/details/gt2obtmknkh.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.fengsongda.top/Article/details/gt2wycdfgqu.html

TS:   if (!x) {}
来源：http://dali.nanxinkj.top/Article/details/gt2kyyfdfys.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.jqgfzy.top/Article/details/gt2nqvuuofa.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.tanke756.top/Article/details/gt2ayaodgtu.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.yueranfly.top/Article/details/gt2yhtqfgzk.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.yonumen.top/Article/details/gt2rtyhdsex.html

[A17] 位运算
来源：http://dali.wangdashe.top/Article/details/gt2obpqkbwm.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.cdnleiting.top/Article/details/gt2nztetycp.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.hnqzz.top/Article/details/gt2cflqvkde.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xylfe.cn/Article/details/gt2egtwuuvp.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.shzxlz.cn/Article/details/gt2nceokhtq.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jiagoushi.top/Article/details/gt2qsvtkesm.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.daria6918.cn/Article/details/gt2kqrxsfaf.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jiagoushi.top/Article/details/gt2nyiwodeb.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hnxiangtu.top/Article/details/gt2jpapitvp.html

[A18] 字符与 ASCII 码互转
来源：http://dali.daxiang520.top/Article/details/gt2qlbibdjj.html

Py:   ord("A"); chr(65)
来源：http://dali.yj20258888.top/Article/details/gt2dvmmxbkv.html

PHP:  ord("A"); chr(65)
来源：http://dali.sufxvd.cn/Article/details/gt2rtdlawdz.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.hammf.cn/Article/details/gt2pgersfor.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.kuanghao11.cn/Article/details/gt2fwbrwtqr.html

Java: (int) 'A'; (char) 65
来源：http://dali.ybcxt.top/Article/details/gt2seeapfgl.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.yueranfly.top/Article/details/gt2lnmsiugs.html

Ruby: "A".ord; 65.chr
来源：http://dali.yvedp.cn/Article/details/gt2rirplnnl.html

C#:   (int)'A'; (char)65
来源：http://dali.yj202588.top/Article/details/gt2yvgpjbkh.html

[A19] 交换两个变量
来源：http://dali.yuanzhike.top/Article/details/gt2cqropmaw.html

Py:   a, b = b, a
来源：http://dali.zhengqikj.top/Article/details/gt2syqryelj.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.havefunace.top/Article/details/gt2udjpeopr.html

JS:   [a, b] = [b, a];
来源：http://dali.sufxvd.cn/Article/details/gt2qnfcesen.html

TS:   [a, b] = [b, a];
来源：http://dali.jinqigufen.top/Article/details/gt2yxyngsom.html

Java: int t = a; a = b; b = t;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dkypbalo.html

Go:   a, b = b, a
来源：http://dali.yangfankeji.com/Article/details/gt2wrypqwes.html

Ruby: a, b = b, a
来源：http://dali.chenlongwang.top/Article/details/gt2xhjcdrzl.html

C#:   (a, b) = (b, a);
来源：http://dali.hfpthk.cn/Article/details/gt2zruqemwo.html

[A20] 读取标准输入
来源：http://dali.hnqzz.top/Article/details/gt2rxuprmqz.html

Py:   name = input("请输入：")
来源：http://dali.bjfxy.top/Article/details/gt2jlgsgwma.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.zycfv.cn/Article/details/gt2nubgdtyy.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.tian-w.cn/Article/details/gt2fkhjebrg.html

TS:   // Node.js：readline 模块
来源：http://dali.sysykeji.top/Article/details/gt2kphfvpqk.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.birdmap.top/Article/details/gt2xsqgcuzv.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.0kj1m.cn/Article/details/gt2geoasjni.html

Ruby: gets.chomp
来源：http://dali.hongshengwenyu.top/Article/details/gt2pcowydyz.html

C#:   Console.ReadLine();
来源：http://dali.guowangkeji.top/Article/details/gt2nunhqnjq.html

[A21] 保留指定小数位输出
来源：http://dali.sufxvd.cn/Article/details/gt2farccyny.html

Py:   f"{3.14159:.2f}"
来源：http://dali.jqgfzy.top/Article/details/gt2brywgvhi.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.chenlongwang.top/Article/details/gt2oswltbjb.html

JS:   (3.14159).toFixed(2)
来源：http://dali.zhixingplan.top/Article/details/gt2jnonlmew.html

TS:   (3.14159).toFixed(2)
来源：http://dali.zhongyouzk.top/Article/details/gt2ygxesblc.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.shangyingyoupin.top/Article/details/gt2hbqpinkd.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.iojbl.cn/Article/details/gt2flzykxvj.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zalycfar.html

C#:   3.14159.ToString("F2")
来源：http://dali.tanke756.top/Article/details/gt2jsaxkgxs.html

[A22] 获取字符串长度
来源：http://dali.pengpengdd.cyou/Article/details/gt2soelwqhm.html

Py:   len(s)
来源：http://dali.quarkkingdee.top/Article/details/gt2hvhueorl.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.zhengqikj.top/Article/details/gt2owslgfdb.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.yongpay.top/Article/details/gt2zjbfwwmg.html

TS:   s.length
来源：http://dali.fzhhl.top/Article/details/gt2cuxeruda.html

Java: s.length()
来源：http://dali.hnxiangtu.top/Article/details/gt2fyzjnuek.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2geurmaqy.html

Ruby: s.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cmwsawwr.html

C#:   s.Length
来源：http://dali.sweek.top/Article/details/gt2xualdfux.html

[A23] 大小写转换
来源：http://dali.feifeiyinyue.top/Article/details/gt2gijvinfi.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.cqqwz.cn/Article/details/gt2mmnqbkvv.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.yanxiufei.cn/Article/details/gt2rbhkfzbl.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.vqdsnc.cn/Article/details/gt2xpxbkykj.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.smart0.xyz/Article/details/gt2fmqmnbwo.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.svipenyu.cn/Article/details/gt2xmgslsgk.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2nljuaeez.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.vqdsnc.cn/Article/details/gt2hhshlzol.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ajpzwisj.html

[A24] 去除首尾空白
来源：http://dali.sysykeji.top/Article/details/gt2wbcwbddp.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.haohaochexian.top/Article/details/gt2iaewndtx.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.xylfe.cn/Article/details/gt2gedkxjcq.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.quarkkingdee.top/Article/details/gt2nfctfmbx.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yvztzudt.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.aizwys.cn/Article/details/gt2hoqmxlit.html

Go:   strings.TrimSpace(s)
来源：http://dali.nanxinkj.top/Article/details/gt2kmahqeuw.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.0kj1m.cn/Article/details/gt2kvuytgpx.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.ppjwa.cn/Article/details/gt2qkmccwpw.html

[A25] 字符串比较
来源：http://dali.yuanzhike.top/Article/details/gt2yybcsytu.html

Py:   s1 == s2; s1 != s2
来源：http://dali.ppjwa.cn/Article/details/gt2jixenxmj.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.fzhhl.top/Article/details/gt2xpjyuftr.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.sxryk.cn/Article/details/gt2oddjkpyy.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.tianlin.xyz/Article/details/gt2jbbkvqig.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.jiagoushi.top/Article/details/gt2oraaknoa.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qfypbtbo.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.xuanzx.com/Article/details/gt2riliyoqz.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.birdmap.top/Article/details/gt2ilvpohff.html

[A26] 类型转换总览
来源：http://dali.quarkkingdee.top/Article/details/gt2xxskuwvp.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.yuanzhike.top/Article/details/gt2seqfgtbq.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.tianlin.xyz/Article/details/gt2avoadepw.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.tianlin.xyz/Article/details/gt2ywusdfwy.html

TS:   Number() String() Boolean() x as number
来源：http://dali.jlsjyb.cn/Article/details/gt2gpfohvrc.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.bjfxy.top/Article/details/gt2bwrtzlwn.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.nanxuanxn.top/Article/details/gt2bjdtybvw.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.yueranfly.top/Article/details/gt2wgbwrsfr.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.daxiang520.top/Article/details/gt2etmgqimb.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iktxbhbl.html

B. 流程控制
来源：http://dali.yuanzhike.top/Article/details/gt2bvrucbpm.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2iqbrocbh.html

[B01] 条件判断 if / else
来源：http://dali.tanke756.top/Article/details/gt2yoemuecg.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.yvedp.cn/Article/details/gt2upovkcwc.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hcxhlpok.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.shangyingyoupin.top/Article/details/gt2pogvawep.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yj20258888.top/Article/details/gt2upznympk.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.sweek.top/Article/details/gt2pzecsaxb.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zedpqyrs.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.zhiwuduotai.top/Article/details/gt2gfroqvij.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.fzhhl.top/Article/details/gt2uxgkzhtd.html

[B02] 多分支 else if / elif
来源：http://dali.tianlin.xyz/Article/details/gt2wwawhwwd.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.zhiwuduotai.top/Article/details/gt2ncybndzi.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.ehwqpu.com/Article/details/gt2itczcjxl.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cucudq.cn/Article/details/gt2bckwwjys.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.birdmap.top/Article/details/gt2zpxrjpzq.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ivvv.top/Article/details/gt2xkcuxbcn.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.nwbrower.top/Article/details/gt2ygvxyxbi.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ktuamiam.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.0kj1m.cn/Article/details/gt2uvooetsb.html

[B03] switch / match / case
来源：http://dali.zycfv.cn/Article/details/gt2jzejrewd.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.shzxlz.cn/Article/details/gt2bvmayryb.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.jyoumei.cn/Article/details/gt2mziklgjw.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.daxiang520.top/Article/details/gt2zxzycyvc.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lcmwcisc.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2mfutxmho.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.snrcjt.cn/Article/details/gt2xkymvzwf.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.sufxvd.cn/Article/details/gt2bhntnxch.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.sweek.top/Article/details/gt2izprevyk.html

[B04] for 计数循环
来源：http://dali.jinqigfzy.top/Article/details/gt2iyqzbjwp.html

Py:   for i in range(10): print(i)
来源：http://dali.bjfxy.top/Article/details/gt2rzyubdlq.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.pycfn.com/Article/details/gt2ymvnimue.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yueranfly.top/Article/details/gt2ooyfaefe.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.mhx1999.top/Article/details/gt2lxjjjtup.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.dashuyun.cn/Article/details/gt2bdwcqvad.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.havefunace.top/Article/details/gt2kbmonnfs.html

Ruby: 10.times { |i| puts i }
来源：http://dali.ehwqpu.com/Article/details/gt2ctayaslw.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.xuanzx.com/Article/details/gt2laipymiv.html

[B05] 遍历数组 / 列表
来源：http://dali.bjfxy.top/Article/details/gt2ubcovgee.html

Py:   for item in arr: print(item)
来源：http://dali.yj20258888.top/Article/details/gt2adffobyq.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.haohaochexian.top/Article/details/gt2cqfpstqa.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.guannengcc.top/Article/details/gt2mrhapshf.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.hywenlv.cn/Article/details/gt2yacfiifz.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.ivvv.top/Article/details/gt2pinxuiep.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.guowangkeji.top/Article/details/gt2znfvgwae.html

Ruby: arr.each { |item| puts item }
来源：http://dali.ydzc1.top/Article/details/gt2tzihwbfq.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.yvedp.cn/Article/details/gt2xbjzsxsv.html

[B06] 遍历字典 / 对象
来源：http://dali.feifeiyinyue.top/Article/details/gt2tgwnrbem.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.yuxming.cn/Article/details/gt2bejabnhm.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2avsqwyyj.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yongpay.top/Article/details/gt2wofqhtnh.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jianghu66.top/Article/details/gt2lectfreh.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.jinqigfzy.top/Article/details/gt2unfikqlc.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.zdqjudy.top/Article/details/gt2tlxsyxvl.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.gogol.net.cn/Article/details/gt2ygytjzjy.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.cucudq.cn/Article/details/gt2rnouqwql.html

[B07] while 循环
来源：http://dali.hnqzz.top/Article/details/gt2oclxsbsf.html

Py:   while i < 10: i += 1
来源：http://dali.yanxiufei.cn/Article/details/gt2vtjxohsc.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.9152youxi.cn/Article/details/gt2butphaui.html

JS:   while (i < 10) { i++; }
来源：http://dali.shzxlz.cn/Article/details/gt2aibnxazt.html

TS:   while (i < 10) { i++; }
来源：http://dali.sufxvd.cn/Article/details/gt2dzrngytc.html

Java: while (i < 10) { i++; }
来源：http://dali.yueranfly.top/Article/details/gt2tnkcdrej.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.yj202588.top/Article/details/gt2lvghydvp.html

Ruby: while i < 10; i += 1; end
来源：http://dali.bjfxy.top/Article/details/gt2mbhqhgfs.html

C#:   while (i < 10) { i++; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dlljyyxd.html

[B08] do-while（至少执行一次）
来源：http://dali.cdnleiting.top/Article/details/gt2yyovqbqq.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.gzhubu.top/Article/details/gt2bpjpxbzo.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.ppjwa.cn/Article/details/gt2fzduyscu.html

JS:   do { i++; } while (i < 10);
来源：http://dali.chenlongwang.top/Article/details/gt2scoluvpy.html

TS:   do { i++; } while (i < 10);
来源：http://dali.dianchejie.cn/Article/details/gt2szasxlgm.html

Java: do { i++; } while (i < 10);
来源：http://dali.smart0.xyz/Article/details/gt2pkahstoe.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.gogol.net.cn/Article/details/gt2qyusbuib.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.jianghu66.top/Article/details/gt2qmalqcgx.html

C#:   do { i++; } while (i < 10);
来源：http://dali.yonumen.top/Article/details/gt2fybiwmts.html

[B09] break 与 continue
来源：http://dali.gotoacloud.top/Article/details/gt2wrwinmol.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.zhengqikj.top/Article/details/gt2zttzvffk.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.dianchejie.cn/Article/details/gt2ienurvlr.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hnxiangtu.top/Article/details/gt2ppluzblf.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zdqjudy.top/Article/details/gt2awdaenzl.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shuidangran.top/Article/details/gt2bxowkqyz.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.ivvv.top/Article/details/gt2plwtnaac.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.sxryk.cn/Article/details/gt2cbuiooqj.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yongpay.top/Article/details/gt2uqcsrzsw.html

[B10] 遍历同时拿索引
来源：http://dali.aibaodan.cn/Article/details/gt2ckeqdbfg.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.jyoumei.cn/Article/details/gt2fgsmvkcx.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.vqdsnc.cn/Article/details/gt2wqwxzfyk.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.hfpthk.cn/Article/details/gt2ruvtuslq.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.dashuyun.cn/Article/details/gt2vfwyapwb.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.dashuyun.cn/Article/details/gt2fztwwpws.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.9152youxi.cn/Article/details/gt2rycqhmsw.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.sxryk.cn/Article/details/gt2joqvegzc.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.yj20258888.top/Article/details/gt2iafosdww.html

[B11] 生成数字序列 / 区间
来源：http://dali.chenzaomai.com/Article/details/gt2ykkkhicy.html

Py:   list(range(0, 10, 2))
来源：http://dali.nwbrower.top/Article/details/gt2tywnusdd.html

PHP:  range(0, 10, 2);
来源：http://dali.shzxlz.cn/Article/details/gt2pzosbgfn.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xuetiantiany.cn/Article/details/gt2jzsikpon.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xuanzx.com/Article/details/gt2qjbbqtgi.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.jlsjyb.cn/Article/details/gt2xtupjzxf.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhixingplan.top/Article/details/gt2muhhzfop.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yanxiufei.cn/Article/details/gt2wxtqkbtr.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.hammf.cn/Article/details/gt2fvqufgfy.html

[B12] 跳出多层循环
来源：http://dali.zhiwuduotai.top/Article/details/gt2ofswhdma.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.guannengcc.top/Article/details/gt2nasfsxva.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.cqqwz.cn/Article/details/gt2wzkmgbfd.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.fzhhl.top/Article/details/gt2rcsggvcv.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.c1oappe.top/Article/details/gt2dlzlxnqn.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.shangyingyoupin.top/Article/details/gt2rmrftpuw.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.hnqzz.top/Article/details/gt2gtwhsdmd.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.tanke756.top/Article/details/gt2bmjfqtws.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.xinyue.icu/Article/details/gt2tlctucak.html

[B13] 判断是否为数字
来源：http://dali.tianlin.xyz/Article/details/gt2jvllqoop.html

Py:   isinstance(x, (int, float))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zktokhxi.html

PHP:  is_numeric($x)
来源：http://dali.yangfankeji.com/Article/details/gt2otvpcxam.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gukrgrap.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.svipenyu.cn/Article/details/gt2ndthfauj.html

Java: x instanceof Number
来源：http://dali.hnqzz.top/Article/details/gt2fklpxghm.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.yvedp.cn/Article/details/gt2wuthtzmh.html

Ruby: x.is_a?(Numeric)
来源：http://dali.shangyingyoupin.top/Article/details/gt2mjcrqtdg.html

C#:   x is int or double or decimal
来源：http://dali.havefunace.top/Article/details/gt2emhcgsbz.html

[B14] 判断值是否在集合内
来源：http://dali.jianghu66.top/Article/details/gt2fvosyago.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.shuidangran.top/Article/details/gt2dcjgthjy.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.chenlongwang.top/Article/details/gt2uxrkialg.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jlsjyb.cn/Article/details/gt2diyjaalf.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.andypj.xyz/Article/details/gt2ishnjyua.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.sufxvd.cn/Article/details/gt2mnjlsnja.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.wangshuangyany.cn/Article/details/gt2rkcsagei.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.daxiang520.top/Article/details/gt2fkanznvu.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.svipenyu.cn/Article/details/gt2jwtomwrt.html

[B15] 布尔运算与取反
来源：http://dali.sufxvd.cn/Article/details/gt2ixztyzpr.html

Py:   a and b or not c
来源：http://dali.tanke756.top/Article/details/gt2rjqnenbl.html

PHP:  $a && $b || !$c
来源：http://dali.smart0.xyz/Article/details/gt2shdmgnsh.html

JS:   a && b || !c
来源：http://dali.shangyingyoupin.top/Article/details/gt2nldfbnqy.html

TS:   a && b || !c
来源：http://dali.smart0.xyz/Article/details/gt2kcqhhxzz.html

Java: a && b || !c
来源：http://dali.chenjidiqi.icu/Article/details/gt2kjkdperf.html

Go:   a && b || !c
来源：http://dali.daria6918.cn/Article/details/gt2kolslrzt.html

Ruby: a && b || !c
来源：http://dali.shangyingyoupin.top/Article/details/gt2wnjqfqrd.html

C#:   a && b || !c
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iytmetyc.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jinqigufen.top/Article/details/gt2jbzyhywp.html

Py:   if not data: return
来源：http://dali.yj202588.top/Article/details/gt2uemhyakm.html

PHP:  if (!$data) { return; }
来源：http://dali.zhixingplan.top/Article/details/gt2cqontknx.html

JS:   if (!data) return;
来源：http://dali.yonumen.top/Article/details/gt2gfmtnmyk.html

TS:   if (!data) return;
来源：http://dali.cqqwz.cn/Article/details/gt2ddoadhfp.html

Java: if (data == null) return;
来源：http://dali.bjfxy.top/Article/details/gt2fateggkp.html

Go:   if data == nil { return }
来源：http://dali.chenzaomai.com/Article/details/gt2ijvbqocf.html

Ruby: return if data.nil?
来源：http://dali.tanke756.top/Article/details/gt2oslhpjrc.html

C#:   if (data == null) return;
来源：http://dali.xziqi.cn/Article/details/gt2qeartycj.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lcpgilym.html

C. 函数与作用域
来源：http://dali.redwolf501.top/Article/details/gt2sawixrum.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2utbuvjvp.html

[C01] 定义函数
来源：http://dali.yangfankeji.com/Article/details/gt2zlbhiugk.html

Py:   def add(a, b): return a + b
来源：http://dali.yongpay.top/Article/details/gt2hekieply.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.kuanghao11.cn/Article/details/gt2usjmlawc.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jlsjyb.cn/Article/details/gt2iczeymkb.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cqqwz.cn/Article/details/gt2dmevcawc.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.snrcjt.cn/Article/details/gt2lvmtgqko.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.316326.xyz/Article/details/gt2dtzyvlvm.html

Ruby: def add(a, b); a + b; end
来源：http://dali.ehwqpu.com/Article/details/gt2jfpoqfow.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yangfankeji.com/Article/details/gt2iyzrilgl.html

[C02] 默认参数
来源：http://dali.nanxuanxn.top/Article/details/gt2bkqaoqnh.html

Py:   def greet(name="World"): return name
来源：http://dali.quarkkingdee.top/Article/details/gt2ohzvwgpo.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2nqqmpcag.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2lpjlwqjt.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.nanxuanxn.top/Article/details/gt2ftqagpbj.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.redwolf501.top/Article/details/gt2sxfykeyz.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ujqglllt.html

Ruby: def greet(name = "World") = name
来源：http://dali.gaohongyu789.top/Article/details/gt2fhqzmils.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.svipenyu.cn/Article/details/gt2agukiggq.html

[C03] 可变参数
来源：http://dali.jinqigfzy.top/Article/details/gt2hxjdbliy.html

Py:   def total(*args): return sum(args)
来源：http://dali.cucudq.cn/Article/details/gt2zexgazfr.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pilfijut.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zycfv.cn/Article/details/gt2jlggzwfe.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tgptyanx.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhongyouzk.top/Article/details/gt2pwevikyo.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.sufxvd.cn/Article/details/gt2cbgldnqt.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2izqyrtwm.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jqgfzy.top/Article/details/gt2woduhiqf.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yj202588.top/Article/details/gt2behbksoj.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hedopiwb.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lyaywllj.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.guowangkeji.top/Article/details/gt2ikayhybe.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.shuidangran.top/Article/details/gt2gcrlcorc.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yj20258.top/Article/details/gt2hpumuszx.html

Go:   // 无：用配置结构体参数
来源：http://dali.ybcxt.top/Article/details/gt2zesitjlr.html

Ruby: f(a: 1, b: 2)
来源：http://dali.ppjwa.cn/Article/details/gt2hpietaqx.html

C#:   f(a: 1, b: 2)
来源：http://dali.yueranfly.top/Article/details/gt2annrpvkk.html

[C05] 返回多个值
来源：http://dali.guannengcc.top/Article/details/gt2jobxfufb.html

Py:   return a, b
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2irosdzxv.html

PHP:  return [$a, $b];
来源：http://dali.guowangkeji.top/Article/details/gt2ecirgfxd.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xxbebtji.html

TS:   return { a, b };
来源：http://dali.316326.xyz/Article/details/gt2znihrmpb.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.cashguo.top/Article/details/gt2nbstlgjh.html

Go:   return a, b
来源：http://dali.ppjwa.cn/Article/details/gt2icntgxrk.html

Ruby: return a, b
来源：http://dali.kuanghao11.cn/Article/details/gt2ntejvkqf.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.shuidangran.top/Article/details/gt2lzlcpwaq.html


<!-- 参考信息 -->