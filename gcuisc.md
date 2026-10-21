代发 wailian999

JS:   [...s].reverse().join("")
来源：http://dali.yuanzhike.top/Article/details/gtoqsvjesh.html

TS:   [...s].reverse().join("")
来源：http://dali.xinyue.icu/Article/details/gtbuptbbyk.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.guowangkeji.top/Article/details/gtwcvzmcgh.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.tian-w.cn/Article/details/gtxevvqczx.html

Ruby: s.reverse
来源：http://dali.xuanzx.com/Article/details/gtllvfizgj.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.svipenyu.cn/Article/details/gtssyylwzx.html

[E12] 统计某字符出现次数
来源：http://dali.birdmap.top/Article/details/gteamitmyl.html

Py:   s.count("a")
来源：http://dali.nanxinkj.top/Article/details/gthwvmrizt.html

PHP:  substr_count($s, "a");
来源：http://dali.mhx1999.top/Article/details/gtaaogmbpv.html

JS:   s.split("a").length - 1
来源：http://dali.ppjwa.cn/Article/details/gtypjidgtw.html

TS:   s.split("a").length - 1
来源：http://dali.xylfe.cn/Article/details/gtaspcakfr.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yongpay.top/Article/details/gtaxnqwrgt.html

Go:   strings.Count(s, "a")
来源：http://dali.mhx1999.top/Article/details/gtxoukdslv.html

Ruby: s.count("a")
来源：http://dali.gaohongyu789.top/Article/details/gtqdeamsmb.html

C#:   s.Count(c => c == 'a')
来源：http://dali.quarkkingdee.top/Article/details/gtjgmnkkdi.html

[E13] 逐字符遍历
来源：http://dali.9152youxi.cn/Article/details/gtmceroaxu.html

Py:   for ch in s: print(ch)
来源：http://dali.cheryme.top/Article/details/gtabogsqyc.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.gotoacloud.top/Article/details/gthfnkctqv.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuzwtfwsk.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.chenlongwang.top/Article/details/gtntuaoyma.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.aizwys.cn/Article/details/gtmiaturgd.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.smart0.xyz/Article/details/gtfakvwyzn.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.xziqi.cn/Article/details/gtyqdjmvzl.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jqgufenzy.top/Article/details/gtygewlyen.html

[E14] URL 编码与 Base64
来源：http://dali.haohaochexian.top/Article/details/gttvgiwyol.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.mhx1999.top/Article/details/gtornimecn.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.shzxlz.cn/Article/details/gtvawtmztm.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.meibo888.top/Article/details/gtipvmzbio.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.ppjwa.cn/Article/details/gtfjizmszw.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zdqjudy.top/Article/details/gteraxmrfw.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.gotoacloud.top/Article/details/gthhnxfcec.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.ywan-chungtsiang.top/Article/details/gthwwmubvu.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hammf.cn/Article/details/gtyvksvrpi.html

[E15] HTML 转义 / 反转义
来源：http://dali.sweek.top/Article/details/gtdjrzkokq.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.bjfxy.top/Article/details/gtsgprsqel.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.guannengcc.top/Article/details/gtcpwxdozz.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.chenzaomai.com/Article/details/gtadedgxfk.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yuanzhike.top/Article/details/gteaolhmgh.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.chenjidiqi.icu/Article/details/gtthgjnioi.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jinqigufen.top/Article/details/gteweokxjq.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.316326.xyz/Article/details/gtvnvshcya.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.daria6918.cn/Article/details/gtzkiftpxx.html

[E16] 数字千分位
来源：http://dali.ivvv.top/Article/details/gtecxqvoap.html

Py:   f"{1234567:,}"
来源：http://dali.kuanghao11.cn/Article/details/gtzhyxffdh.html

PHP:  number_format(1234567);
来源：http://dali.mhx1999.top/Article/details/gtbcqwsavv.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdvavthma.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jqgufenzy.top/Article/details/gtyymtazuu.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.shanyushiyangtech.top/Article/details/gtucqwjenk.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.birdmap.top/Article/details/gteojiuygf.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yongpay.top/Article/details/gtbqfawqqh.html

