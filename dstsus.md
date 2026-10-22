代发 wailian999

Py:   for ch in s: print(ch)
来源：http://dali.ehwqpu.com/Article/details/gt2vvtubjao.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhoulong.xyz/Article/details/gt2ylagdgtn.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhengqikj.top/Article/details/gt2xrxmwptv.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xsxlaomb.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2xpflmoic.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.xuanzx.com/Article/details/gt2syqwuhgw.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.0kj1m.cn/Article/details/gt2sjxtxfur.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhixingplan.top/Article/details/gt2xdnpnmns.html

[E14] URL 编码与 Base64
来源：http://dali.tian-w.cn/Article/details/gt2phiqkepq.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hnqzz.top/Article/details/gt2imtibtue.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yuanzhike.top/Article/details/gt2sulofyxj.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.chenzaomai.com/Article/details/gt2wqeqfyys.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bolfwmfj.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.feifeiyinyue.top/Article/details/gt2vbhnvrxa.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jinqigfzy.top/Article/details/gt2wdumlgwg.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.dashuyun.cn/Article/details/gt2sdurdpye.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jqgfzy.top/Article/details/gt2wqzquacz.html

[E15] HTML 转义 / 反转义
来源：http://dali.guowangkeji.top/Article/details/gt2rdejmzep.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.andypj.xyz/Article/details/gt2hfjlizlc.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qesdoboj.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uxipztwa.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jyoumei.cn/Article/details/gt2vxvmvmkh.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.sweek.top/Article/details/gt2hfbdzqtd.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.sufxvd.cn/Article/details/gt2ralihxei.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yuxming.cn/Article/details/gt2dzrygkkh.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yuanzhike.top/Article/details/gt2ylkkzhdz.html

[E16] 数字千分位
来源：http://dali.yueranfly.top/Article/details/gt2pvvvhzhh.html

Py:   f"{1234567:,}"
来源：http://dali.andypj.xyz/Article/details/gt2pvupjxkj.html

PHP:  number_format(1234567);
来源：http://dali.jqgfzy.top/Article/details/gt2cfkashde.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.cdnleiting.top/Article/details/gt2xysrfils.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yonumen.top/Article/details/gt2hfqiriet.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.sysykeji.top/Article/details/gt2xoumghwu.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.birdmap.top/Article/details/gt2dkjdetdy.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.wangshuangyany.cn/Article/details/gt2vacwphpg.html

C#:   1234567.ToString("N0")
来源：http://dali.gaohongyu789.top/Article/details/gt2wqoidjtn.html

[E17] 首字母大写
来源：http://dali.yj202588.top/Article/details/gt2vipshnsr.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.0kj1m.cn/Article/details/gt2sixljjsi.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jqgfzy.top/Article/details/gt2wbkbsbkg.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jiagoushi.top/Article/details/gt2wvxylaek.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yanxiufei.cn/Article/details/gt2crfyfsil.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yj202588.top/Article/details/gt2wffvtlir.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.pycfn.com/Article/details/gt2okfwkqnf.html

Ruby: s.capitalize
来源：http://dali.pycfn.com/Article/details/gt2tvrtoqvo.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.nwbrower.top/Article/details/gt2gpmvipsz.html

[E18] 模板占位符替换
来源：http://dali.vqdsnc.cn/Article/details/gt2uhhcedwq.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yonumen.top/Article/details/gt2swiljdos.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.ydzc1.top/Article/details/gt2xvlkdqzf.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ukwqhmnf.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.xziqi.cn/Article/details/gt2wtmzwdcx.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.cashguo.top/Article/details/gt2rzcbrttz.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.cdnleiting.top/Article/details/gt2duhidegz.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yangfankeji.com/Article/details/gt2mpnrhduj.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.cqqwz.cn/Article/details/gt2gnlitukz.html

[E19] 多行文本按行拆分
来源：http://dali.gogol.net.cn/Article/details/gt2akwaskmj.html

Py:   s.splitlines()
来源：http://dali.bjfxy.top/Article/details/gt2aovbstqk.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.9152youxi.cn/Article/details/gt2bfudqfyx.html

