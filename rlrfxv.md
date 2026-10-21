代发 wailian999

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.wangshuangyany.cn/Article/details/gtykiolerp.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yongpay.top/Article/details/gtbsdjtgdc.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.kuanghao11.cn/Article/details/gtfdvbdpwk.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.dianchejie.cn/Article/details/gtjctefqwa.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.shangyingyoupin.top/Article/details/gtbqzeqljc.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yangfankeji.com/Article/details/gtlcddoxyx.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yj20258.top/Article/details/gtrgjmuazj.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.smart0.xyz/Article/details/gtoicbnmaf.html

[E10] 左侧补零 / 定长填充
来源：http://dali.sxryk.cn/Article/details/gtldpdxnbv.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hnqzz.top/Article/details/gtzbgehlrc.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.xuetiantiany.cn/Article/details/gtgkwaranw.html

JS:   "7".padStart(3, "0")
来源：http://dali.hnqzz.top/Article/details/gtscunzdev.html

TS:   "7".padStart(3, "0")
来源：http://dali.jyoumei.cn/Article/details/gtooxkduvq.html

Java: String.format("%03d", 7)
来源：http://dali.yj20258888.top/Article/details/gtgyvvjifk.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.ehwqpu.com/Article/details/gtycguitor.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.cheryme.top/Article/details/gtdoygvady.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yj202588.top/Article/details/gtpplgflpq.html

[E11] 反转字符串
来源：http://dali.wangdashe.top/Article/details/gthzcstfyq.html

Py:   s[::-1]
来源：http://dali.cqqwz.cn/Article/details/gtrfopqobi.html

PHP:  strrev($s);
来源：http://dali.jyoumei.cn/Article/details/gtgenykvsm.html

JS:   [...s].reverse().join("")
来源：http://dali.iojbl.cn/Article/details/gtcbwfxqdu.html

TS:   [...s].reverse().join("")
来源：http://dali.9152youxi.cn/Article/details/gtqrgyojwc.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.c1oappe.top/Article/details/gtymhlysfx.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.daria6918.cn/Article/details/gtvcskaqla.html

Ruby: s.reverse
来源：http://dali.zhengqikj.top/Article/details/gtuiafhyqo.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.dianchejie.cn/Article/details/gtxputwjxo.html

[E12] 统计某字符出现次数
来源：http://dali.vqdsnc.cn/Article/details/gttrhwrntt.html

Py:   s.count("a")
来源：http://dali.hammf.cn/Article/details/gtaedgzvmx.html

PHP:  substr_count($s, "a");
来源：http://dali.zhaomingkeji.xyz/Article/details/gttldpggeh.html

JS:   s.split("a").length - 1
来源：http://dali.shzxlz.cn/Article/details/gtsgdvfqgh.html

TS:   s.split("a").length - 1
来源：http://dali.sweek.top/Article/details/gtdazhoerl.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.fzhhl.top/Article/details/gtsqeaxpsk.html

Go:   strings.Count(s, "a")
来源：http://dali.sysykeji.top/Article/details/gtolgyrfrb.html

Ruby: s.count("a")
来源：http://dali.jqgfzy.top/Article/details/gtupaukvte.html

C#:   s.Count(c => c == 'a')
来源：http://dali.gzhubu.top/Article/details/gtiorjvvxk.html

[E13] 逐字符遍历
来源：http://dali.havefunace.top/Article/details/gtpdfjqceu.html

Py:   for ch in s: print(ch)
来源：http://dali.guowangkeji.top/Article/details/gtecxvdnyv.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.nwbrower.top/Article/details/gtjgvafvwp.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cucudq.cn/Article/details/gtuhmqocvo.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ehwqpu.com/Article/details/gtaouhesum.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.gzhubu.top/Article/details/gtmeajswlr.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jinghuilouyu.cn/Article/details/gthpmbhjtk.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.iojbl.cn/Article/details/gtavkimaxf.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.shuidangran.top/Article/details/gtpvhhzymp.html

