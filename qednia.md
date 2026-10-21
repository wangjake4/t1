代发 wailian999

C#:   // 单行；/* 多行 */
来源：http://dali.shzxlz.cn/Article/details/gtibwjjaod.html

[A15] 空值判断与默认值
来源：http://dali.yueranfly.top/Article/details/gtchorfvef.html

Py:   value = data or "默认值"
来源：http://dali.quarkkingdee.top/Article/details/gtzgfuboep.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.yangfankeji.com/Article/details/gtrmoinxbx.html

JS:   const value = data ?? "默认值";
来源：http://dali.cqqwz.cn/Article/details/gtyynibjxv.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhoulong.xyz/Article/details/gtzxhbtaka.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.gotoacloud.top/Article/details/gtyuztsckw.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.ppjwa.cn/Article/details/gthpwafnfu.html

Ruby: value = data || "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gtlaunbfiu.html

C#:   var value = data ?? "默认值";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoogyjkdq.html

[A16] 真假值判断规则
来源：http://dali.ivvv.top/Article/details/gtfcplhdzh.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.chenzaomai.com/Article/details/gtdzhscktq.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.havefunace.top/Article/details/gtkjrxroja.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.hongshengwenyu.top/Article/details/gtzvrurqkg.html

TS:   if (!x) {}
来源：http://dali.sysykeji.top/Article/details/gtmvlhkohy.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.yj20258888.top/Article/details/gtfxiwcdyb.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.xuetiantiany.cn/Article/details/gtwcfwecdk.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.snrcjt.cn/Article/details/gtcszdmoqh.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.c1oappe.top/Article/details/gtvgtuucye.html

[A17] 位运算
来源：http://dali.nwbrower.top/Article/details/gtdxzoclow.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.mhx1999.top/Article/details/gtzuukzaaw.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.jqgfzy.top/Article/details/gtyzbarmbj.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.cashguo.top/Article/details/gthmumytrq.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.dianchejie.cn/Article/details/gtleuayozr.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.c1oappe.top/Article/details/gtdfvkfkbr.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.cdnleiting.top/Article/details/gtwjmkzagw.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yueranfly.top/Article/details/gtpphpghob.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hysaishi.cn/Article/details/gttiotvacw.html

[A18] 字符与 ASCII 码互转
来源：http://dali.ehwqpu.com/Article/details/gtlxoeeujf.html

Py:   ord("A"); chr(65)
来源：http://dali.yuanzhike.top/Article/details/gtqtwdfpnh.html

PHP:  ord("A"); chr(65)
来源：http://dali.yonumen.top/Article/details/gtwrtgmxmr.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.yj202588.top/Article/details/gtvjxauoxh.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.jianghu66.top/Article/details/gtpfjzyljc.html

Java: (int) 'A'; (char) 65
来源：http://dali.9152youxi.cn/Article/details/gthheifyqc.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.zhijiandao.cn/Article/details/gtxrfvjzve.html

Ruby: "A".ord; 65.chr
来源：http://dali.cashguo.top/Article/details/gtvlmodhlv.html

C#:   (int)'A'; (char)65
来源：http://dali.cashguo.top/Article/details/gtthadozjx.html

[A19] 交换两个变量
来源：http://dali.aizwys.cn/Article/details/gtnyaxcejw.html

Py:   a, b = b, a
来源：http://dali.jqgufenzy.top/Article/details/gtcedcthqk.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.jinqigfzy.top/Article/details/gtlchvqtql.html

JS:   [a, b] = [b, a];
来源：http://dali.cashguo.top/Article/details/gtvskcwgqa.html

TS:   [a, b] = [b, a];
来源：http://dali.zhixingplan.top/Article/details/gtsrlbcvne.html

Java: int t = a; a = b; b = t;
来源：http://dali.yangfankeji.com/Article/details/gteqspmljq.html

Go:   a, b = b, a
来源：http://dali.wangdashe.top/Article/details/gtfudcppuv.html

Ruby: a, b = b, a
来源：http://dali.zhoulong.xyz/Article/details/gtgsozoond.html

C#:   (a, b) = (b, a);
来源：http://dali.yuanzhike.top/Article/details/gtdmtwejtn.html

