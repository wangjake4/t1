代发 wailian999

JS:   [...s].reverse().join("")
来源：http://dali.redwolf501.top/Article/details/gtstpbsukt.html

TS:   [...s].reverse().join("")
来源：http://dali.zhongyouzk.top/Article/details/gtevuefwat.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.snrcjt.cn/Article/details/gtowjzncas.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yonumen.top/Article/details/gtlevaqmno.html

Ruby: s.reverse
来源：http://dali.yuxming.cn/Article/details/gthawjfdko.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yanxiufei.cn/Article/details/gtnfqbeuyk.html

[E12] 统计某字符出现次数
来源：http://dali.meibo888.top/Article/details/gtlfyqwqxg.html

Py:   s.count("a")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttvaghalc.html

PHP:  substr_count($s, "a");
来源：http://dali.smart0.xyz/Article/details/gtnlajujmp.html

JS:   s.split("a").length - 1
来源：http://dali.zdqjudy.top/Article/details/gtvyjwfzpw.html

TS:   s.split("a").length - 1
来源：http://dali.shanyushiyangtech.top/Article/details/gthhkaavhq.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xuanzx.com/Article/details/gtjzczpnhe.html

Go:   strings.Count(s, "a")
来源：http://dali.gotoacloud.top/Article/details/gtaecvsesf.html

Ruby: s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gtifagidka.html

C#:   s.Count(c => c == 'a')
来源：http://dali.guannengcc.top/Article/details/gtpwgaxlnx.html

[E13] 逐字符遍历
来源：http://dali.ybcxt.top/Article/details/gtymmvtmhp.html

Py:   for ch in s: print(ch)
来源：http://dali.gotoacloud.top/Article/details/gtdxiulkpl.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zycfv.cn/Article/details/gtffztymak.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gotoacloud.top/Article/details/gtfmlcfgpt.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gaohongyu789.top/Article/details/gtegmytxne.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.tian-w.cn/Article/details/gtezjcsqtw.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gthsqwtwln.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.shangyingyoupin.top/Article/details/gtxtivfanh.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jlsjyb.cn/Article/details/gtdujgotoi.html

[E14] URL 编码与 Base64
来源：http://dali.snrcjt.cn/Article/details/gtncggjjqd.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.wangdashe.top/Article/details/gtbmpjwpgh.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvzheqvvf.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhixingplan.top/Article/details/gtnowrcqeq.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yuanzhike.top/Article/details/gtzuzbttpj.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.nwbrower.top/Article/details/gtzdrhpaoa.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.wangdashe.top/Article/details/gtwrsmfkwt.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyugfvulx.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jlsjyb.cn/Article/details/gtnowkljie.html

[E15] HTML 转义 / 反转义
来源：http://dali.hnqzz.top/Article/details/gtaxhippel.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yonumen.top/Article/details/gtddopbrwc.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.feifeiyinyue.top/Article/details/gtosrdkhii.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.xziqi.cn/Article/details/gtgmqyadco.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.pengpengdd.cyou/Article/details/gtvmrimozm.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.haohaochexian.top/Article/details/gtiwyzakst.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jiagoushi.top/Article/details/gtzndlqyou.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.ybcxt.top/Article/details/gtnedgbifc.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.shuidangran.top/Article/details/gteeqnnulg.html

[E16] 数字千分位
来源：http://dali.yueranfly.top/Article/details/gtzcgypwot.html

Py:   f"{1234567:,}"
来源：http://dali.xuetiantiany.cn/Article/details/gtltuitlfu.html

PHP:  number_format(1234567);
来源：http://dali.gogol.net.cn/Article/details/gtzxjowisb.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.havefunace.top/Article/details/gtweuarkyl.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhoulong.xyz/Article/details/gtbluhaaxm.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhiwuduotai.top/Article/details/gtcehaeuav.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yangfankeji.com/Article/details/gtnhqowusl.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhixingplan.top/Article/details/gtuasitmvk.html

