代发 wailian999

Py:   for ch in s: print(ch)
来源：http://dali.gogol.net.cn/Article/details/gtdoohwdrg.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yj202588.top/Article/details/gtqcywpynl.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkcdzsiko.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xziqi.cn/Article/details/gtfmbvutsw.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.cashguo.top/Article/details/gtfogybbej.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhijiandao.cn/Article/details/gtoeenxght.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.gaohongyu789.top/Article/details/gtxivyotum.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.redwolf501.top/Article/details/gtdnkfreud.html

[E14] URL 编码与 Base64
来源：http://dali.9152youxi.cn/Article/details/gtddwlkhpe.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hongshengwenyu.top/Article/details/gtthmyyrse.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtynfwydkr.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jqgfzy.top/Article/details/gtbtqeeulv.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yvedp.cn/Article/details/gtoecvvabd.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jyoumei.cn/Article/details/gtslhagake.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.sysykeji.top/Article/details/gtelmyqqjh.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xuanzx.com/Article/details/gtvktyjhuv.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hnxiangtu.top/Article/details/gtggxmehlv.html

[E15] HTML 转义 / 反转义
来源：http://dali.birdmap.top/Article/details/gtywaqkvka.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.bjfxy.top/Article/details/gtspyrqppq.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.chenzaomai.com/Article/details/gtzufkgcox.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtzpxgpjdi.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.gzhubu.top/Article/details/gtkdmyspux.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.shzxlz.cn/Article/details/gtkgzdfsfr.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.nwbrower.top/Article/details/gtzavpvwvo.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.meibo888.top/Article/details/gtpolpezpn.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zdqjudy.top/Article/details/gtfyxdxptv.html

[E16] 数字千分位
来源：http://dali.tian-w.cn/Article/details/gtmiklzlmo.html

Py:   f"{1234567:,}"
来源：http://dali.kuanghao11.cn/Article/details/gtjxpvexhi.html

PHP:  number_format(1234567);
来源：http://dali.0kj1m.cn/Article/details/gtbnjjyuqj.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.9152youxi.cn/Article/details/gtajjdrvcg.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhengqikj.top/Article/details/gtaaeoytpq.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hnqzz.top/Article/details/gtmamdthvu.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlnhaixad.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.chenlongwang.top/Article/details/gtbaufqmyp.html

C#:   1234567.ToString("N0")
来源：http://dali.hysaishi.cn/Article/details/gtkveckpgk.html

[E17] 首字母大写
来源：http://dali.chenlongwang.top/Article/details/gtjylndedr.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.birdmap.top/Article/details/gtefyiyecl.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hnxiangtu.top/Article/details/gtohuhsgjx.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtoilfvasi.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.fengsongda.top/Article/details/gtzkvqjzov.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yj20258888.top/Article/details/gtyduuztlz.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zycfv.cn/Article/details/gtdpyavwvp.html

Ruby: s.capitalize
来源：http://dali.yanxiufei.cn/Article/details/gtabdubvny.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.shanyushiyangtech.top/Article/details/gtnvrsnkya.html

[E18] 模板占位符替换
来源：http://dali.zhixingplan.top/Article/details/gttohtatha.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hnqzz.top/Article/details/gtvphjxxvl.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.pengpengdd.cyou/Article/details/gtxhljnyhz.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhoulong.xyz/Article/details/gtoqpqyqdw.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hnqzz.top/Article/details/gtuylgmmkt.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yongpay.top/Article/details/gthcmswngq.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jyoumei.cn/Article/details/gtkwbbaqts.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhongyouzk.top/Article/details/gttfawnujp.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.ydzc1.top/Article/details/gtefnpiluc.html

[E19] 多行文本按行拆分
来源：http://dali.yvedp.cn/Article/details/gtwgclkaep.html

Py:   s.splitlines()
来源：http://dali.guannengcc.top/Article/details/gtfqlddepw.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.xuetiantiany.cn/Article/details/gtprgwwhiv.html

