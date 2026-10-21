代发 wailian999

[A14] 注释写法
来源：http://dali.shzxlz.cn/Article/details/gtsyfyozvj.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.shuidangran.top/Article/details/gtczssfwkk.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhixingplan.top/Article/details/gtmrvmeqwt.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrozkajhg.html

TS:   // 单行；/* 多行 */
来源：http://dali.ybcxt.top/Article/details/gtmlhneogy.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.sweek.top/Article/details/gtjgaltnfi.html

Go:   // 单行；/* 多行 */
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtutbkepsl.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.gaohongyu789.top/Article/details/gtlytnuuqd.html

C#:   // 单行；/* 多行 */
来源：http://dali.xinyue.icu/Article/details/gtqzhcrzob.html

[A15] 空值判断与默认值
来源：http://dali.ybcxt.top/Article/details/gtobarlutv.html

Py:   value = data or "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gtxmctkeap.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.snrcjt.cn/Article/details/gtuydagmqm.html

JS:   const value = data ?? "默认值";
来源：http://dali.gotoacloud.top/Article/details/gtmrjytudk.html

TS:   const value = data ?? "默认值";
来源：http://dali.sweek.top/Article/details/gtleihyhuc.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.yanxiufei.cn/Article/details/gtslqvnnly.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zdqjudy.top/Article/details/gtuevavukm.html

Ruby: value = data || "默认值"
来源：http://dali.nanxinkj.top/Article/details/gtzrgsgawr.html

C#:   var value = data ?? "默认值";
来源：http://dali.guowangkeji.top/Article/details/gtlrgoirbr.html

[A16] 真假值判断规则
来源：http://dali.gaohongyu789.top/Article/details/gtrhppokrw.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.jqgufenzy.top/Article/details/gtcwpmeghg.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.yj20258.top/Article/details/gtvjncgxim.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.nanxinkj.top/Article/details/gtckcuyeol.html

TS:   if (!x) {}
来源：http://dali.nwbrower.top/Article/details/gtjpffceah.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.nwbrower.top/Article/details/gthcjfqeal.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.cdnleiting.top/Article/details/gtadzcyalz.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.zhijiandao.cn/Article/details/gtapdcvnzk.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.shzxlz.cn/Article/details/gtntdyevfb.html

[A17] 位运算
来源：http://dali.xuanzx.com/Article/details/gthnfxzmbz.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ivvv.top/Article/details/gtkigmkwlh.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.svipenyu.cn/Article/details/gtqlchxntz.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.dianchejie.cn/Article/details/gtohidlmqo.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.yangfankeji.com/Article/details/gtywqtmnjb.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.smart0.xyz/Article/details/gtqdnfkjra.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.nwbrower.top/Article/details/gtknoxkkmb.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhengqikj.top/Article/details/gtwfgwhurw.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.nanxuanxn.top/Article/details/gtmfobaiuk.html

[A18] 字符与 ASCII 码互转
来源：http://dali.chenzaomai.com/Article/details/gtqwmvvayb.html

Py:   ord("A"); chr(65)
来源：http://dali.chenlongwang.top/Article/details/gtzybhgncc.html

PHP:  ord("A"); chr(65)
来源：http://dali.yueranfly.top/Article/details/gtndlnosgy.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.pengpengdd.cyou/Article/details/gtalnyljcw.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.jinqigfzy.top/Article/details/gtxejsoqsn.html

Java: (int) 'A'; (char) 65
来源：http://dali.jiagoushi.top/Article/details/gthqshdoum.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.9152youxi.cn/Article/details/gtatykkshc.html

Ruby: "A".ord; 65.chr
来源：http://dali.ivvv.top/Article/details/gtcgtlmioj.html

C#:   (int)'A'; (char)65
来源：http://dali.zhaomingkeji.xyz/Article/details/gtluzncxdg.html

[A19] 交换两个变量
来源：http://dali.yongpay.top/Article/details/gttrsfdqfm.html

