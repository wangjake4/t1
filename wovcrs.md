代发 wailian999

TS:   "7".padStart(3, "0")
来源：http://dali.mhx1999.top/Article/details/gtbsawwjks.html

Java: String.format("%03d", 7)
来源：http://dali.yj20258888.top/Article/details/gtpzqtnlev.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.chenjidiqi.icu/Article/details/gtvvsvvdms.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.daria6918.cn/Article/details/gtjjnbebyw.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jiagoushi.top/Article/details/gtdgugdayw.html

[E11] 反转字符串
来源：http://dali.zhongyouzk.top/Article/details/gtidoynicm.html

Py:   s[::-1]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrqipenzs.html

PHP:  strrev($s);
来源：http://dali.zdqjudy.top/Article/details/gtyzcexgbk.html

JS:   [...s].reverse().join("")
来源：http://dali.yuxming.cn/Article/details/gtcqhdojgx.html

TS:   [...s].reverse().join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gthpglatjr.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.gzhubu.top/Article/details/gtbytvqctl.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.fengsongda.top/Article/details/gtjgxzbjpt.html

Ruby: s.reverse
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrbfzozge.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.dianchejie.cn/Article/details/gtfofmecuy.html

[E12] 统计某字符出现次数
来源：http://dali.vqdsnc.cn/Article/details/gtboleexzi.html

Py:   s.count("a")
来源：http://dali.shangyingyoupin.top/Article/details/gtmprqidmc.html

PHP:  substr_count($s, "a");
来源：http://dali.zhixingplan.top/Article/details/gtpbytxyzx.html

JS:   s.split("a").length - 1
来源：http://dali.redwolf501.top/Article/details/gtjyavbqsy.html

TS:   s.split("a").length - 1
来源：http://dali.zdqjudy.top/Article/details/gtxwydajph.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhiwuduotai.top/Article/details/gtsppabrmg.html

Go:   strings.Count(s, "a")
来源：http://dali.dashuyun.cn/Article/details/gtgyctcubh.html

Ruby: s.count("a")
来源：http://dali.hnqzz.top/Article/details/gtganinwyj.html

C#:   s.Count(c => c == 'a')
来源：http://dali.feifeiyinyue.top/Article/details/gtfsjopnma.html

[E13] 逐字符遍历
来源：http://dali.hysaishi.cn/Article/details/gtqiguqvgx.html

Py:   for ch in s: print(ch)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpysipzbk.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.9152youxi.cn/Article/details/gtvcvhuejh.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.nanxinkj.top/Article/details/gtoporywjf.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.haohaochexian.top/Article/details/gtpbxqhxok.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.pycfn.com/Article/details/gtdtdmnrrk.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zdqjudy.top/Article/details/gtrcsmypqg.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.shzxlz.cn/Article/details/gtigzfrbpw.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.tanke756.top/Article/details/gtltmubcqf.html

[E14] URL 编码与 Base64
来源：http://dali.wangshuangyany.cn/Article/details/gtngkokilo.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.gzhubu.top/Article/details/gtrqyrapkz.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuhtzrwfu.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.smart0.xyz/Article/details/gtpteevthk.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtvulbkhdt.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jyoumei.cn/Article/details/gttnbhifyb.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yonumen.top/Article/details/gtdoaykuls.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.sysykeji.top/Article/details/gtukikppeb.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.andypj.xyz/Article/details/gtrjyjiddz.html

[E15] HTML 转义 / 反转义
来源：http://dali.jqgfzy.top/Article/details/gtvneitjuu.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yuanzhike.top/Article/details/gtsacnfsfk.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.ivvv.top/Article/details/gtaxotzfwv.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.snrcjt.cn/Article/details/gtmwelzlbf.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.andypj.xyz/Article/details/gtrxrypwmz.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.sysykeji.top/Article/details/gtcsmqxhls.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtnjpmdzrm.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.quarkkingdee.top/Article/details/gtyycsxbno.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.sufxvd.cn/Article/details/gtcgkxhohx.html

