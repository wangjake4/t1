代发 wailian999

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.guowangkeji.top/Article/details/gt2mollyryl.html

[E11] 反转字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ygpzfwwr.html

Py:   s[::-1]
来源：http://dali.yj20258888.top/Article/details/gt2jlipuhka.html

PHP:  strrev($s);
来源：http://dali.sysykeji.top/Article/details/gt2mfmegskn.html

JS:   [...s].reverse().join("")
来源：http://dali.gogol.net.cn/Article/details/gt2tdxxduju.html

TS:   [...s].reverse().join("")
来源：http://dali.iojbl.cn/Article/details/gt2dsfredue.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2clvgevww.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhixingplan.top/Article/details/gt2lwdphtji.html

Ruby: s.reverse
来源：http://dali.birdmap.top/Article/details/gt2aqbmhqpy.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yj20258.top/Article/details/gt2jadobvsy.html

[E12] 统计某字符出现次数
来源：http://dali.wangdashe.top/Article/details/gt2msfttvoq.html

Py:   s.count("a")
来源：http://dali.andypj.xyz/Article/details/gt2mgespjyl.html

PHP:  substr_count($s, "a");
来源：http://dali.jiagoushi.top/Article/details/gt2xapxpsqo.html

JS:   s.split("a").length - 1
来源：http://dali.hongshengwenyu.top/Article/details/gt2jaiitvol.html

TS:   s.split("a").length - 1
来源：http://dali.yuanzhike.top/Article/details/gt2wxfpiulo.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bwkmqkzc.html

Go:   strings.Count(s, "a")
来源：http://dali.zhongyouzk.top/Article/details/gt2vhilloob.html

Ruby: s.count("a")
来源：http://dali.tianlin.xyz/Article/details/gt2bdjpteuq.html

C#:   s.Count(c => c == 'a')
来源：http://dali.cdnleiting.top/Article/details/gt2mhtnyvgl.html

[E13] 逐字符遍历
来源：http://dali.0kj1m.cn/Article/details/gt2gjdnitto.html

Py:   for ch in s: print(ch)
来源：http://dali.sweek.top/Article/details/gt2klgxdvsy.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.gotoacloud.top/Article/details/gt2wdzkxdzz.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aqfnyvyv.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tanke756.top/Article/details/gt2iddkpvfy.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.ehwqpu.com/Article/details/gt2refljfqk.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.aizwys.cn/Article/details/gt2epbyhjqy.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.guowangkeji.top/Article/details/gt2lllihthm.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.quarkkingdee.top/Article/details/gt2oalcynlk.html

[E14] URL 编码与 Base64
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jeyrfeky.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zycfv.cn/Article/details/gt2wpbhcnuf.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.kuanghao11.cn/Article/details/gt2dilhkjcr.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.chenjidiqi.icu/Article/details/gt2izoknccy.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yj20258888.top/Article/details/gt2urkzysod.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.sysykeji.top/Article/details/gt2peztberd.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.dianchejie.cn/Article/details/gt2rnfojcpu.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jlsjyb.cn/Article/details/gt2ddpohmaj.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.9152youxi.cn/Article/details/gt2sigiotpw.html

[E15] HTML 转义 / 反转义
来源：http://dali.hnqzz.top/Article/details/gt2rflnkoca.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jyoumei.cn/Article/details/gt2jwtexnkh.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.vqdsnc.cn/Article/details/gt2oflvpmeb.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.kuanghao11.cn/Article/details/gt2prhfviyp.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.c1oappe.top/Article/details/gt2jwcqtsbh.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.tian-w.cn/Article/details/gt2mmevktcq.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.birdmap.top/Article/details/gt2isjnnqfv.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hfpthk.cn/Article/details/gt2draedjus.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.9152youxi.cn/Article/details/gt2pasdjiiy.html

[E16] 数字千分位
来源：http://dali.aibaodan.cn/Article/details/gt2ccwmolfk.html

Py:   f"{1234567:,}"
来源：http://dali.tanke756.top/Article/details/gt2vkpabxhj.html

