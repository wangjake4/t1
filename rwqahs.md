代发 wailian999

Java: "第一行\n第二行"
来源：http://dali.hammf.cn/Article/details/gtajbiurhj.html

Go:   "第一行\n第二行"
来源：http://dali.yangfankeji.com/Article/details/gtulmvqyti.html

Ruby: "第一行\n第二行"
来源：http://dali.ivvv.top/Article/details/gtnzeyumri.html

C#:   "第一行\n第二行"
来源：http://dali.zycfv.cn/Article/details/gtjdgfvjpp.html

[A14] 注释写法
来源：http://dali.jinqigufen.top/Article/details/gtdldmfgwu.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.gotoacloud.top/Article/details/gtdhlcjnra.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.hysaishi.cn/Article/details/gtcjlcabkv.html

JS:   // 单行；/* 多行 */
来源：http://dali.yuanzhike.top/Article/details/gtgdkvbhbk.html

TS:   // 单行；/* 多行 */
来源：http://dali.yuxming.cn/Article/details/gtpxfisnni.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpeynzeqa.html

Go:   // 单行；/* 多行 */
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsmxhinay.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zdqjudy.top/Article/details/gtnlnxbzbq.html

C#:   // 单行；/* 多行 */
来源：http://dali.birdmap.top/Article/details/gtabwxnzdw.html

[A15] 空值判断与默认值
来源：http://dali.havefunace.top/Article/details/gtomlldagd.html

Py:   value = data or "默认值"
来源：http://dali.jlsjyb.cn/Article/details/gthgbhgjrc.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.jqgfzy.top/Article/details/gteznjyyik.html

JS:   const value = data ?? "默认值";
来源：http://dali.feifeiyinyue.top/Article/details/gtqvpmdpli.html

TS:   const value = data ?? "默认值";
来源：http://dali.dianchejie.cn/Article/details/gtwqovhukq.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.guowangkeji.top/Article/details/gtnwhkktfs.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.hnxiangtu.top/Article/details/gtjvhclcfx.html

Ruby: value = data || "默认值"
来源：http://dali.shanyushiyangtech.top/Article/details/gteenjjjfv.html

C#:   var value = data ?? "默认值";
来源：http://dali.cqqwz.cn/Article/details/gtcpniiglj.html

[A16] 真假值判断规则
来源：http://dali.xinyue.icu/Article/details/gtbfkobzaq.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.haohaochexian.top/Article/details/gteenidoyq.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.feifeiyinyue.top/Article/details/gtwhmfbifk.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.hysaishi.cn/Article/details/gtkwewkail.html

TS:   if (!x) {}
来源：http://dali.fzhhl.top/Article/details/gtlakliisw.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtyjzwgyll.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.jinghuilouyu.cn/Article/details/gtoswdpwbv.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.tian-w.cn/Article/details/gtnbnxuxve.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.aizwys.cn/Article/details/gtwdxujuoc.html

[A17] 位运算
来源：http://dali.wangdashe.top/Article/details/gtxumwoxcd.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hnxiangtu.top/Article/details/gtbjpxukwb.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.chenjidiqi.icu/Article/details/gthscjnhll.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.bjfxy.top/Article/details/gtaltkxgtf.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.316326.xyz/Article/details/gtuzwqutzc.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.chenzaomai.com/Article/details/gtsurdeldh.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.xziqi.cn/Article/details/gtgpesnzeh.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.havefunace.top/Article/details/gtgbvkdjsq.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yvedp.cn/Article/details/gthddywbhu.html

[A18] 字符与 ASCII 码互转
来源：http://dali.0kj1m.cn/Article/details/gtjsiyeulp.html

Py:   ord("A"); chr(65)
来源：http://dali.shzxlz.cn/Article/details/gtwelojzwj.html

PHP:  ord("A"); chr(65)
来源：http://dali.jinqigfzy.top/Article/details/gtvbesaagp.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.hnqzz.top/Article/details/gtbccltndf.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.dashuyun.cn/Article/details/gtibgblpfu.html