[E16] 数字千分位
来源：http://dali.zhiwuduotai.top/Article/details/gtgujewjoo.html

Py:   f"{1234567:,}"
来源：http://dali.hysaishi.cn/Article/details/gtkswjvojf.html

PHP:  number_format(1234567);
来源：http://dali.nanxuanxn.top/Article/details/gthjoykhba.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.tian-w.cn/Article/details/gtuiakxxwe.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.ehwqpu.com/Article/details/gtwjxueozf.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yvedp.cn/Article/details/gtqxtnjdsf.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhixingplan.top/Article/details/gtmcuhhhad.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.gogol.net.cn/Article/details/gtqzhumzcn.html

C#:   1234567.ToString("N0")
来源：http://dali.hywenlv.cn/Article/details/gthflsxorr.html

[E17] 首字母大写
来源：http://dali.yuanzhike.top/Article/details/gtxpljukpm.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.shangyingyoupin.top/Article/details/gttdcowctz.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.fengsongda.top/Article/details/gtbxnvqzkc.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.daria6918.cn/Article/details/gtflddswyr.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.9152youxi.cn/Article/details/gtjxhdnxnq.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtkpcnghwa.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.cheryme.top/Article/details/gthekkodgw.html

Ruby: s.capitalize
来源：http://dali.xylfe.cn/Article/details/gtsaazwsmm.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.xuanzx.com/Article/details/gteqbpdulw.html

[E18] 模板占位符替换
来源：http://dali.jianghu66.top/Article/details/gtxoohsylf.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.kuanghao11.cn/Article/details/gtyzsfcviu.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hfpthk.cn/Article/details/gtecoyvslh.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlxgkwycp.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.sweek.top/Article/details/gtflheodrc.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jqgufenzy.top/Article/details/gtdryryzsm.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.bjfxy.top/Article/details/gtrytwbtbt.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yj202588.top/Article/details/gtctebdetr.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.vqdsnc.cn/Article/details/gtsrgtrszw.html

[E19] 多行文本按行拆分
来源：http://dali.sufxvd.cn/Article/details/gtrbebstef.html

Py:   s.splitlines()
来源：http://dali.shangyingyoupin.top/Article/details/gtzyiqgphd.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hnxiangtu.top/Article/details/gthwwdgmsh.html

JS:   s.split(/\r?\n/)
来源：http://dali.svipenyu.cn/Article/details/gtodtkpykq.html

TS:   s.split(/\r?\n/)
来源：http://dali.aizwys.cn/Article/details/gtftqvzkxm.html

Java: s.lines().toList()
来源：http://dali.redwolf501.top/Article/details/gtkgdcbkba.html

Go:   strings.Split(s, "\n")
来源：http://dali.xuanzx.com/Article/details/gthewrutvm.html

Ruby: s.lines
来源：http://dali.zhoulong.xyz/Article/details/gtbskoiwlj.html

C#:   s.Split('\n')
来源：http://dali.iojbl.cn/Article/details/gtzagzudef.html

[E20] 判断字符串是否为空
来源：http://dali.sufxvd.cn/Article/details/gtkmtjneop.html

Py:   if not s:
来源：http://dali.guannengcc.top/Article/details/gtyrwboqwz.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhengqikj.top/Article/details/gtzuejaaum.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtfafvpcwk.html

TS:   if (s === "") {}
来源：http://dali.sxryk.cn/Article/details/gtrcdxpbbj.html

Java: if (s.isEmpty()) {}
来源：http://dali.ivvv.top/Article/details/gtzrlegaot.html

Go:   if s == "" {}
来源：http://dali.yonumen.top/Article/details/gtgnjitbgd.html

Ruby: if s.empty?
来源：http://dali.svipenyu.cn/Article/details/gtkxgmwqqq.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.gaohongyu789.top/Article/details/gtachgnkgv.html

