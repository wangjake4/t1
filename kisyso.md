代发 wailian999

JS:   [...s].reverse().join("")
来源：http://dali.guowangkeji.top/Article/details/gttogywcjo.html

TS:   [...s].reverse().join("")
来源：http://dali.svipenyu.cn/Article/details/gtnkedaidf.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.nanxuanxn.top/Article/details/gtnrlbklfp.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yuxming.cn/Article/details/gtzszdyxeo.html

Ruby: s.reverse
来源：http://dali.fzhhl.top/Article/details/gtyiczjyof.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.chenzaomai.com/Article/details/gtrppuvzvg.html

[E12] 统计某字符出现次数
来源：http://dali.quarkkingdee.top/Article/details/gtlldswlio.html

Py:   s.count("a")
来源：http://dali.yongpay.top/Article/details/gtkensgztd.html

PHP:  substr_count($s, "a");
来源：http://dali.vqdsnc.cn/Article/details/gtgyiaxfkb.html

JS:   s.split("a").length - 1
来源：http://dali.cucudq.cn/Article/details/gtmdjkyuzj.html

TS:   s.split("a").length - 1
来源：http://dali.wangdashe.top/Article/details/gttybdfori.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.shuidangran.top/Article/details/gtostvchyu.html

Go:   strings.Count(s, "a")
来源：http://dali.hnxiangtu.top/Article/details/gtkscxipig.html

Ruby: s.count("a")
来源：http://dali.havefunace.top/Article/details/gtsxrmqwfm.html

C#:   s.Count(c => c == 'a')
来源：http://dali.shanyushiyangtech.top/Article/details/gtkqzpqksf.html

[E13] 逐字符遍历
来源：http://dali.birdmap.top/Article/details/gtkzbsovij.html

Py:   for ch in s: print(ch)
来源：http://dali.vqdsnc.cn/Article/details/gtzivembuk.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhongyouzk.top/Article/details/gtokhkedgp.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yangfankeji.com/Article/details/gtzddzzgjx.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cdnleiting.top/Article/details/gtjdlbxhrn.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hywenlv.cn/Article/details/gtzgofxlck.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.316326.xyz/Article/details/gtkebvudpo.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.redwolf501.top/Article/details/gtwqdtjurb.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.aibaodan.cn/Article/details/gtprhsfbrz.html

[E14] URL 编码与 Base64
来源：http://dali.shzxlz.cn/Article/details/gtybuqydgt.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hongshengwenyu.top/Article/details/gthtfkuhre.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jyoumei.cn/Article/details/gtjkocktxd.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.daxiang520.top/Article/details/gtwilkppdk.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmqnihhhr.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.guannengcc.top/Article/details/gtoucdxcii.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.pengpengdd.cyou/Article/details/gtlvpbjcyc.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jqgufenzy.top/Article/details/gtstnjccot.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gtkgarlhjw.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhijiandao.cn/Article/details/gtwbmucwvy.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.chenzaomai.com/Article/details/gtqlrjksww.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.chenjidiqi.icu/Article/details/gtaukqhaqq.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.0kj1m.cn/Article/details/gtfsfvvehb.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jianghu66.top/Article/details/gtgvmmtzzp.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hfpthk.cn/Article/details/gtgvonimrl.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hnxiangtu.top/Article/details/gtswnjdfne.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yvedp.cn/Article/details/gtjqsektuz.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yj20258888.top/Article/details/gtvdurmbpn.html

[E16] 数字千分位
来源：http://dali.yonumen.top/Article/details/gttyuzllvw.html

Py:   f"{1234567:,}"
来源：http://dali.cashguo.top/Article/details/gtazpoorqk.html

PHP:  number_format(1234567);
来源：http://dali.sxryk.cn/Article/details/gtvtmukbeh.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jiagoushi.top/Article/details/gtcwjmihoa.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.sxryk.cn/Article/details/gthbszvioz.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.feifeiyinyue.top/Article/details/gthhqqrnup.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.meibo888.top/Article/details/gtguyjlyvx.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.ppjwa.cn/Article/details/gtpuwebkul.html

