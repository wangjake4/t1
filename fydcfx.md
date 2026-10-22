代发 wailian999

[A14] 注释写法
来源：http://dali.iojbl.cn/Article/details/gt2nifanqot.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhengqikj.top/Article/details/gt2bxlmvkki.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.andypj.xyz/Article/details/gt2ughozegr.html

JS:   // 单行；/* 多行 */
来源：http://dali.hammf.cn/Article/details/gt2lvwzauhg.html

TS:   // 单行；/* 多行 */
来源：http://dali.sufxvd.cn/Article/details/gt2fccaayue.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.hongshengwenyu.top/Article/details/gt2kucwpffa.html

Go:   // 单行；/* 多行 */
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qchgehck.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.chenjidiqi.icu/Article/details/gt2aifnvxqe.html

C#:   // 单行；/* 多行 */
来源：http://dali.gogol.net.cn/Article/details/gt2relnjmwa.html

[A15] 空值判断与默认值
来源：http://dali.cucudq.cn/Article/details/gt2amnbmimb.html

Py:   value = data or "默认值"
来源：http://dali.tianlin.xyz/Article/details/gt2cmrnovyp.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.xuanzx.com/Article/details/gt2woltwvyk.html

JS:   const value = data ?? "默认值";
来源：http://dali.havefunace.top/Article/details/gt2ibvshkgd.html

TS:   const value = data ?? "默认值";
来源：http://dali.daria6918.cn/Article/details/gt2zkzwqrmw.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.vqdsnc.cn/Article/details/gt2lqyunhfd.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.quarkkingdee.top/Article/details/gt2gnmgnatx.html

Ruby: value = data || "默认值"
来源：http://dali.yuanzhike.top/Article/details/gt2hlcefofd.html

C#:   var value = data ?? "默认值";
来源：http://dali.vqdsnc.cn/Article/details/gt2ipmvjcxg.html

[A16] 真假值判断规则
来源：http://dali.nanxuanxn.top/Article/details/gt2iixkfbxr.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.quarkkingdee.top/Article/details/gt2jlrhbwpr.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.gogol.net.cn/Article/details/gt2krocilbn.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.hongshengwenyu.top/Article/details/gt2hfvozenp.html

TS:   if (!x) {}
来源：http://dali.jianghu66.top/Article/details/gt2bjzpdphz.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2sjyhqibj.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.yj202588.top/Article/details/gt2oawxvnlq.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.snrcjt.cn/Article/details/gt2vnrgeixk.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jwopbexv.html

[A17] 位运算
来源：http://dali.zhengqikj.top/Article/details/gt2suhfcrea.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.birdmap.top/Article/details/gt2kqwkimwr.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.hysaishi.cn/Article/details/gt2babdyqop.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.daxiang520.top/Article/details/gt2ijbepukl.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.tanke756.top/Article/details/gt2beccnuik.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yanxiufei.cn/Article/details/gt2lmiehkva.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.redwolf501.top/Article/details/gt2orubaxzy.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jinqigfzy.top/Article/details/gt2uogniixs.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hammf.cn/Article/details/gt2dfqerwqx.html

[A18] 字符与 ASCII 码互转
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nglmomuh.html

Py:   ord("A"); chr(65)
来源：http://dali.jqgufenzy.top/Article/details/gt2yxtbuktm.html

PHP:  ord("A"); chr(65)
来源：http://dali.jlsjyb.cn/Article/details/gt2rwubnvab.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.shangyingyoupin.top/Article/details/gt2zbewrzyu.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.daria6918.cn/Article/details/gt2oxitaaft.html

Java: (int) 'A'; (char) 65
来源：http://dali.yueranfly.top/Article/details/gt2gigjqnfe.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.zhongyouzk.top/Article/details/gt2gacypwwu.html

Ruby: "A".ord; 65.chr
来源：http://dali.dashuyun.cn/Article/details/gt2zekgytre.html

C#:   (int)'A'; (char)65
来源：http://dali.cqqwz.cn/Article/details/gt2qewnllta.html

[A19] 交换两个变量
来源：http://dali.yongpay.top/Article/details/gt2xvgsiazm.html

