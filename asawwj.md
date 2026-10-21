代发 wailian999

[A14] 注释写法
来源：http://dali.andypj.xyz/Article/details/gtkfilmvzo.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zycfv.cn/Article/details/gttfgklsgq.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.wangdashe.top/Article/details/gteihajglx.html

JS:   // 单行；/* 多行 */
来源：http://dali.yuanzhike.top/Article/details/gteavphdfd.html

TS:   // 单行；/* 多行 */
来源：http://dali.jianghu66.top/Article/details/gtgzcymepz.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.316326.xyz/Article/details/gtxijwppvs.html

Go:   // 单行；/* 多行 */
来源：http://dali.cashguo.top/Article/details/gtjocfikag.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.yangfankeji.com/Article/details/gtdxwzdbun.html

C#:   // 单行；/* 多行 */
来源：http://dali.yuanzhike.top/Article/details/gtaxsvjslq.html

[A15] 空值判断与默认值
来源：http://dali.pengpengdd.cyou/Article/details/gtqkmcuwxw.html

Py:   value = data or "默认值"
来源：http://dali.meibo888.top/Article/details/gtgxqfiwog.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhongyouzk.top/Article/details/gtuwurgslv.html

JS:   const value = data ?? "默认值";
来源：http://dali.yongpay.top/Article/details/gtjkldrdfx.html

TS:   const value = data ?? "默认值";
来源：http://dali.sysykeji.top/Article/details/gtbixwtufs.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.fengsongda.top/Article/details/gtiadquzxl.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zycfv.cn/Article/details/gtgeeuocgl.html

Ruby: value = data || "默认值"
来源：http://dali.snrcjt.cn/Article/details/gtsjxdkpyv.html

C#:   var value = data ?? "默认值";
来源：http://dali.nanxuanxn.top/Article/details/gtmczdpicc.html

[A16] 真假值判断规则
来源：http://dali.dianchejie.cn/Article/details/gtzfuzqpwp.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.yonumen.top/Article/details/gtomkrvjjt.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.cdnleiting.top/Article/details/gtjyuqzuyu.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.aizwys.cn/Article/details/gtywxatfud.html

TS:   if (!x) {}
来源：http://dali.kuanghao11.cn/Article/details/gtghemuwll.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.svipenyu.cn/Article/details/gtejnmoaqr.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.gogol.net.cn/Article/details/gtpfvupezm.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.hnxiangtu.top/Article/details/gtsvnjoktp.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.aizwys.cn/Article/details/gtpdibqnqs.html

[A17] 位运算
来源：http://dali.xylfe.cn/Article/details/gtyteabrzc.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhengqikj.top/Article/details/gttghtcpxf.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.ehwqpu.com/Article/details/gtqgtzvrqe.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hammf.cn/Article/details/gtlxvkbten.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.hysaishi.cn/Article/details/gtafxkigfx.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.nanxuanxn.top/Article/details/gtioxeakcl.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.shuidangran.top/Article/details/gtlciwsvrj.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hysaishi.cn/Article/details/gtwuvkfqrv.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xziqi.cn/Article/details/gthhmjjnuf.html

[A18] 字符与 ASCII 码互转
来源：http://dali.vqdsnc.cn/Article/details/gtyrvqwmva.html

Py:   ord("A"); chr(65)
来源：http://dali.yj20258888.top/Article/details/gtlcuesiih.html

PHP:  ord("A"); chr(65)
来源：http://dali.feifeiyinyue.top/Article/details/gtwcuaxuhk.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.tanke756.top/Article/details/gtmythtmez.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.xylfe.cn/Article/details/gtervnkcmp.html

Java: (int) 'A'; (char) 65
来源：http://dali.yj20258.top/Article/details/gtgdizcbna.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.shuidangran.top/Article/details/gtgbvnzlbh.html

Ruby: "A".ord; 65.chr
来源：http://dali.hysaishi.cn/Article/details/gtvndedqjt.html

C#:   (int)'A'; (char)65
来源：http://dali.hysaishi.cn/Article/details/gtbqsignus.html

