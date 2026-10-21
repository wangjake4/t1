代发 wailian999

[E10] 左侧补零 / 定长填充
来源：http://dali.zhoulong.xyz/Article/details/gtbzgmqfyw.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.cqqwz.cn/Article/details/gtueffasjv.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yuanzhike.top/Article/details/gtkkezvblq.html

JS:   "7".padStart(3, "0")
来源：http://dali.yj20258.top/Article/details/gttfvftewr.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhengqikj.top/Article/details/gtevtlxcnw.html

Java: String.format("%03d", 7)
来源：http://dali.bjfxy.top/Article/details/gttiojejfc.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.tanke756.top/Article/details/gtxowjdzmb.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.guowangkeji.top/Article/details/gtcytwlshi.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.shanyushiyangkeji.top/Article/details/gtljtzpfln.html

[E11] 反转字符串
来源：http://dali.redwolf501.top/Article/details/gtbceoqhpg.html

Py:   s[::-1]
来源：http://dali.pengpengdd.cyou/Article/details/gtsyfymqcd.html

PHP:  strrev($s);
来源：http://dali.ybcxt.top/Article/details/gttqvyvuyb.html

JS:   [...s].reverse().join("")
来源：http://dali.wangshuangyany.cn/Article/details/gtjjvgmktv.html

TS:   [...s].reverse().join("")
来源：http://dali.yangfankeji.com/Article/details/gtinxadbzr.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yangfankeji.com/Article/details/gttbmkfbbm.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.gaohongyu789.top/Article/details/gtjvroensu.html

Ruby: s.reverse
来源：http://dali.yj20258.top/Article/details/gtnqfnnhqk.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.kuanghao11.cn/Article/details/gtrmwszcxm.html

[E12] 统计某字符出现次数
来源：http://dali.yanxiufei.cn/Article/details/gtenuonvga.html

Py:   s.count("a")
来源：http://dali.cdnleiting.top/Article/details/gttmzdkfgc.html

PHP:  substr_count($s, "a");
来源：http://dali.yueranfly.top/Article/details/gtlcntimkd.html

JS:   s.split("a").length - 1
来源：http://dali.aizwys.cn/Article/details/gttxyndzwx.html

TS:   s.split("a").length - 1
来源：http://dali.hfpthk.cn/Article/details/gtionkhdvl.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.nwbrower.top/Article/details/gtnebwhglc.html

Go:   strings.Count(s, "a")
来源：http://dali.chenzaomai.com/Article/details/gtbyqrysxh.html

Ruby: s.count("a")
来源：http://dali.xuetiantiany.cn/Article/details/gtvwxqfwkb.html

C#:   s.Count(c => c == 'a')
来源：http://dali.vqdsnc.cn/Article/details/gthnlctqat.html

[E13] 逐字符遍历
来源：http://dali.jqgufenzy.top/Article/details/gtxgqzoxyg.html

Py:   for ch in s: print(ch)
来源：http://dali.chenzaomai.com/Article/details/gtbredzbeh.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yongpay.top/Article/details/gtpfvvutrm.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jyoumei.cn/Article/details/gtynztropq.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.dashuyun.cn/Article/details/gtvfdxyahk.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hnqzz.top/Article/details/gtuvrjrqrl.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwskrpetm.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.smart0.xyz/Article/details/gtgdadqhmr.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtbxdcxvux.html

[E14] URL 编码与 Base64
来源：http://dali.cucudq.cn/Article/details/gtwmefnxsn.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yj20258.top/Article/details/gtunaskawb.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtarintlla.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.tanke756.top/Article/details/gtcbenuqvw.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcjxxldfb.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.316326.xyz/Article/details/gtkycufvws.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yvedp.cn/Article/details/gtjchdksds.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.nwbrower.top/Article/details/gtodtghkvw.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jyoumei.cn/Article/details/gtcsdofpvo.html