Py:   a, b = b, a
来源：http://dali.hfpthk.cn/Article/details/gt2ddordeko.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.cdnleiting.top/Article/details/gt2mbvvoojv.html

JS:   [a, b] = [b, a];
来源：http://dali.sysykeji.top/Article/details/gt2xnuuniqg.html

TS:   [a, b] = [b, a];
来源：http://dali.jiagoushi.top/Article/details/gt2jpqnonlt.html

Java: int t = a; a = b; b = t;
来源：http://dali.zhiwuduotai.top/Article/details/gt2qbrtacue.html

Go:   a, b = b, a
来源：http://dali.jlsjyb.cn/Article/details/gt2ksanlzgg.html

Ruby: a, b = b, a
来源：http://dali.shzxlz.cn/Article/details/gt2ybptigps.html

C#:   (a, b) = (b, a);
来源：http://dali.jinqigfzy.top/Article/details/gt2mzzewuem.html

[A20] 读取标准输入
来源：http://dali.jqgufenzy.top/Article/details/gt2uetxcgqz.html

Py:   name = input("请输入：")
来源：http://dali.quarkkingdee.top/Article/details/gt2zaavdvhl.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.cheryme.top/Article/details/gt2oymmchbd.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.yangfankeji.com/Article/details/gt2drkrzgej.html

TS:   // Node.js：readline 模块
来源：http://dali.fzhhl.top/Article/details/gt2pzivvhwa.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.aibaodan.cn/Article/details/gt2rlkevvry.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.andypj.xyz/Article/details/gt2fsgerjfk.html

Ruby: gets.chomp
来源：http://dali.c1oappe.top/Article/details/gt2rkntydtd.html

C#:   Console.ReadLine();
来源：http://dali.chenzaomai.com/Article/details/gt2ujlzngbi.html

[A21] 保留指定小数位输出
来源：http://dali.pycfn.com/Article/details/gt2ppqwgdav.html

Py:   f"{3.14159:.2f}"
来源：http://dali.tianlin.xyz/Article/details/gt2thhsxvnw.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.fengsongda.top/Article/details/gt2duazxqpm.html

JS:   (3.14159).toFixed(2)
来源：http://dali.hammf.cn/Article/details/gt2ibvbfwqe.html

TS:   (3.14159).toFixed(2)
来源：http://dali.kuanghao11.cn/Article/details/gt2pyjjjalg.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.sweek.top/Article/details/gt2zdvgqpby.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.jqgfzy.top/Article/details/gt2dlbsecxj.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.ydzc1.top/Article/details/gt2qnqmvgvm.html

C#:   3.14159.ToString("F2")
来源：http://dali.xuetiantiany.cn/Article/details/gt2hlrlgbzv.html

[A22] 获取字符串长度
来源：http://dali.tanke756.top/Article/details/gt2qkbjlzwl.html

Py:   len(s)
来源：http://dali.zdqjudy.top/Article/details/gt2kzdiuszi.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.daria6918.cn/Article/details/gt2rlrypiyh.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.smart0.xyz/Article/details/gt2mrjemgao.html

TS:   s.length
来源：http://dali.jianghu66.top/Article/details/gt2ekgbzoti.html

Java: s.length()
来源：http://dali.sysykeji.top/Article/details/gt2taulqaxh.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ulnegqfm.html

Ruby: s.length
来源：http://dali.yangfankeji.com/Article/details/gt2kylyglxt.html

C#:   s.Length
来源：http://dali.yj202588.top/Article/details/gt2jytbzqww.html

[A23] 大小写转换
来源：http://dali.yj202588.top/Article/details/gt2viwtfidb.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.havefunace.top/Article/details/gt2ilwzxtyy.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.jqgufenzy.top/Article/details/gt2ckzllkag.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.svipenyu.cn/Article/details/gt2pqdnbhyu.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.yuxming.cn/Article/details/gt2vjcyagbl.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.haohaochexian.top/Article/details/gt2wlgfhaxq.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2txguyavo.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.zhixingplan.top/Article/details/gt2bdpfhtnk.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.wangshuangyany.cn/Article/details/gt2vodneaxs.html