[A19] 交换两个变量
来源：http://dali.xziqi.cn/Article/details/gtflcvfmij.html

Py:   a, b = b, a
来源：http://dali.sysykeji.top/Article/details/gtgbnrlimg.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.yvedp.cn/Article/details/gtrixmapqz.html

JS:   [a, b] = [b, a];
来源：http://dali.jinqigfzy.top/Article/details/gttkomavtj.html

TS:   [a, b] = [b, a];
来源：http://dali.yueranfly.top/Article/details/gtbzywvexz.html

Java: int t = a; a = b; b = t;
来源：http://dali.aizwys.cn/Article/details/gtseclxvvl.html

Go:   a, b = b, a
来源：http://dali.316326.xyz/Article/details/gtixofvlty.html

Ruby: a, b = b, a
来源：http://dali.zhiwuduotai.top/Article/details/gttcafbabr.html

C#:   (a, b) = (b, a);
来源：http://dali.haohaochexian.top/Article/details/gtiiljbyqw.html

[A20] 读取标准输入
来源：http://dali.c1oappe.top/Article/details/gtbqlegmdd.html

Py:   name = input("请输入：")
来源：http://dali.tianlin.xyz/Article/details/gterqnqhau.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.tanke756.top/Article/details/gtshejthdm.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.aibaodan.cn/Article/details/gtbnuqxumr.html

TS:   // Node.js：readline 模块
来源：http://dali.yvedp.cn/Article/details/gtckucsutd.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.yongpay.top/Article/details/gtcapyfcwi.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.haohaochexian.top/Article/details/gtmiupijpv.html

Ruby: gets.chomp
来源：http://dali.zhiwuduotai.top/Article/details/gtyrbvdwks.html

C#:   Console.ReadLine();
来源：http://dali.zhoulong.xyz/Article/details/gtcyzamweq.html

[A21] 保留指定小数位输出
来源：http://dali.yueranfly.top/Article/details/gtorntptsq.html

Py:   f"{3.14159:.2f}"
来源：http://dali.cashguo.top/Article/details/gtyfglaebt.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqpuhdbxg.html

JS:   (3.14159).toFixed(2)
来源：http://dali.vqdsnc.cn/Article/details/gtzknmqhfm.html

TS:   (3.14159).toFixed(2)
来源：http://dali.shangyingyoupin.top/Article/details/gtwwnsjuuk.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.yvedp.cn/Article/details/gtokvyardp.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.gogol.net.cn/Article/details/gtlepqjznc.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.dashuyun.cn/Article/details/gtrmlemxhl.html

C#:   3.14159.ToString("F2")
来源：http://dali.quarkkingdee.top/Article/details/gtsymdskvu.html

[A22] 获取字符串长度
来源：http://dali.yuanzhike.top/Article/details/gtdiaqxehb.html

Py:   len(s)
来源：http://dali.jlsjyb.cn/Article/details/gtutltwjtu.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.9152youxi.cn/Article/details/gtjnkjawqq.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.sufxvd.cn/Article/details/gtbllsnhoq.html

TS:   s.length
来源：http://dali.jiagoushi.top/Article/details/gtpyrfisxs.html

Java: s.length()
来源：http://dali.andypj.xyz/Article/details/gtspippsxu.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.yanxiufei.cn/Article/details/gtotkoxgig.html

Ruby: s.length
来源：http://dali.ybcxt.top/Article/details/gtffwzfldt.html

C#:   s.Length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkylqluwe.html

[A23] 大小写转换
来源：http://dali.nanxinkj.top/Article/details/gtgnprcquo.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.sxryk.cn/Article/details/gtqojnbjrw.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.yuanzhike.top/Article/details/gtxbceteur.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.yueranfly.top/Article/details/gtjoecbxev.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.jinghuilouyu.cn/Article/details/gtnsvcqdgx.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.yj202588.top/Article/details/gtlftkkcyp.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.jiagoushi.top/Article/details/gtgjtlwyit.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.tianlin.xyz/Article/details/gtefvlpmge.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.fzhhl.top/Article/details/gtpclexpow.html