[E21] 超长截断加省略号
来源：http://dali.sufxvd.cn/Article/details/gtpyhoirha.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yonumen.top/Article/details/gtzkwzrmfu.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.xinyue.icu/Article/details/gtqyskjpsy.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yangfankeji.com/Article/details/gthvzrbwam.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.snrcjt.cn/Article/details/gtzfvgpexk.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ybcxt.top/Article/details/gtotpmajhb.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.wangshuangyany.cn/Article/details/gtruyltczj.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.gzhubu.top/Article/details/gtlrbbjmyx.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hnqzz.top/Article/details/gtngbvdjiw.html

[E22] 字节长度与字符长度
来源：http://dali.dianchejie.cn/Article/details/gtzgufjhnu.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.gogol.net.cn/Article/details/gtryqmlyqm.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.havefunace.top/Article/details/gtlmztyuyh.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yvedp.cn/Article/details/gtudipktvo.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hysaishi.cn/Article/details/gtigizgqks.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xinyue.icu/Article/details/gtwyfnaqps.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.wangshuangyany.cn/Article/details/gtvqmniuxn.html

Ruby: s.bytesize;  s.length
来源：http://dali.yangfankeji.com/Article/details/gtbxkjpvbu.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.kuanghao11.cn/Article/details/gtpvrymefv.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtvpgqlobm.html

F. 文件与目录
来源：http://dali.yongpay.top/Article/details/gtpgbhsigv.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtunwtggnt.html

[F01] 读取整个文件
来源：http://dali.jinghuilouyu.cn/Article/details/gthahjslml.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.sysykeji.top/Article/details/gtbtblcgdy.html

PHP:  file_get_contents("a.txt");
来源：http://dali.daxiang520.top/Article/details/gtsnmcbfbw.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yangfankeji.com/Article/details/gthokiqmxz.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jiagoushi.top/Article/details/gtgyepyfuv.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.fengsongda.top/Article/details/gtndimrfpj.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hfpthk.cn/Article/details/gtsxvkcoma.html