[E15] HTML 转义 / 反转义
来源：http://dali.jyoumei.cn/Article/details/gtxnukbvbx.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.fzhhl.top/Article/details/gtccdvihod.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hammf.cn/Article/details/gthaosmrdy.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.quarkkingdee.top/Article/details/gtdbjyfbri.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.chenjidiqi.icu/Article/details/gtnptrjivq.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.gzhubu.top/Article/details/gtxiepbcza.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtpidgkypn.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.ydzc1.top/Article/details/gtfaeyqghl.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.pycfn.com/Article/details/gtnpftnpxs.html

[E16] 数字千分位
来源：http://dali.dianchejie.cn/Article/details/gtqwogunxm.html

Py:   f"{1234567:,}"
来源：http://dali.cheryme.top/Article/details/gtmhkxohbn.html

PHP:  number_format(1234567);
来源：http://dali.xinyue.icu/Article/details/gtbesbvepu.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhiwuduotai.top/Article/details/gtjktirujk.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.smart0.xyz/Article/details/gtliowidto.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.birdmap.top/Article/details/gtqxvmjzkt.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.xuetiantiany.cn/Article/details/gtwxkzzlyf.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.andypj.xyz/Article/details/gtymeijyup.html

C#:   1234567.ToString("N0")
来源：http://dali.yj202588.top/Article/details/gtmkeiyrht.html

[E17] 首字母大写
来源：http://dali.zhoulong.xyz/Article/details/gtyhbblsvn.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zdqjudy.top/Article/details/gthmfsyptn.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.fengsongda.top/Article/details/gtmmxwsvdf.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.guowangkeji.top/Article/details/gtpsbghcqc.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj20258888.top/Article/details/gtqgtijwps.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.svipenyu.cn/Article/details/gtdnueiely.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.cheryme.top/Article/details/gtdelejyfy.html

Ruby: s.capitalize
来源：http://dali.zhengqikj.top/Article/details/gtwpbuvhpl.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jinghuilouyu.cn/Article/details/gtsrwkpqkm.html

[E18] 模板占位符替换
来源：http://dali.nanxuanxn.top/Article/details/gtnjionmur.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhengqikj.top/Article/details/gtmpjhmegz.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yangfankeji.com/Article/details/gtdhwyvksn.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yangfankeji.com/Article/details/gtswgcmvdt.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.wangshuangyany.cn/Article/details/gtyipfndku.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xuanzx.com/Article/details/gthqrkjxuz.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.tianlin.xyz/Article/details/gtjgzkfgwl.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yj202588.top/Article/details/gtkwuidbuc.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.daria6918.cn/Article/details/gtzylpbpwz.html

[E19] 多行文本按行拆分
来源：http://dali.cheryme.top/Article/details/gtefyexecq.html

Py:   s.splitlines()
来源：http://dali.ehwqpu.com/Article/details/gtizqzmwkk.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.nanxuanxn.top/Article/details/gtvgfhxtje.html

JS:   s.split(/\r?\n/)
来源：http://dali.hysaishi.cn/Article/details/gtwsnzebwq.html

TS:   s.split(/\r?\n/)
来源：http://dali.xylfe.cn/Article/details/gtpecvmryh.html

Java: s.lines().toList()
来源：http://dali.tian-w.cn/Article/details/gtbpdnekgx.html

Go:   strings.Split(s, "\n")
来源：http://dali.316326.xyz/Article/details/gtshiuurfi.html

Ruby: s.lines
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkjeeeewr.html

C#:   s.Split('\n')
来源：http://dali.xinyue.icu/Article/details/gtvpxmnuil.html

[E20] 判断字符串是否为空
来源：http://dali.redwolf501.top/Article/details/gtlscammkt.html

Py:   if not s:
来源：http://dali.andypj.xyz/Article/details/gtxgherriz.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.smart0.xyz/Article/details/gtnbjkrioe.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yj202588.top/Article/details/gtbprjxcfm.html

TS:   if (s === "") {}
来源：http://dali.zhixingplan.top/Article/details/gtryopbjsa.html