[A24] 去除首尾空白
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ovaxjmzr.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.redwolf501.top/Article/details/gt2kmlzisyq.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.cashguo.top/Article/details/gt2faqzftbu.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.ybcxt.top/Article/details/gt2gvulfbrc.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.wangdashe.top/Article/details/gt2gjgnrttl.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.yuxming.cn/Article/details/gt2llabiton.html

Go:   strings.TrimSpace(s)
来源：http://dali.redwolf501.top/Article/details/gt2qirymjkw.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.hongshengwenyu.top/Article/details/gt2osavdyph.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.zhijiandao.cn/Article/details/gt2cckamuqd.html

[A25] 字符串比较
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oirectgk.html

Py:   s1 == s2; s1 != s2
来源：http://dali.chenlongwang.top/Article/details/gt2pltnbhqg.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.zdqjudy.top/Article/details/gt2cczouirt.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.jyoumei.cn/Article/details/gt2oypbccpn.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.sweek.top/Article/details/gt2qxwvwqqr.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.tian-w.cn/Article/details/gt2fjlrrtvc.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.yonumen.top/Article/details/gt2foixrztc.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.dashuyun.cn/Article/details/gt2uabtiofh.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.havefunace.top/Article/details/gt2ddhdsixw.html

[A26] 类型转换总览
来源：http://dali.sxryk.cn/Article/details/gt2yvcyysjn.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.zhiwuduotai.top/Article/details/gt2xxerxlav.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.havefunace.top/Article/details/gt2jlpmfcid.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.daxiang520.top/Article/details/gt2qvggsqrs.html

TS:   Number() String() Boolean() x as number
来源：http://dali.gaohongyu789.top/Article/details/gt2rwpykodd.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.tian-w.cn/Article/details/gt2qteyobae.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.yj20258.top/Article/details/gt2nfuvowho.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.cheryme.top/Article/details/gt2vrgcbazw.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.yj20258.top/Article/details/gt2mkktwqnt.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2fiyfzvit.html

B. 流程控制
来源：http://dali.cqqwz.cn/Article/details/gt2fiatnstj.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2dpcyozzm.html

[B01] 条件判断 if / else
来源：http://dali.gotoacloud.top/Article/details/gt2nbtrfqac.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ddubpsfn.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.cucudq.cn/Article/details/gt2rvgsvwjp.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.quarkkingdee.top/Article/details/gt2tuqqqumg.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.nwbrower.top/Article/details/gt2jplthbnj.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.wangshuangyany.cn/Article/details/gt2rhdhqulk.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.hammf.cn/Article/details/gt2jmjrcpha.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.jinqigufen.top/Article/details/gt2pixmfecc.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.yuxming.cn/Article/details/gt2dtjlksct.html

[B02] 多分支 else if / elif
来源：http://dali.cqqwz.cn/Article/details/gt2kjfswuty.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.ivvv.top/Article/details/gt2ctwribrs.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kqeycnqd.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hongshengwenyu.top/Article/details/gt2blmksdka.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.chenjidiqi.icu/Article/details/gt2cjyggxmk.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.havefunace.top/Article/details/gt2twtpgyni.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.smart0.xyz/Article/details/gt2thmiexem.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.yongpay.top/Article/details/gt2lbnrorjk.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.fzhhl.top/Article/details/gt2zaglripn.html

[B03] switch / match / case
来源：http://dali.cashguo.top/Article/details/gt2csfrcpjb.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.zhongyouzk.top/Article/details/gt2uwhvukfj.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.zhixingplan.top/Article/details/gt2idzuzmrs.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.nwbrower.top/Article/details/gt2dhxtyfzg.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.chenzaomai.com/Article/details/gt2ihoaczfi.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jvxtzbrl.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.yj202588.top/Article/details/gt2zuboflmw.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.sufxvd.cn/Article/details/gt2uhpzipia.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.iojbl.cn/Article/details/gt2zxumnmcg.html

[B04] for 计数循环
来源：http://dali.yuanzhike.top/Article/details/gt2sywduwje.html