PHP:  number_format(1234567);
来源：http://dali.jiagoushi.top/Article/details/gt2btydrvnm.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yonumen.top/Article/details/gt2lqsaziup.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.wangshuangyany.cn/Article/details/gt2crpshsbn.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.nwbrower.top/Article/details/gt2twawobaj.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.ivvv.top/Article/details/gt2hvhtnzhn.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yueranfly.top/Article/details/gt2gjxeojui.html

C#:   1234567.ToString("N0")
来源：http://dali.snrcjt.cn/Article/details/gt2jyhafhix.html

[E17] 首字母大写
来源：http://dali.hysaishi.cn/Article/details/gt2peujnlbj.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.meibo888.top/Article/details/gt2xxopzxys.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.kuanghao11.cn/Article/details/gt2aolegjrp.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sxryk.cn/Article/details/gt2rdsnstnd.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhoulong.xyz/Article/details/gt2lnstnaqg.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.bjfxy.top/Article/details/gt2hmbbcafp.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.tianlin.xyz/Article/details/gt2cifglfsw.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2tofywzfm.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.tianlin.xyz/Article/details/gt2aayogell.html

[E18] 模板占位符替换
来源：http://dali.yj20258.top/Article/details/gt2mjrokxht.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hongshengwenyu.top/Article/details/gt2hfpbytna.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.havefunace.top/Article/details/gt2fojwhshj.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.316326.xyz/Article/details/gt2sfdyqrza.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.smart0.xyz/Article/details/gt2bpcgbdtw.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yj20258.top/Article/details/gt2cgqkcjcl.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.guannengcc.top/Article/details/gt2hobtexsd.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.hnxiangtu.top/Article/details/gt2ayddntvk.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.aibaodan.cn/Article/details/gt2fnvyduti.html

[E19] 多行文本按行拆分
来源：http://dali.havefunace.top/Article/details/gt2fjmvryub.html

Py:   s.splitlines()
来源：http://dali.yongpay.top/Article/details/gt2ospasbtj.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.meibo888.top/Article/details/gt2zmapymez.html

JS:   s.split(/\r?\n/)
来源：http://dali.birdmap.top/Article/details/gt2ogybioez.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxmjafah.html

Java: s.lines().toList()
来源：http://dali.9152youxi.cn/Article/details/gt2stxmdsfy.html

Go:   strings.Split(s, "\n")
来源：http://dali.wangdashe.top/Article/details/gt2acivvtbw.html

Ruby: s.lines
来源：http://dali.tanke756.top/Article/details/gt2lrbqsbpe.html

C#:   s.Split('\n')
来源：http://dali.wangshuangyany.cn/Article/details/gt2jsojbhcj.html

[E20] 判断字符串是否为空
来源：http://dali.yuxming.cn/Article/details/gt2lidynvba.html

Py:   if not s:
来源：http://dali.aibaodan.cn/Article/details/gt2rlevcbco.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jinqigufen.top/Article/details/gt2cnduhtzm.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2nimvnghl.html

TS:   if (s === "") {}
来源：http://dali.guowangkeji.top/Article/details/gt2qfaspngp.html

Java: if (s.isEmpty()) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2ewqdbbka.html

Go:   if s == "" {}
来源：http://dali.andypj.xyz/Article/details/gt2yxhohudq.html

Ruby: if s.empty?
来源：http://dali.yueranfly.top/Article/details/gt2ovkgjuna.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zdqjudy.top/Article/details/gt2ndzswukn.html

[E21] 超长截断加省略号
来源：http://dali.wangdashe.top/Article/details/gt2eesddzhy.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jinqigfzy.top/Article/details/gt2oxgnazzw.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.bjfxy.top/Article/details/gt2mqueqcrw.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.aizwys.cn/Article/details/gt2msstgmyp.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jyoumei.cn/Article/details/gt2qyekydnp.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ivvv.top/Article/details/gt2gqcamlam.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.fzhhl.top/Article/details/gt2rlwbatjt.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.iojbl.cn/Article/details/gt2zluwqfxa.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.xziqi.cn/Article/details/gt2zzabanac.html