[E14] URL 编码与 Base64
来源：http://dali.smart0.xyz/Article/details/gtdjvoqjpq.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.cdnleiting.top/Article/details/gtsaipzxqo.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.ivvv.top/Article/details/gttzswipxk.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jlsjyb.cn/Article/details/gthxjfnkit.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.gotoacloud.top/Article/details/gtklhxmxtk.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.wangdashe.top/Article/details/gtsixiidej.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcdkezwqg.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhoulong.xyz/Article/details/gtbcxhkwcx.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.nwbrower.top/Article/details/gtsemeptry.html

[E15] HTML 转义 / 反转义
来源：http://dali.9152youxi.cn/Article/details/gtmxxwpkha.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.gotoacloud.top/Article/details/gtqjuezhid.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.xinyue.icu/Article/details/gtflkrahoc.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jqgfzy.top/Article/details/gtbrjvekni.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhiwuduotai.top/Article/details/gtbuypwpxf.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yongpay.top/Article/details/gttnoqjcfq.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.daxiang520.top/Article/details/gtimcebeur.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.cashguo.top/Article/details/gtzroctbbr.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.shzxlz.cn/Article/details/gtkgkcqlxr.html

[E16] 数字千分位
来源：http://dali.ywan-chungtsiang.top/Article/details/gtohfuktez.html

Py:   f"{1234567:,}"
来源：http://dali.chenzaomai.com/Article/details/gtbszivwwa.html

PHP:  number_format(1234567);
来源：http://dali.jinqigfzy.top/Article/details/gtqswhwzua.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.sweek.top/Article/details/gtklxigyxa.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.tian-w.cn/Article/details/gtgzcxfzrt.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.andypj.xyz/Article/details/gtazymyjod.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.iojbl.cn/Article/details/gtexhebpgw.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.gzhubu.top/Article/details/gtgvwpceiz.html

C#:   1234567.ToString("N0")
来源：http://dali.jianghu66.top/Article/details/gtbtbbhgjs.html

[E17] 首字母大写
来源：http://dali.ivvv.top/Article/details/gtukwhfefv.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ppjwa.cn/Article/details/gtalfebvct.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.bjfxy.top/Article/details/gtsvhfiizx.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hnxiangtu.top/Article/details/gtzumuuugc.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sufxvd.cn/Article/details/gtjioeptui.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yj20258888.top/Article/details/gtbqhvmvln.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jqgufenzy.top/Article/details/gtjdvfgrfq.html

Ruby: s.capitalize
来源：http://dali.sufxvd.cn/Article/details/gtdcsrfbib.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jinqigufen.top/Article/details/gtmrzcssqs.html

[E18] 模板占位符替换
来源：http://dali.hywenlv.cn/Article/details/gtjphxxhzd.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.xuetiantiany.cn/Article/details/gteeqftbaz.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jlsjyb.cn/Article/details/gtqlybmhqh.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbwapcrkr.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.nanxuanxn.top/Article/details/gtfyroitxs.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.guannengcc.top/Article/details/gtcckdibxm.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.ydzc1.top/Article/details/gteqlinyka.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.kuanghao11.cn/Article/details/gtoxoisiqz.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.sufxvd.cn/Article/details/gtjuqlpsus.html

[E19] 多行文本按行拆分
来源：http://dali.hnqzz.top/Article/details/gtizvljxlh.html

Py:   s.splitlines()
来源：http://dali.redwolf501.top/Article/details/gtqohmcsfd.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.sweek.top/Article/details/gthehupxkb.html

JS:   s.split(/\r?\n/)
来源：http://dali.shuidangran.top/Article/details/gtsiootszx.html

TS:   s.split(/\r?\n/)
来源：http://dali.cdnleiting.top/Article/details/gtqmwymprl.html

Java: s.lines().toList()
来源：http://dali.xuetiantiany.cn/Article/details/gtjvgyrpnu.html

Go:   strings.Split(s, "\n")
来源：http://dali.yueranfly.top/Article/details/gtaigghljp.html

