代发 wailian999

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhengqikj.top/Article/details/gtxwtfjtyd.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.guannengcc.top/Article/details/gtemaminbw.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jyoumei.cn/Article/details/gtgljiqhwi.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gtymagdkay.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yj202588.top/Article/details/gtpfxxtbqd.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yj20258.top/Article/details/gtkaiykujt.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.guannengcc.top/Article/details/gtvgpvijap.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yj20258.top/Article/details/gtldgmoldh.html

[E10] 左侧补零 / 定长填充
来源：http://dali.ybcxt.top/Article/details/gtevpxbhwb.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.cashguo.top/Article/details/gtnfqzpvrc.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jianghu66.top/Article/details/gtcgidrtma.html

JS:   "7".padStart(3, "0")
来源：http://dali.wangshuangyany.cn/Article/details/gtmgynbwct.html

TS:   "7".padStart(3, "0")
来源：http://dali.sysykeji.top/Article/details/gtzhwnehyh.html

Java: String.format("%03d", 7)
来源：http://dali.mhx1999.top/Article/details/gttlsojhpu.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.andypj.xyz/Article/details/gtcwybwben.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.sweek.top/Article/details/gttqhbobox.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.hnxiangtu.top/Article/details/gtkgfecrox.html

[E11] 反转字符串
来源：http://dali.yueranfly.top/Article/details/gtozdicwdd.html

Py:   s[::-1]
来源：http://dali.316326.xyz/Article/details/gtuuttjutn.html

PHP:  strrev($s);
来源：http://dali.iojbl.cn/Article/details/gtvsmteoko.html

JS:   [...s].reverse().join("")
来源：http://dali.xziqi.cn/Article/details/gtcujqlnex.html

TS:   [...s].reverse().join("")
来源：http://dali.cqqwz.cn/Article/details/gtvkedepep.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hysaishi.cn/Article/details/gttrianesh.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuxgorgla.html

Ruby: s.reverse
来源：http://dali.tianlin.xyz/Article/details/gtbfvaaudc.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.chenzaomai.com/Article/details/gthrwxejft.html

[E12] 统计某字符出现次数
来源：http://dali.gaohongyu789.top/Article/details/gtgguzqfqe.html

Py:   s.count("a")
来源：http://dali.jqgufenzy.top/Article/details/gtcfslutys.html

PHP:  substr_count($s, "a");
来源：http://dali.yonumen.top/Article/details/gtktlxugxb.html

JS:   s.split("a").length - 1
来源：http://dali.yongpay.top/Article/details/gttuvxvaza.html

TS:   s.split("a").length - 1
来源：http://dali.cashguo.top/Article/details/gtaxskfwuk.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yvedp.cn/Article/details/gttkmwropk.html

Go:   strings.Count(s, "a")
来源：http://dali.sufxvd.cn/Article/details/gtfwkreyaj.html

Ruby: s.count("a")
来源：http://dali.hammf.cn/Article/details/gttjeznzwb.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yangfankeji.com/Article/details/gtijuvpqrm.html

[E13] 逐字符遍历
来源：http://dali.jyoumei.cn/Article/details/gtocmvttxl.html

Py:   for ch in s: print(ch)
来源：http://dali.tanke756.top/Article/details/gtghuewdvt.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.shangyingyoupin.top/Article/details/gtfrbexvtu.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jiagoushi.top/Article/details/gtdggkvmlj.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sweek.top/Article/details/gtcgjfhhvr.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.pycfn.com/Article/details/gttzsifuzp.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.cheryme.top/Article/details/gtldfzfacr.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yonumen.top/Article/details/gtxadnjlol.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gttjlblmna.html

[E14] URL 编码与 Base64
来源：http://dali.cheryme.top/Article/details/gtxyiyomfs.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gtdblxfkhe.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.tanke756.top/Article/details/gttqqwkfdj.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yongpay.top/Article/details/gtribwrdds.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yonumen.top/Article/details/gtozkoblyb.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.gogol.net.cn/Article/details/gtmbfnlvmg.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jqgufenzy.top/Article/details/gtoolnqxeb.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yuanzhike.top/Article/details/gtiyjlvqop.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yonumen.top/Article/details/gtuwwcjylm.html

[E15] HTML 转义 / 反转义
来源：http://dali.vqdsnc.cn/Article/details/gtibfcuwcc.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jiagoushi.top/Article/details/gtmooxcwks.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtateoltfp.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.bjfxy.top/Article/details/gtqvdlxnmn.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.kuanghao11.cn/Article/details/gtbmhknsfa.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jinyuanbaomall.cn/Article/details/gttyaggjyb.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcyusmqrv.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.haohaochexian.top/Article/details/gtawhcxzjk.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.xuanzx.com/Article/details/gtdlqugjrl.html