C#:   1234567.ToString("N0")
来源：http://dali.haohaochexian.top/Article/details/gtbwbcyizh.html

[E17] 首字母大写
来源：http://dali.tanke756.top/Article/details/gtxnzujrfm.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yuxming.cn/Article/details/gtohxanmce.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.xziqi.cn/Article/details/gtqbhgxplx.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenzaomai.com/Article/details/gtfhbsqubj.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhongyouzk.top/Article/details/gtlkwqczwn.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jinqigfzy.top/Article/details/gtyemukojs.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.ehwqpu.com/Article/details/gthcpbflsk.html

Ruby: s.capitalize
来源：http://dali.yj202588.top/Article/details/gthuiotwmm.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.shangyingyoupin.top/Article/details/gtwrzvqpbt.html

[E18] 模板占位符替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gttgokqxgy.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.snrcjt.cn/Article/details/gtehcgvfcd.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.gogol.net.cn/Article/details/gtezxpjrmp.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.c1oappe.top/Article/details/gtnegvspzz.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhixingplan.top/Article/details/gtwauulqzh.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yueranfly.top/Article/details/gtcidyspih.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.cheryme.top/Article/details/gtflhjwbaj.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.316326.xyz/Article/details/gtoycjyalr.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.gotoacloud.top/Article/details/gtlqvijyeh.html

[E19] 多行文本按行拆分
来源：http://dali.sweek.top/Article/details/gtyflbhhot.html

Py:   s.splitlines()
来源：http://dali.ydzc1.top/Article/details/gtwsszefdf.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yvedp.cn/Article/details/gtyjhidork.html

JS:   s.split(/\r?\n/)
来源：http://dali.hywenlv.cn/Article/details/gtabtamfbj.html

TS:   s.split(/\r?\n/)
来源：http://dali.havefunace.top/Article/details/gtmibkiqzf.html

Java: s.lines().toList()
来源：http://dali.smart0.xyz/Article/details/gtpmdweoyd.html

Go:   strings.Split(s, "\n")
来源：http://dali.jyoumei.cn/Article/details/gtzyujuokd.html

Ruby: s.lines
来源：http://dali.gotoacloud.top/Article/details/gttilaekbb.html

C#:   s.Split('\n')
来源：http://dali.pengpengdd.cyou/Article/details/gtjcjxkfxg.html

[E20] 判断字符串是否为空
来源：http://dali.shanyushiyangtech.top/Article/details/gtximnkskw.html

Py:   if not s:
来源：http://dali.iojbl.cn/Article/details/gtcqmuukhd.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jqgufenzy.top/Article/details/gtbbislvul.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yvedp.cn/Article/details/gtnfftfmoi.html

TS:   if (s === "") {}
来源：http://dali.yanxiufei.cn/Article/details/gtdxsmyvwj.html

Java: if (s.isEmpty()) {}
来源：http://dali.gzhubu.top/Article/details/gtkdfholxq.html

Go:   if s == "" {}
来源：http://dali.shuidangran.top/Article/details/gtqublqcgr.html

Ruby: if s.empty?
来源：http://dali.gaohongyu789.top/Article/details/gtfmfffdou.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.gaohongyu789.top/Article/details/gtrzlvowft.html

[E21] 超长截断加省略号
来源：http://dali.wangdashe.top/Article/details/gtfrtnkufy.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yueranfly.top/Article/details/gtnocpnbae.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhoulong.xyz/Article/details/gtsliuzunu.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gtroastvkm.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.tianlin.xyz/Article/details/gtyrscgjpg.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.feifeiyinyue.top/Article/details/gtbrcmjqlr.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.meibo888.top/Article/details/gtwsvvglam.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.meibo888.top/Article/details/gtqpwvobfp.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.gaohongyu789.top/Article/details/gtigqqrvqb.html