Java: (int) 'A'; (char) 65
来源：http://dali.sysykeji.top/Article/details/gthbeuisno.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.jqgfzy.top/Article/details/gtyilulwfp.html

Ruby: "A".ord; 65.chr
来源：http://dali.gotoacloud.top/Article/details/gtuoxdnacz.html

C#:   (int)'A'; (char)65
来源：http://dali.dashuyun.cn/Article/details/gtazzcquco.html

[A19] 交换两个变量
来源：http://dali.xylfe.cn/Article/details/gtbykwvumr.html

Py:   a, b = b, a
来源：http://dali.xziqi.cn/Article/details/gtkmoqjxvf.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.cdnleiting.top/Article/details/gtpxrltlqi.html

JS:   [a, b] = [b, a];
来源：http://dali.daxiang520.top/Article/details/gtwaffsvct.html

TS:   [a, b] = [b, a];
来源：http://dali.ppjwa.cn/Article/details/gtieqmzhnk.html

Java: int t = a; a = b; b = t;
来源：http://dali.yongpay.top/Article/details/gtfiknrwzd.html

Go:   a, b = b, a
来源：http://dali.jyoumei.cn/Article/details/gtmvyzvyvu.html

Ruby: a, b = b, a
来源：http://dali.jinqigfzy.top/Article/details/gtbygeasqr.html

C#:   (a, b) = (b, a);
来源：http://dali.daria6918.cn/Article/details/gtohteigqb.html

[A20] 读取标准输入
来源：http://dali.yanxiufei.cn/Article/details/gtafbxnqtd.html

Py:   name = input("请输入：")
来源：http://dali.zycfv.cn/Article/details/gtepufidzq.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.hammf.cn/Article/details/gtstgnfcjv.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.andypj.xyz/Article/details/gtdtbhdlvf.html

TS:   // Node.js：readline 模块
来源：http://dali.hongshengwenyu.top/Article/details/gthjidujjm.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.dianchejie.cn/Article/details/gtuwbvjooe.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.zhoulong.xyz/Article/details/gtgngjgdwh.html

Ruby: gets.chomp
来源：http://dali.daxiang520.top/Article/details/gtwsidxjck.html

C#:   Console.ReadLine();
来源：http://dali.dianchejie.cn/Article/details/gtsjnkdtok.html

[A21] 保留指定小数位输出
来源：http://dali.zhongyouzk.top/Article/details/gtnqkcxtbt.html

Py:   f"{3.14159:.2f}"
来源：http://dali.snrcjt.cn/Article/details/gtprdcepkc.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.chenjidiqi.icu/Article/details/gtdlhdvtet.html

JS:   (3.14159).toFixed(2)
来源：http://dali.ybcxt.top/Article/details/gtgmvvugub.html

TS:   (3.14159).toFixed(2)
来源：http://dali.nwbrower.top/Article/details/gtukryeujn.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.jinqigfzy.top/Article/details/gtwmxckuyc.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.chenjidiqi.icu/Article/details/gtgmozafsj.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.sweek.top/Article/details/gtfxvkvytr.html

C#:   3.14159.ToString("F2")
来源：http://dali.yuxming.cn/Article/details/gtvxtajfjt.html

[A22] 获取字符串长度
来源：http://dali.xuetiantiany.cn/Article/details/gticylodum.html

Py:   len(s)
来源：http://dali.hnxiangtu.top/Article/details/gtegtyfkvc.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.jqgfzy.top/Article/details/gtukzcprtz.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.yj20258888.top/Article/details/gtatelkjpc.html

TS:   s.length
来源：http://dali.jinqigfzy.top/Article/details/gtbohsxquk.html

Java: s.length()
来源：http://dali.ydzc1.top/Article/details/gtdyaeyfyp.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.cheryme.top/Article/details/gtlcdaajie.html

Ruby: s.length
来源：http://dali.yangfankeji.com/Article/details/gtxawdhgbb.html

C#:   s.Length
来源：http://dali.quarkkingdee.top/Article/details/gtxmljrznz.html