[A20] 读取标准输入
来源：http://dali.birdmap.top/Article/details/gtnfzfldea.html

Py:   name = input("请输入：")
来源：http://dali.iojbl.cn/Article/details/gtvmjksslg.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.jiagoushi.top/Article/details/gtrtsgrzuo.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.fengsongda.top/Article/details/gtxfukflea.html

TS:   // Node.js：readline 模块
来源：http://dali.yj202588.top/Article/details/gtfjrxapek.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.jinghuilouyu.cn/Article/details/gtrpwhvwrl.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.jyoumei.cn/Article/details/gtxydylhio.html

Ruby: gets.chomp
来源：http://dali.zhoulong.xyz/Article/details/gtsfdyibiy.html

C#:   Console.ReadLine();
来源：http://dali.xuanzx.com/Article/details/gtxscrkshm.html

[A21] 保留指定小数位输出
来源：http://dali.dashuyun.cn/Article/details/gtlozikala.html

Py:   f"{3.14159:.2f}"
来源：http://dali.nwbrower.top/Article/details/gtiabzqvva.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.gzhubu.top/Article/details/gtfbnbzpqv.html

JS:   (3.14159).toFixed(2)
来源：http://dali.yj20258.top/Article/details/gtfyfdmkcc.html

TS:   (3.14159).toFixed(2)
来源：http://dali.jqgfzy.top/Article/details/gtbnpjoznh.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.shuidangran.top/Article/details/gtlbtzlclu.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.ivvv.top/Article/details/gtqwsrkzsn.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.haohaochexian.top/Article/details/gtcdsbvxba.html

C#:   3.14159.ToString("F2")
来源：http://dali.zhixingplan.top/Article/details/gtbqogoueg.html

[A22] 获取字符串长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcokndeje.html

