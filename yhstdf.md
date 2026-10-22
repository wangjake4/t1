代发 wailian999

[A14] 注释写法
来源：http://dali.gzhubu.top/Article/details/gt2vouaelwd.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.gogol.net.cn/Article/details/gt2ysybzwzw.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhoulong.xyz/Article/details/gt2epqoifdo.html

JS:   // 单行；/* 多行 */
来源：http://dali.gzhubu.top/Article/details/gt2sawsrnbe.html

TS:   // 单行；/* 多行 */
来源：http://dali.havefunace.top/Article/details/gt2sqylrbmd.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.wangdashe.top/Article/details/gt2uldwpnro.html

Go:   // 单行；/* 多行 */
来源：http://dali.hnxiangtu.top/Article/details/gt2dlxvcrnh.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.redwolf501.top/Article/details/gt2hhkfdnug.html

C#:   // 单行；/* 多行 */
来源：http://dali.yanxiufei.cn/Article/details/gt2oxfdbcrr.html

[A15] 空值判断与默认值
来源：http://dali.ybcxt.top/Article/details/gt2axukqbpx.html

Py:   value = data or "默认值"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qwfeiioj.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.dashuyun.cn/Article/details/gt2vwsunmbh.html

JS:   const value = data ?? "默认值";
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xbnokcvf.html

TS:   const value = data ?? "默认值";
来源：http://dali.pycfn.com/Article/details/gt2csfswmfo.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.hongshengwenyu.top/Article/details/gt2bmmdonlx.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lnckziut.html

Ruby: value = data || "默认值"
来源：http://dali.yj202588.top/Article/details/gt2ohphyuhh.html

C#:   var value = data ?? "默认值";
来源：http://dali.feifeiyinyue.top/Article/details/gt2kkqjcfgo.html

[A16] 真假值判断规则
来源：http://dali.jlsjyb.cn/Article/details/gt2mbwrgjew.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.haohaochexian.top/Article/details/gt2opqsdcpn.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.gogol.net.cn/Article/details/gt2nguxqxlu.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.hongshengwenyu.top/Article/details/gt2xwxmyova.html

TS:   if (!x) {}
来源：http://dali.hammf.cn/Article/details/gt2xkjuzsvw.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.haohaochexian.top/Article/details/gt2ebjgqkyi.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.yonumen.top/Article/details/gt2diwhrpfh.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.daxiang520.top/Article/details/gt2pyiyijnu.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.shuidangran.top/Article/details/gt2ddckdria.html

[A17] 位运算
来源：http://dali.cdnleiting.top/Article/details/gt2pvrleoko.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.bjfxy.top/Article/details/gt2iezudvyb.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.nanxinkj.top/Article/details/gt2ribquxon.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.gzhubu.top/Article/details/gt2gzkibdcj.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.havefunace.top/Article/details/gt2viocjoch.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xinyue.icu/Article/details/gt2bxhlqwdb.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.sufxvd.cn/Article/details/gt2spuhdisc.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.guowangkeji.top/Article/details/gt2uqhlrgty.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xuanzx.com/Article/details/gt2wsmyumzv.html

[A18] 字符与 ASCII 码互转
来源：http://dali.feifeiyinyue.top/Article/details/gt2fuacklfc.html

Py:   ord("A"); chr(65)
来源：http://dali.cucudq.cn/Article/details/gt2jxhsjlhg.html

PHP:  ord("A"); chr(65)
来源：http://dali.quarkkingdee.top/Article/details/gt2qlmbexll.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.meibo888.top/Article/details/gt2bswosdxz.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zhiwuduotai.top/Article/details/gt2kgwoqxhs.html

Java: (int) 'A'; (char) 65
来源：http://dali.nwbrower.top/Article/details/gt2mwnidtdn.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.gzhubu.top/Article/details/gt2ligjywza.html

Ruby: "A".ord; 65.chr
来源：http://dali.zhijiandao.cn/Article/details/gt2kygqjmts.html

C#:   (int)'A'; (char)65
来源：http://dali.smart0.xyz/Article/details/gt2hhaskozt.html

