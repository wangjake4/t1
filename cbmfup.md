代发 wailian999

[E10] 左侧补零 / 定长填充
来源：http://dali.aizwys.cn/Article/details/gtsedxgxeb.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yangfankeji.com/Article/details/gtlhlkfzrz.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhengqikj.top/Article/details/gtvivahfyf.html

JS:   "7".padStart(3, "0")
来源：http://dali.mhx1999.top/Article/details/gtwaktoqsg.html

TS:   "7".padStart(3, "0")
来源：http://dali.ybcxt.top/Article/details/gthayllgsz.html

Java: String.format("%03d", 7)
来源：http://dali.0kj1m.cn/Article/details/gtuggbwevq.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhongyouzk.top/Article/details/gtrcelncbg.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.dianchejie.cn/Article/details/gtwjcyunni.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yuxming.cn/Article/details/gtumhvbwkw.html

[E11] 反转字符串
来源：http://dali.hywenlv.cn/Article/details/gtebmrgonx.html

Py:   s[::-1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtilzkukpr.html

PHP:  strrev($s);
来源：http://dali.cheryme.top/Article/details/gtwbgfeaan.html

JS:   [...s].reverse().join("")
来源：http://dali.dianchejie.cn/Article/details/gtydsbjvvc.html

TS:   [...s].reverse().join("")
来源：http://dali.quarkkingdee.top/Article/details/gtcqckgryn.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.chenlongwang.top/Article/details/gtfrpncvbq.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.xuanzx.com/Article/details/gtwudwwogp.html

Ruby: s.reverse
来源：http://dali.hongshengwenyu.top/Article/details/gtklrhyepa.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yongpay.top/Article/details/gtpluekrxh.html

[E12] 统计某字符出现次数
来源：http://dali.yj20258.top/Article/details/gtgmdlllwd.html

Py:   s.count("a")
来源：http://dali.tian-w.cn/Article/details/gtcdmzwbeg.html

PHP:  substr_count($s, "a");
来源：http://dali.zhixingplan.top/Article/details/gtropezrsl.html

JS:   s.split("a").length - 1
来源：http://dali.ybcxt.top/Article/details/gtcikpqudq.html

TS:   s.split("a").length - 1
来源：http://dali.zhoulong.xyz/Article/details/gtrxgtqxrh.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.sysykeji.top/Article/details/gtgymzshvu.html

Go:   strings.Count(s, "a")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkjfmaube.html

Ruby: s.count("a")
来源：http://dali.jiagoushi.top/Article/details/gtmlguctxm.html

C#:   s.Count(c => c == 'a')
来源：http://dali.cheryme.top/Article/details/gtlzvabctf.html

[E13] 逐字符遍历
来源：http://dali.ivvv.top/Article/details/gtucbgspbg.html

Py:   for ch in s: print(ch)
来源：http://dali.yvedp.cn/Article/details/gtfmvarmrn.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yueranfly.top/Article/details/gtwrgezvaq.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.iojbl.cn/Article/details/gtudvpizvz.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yvedp.cn/Article/details/gtvqjqzrcb.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zycfv.cn/Article/details/gtctilikdo.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jyoumei.cn/Article/details/gtlvmokltb.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.sweek.top/Article/details/gtwfqngzcp.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.ybcxt.top/Article/details/gtwksnaivd.html

[E14] URL 编码与 Base64
来源：http://dali.sufxvd.cn/Article/details/gtlpdsvqul.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hnqzz.top/Article/details/gtiffnyztc.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.9152youxi.cn/Article/details/gtkpfmtxyg.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yj20258888.top/Article/details/gtzhklmtpt.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yvedp.cn/Article/details/gtspilyrho.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.haohaochexian.top/Article/details/gtrkvobdzu.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhongyouzk.top/Article/details/gtllhtikjn.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jinqigfzy.top/Article/details/gtcazfpuqi.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yuxming.cn/Article/details/gtmvjsaffg.html

[E15] HTML 转义 / 反转义
来源：http://dali.hywenlv.cn/Article/details/gtayqsghsm.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhixingplan.top/Article/details/gtuxdtffxe.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hnqzz.top/Article/details/gtvcxywmtp.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hnqzz.top/Article/details/gtemclqpvl.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.wangshuangyany.cn/Article/details/gtocfovdgn.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.haohaochexian.top/Article/details/gteesxnska.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.ybcxt.top/Article/details/gtcarsqzua.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xinyue.icu/Article/details/gtouhjpvyh.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.chenlongwang.top/Article/details/gtwueyegdp.html

[E16] 数字千分位
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsagemloh.html

Py:   f"{1234567:,}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmpitlbhq.html

PHP:  number_format(1234567);
来源：http://dali.yvedp.cn/Article/details/gtazpkzdva.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.hfpthk.cn/Article/details/gtasqikjfy.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.hongshengwenyu.top/Article/details/gtafqipvkc.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.fengsongda.top/Article/details/gtswdheyqi.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yj20258888.top/Article/details/gtygfpunqq.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.cucudq.cn/Article/details/gthzumsrnu.html

C#:   1234567.ToString("N0")
来源：http://dali.chenlongwang.top/Article/details/gtsnutfqwu.html

[E17] 首字母大写
来源：http://dali.yvedp.cn/Article/details/gtztmncwel.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.quarkkingdee.top/Article/details/gtucraxvxj.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hysaishi.cn/Article/details/gtxrgyniai.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cqqwz.cn/Article/details/gtazvzsenk.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ivvv.top/Article/details/gtbzriiqhg.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.quarkkingdee.top/Article/details/gtqqvsbykn.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.xuetiantiany.cn/Article/details/gtouuawpka.html

Ruby: s.capitalize
来源：http://dali.mhx1999.top/Article/details/gtwtekxrjw.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.hywenlv.cn/Article/details/gtivpfvvqg.html

[E18] 模板占位符替换
来源：http://dali.ppjwa.cn/Article/details/gtfiftoups.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ivvv.top/Article/details/gtsjtvjftv.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkylnsqds.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhoulong.xyz/Article/details/gtfcgslwkw.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yueranfly.top/Article/details/gtjkbgbyat.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.tian-w.cn/Article/details/gtmdyzoqor.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yangfankeji.com/Article/details/gtsqtehooj.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.hnqzz.top/Article/details/gtxraxhkyz.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.hammf.cn/Article/details/gtdgkcvwsm.html

[E19] 多行文本按行拆分
来源：http://dali.jqgufenzy.top/Article/details/gtimdayxge.html

Py:   s.splitlines()
来源：http://dali.feifeiyinyue.top/Article/details/gtllhoyqqo.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.c1oappe.top/Article/details/gtcdnhvscf.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtletmnzcs.html

TS:   s.split(/\r?\n/)
来源：http://dali.xuetiantiany.cn/Article/details/gtcjqeoxln.html

Java: s.lines().toList()
来源：http://dali.yvedp.cn/Article/details/gtunkkxkcy.html

Go:   strings.Split(s, "\n")
来源：http://dali.birdmap.top/Article/details/gtwkdysnjt.html

Ruby: s.lines
来源：http://dali.gogol.net.cn/Article/details/gtncwyhajf.html

C#:   s.Split('\n')
来源：http://dali.hammf.cn/Article/details/gtawsypgde.html

[E20] 判断字符串是否为空
来源：http://dali.yuxming.cn/Article/details/gtzrwshwjt.html

Py:   if not s:
来源：http://dali.yj20258.top/Article/details/gtbylotoga.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.chenzaomai.com/Article/details/gtofkxhuox.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hnqzz.top/Article/details/gtxdtpldva.html

TS:   if (s === "") {}
来源：http://dali.gaohongyu789.top/Article/details/gtutwwbivo.html

Java: if (s.isEmpty()) {}
来源：http://dali.xuanzx.com/Article/details/gtqxupdnra.html

Go:   if s == "" {}
来源：http://dali.yonumen.top/Article/details/gtofinnbyc.html

Ruby: if s.empty?
来源：http://dali.zdqjudy.top/Article/details/gtolatysnk.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.cheryme.top/Article/details/gtmlbgktcy.html

[E21] 超长截断加省略号
来源：http://dali.sxryk.cn/Article/details/gtdmpnedad.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.gzhubu.top/Article/details/gtnzonyrcg.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.dashuyun.cn/Article/details/gtphfolssp.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gtwuoedtvy.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zdqjudy.top/Article/details/gtljzplbok.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.chenlongwang.top/Article/details/gttvmnrtkq.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.haohaochexian.top/Article/details/gttvcukzdq.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xuetiantiany.cn/Article/details/gtsfdedice.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.tian-w.cn/Article/details/gthjvuqtxj.html

[E22] 字节长度与字符长度
来源：http://dali.shanyushiyangtech.top/Article/details/gtvskvvayh.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yongpay.top/Article/details/gtfdzhafuk.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ivvv.top/Article/details/gtonpnahmj.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.tianlin.xyz/Article/details/gtkdlxdxgz.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtehdxpnoj.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.0kj1m.cn/Article/details/gtkflzjxon.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.chenjidiqi.icu/Article/details/gtcipexwbj.html

Ruby: s.bytesize;  s.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqrhkwinf.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.cashguo.top/Article/details/gtgtvhpzqr.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtxmivhnvk.html

F. 文件与目录
来源：http://dali.yangfankeji.com/Article/details/gtghpvgbps.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtnornpjmd.html

[F01] 读取整个文件
来源：http://dali.ppjwa.cn/Article/details/gtngbgsyfi.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.haohaochexian.top/Article/details/gtxlgncxik.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gtpfxnvbdc.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.dashuyun.cn/Article/details/gtbyuhzezp.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhixingplan.top/Article/details/gtytctemfp.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cashguo.top/Article/details/gtanmpqbfb.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hnqzz.top/Article/details/gttmwqhfod.html

Ruby: File.read("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtbopezggv.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.sysykeji.top/Article/details/gtacoyhbut.html

[F02] 逐行读取文件
来源：http://dali.jinqigufen.top/Article/details/gtivssaugd.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.shanyushiyangtech.top/Article/details/gtehdeyaje.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtwobwgcfb.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.daxiang520.top/Article/details/gtcpwhrvfd.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cdnleiting.top/Article/details/gtjaikvoii.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhengqikj.top/Article/details/gtwfdvqkyo.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yangfankeji.com/Article/details/gtmqfxflyu.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.ehwqpu.com/Article/details/gtpgtqrzkf.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.0kj1m.cn/Article/details/gtvxfqmfjl.html

[F03] 写入文件（覆盖）
来源：http://dali.ehwqpu.com/Article/details/gtxqhzdyhu.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jiagoushi.top/Article/details/gtwpcrixlf.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.c1oappe.top/Article/details/gtvsuambnr.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinghuilouyu.cn/Article/details/gtdodgpbcs.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tian-w.cn/Article/details/gtvnwqflvo.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jianghu66.top/Article/details/gtiexnmtgj.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yvedp.cn/Article/details/gtfseiaoij.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jinqigfzy.top/Article/details/gtxfletefs.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yongpay.top/Article/details/gtnbzjvbbh.html

[F04] 追加写入文件
来源：http://dali.nwbrower.top/Article/details/gtdxmizefz.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yanxiufei.cn/Article/details/gtoixvebku.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yuxming.cn/Article/details/gtgfssajgx.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.9152youxi.cn/Article/details/gtqfdbrpbi.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.pengpengdd.cyou/Article/details/gtqdhiwuza.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yonumen.top/Article/details/gtkyuktgrw.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.sufxvd.cn/Article/details/gtgcwwnbjx.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.shangyingyoupin.top/Article/details/gtjuizobrq.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.chenjidiqi.icu/Article/details/gtbjhegmdi.html

[F05] 判断文件或目录是否存在
来源：http://dali.yonumen.top/Article/details/gtoddcmbdd.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.xinyue.icu/Article/details/gtqhvonhzo.html

PHP:  file_exists("a.txt");
来源：http://dali.jianghu66.top/Article/details/gtwuuxwfvp.html

JS:   fs.existsSync("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtypcaexxb.html

TS:   fs.existsSync("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtxrakxntr.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hywenlv.cn/Article/details/gtaujneyra.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.tianlin.xyz/Article/details/gtqttkwulk.html

Ruby: File.exist?("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtfompiiym.html

C#:   File.Exists("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtdzmphyvb.html

[F06] 删除文件
来源：http://dali.gogol.net.cn/Article/details/gtohmxsset.html

Py:   os.remove("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtvqixwcih.html

PHP:  unlink("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gtxdfeteou.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtxqlwjemy.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gttfnedjqz.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.tanke756.top/Article/details/gtqnkcitag.html

Go:   os.Remove("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtsmqptaek.html

Ruby: File.delete("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtzhxfhhbj.html

C#:   File.Delete("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtqaslizdz.html

[F07] 创建目录（含多级）
来源：http://dali.dashuyun.cn/Article/details/gtvoxztgrr.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yj20258.top/Article/details/gtbleklbso.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.ivvv.top/Article/details/gtjhwbjfig.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.feifeiyinyue.top/Article/details/gtbkwdoqwc.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.wangdashe.top/Article/details/gtynmqtfww.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.shangyingyoupin.top/Article/details/gtnkxmbqvt.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jinqigfzy.top/Article/details/gtnpkfyisn.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.cdnleiting.top/Article/details/gtupufugac.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jlsjyb.cn/Article/details/gtmyaurdja.html

[F08] 遍历目录
来源：http://dali.yvedp.cn/Article/details/gtixscaxaj.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.dianchejie.cn/Article/details/gtcywdeajm.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.cqqwz.cn/Article/details/gtkzqcblzu.html

JS:   fs.readdirSync("dir")
来源：http://dali.yj202588.top/Article/details/gtmtohjnpx.html

TS:   fs.readdirSync("dir")
来源：http://dali.gogol.net.cn/Article/details/gtbadwsixr.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpixcrfle.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zycfv.cn/Article/details/gtittroest.html

Ruby: Dir.children("dir")
来源：http://dali.haohaochexian.top/Article/details/gtnytcydvr.html

C#:   Directory.GetFiles("dir")
来源：http://dali.shangyingyoupin.top/Article/details/gtpthruqww.html

[F09] 获取文件大小
来源：http://dali.cucudq.cn/Article/details/gtksoelqfn.html

Py:   os.path.getsize("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtnmaasaps.html

PHP:  filesize("a.txt");
来源：http://dali.yuxming.cn/Article/details/gttkutdola.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpcubeoxh.html

TS:   fs.statSync("a.txt").size
来源：http://dali.shuidangran.top/Article/details/gtjmhcfhab.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gtyteydwsp.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjhbvbtbi.html

Ruby: File.size("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtelavetrd.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.vqdsnc.cn/Article/details/gtobvljmlt.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhoulong.xyz/Article/details/gtceffkyyf.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.guannengcc.top/Article/details/gtcdlvyhko.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.cdnleiting.top/Article/details/gtfaajxqrw.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hammf.cn/Article/details/gtofravntq.html

TS:   path.extname("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtmmjbtznh.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.sweek.top/Article/details/gttmmyvgaq.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yuanzhike.top/Article/details/gttpwqqpnd.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xylfe.cn/Article/details/gtoysxaxxx.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.sxryk.cn/Article/details/gtanzbuxzn.html

[F11] 复制与移动文件
来源：http://dali.wangshuangyany.cn/Article/details/gtsjdlqaoo.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.pycfn.com/Article/details/gtcjioxisf.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.redwolf501.top/Article/details/gtftfpwfrd.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.iojbl.cn/Article/details/gtsvruxhic.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmsfiwupf.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.kuanghao11.cn/Article/details/gtwrwuoztv.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.sufxvd.cn/Article/details/gtbxnoclux.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.daxiang520.top/Article/details/gteavaofrt.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.redwolf501.top/Article/details/gtijipuzai.html

[F12] CSV 读写
来源：http://dali.sxryk.cn/Article/details/gtqwrwnwgw.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gtymwtpzpq.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.svipenyu.cn/Article/details/gtnxtyjcxr.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.shanyushiyangtech.top/Article/details/gtibziafbp.html

TS:   // 同上
来源：http://dali.chenzaomai.com/Article/details/gtnvqzccpk.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.daxiang520.top/Article/details/gtctlhgdqs.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.shuidangran.top/Article/details/gtuapqiujr.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhiwuduotai.top/Article/details/gtwjaotchz.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.redwolf501.top/Article/details/gtgpmisyni.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gttftgqxlr.html

G. 面向对象
来源：http://dali.yj20258.top/Article/details/gtmjpyvnbf.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvcgxfoux.html

[G01] 定义类
来源：http://dali.hnqzz.top/Article/details/gtcpawzzik.html

Py:   class User: pass
来源：http://dali.shanyushiyangkeji.top/Article/details/gteevyvrwu.html

PHP:  class User {}
来源：http://dali.sxryk.cn/Article/details/gtyifcjubb.html

JS:   class User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgvulewqf.html

TS:   class User { name: string = ""; }
来源：http://dali.wangshuangyany.cn/Article/details/gtwqsrjzcw.html

Java: class User {}
来源：http://dali.nanxuanxn.top/Article/details/gtdvsqhivv.html

Go:   type User struct { Name string }
来源：http://dali.feifeiyinyue.top/Article/details/gtnfhrkrpa.html

Ruby: class User; end
来源：http://dali.gaohongyu789.top/Article/details/gtcbyvfnzs.html

C#:   class User {}
来源：http://dali.dianchejie.cn/Article/details/gtjtuezinx.html

[G02] 构造函数
来源：http://dali.gzhubu.top/Article/details/gtmrxheorp.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.gaohongyu789.top/Article/details/gtvuxmheef.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yj20258.top/Article/details/gtkvivtvsg.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.svipenyu.cn/Article/details/gtvpasspma.html

TS:   constructor(public name: string) {}
来源：http://dali.xuanzx.com/Article/details/gtshctchzr.html

Java: User(String name) { this.name = name; }
来源：http://dali.yj20258888.top/Article/details/gtjrjxccnd.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jqgufenzy.top/Article/details/gtmkljkmoj.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ehwqpu.com/Article/details/gtejlmpxcc.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yueranfly.top/Article/details/gtfzbwgfdi.html

[G03] 实例属性
来源：http://dali.haohaochexian.top/Article/details/gtgfgotttj.html

Py:   self.name = "x"
来源：http://dali.cdnleiting.top/Article/details/gtkelufzli.html

PHP:  public string $name = "x";
来源：http://dali.jinqigufen.top/Article/details/gtrbhffcvu.html

JS:   this.name = "x";
来源：http://dali.dianchejie.cn/Article/details/gtxmqbnizp.html

TS:   name: string = "x";
来源：http://dali.sxryk.cn/Article/details/gtgulstiqs.html

Java: private String name;
来源：http://dali.hnxiangtu.top/Article/details/gtluwqszhs.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxpjbhcpf.html

Ruby: @name = "x"
来源：http://dali.tanke756.top/Article/details/gtxrpvhwnw.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.aibaodan.cn/Article/details/gtzjnzufwt.html

[G04] 定义方法
来源：http://dali.shanyushiyangtech.top/Article/details/gtzdwdiilr.html

Py:   def greet(self): return self.name
来源：http://dali.guannengcc.top/Article/details/gtfxzleevr.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtvvnvmeeq.html

JS:   greet() { return this.name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtarhihgpc.html

TS:   greet(): string { return this.name; }
来源：http://dali.hnqzz.top/Article/details/gtelzqggqi.html

Java: String greet() { return name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuweryyvx.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.shzxlz.cn/Article/details/gtgotsjfxa.html

Ruby: def greet; @name; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnxoeaawj.html

C#:   public string Greet() => Name;
来源：http://dali.nanxuanxn.top/Article/details/gtcpkgbogt.html

[G05] 继承
来源：http://dali.xuetiantiany.cn/Article/details/gtxagdllls.html

Py:   class Admin(User): pass
来源：http://dali.nanxuanxn.top/Article/details/gtgtsdnkox.html

PHP:  class Admin extends User {}
来源：http://dali.hnxiangtu.top/Article/details/gtutgxdrxf.html

JS:   class Admin extends User {}
来源：http://dali.shuidangran.top/Article/details/gtpmaibmwn.html

TS:   class Admin extends User {}
来源：http://dali.yj20258.top/Article/details/gtjmjolxry.html

Java: class Admin extends User {}
来源：http://dali.cdnleiting.top/Article/details/gtcgmuqevy.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ehwqpu.com/Article/details/gtgbsycqwc.html

Ruby: class Admin < User; end
来源：http://dali.yj202588.top/Article/details/gtcpmqwxzp.html

C#:   class Admin : User {}
来源：http://dali.yangfankeji.com/Article/details/gtnnakmnnb.html

[G06] 重写方法
来源：http://dali.jqgfzy.top/Article/details/gtjitmtngr.html

Py:   def greet(self): return "admin"
来源：http://dali.smart0.xyz/Article/details/gtevjjsjrh.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.cdnleiting.top/Article/details/gtehosttef.html

JS:   greet() { return "admin"; }
来源：http://dali.tian-w.cn/Article/details/gtqngmdqor.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hammf.cn/Article/details/gthczggbvr.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtobobbrnv.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.gogol.net.cn/Article/details/gtsiygsoqr.html

Ruby: def greet; "admin"; end
来源：http://dali.svipenyu.cn/Article/details/gtpnmaagvz.html

C#:   public override string Greet() => "admin";
来源：http://dali.hnxiangtu.top/Article/details/gtkwchrjcw.html

[G07] 调用父类方法
来源：http://dali.meibo888.top/Article/details/gtdjslwiof.html

Py:   super().greet()
来源：http://dali.chenzaomai.com/Article/details/gtpiuhesqk.html

PHP:  parent::greet();
来源：http://dali.cqqwz.cn/Article/details/gtzkjdijzc.html

JS:   super.greet();
来源：http://dali.gogol.net.cn/Article/details/gthzllmpxl.html

TS:   super.greet();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtapxcxtgn.html

Java: super.greet();
来源：http://dali.jlsjyb.cn/Article/details/gtpvzgtfri.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jianghu66.top/Article/details/gtdfotzrdk.html

Ruby: super
来源：http://dali.daxiang520.top/Article/details/gtvgjuzswj.html

C#:   base.Greet();
来源：http://dali.jinghuilouyu.cn/Article/details/gtziljqwuv.html

[G08] 静态方法与属性
来源：http://dali.bjfxy.top/Article/details/gtdvdtasyt.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.kuanghao11.cn/Article/details/gtkzhrjnlv.html

PHP:  public static function f() {}
来源：http://dali.316326.xyz/Article/details/gtfvqkmeik.html

JS:   static f() {}
来源：http://dali.hammf.cn/Article/details/gtuzrgrffs.html

TS:   static f(): void {}
来源：http://dali.zhixingplan.top/Article/details/gtpvoxghqh.html

Java: static void f() {}
来源：http://dali.jinqigfzy.top/Article/details/gtssyiqcnr.html


<!-- 参考信息 -->