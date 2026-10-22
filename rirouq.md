代发 wailian999

Py:   for ch in s: print(ch)
来源：http://dali.xinyue.icu/Article/details/gtbwknjbey.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.smart0.xyz/Article/details/gtdvfsghwb.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tianlin.xyz/Article/details/gtvwkgxowr.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.meibo888.top/Article/details/gtlijbybyg.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yvedp.cn/Article/details/gtwuzwedrp.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jyoumei.cn/Article/details/gtwejzaeiv.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.ehwqpu.com/Article/details/gtjmkgacdo.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.wangshuangyany.cn/Article/details/gtvmfnehzf.html

[E14] URL 编码与 Base64
来源：http://dali.redwolf501.top/Article/details/gtyiabckyw.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jinghuilouyu.cn/Article/details/gtvaewuodg.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yj20258888.top/Article/details/gtafczpdzi.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.andypj.xyz/Article/details/gtsxlrtszm.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.cheryme.top/Article/details/gtazmutkez.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.xuanzx.com/Article/details/gtpirhdalu.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hongshengwenyu.top/Article/details/gtpknjaiyu.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.vqdsnc.cn/Article/details/gtzmryjjdl.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yueranfly.top/Article/details/gtoddspqzx.html

[E15] HTML 转义 / 反转义
来源：http://dali.sxryk.cn/Article/details/gtypghzkkz.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jianghu66.top/Article/details/gtobxivhoe.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.daria6918.cn/Article/details/gtgngkhlbq.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.cheryme.top/Article/details/gtyqkykmpw.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.smart0.xyz/Article/details/gtbmkevnew.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.andypj.xyz/Article/details/gtldtwsrxx.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.dianchejie.cn/Article/details/gtmyzpyjco.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.aibaodan.cn/Article/details/gtlkktpxir.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.nwbrower.top/Article/details/gtabatcbjq.html

[E16] 数字千分位
来源：http://dali.gogol.net.cn/Article/details/gtnzdjoetj.html

Py:   f"{1234567:,}"
来源：http://dali.yj202588.top/Article/details/gtvqymxwjg.html

PHP:  number_format(1234567);
来源：http://dali.shzxlz.cn/Article/details/gtyzuwwzos.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.gzhubu.top/Article/details/gtemlyxhdz.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.wangshuangyany.cn/Article/details/gtguprgnhw.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yvedp.cn/Article/details/gtvxncvqxt.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.pengpengdd.cyou/Article/details/gtguijicgm.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhiwuduotai.top/Article/details/gtlemmdtdz.html

C#:   1234567.ToString("N0")
来源：http://dali.shanyushiyangtech.top/Article/details/gtfvavidsh.html

[E17] 首字母大写
来源：http://dali.316326.xyz/Article/details/gthwspbvik.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ehwqpu.com/Article/details/gtcshuaflr.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.haohaochexian.top/Article/details/gtijxoxwmf.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.tianlin.xyz/Article/details/gtgxuwesgf.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.haohaochexian.top/Article/details/gtuouggjos.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.sweek.top/Article/details/gtptrwdtfa.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.shangyingyoupin.top/Article/details/gtzjvegahf.html

Ruby: s.capitalize
来源：http://dali.jinghuilouyu.cn/Article/details/gtrpqqccqx.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ivvv.top/Article/details/gtdogibxxg.html

[E18] 模板占位符替换
来源：http://dali.fzhhl.top/Article/details/gtudfoethf.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.cheryme.top/Article/details/gtcvzmkmho.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.ppjwa.cn/Article/details/gtplqjmwgx.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hnqzz.top/Article/details/gtcntzbdwu.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.wangdashe.top/Article/details/gtmbqtwcca.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.wangdashe.top/Article/details/gtlivnvaxl.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.cqqwz.cn/Article/details/gtaveggjsu.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.aizwys.cn/Article/details/gtawiyibpo.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.sweek.top/Article/details/gtazzipkla.html

[E19] 多行文本按行拆分
来源：http://dali.sweek.top/Article/details/gttpilqgwm.html

