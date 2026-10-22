代发 wailian999

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.nanxinkj.top/Article/details/gt2hnqnhyjs.html

Ruby: "Hello, #{name}!"
来源：http://dali.haohaochexian.top/Article/details/gt2yqqtabbp.html

C#:   $"Hello, {name}!"
来源：http://dali.daxiang520.top/Article/details/gt2dtbsasmu.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lfilrnxo.html

Py:   "第一行\n第二行"
来源：http://dali.fzhhl.top/Article/details/gt2sexspmqe.html

PHP:  "第一行\n第二行"
来源：http://dali.yj202588.top/Article/details/gt2whphffbp.html

JS:   "第一行\n第二行"
来源：http://dali.xuetiantiany.cn/Article/details/gt2ukmgujfl.html

TS:   "第一行\n第二行"
来源：http://dali.jiagoushi.top/Article/details/gt2mwbqkpkl.html

Java: "第一行\n第二行"
来源：http://dali.ybcxt.top/Article/details/gt2dgtynoup.html

Go:   "第一行\n第二行"
来源：http://dali.chenlongwang.top/Article/details/gt2djkovxxr.html

Ruby: "第一行\n第二行"
来源：http://dali.c1oappe.top/Article/details/gt2shxfxdgl.html

C#:   "第一行\n第二行"
来源：http://dali.quarkkingdee.top/Article/details/gt2yxqgecws.html

[A14] 注释写法
来源：http://dali.hfpthk.cn/Article/details/gt2kfmrjfku.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.ppjwa.cn/Article/details/gt2alokymav.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.dianchejie.cn/Article/details/gt2zrekqmow.html

JS:   // 单行；/* 多行 */
来源：http://dali.smart0.xyz/Article/details/gt2tpcjzetg.html

TS:   // 单行；/* 多行 */
来源：http://dali.mhx1999.top/Article/details/gt2platuajj.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.shzxlz.cn/Article/details/gt2xzqmhvpx.html

Go:   // 单行；/* 多行 */
来源：http://dali.daxiang520.top/Article/details/gt2rrnmarnl.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.sxryk.cn/Article/details/gt2klqmsheo.html

C#:   // 单行；/* 多行 */
来源：http://dali.dashuyun.cn/Article/details/gt2kinfhhhu.html

[A15] 空值判断与默认值
来源：http://dali.hammf.cn/Article/details/gt2ryttujrz.html

Py:   value = data or "默认值"
来源：http://dali.shzxlz.cn/Article/details/gt2mupcfbjq.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.hfpthk.cn/Article/details/gt2sxskgunu.html

JS:   const value = data ?? "默认值";
来源：http://dali.jiagoushi.top/Article/details/gt2lmlugpgd.html

TS:   const value = data ?? "默认值";
来源：http://dali.svipenyu.cn/Article/details/gt2rwgjfsvl.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.feifeiyinyue.top/Article/details/gt2kahgyxvi.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.daxiang520.top/Article/details/gt2xeowgoic.html

Ruby: value = data || "默认值"
来源：http://dali.yj20258888.top/Article/details/gt2dgysupri.html

C#:   var value = data ?? "默认值";
来源：http://dali.tian-w.cn/Article/details/gt2sklqqutl.html

[A16] 真假值判断规则
来源：http://dali.ivvv.top/Article/details/gt2sfvcunni.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.9152youxi.cn/Article/details/gt2kyouhhyy.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.yuxming.cn/Article/details/gt2kdyybqwz.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.yvedp.cn/Article/details/gt2mougupco.html

TS:   if (!x) {}
来源：http://dali.bjfxy.top/Article/details/gt2jfaxzqrq.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.smart0.xyz/Article/details/gt2qybdrcbe.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.0kj1m.cn/Article/details/gt2aibpputz.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.chenjidiqi.icu/Article/details/gt2fwygsirj.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.sweek.top/Article/details/gt2jnrkkiqy.html

[A17] 位运算
来源：http://dali.aibaodan.cn/Article/details/gt2hrtyslup.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhixingplan.top/Article/details/gt2zkougnnn.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.gotoacloud.top/Article/details/gt2qpckrive.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.feifeiyinyue.top/Article/details/gt2xzwvarqj.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.yanxiufei.cn/Article/details/gt2vqjbdapg.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yuanzhike.top/Article/details/gt2jsriuvsh.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.xylfe.cn/Article/details/gt2qldrrdii.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kagovrqe.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yj202588.top/Article/details/gt2mkcfcfms.html