[A23] 大小写转换
来源：http://dali.dianchejie.cn/Article/details/gtcfqqvbvj.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.pycfn.com/Article/details/gtcysscuhu.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.sysykeji.top/Article/details/gtqjmaphyd.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.feifeiyinyue.top/Article/details/gthztxiffq.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.haohaochexian.top/Article/details/gtqnkoapvn.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.xuetiantiany.cn/Article/details/gtqomfqbhc.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.9152youxi.cn/Article/details/gtegtbfhbf.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.svipenyu.cn/Article/details/gtpilnxazz.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.daria6918.cn/Article/details/gtvvlvkpyz.html

[A24] 去除首尾空白
来源：http://dali.jinqigufen.top/Article/details/gtpymtmyoo.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.tian-w.cn/Article/details/gtjpogzcat.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.shuidangran.top/Article/details/gtcmhkzcwk.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.shuidangran.top/Article/details/gtmhotncoq.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.cdnleiting.top/Article/details/gtqgmthvtt.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.jlsjyb.cn/Article/details/gtuyonfdzc.html

Go:   strings.TrimSpace(s)
来源：http://dali.zhixingplan.top/Article/details/gtrggdkteg.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.aizwys.cn/Article/details/gtrsryqfqi.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.chenjidiqi.icu/Article/details/gtzhfijyya.html

[A25] 字符串比较
来源：http://dali.hnqzz.top/Article/details/gtmzlfdckp.html

Py:   s1 == s2; s1 != s2
来源：http://dali.sxryk.cn/Article/details/gtivzhgeob.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpkrqycyw.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.ybcxt.top/Article/details/gtswbprwje.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyqqgpzex.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.xziqi.cn/Article/details/gtclqtigod.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.smart0.xyz/Article/details/gtlnlhxdqa.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.shangyingyoupin.top/Article/details/gtgkelyaqm.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.zhijiandao.cn/Article/details/gtbddzzjck.html

[A26] 类型转换总览
来源：http://dali.dianchejie.cn/Article/details/gtxmpvgbhn.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.wangdashe.top/Article/details/gtyxvnsqvx.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.andypj.xyz/Article/details/gtzvmtdwzo.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.zhixingplan.top/Article/details/gtdlotgdqx.html

TS:   Number() String() Boolean() x as number
来源：http://dali.zhoulong.xyz/Article/details/gtngfpxljk.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.pengpengdd.cyou/Article/details/gtetyjbzip.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.hnqzz.top/Article/details/gtnekdvzer.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.nanxuanxn.top/Article/details/gtdfcwifeg.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.0kj1m.cn/Article/details/gttbiqswgo.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtohfxqeuq.html

B. 流程控制
来源：http://dali.cheryme.top/Article/details/gtfaekvand.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtrenxuuax.html

[B01] 条件判断 if / else
来源：http://dali.jqgfzy.top/Article/details/gtrzarfsfd.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.zhengqikj.top/Article/details/gtaxyrgvcu.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.cheryme.top/Article/details/gtydxqhyhh.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zhiwuduotai.top/Article/details/gtjtgomvmp.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.svipenyu.cn/Article/details/gtiblkfczi.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.jinqigufen.top/Article/details/gtwjykosoi.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.zhiwuduotai.top/Article/details/gttozalaae.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.jqgfzy.top/Article/details/gtvrvyvwyq.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.cqqwz.cn/Article/details/gtaasofwld.html

[B02] 多分支 else if / elif
来源：http://dali.shzxlz.cn/Article/details/gtdtbjxpvw.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.xuanzx.com/Article/details/gtddwceyth.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.tianlin.xyz/Article/details/gtybwdqcun.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yueranfly.top/Article/details/gtddnuzaoe.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhijiandao.cn/Article/details/gtrohecdia.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.mhx1999.top/Article/details/gtyfnzzbgm.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.c1oappe.top/Article/details/gtttzfzvgk.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.fzhhl.top/Article/details/gtztkszrfi.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zycfv.cn/Article/details/gtwgcszvda.html

