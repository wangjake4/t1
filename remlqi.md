代发 wailian999

Py:   for ch in s: print(ch)
来源：http://dali.jiagoushi.top/Article/details/gtusqakbvs.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.ybcxt.top/Article/details/gtchwygcpv.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.feifeiyinyue.top/Article/details/gthiixzcci.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.svipenyu.cn/Article/details/gtnbvnyndy.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.guowangkeji.top/Article/details/gtexpqyesk.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.sufxvd.cn/Article/details/gthbzcnqkj.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.sysykeji.top/Article/details/gtqyrfcpse.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.nanxuanxn.top/Article/details/gtgpbnrxzk.html

[E14] URL 编码与 Base64
来源：http://dali.shuidangran.top/Article/details/gteggmivgq.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.meibo888.top/Article/details/gtbkdyuwje.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jlsjyb.cn/Article/details/gtjobzrflv.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.tanke756.top/Article/details/gtqrrrrsvw.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.wangdashe.top/Article/details/gtgikhvfpl.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.daria6918.cn/Article/details/gtnqikduih.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.aibaodan.cn/Article/details/gtbfkjmcuy.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.vqdsnc.cn/Article/details/gtwzhickkc.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.shanyushiyangtech.top/Article/details/gttlteilax.html

[E15] HTML 转义 / 反转义
来源：http://dali.yanxiufei.cn/Article/details/gtvokczsat.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.tanke756.top/Article/details/gtrfwabncx.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.xuanzx.com/Article/details/gtbnwnocgi.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.gogol.net.cn/Article/details/gtjxdnvwpr.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxltrbzsh.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.tanke756.top/Article/details/gthmxkopmh.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.dashuyun.cn/Article/details/gtfyveyybc.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.ppjwa.cn/Article/details/gtsphxqhgn.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yanxiufei.cn/Article/details/gtieivrzie.html

[E16] 数字千分位
来源：http://dali.jlsjyb.cn/Article/details/gtxqmwqnpd.html

Py:   f"{1234567:,}"
来源：http://dali.yuxming.cn/Article/details/gtoacpiknq.html

PHP:  number_format(1234567);
来源：http://dali.shanyushiyangtech.top/Article/details/gtponswhcv.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.wangdashe.top/Article/details/gtqjmvjncq.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.quarkkingdee.top/Article/details/gtsiyofcdx.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yj202588.top/Article/details/gtcmngwvuy.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.nanxuanxn.top/Article/details/gtafnuzysj.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.nanxuanxn.top/Article/details/gticbsdlmb.html

C#:   1234567.ToString("N0")
来源：http://dali.dashuyun.cn/Article/details/gtyadadixr.html

[E17] 首字母大写
来源：http://dali.xinyue.icu/Article/details/gtdvdskcod.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.pycfn.com/Article/details/gtnjybqqts.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.daxiang520.top/Article/details/gtepwyvcra.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hnqzz.top/Article/details/gtwkgthtzd.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhixingplan.top/Article/details/gtbvichepx.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtmvzluyjn.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.svipenyu.cn/Article/details/gtdukmlqig.html

Ruby: s.capitalize
来源：http://dali.gotoacloud.top/Article/details/gtjpfllhhv.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.quarkkingdee.top/Article/details/gtdepykwve.html

[E18] 模板占位符替换
来源：http://dali.aizwys.cn/Article/details/gtdohbquaa.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhengqikj.top/Article/details/gtshoouzxw.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hnqzz.top/Article/details/gtpzrdxegc.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yueranfly.top/Article/details/gtclwlazdl.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hnqzz.top/Article/details/gtaodhlucr.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.snrcjt.cn/Article/details/gtfdxvjjpa.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.dashuyun.cn/Article/details/gtwanqvofx.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.meibo888.top/Article/details/gtxxdomixg.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.daxiang520.top/Article/details/gtyrrjxvlh.html

[E19] 多行文本按行拆分
来源：http://dali.ybcxt.top/Article/details/gtghaxcprq.html