Py:   len(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtomijnpms.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.birdmap.top/Article/details/gtrbsmhtys.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.hammf.cn/Article/details/gthsntbzlg.html

TS:   s.length
来源：http://dali.quarkkingdee.top/Article/details/gtjrkoywsa.html

Java: s.length()
来源：http://dali.jinqigfzy.top/Article/details/gtzksibexx.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnpqfyilp.html

Ruby: s.length
来源：http://dali.c1oappe.top/Article/details/gtvdvsnemw.html

C#:   s.Length
来源：http://dali.sufxvd.cn/Article/details/gtjplrnrum.html

[A23] 大小写转换
来源：http://dali.daxiang520.top/Article/details/gtmihljfxv.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.cdnleiting.top/Article/details/gtjfnqkiyv.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.shuidangran.top/Article/details/gtujttbhxa.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.sxryk.cn/Article/details/gtwylyxosn.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.chenzaomai.com/Article/details/gtzzrmqdxc.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.sweek.top/Article/details/gtmbzeeamm.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.xylfe.cn/Article/details/gtlnlpmxzt.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.ppjwa.cn/Article/details/gtvcfyqcuo.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.nanxuanxn.top/Article/details/gtkzerpgqz.html

[A24] 去除首尾空白
来源：http://dali.xziqi.cn/Article/details/gthtifgnbq.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.hammf.cn/Article/details/gtwuanhnbp.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.zhiwuduotai.top/Article/details/gtouvfnjza.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.sysykeji.top/Article/details/gtogsdiebk.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.sweek.top/Article/details/gtlwkmvuum.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.cdnleiting.top/Article/details/gtfcdemuhx.html

Go:   strings.TrimSpace(s)
来源：http://dali.nwbrower.top/Article/details/gtpzscajny.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.zhiwuduotai.top/Article/details/gtbpvgskfb.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.jqgfzy.top/Article/details/gtbqvgycjz.html

[A25] 字符串比较
来源：http://dali.nwbrower.top/Article/details/gtbbgubgwl.html

Py:   s1 == s2; s1 != s2
来源：http://dali.yangfankeji.com/Article/details/gtfpfkusre.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqyhqlqiw.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yuxming.cn/Article/details/gtpmesdxsk.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.redwolf501.top/Article/details/gtvdblqgou.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.haohaochexian.top/Article/details/gtpknnbord.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.nanxinkj.top/Article/details/gtzqpmkqgo.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.0kj1m.cn/Article/details/gtoklpomgh.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.yueranfly.top/Article/details/gtsibnbfeh.html

[A26] 类型转换总览
来源：http://dali.jinghuilouyu.cn/Article/details/gtiulgaegi.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.zycfv.cn/Article/details/gtmpxfaowb.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.cheryme.top/Article/details/gtglzsurfo.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.gotoacloud.top/Article/details/gtfvhxrmrb.html

TS:   Number() String() Boolean() x as number
来源：http://dali.nanxuanxn.top/Article/details/gtotvbdfsj.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.chenjidiqi.icu/Article/details/gtymmfzuiu.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.daria6918.cn/Article/details/gtqkoyricx.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.bjfxy.top/Article/details/gtufybhucm.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.yuanzhike.top/Article/details/gtuumzsxuw.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtfxjqrwdq.html

B. 流程控制
来源：http://dali.iojbl.cn/Article/details/gtwwspgxre.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtfhkahfxz.html

[B01] 条件判断 if / else
来源：http://dali.tanke756.top/Article/details/gtnijbvomo.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.jiagoushi.top/Article/details/gtuwzjldes.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.ybcxt.top/Article/details/gtpqoiuczx.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.hnxiangtu.top/Article/details/gtzrnvaqml.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jianghu66.top/Article/details/gtoribyxzg.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.jyoumei.cn/Article/details/gtcngdtifv.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.redwolf501.top/Article/details/gttrniamrf.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.tanke756.top/Article/details/gtbrhattze.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.dashuyun.cn/Article/details/gtvoqqwjgl.html

[B02] 多分支 else if / elif
来源：http://dali.yangfankeji.com/Article/details/gtanptvrqx.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.yvedp.cn/Article/details/gtajtzyrqy.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.yonumen.top/Article/details/gtshfwiwhw.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yangfankeji.com/Article/details/gttyooieez.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhijiandao.cn/Article/details/gtecgqkxif.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hnxiangtu.top/Article/details/gtcfhxxsch.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.jlsjyb.cn/Article/details/gtqpefqvck.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.jinghuilouyu.cn/Article/details/gtlxlyptda.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.gaohongyu789.top/Article/details/gtyzpmswmc.html

[B03] switch / match / case
来源：http://dali.zycfv.cn/Article/details/gtpoeslxwv.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.wangdashe.top/Article/details/gtzsgagjev.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.zhixingplan.top/Article/details/gtjowgxupk.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yonumen.top/Article/details/gtltwyfjfr.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zhongyouzk.top/Article/details/gtefwqxmyz.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.guowangkeji.top/Article/details/gtbtqkxnvp.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.fzhhl.top/Article/details/gteokvldow.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.hnqzz.top/Article/details/gtzhuslsuk.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.9152youxi.cn/Article/details/gtvnctcjtc.html

[B04] for 计数循环
来源：http://dali.cqqwz.cn/Article/details/gthjeoljsh.html

Py:   for i in range(10): print(i)
来源：http://dali.mhx1999.top/Article/details/gtnipgcetd.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.hnxiangtu.top/Article/details/gthojtsexq.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhoulong.xyz/Article/details/gtkewinatc.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.bjfxy.top/Article/details/gtwjjpampz.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.xylfe.cn/Article/details/gtqzkqaneo.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.yueranfly.top/Article/details/gtkazrvkgw.html

Ruby: 10.times { |i| puts i }
来源：http://dali.redwolf501.top/Article/details/gtotkghtlq.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbwyepztk.html

[B05] 遍历数组 / 列表
来源：http://dali.cucudq.cn/Article/details/gtkyglzrzb.html

Py:   for item in arr: print(item)
来源：http://dali.cucudq.cn/Article/details/gtujgmoava.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.tanke756.top/Article/details/gthsenvhjt.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.dashuyun.cn/Article/details/gtzwpitpik.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.snrcjt.cn/Article/details/gtlbcqyice.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.zhongyouzk.top/Article/details/gtjwuxohru.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.cdnleiting.top/Article/details/gtvqyeuvzv.html

Ruby: arr.each { |item| puts item }
来源：http://dali.havefunace.top/Article/details/gtrdmkcfoj.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.svipenyu.cn/Article/details/gtrngcqbnf.html

[B06] 遍历字典 / 对象
来源：http://dali.zycfv.cn/Article/details/gtllasaiwv.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.cqqwz.cn/Article/details/gtaowqvhvw.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.cashguo.top/Article/details/gtxdqxklfy.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtbshadjhn.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.pengpengdd.cyou/Article/details/gtcipgdevr.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.sufxvd.cn/Article/details/gtwdkxpcdg.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.daxiang520.top/Article/details/gtyyenmfjh.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.bjfxy.top/Article/details/gtehxtvswq.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.jqgfzy.top/Article/details/gtwhlvxplb.html

[B07] while 循环
来源：http://dali.feifeiyinyue.top/Article/details/gtgeslfdac.html

Py:   while i < 10: i += 1
来源：http://dali.wangshuangyany.cn/Article/details/gtegwrdekk.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.quarkkingdee.top/Article/details/gtgqncqgyc.html

JS:   while (i < 10) { i++; }
来源：http://dali.daria6918.cn/Article/details/gtxxovuwtc.html

TS:   while (i < 10) { i++; }
来源：http://dali.jianghu66.top/Article/details/gtfhmmemnn.html

Java: while (i < 10) { i++; }
来源：http://dali.shuidangran.top/Article/details/gtsxltdske.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.shanyushiyangtech.top/Article/details/gtzgmwwjum.html

Ruby: while i < 10; i += 1; end
来源：http://dali.chenzaomai.com/Article/details/gtnklelxrq.html

C#:   while (i < 10) { i++; }
来源：http://dali.birdmap.top/Article/details/gtdgvfznpn.html

[B08] do-while（至少执行一次）
来源：http://dali.guannengcc.top/Article/details/gtmfbazswo.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.xinyue.icu/Article/details/gtnmhsecxp.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.xuanzx.com/Article/details/gtpqvtrsxe.html

JS:   do { i++; } while (i < 10);
来源：http://dali.daxiang520.top/Article/details/gtvmfxuyzf.html

TS:   do { i++; } while (i < 10);
来源：http://dali.ybcxt.top/Article/details/gteiklbpwk.html

Java: do { i++; } while (i < 10);
来源：http://dali.cheryme.top/Article/details/gtsbwcnlau.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.cheryme.top/Article/details/gtjlftglbb.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.zhongyouzk.top/Article/details/gtzbtdhncg.html

C#:   do { i++; } while (i < 10);
来源：http://dali.chenzaomai.com/Article/details/gtnkklalkt.html

[B09] break 与 continue
来源：http://dali.cheryme.top/Article/details/gtfckgqsra.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.nanxuanxn.top/Article/details/gthmbtwtpu.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.shuidangran.top/Article/details/gtuzohissy.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ehwqpu.com/Article/details/gtuzhqlvtn.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenzaomai.com/Article/details/gthiylaujv.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.birdmap.top/Article/details/gtqbeatmoo.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuxsbztyk.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.shangyingyoupin.top/Article/details/gtwjpdqowe.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yonumen.top/Article/details/gttreqxsxd.html

[B10] 遍历同时拿索引
来源：http://dali.vqdsnc.cn/Article/details/gtwhinblza.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.yueranfly.top/Article/details/gttkcoysah.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.yuanzhike.top/Article/details/gtncgmobcx.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.bjfxy.top/Article/details/gtbzfzcuer.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.0kj1m.cn/Article/details/gtpwtnfucx.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.xziqi.cn/Article/details/gtvfjbcpzb.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.daxiang520.top/Article/details/gtutxoqjxq.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.xylfe.cn/Article/details/gtmlvfpupj.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.jlsjyb.cn/Article/details/gtnllflwfd.html

[B11] 生成数字序列 / 区间
来源：http://dali.yonumen.top/Article/details/gteuwsnqbz.html

Py:   list(range(0, 10, 2))
来源：http://dali.yj202588.top/Article/details/gtsbqtgaiq.html

PHP:  range(0, 10, 2);
来源：http://dali.aizwys.cn/Article/details/gtkscyhext.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jinqigufen.top/Article/details/gttkgsgbui.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.aibaodan.cn/Article/details/gtxalhqeas.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.tanke756.top/Article/details/gtoqdsbwgg.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.ehwqpu.com/Article/details/gttsrkrfbl.html

Ruby: (0...10).step(2).to_a
来源：http://dali.guowangkeji.top/Article/details/gtoowrynpr.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yueranfly.top/Article/details/gtmrascjgq.html

[B12] 跳出多层循环
来源：http://dali.jianghu66.top/Article/details/gtkieztsvf.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.sysykeji.top/Article/details/gtapncyyaj.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.cdnleiting.top/Article/details/gtrhcxgxga.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jqgufenzy.top/Article/details/gtimweckcs.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hongshengwenyu.top/Article/details/gtykmtviqf.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.sxryk.cn/Article/details/gtneubtgoy.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.gotoacloud.top/Article/details/gtfpvettme.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.kuanghao11.cn/Article/details/gttqunmzsv.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jiagoushi.top/Article/details/gtwwmleqgy.html

[B13] 判断是否为数字
来源：http://dali.fengsongda.top/Article/details/gtvnclhkne.html

Py:   isinstance(x, (int, float))
来源：http://dali.hongshengwenyu.top/Article/details/gtqrncdstk.html

PHP:  is_numeric($x)
来源：http://dali.zhoulong.xyz/Article/details/gtenfouohw.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ydzc1.top/Article/details/gtjrindbzu.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.vqdsnc.cn/Article/details/gtumptidjq.html

Java: x instanceof Number
来源：http://dali.zhaomingkeji.xyz/Article/details/gtakzhhtil.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.ppjwa.cn/Article/details/gtkpypsmke.html

Ruby: x.is_a?(Numeric)
来源：http://dali.hysaishi.cn/Article/details/gtwjwcomcu.html

C#:   x is int or double or decimal
来源：http://dali.jinghuilouyu.cn/Article/details/gtyfcvgbxz.html

[B14] 判断值是否在集合内
来源：http://dali.cqqwz.cn/Article/details/gtjpwltqmc.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.xuanzx.com/Article/details/gtndavuxtf.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.gotoacloud.top/Article/details/gtjvfrbwmi.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.316326.xyz/Article/details/gtnjjpdxwx.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.redwolf501.top/Article/details/gtgqrqdyyk.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.tian-w.cn/Article/details/gtvotrherd.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttcarwdxh.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.cucudq.cn/Article/details/gtqjkuuaxt.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.cashguo.top/Article/details/gttynvtdwz.html

[B15] 布尔运算与取反
来源：http://dali.ydzc1.top/Article/details/gtbjkthvcg.html

Py:   a and b or not c
来源：http://dali.yj202588.top/Article/details/gtiqdieyts.html

PHP:  $a && $b || !$c
来源：http://dali.iojbl.cn/Article/details/gtbjhrngjj.html

JS:   a && b || !c
来源：http://dali.jqgfzy.top/Article/details/gtexadhvzt.html

TS:   a && b || !c
来源：http://dali.nanxuanxn.top/Article/details/gtptgmdbzd.html

Java: a && b || !c
来源：http://dali.jinghuilouyu.cn/Article/details/gtcavamtzw.html

Go:   a && b || !c
来源：http://dali.cucudq.cn/Article/details/gtsonjxlqy.html

Ruby: a && b || !c
来源：http://dali.vqdsnc.cn/Article/details/gtytascxch.html

C#:   a && b || !c
来源：http://dali.shzxlz.cn/Article/details/gteeveowqm.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.gaohongyu789.top/Article/details/gtkhdzjhpa.html

Py:   if not data: return
来源：http://dali.0kj1m.cn/Article/details/gtrkgigiuj.html

PHP:  if (!$data) { return; }
来源：http://dali.hammf.cn/Article/details/gtcdqtblgn.html

JS:   if (!data) return;
来源：http://dali.xinyue.icu/Article/details/gtpbhyyvkh.html

TS:   if (!data) return;
来源：http://dali.smart0.xyz/Article/details/gtyicqkvwr.html

Java: if (data == null) return;
来源：http://dali.jyoumei.cn/Article/details/gtqjwhnksr.html

Go:   if data == nil { return }
来源：http://dali.wangshuangyany.cn/Article/details/gtmbxijsei.html

Ruby: return if data.nil?
来源：http://dali.zhongyouzk.top/Article/details/gtoamgmgmx.html

C#:   if (data == null) return;
来源：http://dali.pycfn.com/Article/details/gtuzwbrlpv.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtfsfnouam.html

C. 函数与作用域
来源：http://dali.yueranfly.top/Article/details/gtqzrgxrdw.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtzmrykpgz.html

[C01] 定义函数
来源：http://dali.smart0.xyz/Article/details/gtnjekqflk.html

Py:   def add(a, b): return a + b
来源：http://dali.daria6918.cn/Article/details/gtxidovzzr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtowptflai.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.daria6918.cn/Article/details/gtdahvhwhz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jqgufenzy.top/Article/details/gtvuztmsll.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jinqigufen.top/Article/details/gtzytmsrtl.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.bjfxy.top/Article/details/gtezvzhxhs.html

Ruby: def add(a, b); a + b; end
来源：http://dali.xziqi.cn/Article/details/gtmkhesrmq.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbpbmdbtu.html

[C02] 默认参数
来源：http://dali.hfpthk.cn/Article/details/gtecyfqviu.html

Py:   def greet(name="World"): return name
来源：http://dali.feifeiyinyue.top/Article/details/gtojejrbjg.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.wangdashe.top/Article/details/gtcrpmaeff.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.ppjwa.cn/Article/details/gtnpvpayys.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtygihnafy.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.gotoacloud.top/Article/details/gtkgxgxcrc.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.gotoacloud.top/Article/details/gthnzheeoa.html

Ruby: def greet(name = "World") = name
来源：http://dali.fzhhl.top/Article/details/gtpppcpmfb.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.ydzc1.top/Article/details/gtkclfawqk.html

[C03] 可变参数
来源：http://dali.jqgufenzy.top/Article/details/gthylbqezk.html

Py:   def total(*args): return sum(args)
来源：http://dali.mhx1999.top/Article/details/gtfioifarr.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.gotoacloud.top/Article/details/gtxhconaqt.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zycfv.cn/Article/details/gtmoubsgad.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yuanzhike.top/Article/details/gtftblkstq.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gtgmrcvgzu.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.dianchejie.cn/Article/details/gtgvkhkpdb.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zycfv.cn/Article/details/gtizbtwdma.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jlsjyb.cn/Article/details/gtqaygkydu.html

[C04] 命名参数 / 关键字参数
来源：http://dali.shuidangran.top/Article/details/gtlcxpfvnh.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yonumen.top/Article/details/gtafymkksr.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jinqigfzy.top/Article/details/gtlqndbkhd.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jqgufenzy.top/Article/details/gtoamagmev.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.hongshengwenyu.top/Article/details/gtqovjhpvn.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.quarkkingdee.top/Article/details/gtzhmtrcsf.html

Go:   // 无：用配置结构体参数
来源：http://dali.jiagoushi.top/Article/details/gtmtlgrbyw.html

Ruby: f(a: 1, b: 2)
来源：http://dali.hfpthk.cn/Article/details/gtjznsqpcc.html

C#:   f(a: 1, b: 2)
来源：http://dali.cashguo.top/Article/details/gtqhzckjrk.html

[C05] 返回多个值
来源：http://dali.xziqi.cn/Article/details/gtisohgrku.html

Py:   return a, b
来源：http://dali.yj20258.top/Article/details/gtplmrvgwk.html

PHP:  return [$a, $b];
来源：http://dali.shuidangran.top/Article/details/gtaeqhwcff.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.smart0.xyz/Article/details/gtzlyqeokb.html

TS:   return { a, b };
来源：http://dali.jqgfzy.top/Article/details/gtziibdsxw.html


<!-- 参考信息 -->