[A24] 去除首尾空白
来源：http://dali.c1oappe.top/Article/details/gtqdxtvtzb.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.0kj1m.cn/Article/details/gtslgdahil.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.hnqzz.top/Article/details/gttvobtjbc.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.sysykeji.top/Article/details/gtnbdwmzlj.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yueranfly.top/Article/details/gticmfgxnu.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.sweek.top/Article/details/gtpcqawghr.html

Go:   strings.TrimSpace(s)
来源：http://dali.ybcxt.top/Article/details/gtvzberdin.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.yueranfly.top/Article/details/gtdylwnyer.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.bjfxy.top/Article/details/gtzatpqdhi.html

[A25] 字符串比较
来源：http://dali.sufxvd.cn/Article/details/gtyugzdeww.html

Py:   s1 == s2; s1 != s2
来源：http://dali.chenzaomai.com/Article/details/gtwjlvnskj.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.yuanzhike.top/Article/details/gtukefxojb.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.hnqzz.top/Article/details/gtscyrgmvw.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.cheryme.top/Article/details/gtikjbsaad.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.zhoulong.xyz/Article/details/gtywputmwe.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.yuanzhike.top/Article/details/gtjarrcfrd.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpaxdqvjx.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.gzhubu.top/Article/details/gtnbojedqe.html

[A26] 类型转换总览
来源：http://dali.ppjwa.cn/Article/details/gtsdekibpv.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.yueranfly.top/Article/details/gtjdalzgkz.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.havefunace.top/Article/details/gtxktfvptp.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.ybcxt.top/Article/details/gtmwgxwcsl.html

TS:   Number() String() Boolean() x as number
来源：http://dali.tanke756.top/Article/details/gtasdggrfp.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.zhiwuduotai.top/Article/details/gtnzhrqcdd.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.chenlongwang.top/Article/details/gtcxwfsdpo.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.redwolf501.top/Article/details/gtauzwqnko.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.jyoumei.cn/Article/details/gtwakwzhpr.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtwbgbphbi.html

B. 流程控制
来源：http://dali.shuidangran.top/Article/details/gtyafvknmm.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtpsnzgyxp.html

[B01] 条件判断 if / else
来源：http://dali.tianlin.xyz/Article/details/gtauxrbftz.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.316326.xyz/Article/details/gtbyfuhnul.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.sxryk.cn/Article/details/gtxeywhkrh.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.vqdsnc.cn/Article/details/gtylnqfdqe.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.pengpengdd.cyou/Article/details/gttdbgquiz.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.haohaochexian.top/Article/details/gtoemgurop.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.yongpay.top/Article/details/gtamrqizng.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.jinqigufen.top/Article/details/gtcdzdhxde.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.hnqzz.top/Article/details/gtuheqozdn.html

[B02] 多分支 else if / elif
来源：http://dali.gotoacloud.top/Article/details/gtdbecfilx.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.jyoumei.cn/Article/details/gtsohxohft.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.havefunace.top/Article/details/gtnhrmcfxj.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.wangdashe.top/Article/details/gtwhljfyul.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.pengpengdd.cyou/Article/details/gtwykiigcw.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jianghu66.top/Article/details/gtetyjnqrb.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.yongpay.top/Article/details/gtmyvecesi.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.gotoacloud.top/Article/details/gtmlfohwrl.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinqigfzy.top/Article/details/gthallsmka.html

[B03] switch / match / case
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiooxxtmg.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoqifblxn.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.shuidangran.top/Article/details/gtcgljmtfs.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.0kj1m.cn/Article/details/gtrheygnqf.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtewrreoro.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.dianchejie.cn/Article/details/gtsoolfops.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.birdmap.top/Article/details/gtuyuglkxv.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.pengpengdd.cyou/Article/details/gthxusqlvi.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.cheryme.top/Article/details/gtkaebgwec.html

[B04] for 计数循环
来源：http://dali.zhengqikj.top/Article/details/gtlragxnme.html

Py:   for i in range(10): print(i)
来源：http://dali.316326.xyz/Article/details/gtrdcdvdto.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.shangyingyoupin.top/Article/details/gtbbbzfbtd.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.pycfn.com/Article/details/gtiberamho.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.svipenyu.cn/Article/details/gtpkddkkxw.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.mhx1999.top/Article/details/gtqzwypmyr.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.yuxming.cn/Article/details/gtmdlwqxvw.html