JS:   s.split(/\r?\n/)
来源：http://dali.ydzc1.top/Article/details/gtelguyleb.html

TS:   s.split(/\r?\n/)
来源：http://dali.gaohongyu789.top/Article/details/gtxqgrjrjj.html

Java: s.lines().toList()
来源：http://dali.316326.xyz/Article/details/gtwlypznim.html

Go:   strings.Split(s, "\n")
来源：http://dali.svipenyu.cn/Article/details/gtxutkheij.html

Ruby: s.lines
来源：http://dali.jyoumei.cn/Article/details/gtzxgjpoip.html

C#:   s.Split('\n')
来源：http://dali.cucudq.cn/Article/details/gtjhimbboa.html

[E20] 判断字符串是否为空
来源：http://dali.pycfn.com/Article/details/gtzahszdge.html

Py:   if not s:
来源：http://dali.shzxlz.cn/Article/details/gtyjixkvkp.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yuanzhike.top/Article/details/gtxsuoujtv.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.wangdashe.top/Article/details/gtayseujye.html

TS:   if (s === "") {}
来源：http://dali.mhx1999.top/Article/details/gtbpqemyfz.html

Java: if (s.isEmpty()) {}
来源：http://dali.smart0.xyz/Article/details/gtzhfajtcp.html

Go:   if s == "" {}
来源：http://dali.jinqigfzy.top/Article/details/gtsrguijuk.html

Ruby: if s.empty?
来源：http://dali.wangdashe.top/Article/details/gtgejvnuqg.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.xinyue.icu/Article/details/gtgmrrzfqb.html

[E21] 超长截断加省略号
来源：http://dali.zhoulong.xyz/Article/details/gtxwqstwab.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.shanyushiyangkeji.top/Article/details/gthdhknyvm.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.sufxvd.cn/Article/details/gtnoxezkoh.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.redwolf501.top/Article/details/gthsympsbl.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gaohongyu789.top/Article/details/gtyeogoxpf.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hywenlv.cn/Article/details/gtsehfewbf.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cqqwz.cn/Article/details/gtregmufqm.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhiwuduotai.top/Article/details/gtoiredgrw.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.cheryme.top/Article/details/gthrmxtacg.html

[E22] 字节长度与字符长度
来源：http://dali.daria6918.cn/Article/details/gtyrmlqpvf.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.smart0.xyz/Article/details/gtjvqpcspt.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.tanke756.top/Article/details/gtjkdujwfs.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgjaquuox.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xinyue.icu/Article/details/gtkafmdszk.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.gaohongyu789.top/Article/details/gtynndjfsq.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hammf.cn/Article/details/gtephneleq.html

Ruby: s.bytesize;  s.length
来源：http://dali.cdnleiting.top/Article/details/gtdmmsybwe.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqfplqcfg.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtetslyugy.html

F. 文件与目录
来源：http://dali.yj20258888.top/Article/details/gtucjbyinb.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcbahtymf.html

[F01] 读取整个文件
来源：http://dali.birdmap.top/Article/details/gtcsijzmcv.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.gzhubu.top/Article/details/gthtiizxrx.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gthpoaulsi.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yj20258.top/Article/details/gthnrshymm.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jqgfzy.top/Article/details/gtjummjwmm.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.0kj1m.cn/Article/details/gtfscbitae.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.nanxuanxn.top/Article/details/gtjsfsxcjx.html

Ruby: File.read("a.txt")
来源：http://dali.316326.xyz/Article/details/gtdavqssmc.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zycfv.cn/Article/details/gtbetcuwyj.html

[F02] 逐行读取文件
来源：http://dali.cashguo.top/Article/details/gtwwdkkmau.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ivvv.top/Article/details/gtqrpdwwrz.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.shangyingyoupin.top/Article/details/gtlngyfvbv.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.c1oappe.top/Article/details/gttmvwvmqj.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.guowangkeji.top/Article/details/gtzltnmwog.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.xylfe.cn/Article/details/gtejpxrqgs.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yj20258888.top/Article/details/gtyvpokkfl.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhiwuduotai.top/Article/details/gtfufkorae.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hnxiangtu.top/Article/details/gtvgtzozsg.html