Ruby: s.lines
来源：http://dali.cashguo.top/Article/details/gtvvecozsw.html

C#:   s.Split('\n')
来源：http://dali.redwolf501.top/Article/details/gtfghovtbz.html

[E20] 判断字符串是否为空
来源：http://dali.shangyingyoupin.top/Article/details/gthhimzwuo.html

Py:   if not s:
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaogkwgmg.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yj202588.top/Article/details/gtbuinppua.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hysaishi.cn/Article/details/gtpmosrbpu.html

TS:   if (s === "") {}
来源：http://dali.ehwqpu.com/Article/details/gtpqmzwdpx.html

Java: if (s.isEmpty()) {}
来源：http://dali.guowangkeji.top/Article/details/gtjbjvobid.html

Go:   if s == "" {}
来源：http://dali.sxryk.cn/Article/details/gtbaxyzdrc.html

Ruby: if s.empty?
来源：http://dali.hammf.cn/Article/details/gtvbtmktdi.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.xuanzx.com/Article/details/gtpwgkfiwb.html

[E21] 超长截断加省略号
来源：http://dali.gotoacloud.top/Article/details/gtgssbxmjh.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.chenlongwang.top/Article/details/gtdqiaittf.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.andypj.xyz/Article/details/gtydcgftlp.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yj20258888.top/Article/details/gtvjeffonq.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shuidangran.top/Article/details/gtmagelygj.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.shanyushiyangkeji.top/Article/details/gtibuwhilu.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.iojbl.cn/Article/details/gtprlbsini.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yongpay.top/Article/details/gtoedkeoca.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yonumen.top/Article/details/gtewuvnxmz.html

[E22] 字节长度与字符长度
来源：http://dali.gzhubu.top/Article/details/gtfmxwuiwa.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.c1oappe.top/Article/details/gtzppskkoe.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cdnleiting.top/Article/details/gtrxieuyzt.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinqigfzy.top/Article/details/gtvpjaqqmc.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.aibaodan.cn/Article/details/gtjkmlowqo.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jyoumei.cn/Article/details/gtrotdwuec.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.c1oappe.top/Article/details/gtordnpvre.html

Ruby: s.bytesize;  s.length
来源：http://dali.hywenlv.cn/Article/details/gtxyqigdbl.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.xinyue.icu/Article/details/gtqebndjmk.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtorhnwmcf.html

F. 文件与目录
来源：http://dali.316326.xyz/Article/details/gtnvmdqnfm.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtquuvcvik.html

[F01] 读取整个文件
来源：http://dali.fzhhl.top/Article/details/gtqduzkcti.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hnxiangtu.top/Article/details/gtjxmztgta.html

PHP:  file_get_contents("a.txt");
来源：http://dali.mhx1999.top/Article/details/gtwfvdqnvf.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.shzxlz.cn/Article/details/gtgrtwpuqb.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.nwbrower.top/Article/details/gtlyokwlfd.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.daxiang520.top/Article/details/gtrucaygsk.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yvedp.cn/Article/details/gtyvxcotqs.html