Py:   for i in range(10): print(i)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dvxbwggt.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.yvedp.cn/Article/details/gt2srclbjkl.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.fengsongda.top/Article/details/gt2erdvbwdh.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.aibaodan.cn/Article/details/gt2emgtumxl.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.nanxinkj.top/Article/details/gt2tpvafomu.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.yangfankeji.com/Article/details/gt2fhpzevon.html

Ruby: 10.times { |i| puts i }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2buukbqtc.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.iojbl.cn/Article/details/gt2rwoanido.html

[B05] 遍历数组 / 列表
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yhudijrs.html

Py:   for item in arr: print(item)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjuurdez.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.chenlongwang.top/Article/details/gt2yxzrzsqs.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.ydzc1.top/Article/details/gt2klsiqmyz.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.gogol.net.cn/Article/details/gt2avldptsu.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.nanxuanxn.top/Article/details/gt2xhvhhlky.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.fzhhl.top/Article/details/gt2mpkawvwt.html

Ruby: arr.each { |item| puts item }
来源：http://dali.cashguo.top/Article/details/gt2xgcmbmyu.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.bjfxy.top/Article/details/gt2xqzlgysr.html

[B06] 遍历字典 / 对象
来源：http://dali.xinyue.icu/Article/details/gt2dhxjgrqu.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.yvedp.cn/Article/details/gt2mevznqcg.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.yvedp.cn/Article/details/gt2udikcife.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhoulong.xyz/Article/details/gt2eabjgvas.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.gotoacloud.top/Article/details/gt2nzforguh.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.yonumen.top/Article/details/gt2rboiisem.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.havefunace.top/Article/details/gt2qzoosrxb.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.jqgufenzy.top/Article/details/gt2gmsuyubv.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.jiagoushi.top/Article/details/gt2uicxwmrh.html

[B07] while 循环
来源：http://dali.gotoacloud.top/Article/details/gt2pwbegspj.html

Py:   while i < 10: i += 1
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zlhojyrw.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.jiagoushi.top/Article/details/gt2doyuptiv.html

JS:   while (i < 10) { i++; }
来源：http://dali.aizwys.cn/Article/details/gt2vsemqlxa.html

TS:   while (i < 10) { i++; }
来源：http://dali.9152youxi.cn/Article/details/gt2gbrfqjqe.html