[F03] 写入文件（覆盖）
来源：http://dali.xuetiantiany.cn/Article/details/gtvhzpzwlp.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hongshengwenyu.top/Article/details/gtozrwvfqc.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.dashuyun.cn/Article/details/gtphcnypsz.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shanyushiyangtech.top/Article/details/gtduxwdsca.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hysaishi.cn/Article/details/gtkkakivqq.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.fengsongda.top/Article/details/gtybuikztx.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.hysaishi.cn/Article/details/gtsfypkpvb.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtddpjxrow.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yueranfly.top/Article/details/gtqffbgroo.html

[F04] 追加写入文件
来源：http://dali.xylfe.cn/Article/details/gttuazxyyj.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zycfv.cn/Article/details/gtbuhcorew.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.cheryme.top/Article/details/gttyuujedw.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cdnleiting.top/Article/details/gtwcdxxyev.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sysykeji.top/Article/details/gtppidzxxn.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.meibo888.top/Article/details/gtovobvsgo.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhengqikj.top/Article/details/gtqnyxynxt.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.ehwqpu.com/Article/details/gtxtwltyzd.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gtfzyalddv.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhongyouzk.top/Article/details/gtneyccvxu.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhiwuduotai.top/Article/details/gttfknhbcp.html

PHP:  file_exists("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gtirjkmviv.html

JS:   fs.existsSync("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtoezoxrpl.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtzjzxadfm.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jianghu66.top/Article/details/gtqwnzrmde.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jinqigufen.top/Article/details/gttbtugxtt.html

Ruby: File.exist?("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtyvucmffh.html

C#:   File.Exists("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtgecxjxqp.html

[F06] 删除文件
来源：http://dali.gzhubu.top/Article/details/gtlscdyfrk.html

Py:   os.remove("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtwsjlfuch.html

PHP:  unlink("a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gtbxgnerjo.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtgsmqymdn.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtftuccjij.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.svipenyu.cn/Article/details/gtccajnzly.html

Go:   os.Remove("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtswdejhbm.html

Ruby: File.delete("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtzmagqlqj.html

C#:   File.Delete("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gturrvikvy.html

[F07] 创建目录（含多级）
来源：http://dali.daxiang520.top/Article/details/gtqvyopsqr.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yuanzhike.top/Article/details/gtkgnpqokw.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yj202588.top/Article/details/gtopxyokhj.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ppjwa.cn/Article/details/gtjphjzvbx.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shanyushiyangtech.top/Article/details/gtswzferct.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtpvvrtpkv.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.cqqwz.cn/Article/details/gtslpppxmu.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.0kj1m.cn/Article/details/gtbuwhuaop.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.quarkkingdee.top/Article/details/gtompyrceu.html

[F08] 遍历目录
来源：http://dali.ybcxt.top/Article/details/gtjgfupcnw.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.sxryk.cn/Article/details/gtcskxkgmr.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.pengpengdd.cyou/Article/details/gtbkzdeiro.html

JS:   fs.readdirSync("dir")
来源：http://dali.ppjwa.cn/Article/details/gtwarpndka.html

TS:   fs.readdirSync("dir")
来源：http://dali.havefunace.top/Article/details/gtrsnckvey.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.aizwys.cn/Article/details/gtiijxzbkj.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.chenjidiqi.icu/Article/details/gtuksjpsil.html

Ruby: Dir.children("dir")
来源：http://dali.jyoumei.cn/Article/details/gtmkbahohn.html

C#:   Directory.GetFiles("dir")
来源：http://dali.fengsongda.top/Article/details/gtmokpcexs.html

[F09] 获取文件大小
来源：http://dali.feifeiyinyue.top/Article/details/gtwpdkpcik.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtzrunfvsy.html

PHP:  filesize("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gtfqefxhdn.html

JS:   fs.statSync("a.txt").size
来源：http://dali.guannengcc.top/Article/details/gtdlmfnryv.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhengqikj.top/Article/details/gtjgcrpcpv.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hnqzz.top/Article/details/gtdfsrynbn.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jlsjyb.cn/Article/details/gtlpoijqoz.html

Ruby: File.size("a.txt")
来源：http://dali.yongpay.top/Article/details/gtsubbofdm.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hfpthk.cn/Article/details/gtwtikytec.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.9152youxi.cn/Article/details/gtfabvusaf.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtgzafhgtm.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gtacpnawgh.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.ivvv.top/Article/details/gthmauddgh.html

TS:   path.extname("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gteukqtflf.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.xylfe.cn/Article/details/gtjiydvtbd.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gteoaxdrgi.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ivvv.top/Article/details/gtdokfawkn.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtavjrcabm.html

[F11] 复制与移动文件
来源：http://dali.nanxinkj.top/Article/details/gtomzhibnr.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.gzhubu.top/Article/details/gtocbruzka.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.cashguo.top/Article/details/gtgabepvsa.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.birdmap.top/Article/details/gtwzqijzym.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sweek.top/Article/details/gtskwvxzba.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhixingplan.top/Article/details/gtwkulutsy.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xuetiantiany.cn/Article/details/gteqfyjnsp.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yuxming.cn/Article/details/gttojyghcp.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jqgufenzy.top/Article/details/gtqjukwmbi.html

[F12] CSV 读写
来源：http://dali.iojbl.cn/Article/details/gtooiivlfg.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.pycfn.com/Article/details/gtumgbitwf.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yangfankeji.com/Article/details/gtjzclbqab.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.birdmap.top/Article/details/gtsgnbfzps.html

TS:   // 同上
来源：http://dali.shanyushiyangtech.top/Article/details/gtqveqjstm.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jlsjyb.cn/Article/details/gtnvbluzeg.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.pengpengdd.cyou/Article/details/gtzagdccla.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.nanxinkj.top/Article/details/gtsdqeufsc.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.cdnleiting.top/Article/details/gtibcxhxci.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtuvjbmrci.html

G. 面向对象
来源：http://dali.sufxvd.cn/Article/details/gtpjljvvuu.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtchhqzgqa.html

[G01] 定义类
来源：http://dali.snrcjt.cn/Article/details/gtfvvygzxb.html

Py:   class User: pass
来源：http://dali.yj20258888.top/Article/details/gtwipxmcou.html

PHP:  class User {}
来源：http://dali.xuanzx.com/Article/details/gtvhgzladj.html

JS:   class User {}
来源：http://dali.bjfxy.top/Article/details/gtupsnqhkh.html

TS:   class User { name: string = ""; }
来源：http://dali.zhongyouzk.top/Article/details/gtnimatdxy.html

Java: class User {}
来源：http://dali.9152youxi.cn/Article/details/gtnkzwnzil.html

Go:   type User struct { Name string }
来源：http://dali.jqgufenzy.top/Article/details/gtygsxfjdf.html

Ruby: class User; end
来源：http://dali.zhengqikj.top/Article/details/gtgnxmgijh.html

C#:   class User {}
来源：http://dali.jianghu66.top/Article/details/gtvgkqdxqs.html

[G02] 构造函数
来源：http://dali.bjfxy.top/Article/details/gtyzxlznef.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yueranfly.top/Article/details/gtccwnrwbj.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.snrcjt.cn/Article/details/gtdwhnxfok.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.cdnleiting.top/Article/details/gtojnblsen.html

TS:   constructor(public name: string) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtktgedfgb.html

Java: User(String name) { this.name = name; }
来源：http://dali.yonumen.top/Article/details/gtdjqkmnfu.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ivvv.top/Article/details/gtbymqifts.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zycfv.cn/Article/details/gtvwxiplgp.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hysaishi.cn/Article/details/gtkltmdmue.html

[G03] 实例属性
来源：http://dali.nanxinkj.top/Article/details/gtytevngtr.html

Py:   self.name = "x"
来源：http://dali.chenzaomai.com/Article/details/gtvbgaqkgb.html

PHP:  public string $name = "x";
来源：http://dali.jinqigfzy.top/Article/details/gtbqkekhck.html

JS:   this.name = "x";
来源：http://dali.redwolf501.top/Article/details/gtqmmrilyx.html

TS:   name: string = "x";
来源：http://dali.iojbl.cn/Article/details/gtebmxicnd.html

Java: private String name;
来源：http://dali.dianchejie.cn/Article/details/gtbzmlcqkf.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.shanyushiyangtech.top/Article/details/gtjbmncvcj.html

Ruby: @name = "x"
来源：http://dali.zhiwuduotai.top/Article/details/gtmqnvbtql.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.cucudq.cn/Article/details/gtpikncwdj.html

[G04] 定义方法
来源：http://dali.gogol.net.cn/Article/details/gtvclprdba.html

Py:   def greet(self): return self.name
来源：http://dali.bjfxy.top/Article/details/gtweeyelrd.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.nwbrower.top/Article/details/gtqifdsmie.html

JS:   greet() { return this.name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtavlvaaho.html

TS:   greet(): string { return this.name; }
来源：http://dali.ehwqpu.com/Article/details/gtghcilzyj.html

Java: String greet() { return name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtzuujogve.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xuetiantiany.cn/Article/details/gtkimerrmi.html

Ruby: def greet; @name; end
来源：http://dali.aibaodan.cn/Article/details/gthoeetzoz.html

C#:   public string Greet() => Name;
来源：http://dali.guannengcc.top/Article/details/gtxfbkhnrd.html

[G05] 继承
来源：http://dali.ivvv.top/Article/details/gttdlrmmsn.html

Py:   class Admin(User): pass
来源：http://dali.zhongyouzk.top/Article/details/gtxnzmdkhd.html

PHP:  class Admin extends User {}
来源：http://dali.hammf.cn/Article/details/gtgtjctyjv.html

JS:   class Admin extends User {}
来源：http://dali.fengsongda.top/Article/details/gtxlcisdkf.html

TS:   class Admin extends User {}
来源：http://dali.yj20258888.top/Article/details/gtnciuqlhc.html

Java: class Admin extends User {}
来源：http://dali.jinqigfzy.top/Article/details/gtjqtwsyqj.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.havefunace.top/Article/details/gtvdzrlqfs.html

Ruby: class Admin < User; end
来源：http://dali.yj20258888.top/Article/details/gtijgwkhkw.html

C#:   class Admin : User {}
来源：http://dali.ivvv.top/Article/details/gtlnogvlsf.html

[G06] 重写方法
来源：http://dali.ivvv.top/Article/details/gtkdgzbqqz.html

Py:   def greet(self): return "admin"
来源：http://dali.hysaishi.cn/Article/details/gtfsrlwxfe.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.wangshuangyany.cn/Article/details/gttqylpudg.html

JS:   greet() { return "admin"; }
来源：http://dali.zhoulong.xyz/Article/details/gtcxanhrvq.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yueranfly.top/Article/details/gtczljxtdu.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.meibo888.top/Article/details/gtdrbzondm.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jinqigufen.top/Article/details/gtyuhggyyo.html

Ruby: def greet; "admin"; end
来源：http://dali.jianghu66.top/Article/details/gtjktlljux.html

C#:   public override string Greet() => "admin";
来源：http://dali.hysaishi.cn/Article/details/gtqiluvgxz.html

[G07] 调用父类方法
来源：http://dali.zhengqikj.top/Article/details/gtnivwfzbe.html

Py:   super().greet()
来源：http://dali.yj20258.top/Article/details/gtppzcmobc.html

PHP:  parent::greet();
来源：http://dali.cucudq.cn/Article/details/gtbmcakntg.html

JS:   super.greet();
来源：http://dali.vqdsnc.cn/Article/details/gtxosmktwz.html

TS:   super.greet();
来源：http://dali.wangshuangyany.cn/Article/details/gtemyzdvop.html

Java: super.greet();
来源：http://dali.wangshuangyany.cn/Article/details/gtusrpmzvj.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.daria6918.cn/Article/details/gtrojlauxx.html

Ruby: super
来源：http://dali.kuanghao11.cn/Article/details/gtmkyrfdrr.html

C#:   base.Greet();
来源：http://dali.jyoumei.cn/Article/details/gtdojsbjec.html

[G08] 静态方法与属性
来源：http://dali.haohaochexian.top/Article/details/gtzwibygku.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.sufxvd.cn/Article/details/gtispfysrg.html

PHP:  public static function f() {}
来源：http://dali.wangdashe.top/Article/details/gtzjfadrfb.html

JS:   static f() {}
来源：http://dali.ivvv.top/Article/details/gtsqsfkcgb.html

TS:   static f(): void {}
来源：http://dali.hywenlv.cn/Article/details/gtunrsogda.html

Java: static void f() {}
来源：http://dali.snrcjt.cn/Article/details/gtqxpxhxas.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.redwolf501.top/Article/details/gtoleakezw.html

Ruby: def self.f; end
来源：http://dali.jiagoushi.top/Article/details/gtolueyxxp.html

C#:   public static void F() {}
来源：http://dali.xziqi.cn/Article/details/gtmvbqvuaz.html

[G09] 接口 / 抽象类
来源：http://dali.kuanghao11.cn/Article/details/gtbdkuwdye.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.aizwys.cn/Article/details/gtllsttktw.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.aibaodan.cn/Article/details/gtahuwoeqf.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jianghu66.top/Article/details/gtrpzfxniw.html

TS:   interface Shape { area(): number; }
来源：http://dali.pycfn.com/Article/details/gtyvcbebqt.html

Java: interface Shape { double area(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtvdorpfhf.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xylfe.cn/Article/details/gtoohjxtzf.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.nanxinkj.top/Article/details/gtrktlcdwb.html

C#:   interface IShape { double Area(); }
来源：http://dali.quarkkingdee.top/Article/details/gtdemakhre.html

[G10] 访问控制
来源：http://dali.havefunace.top/Article/details/gtpewtpwki.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yj202588.top/Article/details/gtvbkcdzgm.html

PHP:  public / protected / private
来源：http://dali.dianchejie.cn/Article/details/gtbzcsluqp.html

JS:   #private 字段；其余公开
来源：http://dali.yuxming.cn/Article/details/gtylivajbb.html

TS:   public / protected / private
来源：http://dali.jqgfzy.top/Article/details/gtqdlzlurr.html

Java: public / protected / private / 默认包级
来源：http://dali.yuanzhike.top/Article/details/gtawxktrpb.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.tanke756.top/Article/details/gtcynosvmg.html

Ruby: public / protected / private
来源：http://dali.aizwys.cn/Article/details/gtagmzbyzb.html

C#:   public / protected / private / internal
来源：http://dali.yj20258888.top/Article/details/gtfdxzfpcm.html

[G11] getter / setter
来源：http://dali.mhx1999.top/Article/details/gtjtqvhmvg.html

Py:   @property 与 @x.setter
来源：http://dali.hywenlv.cn/Article/details/gtjdemctlw.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.0kj1m.cn/Article/details/gtscfbsofg.html

JS:   get name() { return this._name; }
来源：http://dali.vqdsnc.cn/Article/details/gtsjrdzxsv.html

TS:   get name(): string { return this._name; }
来源：http://dali.gaohongyu789.top/Article/details/gtxfgxkpsf.html

Java: public String getName() { return name; }
来源：http://dali.dianchejie.cn/Article/details/gtfswvlznx.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.sysykeji.top/Article/details/gtxthhpsrs.html


<!-- 参考信息 -->