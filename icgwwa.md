代发 wailian999

Java: s.replaceAll("\\s+", "")
来源：http://dali.sweek.top/Article/details/gttlphjlpv.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.guannengcc.top/Article/details/gtujjqeawh.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.0kj1m.cn/Article/details/gtngfhohbx.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.nanxuanxn.top/Article/details/gtkjaytrkl.html

[E10] 左侧补零 / 定长填充
来源：http://dali.shanyushiyangkeji.top/Article/details/gtizgranpt.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jinqigufen.top/Article/details/gttsuarswb.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.aizwys.cn/Article/details/gtfqraairh.html

JS:   "7".padStart(3, "0")
来源：http://dali.smart0.xyz/Article/details/gtyqaeifxr.html

TS:   "7".padStart(3, "0")
来源：http://dali.birdmap.top/Article/details/gtptfypnme.html

Java: String.format("%03d", 7)
来源：http://dali.c1oappe.top/Article/details/gtohwclqfa.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.nwbrower.top/Article/details/gtyqshxqbl.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hywenlv.cn/Article/details/gtkkevwvtw.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.316326.xyz/Article/details/gtfqvsddcd.html

[E11] 反转字符串
来源：http://dali.ybcxt.top/Article/details/gtkfmigepw.html

Py:   s[::-1]
来源：http://dali.yangfankeji.com/Article/details/gtejhkoyyb.html

PHP:  strrev($s);
来源：http://dali.gogol.net.cn/Article/details/gtcxgzewyp.html

JS:   [...s].reverse().join("")
来源：http://dali.yueranfly.top/Article/details/gtzwnswjxj.html

TS:   [...s].reverse().join("")
来源：http://dali.hywenlv.cn/Article/details/gtmxhxyfjp.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jinqigufen.top/Article/details/gtqwkejdab.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.andypj.xyz/Article/details/gtqdxyaqty.html

Ruby: s.reverse
来源：http://dali.tanke756.top/Article/details/gtadzgrekr.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.svipenyu.cn/Article/details/gthqhlbusc.html

[E12] 统计某字符出现次数
来源：http://dali.snrcjt.cn/Article/details/gtzjesjcuq.html

Py:   s.count("a")
来源：http://dali.zhixingplan.top/Article/details/gteweskfsc.html

PHP:  substr_count($s, "a");
来源：http://dali.sysykeji.top/Article/details/gtjvdkmoqd.html

JS:   s.split("a").length - 1
来源：http://dali.nanxuanxn.top/Article/details/gtdivovejg.html

TS:   s.split("a").length - 1
来源：http://dali.cheryme.top/Article/details/gtofeqwjvv.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yuanzhike.top/Article/details/gtjzcwulvg.html

Go:   strings.Count(s, "a")
来源：http://dali.yonumen.top/Article/details/gtkatxxpeb.html

Ruby: s.count("a")
来源：http://dali.bjfxy.top/Article/details/gtqodkywyq.html

C#:   s.Count(c => c == 'a')
来源：http://dali.fzhhl.top/Article/details/gtotdkmkks.html

[E13] 逐字符遍历
来源：http://dali.shuidangran.top/Article/details/gtzwaatnjx.html

Py:   for ch in s: print(ch)
来源：http://dali.cheryme.top/Article/details/gtrwqunlia.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.feifeiyinyue.top/Article/details/gtjrzexpon.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.bjfxy.top/Article/details/gtonokmufn.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.0kj1m.cn/Article/details/gtqrcnucep.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.nwbrower.top/Article/details/gtwrmfjodr.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.shzxlz.cn/Article/details/gtaemdilwp.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.shuidangran.top/Article/details/gtgsseghvg.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.ydzc1.top/Article/details/gtnzzavzdj.html