[B03] switch / match / case
来源：http://dali.ydzc1.top/Article/details/gtqoxeaihd.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.9152youxi.cn/Article/details/gtreoptail.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.meibo888.top/Article/details/gtzgmjvdfv.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.tian-w.cn/Article/details/gtymnwrsai.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jqgufenzy.top/Article/details/gtqeamljrc.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.hnxiangtu.top/Article/details/gtbdqobljq.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.zhongyouzk.top/Article/details/gtlcvdwpfp.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.jinghuilouyu.cn/Article/details/gtyaacfolv.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.mhx1999.top/Article/details/gtxtdfcvme.html

[B04] for 计数循环
来源：http://dali.dashuyun.cn/Article/details/gtujtidcmc.html

Py:   for i in range(10): print(i)
来源：http://dali.hongshengwenyu.top/Article/details/gthtqiflye.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaidjszra.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqarbtxye.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.dianchejie.cn/Article/details/gtcknyrdnv.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvitcvezi.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.hywenlv.cn/Article/details/gtdwhpsbgm.html

Ruby: 10.times { |i| puts i }
来源：http://dali.smart0.xyz/Article/details/gtkzzsalpq.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.jlsjyb.cn/Article/details/gttrcoofss.html

[B05] 遍历数组 / 列表
来源：http://dali.zdqjudy.top/Article/details/gttkmprdgh.html

Py:   for item in arr: print(item)
来源：http://dali.yj202588.top/Article/details/gtytgfvfwb.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.jianghu66.top/Article/details/gtcguznvvq.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.0kj1m.cn/Article/details/gtrorfqeih.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.xuanzx.com/Article/details/gtjngpohin.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.feifeiyinyue.top/Article/details/gtdrqzupdw.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.fzhhl.top/Article/details/gtduhdchbx.html

Ruby: arr.each { |item| puts item }
来源：http://dali.snrcjt.cn/Article/details/gteqbmkfft.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.jyoumei.cn/Article/details/gtupoczjur.html

[B06] 遍历字典 / 对象
来源：http://dali.ivvv.top/Article/details/gtgzqkapzb.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.iojbl.cn/Article/details/gtxfzmtkgc.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.shzxlz.cn/Article/details/gtwvoavhlt.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jyoumei.cn/Article/details/gtltsewbsd.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.kuanghao11.cn/Article/details/gtywahsbmh.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.shzxlz.cn/Article/details/gtdtgeiqtz.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.zycfv.cn/Article/details/gtqlpqmpoq.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.xylfe.cn/Article/details/gtpbuhasan.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.andypj.xyz/Article/details/gtxsxdjees.html

[B07] while 循环
来源：http://dali.birdmap.top/Article/details/gtzeuadudq.html

Py:   while i < 10: i += 1
来源：http://dali.pycfn.com/Article/details/gtkxuoowxq.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.tianlin.xyz/Article/details/gtrvpmqepy.html

JS:   while (i < 10) { i++; }
来源：http://dali.chenlongwang.top/Article/details/gtuizfitmz.html

TS:   while (i < 10) { i++; }
来源：http://dali.hongshengwenyu.top/Article/details/gtkdvaribq.html

Java: while (i < 10) { i++; }
来源：http://dali.cucudq.cn/Article/details/gtcmhjonfl.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.dashuyun.cn/Article/details/gttnngwzmm.html

Ruby: while i < 10; i += 1; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnbuyidpp.html

C#:   while (i < 10) { i++; }
来源：http://dali.zhongyouzk.top/Article/details/gtqsfyimuc.html

[B08] do-while（至少执行一次）
来源：http://dali.zhengqikj.top/Article/details/gttbudlakw.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.yongpay.top/Article/details/gtlwejtdyk.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jiagoushi.top/Article/details/gtcdwovrcl.html

JS:   do { i++; } while (i < 10);
来源：http://dali.haohaochexian.top/Article/details/gtqzdnbgso.html

TS:   do { i++; } while (i < 10);
来源：http://dali.cdnleiting.top/Article/details/gtidhinjpw.html

Java: do { i++; } while (i < 10);
来源：http://dali.yanxiufei.cn/Article/details/gtaezndpou.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.shanyushiyangtech.top/Article/details/gtnkwqrsbs.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbjznmmuv.html

