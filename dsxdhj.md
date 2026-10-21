代发 wailian999

[E14] URL 编码与 Base64
来源：http://dali.quarkkingdee.top/Article/details/gtzesihzuu.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.sweek.top/Article/details/gtyxtmjofw.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.redwolf501.top/Article/details/gtppeodudd.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.pengpengdd.cyou/Article/details/gtkwudifag.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jlsjyb.cn/Article/details/gtamdfrqoz.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hysaishi.cn/Article/details/gtlppujqqr.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zdqjudy.top/Article/details/gtdqqysbtm.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yvedp.cn/Article/details/gtiniyyptw.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.cashguo.top/Article/details/gtslcxfbjy.html

[E15] HTML 转义 / 反转义
来源：http://dali.shanyushiyangtech.top/Article/details/gtehrwjopz.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.xinyue.icu/Article/details/gtybmdotpm.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.xinyue.icu/Article/details/gtmtxdcsfo.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zycfv.cn/Article/details/gtnmlgnety.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.sysykeji.top/Article/details/gtdjrpxulz.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.andypj.xyz/Article/details/gtnveufmew.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.guannengcc.top/Article/details/gteprhtlbb.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yj20258.top/Article/details/gtuuggdhxk.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yj20258888.top/Article/details/gtlzvoyscz.html

[E16] 数字千分位
来源：http://dali.guowangkeji.top/Article/details/gtaeioyhls.html

Py:   f"{1234567:,}"
来源：http://dali.ppjwa.cn/Article/details/gtclueyqov.html

PHP:  number_format(1234567);
来源：http://dali.cucudq.cn/Article/details/gtiyzknbjf.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.daria6918.cn/Article/details/gtkoeducnw.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jqgfzy.top/Article/details/gtlhyaghpa.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.xziqi.cn/Article/details/gtsnyfozpe.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.chenzaomai.com/Article/details/gtdgajyqxu.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfamrrzki.html

C#:   1234567.ToString("N0")
来源：http://dali.vqdsnc.cn/Article/details/gtxavemhzy.html

[E17] 首字母大写
来源：http://dali.guowangkeji.top/Article/details/gtldlmmfzk.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.shzxlz.cn/Article/details/gthnjsaqop.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.nwbrower.top/Article/details/gtkpgcwdry.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhixingplan.top/Article/details/gtcuurwdep.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gotoacloud.top/Article/details/gtjcxwnbwq.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.ydzc1.top/Article/details/gtxhefehge.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.tanke756.top/Article/details/gtmiqpfqnj.html

Ruby: s.capitalize
来源：http://dali.daxiang520.top/Article/details/gtcpakrhsl.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yj202588.top/Article/details/gtrhoiwvng.html

[E18] 模板占位符替换
来源：http://dali.gaohongyu789.top/Article/details/gtaurafowj.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.0kj1m.cn/Article/details/gtavizdffz.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.gaohongyu789.top/Article/details/gtfxcafaax.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yj20258.top/Article/details/gtkgoqqpzl.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.xylfe.cn/Article/details/gtyhqngnrs.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.chenjidiqi.icu/Article/details/gtuiqgbbqv.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yj202588.top/Article/details/gtjidgvmzp.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.ydzc1.top/Article/details/gtznbuwvho.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jinqigufen.top/Article/details/gtpxcbvfad.html

[E19] 多行文本按行拆分
来源：http://dali.hongshengwenyu.top/Article/details/gtmmozaeag.html

Py:   s.splitlines()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxdluplow.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hywenlv.cn/Article/details/gtojorceku.html

JS:   s.split(/\r?\n/)
来源：http://dali.xziqi.cn/Article/details/gteyanxlzc.html

TS:   s.split(/\r?\n/)
来源：http://dali.wangdashe.top/Article/details/gthpakhwuu.html

Java: s.lines().toList()
来源：http://dali.cashguo.top/Article/details/gtdtvluots.html

Go:   strings.Split(s, "\n")
来源：http://dali.hnqzz.top/Article/details/gtcjfnqscm.html