[E16] 数字千分位
来源：http://dali.xinyue.icu/Article/details/gtyaiudjyk.html

Py:   f"{1234567:,}"
来源：http://dali.dashuyun.cn/Article/details/gthwuhcjmv.html

PHP:  number_format(1234567);
来源：http://dali.zhiwuduotai.top/Article/details/gtvmknrakl.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jqgufenzy.top/Article/details/gtqdlvwojp.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.kuanghao11.cn/Article/details/gtllfvtxrr.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqdbnuwwq.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.ehwqpu.com/Article/details/gthyodfsay.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.cucudq.cn/Article/details/gtddcxzkmr.html

C#:   1234567.ToString("N0")
来源：http://dali.hammf.cn/Article/details/gthgqatjtc.html

[E17] 首字母大写
来源：http://dali.xylfe.cn/Article/details/gtmydyxiev.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.meibo888.top/Article/details/gtkblrgnlh.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gtqxaxajwn.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hysaishi.cn/Article/details/gtalljhhif.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttcipitao.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhixingplan.top/Article/details/gticryegpa.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.tanke756.top/Article/details/gtbenilqfc.html

Ruby: s.capitalize
来源：http://dali.yvedp.cn/Article/details/gtnhpqhwhq.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.bjfxy.top/Article/details/gtzsiwbrta.html

[E18] 模板占位符替换
来源：http://dali.0kj1m.cn/Article/details/gtpxkeyuwp.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.wangshuangyany.cn/Article/details/gtviaoekye.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.pycfn.com/Article/details/gtofghhlob.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.nwbrower.top/Article/details/gtralhrmev.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbokhfbng.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.guowangkeji.top/Article/details/gtihwtbvdn.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthzvnsmfl.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.cucudq.cn/Article/details/gthrpsclno.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.pycfn.com/Article/details/gtrfmunehy.html

[E19] 多行文本按行拆分
来源：http://dali.dianchejie.cn/Article/details/gtllgkhbir.html

Py:   s.splitlines()
来源：http://dali.chenzaomai.com/Article/details/gtsblehpqt.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hammf.cn/Article/details/gtrlvlqjkm.html

JS:   s.split(/\r?\n/)
来源：http://dali.xuanzx.com/Article/details/gtzbsuzoal.html

TS:   s.split(/\r?\n/)
来源：http://dali.fengsongda.top/Article/details/gtopsyyxqi.html

Java: s.lines().toList()
来源：http://dali.cheryme.top/Article/details/gtwoqohmhu.html

Go:   strings.Split(s, "\n")
来源：http://dali.gogol.net.cn/Article/details/gtitrybjka.html

Ruby: s.lines
来源：http://dali.nwbrower.top/Article/details/gtnflaycms.html

C#:   s.Split('\n')
来源：http://dali.yj20258888.top/Article/details/gttxstqtps.html

[E20] 判断字符串是否为空
来源：http://dali.aibaodan.cn/Article/details/gtuskpipzw.html

Py:   if not s:
来源：http://dali.chenjidiqi.icu/Article/details/gtyrktitej.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yuxming.cn/Article/details/gtuqmlnboe.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtpjpqfdik.html

TS:   if (s === "") {}
来源：http://dali.hysaishi.cn/Article/details/gtxkvwwitc.html

Java: if (s.isEmpty()) {}
来源：http://dali.nanxuanxn.top/Article/details/gtnxyabsts.html

Go:   if s == "" {}
来源：http://dali.yonumen.top/Article/details/gtwwejkkin.html

Ruby: if s.empty?
来源：http://dali.cqqwz.cn/Article/details/gtntzihkvl.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.gogol.net.cn/Article/details/gtjlqivpdm.html

[E21] 超长截断加省略号
来源：http://dali.9152youxi.cn/Article/details/gtdvmhgbqi.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.dianchejie.cn/Article/details/gtcdwylaef.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.havefunace.top/Article/details/gtiofotrwq.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsptojofu.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.aibaodan.cn/Article/details/gtjsfiiesc.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.cucudq.cn/Article/details/gtgtrnkzpp.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cashguo.top/Article/details/gtdeijrvbt.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.dashuyun.cn/Article/details/gtsejdzqcq.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsroytcjf.html