[A19] 交换两个变量
来源：http://dali.nanxinkj.top/Article/details/gt2ewhlibqa.html

Py:   a, b = b, a
来源：http://dali.fzhhl.top/Article/details/gt2msrqlfoa.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.dashuyun.cn/Article/details/gt2cerykqvk.html

JS:   [a, b] = [b, a];
来源：http://dali.mhx1999.top/Article/details/gt2umhnaxwz.html

TS:   [a, b] = [b, a];
来源：http://dali.wangshuangyany.cn/Article/details/gt2buixksqc.html

Java: int t = a; a = b; b = t;
来源：http://dali.feifeiyinyue.top/Article/details/gt2edqpopmq.html

Go:   a, b = b, a
来源：http://dali.pengpengdd.cyou/Article/details/gt2kdvzsipz.html

Ruby: a, b = b, a
来源：http://dali.guannengcc.top/Article/details/gt2pwlnehzy.html

C#:   (a, b) = (b, a);
来源：http://dali.andypj.xyz/Article/details/gt2gswloiwf.html

[A20] 读取标准输入
来源：http://dali.shzxlz.cn/Article/details/gt2fdgzapjq.html

Py:   name = input("请输入：")
来源：http://dali.xuetiantiany.cn/Article/details/gt2xhfgriej.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.jianghu66.top/Article/details/gt2fbiloeui.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.yonumen.top/Article/details/gt2zfkihrjy.html

TS:   // Node.js：readline 模块
来源：http://dali.yvedp.cn/Article/details/gt2bgaxkhtb.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.shuidangran.top/Article/details/gt2vlouytgm.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.ivvv.top/Article/details/gt2gtjgusze.html

Ruby: gets.chomp
来源：http://dali.zhiwuduotai.top/Article/details/gt2flryvuns.html

C#:   Console.ReadLine();
来源：http://dali.shangyingyoupin.top/Article/details/gt2mtxtbein.html

[A21] 保留指定小数位输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ycxxyowv.html

Py:   f"{3.14159:.2f}"
来源：http://dali.shzxlz.cn/Article/details/gt2lrfxeivt.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zgyycndn.html

JS:   (3.14159).toFixed(2)
来源：http://dali.zhoulong.xyz/Article/details/gt2mibyqxki.html