[E14] URL 编码与 Base64
来源：http://dali.sufxvd.cn/Article/details/gtakecadqf.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.guowangkeji.top/Article/details/gtounsrzvn.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.sxryk.cn/Article/details/gtgcfnifkw.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.guannengcc.top/Article/details/gtuqranqkb.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.sysykeji.top/Article/details/gtaawwyncq.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.dianchejie.cn/Article/details/gtwjmhdjjl.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.nanxuanxn.top/Article/details/gtgxqpgrdl.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jqgufenzy.top/Article/details/gtimrximde.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.ivvv.top/Article/details/gtdxfabpon.html

[E15] HTML 转义 / 反转义
来源：http://dali.yangfankeji.com/Article/details/gtvoduwxkm.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.aizwys.cn/Article/details/gtrbeszsva.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.sweek.top/Article/details/gtixomowmt.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.meibo888.top/Article/details/gtnrlxwhkw.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.cashguo.top/Article/details/gtivgjlytr.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.9152youxi.cn/Article/details/gtyvkenmgk.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yangfankeji.com/Article/details/gtmtwhhwgu.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.shuidangran.top/Article/details/gtdyipnkvo.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.gzhubu.top/Article/details/gtcttnuavl.html

[E16] 数字千分位
来源：http://dali.shangyingyoupin.top/Article/details/gtxaxlixun.html

Py:   f"{1234567:,}"
来源：http://dali.jinqigufen.top/Article/details/gtxemqqqzf.html

PHP:  number_format(1234567);
来源：http://dali.ehwqpu.com/Article/details/gtxcasfhns.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.andypj.xyz/Article/details/gtccvpnyph.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhiwuduotai.top/Article/details/gtbxhncbly.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.tanke756.top/Article/details/gtukjnxfkw.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.tianlin.xyz/Article/details/gtbrlykniy.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.cashguo.top/Article/details/gtwelqbail.html

C#:   1234567.ToString("N0")
来源：http://dali.smart0.xyz/Article/details/gtkcbzrwrs.html

[E17] 首字母大写
来源：http://dali.shangyingyoupin.top/Article/details/gtywmnaodw.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.haohaochexian.top/Article/details/gteehgnucf.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.birdmap.top/Article/details/gtbodarvxu.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.aibaodan.cn/Article/details/gtgloflicc.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zycfv.cn/Article/details/gtqdwblquh.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.hywenlv.cn/Article/details/gtgldjcgwu.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.daxiang520.top/Article/details/gtalisiqco.html

Ruby: s.capitalize
来源：http://dali.jinqigufen.top/Article/details/gtcmzegsfs.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.pengpengdd.cyou/Article/details/gtnumyexhh.html

[E18] 模板占位符替换
来源：http://dali.guannengcc.top/Article/details/gtfyhtlhgz.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ybcxt.top/Article/details/gthdmdzlzi.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.cheryme.top/Article/details/gtwltkpfme.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yuxming.cn/Article/details/gtasehkdgm.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.smart0.xyz/Article/details/gtkvckmrvb.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.bjfxy.top/Article/details/gtrxgbepny.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.cashguo.top/Article/details/gtnquegjcu.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.aizwys.cn/Article/details/gtftjokdnn.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.hammf.cn/Article/details/gtyfpadeet.html

[E19] 多行文本按行拆分
来源：http://dali.jiagoushi.top/Article/details/gtiejmcjra.html

Py:   s.splitlines()
来源：http://dali.zhengqikj.top/Article/details/gtrquzecna.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhixingplan.top/Article/details/gtkdxtxsir.html