Java: while (i < 10) { i++; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2piahupst.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.xuetiantiany.cn/Article/details/gt2mjpvelql.html

Ruby: while i < 10; i += 1; end
来源：http://dali.bjfxy.top/Article/details/gt2pqkilzpf.html

C#:   while (i < 10) { i++; }
来源：http://dali.hysaishi.cn/Article/details/gt2lihmbzis.html

[B08] do-while（至少执行一次）
来源：http://dali.yvedp.cn/Article/details/gt2pxpodtnq.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.pengpengdd.cyou/Article/details/gt2nbfkiynp.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dagmewwl.html

JS:   do { i++; } while (i < 10);
来源：http://dali.smart0.xyz/Article/details/gt2gutavdsr.html

TS:   do { i++; } while (i < 10);
来源：http://dali.andypj.xyz/Article/details/gt2cwigoxyq.html

Java: do { i++; } while (i < 10);
来源：http://dali.fengsongda.top/Article/details/gt2wrpnfvia.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.hnxiangtu.top/Article/details/gt2udijdmcc.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.havefunace.top/Article/details/gt2uuwxztkx.html

C#:   do { i++; } while (i < 10);
来源：http://dali.sysykeji.top/Article/details/gt2qprulicj.html

[B09] break 与 continue
来源：http://dali.yuanzhike.top/Article/details/gt2jrnsfvey.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.yvedp.cn/Article/details/gt2avatbppr.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.hywenlv.cn/Article/details/gt2optkhakd.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gzhubu.top/Article/details/gt2kikyataz.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.daria6918.cn/Article/details/gt2mqmyxqup.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cqqwz.cn/Article/details/gt2fipuvrsl.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zhongyouzk.top/Article/details/gt2mxnijwuo.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzfptbij.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ydzc1.top/Article/details/gt2djoreldu.html

[B10] 遍历同时拿索引
来源：http://dali.ehwqpu.com/Article/details/gt2kilegszm.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.yangfankeji.com/Article/details/gt2oyjyjrps.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.ehwqpu.com/Article/details/gt2hckgtdeo.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.nanxinkj.top/Article/details/gt2meqakejj.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.dashuyun.cn/Article/details/gt2clkwnxgi.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2tdimgsra.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.guowangkeji.top/Article/details/gt2borbgwce.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zdqjudy.top/Article/details/gt2hcbluwqm.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.cheryme.top/Article/details/gt2tmuuejml.html

[B11] 生成数字序列 / 区间
来源：http://dali.hammf.cn/Article/details/gt2phrryzrw.html

Py:   list(range(0, 10, 2))
来源：http://dali.hammf.cn/Article/details/gt2gyrrrwnt.html

PHP:  range(0, 10, 2);
来源：http://dali.xinyue.icu/Article/details/gt2siuraqwl.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.sufxvd.cn/Article/details/gt2jjrhzaal.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jinqigufen.top/Article/details/gt2bpoylpyo.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.9152youxi.cn/Article/details/gt2tqmlqdlp.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tlkyddmc.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zdqjudy.top/Article/details/gt2ecbekyga.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.guowangkeji.top/Article/details/gt2mfjrfiuy.html

[B12] 跳出多层循环
来源：http://dali.shanyushiyangtech.top/Article/details/gt2begpuogy.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vcqculpb.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.9152youxi.cn/Article/details/gt2mnnuffcf.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.chenjidiqi.icu/Article/details/gt2rciibayy.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhongyouzk.top/Article/details/gt2vfspczck.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.ehwqpu.com/Article/details/gt2godusibu.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhiwuduotai.top/Article/details/gt2fmeyxhdj.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.ehwqpu.com/Article/details/gt2phfzzagd.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.fzhhl.top/Article/details/gt2jufzgkvl.html

[B13] 判断是否为数字
来源：http://dali.fzhhl.top/Article/details/gt2pvxuzurd.html

Py:   isinstance(x, (int, float))
来源：http://dali.gaohongyu789.top/Article/details/gt2hjcrqatc.html

PHP:  is_numeric($x)
来源：http://dali.andypj.xyz/Article/details/gt2sxyrfcuc.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.bjfxy.top/Article/details/gt2blxpgxge.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.smart0.xyz/Article/details/gt2pymdkiqw.html

Java: x instanceof Number
来源：http://dali.wangdashe.top/Article/details/gt2umejixap.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.hysaishi.cn/Article/details/gt2ichvklqu.html

Ruby: x.is_a?(Numeric)
来源：http://dali.haohaochexian.top/Article/details/gt2rogmkkpv.html

C#:   x is int or double or decimal
来源：http://dali.jqgufenzy.top/Article/details/gt2ugubzvvq.html

[B14] 判断值是否在集合内
来源：http://dali.yonumen.top/Article/details/gt2xuylprjk.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.feifeiyinyue.top/Article/details/gt2hdkaygab.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yuxming.cn/Article/details/gt2jgpsnnum.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yj202588.top/Article/details/gt2cdzsizrf.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.sxryk.cn/Article/details/gt2nccrswpa.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yuanzhike.top/Article/details/gt2hasfnljr.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.xinyue.icu/Article/details/gt2lxicjvsz.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.mhx1999.top/Article/details/gt2ieufmkds.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.xuanzx.com/Article/details/gt2brggkzpb.html

[B15] 布尔运算与取反
来源：http://dali.tianlin.xyz/Article/details/gt2auzgumux.html

Py:   a and b or not c
来源：http://dali.feifeiyinyue.top/Article/details/gt2docybflp.html

PHP:  $a && $b || !$c
来源：http://dali.zdqjudy.top/Article/details/gt2yqnetjqs.html

JS:   a && b || !c
来源：http://dali.wangdashe.top/Article/details/gt2jffyvchb.html

TS:   a && b || !c
来源：http://dali.316326.xyz/Article/details/gt2dnktaess.html

Java: a && b || !c
来源：http://dali.9152youxi.cn/Article/details/gt2nwjggwro.html

Go:   a && b || !c
来源：http://dali.hammf.cn/Article/details/gt2ruvfdwsz.html

Ruby: a && b || !c
来源：http://dali.yanxiufei.cn/Article/details/gt2fppcowvl.html

C#:   a && b || !c
来源：http://dali.shzxlz.cn/Article/details/gt2bwfufuph.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.nanxinkj.top/Article/details/gt2sebuypyu.html

Py:   if not data: return
来源：http://dali.zhoulong.xyz/Article/details/gt2wnqjflse.html

PHP:  if (!$data) { return; }
来源：http://dali.xziqi.cn/Article/details/gt2ebeqtqkg.html

JS:   if (!data) return;
来源：http://dali.feifeiyinyue.top/Article/details/gt2rkjgzsou.html

TS:   if (!data) return;
来源：http://dali.fengsongda.top/Article/details/gt2tfevkhxa.html

Java: if (data == null) return;
来源：http://dali.sxryk.cn/Article/details/gt2ivetaisx.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2ebzsigxq.html

Ruby: return if data.nil?
来源：http://dali.zhoulong.xyz/Article/details/gt2zpyyicso.html

C#:   if (data == null) return;
来源：http://dali.shuidangran.top/Article/details/gt2jjwwnhrs.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2vmcvbxdk.html

C. 函数与作用域
来源：http://dali.ivvv.top/Article/details/gt2ryeaushw.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2dkamdcii.html

[C01] 定义函数
来源：http://dali.c1oappe.top/Article/details/gt2urvyrysv.html

Py:   def add(a, b): return a + b
来源：http://dali.bjfxy.top/Article/details/gt2efykwdvl.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.vqdsnc.cn/Article/details/gt2pgprenmw.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.shuidangran.top/Article/details/gt2rtdsxdaf.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2lfjvmutk.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.iojbl.cn/Article/details/gt2eeazstyf.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.guowangkeji.top/Article/details/gt2gkwvvymj.html

Ruby: def add(a, b); a + b; end
来源：http://dali.cucudq.cn/Article/details/gt2dhzquzhk.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.wangdashe.top/Article/details/gt2quvqccuy.html

[C02] 默认参数
来源：http://dali.yanxiufei.cn/Article/details/gt2bphjczeu.html

Py:   def greet(name="World"): return name
来源：http://dali.jiagoushi.top/Article/details/gt2smtkppzg.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.haohaochexian.top/Article/details/gt2chjxslnv.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.fengsongda.top/Article/details/gt2ezdiswzn.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jqgfzy.top/Article/details/gt2cxtsqfyj.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lufpemgk.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yj202588.top/Article/details/gt2nbssfsgc.html

Ruby: def greet(name = "World") = name
来源：http://dali.daxiang520.top/Article/details/gt2drvvetwd.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.tianlin.xyz/Article/details/gt2efihpaid.html

[C03] 可变参数
来源：http://dali.guannengcc.top/Article/details/gt2xijkxmzk.html

Py:   def total(*args): return sum(args)
来源：http://dali.dianchejie.cn/Article/details/gt2xgtadesf.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ypjbulnd.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xinyue.icu/Article/details/gt2ycclvnyc.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2lxcblpdw.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.redwolf501.top/Article/details/gt2exlonfop.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.kuanghao11.cn/Article/details/gt2ozdggqdx.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.ivvv.top/Article/details/gt2jxusjxwy.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jqgufenzy.top/Article/details/gt2bkkdsvub.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yvedp.cn/Article/details/gt2rtldvlul.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.xziqi.cn/Article/details/gt2stdpkjuk.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.haohaochexian.top/Article/details/gt2tellklqx.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.fzhhl.top/Article/details/gt2clflfkux.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yueranfly.top/Article/details/gt2aajbdfbk.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.tian-w.cn/Article/details/gt2iwdxqmqt.html


<!-- 参考信息 -->