代发 wailian999

PHP:  substr_count($s, "a");
来源：http://dali.kuanghao11.cn/Article/details/gtjwzgmbeb.html

JS:   s.split("a").length - 1
来源：http://dali.guowangkeji.top/Article/details/gtigvztszg.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gtwurnwtal.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.hywenlv.cn/Article/details/gtyhgcfaol.html

Go:   strings.Count(s, "a")
来源：http://dali.cheryme.top/Article/details/gtwjrbaxzf.html

Ruby: s.count("a")
来源：http://dali.yuanzhike.top/Article/details/gtupfmymrq.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jlsjyb.cn/Article/details/gtuldaitzf.html

[E13] 逐字符遍历
来源：http://dali.chenjidiqi.icu/Article/details/gtdanghyqe.html

Py:   for ch in s: print(ch)
来源：http://dali.ivvv.top/Article/details/gtnzegwtio.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.kuanghao11.cn/Article/details/gthfgvzngz.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.feifeiyinyue.top/Article/details/gtvgacuqsp.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.aibaodan.cn/Article/details/gtcratlrvk.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.kuanghao11.cn/Article/details/gtadpvfcvx.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gtanmglocb.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.tanke756.top/Article/details/gtmoojkyus.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zycfv.cn/Article/details/gtkqbpvzex.html

[E14] URL 编码与 Base64
来源：http://dali.yuanzhike.top/Article/details/gtyogcyreo.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.ybcxt.top/Article/details/gtcikiowcm.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhongyouzk.top/Article/details/gtikticdav.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.sufxvd.cn/Article/details/gtvafjgpvi.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.andypj.xyz/Article/details/gtsgwzgtbo.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.xuetiantiany.cn/Article/details/gtmgezzlzs.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jinqigufen.top/Article/details/gtqimdhgbv.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.guowangkeji.top/Article/details/gttnsfhkvl.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yangfankeji.com/Article/details/gtelorolsc.html

[E15] HTML 转义 / 反转义
来源：http://dali.jinqigfzy.top/Article/details/gtstskrcoz.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.haohaochexian.top/Article/details/gtjseksqwi.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.shzxlz.cn/Article/details/gtvgjadgph.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jyoumei.cn/Article/details/gtelgqnost.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yuanzhike.top/Article/details/gtgvjkqjtu.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyducydae.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.birdmap.top/Article/details/gtsuzeoriw.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yj202588.top/Article/details/gtapbdvear.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hnxiangtu.top/Article/details/gtkjwauerw.html

[E16] 数字千分位
来源：http://dali.birdmap.top/Article/details/gtemmhqbid.html

Py:   f"{1234567:,}"
来源：http://dali.316326.xyz/Article/details/gtdbtjmacn.html

PHP:  number_format(1234567);
来源：http://dali.meibo888.top/Article/details/gtxbrqnyhb.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.chenjidiqi.icu/Article/details/gtyasrruej.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yuanzhike.top/Article/details/gtrepumjkc.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.daxiang520.top/Article/details/gtfjgwwvrw.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.ehwqpu.com/Article/details/gtgyvniryj.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yj20258.top/Article/details/gtelqrmepw.html

C#:   1234567.ToString("N0")
来源：http://dali.chenlongwang.top/Article/details/gtzyckwyos.html

[E17] 首字母大写
来源：http://dali.yuxming.cn/Article/details/gtqvrtdhss.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.shanyushiyangtech.top/Article/details/gtuyqbbugf.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.smart0.xyz/Article/details/gtxgbtswau.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yuanzhike.top/Article/details/gtqdyhqskz.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvexyuwzc.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmpopgjcm.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.xylfe.cn/Article/details/gtlwmfitjw.html

Ruby: s.capitalize
来源：http://dali.cashguo.top/Article/details/gtwwykcctf.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jqgfzy.top/Article/details/gtpzfrqewo.html