Py:   s.splitlines()
来源：http://dali.ydzc1.top/Article/details/gtzxwykjpi.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.sufxvd.cn/Article/details/gtvxkkvbzo.html

JS:   s.split(/\r?\n/)
来源：http://dali.wangdashe.top/Article/details/gtpdkdnsxc.html

TS:   s.split(/\r?\n/)
来源：http://dali.316326.xyz/Article/details/gtlukxhbfv.html

Java: s.lines().toList()
来源：http://dali.nwbrower.top/Article/details/gtvvigmdbs.html

Go:   strings.Split(s, "\n")
来源：http://dali.tian-w.cn/Article/details/gthdfzzley.html

Ruby: s.lines
来源：http://dali.hammf.cn/Article/details/gtlffrwjqg.html

C#:   s.Split('\n')
来源：http://dali.zdqjudy.top/Article/details/gtmtmejhda.html

[E20] 判断字符串是否为空
来源：http://dali.9152youxi.cn/Article/details/gtohzvustk.html

Py:   if not s:
来源：http://dali.yanxiufei.cn/Article/details/gtdqacahkb.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.kuanghao11.cn/Article/details/gtecifxjdl.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jqgfzy.top/Article/details/gtreagoied.html

TS:   if (s === "") {}
来源：http://dali.0kj1m.cn/Article/details/gtfiqemnnf.html

Java: if (s.isEmpty()) {}
来源：http://dali.ehwqpu.com/Article/details/gtbrjsdipu.html

Go:   if s == "" {}
来源：http://dali.yvedp.cn/Article/details/gtkbbrdrly.html

Ruby: if s.empty?
来源：http://dali.zhiwuduotai.top/Article/details/gtshsevyur.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.sysykeji.top/Article/details/gtuhtcdutx.html

[E21] 超长截断加省略号
来源：http://dali.yongpay.top/Article/details/gtmrdazwyv.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.daria6918.cn/Article/details/gtsnmjgkom.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yanxiufei.cn/Article/details/gtygagrewp.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.kuanghao11.cn/Article/details/gtinmsxnrt.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jqgufenzy.top/Article/details/gtrhtcfdoz.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zycfv.cn/Article/details/gtyukrixqi.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.nanxuanxn.top/Article/details/gtkdubozpk.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.pycfn.com/Article/details/gtrqoxhqxt.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.daxiang520.top/Article/details/gtwikftjzs.html

[E22] 字节长度与字符长度
来源：http://dali.9152youxi.cn/Article/details/gtltbjkegq.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.aizwys.cn/Article/details/gtmlhrcjgx.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sufxvd.cn/Article/details/gtvzmlunyq.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.wangshuangyany.cn/Article/details/gtkefdjmce.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xziqi.cn/Article/details/gteokwrgkc.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.gaohongyu789.top/Article/details/gtherxyzsf.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.wangshuangyany.cn/Article/details/gttoikbchz.html

Ruby: s.bytesize;  s.length
来源：http://dali.daria6918.cn/Article/details/gtfkmavzmc.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.tian-w.cn/Article/details/gtkohecrqj.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtjuysejzt.html

F. 文件与目录
来源：http://dali.gaohongyu789.top/Article/details/gtjfkuwvyq.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtptakbxfv.html

[F01] 读取整个文件
来源：http://dali.nanxinkj.top/Article/details/gtlvkhmoxl.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.kuanghao11.cn/Article/details/gtmnawtrmb.html

PHP:  file_get_contents("a.txt");
来源：http://dali.guannengcc.top/Article/details/gtdbinxgjo.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.ehwqpu.com/Article/details/gtxngajmdo.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.tian-w.cn/Article/details/gtdgvnowck.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hnxiangtu.top/Article/details/gtfxlznavf.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.havefunace.top/Article/details/gtbypuxveh.html