[A18] 字符与 ASCII 码互转
来源：http://dali.daxiang520.top/Article/details/gt2lpyxoxof.html

Py:   ord("A"); chr(65)
来源：http://dali.hnxiangtu.top/Article/details/gt2qakcefxv.html

PHP:  ord("A"); chr(65)
来源：http://dali.meibo888.top/Article/details/gt2tmjqehyg.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.birdmap.top/Article/details/gt2maohzbpa.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.yj20258.top/Article/details/gt2mkfdygxt.html

Java: (int) 'A'; (char) 65
来源：http://dali.zhiwuduotai.top/Article/details/gt2ahthcbaa.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.smart0.xyz/Article/details/gt2texbieyo.html

Ruby: "A".ord; 65.chr
来源：http://dali.aizwys.cn/Article/details/gt2pxzafjgc.html

C#:   (int)'A'; (char)65
来源：http://dali.yangfankeji.com/Article/details/gt2dbhiincn.html

[A19] 交换两个变量
来源：http://dali.c1oappe.top/Article/details/gt2kmqhgxcd.html

Py:   a, b = b, a
来源：http://dali.chenjidiqi.icu/Article/details/gt2bouxcxxm.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.ybcxt.top/Article/details/gt2ulqhftdn.html

JS:   [a, b] = [b, a];
来源：http://dali.zhijiandao.cn/Article/details/gt2hyjarxlc.html

TS:   [a, b] = [b, a];
来源：http://dali.cashguo.top/Article/details/gt2drobiyew.html

Java: int t = a; a = b; b = t;
来源：http://dali.birdmap.top/Article/details/gt2mzpjozub.html

Go:   a, b = b, a
来源：http://dali.wangdashe.top/Article/details/gt2miplgudw.html

Ruby: a, b = b, a
来源：http://dali.yueranfly.top/Article/details/gt2bfqsaltd.html

C#:   (a, b) = (b, a);
来源：http://dali.redwolf501.top/Article/details/gt2xbpentam.html

[A20] 读取标准输入
来源：http://dali.zycfv.cn/Article/details/gt2mdfpcoaw.html

Py:   name = input("请输入：")
来源：http://dali.cheryme.top/Article/details/gt2wyesiwzd.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.daria6918.cn/Article/details/gt2yfdiapwq.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.feifeiyinyue.top/Article/details/gt2yepvpeuf.html

TS:   // Node.js：readline 模块
来源：http://dali.jqgufenzy.top/Article/details/gt2znavbyoe.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.chenlongwang.top/Article/details/gt2qmkuqnof.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.jianghu66.top/Article/details/gt2bhcusbrt.html

Ruby: gets.chomp
来源：http://dali.gzhubu.top/Article/details/gt2ztszwgpq.html

C#:   Console.ReadLine();
来源：http://dali.cucudq.cn/Article/details/gt2qssawzcc.html

[A21] 保留指定小数位输出
来源：http://dali.zhengqikj.top/Article/details/gt2nntfmayv.html

Py:   f"{3.14159:.2f}"
来源：http://dali.jqgfzy.top/Article/details/gt2amwxeyle.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.zhengqikj.top/Article/details/gt2gwlbkebg.html

JS:   (3.14159).toFixed(2)
来源：http://dali.hnxiangtu.top/Article/details/gt2iyilhifa.html

TS:   (3.14159).toFixed(2)
来源：http://dali.aibaodan.cn/Article/details/gt2xjsdumul.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.zhixingplan.top/Article/details/gt2onklxpek.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.9152youxi.cn/Article/details/gt2eyksltzx.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.316326.xyz/Article/details/gt2lfaeoosc.html

C#:   3.14159.ToString("F2")
来源：http://dali.tian-w.cn/Article/details/gt2mmyxhldl.html

[A22] 获取字符串长度
来源：http://dali.kuanghao11.cn/Article/details/gt2pfvzqvvn.html