C#:   1234567.ToString("N0")
来源：http://dali.chenlongwang.top/Article/details/gtoxgwpges.html

[E17] 首字母大写
来源：http://dali.hnqzz.top/Article/details/gtwrgkfsqh.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.wangdashe.top/Article/details/gtmwmgtkne.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hnxiangtu.top/Article/details/gtfaixueno.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yanxiufei.cn/Article/details/gtmujcxijy.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.quarkkingdee.top/Article/details/gtkgxchprd.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.svipenyu.cn/Article/details/gtuzpfhblc.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.fzhhl.top/Article/details/gtdxkzxerj.html

Ruby: s.capitalize
来源：http://dali.yj20258888.top/Article/details/gtlmldjnjz.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.hnxiangtu.top/Article/details/gtqjcvhfif.html

[E18] 模板占位符替换
来源：http://dali.cashguo.top/Article/details/gtlitifsom.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.cdnleiting.top/Article/details/gtoleelmbb.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.chenjidiqi.icu/Article/details/gttjnlfjvg.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.xinyue.icu/Article/details/gtmgpnfzaz.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.sxryk.cn/Article/details/gtcdvsnziy.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhoulong.xyz/Article/details/gtqbjwhyuo.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtysqgveis.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.meibo888.top/Article/details/gtesdjwqzg.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zdqjudy.top/Article/details/gtqgqqeaxc.html

[E19] 多行文本按行拆分
来源：http://dali.9152youxi.cn/Article/details/gtilguwgfs.html

Py:   s.splitlines()
来源：http://dali.gogol.net.cn/Article/details/gtulaetuwj.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.nanxinkj.top/Article/details/gtztycxibl.html

JS:   s.split(/\r?\n/)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpoqdgcdy.html

TS:   s.split(/\r?\n/)
来源：http://dali.jianghu66.top/Article/details/gtdlcgaovy.html

Java: s.lines().toList()
来源：http://dali.yonumen.top/Article/details/gtzlgbeopi.html

Go:   strings.Split(s, "\n")
来源：http://dali.chenjidiqi.icu/Article/details/gtgeducsia.html

Ruby: s.lines
来源：http://dali.jinqigfzy.top/Article/details/gtrygfnnem.html

C#:   s.Split('\n')
来源：http://dali.yanxiufei.cn/Article/details/gteujxhijd.html

[E20] 判断字符串是否为空
来源：http://dali.wangshuangyany.cn/Article/details/gtnejadsxg.html

Py:   if not s:
来源：http://dali.jqgufenzy.top/Article/details/gtqivqsmip.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.ivvv.top/Article/details/gtlduudlwt.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.kuanghao11.cn/Article/details/gtzzphsxth.html

TS:   if (s === "") {}
来源：http://dali.chenlongwang.top/Article/details/gtdbsundku.html

Java: if (s.isEmpty()) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtlyjbxgix.html

Go:   if s == "" {}
来源：http://dali.yanxiufei.cn/Article/details/gthrlwioqw.html

Ruby: if s.empty?
来源：http://dali.meibo888.top/Article/details/gteaxjsbfq.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.andypj.xyz/Article/details/gtqubymlbx.html

[E21] 超长截断加省略号
来源：http://dali.zhengqikj.top/Article/details/gtjduhdfkg.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.chenlongwang.top/Article/details/gtliosdgij.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hysaishi.cn/Article/details/gtvqwhxdys.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.tianlin.xyz/Article/details/gtluikbahi.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhixingplan.top/Article/details/gtoxmydcqz.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.fengsongda.top/Article/details/gtxzunzndy.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.shanyushiyangtech.top/Article/details/gtpeiehdys.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yuxming.cn/Article/details/gtlubnbpyr.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.daxiang520.top/Article/details/gtnomdefwt.html