TS:   (3.14159).toFixed(2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2holcknkb.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.snrcjt.cn/Article/details/gt2hupetvys.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.zhengqikj.top/Article/details/gt2cgdrfejb.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kkoeuwtu.html

C#:   3.14159.ToString("F2")
来源：http://dali.quarkkingdee.top/Article/details/gt2nujbjdoa.html

[A22] 获取字符串长度
来源：http://dali.birdmap.top/Article/details/gt2ltcmvgoo.html

Py:   len(s)
来源：http://dali.yonumen.top/Article/details/gt2qxxewocf.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.jinqigfzy.top/Article/details/gt2tyoiziiu.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.nwbrower.top/Article/details/gt2zwsahsmg.html

TS:   s.length
来源：http://dali.sufxvd.cn/Article/details/gt2naiebjao.html

Java: s.length()
来源：http://dali.gzhubu.top/Article/details/gt2bzxyetwj.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2tqblquqa.html

Ruby: s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2bwvkfjfc.html

C#:   s.Length
来源：http://dali.sweek.top/Article/details/gt2mshewita.html

[A23] 大小写转换
来源：http://dali.9152youxi.cn/Article/details/gt2mkajychx.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.xylfe.cn/Article/details/gt2bhziotxj.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.wangdashe.top/Article/details/gt2iybqkzyi.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.pycfn.com/Article/details/gt2dfowvjbz.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yfxenyjr.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.ybcxt.top/Article/details/gt2qinxekdr.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.vqdsnc.cn/Article/details/gt2swkwzmrs.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.ydzc1.top/Article/details/gt2clpkxrok.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.ybcxt.top/Article/details/gt2snbjzkpx.html

[A24] 去除首尾空白
来源：http://dali.jyoumei.cn/Article/details/gt2fyhiyybi.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.cdnleiting.top/Article/details/gt2isntgumx.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2rvsdxphe.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.xylfe.cn/Article/details/gt2fdlfdeik.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.shangyingyoupin.top/Article/details/gt2exyadnto.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.wangdashe.top/Article/details/gt2gnfkviza.html

Go:   strings.TrimSpace(s)
来源：http://dali.haohaochexian.top/Article/details/gt2shsdadxa.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.xuanzx.com/Article/details/gt2ncwukrvv.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.smart0.xyz/Article/details/gt2jxcojqnr.html

[A25] 字符串比较
来源：http://dali.jiagoushi.top/Article/details/gt2nikwyidr.html

Py:   s1 == s2; s1 != s2
来源：http://dali.mhx1999.top/Article/details/gt2xckdbyzn.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.aizwys.cn/Article/details/gt2wqpwnaic.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yj202588.top/Article/details/gt2njlrgryo.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2euninlua.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.birdmap.top/Article/details/gt2nsiqfykm.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.birdmap.top/Article/details/gt2ftnccoxs.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2anxdoxjm.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.yuxming.cn/Article/details/gt2igxwwfaf.html

[A26] 类型转换总览
来源：http://dali.pycfn.com/Article/details/gt2gvlxxinc.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.gotoacloud.top/Article/details/gt2zrjpldpj.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.ybcxt.top/Article/details/gt2etobdiea.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.yongpay.top/Article/details/gt2oajdiect.html

TS:   Number() String() Boolean() x as number
来源：http://dali.sysykeji.top/Article/details/gt2ftxevpmd.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.kuanghao11.cn/Article/details/gt2qxqljhep.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.yj20258.top/Article/details/gt2pscjoawe.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.cqqwz.cn/Article/details/gt2fjwvfctk.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.sxryk.cn/Article/details/gt2aosizivd.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2fzlgjeon.html

B. 流程控制
来源：http://dali.wangdashe.top/Article/details/gt2pjgaxcny.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2isvsneue.html

[B01] 条件判断 if / else
来源：http://dali.316326.xyz/Article/details/gt2pfwlndqq.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.zhiwuduotai.top/Article/details/gt2zgcxitey.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.meibo888.top/Article/details/gt2ayqszcxq.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yuxming.cn/Article/details/gt2pmdbstrw.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.gaohongyu789.top/Article/details/gt2ihlozlzl.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.sxryk.cn/Article/details/gt2vzypvakt.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.hammf.cn/Article/details/gt2jlpfxavt.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.nanxinkj.top/Article/details/gt2sjicgrif.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.gaohongyu789.top/Article/details/gt2iehlhvgn.html

[B02] 多分支 else if / elif
来源：http://dali.yj20258.top/Article/details/gt2ptucrasi.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.yj20258888.top/Article/details/gt2bfsiflzb.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.hnqzz.top/Article/details/gt2mixikohw.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hnxiangtu.top/Article/details/gt2rtghdwpz.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.gotoacloud.top/Article/details/gt2susquygr.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.svipenyu.cn/Article/details/gt2smvsjdau.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.ehwqpu.com/Article/details/gt2etkvwbhp.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.nanxuanxn.top/Article/details/gt2wshowhoi.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hywenlv.cn/Article/details/gt2xerhhbee.html

[B03] switch / match / case
来源：http://dali.meibo888.top/Article/details/gt2dkurlmxz.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.iojbl.cn/Article/details/gt2agbfvmhi.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.birdmap.top/Article/details/gt2dbvgifdd.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.meibo888.top/Article/details/gt2snnxspua.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hbxzsmcw.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.daria6918.cn/Article/details/gt2gzupdned.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.gotoacloud.top/Article/details/gt2vnltwucg.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.yuanzhike.top/Article/details/gt2bdqgbodh.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.zhixingplan.top/Article/details/gt2dedkqzws.html

[B04] for 计数循环
来源：http://dali.zhongyouzk.top/Article/details/gt2emzoilnq.html

Py:   for i in range(10): print(i)
来源：http://dali.zhengqikj.top/Article/details/gt2cflhjqoq.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.gzhubu.top/Article/details/gt2pdvodtiw.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.cdnleiting.top/Article/details/gt2vzxsxytc.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.tian-w.cn/Article/details/gt2thgwzznc.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.hnxiangtu.top/Article/details/gt2azjepyud.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.cashguo.top/Article/details/gt2wrvyqzuf.html

Ruby: 10.times { |i| puts i }
来源：http://dali.ehwqpu.com/Article/details/gt2ysyomyjs.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.yj20258888.top/Article/details/gt2cscnuqhu.html

[B05] 遍历数组 / 列表
来源：http://dali.jyoumei.cn/Article/details/gt2rtkmczrw.html

Py:   for item in arr: print(item)
来源：http://dali.jyoumei.cn/Article/details/gt2ixvdfdbp.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.xinyue.icu/Article/details/gt2iqtpljsh.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.jqgfzy.top/Article/details/gt2wzecrcjm.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.havefunace.top/Article/details/gt2rqmshpqc.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.sufxvd.cn/Article/details/gt2gwbyfkmg.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.hfpthk.cn/Article/details/gt2iurjubhx.html

Ruby: arr.each { |item| puts item }
来源：http://dali.gaohongyu789.top/Article/details/gt2xoqxijby.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.fengsongda.top/Article/details/gt2ulsawljo.html

[B06] 遍历字典 / 对象
来源：http://dali.tanke756.top/Article/details/gt2bqgilrkj.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.wangshuangyany.cn/Article/details/gt2vlhhufzx.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.yj20258.top/Article/details/gt2pksahpll.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.gogol.net.cn/Article/details/gt2fmlyybea.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jinqigfzy.top/Article/details/gt2wkucqylf.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.jqgfzy.top/Article/details/gt2fghhkpku.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ljqajknw.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.hnqzz.top/Article/details/gt2jngfeaac.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.dianchejie.cn/Article/details/gt2afrpndzu.html

[B07] while 循环
来源：http://dali.ehwqpu.com/Article/details/gt2ftqlkmez.html

Py:   while i < 10: i += 1
来源：http://dali.wangshuangyany.cn/Article/details/gt2kxwtagvh.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.gogol.net.cn/Article/details/gt2iqokggsi.html

JS:   while (i < 10) { i++; }
来源：http://dali.yanxiufei.cn/Article/details/gt2antbtiob.html

TS:   while (i < 10) { i++; }
来源：http://dali.dashuyun.cn/Article/details/gt2yrxahwlk.html

Java: while (i < 10) { i++; }
来源：http://dali.daxiang520.top/Article/details/gt2tptyoxxf.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.jinqigufen.top/Article/details/gt2cwwgookq.html

Ruby: while i < 10; i += 1; end
来源：http://dali.tanke756.top/Article/details/gt2vtickixe.html

C#:   while (i < 10) { i++; }
来源：http://dali.yonumen.top/Article/details/gt2qxyeaypz.html

[B08] do-while（至少执行一次）
来源：http://dali.zhiwuduotai.top/Article/details/gt2osfmaxri.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.tian-w.cn/Article/details/gt2umbgpsgi.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jinqigufen.top/Article/details/gt2hbopucnt.html

JS:   do { i++; } while (i < 10);
来源：http://dali.chenlongwang.top/Article/details/gt2ufppsjxz.html

TS:   do { i++; } while (i < 10);
来源：http://dali.ivvv.top/Article/details/gt2jxkjbpfp.html

Java: do { i++; } while (i < 10);
来源：http://dali.cdnleiting.top/Article/details/gt2wfwxdtqb.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.tanke756.top/Article/details/gt2zjqshsbr.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.aizwys.cn/Article/details/gt2pgaosplp.html

C#:   do { i++; } while (i < 10);
来源：http://dali.chenjidiqi.icu/Article/details/gt2wjtfkwue.html

[B09] break 与 continue
来源：http://dali.bjfxy.top/Article/details/gt2ovhkkgrq.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.zhengqikj.top/Article/details/gt2hxfkucll.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wruhbbme.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.0kj1m.cn/Article/details/gt2zfvfgsrv.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jqgfzy.top/Article/details/gt2fsdwhffb.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yanxiufei.cn/Article/details/gt2jkjmxmoy.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.birdmap.top/Article/details/gt2jnacddld.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.chenzaomai.com/Article/details/gt2vhoyrqqr.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ivvv.top/Article/details/gt2yvlziejd.html

[B10] 遍历同时拿索引
来源：http://dali.jlsjyb.cn/Article/details/gt2skuongsq.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.fengsongda.top/Article/details/gt2vuevawps.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.sxryk.cn/Article/details/gt2fssoohig.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yuanzhike.top/Article/details/gt2dcwqzgib.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sxewsbcp.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.hammf.cn/Article/details/gt2gawcmtef.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.wangdashe.top/Article/details/gt2bcykanhw.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.jqgfzy.top/Article/details/gt2bwwsihia.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.jyoumei.cn/Article/details/gt2eptmqdzk.html

[B11] 生成数字序列 / 区间
来源：http://dali.yangfankeji.com/Article/details/gt2lwoyimvq.html

Py:   list(range(0, 10, 2))
来源：http://dali.snrcjt.cn/Article/details/gt2ekyzuyjo.html

PHP:  range(0, 10, 2);
来源：http://dali.dianchejie.cn/Article/details/gt2tnouwgnc.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.guowangkeji.top/Article/details/gt2oabphnru.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.shangyingyoupin.top/Article/details/gt2cnrmnlfj.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.nanxuanxn.top/Article/details/gt2algypjsi.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.snrcjt.cn/Article/details/gt2qhazehrn.html

Ruby: (0...10).step(2).to_a
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vjutovvh.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.svipenyu.cn/Article/details/gt2ammoiafw.html

[B12] 跳出多层循环
来源：http://dali.tian-w.cn/Article/details/gt2hkiehfnj.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.pengpengdd.cyou/Article/details/gt2zfbittek.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.9152youxi.cn/Article/details/gt2hluvqzfr.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yueranfly.top/Article/details/gt2tefsvufu.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yj202588.top/Article/details/gt2vqwnlysz.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.sufxvd.cn/Article/details/gt2cqcsyfet.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.fzhhl.top/Article/details/gt2efripgaj.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhengqikj.top/Article/details/gt2owthclzo.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.xuanzx.com/Article/details/gt2pagaevyl.html

[B13] 判断是否为数字
来源：http://dali.tianlin.xyz/Article/details/gt2plrcagfb.html

Py:   isinstance(x, (int, float))
来源：http://dali.jinqigufen.top/Article/details/gt2yoylgifc.html

PHP:  is_numeric($x)
来源：http://dali.zhengqikj.top/Article/details/gt2burohqgw.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.chenjidiqi.icu/Article/details/gt2qjcbejru.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.fzhhl.top/Article/details/gt2zdesbgpy.html

Java: x instanceof Number
来源：http://dali.0kj1m.cn/Article/details/gt2ikufdeev.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.cucudq.cn/Article/details/gt2uaeqyubk.html

Ruby: x.is_a?(Numeric)
来源：http://dali.jqgfzy.top/Article/details/gt2kybxtiyt.html

C#:   x is int or double or decimal
来源：http://dali.yonumen.top/Article/details/gt2wkvndzjo.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2gptuwlnf.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.tian-w.cn/Article/details/gt2agrtebwd.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.svipenyu.cn/Article/details/gt2jqmfdapo.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.aibaodan.cn/Article/details/gt2bvmjdsya.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.xziqi.cn/Article/details/gt2hcposvta.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.hysaishi.cn/Article/details/gt2gjyeshmv.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2kbdbqrzr.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jiagoushi.top/Article/details/gt2xywjhtek.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jinqigfzy.top/Article/details/gt2jbocofsx.html

[B15] 布尔运算与取反
来源：http://dali.yueranfly.top/Article/details/gt2rumbpmkt.html

Py:   a and b or not c
来源：http://dali.havefunace.top/Article/details/gt2xcxjnwdg.html

PHP:  $a && $b || !$c
来源：http://dali.gogol.net.cn/Article/details/gt2apujqipd.html

JS:   a && b || !c
来源：http://dali.jqgfzy.top/Article/details/gt2rzehwbnx.html

TS:   a && b || !c
来源：http://dali.zhixingplan.top/Article/details/gt2budolkzi.html

Java: a && b || !c
来源：http://dali.ehwqpu.com/Article/details/gt2yhyookwk.html

Go:   a && b || !c
来源：http://dali.shzxlz.cn/Article/details/gt2yrhekwak.html

Ruby: a && b || !c
来源：http://dali.xuetiantiany.cn/Article/details/gt2wcnurdyy.html

C#:   a && b || !c
来源：http://dali.jianghu66.top/Article/details/gt2cfmyseoa.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jqgufenzy.top/Article/details/gt2qdseoifx.html

Py:   if not data: return
来源：http://dali.gzhubu.top/Article/details/gt2ttxowsyk.html

PHP:  if (!$data) { return; }
来源：http://dali.mhx1999.top/Article/details/gt2jcluorhf.html

JS:   if (!data) return;
来源：http://dali.kuanghao11.cn/Article/details/gt2nzsinppf.html

TS:   if (!data) return;
来源：http://dali.hnxiangtu.top/Article/details/gt2aqcszerb.html

Java: if (data == null) return;
来源：http://dali.pycfn.com/Article/details/gt2zevrqegv.html

Go:   if data == nil { return }
来源：http://dali.quarkkingdee.top/Article/details/gt2qvokkkdh.html

Ruby: return if data.nil?
来源：http://dali.hnxiangtu.top/Article/details/gt2ymtdgtgo.html

C#:   if (data == null) return;
来源：http://dali.zhoulong.xyz/Article/details/gt2vwfezicz.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2vovofobh.html

C. 函数与作用域
来源：http://dali.chenlongwang.top/Article/details/gt2usxnagmv.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2iculqhtm.html

[C01] 定义函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vidmvppx.html

Py:   def add(a, b): return a + b
来源：http://dali.feifeiyinyue.top/Article/details/gt2mjpoymql.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sweek.top/Article/details/gt2aqvpzsco.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2amfjhwxs.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ybcxt.top/Article/details/gt2owgmyurk.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.redwolf501.top/Article/details/gt2wenalasm.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.shzxlz.cn/Article/details/gt2qohxxpyy.html

Ruby: def add(a, b); a + b; end
来源：http://dali.svipenyu.cn/Article/details/gt2zulsnvqj.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2srmyurmu.html

[C02] 默认参数
来源：http://dali.gzhubu.top/Article/details/gt2dlmhyemf.html

Py:   def greet(name="World"): return name
来源：http://dali.xylfe.cn/Article/details/gt2luxihtap.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jqgfzy.top/Article/details/gt2zadvxaqw.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yj202588.top/Article/details/gt2uimbmguu.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2ucrcthte.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.hnqzz.top/Article/details/gt2qliypnwc.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.ehwqpu.com/Article/details/gt2hnplxpxw.html

Ruby: def greet(name = "World") = name
来源：http://dali.sysykeji.top/Article/details/gt2dzwlkmwy.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.ybcxt.top/Article/details/gt2lnbkivlg.html

[C03] 可变参数
来源：http://dali.chenzaomai.com/Article/details/gt2gwyipkde.html

Py:   def total(*args): return sum(args)
来源：http://dali.yvedp.cn/Article/details/gt2lnokscnd.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.wangdashe.top/Article/details/gt2nwblimrd.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.aizwys.cn/Article/details/gt2tykbjino.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.meibo888.top/Article/details/gt2usjqveoj.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.gzhubu.top/Article/details/gt2eymunorm.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.ybcxt.top/Article/details/gt2ezuodudq.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.birdmap.top/Article/details/gt2ulhoxvbf.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.c1oappe.top/Article/details/gt2lgywtyzm.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhoulong.xyz/Article/details/gt2idbtrqsg.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.meibo888.top/Article/details/gt2jcohuqis.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.tian-w.cn/Article/details/gt2jfhneydn.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.ydzc1.top/Article/details/gt2plszajir.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhongyouzk.top/Article/details/gt2dsyehcle.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nitiukbr.html


<!-- 参考信息 -->