Py:   len(s)
来源：http://dali.ydzc1.top/Article/details/gt2alolbpfc.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.yanxiufei.cn/Article/details/gt2xxxeettk.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.kuanghao11.cn/Article/details/gt2khyyyved.html

TS:   s.length
来源：http://dali.dianchejie.cn/Article/details/gt2inqnwhdr.html

Java: s.length()
来源：http://dali.kuanghao11.cn/Article/details/gt2gqjchjvj.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.jianghu66.top/Article/details/gt2dirvhvqo.html

Ruby: s.length
来源：http://dali.xinyue.icu/Article/details/gt2fmcuemgh.html

C#:   s.Length
来源：http://dali.cdnleiting.top/Article/details/gt2duobbvsq.html

[A23] 大小写转换
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rohvhiec.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.birdmap.top/Article/details/gt2aqegubir.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.snrcjt.cn/Article/details/gt2hmtlluui.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xalgchup.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.wangdashe.top/Article/details/gt2utjphbec.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.gaohongyu789.top/Article/details/gt2mvcpcgqx.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.ivvv.top/Article/details/gt2znnyeqlx.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.xziqi.cn/Article/details/gt2pkjzmcgg.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2relxbath.html

[A24] 去除首尾空白
来源：http://dali.snrcjt.cn/Article/details/gt2nvteeqjz.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.shzxlz.cn/Article/details/gt2nyihelai.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.jinqigfzy.top/Article/details/gt2qwfebjqj.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.haohaochexian.top/Article/details/gt2khxehuva.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.quarkkingdee.top/Article/details/gt2jjfqjpgh.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.yj202588.top/Article/details/gt2orugsulf.html

Go:   strings.TrimSpace(s)
来源：http://dali.sxryk.cn/Article/details/gt2hqttacvk.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.jqgfzy.top/Article/details/gt2yvgnzpxw.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.sweek.top/Article/details/gt2lrpipjei.html

[A25] 字符串比较
来源：http://dali.aibaodan.cn/Article/details/gt2xuupcrzd.html

Py:   s1 == s2; s1 != s2
来源：http://dali.tanke756.top/Article/details/gt2sqevzjyr.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.sysykeji.top/Article/details/gt2jmgeriow.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.jyoumei.cn/Article/details/gt2arycsfcg.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yj20258.top/Article/details/gt2kwmolhxh.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2myyuubnw.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.dashuyun.cn/Article/details/gt2wndtcjmr.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.gzhubu.top/Article/details/gt2oogsxpwq.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.ppjwa.cn/Article/details/gt2auihqgax.html

[A26] 类型转换总览
来源：http://dali.wangdashe.top/Article/details/gt2mlkguarp.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.ivvv.top/Article/details/gt2ftybbbxf.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.vqdsnc.cn/Article/details/gt2ibudkqmq.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.hnqzz.top/Article/details/gt2xjqgdwqi.html

TS:   Number() String() Boolean() x as number
来源：http://dali.haohaochexian.top/Article/details/gt2tiujyrob.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.jqgufenzy.top/Article/details/gt2uqfvcjio.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.ydzc1.top/Article/details/gt2yfnhwmdq.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.cdnleiting.top/Article/details/gt2ojubcqnw.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.jiagoushi.top/Article/details/gt2qmciedex.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2sejxjcix.html

B. 流程控制
来源：http://dali.dianchejie.cn/Article/details/gt2dwkdjaxq.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2bebxaerf.html

[B01] 条件判断 if / else
来源：http://dali.zhongyouzk.top/Article/details/gt2imosntfs.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.meibo888.top/Article/details/gt2hdmozkkp.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.sweek.top/Article/details/gt2cruodazg.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.cheryme.top/Article/details/gt2yekutngm.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jiagoushi.top/Article/details/gt2sxzxhqgd.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.yangfankeji.com/Article/details/gt2pvggrvvq.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.snrcjt.cn/Article/details/gt2qkwyojtb.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.sxryk.cn/Article/details/gt2farmbari.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.cucudq.cn/Article/details/gt2wzdpmulc.html