C#:   do { i++; } while (i < 10);
来源：http://dali.dashuyun.cn/Article/details/gtshcafddc.html

[B09] break 与 continue
来源：http://dali.hysaishi.cn/Article/details/gtfczaluzv.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.hnqzz.top/Article/details/gtkcprgjmn.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.smart0.xyz/Article/details/gtyvlrdonz.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.kuanghao11.cn/Article/details/gtytsaqmkk.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sweek.top/Article/details/gtdergpxzw.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenjidiqi.icu/Article/details/gtegajnzlo.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.vqdsnc.cn/Article/details/gtgvykpozj.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.cashguo.top/Article/details/gtqevousjx.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yanxiufei.cn/Article/details/gthciwyiti.html

[B10] 遍历同时拿索引
来源：http://dali.cheryme.top/Article/details/gtbmwbuawp.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.birdmap.top/Article/details/gtzwoppbpd.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.yj20258888.top/Article/details/gtyqypfxvp.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.cqqwz.cn/Article/details/gtbzndgbin.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.yj20258888.top/Article/details/gtnrbmwwla.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.fengsongda.top/Article/details/gtmpdvajbh.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.dashuyun.cn/Article/details/gtucqigsvz.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.cashguo.top/Article/details/gthlzibhld.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.hongshengwenyu.top/Article/details/gtmjlmfoqs.html

[B11] 生成数字序列 / 区间
来源：http://dali.yongpay.top/Article/details/gtojhoupsy.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhengqikj.top/Article/details/gtddonulzn.html

PHP:  range(0, 10, 2);
来源：http://dali.xinyue.icu/Article/details/gtqxuygxpk.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.vqdsnc.cn/Article/details/gtmwsapwoj.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhoulong.xyz/Article/details/gtvgtlooay.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.shuidangran.top/Article/details/gtbogjmcdv.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.snrcjt.cn/Article/details/gttkijwbvz.html

Ruby: (0...10).step(2).to_a
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxrmlvgno.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiquneqva.html

[B12] 跳出多层循环
来源：http://dali.nwbrower.top/Article/details/gtgbrmtqsv.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.tianlin.xyz/Article/details/gthuzhmnok.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.hongshengwenyu.top/Article/details/gtptvdnazr.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzsekxkhu.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shuidangran.top/Article/details/gtwolvsxjq.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.sxryk.cn/Article/details/gtgananzrq.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.chenzaomai.com/Article/details/gtljcyfigu.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.tanke756.top/Article/details/gtgdospdio.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.nanxuanxn.top/Article/details/gtdfbkzdjh.html

[B13] 判断是否为数字
来源：http://dali.hnqzz.top/Article/details/gtoyclotmv.html

Py:   isinstance(x, (int, float))
来源：http://dali.hnqzz.top/Article/details/gtfrycoebe.html

PHP:  is_numeric($x)
来源：http://dali.ehwqpu.com/Article/details/gtknclsxua.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqjjxytou.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhongyouzk.top/Article/details/gtvjpwfbrw.html

Java: x instanceof Number
来源：http://dali.vqdsnc.cn/Article/details/gtpfdygdmx.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.cashguo.top/Article/details/gtqxwcpius.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zycfv.cn/Article/details/gtmatwkuol.html

C#:   x is int or double or decimal
来源：http://dali.mhx1999.top/Article/details/gtqbqnlvxz.html

[B14] 判断值是否在集合内
来源：http://dali.fengsongda.top/Article/details/gtefymvtnm.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.xuanzx.com/Article/details/gthtfoyuhf.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.iojbl.cn/Article/details/gtcoqnkrdb.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.tian-w.cn/Article/details/gtmsgsxnpo.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yj20258888.top/Article/details/gtqznnxzzb.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.cheryme.top/Article/details/gtngmikbzb.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.wangshuangyany.cn/Article/details/gtjklxcfam.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.meibo888.top/Article/details/gtrjblutey.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtidfwjxaj.html

[B15] 布尔运算与取反
来源：http://dali.sweek.top/Article/details/gtzkxccykj.html