Py:   a, b = b, a
来源：http://dali.chenlongwang.top/Article/details/gtlmqlremc.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.daria6918.cn/Article/details/gtfbmuynga.html

JS:   [a, b] = [b, a];
来源：http://dali.redwolf501.top/Article/details/gttflxupwt.html

TS:   [a, b] = [b, a];
来源：http://dali.shuidangran.top/Article/details/gtvyufrhqo.html

Java: int t = a; a = b; b = t;
来源：http://dali.gaohongyu789.top/Article/details/gtcrgzffdk.html

Go:   a, b = b, a
来源：http://dali.cheryme.top/Article/details/gtpsjwhzgc.html

Ruby: a, b = b, a
来源：http://dali.hywenlv.cn/Article/details/gtfhunlvvx.html

C#:   (a, b) = (b, a);
来源：http://dali.ybcxt.top/Article/details/gtoofbtsgo.html

[A20] 读取标准输入
来源：http://dali.haohaochexian.top/Article/details/gtivjmlhrs.html

Py:   name = input("请输入：")
来源：http://dali.cqqwz.cn/Article/details/gtjepyvpbc.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.shzxlz.cn/Article/details/gtfzstjohh.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.guowangkeji.top/Article/details/gtchbsgwex.html

TS:   // Node.js：readline 模块
来源：http://dali.nwbrower.top/Article/details/gtofzuxknq.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.smart0.xyz/Article/details/gtukqioxgd.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.tanke756.top/Article/details/gtgobgvuae.html

Ruby: gets.chomp
来源：http://dali.xziqi.cn/Article/details/gtjafsvkwq.html

C#:   Console.ReadLine();
来源：http://dali.daxiang520.top/Article/details/gtsnvlatgj.html

[A21] 保留指定小数位输出
来源：http://dali.tian-w.cn/Article/details/gttviopajl.html

Py:   f"{3.14159:.2f}"
来源：http://dali.redwolf501.top/Article/details/gtzqdmlcxs.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.yanxiufei.cn/Article/details/gtgjxqqvcn.html

JS:   (3.14159).toFixed(2)
来源：http://dali.svipenyu.cn/Article/details/gtihrxkeid.html

TS:   (3.14159).toFixed(2)
来源：http://dali.havefunace.top/Article/details/gtnpifivuf.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.havefunace.top/Article/details/gthsviozfy.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkiexvmqv.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.zhiwuduotai.top/Article/details/gtvrldyxwq.html

C#:   3.14159.ToString("F2")
来源：http://dali.tian-w.cn/Article/details/gtzgkevadv.html

[A22] 获取字符串长度
来源：http://dali.zhongyouzk.top/Article/details/gtosvxojfb.html

