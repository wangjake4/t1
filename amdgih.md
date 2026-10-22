代发 wailian999

Go:   strings.Count(s, "a")
来源：http://dali.guowangkeji.top/Article/details/gtzvyxmzur.html

Ruby: s.count("a")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtghkodusz.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yonumen.top/Article/details/gthwewmixi.html

[E13] 逐字符遍历
来源：http://dali.chenjidiqi.icu/Article/details/gtgcfdabpp.html

Py:   for ch in s: print(ch)
来源：http://dali.shangyingyoupin.top/Article/details/gtfaznjqlh.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.wangshuangyany.cn/Article/details/gttmmdxmsj.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yangfankeji.com/Article/details/gteymbobfz.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.dashuyun.cn/Article/details/gtxccikmpb.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.xuetiantiany.cn/Article/details/gtfaoqeejp.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.svipenyu.cn/Article/details/gtewhafnus.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.9152youxi.cn/Article/details/gtsvpmqdci.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.9152youxi.cn/Article/details/gtzkougoyu.html

[E14] URL 编码与 Base64
来源：http://dali.jiagoushi.top/Article/details/gtftspvhex.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.gotoacloud.top/Article/details/gtkzibafqa.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.snrcjt.cn/Article/details/gtiyolhntw.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.cdnleiting.top/Article/details/gtnluyjcme.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.daxiang520.top/Article/details/gtxicwzjnj.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.xuanzx.com/Article/details/gtqjrxzhpo.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.guannengcc.top/Article/details/gtkiiqtfvu.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.gogol.net.cn/Article/details/gtnusgkoew.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.andypj.xyz/Article/details/gtgwcudvtv.html

[E15] HTML 转义 / 反转义
来源：http://dali.kuanghao11.cn/Article/details/gtvkuxpclc.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.bjfxy.top/Article/details/gtjcyhqsie.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.vqdsnc.cn/Article/details/gtthtyzsic.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jianghu66.top/Article/details/gtyajfxfzc.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.vqdsnc.cn/Article/details/gtkylffmfe.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkxfavsbs.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.wangdashe.top/Article/details/gtnbgpusgt.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yueranfly.top/Article/details/gtcloxpiyy.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.fzhhl.top/Article/details/gtvkihdbll.html

[E16] 数字千分位
来源：http://dali.dianchejie.cn/Article/details/gtntqjdklj.html

Py:   f"{1234567:,}"
来源：http://dali.guowangkeji.top/Article/details/gtadvhhmxd.html

PHP:  number_format(1234567);
来源：http://dali.yuxming.cn/Article/details/gtyjylkvrp.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.shuidangran.top/Article/details/gtzhgstuom.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.shzxlz.cn/Article/details/gtfwphrcmn.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.kuanghao11.cn/Article/details/gtjlmgwiar.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.quarkkingdee.top/Article/details/gtlsybljqa.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gtziskuwqk.html

C#:   1234567.ToString("N0")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvmptewia.html

[E17] 首字母大写
来源：http://dali.hysaishi.cn/Article/details/gtusogrkvf.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ybcxt.top/Article/details/gtokdjwfcg.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jinqigfzy.top/Article/details/gtxqldjuxa.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.guannengcc.top/Article/details/gtftaaiixh.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.guannengcc.top/Article/details/gttgxzmnwn.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.cucudq.cn/Article/details/gtgbfunhgd.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.fzhhl.top/Article/details/gtgyhsfnvc.html

Ruby: s.capitalize
来源：http://dali.quarkkingdee.top/Article/details/gtxbluzxww.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.xuetiantiany.cn/Article/details/gtoxyeuztq.html

[E18] 模板占位符替换
来源：http://dali.snrcjt.cn/Article/details/gttmgmeacq.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.xuanzx.com/Article/details/gtmzlomuhf.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.bjfxy.top/Article/details/gtzbujwjvn.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.tianlin.xyz/Article/details/gtxyxxfagn.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.cdnleiting.top/Article/details/gtoowbrjms.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jinqigfzy.top/Article/details/gtxqvnhuxw.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yuxming.cn/Article/details/gtfeviaecs.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.shangyingyoupin.top/Article/details/gtasnofnqw.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.guannengcc.top/Article/details/gtvitzmpcr.html