[E22] 字节长度与字符长度
来源：http://dali.daria6918.cn/Article/details/gtdbxogkor.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhixingplan.top/Article/details/gtxvzzqsaj.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.tian-w.cn/Article/details/gtqlcdbpdm.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zycfv.cn/Article/details/gtvayhpraj.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyekizale.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.nanxuanxn.top/Article/details/gtwkzhqaws.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.svipenyu.cn/Article/details/gtccgxxeqo.html

Ruby: s.bytesize;  s.length
来源：http://dali.svipenyu.cn/Article/details/gtkmniicwp.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.nwbrower.top/Article/details/gtndjzxdvs.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtwzsgyucb.html

F. 文件与目录
来源：http://dali.zycfv.cn/Article/details/gtivuqdsry.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtpwnppjll.html

[F01] 读取整个文件
来源：http://dali.gaohongyu789.top/Article/details/gtpigryzyl.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.chenzaomai.com/Article/details/gtboqshedy.html

PHP:  file_get_contents("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqwwyalgh.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.quarkkingdee.top/Article/details/gtygrrovnl.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.chenlongwang.top/Article/details/gtfjhtohtc.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cheryme.top/Article/details/gtvgffnfmf.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.sxryk.cn/Article/details/gtsubmptat.html

Ruby: File.read("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtxgjiggdk.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.bjfxy.top/Article/details/gtbscfdkqg.html

[F02] 逐行读取文件
来源：http://dali.jqgfzy.top/Article/details/gtimlnhqub.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.mhx1999.top/Article/details/gtbhkixzkt.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.cashguo.top/Article/details/gtgdtimpgt.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.aibaodan.cn/Article/details/gthrtzaqim.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnzocsxqa.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhengqikj.top/Article/details/gthwdmccei.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.mhx1999.top/Article/details/gtgwobpcqi.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.shangyingyoupin.top/Article/details/gtyimdelrh.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yuxming.cn/Article/details/gtowmgfcyl.html

[F03] 写入文件（覆盖）
来源：http://dali.nanxinkj.top/Article/details/gtjzzolemq.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjzwhdygt.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yj20258.top/Article/details/gtwqnlxxwh.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.wangdashe.top/Article/details/gtqszijzay.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.dashuyun.cn/Article/details/gtthwrcraa.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.c1oappe.top/Article/details/gtekrnqrzw.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.birdmap.top/Article/details/gtquiaetca.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yueranfly.top/Article/details/gtvdqiotik.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.feifeiyinyue.top/Article/details/gtgzhcezwq.html

[F04] 追加写入文件
来源：http://dali.yj20258888.top/Article/details/gtjeutoxuc.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.bjfxy.top/Article/details/gtmwolsyaw.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.tanke756.top/Article/details/gtjitvucgh.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hammf.cn/Article/details/gtbcmllans.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ybcxt.top/Article/details/gtpurweqgh.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.shanyushiyangtech.top/Article/details/gtuubuxtme.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xinyue.icu/Article/details/gtwvnuixro.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.c1oappe.top/Article/details/gtbkxrrmsl.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.dianchejie.cn/Article/details/gtskzobpds.html

[F05] 判断文件或目录是否存在
来源：http://dali.9152youxi.cn/Article/details/gtivbsedtw.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.cheryme.top/Article/details/gtpygjyxpf.html

PHP:  file_exists("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gtumtafyxi.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtidljtvbx.html

TS:   fs.existsSync("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gthnuhcsdp.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hfpthk.cn/Article/details/gtjqawqrob.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.nanxinkj.top/Article/details/gtxsvefcoa.html

Ruby: File.exist?("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtziaoxkgc.html

C#:   File.Exists("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtwzuteiyq.html

[F06] 删除文件
来源：http://dali.yj202588.top/Article/details/gtslnumnfa.html

Py:   os.remove("a.txt")
来源：http://dali.yj20258.top/Article/details/gttoeyyfge.html

PHP:  unlink("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gthywforor.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xuanzx.com/Article/details/gttbqzztky.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtpixrwscf.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.cdnleiting.top/Article/details/gtpyyaqpbr.html

Go:   os.Remove("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtxofzpcxu.html

Ruby: File.delete("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtbeusmlxe.html

C#:   File.Delete("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrtcdwpcq.html

[F07] 创建目录（含多级）
来源：http://dali.cashguo.top/Article/details/gtdrdpgpbp.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.316326.xyz/Article/details/gtxacbtrgp.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhongyouzk.top/Article/details/gtntjfrdns.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinghuilouyu.cn/Article/details/gtjhgawsum.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hysaishi.cn/Article/details/gtjdekjuce.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hywenlv.cn/Article/details/gttvaoywxs.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gtpjtgphib.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.dianchejie.cn/Article/details/gtsxxtzjzk.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.nanxuanxn.top/Article/details/gtsqfmfgwu.html

[F08] 遍历目录
来源：http://dali.jyoumei.cn/Article/details/gtnyydutah.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hfpthk.cn/Article/details/gtuzdupavi.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gtzvznvaqp.html

JS:   fs.readdirSync("dir")
来源：http://dali.dashuyun.cn/Article/details/gttktdhjja.html

TS:   fs.readdirSync("dir")
来源：http://dali.hywenlv.cn/Article/details/gtqyirfevf.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.aizwys.cn/Article/details/gtvwouvuzn.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.gotoacloud.top/Article/details/gtkniowqto.html

Ruby: Dir.children("dir")
来源：http://dali.wangshuangyany.cn/Article/details/gtgegvzhzm.html

C#:   Directory.GetFiles("dir")
来源：http://dali.fengsongda.top/Article/details/gtebnlajix.html

[F09] 获取文件大小
来源：http://dali.yongpay.top/Article/details/gtxrfvwqmf.html

Py:   os.path.getsize("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gthuwrfofm.html

PHP:  filesize("a.txt");
来源：http://dali.xuanzx.com/Article/details/gtqkwueroi.html

JS:   fs.statSync("a.txt").size
来源：http://dali.sysykeji.top/Article/details/gtxdrtjdka.html

TS:   fs.statSync("a.txt").size
来源：http://dali.wangdashe.top/Article/details/gtaxxxmnqu.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.chenjidiqi.icu/Article/details/gtqrvqqkmq.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.dianchejie.cn/Article/details/gtcxradrff.html

Ruby: File.size("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtmtbeozmj.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtagmikshw.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gtvforjodg.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtrugclori.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zycfv.cn/Article/details/gtgdarckqk.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.gzhubu.top/Article/details/gtxtrqwobw.html

TS:   path.extname("a.txt")
来源：http://dali.ybcxt.top/Article/details/gteoeqrnkp.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yj202588.top/Article/details/gtnqrxuxhh.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.andypj.xyz/Article/details/gtphderbia.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtejgjuvte.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtdynrmdmd.html

[F11] 复制与移动文件
来源：http://dali.dianchejie.cn/Article/details/gtjbddbhlh.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.aizwys.cn/Article/details/gtacuzzdue.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.cdnleiting.top/Article/details/gttuteyygq.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yvedp.cn/Article/details/gtqbdjjyme.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtiotvgrhs.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.haohaochexian.top/Article/details/gtdptwaxwz.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jqgfzy.top/Article/details/gtwbticwcr.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ydzc1.top/Article/details/gtrliericc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.birdmap.top/Article/details/gtwhfziurw.html

[F12] CSV 读写
来源：http://dali.ybcxt.top/Article/details/gtxqunzgfk.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkktscpsz.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.pycfn.com/Article/details/gtxijfxsbw.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.cucudq.cn/Article/details/gtoalgbvqp.html

TS:   // 同上
来源：http://dali.ybcxt.top/Article/details/gtzvrxklpa.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.fengsongda.top/Article/details/gtcuglzklv.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hywenlv.cn/Article/details/gtsjylyxlo.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ivvv.top/Article/details/gthluwrukb.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.sxryk.cn/Article/details/gtwxrkxccq.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gttwjuxhgn.html

G. 面向对象
来源：http://dali.fzhhl.top/Article/details/gtvnilifyl.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtojzrjbpi.html

[G01] 定义类
来源：http://dali.hnqzz.top/Article/details/gtpvgoqxhs.html

Py:   class User: pass
来源：http://dali.svipenyu.cn/Article/details/gtxtcyalxa.html

PHP:  class User {}
来源：http://dali.iojbl.cn/Article/details/gtzfwcxkeo.html

JS:   class User {}
来源：http://dali.jianghu66.top/Article/details/gtymaapirx.html

TS:   class User { name: string = ""; }
来源：http://dali.zdqjudy.top/Article/details/gthyjdonej.html

Java: class User {}
来源：http://dali.zycfv.cn/Article/details/gthnrfgwgz.html

Go:   type User struct { Name string }
来源：http://dali.9152youxi.cn/Article/details/gtypldrfgt.html

Ruby: class User; end
来源：http://dali.yueranfly.top/Article/details/gtiiyfkljv.html

C#:   class User {}
来源：http://dali.hywenlv.cn/Article/details/gtuhlmrdim.html

[G02] 构造函数
来源：http://dali.zhiwuduotai.top/Article/details/gtmvbqgznr.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jianghu66.top/Article/details/gtyoleczfk.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtxzmuazju.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yj20258888.top/Article/details/gtvlnvktyp.html

TS:   constructor(public name: string) {}
来源：http://dali.aibaodan.cn/Article/details/gtziggmmjg.html

Java: User(String name) { this.name = name; }
来源：http://dali.aibaodan.cn/Article/details/gtqtfjribt.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.svipenyu.cn/Article/details/gtaeajcmuv.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.smart0.xyz/Article/details/gtfvllcxpy.html

C#:   public User(string name) { Name = name; }
来源：http://dali.gotoacloud.top/Article/details/gtdydiwtxd.html

[G03] 实例属性
来源：http://dali.xylfe.cn/Article/details/gtjjymradm.html

Py:   self.name = "x"
来源：http://dali.haohaochexian.top/Article/details/gtgdksfnfh.html

PHP:  public string $name = "x";
来源：http://dali.xinyue.icu/Article/details/gtenirbmwm.html

JS:   this.name = "x";
来源：http://dali.ivvv.top/Article/details/gtenrltfux.html

TS:   name: string = "x";
来源：http://dali.tian-w.cn/Article/details/gtqqtkufud.html

Java: private String name;
来源：http://dali.zhengqikj.top/Article/details/gtfppovrsw.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.daxiang520.top/Article/details/gtercntbry.html

Ruby: @name = "x"
来源：http://dali.zdqjudy.top/Article/details/gticgyepdx.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhoulong.xyz/Article/details/gtqtloyphj.html

[G04] 定义方法
来源：http://dali.cheryme.top/Article/details/gtasftxaxi.html

Py:   def greet(self): return self.name
来源：http://dali.hfpthk.cn/Article/details/gtcdpubrcl.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.haohaochexian.top/Article/details/gtxkrohvjl.html

JS:   greet() { return this.name; }
来源：http://dali.jianghu66.top/Article/details/gtzntzgrou.html

TS:   greet(): string { return this.name; }
来源：http://dali.sxryk.cn/Article/details/gtlumgujei.html

Java: String greet() { return name; }
来源：http://dali.tanke756.top/Article/details/gttvamorvp.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yj20258.top/Article/details/gtwjmmpzgm.html

Ruby: def greet; @name; end
来源：http://dali.iojbl.cn/Article/details/gthoigtwoc.html

C#:   public string Greet() => Name;
来源：http://dali.shanyushiyangkeji.top/Article/details/gttgykuspr.html

[G05] 继承
来源：http://dali.jqgufenzy.top/Article/details/gtvonllpvz.html

Py:   class Admin(User): pass
来源：http://dali.cheryme.top/Article/details/gtaoecyszb.html

PHP:  class Admin extends User {}
来源：http://dali.smart0.xyz/Article/details/gtkixxebtw.html

JS:   class Admin extends User {}
来源：http://dali.chenzaomai.com/Article/details/gtjlcxnvwm.html

TS:   class Admin extends User {}
来源：http://dali.xinyue.icu/Article/details/gtpmpzbwvz.html

Java: class Admin extends User {}
来源：http://dali.zhixingplan.top/Article/details/gtjkrqlsrv.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhoulong.xyz/Article/details/gtrwaoeatr.html

Ruby: class Admin < User; end
来源：http://dali.xuanzx.com/Article/details/gtxijujyxk.html

C#:   class Admin : User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtgvkqozmv.html

[G06] 重写方法
来源：http://dali.tian-w.cn/Article/details/gtphzjbbat.html

Py:   def greet(self): return "admin"
来源：http://dali.zdqjudy.top/Article/details/gtwvfsqidy.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jqgufenzy.top/Article/details/gtemjfwaha.html

JS:   greet() { return "admin"; }
来源：http://dali.dashuyun.cn/Article/details/gtqrbtxrlk.html

TS:   greet(): string { return "admin"; }
来源：http://dali.gogol.net.cn/Article/details/gtpcgbwjrg.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtorqjzjof.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jiagoushi.top/Article/details/gtjpfanzmo.html

Ruby: def greet; "admin"; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtawnnwzsf.html

C#:   public override string Greet() => "admin";
来源：http://dali.nanxuanxn.top/Article/details/gttjrohgwe.html

[G07] 调用父类方法
来源：http://dali.cashguo.top/Article/details/gtryutuzmh.html

Py:   super().greet()
来源：http://dali.c1oappe.top/Article/details/gtoocoyffs.html

PHP:  parent::greet();
来源：http://dali.sufxvd.cn/Article/details/gtbwxijdxi.html

JS:   super.greet();
来源：http://dali.wangshuangyany.cn/Article/details/gtpgzyuupz.html

TS:   super.greet();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkexuvxij.html

Java: super.greet();
来源：http://dali.yvedp.cn/Article/details/gtzznqazuh.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jinqigfzy.top/Article/details/gthzfrjlfd.html

Ruby: super
来源：http://dali.hywenlv.cn/Article/details/gtabeyluxp.html

C#:   base.Greet();
来源：http://dali.yanxiufei.cn/Article/details/gtdwucffmw.html

[G08] 静态方法与属性
来源：http://dali.chenjidiqi.icu/Article/details/gtkzewpgkj.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hfpthk.cn/Article/details/gtdommdsqi.html

PHP:  public static function f() {}
来源：http://dali.xuetiantiany.cn/Article/details/gtrkesgfeb.html

JS:   static f() {}
来源：http://dali.jiagoushi.top/Article/details/gtbqhzbrjn.html

TS:   static f(): void {}
来源：http://dali.yonumen.top/Article/details/gtqznaxfvs.html

Java: static void f() {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtrxjfwkuj.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhoulong.xyz/Article/details/gtzfcdtsen.html

Ruby: def self.f; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtigsygdpj.html

C#:   public static void F() {}
来源：http://dali.xuetiantiany.cn/Article/details/gtgsodycqq.html

[G09] 接口 / 抽象类
来源：http://dali.jlsjyb.cn/Article/details/gtuyjurwty.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xziqi.cn/Article/details/gttaladjie.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtzdqivpvn.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaxaswepx.html

TS:   interface Shape { area(): number; }
来源：http://dali.bjfxy.top/Article/details/gtjmwtmlmn.html

Java: interface Shape { double area(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtzdstbabi.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.c1oappe.top/Article/details/gtcxcoknev.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jiagoushi.top/Article/details/gtyrdnylli.html

C#:   interface IShape { double Area(); }
来源：http://dali.yj202588.top/Article/details/gtztwuxllc.html


<!-- 参考信息 -->