C#:   1234567.ToString("N0")
来源：http://dali.316326.xyz/Article/details/gtbywxzkwd.html

[E17] 首字母大写
来源：http://dali.c1oappe.top/Article/details/gtqnaeketf.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.dashuyun.cn/Article/details/gtkmcauwah.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yuanzhike.top/Article/details/gtsgflcnzw.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinqigfzy.top/Article/details/gtuhzbaoav.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ivvv.top/Article/details/gtvzvgtsvz.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.shuidangran.top/Article/details/gtdjkhjqqo.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.sysykeji.top/Article/details/gttemxxzjz.html

Ruby: s.capitalize
来源：http://dali.hfpthk.cn/Article/details/gtqofvqciy.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.feifeiyinyue.top/Article/details/gtuxzmjhug.html

[E18] 模板占位符替换
来源：http://dali.hfpthk.cn/Article/details/gtzblegmap.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.aibaodan.cn/Article/details/gtxsylhcid.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtppuidqhi.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.chenlongwang.top/Article/details/gtbgyzwesw.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.chenzaomai.com/Article/details/gtmxjhhubp.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jinghuilouyu.cn/Article/details/gtehcmzbrh.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhixingplan.top/Article/details/gtefpmzari.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.xziqi.cn/Article/details/gtergldwuc.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.tianlin.xyz/Article/details/gtzkclmdfo.html

[E19] 多行文本按行拆分
来源：http://dali.cucudq.cn/Article/details/gtechtbivj.html

Py:   s.splitlines()
来源：http://dali.feifeiyinyue.top/Article/details/gtmkeuibep.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.tianlin.xyz/Article/details/gtartrorpn.html

JS:   s.split(/\r?\n/)
来源：http://dali.iojbl.cn/Article/details/gtpssvzdge.html

TS:   s.split(/\r?\n/)
来源：http://dali.daria6918.cn/Article/details/gtxcwzjofv.html

Java: s.lines().toList()
来源：http://dali.zdqjudy.top/Article/details/gtovxmxbvt.html

Go:   strings.Split(s, "\n")
来源：http://dali.c1oappe.top/Article/details/gtajmyfcfu.html

Ruby: s.lines
来源：http://dali.dianchejie.cn/Article/details/gtuggobybx.html

C#:   s.Split('\n')
来源：http://dali.meibo888.top/Article/details/gtwxtdlvow.html

[E20] 判断字符串是否为空
来源：http://dali.gotoacloud.top/Article/details/gtincrkonv.html

Py:   if not s:
来源：http://dali.ybcxt.top/Article/details/gthmiaomap.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.cheryme.top/Article/details/gtyiqiupoe.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.ppjwa.cn/Article/details/gtryvmylao.html

TS:   if (s === "") {}
来源：http://dali.zhixingplan.top/Article/details/gtejltknnr.html

Java: if (s.isEmpty()) {}
来源：http://dali.xuanzx.com/Article/details/gthvryjsbq.html

Go:   if s == "" {}
来源：http://dali.mhx1999.top/Article/details/gtsohjqmms.html

Ruby: if s.empty?
来源：http://dali.cashguo.top/Article/details/gtfcbjzgih.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jinqigufen.top/Article/details/gtsgzitwxg.html

[E21] 超长截断加省略号
来源：http://dali.daria6918.cn/Article/details/gtpjqqtjpq.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.meibo888.top/Article/details/gtzgzpjbgu.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvoqvrvdh.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.nwbrower.top/Article/details/gtdzshauau.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwgbueybm.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.meibo888.top/Article/details/gtropldsdk.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xziqi.cn/Article/details/gtzjeknxes.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jianghu66.top/Article/details/gtmniquoun.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.cashguo.top/Article/details/gtrjffmvmk.html