[E19] 多行文本按行拆分
来源：http://dali.fengsongda.top/Article/details/gtfbzafezg.html

Py:   s.splitlines()
来源：http://dali.gzhubu.top/Article/details/gttmmfvcfb.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.sufxvd.cn/Article/details/gtwzygjtzg.html

JS:   s.split(/\r?\n/)
来源：http://dali.shangyingyoupin.top/Article/details/gtbdrlpgef.html

TS:   s.split(/\r?\n/)
来源：http://dali.chenzaomai.com/Article/details/gtejcwrxrs.html

Java: s.lines().toList()
来源：http://dali.chenlongwang.top/Article/details/gtyncodmgg.html

Go:   strings.Split(s, "\n")
来源：http://dali.cqqwz.cn/Article/details/gtwzlouita.html

Ruby: s.lines
来源：http://dali.xinyue.icu/Article/details/gtxrxqdmtx.html

C#:   s.Split('\n')
来源：http://dali.jinghuilouyu.cn/Article/details/gthhnokktm.html

[E20] 判断字符串是否为空
来源：http://dali.chenzaomai.com/Article/details/gtcqorwjaz.html

Py:   if not s:
来源：http://dali.hammf.cn/Article/details/gtfljaysok.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.gotoacloud.top/Article/details/gtmjkljtfj.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yuxming.cn/Article/details/gthburikfi.html

TS:   if (s === "") {}
来源：http://dali.shuidangran.top/Article/details/gtefhxgali.html

Java: if (s.isEmpty()) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtexbyjllk.html

Go:   if s == "" {}
来源：http://dali.zhengqikj.top/Article/details/gtsdmmxukb.html

Ruby: if s.empty?
来源：http://dali.aizwys.cn/Article/details/gtvpwcsmdq.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.316326.xyz/Article/details/gtsrdnocpc.html

[E21] 超长截断加省略号
来源：http://dali.jinqigfzy.top/Article/details/gtgpdvwbtj.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhengqikj.top/Article/details/gtcgrcxvtz.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yuanzhike.top/Article/details/gtrrrtjuem.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cheryme.top/Article/details/gtxoeummjl.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.daxiang520.top/Article/details/gtmfbpgncz.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yueranfly.top/Article/details/gtpnppbrof.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yanxiufei.cn/Article/details/gtjwcaqnti.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xuetiantiany.cn/Article/details/gttkxjhgyd.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jqgufenzy.top/Article/details/gtmnrnhexm.html

[E22] 字节长度与字符长度
来源：http://dali.cucudq.cn/Article/details/gtaonlgcim.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yj202588.top/Article/details/gtzywsqgdi.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnxizswoj.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cucudq.cn/Article/details/gtojyzpgau.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gzhubu.top/Article/details/gtltwbtque.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.9152youxi.cn/Article/details/gtudtmlvtf.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhiwuduotai.top/Article/details/gtgdahczud.html

Ruby: s.bytesize;  s.length
来源：http://dali.hongshengwenyu.top/Article/details/gtplhqjgcp.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.pycfn.com/Article/details/gtpvjqbhtv.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaixsvukw.html

F. 文件与目录
来源：http://dali.iojbl.cn/Article/details/gtolbnqqhz.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtkmglspng.html

[F01] 读取整个文件
来源：http://dali.yonumen.top/Article/details/gtkgqonvrv.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yongpay.top/Article/details/gtmnsrmuoz.html

PHP:  file_get_contents("a.txt");
来源：http://dali.cqqwz.cn/Article/details/gtryqrmrky.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yueranfly.top/Article/details/gtgpjdzrur.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.ehwqpu.com/Article/details/gtidzsfvuy.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jlsjyb.cn/Article/details/gtymsalsdg.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jinqigfzy.top/Article/details/gtdnpsfhue.html