JS:   s.split(/\r?\n/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtizauoxep.html

TS:   s.split(/\r?\n/)
来源：http://dali.daxiang520.top/Article/details/gtqkugehtr.html

Java: s.lines().toList()
来源：http://dali.ppjwa.cn/Article/details/gtihoiltbm.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhoulong.xyz/Article/details/gtcwrxaswc.html

Ruby: s.lines
来源：http://dali.nwbrower.top/Article/details/gtuibodhmd.html

C#:   s.Split('\n')
来源：http://dali.yj20258.top/Article/details/gtllwnwvlh.html

[E20] 判断字符串是否为空
来源：http://dali.aibaodan.cn/Article/details/gtsavuxswg.html

Py:   if not s:
来源：http://dali.zhixingplan.top/Article/details/gtxwsiheni.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.ppjwa.cn/Article/details/gtijjybodj.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yj202588.top/Article/details/gtnybuusat.html

TS:   if (s === "") {}
来源：http://dali.ivvv.top/Article/details/gtvivmbyoy.html

Java: if (s.isEmpty()) {}
来源：http://dali.guannengcc.top/Article/details/gttstecung.html

Go:   if s == "" {}
来源：http://dali.jiagoushi.top/Article/details/gtetczwrot.html

Ruby: if s.empty?
来源：http://dali.316326.xyz/Article/details/gtgavxlhyn.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.sufxvd.cn/Article/details/gtphpgftap.html

[E21] 超长截断加省略号
来源：http://dali.nanxuanxn.top/Article/details/gtdoxthfwt.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.pycfn.com/Article/details/gtxxkuqgfs.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.316326.xyz/Article/details/gtstcyjbhn.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.aizwys.cn/Article/details/gteedgpbyl.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ybcxt.top/Article/details/gthgplzdxd.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yuxming.cn/Article/details/gtsjwtfwnr.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jlsjyb.cn/Article/details/gtqruaofin.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.wangdashe.top/Article/details/gtvwbslhys.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jiagoushi.top/Article/details/gtzzrqxtwf.html

[E22] 字节长度与字符长度
来源：http://dali.kuanghao11.cn/Article/details/gtnjphblza.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.nanxinkj.top/Article/details/gtbxjezqpv.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.nanxinkj.top/Article/details/gtvcfjsfty.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xinyue.icu/Article/details/gtxewionff.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hnqzz.top/Article/details/gtvuuemloj.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xziqi.cn/Article/details/gtejmkoblx.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.xuetiantiany.cn/Article/details/gtmudpufza.html

Ruby: s.bytesize;  s.length
来源：http://dali.hammf.cn/Article/details/gtckzhvivi.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.shangyingyoupin.top/Article/details/gtiiclmjww.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtvrznscrm.html

F. 文件与目录
来源：http://dali.bjfxy.top/Article/details/gthnjiwrnd.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtsxbhsmtv.html

[F01] 读取整个文件
来源：http://dali.cqqwz.cn/Article/details/gtgcoasxmj.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.shuidangran.top/Article/details/gtygpsmsow.html

PHP:  file_get_contents("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gtcsvefsgy.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hammf.cn/Article/details/gtmzxxzpux.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.shuidangran.top/Article/details/gtwzizncnx.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hnxiangtu.top/Article/details/gtqbdgdnxj.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.birdmap.top/Article/details/gtkrvugykl.html

Ruby: File.read("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtjtjkmsnt.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yongpay.top/Article/details/gttmoeiuyv.html

[F02] 逐行读取文件
来源：http://dali.gaohongyu789.top/Article/details/gticzddved.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yuanzhike.top/Article/details/gteoqaamfm.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hongshengwenyu.top/Article/details/gtkgqujkxj.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yangfankeji.com/Article/details/gthoovlise.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.bjfxy.top/Article/details/gtqqmawlfa.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hysaishi.cn/Article/details/gtueosclis.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.xuanzx.com/Article/details/gtcvsldtyg.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.kuanghao11.cn/Article/details/gtxpmmvbtq.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtmizkhsos.html

[F03] 写入文件（覆盖）
来源：http://dali.vqdsnc.cn/Article/details/gtuekfdaui.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.svipenyu.cn/Article/details/gtgypblcdn.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.svipenyu.cn/Article/details/gtnkaxypps.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ybcxt.top/Article/details/gtxrwpgzck.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.daria6918.cn/Article/details/gtirxrlydj.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.shanyushiyangkeji.top/Article/details/gthyqqbaok.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yj202588.top/Article/details/gtcnrtagkb.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.bjfxy.top/Article/details/gtatsiurlk.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ydzc1.top/Article/details/gtxqjhuqad.html

[F04] 追加写入文件
来源：http://dali.jqgfzy.top/Article/details/gtsncdqpjf.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.wangshuangyany.cn/Article/details/gtbabjjthr.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xuetiantiany.cn/Article/details/gtnkwoyquz.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jiagoushi.top/Article/details/gtopdjltbh.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cqqwz.cn/Article/details/gtmlzqvltc.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.chenjidiqi.icu/Article/details/gtxjwnaiiz.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.gotoacloud.top/Article/details/gttviweyrw.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhixingplan.top/Article/details/gtldpfqdau.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jiagoushi.top/Article/details/gtwuiltxgc.html

[F05] 判断文件或目录是否存在
来源：http://dali.shangyingyoupin.top/Article/details/gttjvqppob.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.xylfe.cn/Article/details/gtluxzsmfg.html

PHP:  file_exists("a.txt");
来源：http://dali.pycfn.com/Article/details/gtdhbefgcf.html

JS:   fs.existsSync("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtlghgfymb.html

TS:   fs.existsSync("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtixcnzqgs.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jianghu66.top/Article/details/gtyxkdjhaj.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.cqqwz.cn/Article/details/gthbnwltmf.html

Ruby: File.exist?("a.txt")
来源：http://dali.havefunace.top/Article/details/gtjxxxxjyd.html

C#:   File.Exists("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gteufmhjnc.html

[F06] 删除文件
来源：http://dali.cheryme.top/Article/details/gtfvckiusi.html

Py:   os.remove("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtxzwqxkec.html

PHP:  unlink("a.txt");
来源：http://dali.meibo888.top/Article/details/gtjgyljtdz.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtxzbyprec.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtplcqqkfx.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.wangdashe.top/Article/details/gtvorwpewa.html

Go:   os.Remove("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtwerdbjbc.html

Ruby: File.delete("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtruhusgua.html

C#:   File.Delete("a.txt");
来源：http://dali.cucudq.cn/Article/details/gtjrifsbbp.html

[F07] 创建目录（含多级）
来源：http://dali.cqqwz.cn/Article/details/gtoxigkcqo.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhongyouzk.top/Article/details/gtenzmcsqy.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.kuanghao11.cn/Article/details/gtkwnrdwzg.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shuidangran.top/Article/details/gtvlvaugre.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhengqikj.top/Article/details/gtpmlpijvr.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.iojbl.cn/Article/details/gtarpouela.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gtykjutxwy.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jianghu66.top/Article/details/gtxuideneb.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhongyouzk.top/Article/details/gtwtyxhgyi.html

[F08] 遍历目录
来源：http://dali.gzhubu.top/Article/details/gttjzlivic.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.fzhhl.top/Article/details/gtfnejuvec.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.gogol.net.cn/Article/details/gtzupdsrtu.html

JS:   fs.readdirSync("dir")
来源：http://dali.chenlongwang.top/Article/details/gtqmbmimyd.html

TS:   fs.readdirSync("dir")
来源：http://dali.hfpthk.cn/Article/details/gtvjhnahoq.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hywenlv.cn/Article/details/gtzpunlbam.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.cashguo.top/Article/details/gtcjbrunij.html

Ruby: Dir.children("dir")
来源：http://dali.ivvv.top/Article/details/gtjobweowd.html

C#:   Directory.GetFiles("dir")
来源：http://dali.9152youxi.cn/Article/details/gtgvngwwnd.html

[F09] 获取文件大小
来源：http://dali.xuanzx.com/Article/details/gtscrapunc.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtvptpwyga.html

PHP:  filesize("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gtcogrrvdb.html

JS:   fs.statSync("a.txt").size
来源：http://dali.nanxinkj.top/Article/details/gthhfjyeba.html

TS:   fs.statSync("a.txt").size
来源：http://dali.cucudq.cn/Article/details/gtwrleqqox.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.ivvv.top/Article/details/gtoyqvbdop.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtajvaorzx.html

Ruby: File.size("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtubjcnisv.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.sxryk.cn/Article/details/gtavijndxb.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.kuanghao11.cn/Article/details/gtexmlprjc.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.daria6918.cn/Article/details/gtgvchjrrx.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtadruksej.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.guannengcc.top/Article/details/gtmpvzbvqa.html

TS:   path.extname("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtswcipqfx.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.meibo888.top/Article/details/gtkziadjmf.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlslmeckh.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.cheryme.top/Article/details/gttmsllfvp.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xziqi.cn/Article/details/gtdzuabrko.html

[F11] 复制与移动文件
来源：http://dali.feifeiyinyue.top/Article/details/gtgqyowbhs.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.wangdashe.top/Article/details/gtwywbrnmc.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtuuuqcfif.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yongpay.top/Article/details/gtgfxtyorx.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.0kj1m.cn/Article/details/gtewwcejtt.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.sufxvd.cn/Article/details/gtoaqdmurn.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.shanyushiyangtech.top/Article/details/gtnluqgfwb.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtduyrvruw.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hnxiangtu.top/Article/details/gtfcysauim.html

[F12] CSV 读写
来源：http://dali.dianchejie.cn/Article/details/gtscggwwyg.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.gzhubu.top/Article/details/gtokcsmeso.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yangfankeji.com/Article/details/gtqeqdilwc.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jlsjyb.cn/Article/details/gtktcsfdvi.html

TS:   // 同上
来源：http://dali.tanke756.top/Article/details/gtzfxicogb.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xinyue.icu/Article/details/gtatedidkd.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zycfv.cn/Article/details/gtfvedmwno.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xziqi.cn/Article/details/gtpsuabjnf.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhixingplan.top/Article/details/gtukvilopy.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtaogdsqyd.html

G. 面向对象
来源：http://dali.xuetiantiany.cn/Article/details/gtuxnasobb.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtadshxogi.html

[G01] 定义类
来源：http://dali.bjfxy.top/Article/details/gtsetglrdi.html

Py:   class User: pass
来源：http://dali.fengsongda.top/Article/details/gtgnezhjhn.html

PHP:  class User {}
来源：http://dali.sxryk.cn/Article/details/gtujgbjxpj.html

JS:   class User {}
来源：http://dali.tanke756.top/Article/details/gtfsgecymg.html

TS:   class User { name: string = ""; }
来源：http://dali.yj20258.top/Article/details/gttwvofwya.html

Java: class User {}
来源：http://dali.zhoulong.xyz/Article/details/gtvuhmrtwd.html

Go:   type User struct { Name string }
来源：http://dali.yvedp.cn/Article/details/gtfrgyircb.html

Ruby: class User; end
来源：http://dali.feifeiyinyue.top/Article/details/gtxujhxlyh.html

C#:   class User {}
来源：http://dali.nanxuanxn.top/Article/details/gtsyssebfz.html

[G02] 构造函数
来源：http://dali.tian-w.cn/Article/details/gtvypjifgx.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.ivvv.top/Article/details/gtbcjpfvnl.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.316326.xyz/Article/details/gtatsfgyrd.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.gzhubu.top/Article/details/gtybwesbrn.html

TS:   constructor(public name: string) {}
来源：http://dali.zdqjudy.top/Article/details/gtwchzfubj.html

Java: User(String name) { this.name = name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtbcunfgox.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.sxryk.cn/Article/details/gtgipcwckk.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvjypegvv.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zycfv.cn/Article/details/gtpudntrvr.html

[G03] 实例属性
来源：http://dali.nanxuanxn.top/Article/details/gtdsqbgwhm.html

Py:   self.name = "x"
来源：http://dali.shanyushiyangtech.top/Article/details/gtcorljfnx.html

PHP:  public string $name = "x";
来源：http://dali.zhixingplan.top/Article/details/gtwvipkgjh.html

JS:   this.name = "x";
来源：http://dali.gzhubu.top/Article/details/gtejszhein.html

TS:   name: string = "x";
来源：http://dali.zhongyouzk.top/Article/details/gtzspsvjuf.html

Java: private String name;
来源：http://dali.xuetiantiany.cn/Article/details/gtrqqzdthd.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.guannengcc.top/Article/details/gtqjogkqgo.html

Ruby: @name = "x"
来源：http://dali.dashuyun.cn/Article/details/gtyljzgjcb.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjrdeppsn.html

[G04] 定义方法
来源：http://dali.yueranfly.top/Article/details/gteltcpmjm.html

Py:   def greet(self): return self.name
来源：http://dali.feifeiyinyue.top/Article/details/gtczuuetzq.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.redwolf501.top/Article/details/gtqxfvoudy.html

JS:   greet() { return this.name; }
来源：http://dali.hnxiangtu.top/Article/details/gtrerqhmzy.html

TS:   greet(): string { return this.name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtksuhaglx.html

Java: String greet() { return name; }
来源：http://dali.iojbl.cn/Article/details/gtoqxlrtxm.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hammf.cn/Article/details/gtwgxqotci.html

Ruby: def greet; @name; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwfsvxrms.html

C#:   public string Greet() => Name;
来源：http://dali.jianghu66.top/Article/details/gtcqrtkvdl.html

[G05] 继承
来源：http://dali.zhongyouzk.top/Article/details/gtdbtzpkpz.html

Py:   class Admin(User): pass
来源：http://dali.hnqzz.top/Article/details/gtxcmrnput.html

PHP:  class Admin extends User {}
来源：http://dali.chenjidiqi.icu/Article/details/gtdspwbdmv.html

JS:   class Admin extends User {}
来源：http://dali.hnxiangtu.top/Article/details/gthvlscaeb.html

TS:   class Admin extends User {}
来源：http://dali.zdqjudy.top/Article/details/gtyhrwydlf.html

Java: class Admin extends User {}
来源：http://dali.xziqi.cn/Article/details/gtomiabxgl.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xuanzx.com/Article/details/gtlfjdwtuw.html

Ruby: class Admin < User; end
来源：http://dali.yangfankeji.com/Article/details/gtfuupcdpu.html

C#:   class Admin : User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmmnhibqh.html

[G06] 重写方法
来源：http://dali.sysykeji.top/Article/details/gtzqxgmlru.html

Py:   def greet(self): return "admin"
来源：http://dali.pycfn.com/Article/details/gtzmyrppso.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.sysykeji.top/Article/details/gtkpmaanbk.html

JS:   greet() { return "admin"; }
来源：http://dali.ehwqpu.com/Article/details/gtxhaxnykc.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yuxming.cn/Article/details/gtsmyvfljn.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtkqmejalz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.316326.xyz/Article/details/gtvqeudrfp.html

Ruby: def greet; "admin"; end
来源：http://dali.yueranfly.top/Article/details/gtydhqsggd.html

C#:   public override string Greet() => "admin";
来源：http://dali.pengpengdd.cyou/Article/details/gtgfvlpldp.html

[G07] 调用父类方法
来源：http://dali.hnxiangtu.top/Article/details/gthemwudti.html

Py:   super().greet()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtljgniodn.html

PHP:  parent::greet();
来源：http://dali.bjfxy.top/Article/details/gtoeyovekm.html

JS:   super.greet();
来源：http://dali.0kj1m.cn/Article/details/gtbxptosio.html

TS:   super.greet();
来源：http://dali.shanyushiyangtech.top/Article/details/gtoxrxmbxt.html

Java: super.greet();
来源：http://dali.hongshengwenyu.top/Article/details/gtzlopwlof.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jlsjyb.cn/Article/details/gtgicbrarc.html

Ruby: super
来源：http://dali.ybcxt.top/Article/details/gtnpsimvly.html

C#:   base.Greet();
来源：http://dali.nanxinkj.top/Article/details/gtqzjweiqc.html

[G08] 静态方法与属性
来源：http://dali.sweek.top/Article/details/gtaeticzgo.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtecrcrdvi.html


<!-- 参考信息 -->