Java: if (s.isEmpty()) {}
来源：http://dali.dashuyun.cn/Article/details/gtsomfvbee.html

Go:   if s == "" {}
来源：http://dali.cqqwz.cn/Article/details/gtrrigldkc.html

Ruby: if s.empty?
来源：http://dali.jqgfzy.top/Article/details/gtkvpcitzq.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.tian-w.cn/Article/details/gtbgohfmwt.html

[E21] 超长截断加省略号
来源：http://dali.yanxiufei.cn/Article/details/gtrogdfuvv.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xylfe.cn/Article/details/gtsvggwbgs.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.dianchejie.cn/Article/details/gtnxajvuip.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.guowangkeji.top/Article/details/gtbxogdtpa.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yonumen.top/Article/details/gtdeskargk.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.shanyushiyangkeji.top/Article/details/gthxkzkwnj.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yuanzhike.top/Article/details/gtobqtadja.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.shangyingyoupin.top/Article/details/gtvdndgeza.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.xuetiantiany.cn/Article/details/gtvrjypmxc.html

[E22] 字节长度与字符长度
来源：http://dali.vqdsnc.cn/Article/details/gtjhoavkyn.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.chenzaomai.com/Article/details/gtlpaaprgy.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hnqzz.top/Article/details/gtlxahbocs.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yj20258888.top/Article/details/gtyibhytib.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.andypj.xyz/Article/details/gtpfzmivqs.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.ydzc1.top/Article/details/gtjuucivux.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.tanke756.top/Article/details/gtfryinyzo.html

Ruby: s.bytesize;  s.length
来源：http://dali.sysykeji.top/Article/details/gtllsboola.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.pycfn.com/Article/details/gtvrnzsgmv.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtkifgehvl.html

F. 文件与目录
来源：http://dali.yueranfly.top/Article/details/gtxhvqwxvo.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtetvewhby.html

[F01] 读取整个文件
来源：http://dali.ybcxt.top/Article/details/gtsrxyokmm.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jinqigfzy.top/Article/details/gtusctetvf.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yueranfly.top/Article/details/gtiizuhirt.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.cucudq.cn/Article/details/gtvlfluatp.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zdqjudy.top/Article/details/gtfogipylr.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.aizwys.cn/Article/details/gtzcdeebln.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.shzxlz.cn/Article/details/gtawibmkij.html