Ruby: File.read("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtjxrxaozk.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gtoxszmirw.html

[F02] 逐行读取文件
来源：http://dali.0kj1m.cn/Article/details/gtnbvebpmb.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.snrcjt.cn/Article/details/gtvuemxylp.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.nwbrower.top/Article/details/gtikmannuj.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zdqjudy.top/Article/details/gtrowjrncn.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xinyue.icu/Article/details/gtifnwkeks.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yangfankeji.com/Article/details/gthggtehca.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.svipenyu.cn/Article/details/gtpxfmokcc.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.cheryme.top/Article/details/gtxlpvttei.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.mhx1999.top/Article/details/gtlnwctqyq.html

[F03] 写入文件（覆盖）
来源：http://dali.gogol.net.cn/Article/details/gtxrxccojy.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.shuidangran.top/Article/details/gtfvfkwrbq.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yonumen.top/Article/details/gtzdolazdr.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shuidangran.top/Article/details/gttccsmawf.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shangyingyoupin.top/Article/details/gtswlfdqgh.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.ivvv.top/Article/details/gtfxpduvfe.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.guowangkeji.top/Article/details/gtfojzkerj.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.redwolf501.top/Article/details/gtjqsovbxr.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.nanxuanxn.top/Article/details/gtalslgwsh.html

[F04] 追加写入文件
来源：http://dali.guowangkeji.top/Article/details/gtdbevzyoy.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yanxiufei.cn/Article/details/gtdeyhlryz.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhixingplan.top/Article/details/gtusrysggk.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.svipenyu.cn/Article/details/gtfdyzzypz.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.svipenyu.cn/Article/details/gtpfhwybuv.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.cashguo.top/Article/details/gtahepdeyx.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxkwtxkwk.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.nanxuanxn.top/Article/details/gtmfmmwhuk.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jiagoushi.top/Article/details/gtinszkqgw.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhoulong.xyz/Article/details/gtejrmqohp.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jinqigufen.top/Article/details/gtxdyztuib.html

PHP:  file_exists("a.txt");
来源：http://dali.xziqi.cn/Article/details/gtxdjxmktm.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtiqoptjxw.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtaqyigsfp.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.cheryme.top/Article/details/gtmwjwcdgx.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hnxiangtu.top/Article/details/gthlkxrfxc.html

Ruby: File.exist?("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtbphlgxqe.html

C#:   File.Exists("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtzrxyukct.html

[F06] 删除文件
来源：http://dali.dianchejie.cn/Article/details/gtaclttmmt.html

Py:   os.remove("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtbjljfyoj.html

PHP:  unlink("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtrfmhtrip.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtvosupixp.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yongpay.top/Article/details/gtpmhlvfwr.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.ivvv.top/Article/details/gturkuoaop.html

Go:   os.Remove("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtyklqnuqg.html

Ruby: File.delete("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtuvnkcpgl.html

C#:   File.Delete("a.txt");
来源：http://dali.tanke756.top/Article/details/gtuiwgoerc.html

[F07] 创建目录（含多级）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxpkynstq.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.nwbrower.top/Article/details/gtjqfgjwqk.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xziqi.cn/Article/details/gtcvjcwjzd.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jqgufenzy.top/Article/details/gtzpowsqtr.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.daria6918.cn/Article/details/gtvenolzap.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.tian-w.cn/Article/details/gtpptsgwmq.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ybcxt.top/Article/details/gtabxphdhr.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.c1oappe.top/Article/details/gtawekiykr.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jyoumei.cn/Article/details/gtmwmmbikr.html

[F08] 遍历目录
来源：http://dali.tian-w.cn/Article/details/gtpaviopre.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jyoumei.cn/Article/details/gtnqodprdz.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.sysykeji.top/Article/details/gtbuxnitfm.html

JS:   fs.readdirSync("dir")
来源：http://dali.sysykeji.top/Article/details/gtortenemz.html

TS:   fs.readdirSync("dir")
来源：http://dali.chenzaomai.com/Article/details/gtconynkog.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yueranfly.top/Article/details/gtrftulcvi.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttquyddks.html

Ruby: Dir.children("dir")
来源：http://dali.ehwqpu.com/Article/details/gtanhgyaed.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jlsjyb.cn/Article/details/gtjnivvvmq.html

[F09] 获取文件大小
来源：http://dali.zhengqikj.top/Article/details/gtetdeoxib.html

Py:   os.path.getsize("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtmqwppdqe.html

PHP:  filesize("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gtmdhjjyjg.html

JS:   fs.statSync("a.txt").size
来源：http://dali.gzhubu.top/Article/details/gtqnczuzbj.html

TS:   fs.statSync("a.txt").size
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfwyhkyte.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hfpthk.cn/Article/details/gtmvwupqxg.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.gzhubu.top/Article/details/gtxzvpjatt.html

Ruby: File.size("a.txt")
来源：http://dali.guannengcc.top/Article/details/gttagsoaff.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hnxiangtu.top/Article/details/gtnowmugox.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhaomingkeji.xyz/Article/details/gtryawkzfh.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtejyawxqf.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gtcszhvdcf.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtotypdpyx.html

TS:   path.extname("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtgtqvhwlo.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hongshengwenyu.top/Article/details/gtzytlhwco.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtbdizrcuq.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yj202588.top/Article/details/gtarsajelo.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtfajzvzae.html

[F11] 复制与移动文件
来源：http://dali.hfpthk.cn/Article/details/gtkbeuanye.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.cqqwz.cn/Article/details/gtomigrcvo.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yueranfly.top/Article/details/gtvpknykri.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hysaishi.cn/Article/details/gtrqyfgydq.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yangfankeji.com/Article/details/gtanihrsge.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.chenlongwang.top/Article/details/gtatfkzjwe.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.chenzaomai.com/Article/details/gtnhhzqvjm.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hywenlv.cn/Article/details/gtilpmliik.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xinyue.icu/Article/details/gtpswnlhqt.html

[F12] CSV 读写
来源：http://dali.tian-w.cn/Article/details/gtnwjxsnyl.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.cucudq.cn/Article/details/gtpfaiuyac.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.fengsongda.top/Article/details/gtdrbxljzp.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.vqdsnc.cn/Article/details/gtbhnkjuor.html

TS:   // 同上
来源：http://dali.aizwys.cn/Article/details/gtqvbzmlmg.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.shzxlz.cn/Article/details/gtoihmdftj.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jinqigfzy.top/Article/details/gtthidepxe.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yangfankeji.com/Article/details/gtkmizuoce.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhongyouzk.top/Article/details/gtsinsjhwz.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtxqlmclzw.html

G. 面向对象
来源：http://dali.yj20258888.top/Article/details/gtftqiyqks.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtjtmkxfwv.html

[G01] 定义类
来源：http://dali.bjfxy.top/Article/details/gtwracvdve.html

Py:   class User: pass
来源：http://dali.sweek.top/Article/details/gtdbxalast.html

PHP:  class User {}
来源：http://dali.yueranfly.top/Article/details/gtwxakpdzc.html

JS:   class User {}
来源：http://dali.yongpay.top/Article/details/gtawrnpxbt.html

TS:   class User { name: string = ""; }
来源：http://dali.smart0.xyz/Article/details/gtoauzunom.html

Java: class User {}
来源：http://dali.yj20258888.top/Article/details/gtrajegpuf.html

Go:   type User struct { Name string }
来源：http://dali.dianchejie.cn/Article/details/gtffnmijlb.html

Ruby: class User; end
来源：http://dali.yanxiufei.cn/Article/details/gtbvpzylgr.html

C#:   class User {}
来源：http://dali.hywenlv.cn/Article/details/gtnejhuxcp.html

[G02] 构造函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqqltpryd.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zdqjudy.top/Article/details/gtlncrvdtr.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.guannengcc.top/Article/details/gtbstvvknb.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.iojbl.cn/Article/details/gtrorgrefa.html

TS:   constructor(public name: string) {}
来源：http://dali.haohaochexian.top/Article/details/gtqysmdmem.html

Java: User(String name) { this.name = name; }
来源：http://dali.hammf.cn/Article/details/gtuufcfior.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhengqikj.top/Article/details/gtpwxenhgz.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.nanxinkj.top/Article/details/gtaxunqqam.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhengqikj.top/Article/details/gtletowwpd.html

[G03] 实例属性
来源：http://dali.shuidangran.top/Article/details/gtyoqckjgx.html

Py:   self.name = "x"
来源：http://dali.nanxinkj.top/Article/details/gtacacfvlw.html

PHP:  public string $name = "x";
来源：http://dali.iojbl.cn/Article/details/gtcnxdytst.html

JS:   this.name = "x";
来源：http://dali.sysykeji.top/Article/details/gtckbftyxr.html

TS:   name: string = "x";
来源：http://dali.sysykeji.top/Article/details/gtdtzdjotv.html

Java: private String name;
来源：http://dali.dianchejie.cn/Article/details/gtfcpfetyt.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.dianchejie.cn/Article/details/gtkjtcrrka.html

Ruby: @name = "x"
来源：http://dali.zhixingplan.top/Article/details/gtwgkekagb.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhengqikj.top/Article/details/gtujgpedjr.html

[G04] 定义方法
来源：http://dali.gzhubu.top/Article/details/gtggasqtfx.html

Py:   def greet(self): return self.name
来源：http://dali.havefunace.top/Article/details/gtsgizexej.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.wangdashe.top/Article/details/gtbocikgqt.html

JS:   greet() { return this.name; }
来源：http://dali.yueranfly.top/Article/details/gtktjvxucu.html

TS:   greet(): string { return this.name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtzdrjnpeq.html

Java: String greet() { return name; }
来源：http://dali.cashguo.top/Article/details/gttvfkgmlb.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.havefunace.top/Article/details/gtvxwngone.html

Ruby: def greet; @name; end
来源：http://dali.sxryk.cn/Article/details/gttvxqbnak.html

C#:   public string Greet() => Name;
来源：http://dali.zdqjudy.top/Article/details/gtjmfwukxm.html

[G05] 继承
来源：http://dali.hongshengwenyu.top/Article/details/gtcwajjnwk.html

Py:   class Admin(User): pass
来源：http://dali.jinqigfzy.top/Article/details/gtafqgjtng.html

PHP:  class Admin extends User {}
来源：http://dali.haohaochexian.top/Article/details/gtglvzzssn.html

JS:   class Admin extends User {}
来源：http://dali.dianchejie.cn/Article/details/gtgleqdrtt.html

TS:   class Admin extends User {}
来源：http://dali.316326.xyz/Article/details/gtxpsfguxu.html

Java: class Admin extends User {}
来源：http://dali.gotoacloud.top/Article/details/gtnallhtdz.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.tianlin.xyz/Article/details/gttaswtkzq.html

Ruby: class Admin < User; end
来源：http://dali.gogol.net.cn/Article/details/gttucsrkln.html

C#:   class Admin : User {}
来源：http://dali.jiagoushi.top/Article/details/gttduqxkku.html

[G06] 重写方法
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdjklkzfx.html

Py:   def greet(self): return "admin"
来源：http://dali.jinqigufen.top/Article/details/gteaofkbxr.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.tian-w.cn/Article/details/gtelatkjho.html

JS:   greet() { return "admin"; }
来源：http://dali.jinqigufen.top/Article/details/gtynbvpvlp.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpguehnke.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yuxming.cn/Article/details/gtudwnnftw.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ehwqpu.com/Article/details/gtubylltav.html

Ruby: def greet; "admin"; end
来源：http://dali.hammf.cn/Article/details/gtnrwogqht.html

C#:   public override string Greet() => "admin";
来源：http://dali.shzxlz.cn/Article/details/gtufbbprtj.html

[G07] 调用父类方法
来源：http://dali.jyoumei.cn/Article/details/gtzkipedtc.html

Py:   super().greet()
来源：http://dali.ehwqpu.com/Article/details/gthptuabcy.html

PHP:  parent::greet();
来源：http://dali.snrcjt.cn/Article/details/gtyyxyanjr.html

JS:   super.greet();
来源：http://dali.yvedp.cn/Article/details/gtqsjkbjzf.html

TS:   super.greet();
来源：http://dali.sxryk.cn/Article/details/gtzpdlqogy.html

Java: super.greet();
来源：http://dali.jinqigufen.top/Article/details/gtsbzpvktg.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.cdnleiting.top/Article/details/gtfmxbcqcg.html

Ruby: super
来源：http://dali.smart0.xyz/Article/details/gtjrdnfqlf.html

C#:   base.Greet();
来源：http://dali.feifeiyinyue.top/Article/details/gtntbhcgqd.html

[G08] 静态方法与属性
来源：http://dali.daria6918.cn/Article/details/gtutasljfu.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.sweek.top/Article/details/gtnbfnbned.html

PHP:  public static function f() {}
来源：http://dali.smart0.xyz/Article/details/gtbtrohjht.html

JS:   static f() {}
来源：http://dali.fengsongda.top/Article/details/gtouakqyep.html

TS:   static f(): void {}
来源：http://dali.daria6918.cn/Article/details/gtzogwwlre.html

Java: static void f() {}
来源：http://dali.snrcjt.cn/Article/details/gtxpxxodiv.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhoulong.xyz/Article/details/gtmteplmpi.html

Ruby: def self.f; end
来源：http://dali.andypj.xyz/Article/details/gtqsltuzgz.html

C#:   public static void F() {}
来源：http://dali.gzhubu.top/Article/details/gtdbryrkoi.html

[G09] 接口 / 抽象类
来源：http://dali.kuanghao11.cn/Article/details/gtzjinfbda.html


<!-- 参考信息 -->