JS:   s.split(/\r?\n/)
来源：http://dali.9152youxi.cn/Article/details/gt2pkqvtdpc.html

TS:   s.split(/\r?\n/)
来源：http://dali.cheryme.top/Article/details/gt2bexsvuiu.html

Java: s.lines().toList()
来源：http://dali.jinqigfzy.top/Article/details/gt2gbykruqw.html

Go:   strings.Split(s, "\n")
来源：http://dali.dashuyun.cn/Article/details/gt2wdxdegfr.html

Ruby: s.lines
来源：http://dali.gogol.net.cn/Article/details/gt2fewzktey.html

C#:   s.Split('\n')
来源：http://dali.chenlongwang.top/Article/details/gt2vwqvosgf.html

[E20] 判断字符串是否为空
来源：http://dali.jinqigfzy.top/Article/details/gt2vpoeykmv.html

Py:   if not s:
来源：http://dali.dianchejie.cn/Article/details/gt2ntgqpiev.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.chenjidiqi.icu/Article/details/gt2rqxpcqna.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.xinyue.icu/Article/details/gt2devcfzkl.html

TS:   if (s === "") {}
来源：http://dali.jinqigfzy.top/Article/details/gt2sxllpvnb.html

Java: if (s.isEmpty()) {}
来源：http://dali.jinqigufen.top/Article/details/gt2wjndwrar.html

Go:   if s == "" {}
来源：http://dali.pycfn.com/Article/details/gt2sjufdqga.html

Ruby: if s.empty?
来源：http://dali.cucudq.cn/Article/details/gt2zfqxmwim.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.shuidangran.top/Article/details/gt2lsaxjwad.html

[E21] 超长截断加省略号
来源：http://dali.nanxinkj.top/Article/details/gt2hhuacxrl.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.pengpengdd.cyou/Article/details/gt2esvlwkcl.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.cucudq.cn/Article/details/gt2bxwmswah.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yuxming.cn/Article/details/gt2vkevwagv.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2wdsuxyry.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.xuanzx.com/Article/details/gt2fpxcsqqg.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.ydzc1.top/Article/details/gt2ujmfjsfc.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.pycfn.com/Article/details/gt2uxjdfxey.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.bjfxy.top/Article/details/gt2uvdpepvx.html

[E22] 字节长度与字符长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2diggztlu.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.dashuyun.cn/Article/details/gt2djkjeema.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yj202588.top/Article/details/gt2mebxaoit.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shuidangran.top/Article/details/gt2wzqwuycv.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kjpgnbah.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhoulong.xyz/Article/details/gt2lpgznhps.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jlsjyb.cn/Article/details/gt2accbajmo.html

Ruby: s.bytesize;  s.length
来源：http://dali.redwolf501.top/Article/details/gt2rtgteovi.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.xylfe.cn/Article/details/gt2wwvrxgbf.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2nqbyzuoo.html

F. 文件与目录
来源：http://dali.xuetiantiany.cn/Article/details/gt2ppybiadg.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2mapbluxr.html

[F01] 读取整个文件
来源：http://dali.yj20258888.top/Article/details/gt2sgakbibw.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2schwvdgv.html