[E22] 字节长度与字符长度
来源：http://dali.shuidangran.top/Article/details/gtecvgbrqa.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jqgfzy.top/Article/details/gtwptoliuz.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.dashuyun.cn/Article/details/gtmnhuqucc.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sufxvd.cn/Article/details/gtxrkpsoxd.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gotoacloud.top/Article/details/gtcwyfqrzw.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jqgufenzy.top/Article/details/gtinjuepkn.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.meibo888.top/Article/details/gttjdkcops.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhoulong.xyz/Article/details/gtcjzjsjvw.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcegdnfkv.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtxbgfvxym.html

F. 文件与目录
来源：http://dali.yj20258888.top/Article/details/gtwddojttl.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtfwpmgnce.html

[F01] 读取整个文件
来源：http://dali.svipenyu.cn/Article/details/gtdgkmhqmh.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.iojbl.cn/Article/details/gtjgyqexwq.html

PHP:  file_get_contents("a.txt");
来源：http://dali.ybcxt.top/Article/details/gthegiknjt.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.nwbrower.top/Article/details/gtgetxggvn.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.c1oappe.top/Article/details/gtcifopvgu.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhiwuduotai.top/Article/details/gtlyunkzjo.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.316326.xyz/Article/details/gttvepdxqo.html

Ruby: File.read("a.txt")
来源：http://dali.cheryme.top/Article/details/gtdlgmxoda.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.guannengcc.top/Article/details/gtismneopl.html

[F02] 逐行读取文件
来源：http://dali.tian-w.cn/Article/details/gtbqyuigdq.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.meibo888.top/Article/details/gtimbcfsph.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.nanxuanxn.top/Article/details/gtbxayeeqi.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sufxvd.cn/Article/details/gtiltechev.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinqigfzy.top/Article/details/gtnpvicsco.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.daxiang520.top/Article/details/gtagleopnl.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.sufxvd.cn/Article/details/gtzhoauflg.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.wangdashe.top/Article/details/gtqxmnanfw.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.tanke756.top/Article/details/gtkjffxlgt.html

[F03] 写入文件（覆盖）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnygwtvkx.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.nwbrower.top/Article/details/gtumnzjmbc.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.meibo888.top/Article/details/gtuygcxwgw.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shzxlz.cn/Article/details/gtaatwaudu.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sxryk.cn/Article/details/gtkxxyiowc.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.aibaodan.cn/Article/details/gtltacjumg.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.svipenyu.cn/Article/details/gtfvqcrpyz.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.chenzaomai.com/Article/details/gtxqwzftrh.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ivvv.top/Article/details/gtjfftujpu.html

[F04] 追加写入文件
来源：http://dali.zhoulong.xyz/Article/details/gtxjblyfdn.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hywenlv.cn/Article/details/gtqgqxehno.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.quarkkingdee.top/Article/details/gtuyjqvoek.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yueranfly.top/Article/details/gthlmhgcth.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.daxiang520.top/Article/details/gttghlizfy.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yueranfly.top/Article/details/gtalkwagrj.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.chenjidiqi.icu/Article/details/gtjiepjrnj.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hammf.cn/Article/details/gtborsiexj.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jyoumei.cn/Article/details/gtggkjrrcu.html

[F05] 判断文件或目录是否存在
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfpauggny.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.vqdsnc.cn/Article/details/gtaidjjbqu.html

PHP:  file_exists("a.txt");
来源：http://dali.birdmap.top/Article/details/gtjgpvfxei.html

JS:   fs.existsSync("a.txt")
来源：http://dali.meibo888.top/Article/details/gtvdxfajxt.html