Ruby: 10.times { |i| puts i }
来源：http://dali.ivvv.top/Article/details/gtmzkholjl.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.fzhhl.top/Article/details/gtzojwhnmj.html

[B05] 遍历数组 / 列表
来源：http://dali.wangdashe.top/Article/details/gtoxrwyyke.html

Py:   for item in arr: print(item)
来源：http://dali.yuxming.cn/Article/details/gtckahgwnv.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.yanxiufei.cn/Article/details/gtyclmmrkk.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.pengpengdd.cyou/Article/details/gtojsjcuok.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.gogol.net.cn/Article/details/gteprydpje.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.meibo888.top/Article/details/gtyuhwsafa.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.kuanghao11.cn/Article/details/gtgzdtoaer.html

Ruby: arr.each { |item| puts item }
来源：http://dali.andypj.xyz/Article/details/gtdhlgaort.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.yj20258.top/Article/details/gtucojhjgo.html

[B06] 遍历字典 / 对象
来源：http://dali.yuxming.cn/Article/details/gtniqwhutu.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.shuidangran.top/Article/details/gthgytkppx.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsqbkkrhm.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.wangdashe.top/Article/details/gtoxzgwyub.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.hfpthk.cn/Article/details/gtayqxfnjh.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.daxiang520.top/Article/details/gtylsveciu.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.chenzaomai.com/Article/details/gtppnpwjso.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.yuxming.cn/Article/details/gtbcjtdxku.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.yj20258.top/Article/details/gtuqqgrppe.html

[B07] while 循环
来源：http://dali.pycfn.com/Article/details/gtyenvjpxp.html

Py:   while i < 10: i += 1
来源：http://dali.jinqigfzy.top/Article/details/gtcxzoynqe.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.ppjwa.cn/Article/details/gtsuxonblo.html

JS:   while (i < 10) { i++; }
来源：http://dali.redwolf501.top/Article/details/gthbqsgrff.html

TS:   while (i < 10) { i++; }
来源：http://dali.bjfxy.top/Article/details/gtwonqjboy.html

Java: while (i < 10) { i++; }
来源：http://dali.sxryk.cn/Article/details/gtzvzobhpg.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.yuxming.cn/Article/details/gtyygsbzfp.html

Ruby: while i < 10; i += 1; end
来源：http://dali.meibo888.top/Article/details/gtyfaglrfn.html

C#:   while (i < 10) { i++; }
来源：http://dali.iojbl.cn/Article/details/gtpqhzvhuy.html

[B08] do-while（至少执行一次）
来源：http://dali.xuetiantiany.cn/Article/details/gtqqgffgmt.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.xuetiantiany.cn/Article/details/gtnenwuqgx.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.andypj.xyz/Article/details/gtlcwtjhhd.html

JS:   do { i++; } while (i < 10);
来源：http://dali.fzhhl.top/Article/details/gtncoacbad.html

TS:   do { i++; } while (i < 10);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqrqfqmeq.html

Java: do { i++; } while (i < 10);
来源：http://dali.hnqzz.top/Article/details/gtcqsmcfni.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.guowangkeji.top/Article/details/gtjtaripsl.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.xylfe.cn/Article/details/gtepjiarfe.html

C#:   do { i++; } while (i < 10);
来源：http://dali.guowangkeji.top/Article/details/gtmrkcvbim.html

[B09] break 与 continue
来源：http://dali.jinqigufen.top/Article/details/gtzuhjlhgx.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.zhongyouzk.top/Article/details/gtdxzfwkle.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.dashuyun.cn/Article/details/gtvjkuiobo.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.0kj1m.cn/Article/details/gtflcmfenu.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhoulong.xyz/Article/details/gtcluzqbes.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hnxiangtu.top/Article/details/gtbgknruhv.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.dianchejie.cn/Article/details/gtblnywsdk.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zhongyouzk.top/Article/details/gttuncqtrj.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hywenlv.cn/Article/details/gtbigragcb.html