Ruby: File.read("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtmctisuyc.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gtzebximmf.html

[F02] 逐行读取文件
来源：http://dali.zycfv.cn/Article/details/gtmnahmshe.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.vqdsnc.cn/Article/details/gttboewdfr.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.smart0.xyz/Article/details/gtmkqqufic.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbmyfkjie.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hysaishi.cn/Article/details/gtpyrnrqrt.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.sxryk.cn/Article/details/gtmeupumqi.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.nanxuanxn.top/Article/details/gthmmhzecs.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.vqdsnc.cn/Article/details/gtodirntyc.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.gaohongyu789.top/Article/details/gtrmbjdmhn.html

[F03] 写入文件（覆盖）
来源：http://dali.jiagoushi.top/Article/details/gtmhuanrew.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jyoumei.cn/Article/details/gtrdjkikxq.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.vqdsnc.cn/Article/details/gtzohhsnup.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jianghu66.top/Article/details/gtokxhdbki.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.wangshuangyany.cn/Article/details/gtlhyxmkta.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.havefunace.top/Article/details/gtoeszowez.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.cheryme.top/Article/details/gthqoiwepk.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.snrcjt.cn/Article/details/gtxipnzlzq.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.pycfn.com/Article/details/gtpmbrhese.html

[F04] 追加写入文件
来源：http://dali.hysaishi.cn/Article/details/gtlxjmskwr.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yueranfly.top/Article/details/gthgezagyf.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.snrcjt.cn/Article/details/gtluyulehh.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xylfe.cn/Article/details/gtgucsgpfb.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nanxinkj.top/Article/details/gtpshhreas.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.tanke756.top/Article/details/gtulgfqzxs.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zdqjudy.top/Article/details/gtmxnobkuk.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.ivvv.top/Article/details/gtibzusfhd.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.guowangkeji.top/Article/details/gtycaxanwq.html

[F05] 判断文件或目录是否存在
来源：http://dali.ehwqpu.com/Article/details/gtwilzqrho.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.wangshuangyany.cn/Article/details/gtgvsgpjld.html

PHP:  file_exists("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtnfhgqldc.html

JS:   fs.existsSync("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtgfgapiob.html

TS:   fs.existsSync("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtjgsflwfg.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hfpthk.cn/Article/details/gtdzxkbmte.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhiwuduotai.top/Article/details/gtsyrfqzxe.html

Ruby: File.exist?("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtpdcjrous.html

C#:   File.Exists("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtwbegppig.html

[F06] 删除文件
来源：http://dali.bjfxy.top/Article/details/gtkzdezpwl.html

Py:   os.remove("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtsexavtoc.html

PHP:  unlink("a.txt");
来源：http://dali.ydzc1.top/Article/details/gtbsgdctwq.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.fzhhl.top/Article/details/gthrtlwaeh.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gttwikidzm.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhongyouzk.top/Article/details/gtoywescmf.html

Go:   os.Remove("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtiposihyg.html

Ruby: File.delete("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtulfyawta.html

C#:   File.Delete("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuxtwhmdu.html

[F07] 创建目录（含多级）
来源：http://dali.cucudq.cn/Article/details/gtgdgubbmp.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.cucudq.cn/Article/details/gtgivrwbat.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yj202588.top/Article/details/gtkclnybhm.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.andypj.xyz/Article/details/gtjnncqvua.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hnxiangtu.top/Article/details/gtfkfftyrg.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.shuidangran.top/Article/details/gtazzggxmp.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xuetiantiany.cn/Article/details/gtpkslwaok.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.sufxvd.cn/Article/details/gtfarqfxko.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yonumen.top/Article/details/gtwzzkhyij.html

[F08] 遍历目录
来源：http://dali.jinyuanbaomall.cn/Article/details/gtucrmgcrl.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.gogol.net.cn/Article/details/gtupikschy.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.gaohongyu789.top/Article/details/gtqvbyuvhj.html

JS:   fs.readdirSync("dir")
来源：http://dali.c1oappe.top/Article/details/gtbpdlkoef.html

TS:   fs.readdirSync("dir")
来源：http://dali.jiagoushi.top/Article/details/gtxmcpuqau.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhixingplan.top/Article/details/gtcnfxxhph.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.dashuyun.cn/Article/details/gtjnmzdrgd.html

Ruby: Dir.children("dir")
来源：http://dali.zycfv.cn/Article/details/gtyoyfkckq.html

C#:   Directory.GetFiles("dir")
来源：http://dali.havefunace.top/Article/details/gtlaewzymt.html

[F09] 获取文件大小
来源：http://dali.havefunace.top/Article/details/gtlewvtlic.html

Py:   os.path.getsize("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtvfluxiuk.html

PHP:  filesize("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gthxomvpxz.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jinqigfzy.top/Article/details/gtndobievm.html

TS:   fs.statSync("a.txt").size
来源：http://dali.dianchejie.cn/Article/details/gtqlvpebmo.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cdnleiting.top/Article/details/gtawqnsszw.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.0kj1m.cn/Article/details/gtwmhomypm.html

Ruby: File.size("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gttfzroqvn.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.tianlin.xyz/Article/details/gttsmqzwpn.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.vqdsnc.cn/Article/details/gthtmchgoo.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtebooobqt.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gtinaildxw.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtrtjxvjvp.html

TS:   path.extname("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gttjqqdyfa.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.0kj1m.cn/Article/details/gtzanflaku.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xuanzx.com/Article/details/gtpynhvlup.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtdaxotujh.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ybcxt.top/Article/details/gtlfwcwcxm.html

[F11] 复制与移动文件
来源：http://dali.meibo888.top/Article/details/gtnvpnlbrm.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtfylepupg.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.redwolf501.top/Article/details/gtzteabmoy.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhixingplan.top/Article/details/gtdjpqjauv.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jyoumei.cn/Article/details/gtmyvirtan.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hywenlv.cn/Article/details/gtkyrclbmz.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.birdmap.top/Article/details/gthxyhmtco.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvbarxryg.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xuetiantiany.cn/Article/details/gtjbuetylq.html

[F12] CSV 读写
来源：http://dali.jinqigfzy.top/Article/details/gtznuyyzlc.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yongpay.top/Article/details/gtqiqkqolc.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.tian-w.cn/Article/details/gtrspdztqe.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.chenjidiqi.icu/Article/details/gtweyynfci.html

TS:   // 同上
来源：http://dali.jlsjyb.cn/Article/details/gtpbzbliji.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.pycfn.com/Article/details/gtkympguru.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jqgfzy.top/Article/details/gtendkrnot.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.meibo888.top/Article/details/gtiovelmvi.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yangfankeji.com/Article/details/gtwjldylni.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtmmutnxuj.html

G. 面向对象
来源：http://dali.xinyue.icu/Article/details/gtxraguvjh.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtylhuurhd.html

[G01] 定义类
来源：http://dali.haohaochexian.top/Article/details/gtjvgerbcw.html

Py:   class User: pass
来源：http://dali.redwolf501.top/Article/details/gtmdpyvxvj.html

PHP:  class User {}
来源：http://dali.hysaishi.cn/Article/details/gtmaftpmmk.html

JS:   class User {}
来源：http://dali.daria6918.cn/Article/details/gtawfgwvgr.html

TS:   class User { name: string = ""; }
来源：http://dali.yonumen.top/Article/details/gteuiayuhz.html

Java: class User {}
来源：http://dali.yangfankeji.com/Article/details/gtookbyovq.html

Go:   type User struct { Name string }
来源：http://dali.redwolf501.top/Article/details/gtidjghito.html

Ruby: class User; end
来源：http://dali.hfpthk.cn/Article/details/gtgvbfqbsa.html

C#:   class User {}
来源：http://dali.bjfxy.top/Article/details/gtvmmqhzjx.html

[G02] 构造函数
来源：http://dali.yj20258.top/Article/details/gtmwvbbldm.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xuetiantiany.cn/Article/details/gtbyebvump.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ybcxt.top/Article/details/gtrkldrddj.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yueranfly.top/Article/details/gtxhcdjmgu.html

TS:   constructor(public name: string) {}
来源：http://dali.daxiang520.top/Article/details/gtpqnkjcor.html

Java: User(String name) { this.name = name; }
来源：http://dali.meibo888.top/Article/details/gtbfzdiknq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.chenzaomai.com/Article/details/gtcaypsxfd.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtajjiazwh.html

C#:   public User(string name) { Name = name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtwenasgjh.html

[G03] 实例属性
来源：http://dali.yj20258888.top/Article/details/gtlgfkduew.html

Py:   self.name = "x"
来源：http://dali.zhoulong.xyz/Article/details/gtfylhfnjq.html

PHP:  public string $name = "x";
来源：http://dali.bjfxy.top/Article/details/gtquurifip.html

JS:   this.name = "x";
来源：http://dali.tian-w.cn/Article/details/gtxmzeepti.html

TS:   name: string = "x";
来源：http://dali.meibo888.top/Article/details/gtlhldvgkh.html

Java: private String name;
来源：http://dali.tian-w.cn/Article/details/gtulorzxrx.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hongshengwenyu.top/Article/details/gtjwnaaagv.html

Ruby: @name = "x"
来源：http://dali.shangyingyoupin.top/Article/details/gtzfvydubr.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yanxiufei.cn/Article/details/gtbsftxkwq.html

[G04] 定义方法
来源：http://dali.sxryk.cn/Article/details/gtvdehueun.html

Py:   def greet(self): return self.name
来源：http://dali.sufxvd.cn/Article/details/gtdjalltge.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.nanxuanxn.top/Article/details/gtzjgocuqi.html

JS:   greet() { return this.name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtykiphmcv.html

TS:   greet(): string { return this.name; }
来源：http://dali.dianchejie.cn/Article/details/gtwvwdcksc.html

Java: String greet() { return name; }
来源：http://dali.jqgfzy.top/Article/details/gtqgavcfog.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.vqdsnc.cn/Article/details/gtftxxzvxh.html

Ruby: def greet; @name; end
来源：http://dali.xinyue.icu/Article/details/gtqquzagrg.html

C#:   public string Greet() => Name;
来源：http://dali.pycfn.com/Article/details/gtccxflkre.html

[G05] 继承
来源：http://dali.yongpay.top/Article/details/gthymdvwtt.html

Py:   class Admin(User): pass
来源：http://dali.pycfn.com/Article/details/gtvhuokwcv.html

PHP:  class Admin extends User {}
来源：http://dali.jinqigfzy.top/Article/details/gttohzthhe.html

JS:   class Admin extends User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzghnkifw.html

TS:   class Admin extends User {}
来源：http://dali.cheryme.top/Article/details/gtjcogeply.html

Java: class Admin extends User {}
来源：http://dali.nanxinkj.top/Article/details/gtbznepocp.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.birdmap.top/Article/details/gteaztemox.html

Ruby: class Admin < User; end
来源：http://dali.sysykeji.top/Article/details/gtirclzchd.html

C#:   class Admin : User {}
来源：http://dali.wangshuangyany.cn/Article/details/gtvxozpdbb.html

[G06] 重写方法
来源：http://dali.zhixingplan.top/Article/details/gtnzgqlpxf.html

Py:   def greet(self): return "admin"
来源：http://dali.chenzaomai.com/Article/details/gtwrngcfxo.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.birdmap.top/Article/details/gtooibtwap.html

JS:   greet() { return "admin"; }
来源：http://dali.guannengcc.top/Article/details/gtrbwwymbm.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zdqjudy.top/Article/details/gtajhinrqc.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.c1oappe.top/Article/details/gtczmsmpja.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shzxlz.cn/Article/details/gtzrxmnwqe.html

Ruby: def greet; "admin"; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gttxvmvpnl.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhixingplan.top/Article/details/gtlqakpelc.html

[G07] 调用父类方法
来源：http://dali.hammf.cn/Article/details/gtsebsmhhu.html

Py:   super().greet()
来源：http://dali.meibo888.top/Article/details/gtqxgrelut.html

PHP:  parent::greet();
来源：http://dali.sufxvd.cn/Article/details/gtotwmrver.html

JS:   super.greet();
来源：http://dali.guannengcc.top/Article/details/gtkrboawqy.html

TS:   super.greet();
来源：http://dali.mhx1999.top/Article/details/gtyrjreenj.html

Java: super.greet();
来源：http://dali.chenjidiqi.icu/Article/details/gtpvwbcfel.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yj20258.top/Article/details/gtekjuzhji.html

Ruby: super
来源：http://dali.ivvv.top/Article/details/gtvfitfkib.html

C#:   base.Greet();
来源：http://dali.ppjwa.cn/Article/details/gtbbkuawit.html

[G08] 静态方法与属性
来源：http://dali.sysykeji.top/Article/details/gtjhalrjxe.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.chenjidiqi.icu/Article/details/gtithgzcmv.html

PHP:  public static function f() {}
来源：http://dali.jyoumei.cn/Article/details/gtsjkalfac.html

JS:   static f() {}
来源：http://dali.jianghu66.top/Article/details/gtbutmconz.html

TS:   static f(): void {}
来源：http://dali.cqqwz.cn/Article/details/gtejxqzisi.html

Java: static void f() {}
来源：http://dali.ehwqpu.com/Article/details/gtdqxifyxd.html


<!-- 参考信息 -->