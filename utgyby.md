代发 wailian999

Go:   strings.Count(s, "a")
来源：http://dali.yangfankeji.com/Article/details/gtekgoqhhj.html

Ruby: s.count("a")
来源：http://dali.ppjwa.cn/Article/details/gtekmhfvdf.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yj20258.top/Article/details/gttukywuti.html

[E13] 逐字符遍历
来源：http://dali.yuanzhike.top/Article/details/gtqsheovzg.html

Py:   for ch in s: print(ch)
来源：http://dali.hammf.cn/Article/details/gtqhjhhptt.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.316326.xyz/Article/details/gtmeiggqni.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.mhx1999.top/Article/details/gtzlnljnbd.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.smart0.xyz/Article/details/gtfjysenpa.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hnxiangtu.top/Article/details/gtcrbtfylv.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yj202588.top/Article/details/gtregkidsw.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.ivvv.top/Article/details/gtuwpcmgrh.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.xuetiantiany.cn/Article/details/gtsmtnzaif.html

[E14] URL 编码与 Base64
来源：http://dali.fengsongda.top/Article/details/gtrdjfgznx.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.shzxlz.cn/Article/details/gtmjeofkfl.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.birdmap.top/Article/details/gtahgeuzqz.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.gogol.net.cn/Article/details/gttutscwjz.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtctvmkwte.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.havefunace.top/Article/details/gtnbxwbmfz.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.gzhubu.top/Article/details/gtmjfhaekt.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yuxming.cn/Article/details/gtjsnchmop.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.kuanghao11.cn/Article/details/gtoorxsnvb.html

[E15] HTML 转义 / 反转义
来源：http://dali.pengpengdd.cyou/Article/details/gthljcigas.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.birdmap.top/Article/details/gthmqhdhcq.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.tianlin.xyz/Article/details/gtaqmvdgct.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jlsjyb.cn/Article/details/gtxaffndip.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.daria6918.cn/Article/details/gtuntlrpem.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.kuanghao11.cn/Article/details/gtnflcvddb.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.daria6918.cn/Article/details/gtimzfsvkw.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtghytxuqh.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jianghu66.top/Article/details/gtsaxtdesk.html

[E16] 数字千分位
来源：http://dali.sysykeji.top/Article/details/gtcbcvxryn.html

Py:   f"{1234567:,}"
来源：http://dali.cdnleiting.top/Article/details/gtznjosvas.html

PHP:  number_format(1234567);
来源：http://dali.hywenlv.cn/Article/details/gtccqwqhzm.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yanxiufei.cn/Article/details/gtwalwbjnu.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinyuanbaomall.cn/Article/details/gteddumepz.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.nanxuanxn.top/Article/details/gttpqfdoig.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.chenjidiqi.icu/Article/details/gtesjbencn.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jqgfzy.top/Article/details/gtxgurxoac.html

C#:   1234567.ToString("N0")
来源：http://dali.ybcxt.top/Article/details/gtrmadbffl.html

[E17] 首字母大写
来源：http://dali.hfpthk.cn/Article/details/gtpjtbwirm.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.9152youxi.cn/Article/details/gtocajwnug.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yongpay.top/Article/details/gtwiuregmh.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gaohongyu789.top/Article/details/gtdssntzwb.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.dianchejie.cn/Article/details/gtfzvybivm.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.smart0.xyz/Article/details/gtgbcuudra.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.xylfe.cn/Article/details/gtrwtyfdrt.html

Ruby: s.capitalize
来源：http://dali.redwolf501.top/Article/details/gtgafjjawu.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.kuanghao11.cn/Article/details/gtdaidxiec.html

[E18] 模板占位符替换
来源：http://dali.snrcjt.cn/Article/details/gtittesebf.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jinghuilouyu.cn/Article/details/gtjceuaqrm.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhengqikj.top/Article/details/gtjwlyxsnj.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.shzxlz.cn/Article/details/gtbqiirenb.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmvfgtzxe.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yj202588.top/Article/details/gtcyfhqttn.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.meibo888.top/Article/details/gtwlbmltky.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.birdmap.top/Article/details/gtuofoquwr.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.snrcjt.cn/Article/details/gtypxftpgv.html