Ruby: File.read("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtqstwihpu.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.bjfxy.top/Article/details/gthtansmzl.html

[F02] 逐行读取文件
来源：http://dali.quarkkingdee.top/Article/details/gtwlbtuuki.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xinyue.icu/Article/details/gtrottyihy.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yongpay.top/Article/details/gtjelwcurg.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yuxming.cn/Article/details/gtfkxweqtl.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sysykeji.top/Article/details/gtraxoqpnn.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yanxiufei.cn/Article/details/gtdkuchwxl.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.cheryme.top/Article/details/gtgjowcaqa.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.mhx1999.top/Article/details/gtytmmquhn.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hnqzz.top/Article/details/gtelwwlnaz.html

[F03] 写入文件（覆盖）
来源：http://dali.xylfe.cn/Article/details/gtoxppfxji.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yj20258888.top/Article/details/gtrxcshgxc.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.chenzaomai.com/Article/details/gtcrthstja.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.snrcjt.cn/Article/details/gtmajfevoq.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ivvv.top/Article/details/gtarydyjqt.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.sufxvd.cn/Article/details/gtwduehcvi.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.gotoacloud.top/Article/details/gtubdpwuwl.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.316326.xyz/Article/details/gtjofsitve.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.iojbl.cn/Article/details/gtpqanyquq.html

[F04] 追加写入文件
来源：http://dali.zhengqikj.top/Article/details/gtdyikmdhv.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jinghuilouyu.cn/Article/details/gtvnufrqyh.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yueranfly.top/Article/details/gtkzkjpakb.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hywenlv.cn/Article/details/gtqumvqwqx.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.chenjidiqi.icu/Article/details/gtlgzttvnf.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gtvxbxjklc.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.quarkkingdee.top/Article/details/gtnsgxtmvv.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hfpthk.cn/Article/details/gtjhauyybs.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.cheryme.top/Article/details/gtnzaqoajf.html

[F05] 判断文件或目录是否存在
来源：http://dali.redwolf501.top/Article/details/gtqjlwkoxs.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hysaishi.cn/Article/details/gtpjvvoede.html

PHP:  file_exists("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtazdgthdl.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yj20258.top/Article/details/gthbqilrop.html

TS:   fs.existsSync("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtajrsvynt.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.ivvv.top/Article/details/gtuqqjsxxy.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.meibo888.top/Article/details/gtebukyuvm.html

Ruby: File.exist?("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtwbrrwpwd.html

C#:   File.Exists("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtbfqgdwmv.html

[F06] 删除文件
来源：http://dali.vqdsnc.cn/Article/details/gtufpkbmka.html

Py:   os.remove("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtlmrnarxz.html

PHP:  unlink("a.txt");
来源：http://dali.hammf.cn/Article/details/gtfhkdexco.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtufijcrwx.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtzxadweoj.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jqgufenzy.top/Article/details/gtnsysefee.html

Go:   os.Remove("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmcxbfrtx.html

Ruby: File.delete("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtxhdihqrd.html

C#:   File.Delete("a.txt");
来源：http://dali.xuanzx.com/Article/details/gtwjwrrrga.html

[F07] 创建目录（含多级）
来源：http://dali.havefunace.top/Article/details/gtvbyiiazt.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.shuidangran.top/Article/details/gtluzxfebb.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yvedp.cn/Article/details/gtbqjvmxhx.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ywan-chungtsiang.top/Article/details/gthldjclwm.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cashguo.top/Article/details/gtbsyjjaxh.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jinqigfzy.top/Article/details/gtmltyqbqo.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hnxiangtu.top/Article/details/gtgtpkkqzp.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jyoumei.cn/Article/details/gtjdnjphow.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.bjfxy.top/Article/details/gthpqqtsno.html

[F08] 遍历目录
来源：http://dali.haohaochexian.top/Article/details/gtuqdnysev.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.chenzaomai.com/Article/details/gtiddkcani.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.havefunace.top/Article/details/gtzbnmudak.html

JS:   fs.readdirSync("dir")
来源：http://dali.ydzc1.top/Article/details/gtxghuflfu.html

TS:   fs.readdirSync("dir")
来源：http://dali.bjfxy.top/Article/details/gtoujafvzi.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jlsjyb.cn/Article/details/gtpftaufwf.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.dianchejie.cn/Article/details/gtgnxnmmlw.html

Ruby: Dir.children("dir")
来源：http://dali.yuanzhike.top/Article/details/gthzcmnelm.html

C#:   Directory.GetFiles("dir")
来源：http://dali.dashuyun.cn/Article/details/gtwkusrnuy.html

[F09] 获取文件大小
来源：http://dali.cheryme.top/Article/details/gtmxvzumqt.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gthzdtyncu.html

PHP:  filesize("a.txt");
来源：http://dali.gotoacloud.top/Article/details/gtlfdrevje.html

JS:   fs.statSync("a.txt").size
来源：http://dali.sxryk.cn/Article/details/gtbksesrjf.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhixingplan.top/Article/details/gtgjqyfaso.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlhinjxvu.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.iojbl.cn/Article/details/gtuuvbeepn.html

Ruby: File.size("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtpbgrdbsc.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jqgufenzy.top/Article/details/gtoumqvwiw.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.gotoacloud.top/Article/details/gtqijqjhdl.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtihqwroei.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.cashguo.top/Article/details/gtbfmzqddx.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.pycfn.com/Article/details/gtrxpjjgtm.html

TS:   path.extname("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtcynbhche.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.cdnleiting.top/Article/details/gtqmwsrgxi.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ydzc1.top/Article/details/gtpzazfufg.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtpfmflahz.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtiktnfskq.html

[F11] 复制与移动文件
来源：http://dali.tanke756.top/Article/details/gtjwvmnkem.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jiagoushi.top/Article/details/gtqwkxxrsn.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.tanke756.top/Article/details/gtfuqjbsxa.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shuidangran.top/Article/details/gtcoaloqet.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ivvv.top/Article/details/gtqhylqzsw.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xziqi.cn/Article/details/gtzwkudxka.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zdqjudy.top/Article/details/gtzijocrdl.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ydzc1.top/Article/details/gtiorblpxf.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.wangshuangyany.cn/Article/details/gtmkgjkowp.html

[F12] CSV 读写
来源：http://dali.zhiwuduotai.top/Article/details/gtokriharz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.tianlin.xyz/Article/details/gtimgkbzsv.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.gotoacloud.top/Article/details/gtpihncryd.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.cucudq.cn/Article/details/gtzqtkqbxu.html

TS:   // 同上
来源：http://dali.shanyushiyangtech.top/Article/details/gtaztfrive.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhixingplan.top/Article/details/gtcsjlgmtr.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yongpay.top/Article/details/gtdljhxojy.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hongshengwenyu.top/Article/details/gtbavpkpfd.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.shzxlz.cn/Article/details/gttqkkjyjq.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtzhkogoei.html

G. 面向对象
来源：http://dali.chenlongwang.top/Article/details/gtwfvqvzfk.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gthkohkmkm.html

[G01] 定义类
来源：http://dali.ydzc1.top/Article/details/gtotciprvm.html

Py:   class User: pass
来源：http://dali.chenzaomai.com/Article/details/gtqhwyhvyq.html

PHP:  class User {}
来源：http://dali.jyoumei.cn/Article/details/gttruaasdr.html

JS:   class User {}
来源：http://dali.9152youxi.cn/Article/details/gtwihrrjym.html

TS:   class User { name: string = ""; }
来源：http://dali.fengsongda.top/Article/details/gtrbeyigsw.html

Java: class User {}
来源：http://dali.hysaishi.cn/Article/details/gtkjkryoka.html

Go:   type User struct { Name string }
来源：http://dali.zhiwuduotai.top/Article/details/gtcuehcrbu.html

Ruby: class User; end
来源：http://dali.jinqigfzy.top/Article/details/gtaikvozgw.html

C#:   class User {}
来源：http://dali.cheryme.top/Article/details/gtftemgnmd.html

[G02] 构造函数
来源：http://dali.shangyingyoupin.top/Article/details/gtxoddsqpw.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.nwbrower.top/Article/details/gtvssqhyyz.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtjaatwlvw.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtofircscr.html

TS:   constructor(public name: string) {}
来源：http://dali.ybcxt.top/Article/details/gtnutcattu.html

Java: User(String name) { this.name = name; }
来源：http://dali.c1oappe.top/Article/details/gtmpepicwo.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ehwqpu.com/Article/details/gtnvvnztgy.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hnxiangtu.top/Article/details/gtuzpsdkqu.html

C#:   public User(string name) { Name = name; }
来源：http://dali.c1oappe.top/Article/details/gtgolyhrjo.html

[G03] 实例属性
来源：http://dali.xinyue.icu/Article/details/gtlnxtjdab.html

Py:   self.name = "x"
来源：http://dali.xuetiantiany.cn/Article/details/gtlszsborb.html

PHP:  public string $name = "x";
来源：http://dali.wangshuangyany.cn/Article/details/gtfxfhvskz.html

JS:   this.name = "x";
来源：http://dali.dashuyun.cn/Article/details/gtyzlmqhqo.html

TS:   name: string = "x";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtktewpdtw.html

Java: private String name;
来源：http://dali.ivvv.top/Article/details/gtafltmgro.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhixingplan.top/Article/details/gtzaabotqf.html

Ruby: @name = "x"
来源：http://dali.zhiwuduotai.top/Article/details/gtizmpdhdt.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jianghu66.top/Article/details/gtdmxhiavf.html

[G04] 定义方法
来源：http://dali.shzxlz.cn/Article/details/gtsfsvwzkl.html

Py:   def greet(self): return self.name
来源：http://dali.nanxinkj.top/Article/details/gtumpvqxiw.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.svipenyu.cn/Article/details/gtflpcrksu.html

JS:   greet() { return this.name; }
来源：http://dali.wangdashe.top/Article/details/gtxugczmns.html

TS:   greet(): string { return this.name; }
来源：http://dali.cashguo.top/Article/details/gtunxxkygh.html

Java: String greet() { return name; }
来源：http://dali.ivvv.top/Article/details/gtcxquycoi.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hnqzz.top/Article/details/gtkqvfhriy.html

Ruby: def greet; @name; end
来源：http://dali.tianlin.xyz/Article/details/gtiburrnux.html

C#:   public string Greet() => Name;
来源：http://dali.jianghu66.top/Article/details/gtqfhspqhm.html

[G05] 继承
来源：http://dali.tanke756.top/Article/details/gtganrieys.html

Py:   class Admin(User): pass
来源：http://dali.fengsongda.top/Article/details/gtdzhdfcgn.html

PHP:  class Admin extends User {}
来源：http://dali.andypj.xyz/Article/details/gtsvrilkbq.html

JS:   class Admin extends User {}
来源：http://dali.snrcjt.cn/Article/details/gtauypouxd.html

TS:   class Admin extends User {}
来源：http://dali.aibaodan.cn/Article/details/gttrlycmid.html

Java: class Admin extends User {}
来源：http://dali.ivvv.top/Article/details/gttxbovfte.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.pycfn.com/Article/details/gtlzoqrhxj.html

Ruby: class Admin < User; end
来源：http://dali.fengsongda.top/Article/details/gtwlcnuveq.html

C#:   class Admin : User {}
来源：http://dali.pengpengdd.cyou/Article/details/gtmwckfflu.html

[G06] 重写方法
来源：http://dali.cqqwz.cn/Article/details/gtlojpgyly.html

Py:   def greet(self): return "admin"
来源：http://dali.hysaishi.cn/Article/details/gtfklxicye.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.aizwys.cn/Article/details/gtqmjfmpcg.html

JS:   greet() { return "admin"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjnfbwrvh.html

TS:   greet(): string { return "admin"; }
来源：http://dali.nanxinkj.top/Article/details/gtzhzetybz.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.smart0.xyz/Article/details/gtlxsrooas.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jinqigufen.top/Article/details/gtmcunfrxo.html

Ruby: def greet; "admin"; end
来源：http://dali.cashguo.top/Article/details/gtpcgyemrq.html

C#:   public override string Greet() => "admin";
来源：http://dali.zdqjudy.top/Article/details/gtnbbkfbiy.html

[G07] 调用父类方法
来源：http://dali.yuanzhike.top/Article/details/gtopjvncxx.html

Py:   super().greet()
来源：http://dali.ybcxt.top/Article/details/gtozyqoywn.html

PHP:  parent::greet();
来源：http://dali.sufxvd.cn/Article/details/gtvrblfkkv.html

JS:   super.greet();
来源：http://dali.cashguo.top/Article/details/gtpvenybws.html

TS:   super.greet();
来源：http://dali.sxryk.cn/Article/details/gtisqnsnqj.html

Java: super.greet();
来源：http://dali.jlsjyb.cn/Article/details/gtjzozzera.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.gogol.net.cn/Article/details/gtovxailvb.html

Ruby: super
来源：http://dali.cashguo.top/Article/details/gthcnrrwnj.html

C#:   base.Greet();
来源：http://dali.xuetiantiany.cn/Article/details/gtyhnfjawa.html

[G08] 静态方法与属性
来源：http://dali.zycfv.cn/Article/details/gtqsrvsmqq.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.cdnleiting.top/Article/details/gttlxjqnst.html

PHP:  public static function f() {}
来源：http://dali.yvedp.cn/Article/details/gthqbtsupe.html

JS:   static f() {}
来源：http://dali.gotoacloud.top/Article/details/gtrbvtxaun.html

TS:   static f(): void {}
来源：http://dali.ivvv.top/Article/details/gtxnrkjwlx.html

Java: static void f() {}
来源：http://dali.shuidangran.top/Article/details/gttyoxqimu.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yj20258.top/Article/details/gtztognxkg.html

Ruby: def self.f; end
来源：http://dali.sysykeji.top/Article/details/gtfixttoti.html

C#:   public static void F() {}
来源：http://dali.cheryme.top/Article/details/gtjestoxkt.html

[G09] 接口 / 抽象类
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkcxeizro.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.daxiang520.top/Article/details/gtjpgsnxhv.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.wangdashe.top/Article/details/gtkfuombnt.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yueranfly.top/Article/details/gtblvuzyaf.html

TS:   interface Shape { area(): number; }
来源：http://dali.fengsongda.top/Article/details/gtlaebrpap.html

Java: interface Shape { double area(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtwriotjjp.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yangfankeji.com/Article/details/gtptevfvxl.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.aibaodan.cn/Article/details/gtnlxzkzjr.html

C#:   interface IShape { double Area(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgoyvgfpt.html

[G10] 访问控制
来源：http://dali.ivvv.top/Article/details/gtqzidlaxl.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yvedp.cn/Article/details/gtbwkeissc.html

PHP:  public / protected / private
来源：http://dali.jianghu66.top/Article/details/gtgmfczmhv.html

JS:   #private 字段；其余公开
来源：http://dali.jinqigfzy.top/Article/details/gtgeodwmnr.html

TS:   public / protected / private
来源：http://dali.yangfankeji.com/Article/details/gtgqcxxbua.html

Java: public / protected / private / 默认包级
来源：http://dali.zhiwuduotai.top/Article/details/gthlprfjxe.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.dashuyun.cn/Article/details/gtayhjpqhj.html

Ruby: public / protected / private
来源：http://dali.zhoulong.xyz/Article/details/gttqxjvcka.html

C#:   public / protected / private / internal
来源：http://dali.shuidangran.top/Article/details/gtkxdykvrg.html

[G11] getter / setter
来源：http://dali.xziqi.cn/Article/details/gtahpzkqsj.html

Py:   @property 与 @x.setter
来源：http://dali.nanxuanxn.top/Article/details/gthfsxbezo.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.c1oappe.top/Article/details/gtjovedzgh.html

JS:   get name() { return this._name; }
来源：http://dali.nanxuanxn.top/Article/details/gtmndnfudk.html

TS:   get name(): string { return this._name; }
来源：http://dali.meibo888.top/Article/details/gtygfqokix.html

Java: public String getName() { return name; }
来源：http://dali.zycfv.cn/Article/details/gtyuvuuewu.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.9152youxi.cn/Article/details/gtrimoiypz.html


<!-- 参考信息 -->