Py:   s.splitlines()
来源：http://dali.jinghuilouyu.cn/Article/details/gtraohtjxm.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhengqikj.top/Article/details/gttacnuzky.html

JS:   s.split(/\r?\n/)
来源：http://dali.shzxlz.cn/Article/details/gtepvisovj.html

TS:   s.split(/\r?\n/)
来源：http://dali.yuanzhike.top/Article/details/gtmgdabrlq.html

Java: s.lines().toList()
来源：http://dali.zhixingplan.top/Article/details/gtxtgfgncg.html

Go:   strings.Split(s, "\n")
来源：http://dali.fengsongda.top/Article/details/gtipctrzdx.html

Ruby: s.lines
来源：http://dali.hfpthk.cn/Article/details/gtwqlnzbkv.html

C#:   s.Split('\n')
来源：http://dali.xylfe.cn/Article/details/gtpfguygmt.html

[E20] 判断字符串是否为空
来源：http://dali.shzxlz.cn/Article/details/gtpfdlfzlz.html

Py:   if not s:
来源：http://dali.tian-w.cn/Article/details/gtwgyewydn.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.dashuyun.cn/Article/details/gtrnjbfejx.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.quarkkingdee.top/Article/details/gtqxqyktru.html

TS:   if (s === "") {}
来源：http://dali.chenjidiqi.icu/Article/details/gtbgmojccp.html

Java: if (s.isEmpty()) {}
来源：http://dali.hysaishi.cn/Article/details/gttvsfdtqy.html

Go:   if s == "" {}
来源：http://dali.cucudq.cn/Article/details/gtltfjsoxx.html

Ruby: if s.empty?
来源：http://dali.hfpthk.cn/Article/details/gtgsihxyyc.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.aizwys.cn/Article/details/gtxsjnvktk.html

[E21] 超长截断加省略号
来源：http://dali.dashuyun.cn/Article/details/gtgvajqnwn.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.birdmap.top/Article/details/gtndxomeyc.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.chenzaomai.com/Article/details/gtkuvlekod.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.guannengcc.top/Article/details/gtabodnjll.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.meibo888.top/Article/details/gtiaubddyt.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.wangdashe.top/Article/details/gtisqbjunw.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.nwbrower.top/Article/details/gtdasyfyyr.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.shanyushiyangtech.top/Article/details/gtwxdstmzd.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.cheryme.top/Article/details/gtibobppsz.html

[E22] 字节长度与字符长度
来源：http://dali.jinqigfzy.top/Article/details/gtlvxqwmxu.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbfixvegt.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cdnleiting.top/Article/details/gthpphfkew.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.andypj.xyz/Article/details/gtywljvspi.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.guowangkeji.top/Article/details/gtyzwqgexg.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hfpthk.cn/Article/details/gtrogkdsru.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.chenjidiqi.icu/Article/details/gtyiwdzghz.html

Ruby: s.bytesize;  s.length
来源：http://dali.shuidangran.top/Article/details/gtbwrlpszj.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhoulong.xyz/Article/details/gtjyejpswm.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtayrhsinw.html

F. 文件与目录
来源：http://dali.xinyue.icu/Article/details/gtxtbdqulo.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gteeidssta.html

[F01] 读取整个文件
来源：http://dali.zdqjudy.top/Article/details/gtuqtkvwnr.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.xziqi.cn/Article/details/gtltsdsctf.html

PHP:  file_get_contents("a.txt");
来源：http://dali.guannengcc.top/Article/details/gtptcamdsx.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.cqqwz.cn/Article/details/gteezczpvh.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.cqqwz.cn/Article/details/gtwslgkwik.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.shangyingyoupin.top/Article/details/gtdgquersi.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hnxiangtu.top/Article/details/gtmoxowbwy.html