[B10] 遍历同时拿索引
来源：http://dali.cheryme.top/Article/details/gttkbsmecb.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.andypj.xyz/Article/details/gtbombyjlv.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqeeazwbo.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.quarkkingdee.top/Article/details/gteouglnme.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jinghuilouyu.cn/Article/details/gtridiwgjv.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yonumen.top/Article/details/gtcaykekem.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.tian-w.cn/Article/details/gtmwznzzoe.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.shangyingyoupin.top/Article/details/gtmyymgydz.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.gogol.net.cn/Article/details/gtthknlozr.html

[B11] 生成数字序列 / 区间
来源：http://dali.cqqwz.cn/Article/details/gthpjljokz.html

Py:   list(range(0, 10, 2))
来源：http://dali.yongpay.top/Article/details/gtwbqtuhud.html

PHP:  range(0, 10, 2);
来源：http://dali.gaohongyu789.top/Article/details/gtzmysovns.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.pengpengdd.cyou/Article/details/gtellcbibi.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.aibaodan.cn/Article/details/gtkbtaamsb.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.ehwqpu.com/Article/details/gtqthmjfyp.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.jinqigfzy.top/Article/details/gtydvqowii.html

Ruby: (0...10).step(2).to_a
来源：http://dali.nanxinkj.top/Article/details/gtpjkiarhj.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.shzxlz.cn/Article/details/gtyzebnrcc.html

[B12] 跳出多层循环
来源：http://dali.c1oappe.top/Article/details/gtkyxexxkb.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.gaohongyu789.top/Article/details/gtzwpwoelo.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.gzhubu.top/Article/details/gtqtxususz.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpvdldeif.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yanxiufei.cn/Article/details/gtvvauzukp.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.0kj1m.cn/Article/details/gtzwmppglv.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhongyouzk.top/Article/details/gtfihmyrkr.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.vqdsnc.cn/Article/details/gtwhlrfmas.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhijiandao.cn/Article/details/gtbbxsonuq.html

[B13] 判断是否为数字
来源：http://dali.shanyushiyangtech.top/Article/details/gtsjasllzf.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhixingplan.top/Article/details/gtkcecquse.html

PHP:  is_numeric($x)
来源：http://dali.meibo888.top/Article/details/gtennzjjjl.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.daxiang520.top/Article/details/gthcxvzgwg.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ehwqpu.com/Article/details/gtdlkfrpfv.html

Java: x instanceof Number
来源：http://dali.yj20258.top/Article/details/gtdbjzaqaj.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.cdnleiting.top/Article/details/gtswkyyrje.html

Ruby: x.is_a?(Numeric)
来源：http://dali.feifeiyinyue.top/Article/details/gtaflvjwlu.html

C#:   x is int or double or decimal
来源：http://dali.jinqigufen.top/Article/details/gtifeglega.html

[B14] 判断值是否在集合内
来源：http://dali.hongshengwenyu.top/Article/details/gtkhsijfci.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.iojbl.cn/Article/details/gtawqbtetw.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.dianchejie.cn/Article/details/gtjpglfqze.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.hammf.cn/Article/details/gtkzmosqyz.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yuxming.cn/Article/details/gtmnxtdzgk.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.cheryme.top/Article/details/gtkmhvxicy.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.chenlongwang.top/Article/details/gtamjkpbsx.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.aibaodan.cn/Article/details/gtkznmthnq.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yueranfly.top/Article/details/gtttsubqdb.html

[B15] 布尔运算与取反
来源：http://dali.jinqigfzy.top/Article/details/gtbhvpgdat.html

Py:   a and b or not c
来源：http://dali.nwbrower.top/Article/details/gtnjsndshy.html

PHP:  $a && $b || !$c
来源：http://dali.zhiwuduotai.top/Article/details/gtvgyyeact.html

JS:   a && b || !c
来源：http://dali.mhx1999.top/Article/details/gtpxysmksi.html

TS:   a && b || !c
来源：http://dali.vqdsnc.cn/Article/details/gtenveqgbp.html