Ruby: s.lines
来源：http://dali.nanxinkj.top/Article/details/gtiftmawhb.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gtrornanrc.html

[E20] 判断字符串是否为空
来源：http://dali.ybcxt.top/Article/details/gtobvdtuti.html

Py:   if not s:
来源：http://dali.xziqi.cn/Article/details/gtwtyfhdxr.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.sufxvd.cn/Article/details/gtcbgwhipk.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.nanxuanxn.top/Article/details/gtgijpbaoj.html

TS:   if (s === "") {}
来源：http://dali.chenjidiqi.icu/Article/details/gtxcmjgund.html

Java: if (s.isEmpty()) {}
来源：http://dali.hfpthk.cn/Article/details/gtzlggnidc.html

Go:   if s == "" {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtefdnhrzv.html

Ruby: if s.empty?
来源：http://dali.yj202588.top/Article/details/gtbhcdkuhq.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hfpthk.cn/Article/details/gtkskgyqux.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gtfsjpzozv.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.shzxlz.cn/Article/details/gtvmrvqgsn.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhongyouzk.top/Article/details/gtbynaqvnt.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.snrcjt.cn/Article/details/gtuxwuqhoq.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.aizwys.cn/Article/details/gtziyvbokd.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zdqjudy.top/Article/details/gtxjbgxhwu.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhongyouzk.top/Article/details/gtzgppkwhx.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.ywan-chungtsiang.top/Article/details/gtljdyuwhf.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.dianchejie.cn/Article/details/gtbafnhudb.html

[E22] 字节长度与字符长度
来源：http://dali.haohaochexian.top/Article/details/gtuhadsplz.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.316326.xyz/Article/details/gtpzyanqxd.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.wangshuangyany.cn/Article/details/gtgrcsomrw.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gzhubu.top/Article/details/gtutueekfj.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gtrgsiatlr.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hfpthk.cn/Article/details/gtcbqykcco.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hnxiangtu.top/Article/details/gtadrevllg.html

Ruby: s.bytesize;  s.length
来源：http://dali.xylfe.cn/Article/details/gtluyrqyqg.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.guannengcc.top/Article/details/gtmtqbatlr.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtlwmqwdcq.html

F. 文件与目录
来源：http://dali.yuxming.cn/Article/details/gtrjbnsxgf.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtcvxzlvzs.html

[F01] 读取整个文件
来源：http://dali.vqdsnc.cn/Article/details/gtqucvjnbf.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.316326.xyz/Article/details/gtzqqobzvj.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yj20258888.top/Article/details/gtydwjvabh.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.bjfxy.top/Article/details/gtpwedvpof.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.dianchejie.cn/Article/details/gtjrfrxilv.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.shzxlz.cn/Article/details/gtbnbqytey.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yvedp.cn/Article/details/gtiayunxrp.html

Ruby: File.read("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtmjubpqgi.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.fzhhl.top/Article/details/gtwjxvniia.html

[F02] 逐行读取文件
来源：http://dali.xziqi.cn/Article/details/gtdkrcunlj.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jinghuilouyu.cn/Article/details/gtpnqkqrng.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ppjwa.cn/Article/details/gtmivrfoiv.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zdqjudy.top/Article/details/gtbnjanahh.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yanxiufei.cn/Article/details/gtfarumish.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.nanxuanxn.top/Article/details/gtxcomxfuw.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hysaishi.cn/Article/details/gttioiwxez.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yj202588.top/Article/details/gthoovinmd.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.dashuyun.cn/Article/details/gtiziteirj.html

[F03] 写入文件（覆盖）
来源：http://dali.ehwqpu.com/Article/details/gtceszsbat.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtadlupfip.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ybcxt.top/Article/details/gtqvydtbed.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.9152youxi.cn/Article/details/gtfoexyooy.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sufxvd.cn/Article/details/gtbrxztivs.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.nanxinkj.top/Article/details/gtdputjwqo.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.daria6918.cn/Article/details/gtfpzojxlv.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.c1oappe.top/Article/details/gtthkzbmbz.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jianghu66.top/Article/details/gturkgcwir.html

[F04] 追加写入文件
来源：http://dali.mhx1999.top/Article/details/gthcnrrdag.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.feifeiyinyue.top/Article/details/gtuhaubcll.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.guannengcc.top/Article/details/gtmoocevft.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hfpthk.cn/Article/details/gtfjemgbaw.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.meibo888.top/Article/details/gtrfslkgkm.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hywenlv.cn/Article/details/gtirumqrzs.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.quarkkingdee.top/Article/details/gtvfzkhdws.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.guannengcc.top/Article/details/gtxmiyqbkm.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gtshihwuln.html

[F05] 判断文件或目录是否存在
来源：http://dali.hywenlv.cn/Article/details/gtoczmtgdf.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.wangshuangyany.cn/Article/details/gtnptrongj.html

PHP:  file_exists("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtrjndizlj.html

JS:   fs.existsSync("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtvxcexdcc.html

TS:   fs.existsSync("a.txt")
来源：http://dali.tanke756.top/Article/details/gtxfjqqnnu.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.ivvv.top/Article/details/gtvmpiiepa.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.sweek.top/Article/details/gtmpdscxne.html

Ruby: File.exist?("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtilzblcpn.html

C#:   File.Exists("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtiigvqcjo.html

[F06] 删除文件
来源：http://dali.316326.xyz/Article/details/gtgwqzojbu.html

Py:   os.remove("a.txt")
来源：http://dali.cashguo.top/Article/details/gtwparntfz.html

PHP:  unlink("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gtdhmqkmpo.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtcannyrgr.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkliiakwa.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.svipenyu.cn/Article/details/gtzijuadvh.html

Go:   os.Remove("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtujmiyagg.html

Ruby: File.delete("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtgyyiqbdy.html

C#:   File.Delete("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gtrqhemtxx.html

[F07] 创建目录（含多级）
来源：http://dali.pycfn.com/Article/details/gtofsenndk.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhoulong.xyz/Article/details/gtmqlxlicv.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.quarkkingdee.top/Article/details/gttxioyzej.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.guannengcc.top/Article/details/gtoaszvvgw.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yuanzhike.top/Article/details/gtmjemlufr.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.feifeiyinyue.top/Article/details/gtptldwcsn.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jqgufenzy.top/Article/details/gtufejouxp.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.chenzaomai.com/Article/details/gtpwzgxiwk.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.chenlongwang.top/Article/details/gtkrmwghdk.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gtuudzfetx.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yueranfly.top/Article/details/gtgxssqfcm.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnwdoflew.html

JS:   fs.readdirSync("dir")
来源：http://dali.gogol.net.cn/Article/details/gtubrznrif.html

TS:   fs.readdirSync("dir")
来源：http://dali.cucudq.cn/Article/details/gtijuvgfom.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.ivvv.top/Article/details/gthoxiqtww.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.xylfe.cn/Article/details/gtogwbfswu.html

Ruby: Dir.children("dir")
来源：http://dali.xinyue.icu/Article/details/gtnnqqsfwr.html

C#:   Directory.GetFiles("dir")
来源：http://dali.snrcjt.cn/Article/details/gtldxciglm.html

[F09] 获取文件大小
来源：http://dali.shanyushiyangtech.top/Article/details/gtidpqezer.html

Py:   os.path.getsize("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtrddlhfki.html

PHP:  filesize("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gtrvwavvfz.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jinqigufen.top/Article/details/gtgycqgqsb.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzbgeyesw.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.gaohongyu789.top/Article/details/gtjldyoaem.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jqgfzy.top/Article/details/gtupjhrzup.html

Ruby: File.size("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtyfsfbzhf.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.quarkkingdee.top/Article/details/gthvlcxuml.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gtdbqiqtjy.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yj20258888.top/Article/details/gtxcamqoue.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hywenlv.cn/Article/details/gtxdldfcrc.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtprbgqplt.html

TS:   path.extname("a.txt")
来源：http://dali.cashguo.top/Article/details/gtbdzjmmen.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.shzxlz.cn/Article/details/gtptxplhlp.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtkwsbiith.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yj20258888.top/Article/details/gtktoddeih.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtyzetntgy.html

[F11] 复制与移动文件
来源：http://dali.wangdashe.top/Article/details/gtpyqkbwqf.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgfsvxuiu.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gtcqyqvwua.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtgrjewkam.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yueranfly.top/Article/details/gtcpkpomdk.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.9152youxi.cn/Article/details/gtolhgakap.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hnqzz.top/Article/details/gtfqzxovre.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.c1oappe.top/Article/details/gtigvxolbb.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xziqi.cn/Article/details/gtnqzycrfl.html

[F12] CSV 读写
来源：http://dali.gotoacloud.top/Article/details/gtzectdkhs.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ppjwa.cn/Article/details/gtxxufipio.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yj202588.top/Article/details/gtxftkodhe.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.fzhhl.top/Article/details/gtkwjkmqvl.html

TS:   // 同上
来源：http://dali.tian-w.cn/Article/details/gtaukfccii.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.shzxlz.cn/Article/details/gtyvhbaolj.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhixingplan.top/Article/details/gtizqxdaho.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.svipenyu.cn/Article/details/gtgeuvture.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.shzxlz.cn/Article/details/gtvreldhjj.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtqalvpryb.html

G. 面向对象
来源：http://dali.nanxinkj.top/Article/details/gtgfieaqrk.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtxuxhodxk.html

[G01] 定义类
来源：http://dali.jqgfzy.top/Article/details/gtokjubhoq.html

Py:   class User: pass
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpytuvpnv.html

PHP:  class User {}
来源：http://dali.cheryme.top/Article/details/gtijgkbrjb.html

JS:   class User {}
来源：http://dali.quarkkingdee.top/Article/details/gtazyjhwni.html

TS:   class User { name: string = ""; }
来源：http://dali.pengpengdd.cyou/Article/details/gtstudjkby.html

Java: class User {}
来源：http://dali.shuidangran.top/Article/details/gtppezmkvx.html

Go:   type User struct { Name string }
来源：http://dali.andypj.xyz/Article/details/gtaptqtqoe.html

Ruby: class User; end
来源：http://dali.yuxming.cn/Article/details/gtfmzcgjes.html

C#:   class User {}
来源：http://dali.yangfankeji.com/Article/details/gtjdzqnmkx.html

[G02] 构造函数
来源：http://dali.jlsjyb.cn/Article/details/gtlpwtfdld.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.svipenyu.cn/Article/details/gtxxpsdrfe.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.tian-w.cn/Article/details/gtfkbyshyp.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yvedp.cn/Article/details/gtwijbttjr.html

TS:   constructor(public name: string) {}
来源：http://dali.yanxiufei.cn/Article/details/gtjhvgiiiu.html

Java: User(String name) { this.name = name; }
来源：http://dali.gzhubu.top/Article/details/gtgghftnly.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hnqzz.top/Article/details/gtahppoepk.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.wangdashe.top/Article/details/gthgiuatno.html

C#:   public User(string name) { Name = name; }
来源：http://dali.snrcjt.cn/Article/details/gtrmuvtnht.html

[G03] 实例属性
来源：http://dali.hfpthk.cn/Article/details/gtzolqapzn.html

Py:   self.name = "x"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgeutvozg.html

PHP:  public string $name = "x";
来源：http://dali.316326.xyz/Article/details/gtbgynqzeg.html

JS:   this.name = "x";
来源：http://dali.svipenyu.cn/Article/details/gtssfehpnm.html

TS:   name: string = "x";
来源：http://dali.yanxiufei.cn/Article/details/gtclcdeoqb.html

Java: private String name;
来源：http://dali.nanxinkj.top/Article/details/gtjkjlbisn.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.shzxlz.cn/Article/details/gtmuyaqfug.html

Ruby: @name = "x"
来源：http://dali.yj202588.top/Article/details/gtmljynrxf.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.andypj.xyz/Article/details/gtyubtimce.html

[G04] 定义方法
来源：http://dali.vqdsnc.cn/Article/details/gtepapulkb.html

Py:   def greet(self): return self.name
来源：http://dali.smart0.xyz/Article/details/gtemnyavkn.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.haohaochexian.top/Article/details/gttithcxxv.html

JS:   greet() { return this.name; }
来源：http://dali.guowangkeji.top/Article/details/gtqzqurnep.html

TS:   greet(): string { return this.name; }
来源：http://dali.cdnleiting.top/Article/details/gtfeaamjkf.html

Java: String greet() { return name; }
来源：http://dali.jqgufenzy.top/Article/details/gtxhzrjreu.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.gzhubu.top/Article/details/gteoasjllm.html

Ruby: def greet; @name; end
来源：http://dali.gotoacloud.top/Article/details/gtwmroycqa.html

C#:   public string Greet() => Name;
来源：http://dali.mhx1999.top/Article/details/gtgkzeflhr.html

[G05] 继承
来源：http://dali.ehwqpu.com/Article/details/gtzzhraauh.html

Py:   class Admin(User): pass
来源：http://dali.daxiang520.top/Article/details/gtjbxqzvne.html

PHP:  class Admin extends User {}
来源：http://dali.xinyue.icu/Article/details/gtepjelekb.html

JS:   class Admin extends User {}
来源：http://dali.jyoumei.cn/Article/details/gtduenyxaq.html

TS:   class Admin extends User {}
来源：http://dali.yonumen.top/Article/details/gtqsjalgie.html

Java: class Admin extends User {}
来源：http://dali.jlsjyb.cn/Article/details/gtmempnxev.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yj20258888.top/Article/details/gthudevutr.html

Ruby: class Admin < User; end
来源：http://dali.chenzaomai.com/Article/details/gtwzvapree.html

C#:   class Admin : User {}
来源：http://dali.pycfn.com/Article/details/gthfnilabm.html

[G06] 重写方法
来源：http://dali.cqqwz.cn/Article/details/gtcgfyafjv.html

Py:   def greet(self): return "admin"
来源：http://dali.mhx1999.top/Article/details/gtgzsvzxeg.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhoulong.xyz/Article/details/gtjjybjbce.html

JS:   greet() { return "admin"; }
来源：http://dali.yvedp.cn/Article/details/gtrbvhghlu.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yangfankeji.com/Article/details/gtrewgumkz.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ivvv.top/Article/details/gtjjhphhtz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jinghuilouyu.cn/Article/details/gtjwwiidju.html

Ruby: def greet; "admin"; end
来源：http://dali.jyoumei.cn/Article/details/gtbeqzzypz.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhixingplan.top/Article/details/gttrcimnzf.html

[G07] 调用父类方法
来源：http://dali.wangdashe.top/Article/details/gtmygglbqz.html

Py:   super().greet()
来源：http://dali.feifeiyinyue.top/Article/details/gtqjlgmwcb.html

PHP:  parent::greet();
来源：http://dali.redwolf501.top/Article/details/gtvbywxzsu.html

JS:   super.greet();
来源：http://dali.jinghuilouyu.cn/Article/details/gtputcoesj.html

TS:   super.greet();
来源：http://dali.kuanghao11.cn/Article/details/gtiqeqvnpz.html

Java: super.greet();
来源：http://dali.ydzc1.top/Article/details/gtffllnukc.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.fengsongda.top/Article/details/gtlnrsteyj.html

Ruby: super
来源：http://dali.havefunace.top/Article/details/gtkdccwwqs.html

C#:   base.Greet();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthjygdgqy.html

[G08] 静态方法与属性
来源：http://dali.jiagoushi.top/Article/details/gtzgfolmkj.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.wangdashe.top/Article/details/gtivsktxzk.html

PHP:  public static function f() {}
来源：http://dali.sufxvd.cn/Article/details/gtkkqjkelj.html

JS:   static f() {}
来源：http://dali.316326.xyz/Article/details/gtjbwlikex.html

TS:   static f(): void {}
来源：http://dali.yonumen.top/Article/details/gtdzsmmmxw.html

Java: static void f() {}
来源：http://dali.yongpay.top/Article/details/gtkhfjvtxa.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yongpay.top/Article/details/gtewkdbblf.html

Ruby: def self.f; end
来源：http://dali.aibaodan.cn/Article/details/gtjdxjcmoa.html

C#:   public static void F() {}
来源：http://dali.nwbrower.top/Article/details/gtiettfawq.html

[G09] 接口 / 抽象类
来源：http://dali.zhiwuduotai.top/Article/details/gtmxqwutnb.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.havefunace.top/Article/details/gtxxbiceop.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xziqi.cn/Article/details/gtcrcglhts.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.tianlin.xyz/Article/details/gtnyqazlgj.html

TS:   interface Shape { area(): number; }
来源：http://dali.meibo888.top/Article/details/gtjhnmociu.html

Java: interface Shape { double area(); }
来源：http://dali.c1oappe.top/Article/details/gtbzmanmzi.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.vqdsnc.cn/Article/details/gtpoubjakf.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.fengsongda.top/Article/details/gtrpplssql.html

C#:   interface IShape { double Area(); }
来源：http://dali.hysaishi.cn/Article/details/gtpudcnsda.html

[G10] 访问控制
来源：http://dali.hysaishi.cn/Article/details/gtkcxjccvx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.chenjidiqi.icu/Article/details/gtvoyxvoyk.html

PHP:  public / protected / private
来源：http://dali.snrcjt.cn/Article/details/gtwpdopune.html

JS:   #private 字段；其余公开
来源：http://dali.feifeiyinyue.top/Article/details/gtggzbxszn.html

TS:   public / protected / private
来源：http://dali.quarkkingdee.top/Article/details/gtdndaekox.html

Java: public / protected / private / 默认包级
来源：http://dali.dashuyun.cn/Article/details/gtjmlgwwuo.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.pycfn.com/Article/details/gtaosalklx.html

Ruby: public / protected / private
来源：http://dali.ehwqpu.com/Article/details/gtbmvjnrws.html

C#:   public / protected / private / internal
来源：http://dali.gaohongyu789.top/Article/details/gtzqnwxsij.html

[G11] getter / setter
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlrardxpq.html

Py:   @property 与 @x.setter
来源：http://dali.guowangkeji.top/Article/details/gtfyhpedev.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.guowangkeji.top/Article/details/gtpfdzwrth.html

JS:   get name() { return this._name; }
来源：http://dali.ppjwa.cn/Article/details/gtiiosujzf.html

TS:   get name(): string { return this._name; }
来源：http://dali.dashuyun.cn/Article/details/gtimkpyupc.html

Java: public String getName() { return name; }
来源：http://dali.cheryme.top/Article/details/gtemlhxoco.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.316326.xyz/Article/details/gttqgzrsph.html

Ruby: attr_accessor :name
来源：http://dali.bjfxy.top/Article/details/gtvudingcu.html

C#:   public string Name { get; set; }
来源：http://dali.tianlin.xyz/Article/details/gtqwyzynjm.html

[G12] 对象转字符串
来源：http://dali.andypj.xyz/Article/details/gtsxyowtwv.html

Py:   def __str__(self): return self.name
来源：http://dali.kuanghao11.cn/Article/details/gtuovqureb.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hywenlv.cn/Article/details/gtzlgevgja.html

JS:   toString() { return this.name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtrpqjooxa.html

TS:   toString(): string { return this.name; }
来源：http://dali.hnqzz.top/Article/details/gtdujoumgi.html

Java: @Override public String toString() { return name; }
来源：http://dali.birdmap.top/Article/details/gtuczxtjai.html


<!-- 参考信息 -->