[B02] 多分支 else if / elif
来源：http://dali.gogol.net.cn/Article/details/gt2efboxbrw.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.xziqi.cn/Article/details/gt2vhaudqfa.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2noswvqtp.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhongyouzk.top/Article/details/gt2cenzwudx.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.wangshuangyany.cn/Article/details/gt2lfryziet.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yangfankeji.com/Article/details/gt2qjemktwz.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.jiagoushi.top/Article/details/gt2ofbzxput.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.zycfv.cn/Article/details/gt2jiaduqbx.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.fzhhl.top/Article/details/gt2hkkybpdr.html

[B03] switch / match / case
来源：http://dali.chenjidiqi.icu/Article/details/gt2pyrhzete.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.hysaishi.cn/Article/details/gt2asfbcgjv.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.smart0.xyz/Article/details/gt2wvirjqqy.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zhoulong.xyz/Article/details/gt2oimgmjly.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yvedp.cn/Article/details/gt2nprumbgf.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.svipenyu.cn/Article/details/gt2gbfkdpql.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.chenjidiqi.icu/Article/details/gt2gmdfcnum.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.zycfv.cn/Article/details/gt2dlaxoogx.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.ehwqpu.com/Article/details/gt2aktxssum.html

[B04] for 计数循环
来源：http://dali.andypj.xyz/Article/details/gt2mbkiyfah.html

Py:   for i in range(10): print(i)
来源：http://dali.guowangkeji.top/Article/details/gt2eecyujsm.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.fengsongda.top/Article/details/gt2acxllxdy.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jqgufenzy.top/Article/details/gt2iekxkyqo.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.ydzc1.top/Article/details/gt2naxayzov.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.zhengqikj.top/Article/details/gt2smupardl.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.xuetiantiany.cn/Article/details/gt2iayuamku.html

Ruby: 10.times { |i| puts i }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vpzerxel.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.shuidangran.top/Article/details/gt2ilqvaoop.html

[B05] 遍历数组 / 列表
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dsbapuqv.html

Py:   for item in arr: print(item)
来源：http://dali.ppjwa.cn/Article/details/gt2ncoazwti.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.jqgfzy.top/Article/details/gt2qsjxwscp.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.jlsjyb.cn/Article/details/gt2tzqxrpwy.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.bjfxy.top/Article/details/gt2ppwyztzp.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.shzxlz.cn/Article/details/gt2jjkkjasv.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.pengpengdd.cyou/Article/details/gt2vvvuuyld.html

Ruby: arr.each { |item| puts item }
来源：http://dali.0kj1m.cn/Article/details/gt2ozsiucvj.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hnzepafh.html

[B06] 遍历字典 / 对象
来源：http://dali.feifeiyinyue.top/Article/details/gt2ipngvfjj.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.jqgfzy.top/Article/details/gt2qwzuftnp.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.zhengqikj.top/Article/details/gt2cdoddsrg.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yj20258888.top/Article/details/gt2lptuhrxz.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.daxiang520.top/Article/details/gt2nzdmopqr.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.aibaodan.cn/Article/details/gt2bchuddcr.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2streunhe.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.zhengqikj.top/Article/details/gt2iewbspqc.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2faotfazp.html

[B07] while 循环
来源：http://dali.hongshengwenyu.top/Article/details/gt2zsgvgeur.html

Py:   while i < 10: i += 1
来源：http://dali.cqqwz.cn/Article/details/gt2cbjggdel.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.yueranfly.top/Article/details/gt2vdibxjxj.html

JS:   while (i < 10) { i++; }
来源：http://dali.nanxuanxn.top/Article/details/gt2oufqvtdt.html

TS:   while (i < 10) { i++; }
来源：http://dali.yuxming.cn/Article/details/gt2jmumnaka.html