TS:   fs.existsSync("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gthxngjdyo.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.nanxuanxn.top/Article/details/gtqflbanop.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yj202588.top/Article/details/gtykothwwu.html

Ruby: File.exist?("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtpphljfqh.html

C#:   File.Exists("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmlkyanpd.html

[F06] 删除文件
来源：http://dali.yuanzhike.top/Article/details/gtifvbltjv.html

Py:   os.remove("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtifbmbiqu.html

PHP:  unlink("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnxqkecti.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtjnibdcod.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtqxzcwcxl.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.cashguo.top/Article/details/gthdkzryvu.html

Go:   os.Remove("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtwnojlved.html

Ruby: File.delete("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtwkmifpds.html

C#:   File.Delete("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtvaqwxymz.html

[F07] 创建目录（含多级）
来源：http://dali.zhongyouzk.top/Article/details/gtonlwxhry.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.gotoacloud.top/Article/details/gttsnlayxc.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.nanxinkj.top/Article/details/gtydwgejsp.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yangfankeji.com/Article/details/gtvkuqlnbp.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hnqzz.top/Article/details/gtugpakdxr.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhiwuduotai.top/Article/details/gtbkzfyewx.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.cqqwz.cn/Article/details/gtdczaeqdq.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.shzxlz.cn/Article/details/gtfpxjssjt.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yj202588.top/Article/details/gtbppocuio.html

[F08] 遍历目录
来源：http://dali.cucudq.cn/Article/details/gtxwuzuleu.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.guowangkeji.top/Article/details/gtsmyabgex.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.xuanzx.com/Article/details/gtpparnsrm.html

JS:   fs.readdirSync("dir")
来源：http://dali.redwolf501.top/Article/details/gtggteatxd.html

TS:   fs.readdirSync("dir")
来源：http://dali.yj20258888.top/Article/details/gtrqlbazvq.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.sxryk.cn/Article/details/gtnbrmnkmh.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jianghu66.top/Article/details/gtginjqpkk.html

Ruby: Dir.children("dir")
来源：http://dali.shanyushiyangtech.top/Article/details/gtsamoizaw.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jianghu66.top/Article/details/gtyguvrfab.html

[F09] 获取文件大小
来源：http://dali.tian-w.cn/Article/details/gtbqqbfevt.html

Py:   os.path.getsize("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtnewgyntn.html

PHP:  filesize("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gtstsjatvj.html

JS:   fs.statSync("a.txt").size
来源：http://dali.sufxvd.cn/Article/details/gtbvpeaufm.html

TS:   fs.statSync("a.txt").size
来源：http://dali.xuetiantiany.cn/Article/details/gthemzysgf.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cheryme.top/Article/details/gtbxxisvcj.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.feifeiyinyue.top/Article/details/gtfauuwjgg.html

Ruby: File.size("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtykpljael.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhixingplan.top/Article/details/gtqeiccmhj.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yongpay.top/Article/details/gteyvwjoeu.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jianghu66.top/Article/details/gtdzkrzfjs.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yongpay.top/Article/details/gtmqmmtors.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmdbtpuxv.html

TS:   path.extname("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtcdnlahmm.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jinqigfzy.top/Article/details/gtadhqdldp.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtygwwgjyw.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtumpvjjlc.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtxjxqsqib.html

[F11] 复制与移动文件
来源：http://dali.sxryk.cn/Article/details/gtijutgmat.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtmkbuyohe.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gtrnkiicpv.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ppjwa.cn/Article/details/gtadsuaxpe.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yangfankeji.com/Article/details/gtfzfheyxi.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yonumen.top/Article/details/gtlmuqbgpj.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhongyouzk.top/Article/details/gtszhzqzti.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtztodeurl.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.pycfn.com/Article/details/gtlzuedrtd.html

[F12] CSV 读写
来源：http://dali.dianchejie.cn/Article/details/gtxbxmhvmx.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ivvv.top/Article/details/gtqodywszc.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.cdnleiting.top/Article/details/gtpsfgvmyr.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.gotoacloud.top/Article/details/gtwqphqdba.html

TS:   // 同上
来源：http://dali.dianchejie.cn/Article/details/gtxplunrgr.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jianghu66.top/Article/details/gtkxsprgbi.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.tianlin.xyz/Article/details/gtqrewvufq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jiagoushi.top/Article/details/gthajliwta.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.chenzaomai.com/Article/details/gtdgqbquuf.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtptmdkeuw.html

G. 面向对象
来源：http://dali.kuanghao11.cn/Article/details/gtadfbsrih.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtwuvjtaio.html

[G01] 定义类
来源：http://dali.hongshengwenyu.top/Article/details/gtogthydgu.html

Py:   class User: pass
来源：http://dali.wangdashe.top/Article/details/gtaqvlxjdr.html

PHP:  class User {}
来源：http://dali.zhongyouzk.top/Article/details/gtdvjfqlan.html

JS:   class User {}
来源：http://dali.dianchejie.cn/Article/details/gtmgowoxap.html

TS:   class User { name: string = ""; }
来源：http://dali.aizwys.cn/Article/details/gtyqyiohdu.html

Java: class User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtcmibnmjv.html

Go:   type User struct { Name string }
来源：http://dali.ppjwa.cn/Article/details/gtmehispbk.html

Ruby: class User; end
来源：http://dali.hysaishi.cn/Article/details/gtfxujvuxn.html

C#:   class User {}
来源：http://dali.dashuyun.cn/Article/details/gtmhyzdrpp.html

[G02] 构造函数
来源：http://dali.yuanzhike.top/Article/details/gtelkeardx.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.gzhubu.top/Article/details/gtmsotvjmi.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ppjwa.cn/Article/details/gtvzeqatpd.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.haohaochexian.top/Article/details/gteypurhnv.html

TS:   constructor(public name: string) {}
来源：http://dali.quarkkingdee.top/Article/details/gttnkycdva.html

Java: User(String name) { this.name = name; }
来源：http://dali.fzhhl.top/Article/details/gtrnwbukry.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.iojbl.cn/Article/details/gtvjfvusoq.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yvedp.cn/Article/details/gtzcnafakq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.havefunace.top/Article/details/gtycxcuxrq.html

[G03] 实例属性
来源：http://dali.guannengcc.top/Article/details/gtwwufqtde.html

Py:   self.name = "x"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtosgyfkba.html

PHP:  public string $name = "x";
来源：http://dali.shuidangran.top/Article/details/gtgovfitii.html

JS:   this.name = "x";
来源：http://dali.jianghu66.top/Article/details/gtmmjidazn.html

TS:   name: string = "x";
来源：http://dali.zhoulong.xyz/Article/details/gtkjfjmxxs.html

Java: private String name;
来源：http://dali.kuanghao11.cn/Article/details/gtzhmwsrwj.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yj202588.top/Article/details/gtzufpmslu.html

Ruby: @name = "x"
来源：http://dali.gogol.net.cn/Article/details/gtidslxnod.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.feifeiyinyue.top/Article/details/gtoltbjxgz.html

[G04] 定义方法
来源：http://dali.vqdsnc.cn/Article/details/gtzddyjimn.html

Py:   def greet(self): return self.name
来源：http://dali.mhx1999.top/Article/details/gtfdmovdbr.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.snrcjt.cn/Article/details/gtkxiehxel.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gtwdjpneuu.html

TS:   greet(): string { return this.name; }
来源：http://dali.yanxiufei.cn/Article/details/gtguzojapp.html

Java: String greet() { return name; }
来源：http://dali.fengsongda.top/Article/details/gtldcwynwr.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.gzhubu.top/Article/details/gtewaqvxao.html

Ruby: def greet; @name; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gthaqglppi.html

C#:   public string Greet() => Name;
来源：http://dali.0kj1m.cn/Article/details/gtstowxvfe.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gthkbfuycz.html

Py:   class Admin(User): pass
来源：http://dali.jlsjyb.cn/Article/details/gteltrvdpc.html

PHP:  class Admin extends User {}
来源：http://dali.tian-w.cn/Article/details/gthnjevxxz.html

JS:   class Admin extends User {}
来源：http://dali.hywenlv.cn/Article/details/gtsrzwhdaf.html

TS:   class Admin extends User {}
来源：http://dali.hammf.cn/Article/details/gtfhpkoovg.html

Java: class Admin extends User {}
来源：http://dali.hysaishi.cn/Article/details/gtyowrwrwh.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yj202588.top/Article/details/gtvdhvefiz.html

Ruby: class Admin < User; end
来源：http://dali.ydzc1.top/Article/details/gtideyrzsh.html

C#:   class Admin : User {}
来源：http://dali.xinyue.icu/Article/details/gtlplhhepk.html

[G06] 重写方法
来源：http://dali.yongpay.top/Article/details/gtyjaiejbq.html

Py:   def greet(self): return "admin"
来源：http://dali.zycfv.cn/Article/details/gtkjscoiwb.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsqglgnmo.html

JS:   greet() { return "admin"; }
来源：http://dali.cdnleiting.top/Article/details/gtdvuujxll.html

TS:   greet(): string { return "admin"; }
来源：http://dali.dashuyun.cn/Article/details/gtfbitoqrj.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.c1oappe.top/Article/details/gtmkbgqpmx.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.chenjidiqi.icu/Article/details/gtuvqeaqgw.html

Ruby: def greet; "admin"; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtmhbhxtcx.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhongyouzk.top/Article/details/gtjnwmthjw.html

[G07] 调用父类方法
来源：http://dali.chenjidiqi.icu/Article/details/gtftxqqarl.html

Py:   super().greet()
来源：http://dali.0kj1m.cn/Article/details/gtzusaeyou.html

PHP:  parent::greet();
来源：http://dali.mhx1999.top/Article/details/gtylfjrhkp.html

JS:   super.greet();
来源：http://dali.gzhubu.top/Article/details/gtuaklalps.html

TS:   super.greet();
来源：http://dali.yuxming.cn/Article/details/gtdpdyebbk.html

Java: super.greet();
来源：http://dali.0kj1m.cn/Article/details/gtnyesqwef.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.havefunace.top/Article/details/gtvgmkifuq.html

Ruby: super
来源：http://dali.sysykeji.top/Article/details/gtojqgozgj.html

C#:   base.Greet();
来源：http://dali.jinqigufen.top/Article/details/gtzolmtvol.html

[G08] 静态方法与属性
来源：http://dali.sufxvd.cn/Article/details/gtjzqxahyt.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jlsjyb.cn/Article/details/gtcfnxvnmd.html

PHP:  public static function f() {}
来源：http://dali.birdmap.top/Article/details/gtnqyademw.html

JS:   static f() {}
来源：http://dali.shuidangran.top/Article/details/gtqttknqow.html

TS:   static f(): void {}
来源：http://dali.andypj.xyz/Article/details/gtoszyelmw.html

Java: static void f() {}
来源：http://dali.0kj1m.cn/Article/details/gtwtvpnsmy.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.iojbl.cn/Article/details/gtaahudltf.html

Ruby: def self.f; end
来源：http://dali.guowangkeji.top/Article/details/gtzggxfkte.html

C#:   public static void F() {}
来源：http://dali.andypj.xyz/Article/details/gtvubxctyo.html

[G09] 接口 / 抽象类
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthnjixjmk.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.daxiang520.top/Article/details/gtvcaafvzz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yanxiufei.cn/Article/details/gtyagvuiyu.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.andypj.xyz/Article/details/gtqoudaypa.html

TS:   interface Shape { area(): number; }
来源：http://dali.cashguo.top/Article/details/gtkpfipcik.html

Java: interface Shape { double area(); }
来源：http://dali.ybcxt.top/Article/details/gthylcfrnj.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cqqwz.cn/Article/details/gtlmmhnvik.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yuanzhike.top/Article/details/gtnugzdfjj.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhixingplan.top/Article/details/gtxtvxquou.html


<!-- 参考信息 -->