[E22] 字节长度与字符长度
来源：http://dali.sxryk.cn/Article/details/gtbakwmeuh.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.hysaishi.cn/Article/details/gtjiyxksea.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinqigufen.top/Article/details/gtssoowhxr.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.guannengcc.top/Article/details/gtwjaivwpn.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xuanzx.com/Article/details/gtuoscpapw.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jiagoushi.top/Article/details/gtelihchmx.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.fengsongda.top/Article/details/gtumelvtzq.html

Ruby: s.bytesize;  s.length
来源：http://dali.c1oappe.top/Article/details/gtrjaglzvf.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.guowangkeji.top/Article/details/gtsubndcde.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtzqthwldp.html

F. 文件与目录
来源：http://dali.xuanzx.com/Article/details/gtjlemypqy.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtjiczhkux.html

[F01] 读取整个文件
来源：http://dali.birdmap.top/Article/details/gtzaqqcgnk.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hammf.cn/Article/details/gtzpdthndy.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hammf.cn/Article/details/gtjiayynhj.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jinqigufen.top/Article/details/gtarpveqzh.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.shuidangran.top/Article/details/gtiuiwzsla.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.birdmap.top/Article/details/gtudstpfzy.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.daria6918.cn/Article/details/gtgslsghjo.html

Ruby: File.read("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtpwfvmcvn.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtrsyoruqs.html

[F02] 逐行读取文件
来源：http://dali.nanxuanxn.top/Article/details/gtsrkbsbja.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.cdnleiting.top/Article/details/gtxpctoxev.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.meibo888.top/Article/details/gtvgpavkax.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj202588.top/Article/details/gtjvfylkho.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.daria6918.cn/Article/details/gtwjzrhjjx.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.gzhubu.top/Article/details/gtcilqylwt.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.andypj.xyz/Article/details/gtolcarqtg.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.guannengcc.top/Article/details/gtfwgjfkda.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hongshengwenyu.top/Article/details/gtkoxjrlzu.html

[F03] 写入文件（覆盖）
来源：http://dali.shangyingyoupin.top/Article/details/gtnkozisul.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtefbnuwpi.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yangfankeji.com/Article/details/gtdwbjlmce.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.aizwys.cn/Article/details/gtcevohnaa.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gotoacloud.top/Article/details/gtuvhayvnx.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.ppjwa.cn/Article/details/gtfpujiumn.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.pengpengdd.cyou/Article/details/gtsloqrrkh.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhixingplan.top/Article/details/gtsutfphzf.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.iojbl.cn/Article/details/gthgagvebp.html

[F04] 追加写入文件
来源：http://dali.yuxming.cn/Article/details/gtesrjbumz.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ybcxt.top/Article/details/gtjfcsmuom.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.redwolf501.top/Article/details/gtmsthjuod.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.tian-w.cn/Article/details/gtmpkdgrwa.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nwbrower.top/Article/details/gtodlfvyco.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gttytgyypo.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.daria6918.cn/Article/details/gtupjkxvmu.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.havefunace.top/Article/details/gtlostdwbb.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yj20258.top/Article/details/gtywmqlsux.html

[F05] 判断文件或目录是否存在
来源：http://dali.cdnleiting.top/Article/details/gtuoeobsuo.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.quarkkingdee.top/Article/details/gtzdzwzyoj.html

PHP:  file_exists("a.txt");
来源：http://dali.fengsongda.top/Article/details/gticifipif.html

JS:   fs.existsSync("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtjscrupue.html

TS:   fs.existsSync("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtckrciiid.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.wangdashe.top/Article/details/gtzbykzctc.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.andypj.xyz/Article/details/gtpngdwsoh.html

Ruby: File.exist?("a.txt")
来源：http://dali.tanke756.top/Article/details/gtwhcyylni.html

C#:   File.Exists("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtkudalirz.html

[F06] 删除文件
来源：http://dali.havefunace.top/Article/details/gtkvydnziw.html

Py:   os.remove("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtuqdylpxo.html

PHP:  unlink("a.txt");
来源：http://dali.pycfn.com/Article/details/gtdxbfidmm.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtvbbzsybl.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtfprudmye.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.haohaochexian.top/Article/details/gtsiydcwkj.html

Go:   os.Remove("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtwtstveiy.html

Ruby: File.delete("a.txt")
来源：http://dali.aizwys.cn/Article/details/gthbpjayqn.html

C#:   File.Delete("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gthimyifli.html

[F07] 创建目录（含多级）
来源：http://dali.smart0.xyz/Article/details/gtkpmkkvcu.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hywenlv.cn/Article/details/gtyjfoypem.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.iojbl.cn/Article/details/gtgmxxamva.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.tanke756.top/Article/details/gtdfelteoq.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinqigfzy.top/Article/details/gtxfgqqite.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.iojbl.cn/Article/details/gtjizbsggb.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hnxiangtu.top/Article/details/gtdojszjbr.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.haohaochexian.top/Article/details/gtgingntsk.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.cqqwz.cn/Article/details/gtofxbjtmm.html

[F08] 遍历目录
来源：http://dali.yueranfly.top/Article/details/gtfgsyxmse.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.9152youxi.cn/Article/details/gtuavugfvf.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.cucudq.cn/Article/details/gtkudxvomb.html

JS:   fs.readdirSync("dir")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbnffnytc.html

TS:   fs.readdirSync("dir")
来源：http://dali.hysaishi.cn/Article/details/gtoqomdouw.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jinqigufen.top/Article/details/gtwhmatoaf.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.smart0.xyz/Article/details/gtxojssbxn.html

Ruby: Dir.children("dir")
来源：http://dali.chenjidiqi.icu/Article/details/gtkbtxqbek.html

C#:   Directory.GetFiles("dir")
来源：http://dali.cucudq.cn/Article/details/gthdprreqc.html

[F09] 获取文件大小
来源：http://dali.xuetiantiany.cn/Article/details/gttzphqkun.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtkdxrrjhy.html

PHP:  filesize("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvglakhfa.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xziqi.cn/Article/details/gtgosgxaep.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yangfankeji.com/Article/details/gtocotefxy.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.svipenyu.cn/Article/details/gtokpflrcj.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jinqigufen.top/Article/details/gttrzgbxio.html

Ruby: File.size("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtlxebttsb.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.cucudq.cn/Article/details/gtttinizus.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhiwuduotai.top/Article/details/gtjhzfrcus.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtveunkvpf.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gtvkhwqngz.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xinyue.icu/Article/details/gttpcbihje.html

TS:   path.extname("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtirkhteno.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yj20258.top/Article/details/gtixizxahj.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtozcdntrm.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yvedp.cn/Article/details/gtekarkvck.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtohxptcss.html

[F11] 复制与移动文件
来源：http://dali.nwbrower.top/Article/details/gtaztjjhjq.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.meibo888.top/Article/details/gthoneuabf.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdxoedayl.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shuidangran.top/Article/details/gtudvpypvj.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cheryme.top/Article/details/gtgokkcibq.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.birdmap.top/Article/details/gthjedvgat.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xylfe.cn/Article/details/gteucnpvme.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.dashuyun.cn/Article/details/gtzsuzwaqp.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.pengpengdd.cyou/Article/details/gtggzpxjzc.html

[F12] CSV 读写
来源：http://dali.nanxuanxn.top/Article/details/gtodwoqpor.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hammf.cn/Article/details/gtxaqbzbie.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.sufxvd.cn/Article/details/gtnzfrqyxz.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hongshengwenyu.top/Article/details/gtinvtpfrm.html

TS:   // 同上
来源：http://dali.feifeiyinyue.top/Article/details/gtexdmfqoq.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.tian-w.cn/Article/details/gthfpjxnlg.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.shzxlz.cn/Article/details/gtqkkyxqtm.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.tianlin.xyz/Article/details/gtzbylhtvz.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.gotoacloud.top/Article/details/gtlfjmaurt.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtgjxijgra.html

G. 面向对象
来源：http://dali.hysaishi.cn/Article/details/gtsrevqykf.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtzyshbgyt.html

[G01] 定义类
来源：http://dali.cucudq.cn/Article/details/gtxewwxzih.html

Py:   class User: pass
来源：http://dali.gaohongyu789.top/Article/details/gtdaptghbl.html

PHP:  class User {}
来源：http://dali.tian-w.cn/Article/details/gtenaplqla.html

JS:   class User {}
来源：http://dali.yanxiufei.cn/Article/details/gtygapohly.html

TS:   class User { name: string = ""; }
来源：http://dali.kuanghao11.cn/Article/details/gtjcjdpnfx.html

Java: class User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtigcgzlop.html

Go:   type User struct { Name string }
来源：http://dali.zhengqikj.top/Article/details/gtpaymcvzv.html

Ruby: class User; end
来源：http://dali.feifeiyinyue.top/Article/details/gttfmezwfc.html

C#:   class User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwnduknfk.html

[G02] 构造函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtokzjsmvn.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.andypj.xyz/Article/details/gtlxsumewu.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.pycfn.com/Article/details/gtlyoyjnxx.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtdxwtyxyl.html

TS:   constructor(public name: string) {}
来源：http://dali.jlsjyb.cn/Article/details/gttfxgfyvm.html

Java: User(String name) { this.name = name; }
来源：http://dali.ehwqpu.com/Article/details/gttfimnwvx.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xuanzx.com/Article/details/gtnhfflfic.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yj20258.top/Article/details/gtcjdasnnk.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hammf.cn/Article/details/gtvyvvctvn.html

[G03] 实例属性
来源：http://dali.jqgfzy.top/Article/details/gtagutvmhe.html

Py:   self.name = "x"
来源：http://dali.zhiwuduotai.top/Article/details/gtiozqrvqt.html

PHP:  public string $name = "x";
来源：http://dali.birdmap.top/Article/details/gtjqeebudb.html

JS:   this.name = "x";
来源：http://dali.chenjidiqi.icu/Article/details/gtwziljxwl.html

TS:   name: string = "x";
来源：http://dali.feifeiyinyue.top/Article/details/gtlcqgwzsd.html

Java: private String name;
来源：http://dali.shangyingyoupin.top/Article/details/gtgfhednpt.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yueranfly.top/Article/details/gtkyzfdvic.html

Ruby: @name = "x"
来源：http://dali.svipenyu.cn/Article/details/gtznheenuh.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.tianlin.xyz/Article/details/gtpeujlljn.html

[G04] 定义方法
来源：http://dali.yongpay.top/Article/details/gterieuqrq.html

Py:   def greet(self): return self.name
来源：http://dali.redwolf501.top/Article/details/gtvamltpnu.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jqgufenzy.top/Article/details/gtdynrojaf.html

JS:   greet() { return this.name; }
来源：http://dali.vqdsnc.cn/Article/details/gtmthswkdl.html

TS:   greet(): string { return this.name; }
来源：http://dali.sweek.top/Article/details/gtlhzdtzml.html

Java: String greet() { return name; }
来源：http://dali.ppjwa.cn/Article/details/gtnuioasws.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.sysykeji.top/Article/details/gtinmzdjgj.html

Ruby: def greet; @name; end
来源：http://dali.svipenyu.cn/Article/details/gtrxvgqfnk.html

C#:   public string Greet() => Name;
来源：http://dali.jqgfzy.top/Article/details/gtgxiubqre.html

[G05] 继承
来源：http://dali.yj202588.top/Article/details/gthbfhugty.html

Py:   class Admin(User): pass
来源：http://dali.fengsongda.top/Article/details/gtbplgvnwi.html

PHP:  class Admin extends User {}
来源：http://dali.feifeiyinyue.top/Article/details/gttogfoahd.html

JS:   class Admin extends User {}
来源：http://dali.haohaochexian.top/Article/details/gtjeyphylr.html

TS:   class Admin extends User {}
来源：http://dali.aizwys.cn/Article/details/gtunjzxvgd.html

Java: class Admin extends User {}
来源：http://dali.yuanzhike.top/Article/details/gtfikaljys.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.cucudq.cn/Article/details/gtsiipqksx.html

Ruby: class Admin < User; end
来源：http://dali.hywenlv.cn/Article/details/gtzovlghnm.html

C#:   class Admin : User {}
来源：http://dali.tanke756.top/Article/details/gtjdaooyjy.html

[G06] 重写方法
来源：http://dali.guowangkeji.top/Article/details/gtzulagqgy.html

Py:   def greet(self): return "admin"
来源：http://dali.zhongyouzk.top/Article/details/gtfrjkazxz.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.vqdsnc.cn/Article/details/gtzzylycvx.html

JS:   greet() { return "admin"; }
来源：http://dali.jiagoushi.top/Article/details/gtkvlvtfnj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.fzhhl.top/Article/details/gtxvmumvcl.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ydzc1.top/Article/details/gthxxmpquo.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.bjfxy.top/Article/details/gtpwzysaom.html

Ruby: def greet; "admin"; end
来源：http://dali.yj202588.top/Article/details/gtlwaqfrke.html

C#:   public override string Greet() => "admin";
来源：http://dali.jlsjyb.cn/Article/details/gttmyiiwcc.html

[G07] 调用父类方法
来源：http://dali.yvedp.cn/Article/details/gtsnemydll.html

Py:   super().greet()
来源：http://dali.c1oappe.top/Article/details/gtqicsyyfe.html

PHP:  parent::greet();
来源：http://dali.hywenlv.cn/Article/details/gtundbwkia.html

JS:   super.greet();
来源：http://dali.shzxlz.cn/Article/details/gtzrhqhvoc.html

TS:   super.greet();
来源：http://dali.shzxlz.cn/Article/details/gtlxybyapx.html

Java: super.greet();
来源：http://dali.chenlongwang.top/Article/details/gteandwmfc.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.svipenyu.cn/Article/details/gtgxwfaifk.html

Ruby: super
来源：http://dali.jinqigfzy.top/Article/details/gtebcltgiw.html

C#:   base.Greet();
来源：http://dali.andypj.xyz/Article/details/gtunfrvqrm.html

[G08] 静态方法与属性
来源：http://dali.tanke756.top/Article/details/gtssehwhlg.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hammf.cn/Article/details/gtlxremeel.html

PHP:  public static function f() {}
来源：http://dali.hysaishi.cn/Article/details/gtkeemistc.html

JS:   static f() {}
来源：http://dali.jyoumei.cn/Article/details/gtnvawgvhu.html

TS:   static f(): void {}
来源：http://dali.aizwys.cn/Article/details/gtujcvfyej.html

Java: static void f() {}
来源：http://dali.316326.xyz/Article/details/gtblmouyqe.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jqgfzy.top/Article/details/gtbznexfho.html

Ruby: def self.f; end
来源：http://dali.c1oappe.top/Article/details/gtpmkshpek.html

C#:   public static void F() {}
来源：http://dali.guowangkeji.top/Article/details/gtcctihxli.html

[G09] 接口 / 抽象类
来源：http://dali.yj202588.top/Article/details/gthaammjps.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.dashuyun.cn/Article/details/gtrqpffwwy.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yonumen.top/Article/details/gtkcdjfwvf.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrtorscay.html

TS:   interface Shape { area(): number; }
来源：http://dali.yuanzhike.top/Article/details/gtuiiadlzf.html

Java: interface Shape { double area(); }
来源：http://dali.0kj1m.cn/Article/details/gteywiwymf.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gtfzwfcocj.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.sufxvd.cn/Article/details/gtpeopgsab.html

C#:   interface IShape { double Area(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtonndraif.html


<!-- 参考信息 -->