[E22] 字节长度与字符长度
来源：http://dali.c1oappe.top/Article/details/gtfoyckcla.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.redwolf501.top/Article/details/gtydxqurnk.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.haohaochexian.top/Article/details/gtrdlmtazm.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.9152youxi.cn/Article/details/gtamdnzivg.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yuanzhike.top/Article/details/gtdhdjrqmh.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.chenjidiqi.icu/Article/details/gtnxpdlblu.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yuanzhike.top/Article/details/gtwbnhzdny.html

Ruby: s.bytesize;  s.length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtobzffyai.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yj202588.top/Article/details/gtkemsygcs.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtwyxkvcnj.html

F. 文件与目录
来源：http://dali.chenlongwang.top/Article/details/gtyjtfnghe.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtrxsnlydd.html

[F01] 读取整个文件
来源：http://dali.wangshuangyany.cn/Article/details/gtujykfkch.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.gzhubu.top/Article/details/gtoufnfxvv.html

PHP:  file_get_contents("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtnvbytbei.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.andypj.xyz/Article/details/gtryxkqruy.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhongyouzk.top/Article/details/gtkfwaqkfb.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cashguo.top/Article/details/gtbttxocsb.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.xziqi.cn/Article/details/gtqytaxvye.html

Ruby: File.read("a.txt")
来源：http://dali.316326.xyz/Article/details/gtzhdnzeui.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtmntwclzr.html

[F02] 逐行读取文件
来源：http://dali.9152youxi.cn/Article/details/gtbyeokbvf.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.feifeiyinyue.top/Article/details/gtigbrxwfv.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.0kj1m.cn/Article/details/gtaqevbzfu.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jqgfzy.top/Article/details/gtykdwluqr.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gzhubu.top/Article/details/gtrwkznwdr.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gtxsimlxoe.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jlsjyb.cn/Article/details/gtwplelmhi.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yueranfly.top/Article/details/gtvbcmybip.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtallkfxpf.html

[F03] 写入文件（覆盖）
来源：http://dali.nwbrower.top/Article/details/gtrcudsrja.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.kuanghao11.cn/Article/details/gtwfxninbh.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.birdmap.top/Article/details/gtgomjjumn.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ybcxt.top/Article/details/gtymujhemb.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.fzhhl.top/Article/details/gtwdmbiatq.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jinghuilouyu.cn/Article/details/gtdhcjolgq.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.hongshengwenyu.top/Article/details/gtxirrbwiz.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzzkvdikf.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.dianchejie.cn/Article/details/gtklmopsrq.html

[F04] 追加写入文件
来源：http://dali.fengsongda.top/Article/details/gtvcufehtn.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhixingplan.top/Article/details/gtejdwcxye.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yonumen.top/Article/details/gtrbfssowi.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ehwqpu.com/Article/details/gtcfvylgjk.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hongshengwenyu.top/Article/details/gtrnvcqzql.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jinqigfzy.top/Article/details/gtzjfwpyzk.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.guowangkeji.top/Article/details/gtbadmjcik.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.dashuyun.cn/Article/details/gtunracihh.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.pengpengdd.cyou/Article/details/gtfoktnpqb.html

[F05] 判断文件或目录是否存在
来源：http://dali.xylfe.cn/Article/details/gtklvngpdt.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.nwbrower.top/Article/details/gtajulypao.html

PHP:  file_exists("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gtblwmwvbd.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtwxxlluju.html

TS:   fs.existsSync("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtuweceros.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.ybcxt.top/Article/details/gtxwudvdpa.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.xuanzx.com/Article/details/gtppoomeoa.html

Ruby: File.exist?("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtdcahgafx.html

C#:   File.Exists("a.txt")
来源：http://dali.yvedp.cn/Article/details/gteiccqxey.html

[F06] 删除文件
来源：http://dali.mhx1999.top/Article/details/gtkctlxizj.html

Py:   os.remove("a.txt")
来源：http://dali.birdmap.top/Article/details/gtjnclrgvz.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gtgogdnsba.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtakgmysqw.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtzsehkhyj.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hongshengwenyu.top/Article/details/gtanruamuw.html

Go:   os.Remove("a.txt")
来源：http://dali.meibo888.top/Article/details/gtvykgsuuw.html

Ruby: File.delete("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtqfdgsesu.html

C#:   File.Delete("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gtirqnrpdw.html

[F07] 创建目录（含多级）
来源：http://dali.xuetiantiany.cn/Article/details/gtmpkniqwk.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnzvrroes.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzilvhtbw.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenjidiqi.icu/Article/details/gtljylmglo.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cqqwz.cn/Article/details/gtsivhigsy.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hfpthk.cn/Article/details/gtebvajucm.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.mhx1999.top/Article/details/gtdcousxga.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.daria6918.cn/Article/details/gtpzsisiff.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhixingplan.top/Article/details/gtqooyapfb.html

[F08] 遍历目录
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvnqwgntn.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.meibo888.top/Article/details/gtkfkityxm.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.guannengcc.top/Article/details/gtpxnwftjo.html

JS:   fs.readdirSync("dir")
来源：http://dali.shangyingyoupin.top/Article/details/gtfxsarwxs.html

TS:   fs.readdirSync("dir")
来源：http://dali.shangyingyoupin.top/Article/details/gtgktalsjo.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xziqi.cn/Article/details/gteloyxcjj.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.guowangkeji.top/Article/details/gtyxhqpoqq.html

Ruby: Dir.children("dir")
来源：http://dali.yueranfly.top/Article/details/gtcvzzwsmv.html

C#:   Directory.GetFiles("dir")
来源：http://dali.tanke756.top/Article/details/gtwdjjkmot.html

[F09] 获取文件大小
来源：http://dali.yuxming.cn/Article/details/gtoppyqbzh.html

Py:   os.path.getsize("a.txt")
来源：http://dali.cheryme.top/Article/details/gtcflyydey.html

PHP:  filesize("a.txt");
来源：http://dali.yuxming.cn/Article/details/gtblvzlfou.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yongpay.top/Article/details/gtmdafmkvo.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jianghu66.top/Article/details/gtpzelhuit.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.sufxvd.cn/Article/details/gtuizhsxoo.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gtfbryfeeh.html

Ruby: File.size("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gttushfeip.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.kuanghao11.cn/Article/details/gtysubmwlh.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.gotoacloud.top/Article/details/gtojmrplhe.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtcqpwqwwx.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.cashguo.top/Article/details/gtekadukes.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.smart0.xyz/Article/details/gtevzfvshd.html

TS:   path.extname("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtfqktruek.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhengqikj.top/Article/details/gtdokduwyq.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtufnehqrj.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.316326.xyz/Article/details/gtdcacqjtz.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtbogqtdfx.html

[F11] 复制与移动文件
来源：http://dali.yj202588.top/Article/details/gtbwznwgrs.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ydzc1.top/Article/details/gtisufzdtt.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.sxryk.cn/Article/details/gtvvcycvkg.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.daria6918.cn/Article/details/gtpkxoouxw.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtepnpemxb.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.ydzc1.top/Article/details/gtvoivkikp.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.316326.xyz/Article/details/gtlksfeajj.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.9152youxi.cn/Article/details/gtfuxhdwhi.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrnvscngt.html

[F12] CSV 读写
来源：http://dali.gaohongyu789.top/Article/details/gtktoawlgi.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.316326.xyz/Article/details/gtcxyafeot.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.fengsongda.top/Article/details/gthbabfejo.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.ybcxt.top/Article/details/gttlgvzbmo.html

TS:   // 同上
来源：http://dali.yonumen.top/Article/details/gtmsfqqxuv.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhengqikj.top/Article/details/gtbtnalcar.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ywan-chungtsiang.top/Article/details/gtthihoosv.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.wangdashe.top/Article/details/gtuhnygiqd.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.shangyingyoupin.top/Article/details/gtqkbmquck.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtnnrekbjs.html

G. 面向对象
来源：http://dali.cheryme.top/Article/details/gtxhjixegb.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtxalcrbep.html

[G01] 定义类
来源：http://dali.yangfankeji.com/Article/details/gtlkaydjlz.html

Py:   class User: pass
来源：http://dali.sxryk.cn/Article/details/gtcclgzksf.html

PHP:  class User {}
来源：http://dali.cheryme.top/Article/details/gtsdrqdqlb.html

JS:   class User {}
来源：http://dali.hysaishi.cn/Article/details/gtsujyteks.html

TS:   class User { name: string = ""; }
来源：http://dali.cdnleiting.top/Article/details/gtfdtqwcnc.html

Java: class User {}
来源：http://dali.c1oappe.top/Article/details/gtwbgvgflo.html

Go:   type User struct { Name string }
来源：http://dali.ehwqpu.com/Article/details/gtkavsxiix.html

Ruby: class User; end
来源：http://dali.daxiang520.top/Article/details/gtpoxpbpmw.html

C#:   class User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgttkfwbm.html

[G02] 构造函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gthiyyanyp.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hysaishi.cn/Article/details/gtgbuzpsmu.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yuanzhike.top/Article/details/gtdxbuhrya.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.sysykeji.top/Article/details/gtldnuncae.html

TS:   constructor(public name: string) {}
来源：http://dali.jinqigufen.top/Article/details/gtavjwrunu.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhengqikj.top/Article/details/gtwlsfeaqo.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xziqi.cn/Article/details/gtlexojsjn.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.birdmap.top/Article/details/gtjumbpeqh.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yueranfly.top/Article/details/gtvmbxqgiw.html

[G03] 实例属性
来源：http://dali.shuidangran.top/Article/details/gtsrjumxor.html

Py:   self.name = "x"
来源：http://dali.sweek.top/Article/details/gtavvagvmz.html

PHP:  public string $name = "x";
来源：http://dali.guowangkeji.top/Article/details/gtcyxvxajd.html

JS:   this.name = "x";
来源：http://dali.yonumen.top/Article/details/gtthnbtrti.html

TS:   name: string = "x";
来源：http://dali.andypj.xyz/Article/details/gtddhgpvuf.html

Java: private String name;
来源：http://dali.bjfxy.top/Article/details/gtcihyxmtt.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.gotoacloud.top/Article/details/gtxoiloelx.html

Ruby: @name = "x"
来源：http://dali.birdmap.top/Article/details/gtjbbehgqk.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.shangyingyoupin.top/Article/details/gtdzsacgqg.html

[G04] 定义方法
来源：http://dali.hnxiangtu.top/Article/details/gtofbkgecm.html

Py:   def greet(self): return self.name
来源：http://dali.shanyushiyangkeji.top/Article/details/gtixblaaoz.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.gogol.net.cn/Article/details/gtpniwtcpf.html

JS:   greet() { return this.name; }
来源：http://dali.hammf.cn/Article/details/gtouhnifkg.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhixingplan.top/Article/details/gtrmbmoswn.html

Java: String greet() { return name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqprplsvq.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hywenlv.cn/Article/details/gtqamgtcjb.html

Ruby: def greet; @name; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdcdxrdpy.html

C#:   public string Greet() => Name;
来源：http://dali.shzxlz.cn/Article/details/gtowsbfpvl.html

[G05] 继承
来源：http://dali.snrcjt.cn/Article/details/gttdiofymp.html

Py:   class Admin(User): pass
来源：http://dali.jiagoushi.top/Article/details/gtjgvgibsp.html

PHP:  class Admin extends User {}
来源：http://dali.sxryk.cn/Article/details/gtcuxwlwed.html

JS:   class Admin extends User {}
来源：http://dali.jlsjyb.cn/Article/details/gttbqrpkze.html

TS:   class Admin extends User {}
来源：http://dali.bjfxy.top/Article/details/gtrsxbbngb.html

Java: class Admin extends User {}
来源：http://dali.sweek.top/Article/details/gteurnumcu.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hnqzz.top/Article/details/gtpcjcbqdd.html

Ruby: class Admin < User; end
来源：http://dali.hfpthk.cn/Article/details/gtntulxrqp.html

C#:   class Admin : User {}
来源：http://dali.jinqigfzy.top/Article/details/gtlbqkvkea.html

[G06] 重写方法
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoduijmri.html

Py:   def greet(self): return "admin"
来源：http://dali.pengpengdd.cyou/Article/details/gtnxxetvii.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.tanke756.top/Article/details/gtldcygczw.html

JS:   greet() { return "admin"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtpsggyygb.html

TS:   greet(): string { return "admin"; }
来源：http://dali.guowangkeji.top/Article/details/gtdidxbvgb.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.cheryme.top/Article/details/gtangirobs.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.meibo888.top/Article/details/gtchlhitss.html

Ruby: def greet; "admin"; end
来源：http://dali.fengsongda.top/Article/details/gtzyjphezy.html

C#:   public override string Greet() => "admin";
来源：http://dali.chenjidiqi.icu/Article/details/gtlcwgoqkg.html

[G07] 调用父类方法
来源：http://dali.hnqzz.top/Article/details/gtppsnrnhf.html

Py:   super().greet()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnnmhruji.html

PHP:  parent::greet();
来源：http://dali.jianghu66.top/Article/details/gtowsdzxgt.html

JS:   super.greet();
来源：http://dali.feifeiyinyue.top/Article/details/gthjbhwait.html

TS:   super.greet();
来源：http://dali.fzhhl.top/Article/details/gtysrxbvhq.html

Java: super.greet();
来源：http://dali.shanyushiyangtech.top/Article/details/gtzmdszpox.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.chenjidiqi.icu/Article/details/gttvyycqum.html


<!-- 参考信息 -->