Ruby: File.read("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtjlmpidzk.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gtcucdplku.html

[F02] 逐行读取文件
来源：http://dali.redwolf501.top/Article/details/gtwiptxkwd.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hnqzz.top/Article/details/gtvgsksaxm.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.iojbl.cn/Article/details/gtwjotiwqr.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.birdmap.top/Article/details/gtscwvlgxv.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjvmsahya.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.c1oappe.top/Article/details/gtzchzkfsp.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ehwqpu.com/Article/details/gttmuvkwfl.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yvedp.cn/Article/details/gteelsuhme.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.guowangkeji.top/Article/details/gtkgwbxuhi.html

[F03] 写入文件（覆盖）
来源：http://dali.zhixingplan.top/Article/details/gtwhfmzzaw.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.gotoacloud.top/Article/details/gthgzkfhvl.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.0kj1m.cn/Article/details/gtldoqvoti.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xziqi.cn/Article/details/gtvvqlzort.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sufxvd.cn/Article/details/gtacyamteg.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jiagoushi.top/Article/details/gtmvaywond.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jinqigfzy.top/Article/details/gtuixclodx.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jqgufenzy.top/Article/details/gtuoovvhkl.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jqgufenzy.top/Article/details/gtxzemkyxh.html

[F04] 追加写入文件
来源：http://dali.redwolf501.top/Article/details/gtfoufbiis.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.xinyue.icu/Article/details/gtekbhdlav.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.quarkkingdee.top/Article/details/gtztwykoqw.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xuanzx.com/Article/details/gtlxdmzsqj.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqlsjashj.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.cqqwz.cn/Article/details/gtwrrujwuk.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hnqzz.top/Article/details/gttqttjvnr.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jinghuilouyu.cn/Article/details/gtimwqpoar.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yuxming.cn/Article/details/gttmbhbauj.html

[F05] 判断文件或目录是否存在
来源：http://dali.jianghu66.top/Article/details/gtfnzsfgeh.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yj20258.top/Article/details/gtnukwmgdz.html

PHP:  file_exists("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtfnowtogp.html

JS:   fs.existsSync("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtyqbmfdif.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtgsxnriat.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.wangdashe.top/Article/details/gtytsnseux.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yuanzhike.top/Article/details/gttrffdlhw.html

Ruby: File.exist?("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtazfoxzur.html

C#:   File.Exists("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtjkrstjqt.html

[F06] 删除文件
来源：http://dali.zhiwuduotai.top/Article/details/gtnaukowad.html

Py:   os.remove("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtskgdpull.html

PHP:  unlink("a.txt");
来源：http://dali.redwolf501.top/Article/details/gtcfjvwffe.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgwaxmjgr.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtusjuojdt.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.ydzc1.top/Article/details/gtkfhaeexv.html

Go:   os.Remove("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtyrbfmkds.html

Ruby: File.delete("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtazqtvytw.html

C#:   File.Delete("a.txt");
来源：http://dali.sysykeji.top/Article/details/gtivwwappo.html

[F07] 创建目录（含多级）
来源：http://dali.dashuyun.cn/Article/details/gttojldwyo.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xuetiantiany.cn/Article/details/gtlctjzoys.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.aizwys.cn/Article/details/gtgfdataus.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jqgfzy.top/Article/details/gtqhvnipiz.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.iojbl.cn/Article/details/gtmgunrsps.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgymszfim.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.nwbrower.top/Article/details/gtdniqlxtm.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yonumen.top/Article/details/gtplzzxhvf.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.pycfn.com/Article/details/gthxqiwnrm.html

[F08] 遍历目录
来源：http://dali.bjfxy.top/Article/details/gtsymguyfa.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.dianchejie.cn/Article/details/gtzubisogn.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhixingplan.top/Article/details/gtatfdccez.html

JS:   fs.readdirSync("dir")
来源：http://dali.xylfe.cn/Article/details/gtggatzppz.html

TS:   fs.readdirSync("dir")
来源：http://dali.hywenlv.cn/Article/details/gtcbmrnrbo.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xziqi.cn/Article/details/gtbjkvknup.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.dianchejie.cn/Article/details/gtzcapxhjf.html

Ruby: Dir.children("dir")
来源：http://dali.zdqjudy.top/Article/details/gtgztthszj.html

C#:   Directory.GetFiles("dir")
来源：http://dali.nanxinkj.top/Article/details/gtzpzupzhb.html

[F09] 获取文件大小
来源：http://dali.cqqwz.cn/Article/details/gtfrodydib.html

Py:   os.path.getsize("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtbvhxaemz.html

PHP:  filesize("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlgfvlnta.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xuetiantiany.cn/Article/details/gtrffkhing.html

TS:   fs.statSync("a.txt").size
来源：http://dali.xylfe.cn/Article/details/gtfandnfqu.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.dashuyun.cn/Article/details/gtgryfhlob.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.tianlin.xyz/Article/details/gtwwmzxamj.html

Ruby: File.size("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtspydbopc.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.sxryk.cn/Article/details/gtlagiaopi.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jianghu66.top/Article/details/gtrvmxifpv.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.sweek.top/Article/details/gthqjvlmin.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtilbiqdms.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtnvlhawsk.html

TS:   path.extname("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtnculeskz.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jinghuilouyu.cn/Article/details/gtahgvfwry.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.sweek.top/Article/details/gtlflzppxv.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yueranfly.top/Article/details/gtmpvfsdjk.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtaazumyad.html

[F11] 复制与移动文件
来源：http://dali.jianghu66.top/Article/details/gtphvqpmwb.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yonumen.top/Article/details/gtjkmiypiq.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.gzhubu.top/Article/details/gtrvlwnqoi.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.birdmap.top/Article/details/gtleulyobr.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.snrcjt.cn/Article/details/gtqdzxwaqy.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.bjfxy.top/Article/details/gtrarjwczc.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.sxryk.cn/Article/details/gtvswzenuv.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.andypj.xyz/Article/details/gtvvyelkvo.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hammf.cn/Article/details/gtsxysnkco.html

[F12] CSV 读写
来源：http://dali.jianghu66.top/Article/details/gtjfiekyrr.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.birdmap.top/Article/details/gtamvrnivy.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.shanyushiyangtech.top/Article/details/gtxnvvnybf.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.sysykeji.top/Article/details/gtonwbbpal.html

TS:   // 同上
来源：http://dali.sweek.top/Article/details/gtntesaqyx.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xuetiantiany.cn/Article/details/gtjxwurytw.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.nanxuanxn.top/Article/details/gtzqlbahng.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.cdnleiting.top/Article/details/gtymuridws.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvvjeqrdt.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtdydkxjzt.html

G. 面向对象
来源：http://dali.sufxvd.cn/Article/details/gtjoxcvfey.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtrsvbawdf.html

[G01] 定义类
来源：http://dali.quarkkingdee.top/Article/details/gtifoxbdar.html

Py:   class User: pass
来源：http://dali.aibaodan.cn/Article/details/gtgvbmhzlu.html

PHP:  class User {}
来源：http://dali.jyoumei.cn/Article/details/gtsvfccbxd.html

JS:   class User {}
来源：http://dali.cqqwz.cn/Article/details/gthoyqlpkz.html

TS:   class User { name: string = ""; }
来源：http://dali.yuxming.cn/Article/details/gtvpratrux.html

Java: class User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlbwbnfao.html

Go:   type User struct { Name string }
来源：http://dali.smart0.xyz/Article/details/gttvvercsp.html

Ruby: class User; end
来源：http://dali.ehwqpu.com/Article/details/gtifzgxret.html

C#:   class User {}
来源：http://dali.yuxming.cn/Article/details/gtiylrcaup.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gtjqilgrqk.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.tanke756.top/Article/details/gthyngeuff.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.redwolf501.top/Article/details/gtgytprsxh.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.haohaochexian.top/Article/details/gttysoazlr.html

TS:   constructor(public name: string) {}
来源：http://dali.xylfe.cn/Article/details/gtweqbfzui.html

Java: User(String name) { this.name = name; }
来源：http://dali.hnxiangtu.top/Article/details/gtcmdzwfid.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhixingplan.top/Article/details/gtniyyxfjn.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.316326.xyz/Article/details/gtnqdzmcsr.html

C#:   public User(string name) { Name = name; }
来源：http://dali.chenzaomai.com/Article/details/gtnhsslkgt.html

[G03] 实例属性
来源：http://dali.gogol.net.cn/Article/details/gtirmluvfw.html

Py:   self.name = "x"
来源：http://dali.yj202588.top/Article/details/gtxyhrzlwz.html

PHP:  public string $name = "x";
来源：http://dali.nwbrower.top/Article/details/gtdrzuqafl.html

JS:   this.name = "x";
来源：http://dali.tian-w.cn/Article/details/gtvgxntirm.html

TS:   name: string = "x";
来源：http://dali.cqqwz.cn/Article/details/gtsapzmswj.html

Java: private String name;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtixpoyzis.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.redwolf501.top/Article/details/gtezvohpyf.html

Ruby: @name = "x"
来源：http://dali.guowangkeji.top/Article/details/gttcubvwkf.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hammf.cn/Article/details/gtmmxogekw.html

[G04] 定义方法
来源：http://dali.kuanghao11.cn/Article/details/gtlbrdhmmk.html

Py:   def greet(self): return self.name
来源：http://dali.sufxvd.cn/Article/details/gtzhmflbby.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.sxryk.cn/Article/details/gtcfvhmtak.html

JS:   greet() { return this.name; }
来源：http://dali.yangfankeji.com/Article/details/gtgecsbgzu.html

TS:   greet(): string { return this.name; }
来源：http://dali.vqdsnc.cn/Article/details/gtdfdkkmhc.html

Java: String greet() { return name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtjemxtbsa.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.wangshuangyany.cn/Article/details/gtkmlfihql.html

Ruby: def greet; @name; end
来源：http://dali.guowangkeji.top/Article/details/gtxdudfion.html

C#:   public string Greet() => Name;
来源：http://dali.iojbl.cn/Article/details/gtszwihrqb.html

[G05] 继承
来源：http://dali.sweek.top/Article/details/gtjmtcmmfg.html

Py:   class Admin(User): pass
来源：http://dali.sufxvd.cn/Article/details/gtbtdenofl.html

PHP:  class Admin extends User {}
来源：http://dali.wangdashe.top/Article/details/gtwdjoxygb.html

JS:   class Admin extends User {}
来源：http://dali.xuanzx.com/Article/details/gtwnartgos.html

TS:   class Admin extends User {}
来源：http://dali.jqgfzy.top/Article/details/gthviteusn.html

Java: class Admin extends User {}
来源：http://dali.xinyue.icu/Article/details/gtzotucins.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yuxming.cn/Article/details/gttwhegwed.html

Ruby: class Admin < User; end
来源：http://dali.c1oappe.top/Article/details/gtnjszwuvb.html

C#:   class Admin : User {}
来源：http://dali.sweek.top/Article/details/gtfignsdlj.html

[G06] 重写方法
来源：http://dali.zhiwuduotai.top/Article/details/gtbwmxibkk.html

Py:   def greet(self): return "admin"
来源：http://dali.guannengcc.top/Article/details/gtdpobursg.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.tian-w.cn/Article/details/gtifkduvax.html

JS:   greet() { return "admin"; }
来源：http://dali.hywenlv.cn/Article/details/gtutppjntq.html

TS:   greet(): string { return "admin"; }
来源：http://dali.tianlin.xyz/Article/details/gtuszfsqey.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.birdmap.top/Article/details/gtavtnqudh.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.vqdsnc.cn/Article/details/gtswgjpasy.html

Ruby: def greet; "admin"; end
来源：http://dali.guowangkeji.top/Article/details/gtzphheqvd.html

C#:   public override string Greet() => "admin";
来源：http://dali.shuidangran.top/Article/details/gtsuipuxxv.html

[G07] 调用父类方法
来源：http://dali.gogol.net.cn/Article/details/gtkynezhff.html

Py:   super().greet()
来源：http://dali.gogol.net.cn/Article/details/gtvaqzbtvq.html

PHP:  parent::greet();
来源：http://dali.hysaishi.cn/Article/details/gtnjccpemc.html

JS:   super.greet();
来源：http://dali.tian-w.cn/Article/details/gtgburldmq.html

TS:   super.greet();
来源：http://dali.yonumen.top/Article/details/gtmyhqtqnx.html

Java: super.greet();
来源：http://dali.pycfn.com/Article/details/gtosmudvvx.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.pycfn.com/Article/details/gtjecfnumz.html


<!-- 参考信息 -->