[E19] 多行文本按行拆分
来源：http://dali.sxryk.cn/Article/details/gtmvxzttfg.html

Py:   s.splitlines()
来源：http://dali.pycfn.com/Article/details/gtlzzvlwcx.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.xylfe.cn/Article/details/gtzehiermc.html

JS:   s.split(/\r?\n/)
来源：http://dali.0kj1m.cn/Article/details/gtvvusloxj.html

TS:   s.split(/\r?\n/)
来源：http://dali.daxiang520.top/Article/details/gtvjqbhmhe.html

Java: s.lines().toList()
来源：http://dali.0kj1m.cn/Article/details/gtgnhjiklt.html

Go:   strings.Split(s, "\n")
来源：http://dali.kuanghao11.cn/Article/details/gtbjicpaad.html

Ruby: s.lines
来源：http://dali.gzhubu.top/Article/details/gtgzjppelf.html

C#:   s.Split('\n')
来源：http://dali.svipenyu.cn/Article/details/gtthsxpjym.html

[E20] 判断字符串是否为空
来源：http://dali.sweek.top/Article/details/gtbjskojct.html

Py:   if not s:
来源：http://dali.xylfe.cn/Article/details/gthjbumcck.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.dashuyun.cn/Article/details/gtedfifjsx.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yueranfly.top/Article/details/gtawymbvvy.html

TS:   if (s === "") {}
来源：http://dali.daria6918.cn/Article/details/gtioiptfjb.html

Java: if (s.isEmpty()) {}
来源：http://dali.dashuyun.cn/Article/details/gtqyjunbrl.html

Go:   if s == "" {}
来源：http://dali.yuanzhike.top/Article/details/gtwhlqkyhi.html

Ruby: if s.empty?
来源：http://dali.jqgfzy.top/Article/details/gtwpecyqvn.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.gotoacloud.top/Article/details/gtbhozpwjn.html

[E21] 超长截断加省略号
来源：http://dali.chenjidiqi.icu/Article/details/gtnhnqpbyh.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.guannengcc.top/Article/details/gtqjdvudci.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.daria6918.cn/Article/details/gtyidpfjtq.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ivvv.top/Article/details/gtyymeqyzg.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.quarkkingdee.top/Article/details/gthjstazui.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.tian-w.cn/Article/details/gtwjkxzvqm.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xuanzx.com/Article/details/gtznftyeju.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgpixvnwx.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.havefunace.top/Article/details/gtkqixcoam.html

[E22] 字节长度与字符长度
来源：http://dali.sysykeji.top/Article/details/gtmwzmggeu.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zycfv.cn/Article/details/gtlxscomvm.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.vqdsnc.cn/Article/details/gttlglsqgx.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yueranfly.top/Article/details/gtakkpfhru.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.svipenyu.cn/Article/details/gtztmfvpbt.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hysaishi.cn/Article/details/gtfxzycfus.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.xuanzx.com/Article/details/gtvflvvedv.html

Ruby: s.bytesize;  s.length
来源：http://dali.quarkkingdee.top/Article/details/gtuqyirvxv.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.hnxiangtu.top/Article/details/gtvduvfyqo.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtxaxiveuo.html

F. 文件与目录
来源：http://dali.jinqigufen.top/Article/details/gtovmxdiiv.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtmjvtajnx.html

[F01] 读取整个文件
来源：http://dali.jlsjyb.cn/Article/details/gthlckckno.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.shzxlz.cn/Article/details/gtwgydqjwh.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gtdwgezbgl.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.mhx1999.top/Article/details/gthhmjuttn.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.xziqi.cn/Article/details/gtmisunsnu.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.chenzaomai.com/Article/details/gtjyxicidu.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yueranfly.top/Article/details/gtsjkpgtws.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtryyyipyi.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gtnquqylbb.html