Py:   len(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtezzfssal.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.xinyue.icu/Article/details/gtzccbdzzp.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.chenjidiqi.icu/Article/details/gteyujfnub.html

TS:   s.length
来源：http://dali.zhixingplan.top/Article/details/gtpvkbkase.html

Java: s.length()
来源：http://dali.haohaochexian.top/Article/details/gtvijexklr.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.xylfe.cn/Article/details/gtrhezwaue.html

Ruby: s.length
来源：http://dali.gzhubu.top/Article/details/gtqlaivewb.html

C#:   s.Length
来源：http://dali.ehwqpu.com/Article/details/gtmvmjcffy.html

[A23] 大小写转换
来源：http://dali.nanxinkj.top/Article/details/gtzsiggynt.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.shanyushiyangtech.top/Article/details/gtwvkdwubg.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.yvedp.cn/Article/details/gtwxntjvlo.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.cheryme.top/Article/details/gtbpeoczgt.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.cashguo.top/Article/details/gtaebuglov.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhiwuduotai.top/Article/details/gtcovctaua.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.redwolf501.top/Article/details/gthlusvmvh.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.zhixingplan.top/Article/details/gtwlqkgimt.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.fzhhl.top/Article/details/gtuuplxahq.html

[A24] 去除首尾空白
来源：http://dali.birdmap.top/Article/details/gtswjhbbqh.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.vqdsnc.cn/Article/details/gtufzdqrjx.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.yueranfly.top/Article/details/gtukwbbpff.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yanxiufei.cn/Article/details/gtqwwivggx.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.vqdsnc.cn/Article/details/gtfaeyxsya.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.gotoacloud.top/Article/details/gtxrlvgqde.html

Go:   strings.TrimSpace(s)
来源：http://dali.bjfxy.top/Article/details/gtqqwrxqoi.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.yj20258888.top/Article/details/gtukxyzeum.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.guannengcc.top/Article/details/gthdzziapc.html

[A25] 字符串比较
来源：http://dali.snrcjt.cn/Article/details/gtsvxwscsf.html

Py:   s1 == s2; s1 != s2
来源：http://dali.ybcxt.top/Article/details/gtewcoekql.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.ivvv.top/Article/details/gtwgkxtmdz.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yangfankeji.com/Article/details/gthccvlscf.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.svipenyu.cn/Article/details/gtvuvkuicz.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxgpajwgs.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.hfpthk.cn/Article/details/gtodynqakv.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.jinyuanbaomall.cn/Article/details/gthxxunntf.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.tanke756.top/Article/details/gttbzcraxx.html

[A26] 类型转换总览
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgbjoalfh.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.jqgufenzy.top/Article/details/gtaftzudci.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.gogol.net.cn/Article/details/gtvyzxdbzw.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.hammf.cn/Article/details/gtwrwfpiuk.html

TS:   Number() String() Boolean() x as number
来源：http://dali.snrcjt.cn/Article/details/gtscdvczhp.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.yonumen.top/Article/details/gtrxvgjlap.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.havefunace.top/Article/details/gttpnqgbuv.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.sufxvd.cn/Article/details/gtdltmzgfc.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.zdqjudy.top/Article/details/gtzfijlght.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtlvcubniv.html

B. 流程控制
来源：http://dali.zhongyouzk.top/Article/details/gtpntxwald.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtdtcqfgha.html

[B01] 条件判断 if / else
来源：http://dali.feifeiyinyue.top/Article/details/gtjwtbdkmh.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.ivvv.top/Article/details/gtulkzgpsh.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.ehwqpu.com/Article/details/gtjztyhotk.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.haohaochexian.top/Article/details/gtsswolmuq.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.birdmap.top/Article/details/gtjhqgqivc.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvjfsvsja.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.hnxiangtu.top/Article/details/gtpojmjbhl.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.jyoumei.cn/Article/details/gttemgpkmj.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyfzedxyn.html

[B02] 多分支 else if / elif
来源：http://dali.gogol.net.cn/Article/details/gtgickjyve.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.snrcjt.cn/Article/details/gtqqdvtxpm.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.c1oappe.top/Article/details/gtughywllz.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.wangdashe.top/Article/details/gttlgsumzi.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.pengpengdd.cyou/Article/details/gtxrxtbdma.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.gogol.net.cn/Article/details/gtedaonlck.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.daria6918.cn/Article/details/gtxldgrgge.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.daxiang520.top/Article/details/gtxzgavxyu.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.havefunace.top/Article/details/gtrlizeiic.html

[B03] switch / match / case
来源：http://dali.haohaochexian.top/Article/details/gteddcdkny.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.tanke756.top/Article/details/gtphfevjvp.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.wangdashe.top/Article/details/gtdyuzxqfb.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zhoulong.xyz/Article/details/gtcwesbeyb.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.ehwqpu.com/Article/details/gtigvnsubu.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.shuidangran.top/Article/details/gtvarpqmvw.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.yj202588.top/Article/details/gtcshcmofb.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.ybcxt.top/Article/details/gtibmniyxj.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.yuanzhike.top/Article/details/gthmxlknxj.html

[B04] for 计数循环
来源：http://dali.yonumen.top/Article/details/gtsaibuzbb.html

Py:   for i in range(10): print(i)
来源：http://dali.yanxiufei.cn/Article/details/gtspnoztue.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.xuetiantiany.cn/Article/details/gtrtmedjfo.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.chenlongwang.top/Article/details/gtgyvnrawl.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.gogol.net.cn/Article/details/gtpnyfxmii.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.yvedp.cn/Article/details/gtnxtlcrzm.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.shzxlz.cn/Article/details/gtkkxslssj.html

Ruby: 10.times { |i| puts i }
来源：http://dali.ppjwa.cn/Article/details/gtwwcdyjsn.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.meibo888.top/Article/details/gtgaatvjsg.html

[B05] 遍历数组 / 列表
来源：http://dali.daxiang520.top/Article/details/gtnbrbgpox.html

Py:   for item in arr: print(item)
来源：http://dali.yj20258888.top/Article/details/gtzfitekep.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.ppjwa.cn/Article/details/gtevamvryz.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.yongpay.top/Article/details/gtdjryarbi.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.cucudq.cn/Article/details/gtzwsqrhrv.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.chenlongwang.top/Article/details/gtsdmcrtno.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.yuxming.cn/Article/details/gtxpwknbmc.html

Ruby: arr.each { |item| puts item }
来源：http://dali.ppjwa.cn/Article/details/gtzvxiqxtg.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.0kj1m.cn/Article/details/gtsokcyqbm.html

[B06] 遍历字典 / 对象
来源：http://dali.0kj1m.cn/Article/details/gtstajaxpc.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.yj20258.top/Article/details/gtmfjkoevq.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtwhwvupyq.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.hnqzz.top/Article/details/gtddeqwkgr.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zdqjudy.top/Article/details/gtiwjksqyo.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.ydzc1.top/Article/details/gtehgaygmk.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.wangshuangyany.cn/Article/details/gtnbaziluy.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.hfpthk.cn/Article/details/gteghxknap.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnmphleqw.html

[B07] while 循环
来源：http://dali.yj202588.top/Article/details/gtgtspmrto.html

Py:   while i < 10: i += 1
来源：http://dali.hfpthk.cn/Article/details/gtadfsbcaz.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.sufxvd.cn/Article/details/gtnsmuambx.html

JS:   while (i < 10) { i++; }
来源：http://dali.daxiang520.top/Article/details/gtsbwhqhzy.html

TS:   while (i < 10) { i++; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtxdiwfhyk.html

Java: while (i < 10) { i++; }
来源：http://dali.birdmap.top/Article/details/gtbinamypd.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.hnqzz.top/Article/details/gtssyeakre.html

Ruby: while i < 10; i += 1; end
来源：http://dali.aizwys.cn/Article/details/gtymdkuepu.html

C#:   while (i < 10) { i++; }
来源：http://dali.gotoacloud.top/Article/details/gtcajoabqi.html

[B08] do-while（至少执行一次）
来源：http://dali.gaohongyu789.top/Article/details/gtoulesjkn.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.vqdsnc.cn/Article/details/gtaprpiozl.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.cheryme.top/Article/details/gtziuxzzun.html

JS:   do { i++; } while (i < 10);
来源：http://dali.zhoulong.xyz/Article/details/gtqeoirkru.html

TS:   do { i++; } while (i < 10);
来源：http://dali.zhengqikj.top/Article/details/gtkowqowsv.html

Java: do { i++; } while (i < 10);
来源：http://dali.bjfxy.top/Article/details/gtikvzfhqq.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.jianghu66.top/Article/details/gtwmtcjdmg.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.jinqigfzy.top/Article/details/gtqgubsppb.html

C#:   do { i++; } while (i < 10);
来源：http://dali.ppjwa.cn/Article/details/gtrjbruqql.html

[B09] break 与 continue
来源：http://dali.nanxuanxn.top/Article/details/gtppsogavd.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.jqgufenzy.top/Article/details/gtwofhladz.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.iojbl.cn/Article/details/gtcmocayfj.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hysaishi.cn/Article/details/gtafpdcxhf.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.aibaodan.cn/Article/details/gtttcwbzwz.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cashguo.top/Article/details/gtwwfwmptt.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.wangshuangyany.cn/Article/details/gtpyepfvpv.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.hnxiangtu.top/Article/details/gtbcgqirhz.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hfpthk.cn/Article/details/gtggklqrsv.html

[B10] 遍历同时拿索引
来源：http://dali.nanxuanxn.top/Article/details/gtcvjqsedz.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.birdmap.top/Article/details/gtoptaasbh.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.yongpay.top/Article/details/gtpncxzmvr.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtugqwtlat.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.ehwqpu.com/Article/details/gtppmcgstv.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yvedp.cn/Article/details/gtyseqtyew.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.hfpthk.cn/Article/details/gtmeheiljs.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.pengpengdd.cyou/Article/details/gtzjzartra.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.dianchejie.cn/Article/details/gtxofphmcy.html

[B11] 生成数字序列 / 区间
来源：http://dali.mhx1999.top/Article/details/gtducdrfel.html

Py:   list(range(0, 10, 2))
来源：http://dali.chenzaomai.com/Article/details/gtbofnfxyg.html

PHP:  range(0, 10, 2);
来源：http://dali.jyoumei.cn/Article/details/gtbrlghsql.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xuanzx.com/Article/details/gtybuaietm.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jqgufenzy.top/Article/details/gterlvttly.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdsprbymx.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhongyouzk.top/Article/details/gtaluhtswh.html

Ruby: (0...10).step(2).to_a
来源：http://dali.gaohongyu789.top/Article/details/gtpbvzdjrf.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.daxiang520.top/Article/details/gtfvaoxvzc.html

[B12] 跳出多层循环
来源：http://dali.hongshengwenyu.top/Article/details/gtujgwlzpo.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhiwuduotai.top/Article/details/gthmwufldp.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.nanxuanxn.top/Article/details/gtprxpxmvw.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqpvdobly.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.c1oappe.top/Article/details/gtwfmbxjjz.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.jiagoushi.top/Article/details/gttcicbofq.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.yuxming.cn/Article/details/gttwwbinsc.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.0kj1m.cn/Article/details/gtkqlisbuy.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.pycfn.com/Article/details/gtbcwhfijz.html

[B13] 判断是否为数字
来源：http://dali.zdqjudy.top/Article/details/gtutnqtqce.html

Py:   isinstance(x, (int, float))
来源：http://dali.chenzaomai.com/Article/details/gtoqxukggx.html

PHP:  is_numeric($x)
来源：http://dali.smart0.xyz/Article/details/gtwzodovso.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.guannengcc.top/Article/details/gtebjydbmd.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthoeeibff.html

Java: x instanceof Number
来源：http://dali.zhengqikj.top/Article/details/gtakymfdso.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.quarkkingdee.top/Article/details/gtqxajwart.html

Ruby: x.is_a?(Numeric)
来源：http://dali.ivvv.top/Article/details/gtxupkpldf.html

C#:   x is int or double or decimal
来源：http://dali.aizwys.cn/Article/details/gthgvrhdmi.html

[B14] 判断值是否在集合内
来源：http://dali.hfpthk.cn/Article/details/gtkacrelsb.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.kuanghao11.cn/Article/details/gtxeweqqkl.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.cheryme.top/Article/details/gtvlcjmmqt.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.tanke756.top/Article/details/gtbmnxiykm.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtevosopdb.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.snrcjt.cn/Article/details/gtohtvjqnk.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.xylfe.cn/Article/details/gtwoqdbldh.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdukpjoos.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.sweek.top/Article/details/gtpwfhwsaf.html

[B15] 布尔运算与取反
来源：http://dali.aibaodan.cn/Article/details/gtwzodqzup.html

Py:   a and b or not c
来源：http://dali.ppjwa.cn/Article/details/gttnspahbt.html

PHP:  $a && $b || !$c
来源：http://dali.yangfankeji.com/Article/details/gtbiiosjkg.html

JS:   a && b || !c
来源：http://dali.ybcxt.top/Article/details/gtnwzxgbug.html

TS:   a && b || !c
来源：http://dali.hysaishi.cn/Article/details/gtmjkmmhtb.html

Java: a && b || !c
来源：http://dali.smart0.xyz/Article/details/gtepnbwiqa.html

Go:   a && b || !c
来源：http://dali.daxiang520.top/Article/details/gtvvuiiygh.html

Ruby: a && b || !c
来源：http://dali.cashguo.top/Article/details/gtbjigljzh.html

C#:   a && b || !c
来源：http://dali.daxiang520.top/Article/details/gtupeqtybf.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.cheryme.top/Article/details/gtvmckqpbp.html

Py:   if not data: return
来源：http://dali.9152youxi.cn/Article/details/gtevsbsrjt.html

PHP:  if (!$data) { return; }
来源：http://dali.dashuyun.cn/Article/details/gtibkzcwhl.html

JS:   if (!data) return;
来源：http://dali.ppjwa.cn/Article/details/gtkxkkwaze.html

TS:   if (!data) return;
来源：http://dali.yvedp.cn/Article/details/gttyagxaeg.html

Java: if (data == null) return;
来源：http://dali.zhiwuduotai.top/Article/details/gtiyodifis.html

Go:   if data == nil { return }
来源：http://dali.redwolf501.top/Article/details/gtzjtwhjfd.html

Ruby: return if data.nil?
来源：http://dali.pengpengdd.cyou/Article/details/gtwljfbknv.html

C#:   if (data == null) return;
来源：http://dali.nwbrower.top/Article/details/gtfytfwzqb.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtagxhyutm.html

C. 函数与作用域
来源：http://dali.andypj.xyz/Article/details/gtbskrkbtw.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtjjjcayph.html

[C01] 定义函数
来源：http://dali.xziqi.cn/Article/details/gtlmrmuvut.html

Py:   def add(a, b): return a + b
来源：http://dali.gzhubu.top/Article/details/gtpuuqmywr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdrdrelvz.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.sxryk.cn/Article/details/gtyypvczjg.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.gzhubu.top/Article/details/gtousafqzd.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.fzhhl.top/Article/details/gtldjxaomb.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.gzhubu.top/Article/details/gtofofveek.html

Ruby: def add(a, b); a + b; end
来源：http://dali.dianchejie.cn/Article/details/gtzmcigvzj.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.andypj.xyz/Article/details/gtfjldqpbf.html

[C02] 默认参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbchdlyfd.html

Py:   def greet(name="World"): return name
来源：http://dali.iojbl.cn/Article/details/gtacxqaodh.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.mhx1999.top/Article/details/gtaxbgumya.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.cqqwz.cn/Article/details/gtiyjbgwyv.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.gzhubu.top/Article/details/gtqgmfthwf.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.tian-w.cn/Article/details/gtisasnvpk.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.daria6918.cn/Article/details/gtbfqadwmi.html

Ruby: def greet(name = "World") = name
来源：http://dali.meibo888.top/Article/details/gteftilhzg.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.0kj1m.cn/Article/details/gtnwzwmsmr.html

[C03] 可变参数
来源：http://dali.jinqigfzy.top/Article/details/gtogitxzae.html

Py:   def total(*args): return sum(args)
来源：http://dali.jqgufenzy.top/Article/details/gtaezlgdtk.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.tianlin.xyz/Article/details/gtvknftubp.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhongyouzk.top/Article/details/gtqnngbukk.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.pycfn.com/Article/details/gtrcjzteza.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.tanke756.top/Article/details/gtwyppeldy.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.dashuyun.cn/Article/details/gttohafcko.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.redwolf501.top/Article/details/gtakcoeplm.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.hongshengwenyu.top/Article/details/gtofnjqwkd.html

[C04] 命名参数 / 关键字参数
来源：http://dali.pycfn.com/Article/details/gtwxutqyjc.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgvogpuza.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.sxryk.cn/Article/details/gtdjkckbyy.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtfwsyaugc.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.redwolf501.top/Article/details/gtlsqqzajf.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.iojbl.cn/Article/details/gtfexgyhix.html


<!-- 参考信息 -->