Java: a && b || !c
来源：http://dali.ydzc1.top/Article/details/gtbdbiskll.html

Go:   a && b || !c
来源：http://dali.bjfxy.top/Article/details/gtgunxarhn.html

Ruby: a && b || !c
来源：http://dali.wangshuangyany.cn/Article/details/gtasklyeyz.html

C#:   a && b || !c
来源：http://dali.yanxiufei.cn/Article/details/gtmketpoyb.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yvedp.cn/Article/details/gtbwqhgwvh.html

Py:   if not data: return
来源：http://dali.cdnleiting.top/Article/details/gtzcwhyzsn.html

PHP:  if (!$data) { return; }
来源：http://dali.andypj.xyz/Article/details/gthnkfxbjo.html

JS:   if (!data) return;
来源：http://dali.nwbrower.top/Article/details/gtlmwvirru.html

TS:   if (!data) return;
来源：http://dali.jqgfzy.top/Article/details/gtasylgufm.html

Java: if (data == null) return;
来源：http://dali.dashuyun.cn/Article/details/gtyhjxvhwv.html

Go:   if data == nil { return }
来源：http://dali.zhongyouzk.top/Article/details/gtuxbyjmrm.html

Ruby: return if data.nil?
来源：http://dali.hysaishi.cn/Article/details/gtgzpoaxgs.html

C#:   if (data == null) return;
来源：http://dali.guannengcc.top/Article/details/gtvxbavkzt.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtjopjscre.html

C. 函数与作用域
来源：http://dali.jinyuanbaomall.cn/Article/details/gtraocdogr.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtjgwphqtn.html

[C01] 定义函数
来源：http://dali.fengsongda.top/Article/details/gtpbppllwp.html

Py:   def add(a, b): return a + b
来源：http://dali.dashuyun.cn/Article/details/gtylpzeizj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ehwqpu.com/Article/details/gtpbumembl.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yanxiufei.cn/Article/details/gtfxolmwqf.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.iojbl.cn/Article/details/gtndcocayw.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.haohaochexian.top/Article/details/gtxpyieagm.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yj20258.top/Article/details/gtttlzivxy.html

Ruby: def add(a, b); a + b; end
来源：http://dali.nanxuanxn.top/Article/details/gtwgrctlcj.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.iojbl.cn/Article/details/gtsjzaibkb.html

[C02] 默认参数
来源：http://dali.havefunace.top/Article/details/gtwgtkiemz.html

Py:   def greet(name="World"): return name
来源：http://dali.snrcjt.cn/Article/details/gtadvblpxj.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.cashguo.top/Article/details/gtlbaqlssa.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jqgufenzy.top/Article/details/gtlosrlors.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yongpay.top/Article/details/gtvhlqjlig.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.iojbl.cn/Article/details/gtxtbqhtdx.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.sysykeji.top/Article/details/gtyqnrqhtp.html

Ruby: def greet(name = "World") = name
来源：http://dali.daria6918.cn/Article/details/gtcrxbvmjz.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.smart0.xyz/Article/details/gtlomhhors.html

[C03] 可变参数
来源：http://dali.shangyingyoupin.top/Article/details/gtxshhbvvm.html

Py:   def total(*args): return sum(args)
来源：http://dali.mhx1999.top/Article/details/gttyffyapf.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.0kj1m.cn/Article/details/gtcxwmupjb.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.havefunace.top/Article/details/gtcobzwkpr.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.redwolf501.top/Article/details/gtwalckoej.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.snrcjt.cn/Article/details/gtzcxxgtgl.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.kuanghao11.cn/Article/details/gtyfgsydnw.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jinqigufen.top/Article/details/gtyhzegczk.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.hongshengwenyu.top/Article/details/gtvmeewgjo.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhengqikj.top/Article/details/gtngrpoxlq.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.pycfn.com/Article/details/gtpntqjgot.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.shangyingyoupin.top/Article/details/gthojhtwrl.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yj20258.top/Article/details/gtanvsqtbt.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jinghuilouyu.cn/Article/details/gtkvpsbdxf.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.tanke756.top/Article/details/gttellcnzz.html


<!-- 参考信息 -->