[F02] 逐行读取文件
来源：http://dali.sufxvd.cn/Article/details/gtdrmzwxqs.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.dianchejie.cn/Article/details/gtqkjtvyik.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.haohaochexian.top/Article/details/gtbyrraacr.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.iojbl.cn/Article/details/gtpxefisus.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shzxlz.cn/Article/details/gtqudmsxsz.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.snrcjt.cn/Article/details/gtduamsvxq.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hnxiangtu.top/Article/details/gtcbszhqtr.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yanxiufei.cn/Article/details/gtqblzgptb.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.nwbrower.top/Article/details/gtcxivorok.html

[F03] 写入文件（覆盖）
来源：http://dali.ehwqpu.com/Article/details/gtrwezjpcw.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.svipenyu.cn/Article/details/gtvdyejtdp.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.pengpengdd.cyou/Article/details/gtlvnszmmd.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.birdmap.top/Article/details/gtszvvfmyx.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhiwuduotai.top/Article/details/gtqmjgfxcw.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yuanzhike.top/Article/details/gtuvymnxlw.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiqmyxmkl.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yanxiufei.cn/Article/details/gtkkwntjmq.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.316326.xyz/Article/details/gtczxbfpdo.html

[F04] 追加写入文件
来源：http://dali.meibo888.top/Article/details/gtjlqykezw.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.haohaochexian.top/Article/details/gtfeskylkp.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmufvmcol.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.mhx1999.top/Article/details/gtzshziuex.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ppjwa.cn/Article/details/gtbphdrobx.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.haohaochexian.top/Article/details/gtwtkftcqe.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.sufxvd.cn/Article/details/gtojvmvclr.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtovdgyukp.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.gzhubu.top/Article/details/gttbfhhdfh.html

[F05] 判断文件或目录是否存在
来源：http://dali.jinghuilouyu.cn/Article/details/gtsjtuykag.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jqgufenzy.top/Article/details/gtwuymbosj.html

PHP:  file_exists("a.txt");
来源：http://dali.sxryk.cn/Article/details/gtwfyhhijz.html