Ruby: File.read("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtkjocqvzz.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnwutqdiq.html

[F02] 逐行读取文件
来源：http://dali.hysaishi.cn/Article/details/gtxrnivlpl.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.cucudq.cn/Article/details/gtnhrpzqtb.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.svipenyu.cn/Article/details/gtsbdyygvj.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.fzhhl.top/Article/details/gtdmoyfswg.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.redwolf501.top/Article/details/gtuwmhzoln.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ppjwa.cn/Article/details/gtupyffuyj.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.shanyushiyangtech.top/Article/details/gttyziitxk.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.gaohongyu789.top/Article/details/gtqctvejhr.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.gogol.net.cn/Article/details/gtpilgqgkf.html

[F03] 写入文件（覆盖）
来源：http://dali.cucudq.cn/Article/details/gtkatvilpj.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hywenlv.cn/Article/details/gtyvkymsdo.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.meibo888.top/Article/details/gtswqdvaly.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jyoumei.cn/Article/details/gtnsddqhcy.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhixingplan.top/Article/details/gttluqoufp.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhixingplan.top/Article/details/gtkkpzaoim.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.quarkkingdee.top/Article/details/gtkpfvyihi.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.svipenyu.cn/Article/details/gtdlelkepw.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jlsjyb.cn/Article/details/gtcdzqbacb.html

[F04] 追加写入文件
来源：http://dali.jyoumei.cn/Article/details/gttwwlaoop.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.quarkkingdee.top/Article/details/gtuxndqzpm.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.quarkkingdee.top/Article/details/gtypwgtsym.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinghuilouyu.cn/Article/details/gtnuchrcdc.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ehwqpu.com/Article/details/gtyygseora.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yuxming.cn/Article/details/gtfotnubxt.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqknbdrxq.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.sufxvd.cn/Article/details/gthtytzdik.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jlsjyb.cn/Article/details/gtklfyqsuv.html

[F05] 判断文件或目录是否存在
来源：http://dali.vqdsnc.cn/Article/details/gtynjqywwo.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhiwuduotai.top/Article/details/gttbtnqcip.html

PHP:  file_exists("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gtsnjnhbas.html

JS:   fs.existsSync("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtyeppnmvw.html

TS:   fs.existsSync("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gthqqodkwy.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.sysykeji.top/Article/details/gtauldkfvt.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvijuqobm.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtjskwxped.html

C#:   File.Exists("a.txt")
来源：http://dali.tanke756.top/Article/details/gtquizovjy.html

[F06] 删除文件
来源：http://dali.dianchejie.cn/Article/details/gtabtqfwjr.html

Py:   os.remove("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtivfuhkle.html

PHP:  unlink("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gteylqvaag.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.316326.xyz/Article/details/gtmrivfmim.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtleofjtju.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.mhx1999.top/Article/details/gtgsykreuo.html

Go:   os.Remove("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtxiuavqom.html

Ruby: File.delete("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtfmxsiwhc.html

C#:   File.Delete("a.txt");
来源：http://dali.yueranfly.top/Article/details/gtjovtwlnw.html

[F07] 创建目录（含多级）
来源：http://dali.jinqigfzy.top/Article/details/gtmhkeswtp.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtptjwfsqs.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hywenlv.cn/Article/details/gtapzjgyei.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.fengsongda.top/Article/details/gtxxivtnvd.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zdqjudy.top/Article/details/gtlhqleyrd.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.smart0.xyz/Article/details/gtivpdsvzq.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhongyouzk.top/Article/details/gteyuafaqt.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hnqzz.top/Article/details/gtmirnlsmj.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.tanke756.top/Article/details/gttiujtvlv.html

[F08] 遍历目录
来源：http://dali.jinqigufen.top/Article/details/gtpwqhiafr.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.shuidangran.top/Article/details/gtkbghwcox.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.dianchejie.cn/Article/details/gtmdbfswzi.html

JS:   fs.readdirSync("dir")
来源：http://dali.hysaishi.cn/Article/details/gtckhtdcxg.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtskytzigo.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.havefunace.top/Article/details/gtsvgxlhjz.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hongshengwenyu.top/Article/details/gtooslfcsi.html

Ruby: Dir.children("dir")
来源：http://dali.dianchejie.cn/Article/details/gtydguffwj.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yj20258888.top/Article/details/gtrofbfxvc.html

[F09] 获取文件大小
来源：http://dali.daxiang520.top/Article/details/gtpuwhirth.html

Py:   os.path.getsize("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtsfokpozt.html

PHP:  filesize("a.txt");
来源：http://dali.guannengcc.top/Article/details/gtkbvfekln.html

JS:   fs.statSync("a.txt").size
来源：http://dali.dashuyun.cn/Article/details/gthtpcpadr.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxdcuuwtt.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhiwuduotai.top/Article/details/gtecvfnsfx.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.cdnleiting.top/Article/details/gtitzncgof.html

Ruby: File.size("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtogbulqkl.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jlsjyb.cn/Article/details/gtvneqdgcc.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jinghuilouyu.cn/Article/details/gtofkbeaan.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.316326.xyz/Article/details/gtlzuktezo.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.gzhubu.top/Article/details/gtkhzgfkgt.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.ybcxt.top/Article/details/gtraretxwx.html

TS:   path.extname("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtvcoljwtf.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtavwkijmf.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.fzhhl.top/Article/details/gtzuvnzxyi.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtgefbjocs.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hammf.cn/Article/details/gtmsuuaelz.html

[F11] 复制与移动文件
来源：http://dali.yangfankeji.com/Article/details/gtsvqnxuyc.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.daxiang520.top/Article/details/gtvjodnqdn.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtvkwdhsch.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhixingplan.top/Article/details/gtstqizati.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtbpxqqaso.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.316326.xyz/Article/details/gtnmhczftj.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yuxming.cn/Article/details/gtuflftydr.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyvendlqw.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.tanke756.top/Article/details/gtgrthijtk.html

[F12] CSV 读写
来源：http://dali.yanxiufei.cn/Article/details/gtgldqpuvt.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yvedp.cn/Article/details/gtrtmspkoy.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.meibo888.top/Article/details/gtjbuudwme.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.gaohongyu789.top/Article/details/gtejqlkuzh.html

TS:   // 同上
来源：http://dali.jinyuanbaomall.cn/Article/details/gtazmvcdte.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jinyuanbaomall.cn/Article/details/gtafrbzccr.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.chenlongwang.top/Article/details/gtipebuupf.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.316326.xyz/Article/details/gtzpnkxljz.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jqgufenzy.top/Article/details/gtzejucqcs.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtswaqasoc.html

G. 面向对象
来源：http://dali.chenzaomai.com/Article/details/gtfwzlarci.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtshswvots.html

[G01] 定义类
来源：http://dali.sufxvd.cn/Article/details/gtsqnfnicp.html

Py:   class User: pass
来源：http://dali.aibaodan.cn/Article/details/gtjelciddd.html

PHP:  class User {}
来源：http://dali.yuxming.cn/Article/details/gtaphiogmu.html

JS:   class User {}
来源：http://dali.jiagoushi.top/Article/details/gtrpqvlhgg.html

TS:   class User { name: string = ""; }
来源：http://dali.shangyingyoupin.top/Article/details/gtassxjhwd.html

Java: class User {}
来源：http://dali.xuetiantiany.cn/Article/details/gthmtqxhaz.html

Go:   type User struct { Name string }
来源：http://dali.yangfankeji.com/Article/details/gtojcnjdzi.html

Ruby: class User; end
来源：http://dali.cashguo.top/Article/details/gtjvkkmcsg.html

C#:   class User {}
来源：http://dali.shangyingyoupin.top/Article/details/gthjofozrs.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gtdtzypwhj.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xinyue.icu/Article/details/gtwhejbruk.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.havefunace.top/Article/details/gtbdlavmak.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yongpay.top/Article/details/gtyuckxhrs.html

TS:   constructor(public name: string) {}
来源：http://dali.sufxvd.cn/Article/details/gtbtooeilr.html

Java: User(String name) { this.name = name; }
来源：http://dali.wangdashe.top/Article/details/gtuxlfcbxl.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.tianlin.xyz/Article/details/gtiivohskq.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhiwuduotai.top/Article/details/gtekzgxvxj.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jqgufenzy.top/Article/details/gtknypmxzn.html

[G03] 实例属性
来源：http://dali.jqgfzy.top/Article/details/gtihxdvpxs.html

Py:   self.name = "x"
来源：http://dali.chenjidiqi.icu/Article/details/gtkzcbensj.html

PHP:  public string $name = "x";
来源：http://dali.chenlongwang.top/Article/details/gtwxhsnfgt.html

JS:   this.name = "x";
来源：http://dali.fzhhl.top/Article/details/gtiyjcbsfr.html

TS:   name: string = "x";
来源：http://dali.havefunace.top/Article/details/gtkxupycih.html

Java: private String name;
来源：http://dali.kuanghao11.cn/Article/details/gtmtywdode.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.redwolf501.top/Article/details/gtrhuiuzde.html

Ruby: @name = "x"
来源：http://dali.jyoumei.cn/Article/details/gtpsbjqsao.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.smart0.xyz/Article/details/gtqcwkeomd.html

[G04] 定义方法
来源：http://dali.gogol.net.cn/Article/details/gtcwdtrczs.html

Py:   def greet(self): return self.name
来源：http://dali.zycfv.cn/Article/details/gtqafdsvrg.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jinqigfzy.top/Article/details/gtlolshfrw.html

JS:   greet() { return this.name; }
来源：http://dali.ybcxt.top/Article/details/gtvqdyznpi.html

TS:   greet(): string { return this.name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwhfamqpr.html

Java: String greet() { return name; }
来源：http://dali.hnqzz.top/Article/details/gtndcrqgsn.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jlsjyb.cn/Article/details/gtppclffay.html

Ruby: def greet; @name; end
来源：http://dali.hnxiangtu.top/Article/details/gtcprztdbr.html

C#:   public string Greet() => Name;
来源：http://dali.yuxming.cn/Article/details/gtdoetoydf.html

[G05] 继承
来源：http://dali.gogol.net.cn/Article/details/gtatwgtvvg.html

Py:   class Admin(User): pass
来源：http://dali.ppjwa.cn/Article/details/gtxmhdoons.html

PHP:  class Admin extends User {}
来源：http://dali.gogol.net.cn/Article/details/gtvcfabokb.html

JS:   class Admin extends User {}
来源：http://dali.hywenlv.cn/Article/details/gtcwgfhhuo.html

TS:   class Admin extends User {}
来源：http://dali.ppjwa.cn/Article/details/gtxasvshzh.html

Java: class Admin extends User {}
来源：http://dali.zhoulong.xyz/Article/details/gtqdhtumhn.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yangfankeji.com/Article/details/gtmnjrdufr.html

Ruby: class Admin < User; end
来源：http://dali.nwbrower.top/Article/details/gtiwwtbyvl.html

C#:   class Admin : User {}
来源：http://dali.xylfe.cn/Article/details/gtenmfxwsn.html

[G06] 重写方法
来源：http://dali.daxiang520.top/Article/details/gtbltigpkd.html

Py:   def greet(self): return "admin"
来源：http://dali.feifeiyinyue.top/Article/details/gtygvludwl.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.chenlongwang.top/Article/details/gtziogcqou.html

JS:   greet() { return "admin"; }
来源：http://dali.dianchejie.cn/Article/details/gtmdxzfhoc.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ydzc1.top/Article/details/gtixiqamyi.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtjyvjvxvf.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yonumen.top/Article/details/gtuckcjuer.html

Ruby: def greet; "admin"; end
来源：http://dali.vqdsnc.cn/Article/details/gtjjtdhhry.html

C#:   public override string Greet() => "admin";
来源：http://dali.yuanzhike.top/Article/details/gthzwlnnhk.html

[G07] 调用父类方法
来源：http://dali.zhengqikj.top/Article/details/gtvuajvekx.html

Py:   super().greet()
来源：http://dali.zhongyouzk.top/Article/details/gtytedeexi.html

PHP:  parent::greet();
来源：http://dali.tanke756.top/Article/details/gtgukhimoj.html

JS:   super.greet();
来源：http://dali.cdnleiting.top/Article/details/gtdxedgcmw.html

TS:   super.greet();
来源：http://dali.gaohongyu789.top/Article/details/gtxicfvcry.html

Java: super.greet();
来源：http://dali.tian-w.cn/Article/details/gtmzlvusqn.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.svipenyu.cn/Article/details/gtmbgjdydt.html

Ruby: super
来源：http://dali.chenzaomai.com/Article/details/gtayphnpsx.html

C#:   base.Greet();
来源：http://dali.316326.xyz/Article/details/gtbvmnvzje.html

[G08] 静态方法与属性
来源：http://dali.yuanzhike.top/Article/details/gtaymvkxxz.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.chenjidiqi.icu/Article/details/gthnxhdhca.html

PHP:  public static function f() {}
来源：http://dali.cucudq.cn/Article/details/gtuoegphhi.html

JS:   static f() {}
来源：http://dali.jqgufenzy.top/Article/details/gtdfuujmxg.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gtblhqwmwf.html

Java: static void f() {}
来源：http://dali.fengsongda.top/Article/details/gtruukkapv.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.daxiang520.top/Article/details/gtxxhecyoj.html

Ruby: def self.f; end
来源：http://dali.ppjwa.cn/Article/details/gtdmlvjhjg.html

C#:   public static void F() {}
来源：http://dali.pycfn.com/Article/details/gtofilavyb.html

[G09] 接口 / 抽象类
来源：http://dali.tian-w.cn/Article/details/gtuxklxmzc.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.aibaodan.cn/Article/details/gtexkhubia.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zycfv.cn/Article/details/gtntycvypc.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.fzhhl.top/Article/details/gtnfvpvtqp.html

TS:   interface Shape { area(): number; }
来源：http://dali.nanxuanxn.top/Article/details/gtcnuyuahv.html

Java: interface Shape { double area(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtrytrqdkw.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xziqi.cn/Article/details/gtctdacjzv.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhiwuduotai.top/Article/details/gtwluxtwim.html

C#:   interface IShape { double Area(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtxqnseeof.html

[G10] 访问控制
来源：http://dali.jinghuilouyu.cn/Article/details/gtsjoznagr.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.shangyingyoupin.top/Article/details/gtwvagdjmu.html

PHP:  public / protected / private
来源：http://dali.havefunace.top/Article/details/gtbnfzlxjc.html

JS:   #private 字段；其余公开
来源：http://dali.hnqzz.top/Article/details/gtvowtaouy.html

TS:   public / protected / private
来源：http://dali.mhx1999.top/Article/details/gtkbhbidqx.html

Java: public / protected / private / 默认包级
来源：http://dali.iojbl.cn/Article/details/gtpgnzwhka.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.nwbrower.top/Article/details/gtigurouio.html

Ruby: public / protected / private
来源：http://dali.gotoacloud.top/Article/details/gtijsqwrsv.html

C#:   public / protected / private / internal
来源：http://dali.shangyingyoupin.top/Article/details/gtnngmqlac.html

[G11] getter / setter
来源：http://dali.jqgufenzy.top/Article/details/gtxvjjmwcy.html

Py:   @property 与 @x.setter
来源：http://dali.gzhubu.top/Article/details/gtixdbcmwy.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jyoumei.cn/Article/details/gtnryaytby.html


<!-- 参考信息 -->