Ruby: File.read("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtuffqguot.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gtrzuhyreg.html

[F02] 逐行读取文件
来源：http://dali.jianghu66.top/Article/details/gtnxcdzzmj.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.andypj.xyz/Article/details/gtzdxahkrr.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hfpthk.cn/Article/details/gtqgvwvtxk.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jlsjyb.cn/Article/details/gtiofriuag.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shuidangran.top/Article/details/gtaaxyfdsn.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdjdtcded.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zdqjudy.top/Article/details/gtfoyjpfzg.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.andypj.xyz/Article/details/gtgxqwceze.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.bjfxy.top/Article/details/gtgaqmfkce.html

[F03] 写入文件（覆盖）
来源：http://dali.daria6918.cn/Article/details/gtxdrforak.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.snrcjt.cn/Article/details/gtkyefoyvb.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xuanzx.com/Article/details/gtutoqftsg.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.fzhhl.top/Article/details/gtnnmcctat.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hammf.cn/Article/details/gtdektgzvf.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.gaohongyu789.top/Article/details/gtyxqhptlz.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.daria6918.cn/Article/details/gtkbgxabod.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jqgufenzy.top/Article/details/gtzemiywbo.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.tanke756.top/Article/details/gtjiotjqyz.html

[F04] 追加写入文件
来源：http://dali.havefunace.top/Article/details/gtrdomdiqn.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.shangyingyoupin.top/Article/details/gtnxbkyppk.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtahqmjxga.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yanxiufei.cn/Article/details/gtpqayqkuv.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yj202588.top/Article/details/gtnnnfbarg.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.guannengcc.top/Article/details/gtztozwhux.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.cheryme.top/Article/details/gtbforpltp.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.sufxvd.cn/Article/details/gtvpiwrcft.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yj20258.top/Article/details/gtxhbyfmuf.html

[F05] 判断文件或目录是否存在
来源：http://dali.yangfankeji.com/Article/details/gtxlqgifwc.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfdhqbgeq.html

PHP:  file_exists("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gtybfjbfng.html

JS:   fs.existsSync("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtajmjwwng.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hammf.cn/Article/details/gtupvjilsy.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jlsjyb.cn/Article/details/gtulrnpynd.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hysaishi.cn/Article/details/gtxonyaipo.html

Ruby: File.exist?("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtmiquoqtd.html

C#:   File.Exists("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbxznqpvk.html

[F06] 删除文件
来源：http://dali.gaohongyu789.top/Article/details/gtltmzqizj.html

Py:   os.remove("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtduevlcrm.html

PHP:  unlink("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gtlmvmevnt.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtjjygoaxj.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmqvhicxw.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.redwolf501.top/Article/details/gtiovkvdue.html

Go:   os.Remove("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtogmrvtar.html

Ruby: File.delete("a.txt")
来源：http://dali.ivvv.top/Article/details/gteckflyzm.html

C#:   File.Delete("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gtyifbzlwn.html

[F07] 创建目录（含多级）
来源：http://dali.xinyue.icu/Article/details/gtlvnesjzv.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.feifeiyinyue.top/Article/details/gtzkansftq.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.wangshuangyany.cn/Article/details/gtljophywg.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzuysodvi.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.havefunace.top/Article/details/gttadfgtrq.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gttutkqyvd.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.sweek.top/Article/details/gtiabqqmxv.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.sxryk.cn/Article/details/gtsxsurqdh.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jinghuilouyu.cn/Article/details/gtvshqrumf.html

[F08] 遍历目录
来源：http://dali.jiagoushi.top/Article/details/gtekgvamhm.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.chenjidiqi.icu/Article/details/gtxlzxpaax.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.snrcjt.cn/Article/details/gtuxhmehsy.html

JS:   fs.readdirSync("dir")
来源：http://dali.daxiang520.top/Article/details/gtgicslvlw.html

TS:   fs.readdirSync("dir")
来源：http://dali.316326.xyz/Article/details/gtlytdonnm.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.chenlongwang.top/Article/details/gttvhhgwpe.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ybcxt.top/Article/details/gtxdrvzgyh.html

Ruby: Dir.children("dir")
来源：http://dali.yueranfly.top/Article/details/gtnklkbqul.html

C#:   Directory.GetFiles("dir")
来源：http://dali.daria6918.cn/Article/details/gtwkailabc.html

[F09] 获取文件大小
来源：http://dali.sysykeji.top/Article/details/gtukwoxvsu.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gthhpuxmtm.html

PHP:  filesize("a.txt");
来源：http://dali.cucudq.cn/Article/details/gttdckfigz.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yuanzhike.top/Article/details/gtejtckyoy.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jinqigufen.top/Article/details/gtmdszjyik.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhixingplan.top/Article/details/gthqmhxwmf.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.dianchejie.cn/Article/details/gtcqyeypzc.html

Ruby: File.size("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtlcymlhfk.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xuetiantiany.cn/Article/details/gtjfjduyoo.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hysaishi.cn/Article/details/gtmkatavyc.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsrawgzdy.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.cdnleiting.top/Article/details/gtvtyrdqge.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtodmlxyte.html

TS:   path.extname("a.txt")
来源：http://dali.hammf.cn/Article/details/gtarppxiod.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yj20258.top/Article/details/gtgtghxekv.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zycfv.cn/Article/details/gttuzngdrs.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.bjfxy.top/Article/details/gtsirgmfxg.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtsxbuwcqk.html

[F11] 复制与移动文件
来源：http://dali.vqdsnc.cn/Article/details/gtjwoxavys.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xinyue.icu/Article/details/gtesfydzpt.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.chenlongwang.top/Article/details/gtwgjyujjv.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yuanzhike.top/Article/details/gtckkmbdja.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.redwolf501.top/Article/details/gtsusbztpd.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yonumen.top/Article/details/gtqvqlqgmf.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.chenjidiqi.icu/Article/details/gtcrnlbgwq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhixingplan.top/Article/details/gtdlemqfzc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.sysykeji.top/Article/details/gtnqwcysrr.html

[F12] CSV 读写
来源：http://dali.sysykeji.top/Article/details/gtyyivizzq.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jqgfzy.top/Article/details/gtemrkzdxl.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.cucudq.cn/Article/details/gtipdpiilw.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.9152youxi.cn/Article/details/gtsqkhazdo.html

TS:   // 同上
来源：http://dali.pycfn.com/Article/details/gtvnhuvxav.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jqgufenzy.top/Article/details/gtxpomxgsy.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yj20258.top/Article/details/gtdyxcadkv.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.gotoacloud.top/Article/details/gtwpfyxipn.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.fengsongda.top/Article/details/gttomjyloo.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gttarntblf.html

G. 面向对象
来源：http://dali.chenlongwang.top/Article/details/gtuyiimiiy.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtxaonpzdj.html

[G01] 定义类
来源：http://dali.shzxlz.cn/Article/details/gtdrnzepzl.html

Py:   class User: pass
来源：http://dali.ydzc1.top/Article/details/gttkrmrfgi.html

PHP:  class User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkyuimxad.html

JS:   class User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtlrhgsnxz.html

TS:   class User { name: string = ""; }
来源：http://dali.ydzc1.top/Article/details/gtcakxcngy.html

Java: class User {}
来源：http://dali.mhx1999.top/Article/details/gtxcclkiwb.html

Go:   type User struct { Name string }
来源：http://dali.nanxinkj.top/Article/details/gtfrwhoviw.html

Ruby: class User; end
来源：http://dali.cashguo.top/Article/details/gtmlknrlei.html

C#:   class User {}
来源：http://dali.aibaodan.cn/Article/details/gtffnyobbp.html

[G02] 构造函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtetindwbc.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.snrcjt.cn/Article/details/gtybamjnes.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtbdzerhfn.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hywenlv.cn/Article/details/gtniamrskp.html

TS:   constructor(public name: string) {}
来源：http://dali.cheryme.top/Article/details/gtmdsblpel.html

Java: User(String name) { this.name = name; }
来源：http://dali.yangfankeji.com/Article/details/gtvtypdoaq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hywenlv.cn/Article/details/gtojhtawdb.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.tianlin.xyz/Article/details/gtthgiawxd.html

C#:   public User(string name) { Name = name; }
来源：http://dali.dashuyun.cn/Article/details/gtlowlgfyh.html

[G03] 实例属性
来源：http://dali.chenzaomai.com/Article/details/gtwwrtcvrr.html

Py:   self.name = "x"
来源：http://dali.zhongyouzk.top/Article/details/gtmhpyrrxd.html

PHP:  public string $name = "x";
来源：http://dali.yj20258.top/Article/details/gtmjsqwvgo.html

JS:   this.name = "x";
来源：http://dali.nanxuanxn.top/Article/details/gtsydqruny.html

TS:   name: string = "x";
来源：http://dali.dashuyun.cn/Article/details/gtppdhylkj.html

Java: private String name;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsdzfixyi.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhengqikj.top/Article/details/gtkucuiazy.html

Ruby: @name = "x"
来源：http://dali.wangshuangyany.cn/Article/details/gteemhpisf.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.tanke756.top/Article/details/gtmoerfylr.html

[G04] 定义方法
来源：http://dali.yongpay.top/Article/details/gtogayjkrn.html

Py:   def greet(self): return self.name
来源：http://dali.dashuyun.cn/Article/details/gtmtiwebwa.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlemfetks.html

JS:   greet() { return this.name; }
来源：http://dali.tianlin.xyz/Article/details/gtalzlggsy.html

TS:   greet(): string { return this.name; }
来源：http://dali.yvedp.cn/Article/details/gtliyidiei.html

Java: String greet() { return name; }
来源：http://dali.gogol.net.cn/Article/details/gtqaxikzdm.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zycfv.cn/Article/details/gtemoadrdg.html

Ruby: def greet; @name; end
来源：http://dali.redwolf501.top/Article/details/gtbbiglckb.html

C#:   public string Greet() => Name;
来源：http://dali.0kj1m.cn/Article/details/gtwoqrpbuu.html

[G05] 继承
来源：http://dali.hfpthk.cn/Article/details/gtkcgumwhq.html

Py:   class Admin(User): pass
来源：http://dali.andypj.xyz/Article/details/gtrlpaupme.html

PHP:  class Admin extends User {}
来源：http://dali.yvedp.cn/Article/details/gtnmnjxwdb.html

JS:   class Admin extends User {}
来源：http://dali.ehwqpu.com/Article/details/gtobsmrgij.html

TS:   class Admin extends User {}
来源：http://dali.hnqzz.top/Article/details/gtvekxeoax.html

Java: class Admin extends User {}
来源：http://dali.ivvv.top/Article/details/gtywcfzpeh.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.snrcjt.cn/Article/details/gtpfobadtr.html

Ruby: class Admin < User; end
来源：http://dali.hammf.cn/Article/details/gttjdyfbnn.html

C#:   class Admin : User {}
来源：http://dali.zdqjudy.top/Article/details/gtzhwiagkb.html

[G06] 重写方法
来源：http://dali.gaohongyu789.top/Article/details/gtkiajxpsu.html

Py:   def greet(self): return "admin"
来源：http://dali.fzhhl.top/Article/details/gtdivxhwla.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.0kj1m.cn/Article/details/gtpuvprlbr.html

JS:   greet() { return "admin"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjyblhwct.html

TS:   greet(): string { return "admin"; }
来源：http://dali.cqqwz.cn/Article/details/gtmtosmzog.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ehwqpu.com/Article/details/gttxnrxlqj.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hywenlv.cn/Article/details/gtmlffnyob.html

Ruby: def greet; "admin"; end
来源：http://dali.zdqjudy.top/Article/details/gtwzwmgolw.html

C#:   public override string Greet() => "admin";
来源：http://dali.andypj.xyz/Article/details/gtdekjusie.html

[G07] 调用父类方法
来源：http://dali.zhixingplan.top/Article/details/gtxctopvmz.html

Py:   super().greet()
来源：http://dali.zhengqikj.top/Article/details/gtwpzkeuhf.html

PHP:  parent::greet();
来源：http://dali.jinqigfzy.top/Article/details/gtmzuwcbrm.html

JS:   super.greet();
来源：http://dali.cucudq.cn/Article/details/gtpcohzzud.html

TS:   super.greet();
来源：http://dali.fengsongda.top/Article/details/gtalbdhkka.html

Java: super.greet();
来源：http://dali.mhx1999.top/Article/details/gtnpqymczp.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.chenlongwang.top/Article/details/gtsxhwqnnx.html

Ruby: super
来源：http://dali.nanxuanxn.top/Article/details/gtgexfohfu.html

C#:   base.Greet();
来源：http://dali.dianchejie.cn/Article/details/gtygqsotkb.html

[G08] 静态方法与属性
来源：http://dali.guowangkeji.top/Article/details/gtqnbwrulc.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yuanzhike.top/Article/details/gtqmspctar.html

PHP:  public static function f() {}
来源：http://dali.nwbrower.top/Article/details/gtcbnihhla.html

JS:   static f() {}
来源：http://dali.c1oappe.top/Article/details/gtdoufgnnj.html

TS:   static f(): void {}
来源：http://dali.zhongyouzk.top/Article/details/gtaybpmblg.html

Java: static void f() {}
来源：http://dali.zhixingplan.top/Article/details/gtpdrrxtmm.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yuanzhike.top/Article/details/gtrgnlandl.html

Ruby: def self.f; end
来源：http://dali.ppjwa.cn/Article/details/gtbjztjavb.html

C#:   public static void F() {}
来源：http://dali.dashuyun.cn/Article/details/gtwtcmxjue.html

[G09] 接口 / 抽象类
来源：http://dali.wangshuangyany.cn/Article/details/gtanirbbah.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hywenlv.cn/Article/details/gtkrkqkqbw.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.guannengcc.top/Article/details/gtjcurdryb.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jinqigufen.top/Article/details/gtwuukdalp.html

TS:   interface Shape { area(): number; }
来源：http://dali.feifeiyinyue.top/Article/details/gtqvrwgtfw.html

Java: interface Shape { double area(); }
来源：http://dali.ybcxt.top/Article/details/gtrxlcsomp.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.meibo888.top/Article/details/gtjcfvkojr.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.wangshuangyany.cn/Article/details/gtwmogjqwg.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhengqikj.top/Article/details/gthwethkpd.html

[G10] 访问控制
来源：http://dali.9152youxi.cn/Article/details/gtdjocdndz.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.chenjidiqi.icu/Article/details/gtuhrrfqbw.html

PHP:  public / protected / private
来源：http://dali.jqgfzy.top/Article/details/gtwzqyrabk.html

JS:   #private 字段；其余公开
来源：http://dali.ybcxt.top/Article/details/gtplohckhz.html

TS:   public / protected / private
来源：http://dali.tianlin.xyz/Article/details/gtczipbsed.html

Java: public / protected / private / 默认包级
来源：http://dali.aizwys.cn/Article/details/gtbkqekjrd.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.sufxvd.cn/Article/details/gtyeqhrzph.html

Ruby: public / protected / private
来源：http://dali.gotoacloud.top/Article/details/gtvapzivcl.html

C#:   public / protected / private / internal
来源：http://dali.zdqjudy.top/Article/details/gtcugslcxm.html

[G11] getter / setter
来源：http://dali.zdqjudy.top/Article/details/gtppwoavmn.html

Py:   @property 与 @x.setter
来源：http://dali.tianlin.xyz/Article/details/gtqdzdlexc.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jiagoushi.top/Article/details/gtezrdsdca.html

JS:   get name() { return this._name; }
来源：http://dali.sufxvd.cn/Article/details/gtahjhwuii.html

TS:   get name(): string { return this._name; }
来源：http://dali.fzhhl.top/Article/details/gtixgmlnfx.html

Java: public String getName() { return name; }
来源：http://dali.xylfe.cn/Article/details/gtarghxdyk.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jqgufenzy.top/Article/details/gtlqhiawxa.html


<!-- 参考信息 -->