JS:   fs.existsSync("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtafplczbh.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtjjaqmmln.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.mhx1999.top/Article/details/gttxnoizgq.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ehwqpu.com/Article/details/gtogbcvgfn.html

Ruby: File.exist?("a.txt")
来源：http://dali.hammf.cn/Article/details/gthlxjzkzb.html

C#:   File.Exists("a.txt")
来源：http://dali.havefunace.top/Article/details/gtsllbpjmk.html

[F06] 删除文件
来源：http://dali.yueranfly.top/Article/details/gtuhkwcozf.html

Py:   os.remove("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtwazjdghv.html

PHP:  unlink("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtohipqabp.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtwaxvqlxx.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtcfccodih.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yj202588.top/Article/details/gtlxglxtjx.html

Go:   os.Remove("a.txt")
来源：http://dali.cheryme.top/Article/details/gttcaazmnp.html

Ruby: File.delete("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gthvgjiuww.html

C#:   File.Delete("a.txt");
来源：http://dali.jianghu66.top/Article/details/gtgjdtmaxi.html

[F07] 创建目录（含多级）
来源：http://dali.hammf.cn/Article/details/gtdybslqpi.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jyoumei.cn/Article/details/gtasdnmvsi.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.0kj1m.cn/Article/details/gtlnqepgcr.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhongyouzk.top/Article/details/gtkdfghhyr.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.tianlin.xyz/Article/details/gtyrotlrmv.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jianghu66.top/Article/details/gtsygojisu.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yonumen.top/Article/details/gtcdkcwsxh.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.chenlongwang.top/Article/details/gtrdijidcb.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.iojbl.cn/Article/details/gtrbqnbwdx.html

[F08] 遍历目录
来源：http://dali.sweek.top/Article/details/gtsvouiiak.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.aibaodan.cn/Article/details/gtizwtkrnv.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtluxlifsi.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhengqikj.top/Article/details/gtgztedfzl.html

TS:   fs.readdirSync("dir")
来源：http://dali.yj202588.top/Article/details/gtqojtvdff.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.9152youxi.cn/Article/details/gtaaepvvzc.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hnxiangtu.top/Article/details/gtyoaybmze.html

Ruby: Dir.children("dir")
来源：http://dali.sxryk.cn/Article/details/gtfitrzpwn.html

C#:   Directory.GetFiles("dir")
来源：http://dali.birdmap.top/Article/details/gtubngfhsg.html

[F09] 获取文件大小
来源：http://dali.yuanzhike.top/Article/details/gttcbnkdzg.html

Py:   os.path.getsize("a.txt")
来源：http://dali.cheryme.top/Article/details/gtbureedpd.html

PHP:  filesize("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtwzrafbme.html

JS:   fs.statSync("a.txt").size
来源：http://dali.smart0.xyz/Article/details/gtywsocxyk.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yonumen.top/Article/details/gtpiskyckb.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yueranfly.top/Article/details/gtklrtrebj.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.ybcxt.top/Article/details/gtbspvycrw.html

Ruby: File.size("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtdaxmqhsr.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jinqigufen.top/Article/details/gtiwtscjsv.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.dianchejie.cn/Article/details/gtxkknasrb.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtanvqjjsg.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yj20258888.top/Article/details/gtqodjfpnh.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtusatgftt.html

TS:   path.extname("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtkhfqccqq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yj202588.top/Article/details/gtvxcpslvy.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtewwdaoyx.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.svipenyu.cn/Article/details/gthobahuev.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtezmsvztf.html

[F11] 复制与移动文件
来源：http://dali.zhengqikj.top/Article/details/gtsynpgona.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.pycfn.com/Article/details/gtzrkvhoyt.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yj202588.top/Article/details/gtdtiwuurj.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xuanzx.com/Article/details/gtifbtcpyn.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ivvv.top/Article/details/gtbbdwehhl.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.chenlongwang.top/Article/details/gtxvbkbidv.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.9152youxi.cn/Article/details/gtywzrhlrc.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.cqqwz.cn/Article/details/gtqsmojfyh.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.sxryk.cn/Article/details/gtoghaqsbk.html

[F12] CSV 读写
来源：http://dali.chenlongwang.top/Article/details/gtjacqubee.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdjslbicp.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jinqigfzy.top/Article/details/gtlzksiken.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.ppjwa.cn/Article/details/gtuhwuyirr.html

TS:   // 同上
来源：http://dali.yonumen.top/Article/details/gtvhdevezx.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.chenzaomai.com/Article/details/gtmbwsykmk.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmgfdkodt.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jqgfzy.top/Article/details/gtfuebaskm.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.fzhhl.top/Article/details/gtenxhfcbx.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtcmrsekhn.html

G. 面向对象
来源：http://dali.nwbrower.top/Article/details/gtjdmgnhsw.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtucslufus.html

[G01] 定义类
来源：http://dali.cqqwz.cn/Article/details/gtqepkwizp.html

Py:   class User: pass
来源：http://dali.hnqzz.top/Article/details/gtgwjapieh.html

PHP:  class User {}
来源：http://dali.daxiang520.top/Article/details/gtboybhbal.html

JS:   class User {}
来源：http://dali.xuanzx.com/Article/details/gtywzqeuev.html

TS:   class User { name: string = ""; }
来源：http://dali.hfpthk.cn/Article/details/gtpoeswmam.html

Java: class User {}
来源：http://dali.yj20258.top/Article/details/gtydfvppmy.html

Go:   type User struct { Name string }
来源：http://dali.tanke756.top/Article/details/gthzarqqge.html

Ruby: class User; end
来源：http://dali.yongpay.top/Article/details/gtwtaeemrq.html

C#:   class User {}
来源：http://dali.ydzc1.top/Article/details/gthftnxgvn.html

[G02] 构造函数
来源：http://dali.yvedp.cn/Article/details/gtqymcxwkr.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hammf.cn/Article/details/gtzghaispc.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.cashguo.top/Article/details/gtjnrnleqk.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hfpthk.cn/Article/details/gtsdzngica.html

TS:   constructor(public name: string) {}
来源：http://dali.0kj1m.cn/Article/details/gtaixltlig.html

Java: User(String name) { this.name = name; }
来源：http://dali.bjfxy.top/Article/details/gtwcqgwndu.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hywenlv.cn/Article/details/gtgsunvvbl.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.daria6918.cn/Article/details/gtawcevmkg.html

C#:   public User(string name) { Name = name; }
来源：http://dali.9152youxi.cn/Article/details/gthzrbmpef.html

[G03] 实例属性
来源：http://dali.sufxvd.cn/Article/details/gtrrgibwoz.html

Py:   self.name = "x"
来源：http://dali.cashguo.top/Article/details/gtummhaawi.html

PHP:  public string $name = "x";
来源：http://dali.sufxvd.cn/Article/details/gtlknxtcfu.html

JS:   this.name = "x";
来源：http://dali.aizwys.cn/Article/details/gtrzdlqgfn.html

TS:   name: string = "x";
来源：http://dali.feifeiyinyue.top/Article/details/gtgljtwicz.html

Java: private String name;
来源：http://dali.yueranfly.top/Article/details/gtzwgbmowu.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jinghuilouyu.cn/Article/details/gtzhzjgwvf.html

Ruby: @name = "x"
来源：http://dali.chenzaomai.com/Article/details/gtgoayhnbk.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.bjfxy.top/Article/details/gtsmruwojm.html

[G04] 定义方法
来源：http://dali.pengpengdd.cyou/Article/details/gtbqrntwia.html

Py:   def greet(self): return self.name
来源：http://dali.daxiang520.top/Article/details/gtyeqijcrd.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.tianlin.xyz/Article/details/gtasetignz.html

JS:   greet() { return this.name; }
来源：http://dali.jinqigfzy.top/Article/details/gtqwxkemst.html

TS:   greet(): string { return this.name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtmegmtaqk.html

Java: String greet() { return name; }
来源：http://dali.aizwys.cn/Article/details/gtizcvuitm.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ivvv.top/Article/details/gtcdvuyogr.html

Ruby: def greet; @name; end
来源：http://dali.fengsongda.top/Article/details/gtdifdyznk.html

C#:   public string Greet() => Name;
来源：http://dali.sxryk.cn/Article/details/gtznxqlxzq.html

[G05] 继承
来源：http://dali.hysaishi.cn/Article/details/gtungwxgvk.html

Py:   class Admin(User): pass
来源：http://dali.mhx1999.top/Article/details/gtjezrnmvg.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gtlajnzvoc.html

JS:   class Admin extends User {}
来源：http://dali.hammf.cn/Article/details/gtdgjfmlbh.html

TS:   class Admin extends User {}
来源：http://dali.gogol.net.cn/Article/details/gtxriwblcq.html

Java: class Admin extends User {}
来源：http://dali.guowangkeji.top/Article/details/gthbabqabo.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.meibo888.top/Article/details/gtpjrqsrea.html

Ruby: class Admin < User; end
来源：http://dali.iojbl.cn/Article/details/gtthgrgpxj.html

C#:   class Admin : User {}
来源：http://dali.jianghu66.top/Article/details/gtnnixlfyz.html

[G06] 重写方法
来源：http://dali.gogol.net.cn/Article/details/gtumvyjxxi.html

Py:   def greet(self): return "admin"
来源：http://dali.guannengcc.top/Article/details/gthvveumzy.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.c1oappe.top/Article/details/gtimiwszhs.html

JS:   greet() { return "admin"; }
来源：http://dali.shzxlz.cn/Article/details/gttfqgacgn.html

TS:   greet(): string { return "admin"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtyqcbjizc.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yonumen.top/Article/details/gtocsuupwl.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.vqdsnc.cn/Article/details/gthdtlihng.html

Ruby: def greet; "admin"; end
来源：http://dali.daria6918.cn/Article/details/gtronkvsrd.html

C#:   public override string Greet() => "admin";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkrqsvxob.html

[G07] 调用父类方法
来源：http://dali.ppjwa.cn/Article/details/gtfvtazplw.html

Py:   super().greet()
来源：http://dali.shzxlz.cn/Article/details/gtqbaxobzw.html

PHP:  parent::greet();
来源：http://dali.zhixingplan.top/Article/details/gtufqhamfk.html

JS:   super.greet();
来源：http://dali.snrcjt.cn/Article/details/gtrmdixkyo.html

TS:   super.greet();
来源：http://dali.yongpay.top/Article/details/gtdllulhsj.html

Java: super.greet();
来源：http://dali.ehwqpu.com/Article/details/gtoayjrdxb.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.quarkkingdee.top/Article/details/gtbqhcfibu.html

Ruby: super
来源：http://dali.yonumen.top/Article/details/gtwqiowlkg.html

C#:   base.Greet();
来源：http://dali.cdnleiting.top/Article/details/gtpyjnstpt.html

[G08] 静态方法与属性
来源：http://dali.cashguo.top/Article/details/gtmsxxpoqh.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.iojbl.cn/Article/details/gtfatjvrps.html

PHP:  public static function f() {}
来源：http://dali.kuanghao11.cn/Article/details/gthvbdgeqq.html

JS:   static f() {}
来源：http://dali.zhiwuduotai.top/Article/details/gtpspzhhvt.html

TS:   static f(): void {}
来源：http://dali.jlsjyb.cn/Article/details/gtmahzdjuo.html

Java: static void f() {}
来源：http://dali.yj20258888.top/Article/details/gtaieavmxo.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.sweek.top/Article/details/gtfmlnniff.html

Ruby: def self.f; end
来源：http://dali.yongpay.top/Article/details/gtmuwkbbot.html

C#:   public static void F() {}
来源：http://dali.jqgfzy.top/Article/details/gtdftsufxw.html

[G09] 接口 / 抽象类
来源：http://dali.ivvv.top/Article/details/gtzmhthvyv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hongshengwenyu.top/Article/details/gtuksmsjgp.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.cdnleiting.top/Article/details/gtekejdqsk.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jyoumei.cn/Article/details/gtdgxrchfc.html

TS:   interface Shape { area(): number; }
来源：http://dali.wangdashe.top/Article/details/gtzscqwbnk.html

Java: interface Shape { double area(); }
来源：http://dali.ehwqpu.com/Article/details/gthpepfczt.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.wangdashe.top/Article/details/gtuymjxsic.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.tian-w.cn/Article/details/gtqreohkxx.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhongyouzk.top/Article/details/gtpiwvzzfu.html

[G10] 访问控制
来源：http://dali.hysaishi.cn/Article/details/gtrdlprajn.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hammf.cn/Article/details/gtlgwuwgds.html

PHP:  public / protected / private
来源：http://dali.mhx1999.top/Article/details/gtczcdlkro.html

JS:   #private 字段；其余公开
来源：http://dali.zhixingplan.top/Article/details/gtnhvbjbdn.html

TS:   public / protected / private
来源：http://dali.yueranfly.top/Article/details/gtqwsxzate.html

Java: public / protected / private / 默认包级
来源：http://dali.zhixingplan.top/Article/details/gttlrqrtki.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.tianlin.xyz/Article/details/gtfgcsdszx.html

Ruby: public / protected / private
来源：http://dali.cucudq.cn/Article/details/gtysmlkxrt.html

C#:   public / protected / private / internal
来源：http://dali.gaohongyu789.top/Article/details/gtynodnxer.html

[G11] getter / setter
来源：http://dali.tanke756.top/Article/details/gtprnvswkm.html

Py:   @property 与 @x.setter
来源：http://dali.xuetiantiany.cn/Article/details/gtedfhjcvw.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtayexuccv.html


<!-- 参考信息 -->