[E22] 字节长度与字符长度
来源：http://dali.xinyue.icu/Article/details/gt2bphspfep.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.9152youxi.cn/Article/details/gt2yopjqqqe.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zdqjudy.top/Article/details/gt2qmuyjkhq.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.quarkkingdee.top/Article/details/gt2novmvfez.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.mhx1999.top/Article/details/gt2kactezpo.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.gotoacloud.top/Article/details/gt2woftjylh.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.fzhhl.top/Article/details/gt2dyzlybtz.html

Ruby: s.bytesize;  s.length
来源：http://dali.cucudq.cn/Article/details/gt2vtrhaxpr.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yanxiufei.cn/Article/details/gt2qgrwbxby.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2oqhzfkiw.html

F. 文件与目录
来源：http://dali.guowangkeji.top/Article/details/gt2wnoiasmf.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2nbzmfmya.html

[F01] 读取整个文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ordupreu.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pflpdgmk.html

PHP:  file_get_contents("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gt2msogjawz.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.quarkkingdee.top/Article/details/gt2rivnakhq.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.haohaochexian.top/Article/details/gt2mrudxiti.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.ppjwa.cn/Article/details/gt2ryomgklm.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yj20258888.top/Article/details/gt2qlkjbihc.html

Ruby: File.read("a.txt")
来源：http://dali.mhx1999.top/Article/details/gt2dtvhboyd.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.wangdashe.top/Article/details/gt2pablpapg.html

[F02] 逐行读取文件
来源：http://dali.cqqwz.cn/Article/details/gt2myvvlbmo.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ydzc1.top/Article/details/gt2wzdeaqln.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.tianlin.xyz/Article/details/gt2uugafdxa.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2funcioqi.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nanxinkj.top/Article/details/gt2fmxmhtvs.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yuanzhike.top/Article/details/gt2popoovyl.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jinqigfzy.top/Article/details/gt2ptpwwspt.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.xziqi.cn/Article/details/gt2yvyuvaix.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jlsjyb.cn/Article/details/gt2caadiigr.html

[F03] 写入文件（覆盖）
来源：http://dali.andypj.xyz/Article/details/gt2yowxsspy.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhoulong.xyz/Article/details/gt2gwvndvrf.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.chenlongwang.top/Article/details/gt2iuqhykpf.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ybcxt.top/Article/details/gt2uvmahnym.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinqigufen.top/Article/details/gt2kafsjxcq.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.mhx1999.top/Article/details/gt2vzefclul.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xuanzx.com/Article/details/gt2lmxdzyup.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xuanzx.com/Article/details/gt2garyhzwy.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.fengsongda.top/Article/details/gt2oizaencc.html

[F04] 追加写入文件
来源：http://dali.birdmap.top/Article/details/gt2euizvkqm.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.cdnleiting.top/Article/details/gt2ohmqzvyl.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2cgmxbsqw.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.dianchejie.cn/Article/details/gt2sahrzxqb.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hywenlv.cn/Article/details/gt2hhitpxvz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.andypj.xyz/Article/details/gt2mgwbvcnf.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hywenlv.cn/Article/details/gt2ibjqonhr.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hywenlv.cn/Article/details/gt2rqicathm.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hongshengwenyu.top/Article/details/gt2qxxrauvp.html

[F05] 判断文件或目录是否存在
来源：http://dali.yonumen.top/Article/details/gt2hogpvvhs.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.sysykeji.top/Article/details/gt2jlodzgzu.html

PHP:  file_exists("a.txt");
来源：http://dali.cheryme.top/Article/details/gt2ssxftcxa.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xylfe.cn/Article/details/gt2wdkolkur.html

TS:   fs.existsSync("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2jwwjmxbc.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhiwuduotai.top/Article/details/gt2iacocjjc.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.chenzaomai.com/Article/details/gt2usapcvxf.html

Ruby: File.exist?("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2cdqqsmxo.html

C#:   File.Exists("a.txt")
来源：http://dali.yj20258.top/Article/details/gt2bntlggwo.html

[F06] 删除文件
来源：http://dali.haohaochexian.top/Article/details/gt2ujgloatb.html

Py:   os.remove("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ztmzoewe.html

PHP:  unlink("a.txt");
来源：http://dali.birdmap.top/Article/details/gt2sdthoifv.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2vyjntrvk.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2hqnvbvbz.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.gaohongyu789.top/Article/details/gt2kkvpxfls.html

Go:   os.Remove("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2ddhypedj.html

Ruby: File.delete("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2wayywzif.html

C#:   File.Delete("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gt2fezyzpzu.html

[F07] 创建目录（含多级）
来源：http://dali.redwolf501.top/Article/details/gt2rwtsvdpp.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.9152youxi.cn/Article/details/gt2wtmntmim.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yangfankeji.com/Article/details/gt2znnhxxwt.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.quarkkingdee.top/Article/details/gt2vdyrdlnv.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.svipenyu.cn/Article/details/gt2eajdpdnc.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2piwqvzts.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.iojbl.cn/Article/details/gt2olrwbxhp.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hfpthk.cn/Article/details/gt2oyhappzq.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.smart0.xyz/Article/details/gt2qwjwerjs.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2dcqggvwa.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.feifeiyinyue.top/Article/details/gt2cccqsqwa.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.fengsongda.top/Article/details/gt2waamtsrp.html

JS:   fs.readdirSync("dir")
来源：http://dali.yvedp.cn/Article/details/gt2ppkyjfwn.html

TS:   fs.readdirSync("dir")
来源：http://dali.snrcjt.cn/Article/details/gt2ityyxhej.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.snrcjt.cn/Article/details/gt2qefvmtoc.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.smart0.xyz/Article/details/gt2nnvbdoks.html

Ruby: Dir.children("dir")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dvgibgmc.html

C#:   Directory.GetFiles("dir")
来源：http://dali.haohaochexian.top/Article/details/gt2fpnmecrh.html

[F09] 获取文件大小
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ipgzgonv.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2cakaxypz.html

PHP:  filesize("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gt2osmthyxk.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tfnfzrgw.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2amyfopax.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cashguo.top/Article/details/gt2lzcvgkll.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yueranfly.top/Article/details/gt2nwbrlivw.html

Ruby: File.size("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2bpkbywpu.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.dianchejie.cn/Article/details/gt2cdltupze.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yvjtxevp.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2qxlanytu.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gt2gfotgyca.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2xtohmoam.html

TS:   path.extname("a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2liicfule.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.nwbrower.top/Article/details/gt2dgrdilyk.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.cheryme.top/Article/details/gt2vuvgebca.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2fumppoxe.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ivvv.top/Article/details/gt2ecskefox.html

[F11] 复制与移动文件
来源：http://dali.hywenlv.cn/Article/details/gt2vbkglrpe.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.smart0.xyz/Article/details/gt2xlgkskts.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.ydzc1.top/Article/details/gt2mnrhvvyh.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2nugfmrdt.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.guannengcc.top/Article/details/gt2jbolieff.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xuanzx.com/Article/details/gt2gctarxzx.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yj202588.top/Article/details/gt2zzthujvn.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xylfe.cn/Article/details/gt2hqwomzhc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yueranfly.top/Article/details/gt2fydujspf.html

[F12] CSV 读写
来源：http://dali.gzhubu.top/Article/details/gt2pevgvfzy.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ivvv.top/Article/details/gt2wxjqhhnz.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.smart0.xyz/Article/details/gt2kcnkismc.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.ivvv.top/Article/details/gt2uirvlvdb.html

TS:   // 同上
来源：http://dali.smart0.xyz/Article/details/gt2xcphafan.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.gogol.net.cn/Article/details/gt2mlbrhqrl.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cwsdfkqu.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhixingplan.top/Article/details/gt2cduxveva.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.0kj1m.cn/Article/details/gt2akysjttt.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2ugpitjgy.html

G. 面向对象
来源：http://dali.snrcjt.cn/Article/details/gt2swcphtvq.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2jfclsgwq.html

[G01] 定义类
来源：http://dali.shangyingyoupin.top/Article/details/gt2xwyegsaz.html

Py:   class User: pass
来源：http://dali.hnxiangtu.top/Article/details/gt2olxjzcow.html

PHP:  class User {}
来源：http://dali.svipenyu.cn/Article/details/gt2uzuhtebt.html

JS:   class User {}
来源：http://dali.ppjwa.cn/Article/details/gt2kivfjmyy.html

TS:   class User { name: string = ""; }
来源：http://dali.aizwys.cn/Article/details/gt2hcjjghkb.html

Java: class User {}
来源：http://dali.sweek.top/Article/details/gt2gttbaept.html

Go:   type User struct { Name string }
来源：http://dali.zhiwuduotai.top/Article/details/gt2cbolvfam.html

Ruby: class User; end
来源：http://dali.gotoacloud.top/Article/details/gt2zjxuqcjp.html

C#:   class User {}
来源：http://dali.gaohongyu789.top/Article/details/gt2nydtgsax.html

[G02] 构造函数
来源：http://dali.sxryk.cn/Article/details/gt2rvddxaok.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yj20258.top/Article/details/gt2uoazazah.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.cheryme.top/Article/details/gt2ptbbfhid.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.nanxinkj.top/Article/details/gt2bczevkdy.html

TS:   constructor(public name: string) {}
来源：http://dali.hfpthk.cn/Article/details/gt2kpgtegmm.html

Java: User(String name) { this.name = name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2icgbjvea.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.gotoacloud.top/Article/details/gt2eybrmijh.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.pengpengdd.cyou/Article/details/gt2yqsydwup.html

C#:   public User(string name) { Name = name; }
来源：http://dali.birdmap.top/Article/details/gt2czsznqrx.html

[G03] 实例属性
来源：http://dali.jlsjyb.cn/Article/details/gt2uwbylaqv.html

Py:   self.name = "x"
来源：http://dali.shuidangran.top/Article/details/gt2whdroici.html

PHP:  public string $name = "x";
来源：http://dali.tianlin.xyz/Article/details/gt2tzemyqrv.html

JS:   this.name = "x";
来源：http://dali.xylfe.cn/Article/details/gt2kjqzdjup.html

TS:   name: string = "x";
来源：http://dali.svipenyu.cn/Article/details/gt2dibjrjvl.html

Java: private String name;
来源：http://dali.dianchejie.cn/Article/details/gt2jfnrkovr.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.gogol.net.cn/Article/details/gt2yokxdxrr.html

Ruby: @name = "x"
来源：http://dali.gaohongyu789.top/Article/details/gt2dcbfrsxv.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jiagoushi.top/Article/details/gt2dydnfqhh.html

[G04] 定义方法
来源：http://dali.hnxiangtu.top/Article/details/gt2vkffhdqz.html

Py:   def greet(self): return self.name
来源：http://dali.ppjwa.cn/Article/details/gt2uqmjesfs.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2dgkjsrot.html

JS:   greet() { return this.name; }
来源：http://dali.xziqi.cn/Article/details/gt2gxiqnpgs.html

TS:   greet(): string { return this.name; }
来源：http://dali.ybcxt.top/Article/details/gt2jwtacrjk.html

Java: String greet() { return name; }
来源：http://dali.zdqjudy.top/Article/details/gt2kpwxvvfv.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.andypj.xyz/Article/details/gt2mplpgjnp.html

Ruby: def greet; @name; end
来源：http://dali.hfpthk.cn/Article/details/gt2rstzgfke.html

C#:   public string Greet() => Name;
来源：http://dali.ehwqpu.com/Article/details/gt2nbfcmlek.html

[G05] 继承
来源：http://dali.yvedp.cn/Article/details/gt2oneejomr.html

Py:   class Admin(User): pass
来源：http://dali.dashuyun.cn/Article/details/gt2onpriela.html

PHP:  class Admin extends User {}
来源：http://dali.sufxvd.cn/Article/details/gt2rjbgtnzv.html

JS:   class Admin extends User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wthmqprb.html

TS:   class Admin extends User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ffgfjzck.html

Java: class Admin extends User {}
来源：http://dali.shzxlz.cn/Article/details/gt2gdctlnok.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.svipenyu.cn/Article/details/gt2vnerijnn.html

Ruby: class Admin < User; end
来源：http://dali.chenzaomai.com/Article/details/gt2xlkhrnug.html

C#:   class Admin : User {}
来源：http://dali.sysykeji.top/Article/details/gt2znuvlekn.html

[G06] 重写方法
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zfafzqnb.html

Py:   def greet(self): return "admin"
来源：http://dali.yj202588.top/Article/details/gt2gorwhzka.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.nanxuanxn.top/Article/details/gt2uqrbkcsk.html

JS:   greet() { return "admin"; }
来源：http://dali.tian-w.cn/Article/details/gt2iibzyqxy.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ybcxt.top/Article/details/gt2gmhqpvnl.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jyoumei.cn/Article/details/gt2diatfrbn.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.gotoacloud.top/Article/details/gt2txrvumlx.html

Ruby: def greet; "admin"; end
来源：http://dali.yangfankeji.com/Article/details/gt2eudkcfxu.html

C#:   public override string Greet() => "admin";
来源：http://dali.cashguo.top/Article/details/gt2umuylnrd.html

[G07] 调用父类方法
来源：http://dali.yuxming.cn/Article/details/gt2lloxacqc.html

Py:   super().greet()
来源：http://dali.tanke756.top/Article/details/gt2jfpmbzcz.html

PHP:  parent::greet();
来源：http://dali.shuidangran.top/Article/details/gt2oiyvflze.html

JS:   super.greet();
来源：http://dali.ppjwa.cn/Article/details/gt2jzbcoevo.html

TS:   super.greet();
来源：http://dali.cqqwz.cn/Article/details/gt2nekwmrpj.html

Java: super.greet();
来源：http://dali.jqgufenzy.top/Article/details/gt2glbpmhkl.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.9152youxi.cn/Article/details/gt2ylbmvugk.html

Ruby: super
来源：http://dali.guowangkeji.top/Article/details/gt2zgqrobea.html

C#:   base.Greet();
来源：http://dali.pengpengdd.cyou/Article/details/gt2ffnolzdl.html

[G08] 静态方法与属性
来源：http://dali.svipenyu.cn/Article/details/gt2baeugvve.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.wangshuangyany.cn/Article/details/gt2tkixbcax.html

PHP:  public static function f() {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2vryetczb.html

JS:   static f() {}
来源：http://dali.yj202588.top/Article/details/gt2ufcgtbbm.html

TS:   static f(): void {}
来源：http://dali.zhongyouzk.top/Article/details/gt2virhbhdr.html

Java: static void f() {}
来源：http://dali.yj20258.top/Article/details/gt2ujonirus.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.daxiang520.top/Article/details/gt2ixnxbwfl.html

Ruby: def self.f; end
来源：http://dali.pycfn.com/Article/details/gt2zmftktkd.html

C#:   public static void F() {}
来源：http://dali.shzxlz.cn/Article/details/gt2bhjthdiv.html

[G09] 接口 / 抽象类
来源：http://dali.pengpengdd.cyou/Article/details/gt2ggtxtxec.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.316326.xyz/Article/details/gt2rdozrqha.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.bjfxy.top/Article/details/gt2aogwngph.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.chenlongwang.top/Article/details/gt2tbjimaxx.html

TS:   interface Shape { area(): number; }
来源：http://dali.zycfv.cn/Article/details/gt2hybgzgtg.html


<!-- 参考信息 -->