Java: while (i < 10) { i++; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2xjzjegqh.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.ehwqpu.com/Article/details/gt2ltdicgim.html

Ruby: while i < 10; i += 1; end
来源：http://dali.ydzc1.top/Article/details/gt2eptwlicy.html

C#:   while (i < 10) { i++; }
来源：http://dali.hammf.cn/Article/details/gt2kbyukvyl.html

[B08] do-while（至少执行一次）
来源：http://dali.meibo888.top/Article/details/gt2eqtfwumb.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.jinqigufen.top/Article/details/gt2lsxxncse.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uijrhqvb.html

JS:   do { i++; } while (i < 10);
来源：http://dali.snrcjt.cn/Article/details/gt2ffjjgasb.html

TS:   do { i++; } while (i < 10);
来源：http://dali.cashguo.top/Article/details/gt2yglwybdg.html

Java: do { i++; } while (i < 10);
来源：http://dali.feifeiyinyue.top/Article/details/gt2zwvcejgg.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.hywenlv.cn/Article/details/gt2pwuvhoqw.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.yvedp.cn/Article/details/gt2nvxhamxn.html

C#:   do { i++; } while (i < 10);
来源：http://dali.jianghu66.top/Article/details/gt2ccxymrtp.html

[B09] break 与 continue
来源：http://dali.hfpthk.cn/Article/details/gt2bgjdvkoe.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.ybcxt.top/Article/details/gt2noqvhoif.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.svipenyu.cn/Article/details/gt2wfkgfaqj.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yonumen.top/Article/details/gt2klfzpvcu.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.snrcjt.cn/Article/details/gt2hnokdynq.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jqgfzy.top/Article/details/gt2juxnxaii.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.daria6918.cn/Article/details/gt2qgypajer.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.iojbl.cn/Article/details/gt2aqwpvlmx.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fndamnbp.html

[B10] 遍历同时拿索引
来源：http://dali.kuanghao11.cn/Article/details/gt2pdkqidku.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxurzihe.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.aibaodan.cn/Article/details/gt2rgvvqwzz.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.fengsongda.top/Article/details/gt2lrwfasep.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.cucudq.cn/Article/details/gt2pssbipwd.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yj20258888.top/Article/details/gt2xfutorgj.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zhixingplan.top/Article/details/gt2alofixny.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.yj202588.top/Article/details/gt2iowlzwoc.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.cashguo.top/Article/details/gt2mwsvbqrh.html

[B11] 生成数字序列 / 区间
来源：http://dali.ppjwa.cn/Article/details/gt2lnvisfbg.html

Py:   list(range(0, 10, 2))
来源：http://dali.shuidangran.top/Article/details/gt2bzhqqpuf.html

PHP:  range(0, 10, 2);
来源：http://dali.jqgfzy.top/Article/details/gt2yomhqcxw.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.gaohongyu789.top/Article/details/gt2mceegwyq.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.0kj1m.cn/Article/details/gt2manvnpgp.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.ehwqpu.com/Article/details/gt2wjyuhxup.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.haohaochexian.top/Article/details/gt2aduhetuo.html

Ruby: (0...10).step(2).to_a
来源：http://dali.iojbl.cn/Article/details/gt2xpzvprkk.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.fzhhl.top/Article/details/gt2wmysgbgd.html

[B12] 跳出多层循环
来源：http://dali.nwbrower.top/Article/details/gt2yvfddena.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.hysaishi.cn/Article/details/gt2icfuwqco.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.chenlongwang.top/Article/details/gt2ymsyzlsc.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.wangshuangyany.cn/Article/details/gt2jelfgfwz.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhoulong.xyz/Article/details/gt2yhbgosei.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.pengpengdd.cyou/Article/details/gt2fhvmlqqi.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.yongpay.top/Article/details/gt2wbghdzjw.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.ybcxt.top/Article/details/gt2lnpdtfsy.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fqtmzgzv.html

[B13] 判断是否为数字
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iyxzawil.html

Py:   isinstance(x, (int, float))
来源：http://dali.wangdashe.top/Article/details/gt2bjdbvozo.html

PHP:  is_numeric($x)
来源：http://dali.9152youxi.cn/Article/details/gt2lpnaygge.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhongyouzk.top/Article/details/gt2qorgsing.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.fzhhl.top/Article/details/gt2spixgrul.html

Java: x instanceof Number
来源：http://dali.kuanghao11.cn/Article/details/gt2iktyncxe.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.fengsongda.top/Article/details/gt2rayddpqg.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yuanzhike.top/Article/details/gt2tzxrrhgj.html

C#:   x is int or double or decimal
来源：http://dali.feifeiyinyue.top/Article/details/gt2okgadhgg.html

[B14] 判断值是否在集合内
来源：http://dali.zycfv.cn/Article/details/gt2ojnkerai.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.aibaodan.cn/Article/details/gt2bwzwutsc.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.daxiang520.top/Article/details/gt2hplslkaf.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.sxryk.cn/Article/details/gt2lpvzdakm.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.guowangkeji.top/Article/details/gt2lascdmda.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhongyouzk.top/Article/details/gt2dyyorozo.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.ppjwa.cn/Article/details/gt2wprndzzy.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.hywenlv.cn/Article/details/gt2kevhruwi.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yvedp.cn/Article/details/gt2ifyiaznd.html

[B15] 布尔运算与取反
来源：http://dali.zycfv.cn/Article/details/gt2ewghcyef.html

Py:   a and b or not c
来源：http://dali.ydzc1.top/Article/details/gt2jjksymid.html

PHP:  $a && $b || !$c
来源：http://dali.daria6918.cn/Article/details/gt2bfyjttqo.html

JS:   a && b || !c
来源：http://dali.fzhhl.top/Article/details/gt2xgrypzyd.html

TS:   a && b || !c
来源：http://dali.kuanghao11.cn/Article/details/gt2vymekdom.html

Java: a && b || !c
来源：http://dali.sufxvd.cn/Article/details/gt2evtraimm.html

Go:   a && b || !c
来源：http://dali.yj20258888.top/Article/details/gt2cpeubcjj.html

Ruby: a && b || !c
来源：http://dali.daxiang520.top/Article/details/gt2rlmwbewg.html

C#:   a && b || !c
来源：http://dali.yj20258.top/Article/details/gt2hibeooiz.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhengqikj.top/Article/details/gt2bszwxpxi.html

Py:   if not data: return
来源：http://dali.hfpthk.cn/Article/details/gt2enxujyyq.html

PHP:  if (!$data) { return; }
来源：http://dali.c1oappe.top/Article/details/gt2wsyoregj.html

JS:   if (!data) return;
来源：http://dali.sufxvd.cn/Article/details/gt2argldsla.html

TS:   if (!data) return;
来源：http://dali.xuetiantiany.cn/Article/details/gt2aaaryhaq.html

Java: if (data == null) return;
来源：http://dali.tanke756.top/Article/details/gt2akoiaekj.html

Go:   if data == nil { return }
来源：http://dali.gotoacloud.top/Article/details/gt2aeqxqfmg.html

Ruby: return if data.nil?
来源：http://dali.guowangkeji.top/Article/details/gt2wazndhcm.html

C#:   if (data == null) return;
来源：http://dali.zhoulong.xyz/Article/details/gt2ebbimgse.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2lskkvqod.html

C. 函数与作用域
来源：http://dali.hnxiangtu.top/Article/details/gt2ehvuqwpi.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2fmtjaski.html

[C01] 定义函数
来源：http://dali.zhoulong.xyz/Article/details/gt2wyokxsqn.html

Py:   def add(a, b): return a + b
来源：http://dali.fengsongda.top/Article/details/gt2kgprpfhc.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gaohongyu789.top/Article/details/gt2qyqbaoai.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2izsuslwi.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ydzc1.top/Article/details/gt2wfvuuyig.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwcptvoe.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jqgufenzy.top/Article/details/gt2zrzjaykp.html

Ruby: def add(a, b); a + b; end
来源：http://dali.chenlongwang.top/Article/details/gt2eywsncdu.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yonumen.top/Article/details/gt2zatmplfz.html

[C02] 默认参数
来源：http://dali.sweek.top/Article/details/gt2dmrvaqyi.html

Py:   def greet(name="World"): return name
来源：http://dali.jinqigfzy.top/Article/details/gt2fqzhamjz.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zdqjudy.top/Article/details/gt2bbkjjbrv.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sjbhzuqw.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2ouyubpuv.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhixingplan.top/Article/details/gt2ovevnswb.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.xinyue.icu/Article/details/gt2albhkfrr.html

Ruby: def greet(name = "World") = name
来源：http://dali.daxiang520.top/Article/details/gt2xuqpfgqq.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.ydzc1.top/Article/details/gt2nssdtcdp.html

[C03] 可变参数
来源：http://dali.yvedp.cn/Article/details/gt2yzzsrvax.html

Py:   def total(*args): return sum(args)
来源：http://dali.yongpay.top/Article/details/gt2kmomyigh.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.hammf.cn/Article/details/gt2xsedifol.html


<!-- 参考信息 -->