PHP:  file_get_contents("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gt2exluadzq.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.gaohongyu789.top/Article/details/gt2mieppayp.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.ivvv.top/Article/details/gt2kyydxyxo.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.gaohongyu789.top/Article/details/gt2inbwirkx.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jianghu66.top/Article/details/gt2oyhofjoc.html

Ruby: File.read("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2slsfidet.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gt2eytodgju.html

[F02] 逐行读取文件
来源：http://dali.aibaodan.cn/Article/details/gt2epybxcfj.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.dashuyun.cn/Article/details/gt2fwoqzdmt.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhengqikj.top/Article/details/gt2pkvntgnl.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yuanzhike.top/Article/details/gt2utkalcgu.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.dashuyun.cn/Article/details/gt2szzwmcwl.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jqgufenzy.top/Article/details/gt2knhccvlx.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.daria6918.cn/Article/details/gt2zlozskuc.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.xylfe.cn/Article/details/gt2pmujmaak.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yj202588.top/Article/details/gt2cgrucvvq.html

[F03] 写入文件（覆盖）
来源：http://dali.bjfxy.top/Article/details/gt2nweosrmv.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.nanxinkj.top/Article/details/gt2qcsolwkw.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.hysaishi.cn/Article/details/gt2avelprtz.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.feifeiyinyue.top/Article/details/gt2lxdutqrn.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gaohongyu789.top/Article/details/gt2dbtfzxxw.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.dashuyun.cn/Article/details/gt2ltlrmoog.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.cashguo.top/Article/details/gt2pnyspulx.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.nanxinkj.top/Article/details/gt2murzqbwj.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.sufxvd.cn/Article/details/gt2xxzlqayt.html

[F04] 追加写入文件
来源：http://dali.yj202588.top/Article/details/gt2ftvljjru.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.quarkkingdee.top/Article/details/gt2ziyfdmqw.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zycfv.cn/Article/details/gt2gwamjbbg.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hnxiangtu.top/Article/details/gt2bvoftgrl.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.c1oappe.top/Article/details/gt2oqozzngn.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.feifeiyinyue.top/Article/details/gt2fndnxggj.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.wangshuangyany.cn/Article/details/gt2gmdmxhrg.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.snrcjt.cn/Article/details/gt2uqzlbkko.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.chenjidiqi.icu/Article/details/gt2opnannkk.html

[F05] 判断文件或目录是否存在
来源：http://dali.yanxiufei.cn/Article/details/gt2byhrfjxg.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.svipenyu.cn/Article/details/gt2psgeodsw.html

PHP:  file_exists("a.txt");
来源：http://dali.yonumen.top/Article/details/gt2grpisdis.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2jzyyxzyv.html

TS:   fs.existsSync("a.txt")
来源：http://dali.cucudq.cn/Article/details/gt2ibsyrwqg.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.pycfn.com/Article/details/gt2zlzrrpkn.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.xuetiantiany.cn/Article/details/gt2vqadnnwv.html

Ruby: File.exist?("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2xeqdodov.html

C#:   File.Exists("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bcrmhgmz.html

[F06] 删除文件
来源：http://dali.aizwys.cn/Article/details/gt2evkpzzgj.html

Py:   os.remove("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2ncnkhywk.html

PHP:  unlink("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gt2jpnwesxm.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2oagjhaau.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qpsehcre.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2snjbdrea.html

Go:   os.Remove("a.txt")
来源：http://dali.cashguo.top/Article/details/gt2nwdjzipc.html

Ruby: File.delete("a.txt")
来源：http://dali.hammf.cn/Article/details/gt2zydtxgbx.html

C#:   File.Delete("a.txt");
来源：http://dali.daria6918.cn/Article/details/gt2lxhvkudr.html

[F07] 创建目录（含多级）
来源：http://dali.vqdsnc.cn/Article/details/gt2mumyvmth.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.feifeiyinyue.top/Article/details/gt2kehlqzfs.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.guowangkeji.top/Article/details/gt2oulhdbyt.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nwbrower.top/Article/details/gt2gicwbjqi.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gzhubu.top/Article/details/gt2xuvnmcka.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.wangshuangyany.cn/Article/details/gt2jbzqhary.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.fzhhl.top/Article/details/gt2gtsvajbz.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.fengsongda.top/Article/details/gt2qhfuofsq.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.cucudq.cn/Article/details/gt2esnsissp.html

[F08] 遍历目录
来源：http://dali.yanxiufei.cn/Article/details/gt2bdrfhckq.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.guannengcc.top/Article/details/gt2leflmmby.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yueranfly.top/Article/details/gt2jqavkzfb.html

JS:   fs.readdirSync("dir")
来源：http://dali.0kj1m.cn/Article/details/gt2hpehcdbj.html

TS:   fs.readdirSync("dir")
来源：http://dali.birdmap.top/Article/details/gt2axpjyaxf.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hysaishi.cn/Article/details/gt2nptyfmcw.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hnxiangtu.top/Article/details/gt2eytljolk.html

Ruby: Dir.children("dir")
来源：http://dali.zhongyouzk.top/Article/details/gt2jufopdjz.html

C#:   Directory.GetFiles("dir")
来源：http://dali.sufxvd.cn/Article/details/gt2clkzaxgr.html

[F09] 获取文件大小
来源：http://dali.shzxlz.cn/Article/details/gt2uszqsasf.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2esdifiwz.html

PHP:  filesize("a.txt");
来源：http://dali.aizwys.cn/Article/details/gt2xynkxrhr.html

JS:   fs.statSync("a.txt").size
来源：http://dali.pycfn.com/Article/details/gt2uulddaox.html

TS:   fs.statSync("a.txt").size
来源：http://dali.pycfn.com/Article/details/gt2bjshfxvc.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2urglybln.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.chenlongwang.top/Article/details/gt2aqmtmetx.html

Ruby: File.size("a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2lclgkclq.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.gzhubu.top/Article/details/gt2dwvcnpys.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.fzhhl.top/Article/details/gt2dxolpars.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2ftcgnvju.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yuanzhike.top/Article/details/gt2wzmbexkz.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2tajerrnr.html

TS:   path.extname("a.txt")
来源：http://dali.meibo888.top/Article/details/gt2pxkdayfy.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hammf.cn/Article/details/gt2yfxhjwte.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2sfrjaikq.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2iuzgiyyd.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2qxrmljrg.html

[F11] 复制与移动文件
来源：http://dali.jyoumei.cn/Article/details/gt2eaqtwuri.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.pycfn.com/Article/details/gt2vdhdiqzx.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.gzhubu.top/Article/details/gt2vrvpioux.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xinyue.icu/Article/details/gt2olukqxxa.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.birdmap.top/Article/details/gt2kuxcdzof.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jqgfzy.top/Article/details/gt2rfueabhz.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.mhx1999.top/Article/details/gt2fjxdcwyc.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2wrkcpxug.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.tianlin.xyz/Article/details/gt2hmvlnifm.html

[F12] CSV 读写
来源：http://dali.ydzc1.top/Article/details/gt2cktsnxlt.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.cqqwz.cn/Article/details/gt2fdahjjtz.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xziqi.cn/Article/details/gt2nhocdcmx.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yangfankeji.com/Article/details/gt2rimcxyac.html

TS:   // 同上
来源：http://dali.yvedp.cn/Article/details/gt2zhnknytm.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hfpthk.cn/Article/details/gt2duakuxgs.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.sysykeji.top/Article/details/gt2mihksunj.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yuxming.cn/Article/details/gt2uwozqepe.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.xziqi.cn/Article/details/gt2ldntgmum.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2fcdzjfle.html

G. 面向对象
来源：http://dali.ivvv.top/Article/details/gt2nixqvret.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2ocrkxhsq.html

[G01] 定义类
来源：http://dali.xuanzx.com/Article/details/gt2fddfokwv.html

Py:   class User: pass
来源：http://dali.ehwqpu.com/Article/details/gt2ndviifhl.html

PHP:  class User {}
来源：http://dali.0kj1m.cn/Article/details/gt2qcbokuqo.html

JS:   class User {}
来源：http://dali.ehwqpu.com/Article/details/gt2gbfzmydp.html

TS:   class User { name: string = ""; }
来源：http://dali.fengsongda.top/Article/details/gt2ihzdigxm.html

Java: class User {}
来源：http://dali.yuanzhike.top/Article/details/gt2nkcdgrzs.html

Go:   type User struct { Name string }
来源：http://dali.meibo888.top/Article/details/gt2iggmurrh.html

Ruby: class User; end
来源：http://dali.yonumen.top/Article/details/gt2uaqdmlpg.html

C#:   class User {}
来源：http://dali.jinqigufen.top/Article/details/gt2nxdjqnhg.html

[G02] 构造函数
来源：http://dali.gogol.net.cn/Article/details/gt2qdfiusyy.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.pycfn.com/Article/details/gt2ozfgvakk.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.smart0.xyz/Article/details/gt2wwkrzfzf.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.chenlongwang.top/Article/details/gt2nmgnepow.html

TS:   constructor(public name: string) {}
来源：http://dali.zdqjudy.top/Article/details/gt2spvlivxp.html

Java: User(String name) { this.name = name; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2ydxdhnuz.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cashguo.top/Article/details/gt2mkfkvrtq.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yangfankeji.com/Article/details/gt2mklmnuap.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hysaishi.cn/Article/details/gt2awkhtpju.html

[G03] 实例属性
来源：http://dali.yuanzhike.top/Article/details/gt2hojpxccp.html

Py:   self.name = "x"
来源：http://dali.shangyingyoupin.top/Article/details/gt2vcdvopab.html

PHP:  public string $name = "x";
来源：http://dali.cqqwz.cn/Article/details/gt2csxopbof.html

JS:   this.name = "x";
来源：http://dali.nanxinkj.top/Article/details/gt2qetigrqo.html

TS:   name: string = "x";
来源：http://dali.9152youxi.cn/Article/details/gt2ghxystol.html

Java: private String name;
来源：http://dali.birdmap.top/Article/details/gt2zvuaewkd.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hongshengwenyu.top/Article/details/gt2ymzkysdy.html

Ruby: @name = "x"
来源：http://dali.yuxming.cn/Article/details/gt2lniatbow.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jlsjyb.cn/Article/details/gt2kitzfkuw.html

[G04] 定义方法
来源：http://dali.hnxiangtu.top/Article/details/gt2bwjezuxl.html

Py:   def greet(self): return self.name
来源：http://dali.gaohongyu789.top/Article/details/gt2mviltrkl.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.pycfn.com/Article/details/gt2bxohmknj.html

JS:   greet() { return this.name; }
来源：http://dali.hnqzz.top/Article/details/gt2axttvmid.html

TS:   greet(): string { return this.name; }
来源：http://dali.bjfxy.top/Article/details/gt2ndqbpyfh.html

Java: String greet() { return name; }
来源：http://dali.cdnleiting.top/Article/details/gt2ipbwuodj.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.shzxlz.cn/Article/details/gt2qybmknzl.html

Ruby: def greet; @name; end
来源：http://dali.yvedp.cn/Article/details/gt2vklettgv.html

C#:   public string Greet() => Name;
来源：http://dali.hammf.cn/Article/details/gt2edkhhkqd.html

[G05] 继承
来源：http://dali.jyoumei.cn/Article/details/gt2yghdtogy.html

Py:   class Admin(User): pass
来源：http://dali.zdqjudy.top/Article/details/gt2iwmgyfyd.html

PHP:  class Admin extends User {}
来源：http://dali.jlsjyb.cn/Article/details/gt2iyzxnazq.html

JS:   class Admin extends User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fyxkmghi.html

TS:   class Admin extends User {}
来源：http://dali.yuxming.cn/Article/details/gt2dupfkotx.html

Java: class Admin extends User {}
来源：http://dali.zhoulong.xyz/Article/details/gt2kwzirnqf.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shzxlz.cn/Article/details/gt2ymexxfkt.html

Ruby: class Admin < User; end
来源：http://dali.xuetiantiany.cn/Article/details/gt2lndwitdb.html

C#:   class Admin : User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2foikfpfo.html

[G06] 重写方法
来源：http://dali.redwolf501.top/Article/details/gt2fmydvyzo.html

Py:   def greet(self): return "admin"
来源：http://dali.sysykeji.top/Article/details/gt2upbrzrdh.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jqgufenzy.top/Article/details/gt2wnblcktu.html

JS:   greet() { return "admin"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wcydoazg.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ppjwa.cn/Article/details/gt2wvutuubm.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yvedp.cn/Article/details/gt2mbllnqri.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.guowangkeji.top/Article/details/gt2eocfanof.html

Ruby: def greet; "admin"; end
来源：http://dali.zhixingplan.top/Article/details/gt2jgedppmr.html

C#:   public override string Greet() => "admin";
来源：http://dali.nanxinkj.top/Article/details/gt2abqnbviq.html

[G07] 调用父类方法
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2riiehurq.html

Py:   super().greet()
来源：http://dali.chenjidiqi.icu/Article/details/gt2etdduuce.html

PHP:  parent::greet();
来源：http://dali.yuanzhike.top/Article/details/gt2hwwhalbg.html

JS:   super.greet();
来源：http://dali.xylfe.cn/Article/details/gt2abpymdca.html

TS:   super.greet();
来源：http://dali.yj202588.top/Article/details/gt2osusuhvh.html

Java: super.greet();
来源：http://dali.aibaodan.cn/Article/details/gt2sulvsmij.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fbdpppfg.html

Ruby: super
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sbksckpz.html

C#:   base.Greet();
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mgixdjfs.html

[G08] 静态方法与属性
来源：http://dali.wangdashe.top/Article/details/gt2sagljtek.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.fzhhl.top/Article/details/gt2ponmccdf.html

PHP:  public static function f() {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lbzrydym.html

JS:   static f() {}
来源：http://dali.yj20258.top/Article/details/gt2rzcmqstr.html

TS:   static f(): void {}
来源：http://dali.nanxinkj.top/Article/details/gt2bcgehtby.html

Java: static void f() {}
来源：http://dali.yonumen.top/Article/details/gt2gflnjrtr.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.tianlin.xyz/Article/details/gt2oouskxas.html

Ruby: def self.f; end
来源：http://dali.smart0.xyz/Article/details/gt2aupynkup.html

C#:   public static void F() {}
来源：http://dali.jinqigfzy.top/Article/details/gt2cvqjungb.html

[G09] 接口 / 抽象类
来源：http://dali.hysaishi.cn/Article/details/gt2avmrzfqe.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.fengsongda.top/Article/details/gt2moxkiukj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.dianchejie.cn/Article/details/gt2vlnmebsi.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hammf.cn/Article/details/gt2wzyzzsbh.html

TS:   interface Shape { area(): number; }
来源：http://dali.xylfe.cn/Article/details/gt2hspbczaf.html

Java: interface Shape { double area(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2urqnlwfy.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.sysykeji.top/Article/details/gt2hjnllxoj.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.quarkkingdee.top/Article/details/gt2hxwndlig.html

C#:   interface IShape { double Area(); }
来源：http://dali.ppjwa.cn/Article/details/gt2bhwrpgvf.html

[G10] 访问控制
来源：http://dali.xylfe.cn/Article/details/gt2ytesdkmd.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xinyue.icu/Article/details/gt2mnrkryof.html

PHP:  public / protected / private
来源：http://dali.tian-w.cn/Article/details/gt2idlgqhcs.html

JS:   #private 字段；其余公开
来源：http://dali.redwolf501.top/Article/details/gt2tiivyfme.html

TS:   public / protected / private
来源：http://dali.xziqi.cn/Article/details/gt2ntahmtuy.html

Java: public / protected / private / 默认包级
来源：http://dali.hammf.cn/Article/details/gt2rhopmgxx.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.birdmap.top/Article/details/gt2vcqldtkm.html

Ruby: public / protected / private
来源：http://dali.nanxuanxn.top/Article/details/gt2lqkjfdzx.html

C#:   public / protected / private / internal
来源：http://dali.jqgfzy.top/Article/details/gt2futwgwpn.html

[G11] getter / setter
来源：http://dali.cashguo.top/Article/details/gt2kstsjvbl.html

Py:   @property 与 @x.setter
来源：http://dali.feifeiyinyue.top/Article/details/gt2gyloqbty.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zdqjudy.top/Article/details/gt2sttzueok.html

JS:   get name() { return this._name; }
来源：http://dali.daria6918.cn/Article/details/gt2kxwcfpmj.html

TS:   get name(): string { return this._name; }
来源：http://dali.cdnleiting.top/Article/details/gt2llvbrfua.html

Java: public String getName() { return name; }
来源：http://dali.ivvv.top/Article/details/gt2uxfgdvuq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hongshengwenyu.top/Article/details/gt2hffydkfq.html


<!-- 参考信息 -->