Py:   a and b or not c
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaedzepyg.html

PHP:  $a && $b || !$c
来源：http://dali.hammf.cn/Article/details/gtgrfjcsez.html

JS:   a && b || !c
来源：http://dali.yongpay.top/Article/details/gtzimbluxq.html

TS:   a && b || !c
来源：http://dali.nwbrower.top/Article/details/gtuukgbynp.html

Java: a && b || !c
来源：http://dali.gzhubu.top/Article/details/gtzusfhlpb.html

Go:   a && b || !c
来源：http://dali.yueranfly.top/Article/details/gtvqlevwgr.html

Ruby: a && b || !c
来源：http://dali.jianghu66.top/Article/details/gtwucpodau.html

C#:   a && b || !c
来源：http://dali.yj20258.top/Article/details/gtdvxjjrcu.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.316326.xyz/Article/details/gtuvsehipy.html

Py:   if not data: return
来源：http://dali.jinqigfzy.top/Article/details/gtilelgnfb.html

PHP:  if (!$data) { return; }
来源：http://dali.sysykeji.top/Article/details/gtkorxsqeo.html

JS:   if (!data) return;
来源：http://dali.andypj.xyz/Article/details/gtxxhcicmh.html

TS:   if (!data) return;
来源：http://dali.ppjwa.cn/Article/details/gtdkkmsjfi.html

Java: if (data == null) return;
来源：http://dali.xuanzx.com/Article/details/gtbwmblhas.html

Go:   if data == nil { return }
来源：http://dali.jianghu66.top/Article/details/gtpbkrfqag.html

Ruby: return if data.nil?
来源：http://dali.nwbrower.top/Article/details/gtslkcavdc.html

C#:   if (data == null) return;
来源：http://dali.sxryk.cn/Article/details/gtbxmnkfax.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtqmgdehkh.html

C. 函数与作用域
来源：http://dali.jinqigufen.top/Article/details/gtyagevcuw.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtecvayeom.html

[C01] 定义函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwcxtgovt.html

Py:   def add(a, b): return a + b
来源：http://dali.fzhhl.top/Article/details/gtuibkvuqe.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.316326.xyz/Article/details/gtfmdyfeuq.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtczugdqtn.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjeejwafk.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtpvfuekbu.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.hysaishi.cn/Article/details/gtchyrynfw.html

Ruby: def add(a, b); a + b; end
来源：http://dali.cdnleiting.top/Article/details/gtgspeyncw.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zycfv.cn/Article/details/gtbnargyol.html

[C02] 默认参数
来源：http://dali.hysaishi.cn/Article/details/gtzbgesyqg.html

Py:   def greet(name="World"): return name
来源：http://dali.zycfv.cn/Article/details/gtqrvbxrtf.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.iojbl.cn/Article/details/gtlkrnpetj.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.guannengcc.top/Article/details/gttjgxqaoj.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jiagoushi.top/Article/details/gtyuxgetex.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.wangshuangyany.cn/Article/details/gtukywmtbw.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.vqdsnc.cn/Article/details/gtdqlthkou.html

Ruby: def greet(name = "World") = name
来源：http://dali.c1oappe.top/Article/details/gtlkigakrn.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdrkfdabf.html

[C03] 可变参数
来源：http://dali.shuidangran.top/Article/details/gtuifvqrmz.html

Py:   def total(*args): return sum(args)
来源：http://dali.ybcxt.top/Article/details/gtewcknrxs.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yj202588.top/Article/details/gtkcbyzcqo.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yj202588.top/Article/details/gthvcvfzog.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdxresral.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.quarkkingdee.top/Article/details/gttwevnphy.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jinghuilouyu.cn/Article/details/gtfuqjelzn.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.xylfe.cn/Article/details/gtulpzqcdb.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.aizwys.cn/Article/details/gtjpjgywbx.html

[C04] 命名参数 / 关键字参数
来源：http://dali.dashuyun.cn/Article/details/gttromxcqx.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gtdbicxrxe.html


<!-- 参考信息 -->