[E18] 模板占位符替换
来源：http://dali.zhiwuduotai.top/Article/details/gtscnufqcd.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.xylfe.cn/Article/details/gtzkuwplpm.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.chenzaomai.com/Article/details/gtwoxknujk.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.cashguo.top/Article/details/gtiqhzbrat.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.0kj1m.cn/Article/details/gtmlmavpyr.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zycfv.cn/Article/details/gtdfjdzzkz.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.aizwys.cn/Article/details/gtwtentlvm.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jinqigufen.top/Article/details/gtpboecdgr.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.tian-w.cn/Article/details/gtdbuegyeg.html

[E19] 多行文本按行拆分
来源：http://dali.kuanghao11.cn/Article/details/gttsnckuvg.html

Py:   s.splitlines()
来源：http://dali.chenlongwang.top/Article/details/gtrpzguxfm.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hysaishi.cn/Article/details/gtpbnuvrsu.html

JS:   s.split(/\r?\n/)
来源：http://dali.feifeiyinyue.top/Article/details/gtchzjbmpd.html

TS:   s.split(/\r?\n/)
来源：http://dali.daxiang520.top/Article/details/gtjbnkxslb.html

Java: s.lines().toList()
来源：http://dali.yonumen.top/Article/details/gtlvtbqcse.html

Go:   strings.Split(s, "\n")
来源：http://dali.yvedp.cn/Article/details/gtkatbqpga.html

Ruby: s.lines
来源：http://dali.cashguo.top/Article/details/gtjporwspx.html

C#:   s.Split('\n')
来源：http://dali.yonumen.top/Article/details/gtvwiepsia.html

[E20] 判断字符串是否为空
来源：http://dali.xziqi.cn/Article/details/gtbhntygso.html

Py:   if not s:
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqjpxormq.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.wangdashe.top/Article/details/gtuphuehct.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hnqzz.top/Article/details/gtoswjvepk.html

TS:   if (s === "") {}
来源：http://dali.cheryme.top/Article/details/gtpaqepwmn.html

Java: if (s.isEmpty()) {}
来源：http://dali.9152youxi.cn/Article/details/gtjlahqugn.html

Go:   if s == "" {}
来源：http://dali.tianlin.xyz/Article/details/gtihyrvbkv.html

Ruby: if s.empty?
来源：http://dali.hongshengwenyu.top/Article/details/gtzvetdmzd.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.gogol.net.cn/Article/details/gtevpxdswo.html

[E21] 超长截断加省略号
来源：http://dali.tanke756.top/Article/details/gtbfnouien.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hnxiangtu.top/Article/details/gtonxtofdq.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.xuanzx.com/Article/details/gtopfpjpqi.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shangyingyoupin.top/Article/details/gtuhrmmnka.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.316326.xyz/Article/details/gtfnnpblcu.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yanxiufei.cn/Article/details/gtlxldsuws.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhengqikj.top/Article/details/gteiakndya.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yvedp.cn/Article/details/gtbyrsltky.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hnxiangtu.top/Article/details/gtpbfgdhbj.html

[E22] 字节长度与字符长度
来源：http://dali.haohaochexian.top/Article/details/gtmumirenm.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.wangdashe.top/Article/details/gtvtkbqqtx.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yvedp.cn/Article/details/gtctylrhls.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sysykeji.top/Article/details/gtlhkejdut.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhoulong.xyz/Article/details/gtsmztjqiw.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.vqdsnc.cn/Article/details/gtstpvrnjo.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jlsjyb.cn/Article/details/gtmimxwykb.html

Ruby: s.bytesize;  s.length
来源：http://dali.guowangkeji.top/Article/details/gtcpqutfjo.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yj202588.top/Article/details/gttdndzjbl.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtxdtmoevs.html

F. 文件与目录
来源：http://dali.ivvv.top/Article/details/gtssmfubbn.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtkfdvudcr.html

[F01] 读取整个文件
来源：http://dali.c1oappe.top/Article/details/gtszgghxjj.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yanxiufei.cn/Article/details/gthulnyjji.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yongpay.top/Article/details/gtezyliwdx.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zdqjudy.top/Article/details/gtmojchckx.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.dianchejie.cn/Article/details/gtppqjmnfd.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.gogol.net.cn/Article/details/gtizjfqenp.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.pengpengdd.cyou/Article/details/gtwpverltp.html

Ruby: File.read("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtaduptffu.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.gotoacloud.top/Article/details/gthjfifivc.html

[F02] 逐行读取文件
来源：http://dali.chenlongwang.top/Article/details/gtluqzmjsh.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.chenjidiqi.icu/Article/details/gtpauqabdl.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hnqzz.top/Article/details/gtyaehwmld.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ehwqpu.com/Article/details/gtbhyynyzj.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jianghu66.top/Article/details/gtmmzzdflm.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.fengsongda.top/Article/details/gtfunjhhiy.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.kuanghao11.cn/Article/details/gtghyfemln.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnrlgvwyo.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.svipenyu.cn/Article/details/gtkplmmqts.html

[F03] 写入文件（覆盖）
来源：http://dali.pengpengdd.cyou/Article/details/gtegpvaswz.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.nwbrower.top/Article/details/gtcqglrrsl.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zycfv.cn/Article/details/gtesxpmfui.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yanxiufei.cn/Article/details/gtwhqircpu.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxqxfqxzk.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.cucudq.cn/Article/details/gtypwgecva.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gtvyhwbgpp.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hongshengwenyu.top/Article/details/gtonqtljwi.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcnupdpri.html

[F04] 追加写入文件
来源：http://dali.yuxming.cn/Article/details/gtgzlxqwnr.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnggcsavr.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.havefunace.top/Article/details/gtmeqhirqe.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinqigfzy.top/Article/details/gthfyjsuew.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ivvv.top/Article/details/gteosnptog.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hfpthk.cn/Article/details/gtxhwqdfep.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jyoumei.cn/Article/details/gtjiczzkry.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.smart0.xyz/Article/details/gtbzmdktwq.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yonumen.top/Article/details/gtywyfwzce.html

[F05] 判断文件或目录是否存在
来源：http://dali.316326.xyz/Article/details/gtsbtvryzd.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jiagoushi.top/Article/details/gtazyjviza.html

PHP:  file_exists("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gtwlezkyct.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtcneckbvw.html

TS:   fs.existsSync("a.txt")
来源：http://dali.cucudq.cn/Article/details/gthvdiwacs.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hywenlv.cn/Article/details/gtrgtmkmxr.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gtrbtjsrtq.html

Ruby: File.exist?("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtgaylbess.html

C#:   File.Exists("a.txt")
来源：http://dali.cashguo.top/Article/details/gtsjxziuim.html

[F06] 删除文件
来源：http://dali.ppjwa.cn/Article/details/gtajsuuqax.html

Py:   os.remove("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gttqmclwiq.html

PHP:  unlink("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gtyxhagbxx.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtjbmzlegz.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtztbvqpqa.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.mhx1999.top/Article/details/gtrunsubah.html

Go:   os.Remove("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtpbuoozqo.html

Ruby: File.delete("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtpfsndvwu.html

C#:   File.Delete("a.txt");
来源：http://dali.wangdashe.top/Article/details/gtjledivyk.html

[F07] 创建目录（含多级）
来源：http://dali.ivvv.top/Article/details/gtncpvxrau.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.gogol.net.cn/Article/details/gttngmwaak.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jinqigufen.top/Article/details/gtsshovdsx.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.feifeiyinyue.top/Article/details/gtxxjyemnj.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxudbdkww.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.dashuyun.cn/Article/details/gtdklrnfsa.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.pengpengdd.cyou/Article/details/gtnyzbllyg.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jianghu66.top/Article/details/gtnivhdjfh.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.smart0.xyz/Article/details/gtjcpfbpfv.html

[F08] 遍历目录
来源：http://dali.shanyushiyangtech.top/Article/details/gtihpbvknw.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.sufxvd.cn/Article/details/gtwtfqpcin.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.fengsongda.top/Article/details/gtimerkhba.html

JS:   fs.readdirSync("dir")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsmtqckbh.html

TS:   fs.readdirSync("dir")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvszzfuly.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtghevvslq.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zdqjudy.top/Article/details/gtibvsztxc.html

Ruby: Dir.children("dir")
来源：http://dali.shanyushiyangtech.top/Article/details/gtcznyyoik.html

C#:   Directory.GetFiles("dir")
来源：http://dali.shzxlz.cn/Article/details/gtqmlpmssq.html

[F09] 获取文件大小
来源：http://dali.gogol.net.cn/Article/details/gthfiunxfp.html

Py:   os.path.getsize("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtvhxfztcy.html

PHP:  filesize("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gtvcmyvbdw.html

JS:   fs.statSync("a.txt").size
来源：http://dali.snrcjt.cn/Article/details/gtcaecfobh.html

TS:   fs.statSync("a.txt").size
来源：http://dali.sxryk.cn/Article/details/gtinvqoito.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.c1oappe.top/Article/details/gtxsbvatgx.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.shangyingyoupin.top/Article/details/gtzxcsspnr.html

Ruby: File.size("a.txt")
来源：http://dali.yj20258.top/Article/details/gtgekvtyya.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.sysykeji.top/Article/details/gtykvbkula.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.redwolf501.top/Article/details/gtrjivtoub.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.daria6918.cn/Article/details/gttzdnxbcg.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yj202588.top/Article/details/gtdjtdujoh.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xylfe.cn/Article/details/gtixllevrk.html

TS:   path.extname("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtbkcbpdkq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.0kj1m.cn/Article/details/gtojgekwop.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.sweek.top/Article/details/gthgqjafpq.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yj202588.top/Article/details/gtexdbmviy.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtchydptkh.html

[F11] 复制与移动文件
来源：http://dali.sufxvd.cn/Article/details/gtivoyrcpv.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ehwqpu.com/Article/details/gtlpffyypv.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jianghu66.top/Article/details/gtjymmtjfs.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.haohaochexian.top/Article/details/gtxulrfgdr.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sysykeji.top/Article/details/gtshchirsd.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gtfjuqnyez.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ehwqpu.com/Article/details/gtvjhyzjef.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yangfankeji.com/Article/details/gtymgjruge.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jianghu66.top/Article/details/gtrjaoujja.html

[F12] CSV 读写
来源：http://dali.xinyue.icu/Article/details/gtsftytpre.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yangfankeji.com/Article/details/gteamgwnoy.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtomjvined.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yanxiufei.cn/Article/details/gtuwkksxdb.html

TS:   // 同上
来源：http://dali.yonumen.top/Article/details/gtkoointtw.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqluvbcpw.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.316326.xyz/Article/details/gtvmcqxfff.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.tianlin.xyz/Article/details/gtlygiqouy.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ybcxt.top/Article/details/gtzehgigre.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtfiuqeugs.html

G. 面向对象
来源：http://dali.jinqigfzy.top/Article/details/gtmweklzlr.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtnpvtxnkf.html

[G01] 定义类
来源：http://dali.0kj1m.cn/Article/details/gtwqrzaczk.html

Py:   class User: pass
来源：http://dali.tianlin.xyz/Article/details/gttgzctuab.html

PHP:  class User {}
来源：http://dali.bjfxy.top/Article/details/gtqlikxppd.html

JS:   class User {}
来源：http://dali.sweek.top/Article/details/gttiegfhaj.html

TS:   class User { name: string = ""; }
来源：http://dali.jlsjyb.cn/Article/details/gtivsjsouj.html

Java: class User {}
来源：http://dali.pengpengdd.cyou/Article/details/gtawegqxeu.html

Go:   type User struct { Name string }
来源：http://dali.gotoacloud.top/Article/details/gtswejvioq.html

Ruby: class User; end
来源：http://dali.hnxiangtu.top/Article/details/gtwzzzbwam.html

C#:   class User {}
来源：http://dali.chenjidiqi.icu/Article/details/gtdxasoxfm.html

[G02] 构造函数
来源：http://dali.daria6918.cn/Article/details/gtlwezvpvj.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.sxryk.cn/Article/details/gtawkmxrce.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.dianchejie.cn/Article/details/gtliukkavu.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ivvv.top/Article/details/gtgntmfsah.html

TS:   constructor(public name: string) {}
来源：http://dali.c1oappe.top/Article/details/gtegmhierk.html

Java: User(String name) { this.name = name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtaecstide.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.dianchejie.cn/Article/details/gtjqgzbrfg.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.0kj1m.cn/Article/details/gtxhjdfbfx.html

C#:   public User(string name) { Name = name; }
来源：http://dali.0kj1m.cn/Article/details/gtjgberrcx.html

[G03] 实例属性
来源：http://dali.zycfv.cn/Article/details/gtjhgbxswh.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gtyyuppqny.html

PHP:  public string $name = "x";
来源：http://dali.daxiang520.top/Article/details/gtvgoruona.html

JS:   this.name = "x";
来源：http://dali.cqqwz.cn/Article/details/gtudpvtsmr.html

TS:   name: string = "x";
来源：http://dali.pycfn.com/Article/details/gtyaxgbfvk.html

Java: private String name;
来源：http://dali.0kj1m.cn/Article/details/gtyafuomfn.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jinqigufen.top/Article/details/gtoldxegvc.html

Ruby: @name = "x"
来源：http://dali.wangdashe.top/Article/details/gtjqxcsvnp.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xuanzx.com/Article/details/gtybqlbblh.html

[G04] 定义方法
来源：http://dali.jyoumei.cn/Article/details/gtuzivlkkr.html

Py:   def greet(self): return self.name
来源：http://dali.jinyuanbaomall.cn/Article/details/gterppriqy.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yangfankeji.com/Article/details/gtpngslbhe.html

JS:   greet() { return this.name; }
来源：http://dali.hfpthk.cn/Article/details/gtjsifxjmw.html

TS:   greet(): string { return this.name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtwvmrjmpx.html

Java: String greet() { return name; }
来源：http://dali.nwbrower.top/Article/details/gtvzclpbrn.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhoulong.xyz/Article/details/gtgdmbtprc.html

Ruby: def greet; @name; end
来源：http://dali.daria6918.cn/Article/details/gtwiopfkwt.html

C#:   public string Greet() => Name;
来源：http://dali.fengsongda.top/Article/details/gtdtnvoeli.html

[G05] 继承
来源：http://dali.jinghuilouyu.cn/Article/details/gtnhecqkmc.html

Py:   class Admin(User): pass
来源：http://dali.jyoumei.cn/Article/details/gtlunrehah.html

PHP:  class Admin extends User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmurlayeb.html

JS:   class Admin extends User {}
来源：http://dali.sxryk.cn/Article/details/gtqeqachfg.html

TS:   class Admin extends User {}
来源：http://dali.hammf.cn/Article/details/gtacgppxjd.html

Java: class Admin extends User {}
来源：http://dali.zhoulong.xyz/Article/details/gtvevfltsu.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hammf.cn/Article/details/gtclvwsldu.html

Ruby: class Admin < User; end
来源：http://dali.haohaochexian.top/Article/details/gtmwbaelmd.html

C#:   class Admin : User {}
来源：http://dali.hysaishi.cn/Article/details/gtyfdmucbm.html

[G06] 重写方法
来源：http://dali.zycfv.cn/Article/details/gteiyluafz.html

Py:   def greet(self): return "admin"
来源：http://dali.tanke756.top/Article/details/gtnhvjpmfb.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.sufxvd.cn/Article/details/gtjtkjvfeo.html

JS:   greet() { return "admin"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtkmqasboc.html

TS:   greet(): string { return "admin"; }
来源：http://dali.tian-w.cn/Article/details/gtgwcoeirz.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.birdmap.top/Article/details/gthtwqjaky.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.mhx1999.top/Article/details/gtlusizrba.html

Ruby: def greet; "admin"; end
来源：http://dali.zhiwuduotai.top/Article/details/gtelcbcksj.html

C#:   public override string Greet() => "admin";
来源：http://dali.cheryme.top/Article/details/gtevxfbjdy.html

[G07] 调用父类方法
来源：http://dali.ivvv.top/Article/details/gttutmvokw.html

Py:   super().greet()
来源：http://dali.hfpthk.cn/Article/details/gtlvmhtigm.html

PHP:  parent::greet();
来源：http://dali.ybcxt.top/Article/details/gtvafutavt.html

JS:   super.greet();
来源：http://dali.dashuyun.cn/Article/details/gtpeclxxvu.html

TS:   super.greet();
来源：http://dali.zhengqikj.top/Article/details/gtgaqjhuix.html

Java: super.greet();
来源：http://dali.jianghu66.top/Article/details/gtyqejvhpi.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.chenzaomai.com/Article/details/gtijwqorhs.html

Ruby: super
来源：http://dali.zdqjudy.top/Article/details/gtolrmeoeq.html

C#:   base.Greet();
来源：http://dali.birdmap.top/Article/details/gtfmjtnsca.html

[G08] 静态方法与属性
来源：http://dali.yj20258.top/Article/details/gtqtfwpyaf.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhengqikj.top/Article/details/gtyuvbjawe.html

PHP:  public static function f() {}
来源：http://dali.9152youxi.cn/Article/details/gtwadoawyk.html

JS:   static f() {}
来源：http://dali.ydzc1.top/Article/details/gtxoaxxtkd.html

TS:   static f(): void {}
来源：http://dali.jinqigufen.top/Article/details/gtovlvxsgd.html

Java: static void f() {}
来源：http://dali.ppjwa.cn/Article/details/gtvqvatfbp.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jinqigfzy.top/Article/details/gtiysemnsr.html

Ruby: def self.f; end
来源：http://dali.316326.xyz/Article/details/gtokewtllg.html

C#:   public static void F() {}
来源：http://dali.pycfn.com/Article/details/gtqhykxsnc.html

[G09] 接口 / 抽象类
来源：http://dali.feifeiyinyue.top/Article/details/gthnjwyvcc.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.9152youxi.cn/Article/details/gtldmpdaxj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.pengpengdd.cyou/Article/details/gtrymaqzwa.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ppjwa.cn/Article/details/gtcclrgrps.html

TS:   interface Shape { area(): number; }
来源：http://dali.quarkkingdee.top/Article/details/gtcxigrrhs.html

Java: interface Shape { double area(); }
来源：http://dali.tianlin.xyz/Article/details/gtwuwrauga.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ybcxt.top/Article/details/gtujnzohjv.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.bjfxy.top/Article/details/gtezjodijb.html

C#:   interface IShape { double Area(); }
来源：http://dali.nwbrower.top/Article/details/gtsavapljd.html

[G10] 访问控制
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwfxyeejh.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.guannengcc.top/Article/details/gtqowiekhm.html

PHP:  public / protected / private
来源：http://dali.cdnleiting.top/Article/details/gtrxmkaiew.html

JS:   #private 字段；其余公开
来源：http://dali.nanxinkj.top/Article/details/gtbqyiutll.html

TS:   public / protected / private
来源：http://dali.fzhhl.top/Article/details/gtwkhqxnqn.html

Java: public / protected / private / 默认包级
来源：http://dali.mhx1999.top/Article/details/gtrtzrqiyv.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.0kj1m.cn/Article/details/gtfgupoisf.html

Ruby: public / protected / private
来源：http://dali.guowangkeji.top/Article/details/gtebtzxdyz.html


<!-- 参考信息 -->