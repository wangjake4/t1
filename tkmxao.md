代发 wailian999

Java: s.replaceAll("\\s+", "")
来源：http://dali.feifeiyinyue.top/Article/details/gtniluosrn.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yj20258888.top/Article/details/gtcqqnljwd.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yj20258.top/Article/details/gtfbpaaxuq.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.sysykeji.top/Article/details/gtolpewkvk.html

[E10] 左侧补零 / 定长填充
来源：http://dali.sysykeji.top/Article/details/gtmylbzzso.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.xinyue.icu/Article/details/gtqtlkgidx.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.meibo888.top/Article/details/gtpxiofszr.html

JS:   "7".padStart(3, "0")
来源：http://dali.redwolf501.top/Article/details/gtulabxeco.html

TS:   "7".padStart(3, "0")
来源：http://dali.sysykeji.top/Article/details/gtrincnnjs.html

Java: String.format("%03d", 7)
来源：http://dali.yj202588.top/Article/details/gtsklsetgw.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhengqikj.top/Article/details/gtqfytjxev.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.guannengcc.top/Article/details/gtuuxjlooq.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.sufxvd.cn/Article/details/gtrxreppbd.html

[E11] 反转字符串
来源：http://dali.zdqjudy.top/Article/details/gtixwfmjyy.html

Py:   s[::-1]
来源：http://dali.pycfn.com/Article/details/gtczjfhmmd.html

PHP:  strrev($s);
来源：http://dali.fengsongda.top/Article/details/gtxmeopewi.html

JS:   [...s].reverse().join("")
来源：http://dali.jqgfzy.top/Article/details/gtjelkdrxj.html

TS:   [...s].reverse().join("")
来源：http://dali.ydzc1.top/Article/details/gtvonwwzyy.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.meibo888.top/Article/details/gtmhnayzns.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.ivvv.top/Article/details/gteuydzmtu.html

Ruby: s.reverse
来源：http://dali.jlsjyb.cn/Article/details/gtdzozxlzd.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hywenlv.cn/Article/details/gtbrvspqni.html

[E12] 统计某字符出现次数
来源：http://dali.yvedp.cn/Article/details/gtpcmngftd.html

Py:   s.count("a")
来源：http://dali.jinqigfzy.top/Article/details/gthwiensfm.html

PHP:  substr_count($s, "a");
来源：http://dali.fzhhl.top/Article/details/gtiwdaxjtt.html

JS:   s.split("a").length - 1
来源：http://dali.shuidangran.top/Article/details/gthtblmohk.html

TS:   s.split("a").length - 1
来源：http://dali.zdqjudy.top/Article/details/gtshhpkxwj.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yj202588.top/Article/details/gtrgphlsrz.html

Go:   strings.Count(s, "a")
来源：http://dali.dianchejie.cn/Article/details/gtgjjnhzje.html

Ruby: s.count("a")
来源：http://dali.bjfxy.top/Article/details/gtdffbkxpn.html

C#:   s.Count(c => c == 'a')
来源：http://dali.kuanghao11.cn/Article/details/gtxykldssi.html

[E13] 逐字符遍历
来源：http://dali.ivvv.top/Article/details/gtnbkiitck.html

Py:   for ch in s: print(ch)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwubuqjsu.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.dianchejie.cn/Article/details/gtjyzthsbt.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jiagoushi.top/Article/details/gttfghxibe.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.kuanghao11.cn/Article/details/gtrwheqscu.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gthmjbdbau.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvljnyyao.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yueranfly.top/Article/details/gtbaimpsdz.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.pengpengdd.cyou/Article/details/gtjlckrulu.html

[E14] URL 编码与 Base64
来源：http://dali.daxiang520.top/Article/details/gtzpsgytck.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.ybcxt.top/Article/details/gtjustjhhm.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yonumen.top/Article/details/gtmqppzdzp.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.meibo888.top/Article/details/gtytkytnpc.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yuxming.cn/Article/details/gtxudinvtq.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.9152youxi.cn/Article/details/gtjkfsokat.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhixingplan.top/Article/details/gtgzyupyfg.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.sysykeji.top/Article/details/gtewquytdu.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.aizwys.cn/Article/details/gtmspvucbr.html

[E15] HTML 转义 / 反转义
来源：http://dali.yongpay.top/Article/details/gtaxflqdzq.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwkvceiax.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.nwbrower.top/Article/details/gtmwscfcda.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.xuanzx.com/Article/details/gtvthgqqdf.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yangfankeji.com/Article/details/gtenaslndb.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yuxming.cn/Article/details/gtozocuzbi.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.gzhubu.top/Article/details/gtyrhlauku.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jinqigufen.top/Article/details/gtzxlazxek.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.xinyue.icu/Article/details/gtyirydiey.html

[E16] 数字千分位
来源：http://dali.fzhhl.top/Article/details/gtznoskwhp.html

Py:   f"{1234567:,}"
来源：http://dali.ehwqpu.com/Article/details/gtqwqdlkbl.html

PHP:  number_format(1234567);
来源：http://dali.jinqigufen.top/Article/details/gtubbcyiqn.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yanxiufei.cn/Article/details/gtrdgtwjha.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.hnqzz.top/Article/details/gthzaatngi.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.haohaochexian.top/Article/details/gtjcsoqxxm.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yj20258888.top/Article/details/gtvjfjmnvi.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.gogol.net.cn/Article/details/gtefqaxlws.html

C#:   1234567.ToString("N0")
来源：http://dali.mhx1999.top/Article/details/gtuvbmwqmu.html

[E17] 首字母大写
来源：http://dali.wangshuangyany.cn/Article/details/gtrbuqmlmp.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuhgomtvk.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jinqigufen.top/Article/details/gtpublilnd.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.andypj.xyz/Article/details/gtrrvinzne.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shzxlz.cn/Article/details/gtbfpfhnam.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.cashguo.top/Article/details/gtmhuvvtok.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.kuanghao11.cn/Article/details/gtgxhxgkxw.html

Ruby: s.capitalize
来源：http://dali.xziqi.cn/Article/details/gtytqhmdqa.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvpswsrsu.html

[E18] 模板占位符替换
来源：http://dali.jinqigfzy.top/Article/details/gtlkerbvdd.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.guannengcc.top/Article/details/gtwlxbjute.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.gaohongyu789.top/Article/details/gtnhtuxlqj.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.guowangkeji.top/Article/details/gtebmwygsf.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yangfankeji.com/Article/details/gtefnxylnq.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xinyue.icu/Article/details/gtfqbslyif.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.cashguo.top/Article/details/gtjmhjqofs.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.meibo888.top/Article/details/gtyqrxoltn.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.fzhhl.top/Article/details/gthdsktoyl.html

[E19] 多行文本按行拆分
来源：http://dali.hfpthk.cn/Article/details/gtdrhyhsxp.html

Py:   s.splitlines()
来源：http://dali.cheryme.top/Article/details/gtpviwkjka.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.cdnleiting.top/Article/details/gtpnagqidc.html

JS:   s.split(/\r?\n/)
来源：http://dali.yvedp.cn/Article/details/gtbbbxnyaz.html

TS:   s.split(/\r?\n/)
来源：http://dali.sysykeji.top/Article/details/gthwcqmwex.html

Java: s.lines().toList()
来源：http://dali.hywenlv.cn/Article/details/gtzmwzjses.html

Go:   strings.Split(s, "\n")
来源：http://dali.fengsongda.top/Article/details/gtexqhbrfr.html

Ruby: s.lines
来源：http://dali.jianghu66.top/Article/details/gtotrzlbil.html

C#:   s.Split('\n')
来源：http://dali.dashuyun.cn/Article/details/gtjbsagnpe.html

[E20] 判断字符串是否为空
来源：http://dali.bjfxy.top/Article/details/gtkaazzrin.html

Py:   if not s:
来源：http://dali.jlsjyb.cn/Article/details/gtjchzsgiy.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.chenjidiqi.icu/Article/details/gtsdoitmbe.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yonumen.top/Article/details/gtjliurbua.html

TS:   if (s === "") {}
来源：http://dali.wangshuangyany.cn/Article/details/gtbprkmfea.html

Java: if (s.isEmpty()) {}
来源：http://dali.daxiang520.top/Article/details/gtokwyjylt.html

Go:   if s == "" {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmqonuzwy.html

Ruby: if s.empty?
来源：http://dali.hnxiangtu.top/Article/details/gtsprqmgde.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtiqcwfang.html

[E21] 超长截断加省略号
来源：http://dali.nwbrower.top/Article/details/gtcysnddkp.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.vqdsnc.cn/Article/details/gtptggapon.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yangfankeji.com/Article/details/gtjxjazulu.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xinyue.icu/Article/details/gtvnzchabt.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hnxiangtu.top/Article/details/gtjbqkbser.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.cdnleiting.top/Article/details/gtfchmskna.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.quarkkingdee.top/Article/details/gtjgwikzum.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.meibo888.top/Article/details/gtwykjnuay.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.xziqi.cn/Article/details/gtdykhfmny.html

[E22] 字节长度与字符长度
来源：http://dali.zycfv.cn/Article/details/gtangdiers.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.mhx1999.top/Article/details/gtwkjlpubk.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gthjddzjfq.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xinyue.icu/Article/details/gtzqiiiqlv.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xinyue.icu/Article/details/gtxmjxqdve.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.feifeiyinyue.top/Article/details/gtizcxjygb.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yvedp.cn/Article/details/gtnyfyhqjx.html

Ruby: s.bytesize;  s.length
来源：http://dali.shzxlz.cn/Article/details/gtxlauomjq.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yj20258.top/Article/details/gtcvnstrqj.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtwfhtkkva.html

F. 文件与目录
来源：http://dali.zdqjudy.top/Article/details/gtybykrlko.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtuhrwosyc.html

[F01] 读取整个文件
来源：http://dali.jqgfzy.top/Article/details/gthjiugrzz.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.tianlin.xyz/Article/details/gtmdpdutel.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gtbjtanaew.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.birdmap.top/Article/details/gthgaerfcy.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.vqdsnc.cn/Article/details/gttudfvtzs.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.pengpengdd.cyou/Article/details/gtiougvynd.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.shangyingyoupin.top/Article/details/gtclaefvsm.html

Ruby: File.read("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gteszvdrno.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gttjupgrjq.html

[F02] 逐行读取文件
来源：http://dali.cheryme.top/Article/details/gtlxkdnqsa.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhengqikj.top/Article/details/gtynqdjazs.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.birdmap.top/Article/details/gtbnzlfzaz.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ehwqpu.com/Article/details/gtiskhvfqn.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj202588.top/Article/details/gtuvxlwdrx.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.quarkkingdee.top/Article/details/gtmclbmcoh.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.shanyushiyangtech.top/Article/details/gtxoxyhfzr.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.tanke756.top/Article/details/gtcqpflxxn.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.cucudq.cn/Article/details/gteqzhqbjx.html

[F03] 写入文件（覆盖）
来源：http://dali.xuetiantiany.cn/Article/details/gtektxdmom.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.bjfxy.top/Article/details/gtcjmkjsmf.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jlsjyb.cn/Article/details/gtisckvfmk.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hnqzz.top/Article/details/gtwehqtezb.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.bjfxy.top/Article/details/gtnrdmnalg.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yangfankeji.com/Article/details/gttyjciepo.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.nwbrower.top/Article/details/gtyisejpdu.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.gzhubu.top/Article/details/gtbdqukplq.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqkorxwzj.html

[F04] 追加写入文件
来源：http://dali.guowangkeji.top/Article/details/gtqkchikjk.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.tian-w.cn/Article/details/gtrsqjyqpa.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhiwuduotai.top/Article/details/gtarmmhgui.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ivvv.top/Article/details/gtkeojhcao.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.guowangkeji.top/Article/details/gtcyrwmyyl.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhoulong.xyz/Article/details/gtjxsuwvfp.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.gaohongyu789.top/Article/details/gtpjxzpokg.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.sxryk.cn/Article/details/gtcrcqaohs.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.9152youxi.cn/Article/details/gtohdtkgzg.html

[F05] 判断文件或目录是否存在
来源：http://dali.feifeiyinyue.top/Article/details/gtgyxhhvzy.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jinghuilouyu.cn/Article/details/gtnuomkbzw.html

PHP:  file_exists("a.txt");
来源：http://dali.redwolf501.top/Article/details/gtavovemxj.html

JS:   fs.existsSync("a.txt")
来源：http://dali.tian-w.cn/Article/details/gthrccqewj.html

TS:   fs.existsSync("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtefsuhbfn.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.316326.xyz/Article/details/gtsldjowmd.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhixingplan.top/Article/details/gtbtjreqxn.html

Ruby: File.exist?("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtqtmbvlvc.html

C#:   File.Exists("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtdvmwosfk.html

[F06] 删除文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqbfuunwz.html

Py:   os.remove("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtouokywnx.html

PHP:  unlink("a.txt");
来源：http://dali.havefunace.top/Article/details/gtpblbceai.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.ivvv.top/Article/details/gthifidpgu.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ivvv.top/Article/details/gtcebjbygc.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jinghuilouyu.cn/Article/details/gthrzzlniu.html

Go:   os.Remove("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtxxluqkwn.html

Ruby: File.delete("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtixuhiswp.html

C#:   File.Delete("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpdnhrchb.html

[F07] 创建目录（含多级）
来源：http://dali.xuanzx.com/Article/details/gtfhojqsdv.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.vqdsnc.cn/Article/details/gtlhotkejh.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.quarkkingdee.top/Article/details/gtwvitotvn.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nwbrower.top/Article/details/gtrvjuosxc.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.dashuyun.cn/Article/details/gtrypvplfh.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.9152youxi.cn/Article/details/gtlhlrblqs.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.daxiang520.top/Article/details/gtmcbpivjm.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.pengpengdd.cyou/Article/details/gttfcznoeh.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jiagoushi.top/Article/details/gtwkrmhlut.html

[F08] 遍历目录
来源：http://dali.nwbrower.top/Article/details/gtftnqkgoz.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.chenlongwang.top/Article/details/gtrptvuqgx.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.aibaodan.cn/Article/details/gtkpvocobp.html

JS:   fs.readdirSync("dir")
来源：http://dali.jqgfzy.top/Article/details/gtenlevaud.html

TS:   fs.readdirSync("dir")
来源：http://dali.hongshengwenyu.top/Article/details/gtpwdubjuh.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.0kj1m.cn/Article/details/gtksxhogth.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gtafasilvl.html

Ruby: Dir.children("dir")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyikfxvmh.html

C#:   Directory.GetFiles("dir")
来源：http://dali.vqdsnc.cn/Article/details/gteouqfryd.html

[F09] 获取文件大小
来源：http://dali.c1oappe.top/Article/details/gtwrxedsfe.html

Py:   os.path.getsize("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtsxxyygqm.html

PHP:  filesize("a.txt");
来源：http://dali.tanke756.top/Article/details/gtsmlyyira.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hnxiangtu.top/Article/details/gtxfmxcyhs.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlbkqlwng.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hammf.cn/Article/details/gtwavcikwx.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.guowangkeji.top/Article/details/gtmouevept.html

Ruby: File.size("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtjkogcfkz.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.gaohongyu789.top/Article/details/gtgkbvtcyh.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.tanke756.top/Article/details/gtvvpzncvm.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.c1oappe.top/Article/details/gtjqpmbwri.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.nwbrower.top/Article/details/gtwzbhblhg.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.ivvv.top/Article/details/gtvnvtxdef.html

TS:   path.extname("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtycjvyogm.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjrtweahp.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yuxming.cn/Article/details/gtaetirfkq.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtywltvwsx.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.gzhubu.top/Article/details/gtmkymmtlo.html

[F11] 复制与移动文件
来源：http://dali.chenzaomai.com/Article/details/gteghpabue.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yj20258.top/Article/details/gtmerrqgtp.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.redwolf501.top/Article/details/gtfvamhxzw.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gthtcfbwba.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.tianlin.xyz/Article/details/gtilgiehir.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.fzhhl.top/Article/details/gtxinmecht.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.9152youxi.cn/Article/details/gtbfqnvnaw.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.sxryk.cn/Article/details/gtrkmwzoza.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.snrcjt.cn/Article/details/gtzdssqdqy.html

[F12] CSV 读写
来源：http://dali.daxiang520.top/Article/details/gtwuihtlde.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.pycfn.com/Article/details/gtbdjdyukg.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xziqi.cn/Article/details/gtddtdulea.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhixingplan.top/Article/details/gtamqcbtxg.html

TS:   // 同上
来源：http://dali.nwbrower.top/Article/details/gttbmlzfvl.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.quarkkingdee.top/Article/details/gtlhuezzrr.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.cheryme.top/Article/details/gtfmzaoyod.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xinyue.icu/Article/details/gtwslizosv.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhixingplan.top/Article/details/gthiuqmogx.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtvysnmnrt.html

G. 面向对象
来源：http://dali.0kj1m.cn/Article/details/gtvplzdzeb.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gthxqonvcs.html

[G01] 定义类
来源：http://dali.jyoumei.cn/Article/details/gtrycrmnji.html

Py:   class User: pass
来源：http://dali.sxryk.cn/Article/details/gtwktqztcw.html

PHP:  class User {}
来源：http://dali.tanke756.top/Article/details/gtolsgrpwx.html

JS:   class User {}
来源：http://dali.shzxlz.cn/Article/details/gttlgeonip.html

TS:   class User { name: string = ""; }
来源：http://dali.sysykeji.top/Article/details/gtshkzruma.html

Java: class User {}
来源：http://dali.yanxiufei.cn/Article/details/gtxljygnyr.html

Go:   type User struct { Name string }
来源：http://dali.jqgfzy.top/Article/details/gtviqsakia.html

Ruby: class User; end
来源：http://dali.cheryme.top/Article/details/gtafnkuoxc.html

C#:   class User {}
来源：http://dali.yj20258.top/Article/details/gtzvasdkdi.html

[G02] 构造函数
来源：http://dali.gogol.net.cn/Article/details/gtzoqxduti.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yj20258.top/Article/details/gtsjjkrypa.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yj20258888.top/Article/details/gtkmormltx.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.shzxlz.cn/Article/details/gteqefeqpa.html

TS:   constructor(public name: string) {}
来源：http://dali.dianchejie.cn/Article/details/gtirxucybr.html

Java: User(String name) { this.name = name; }
来源：http://dali.snrcjt.cn/Article/details/gtnaxzdgwr.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.c1oappe.top/Article/details/gtpxdpyqsa.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yj20258.top/Article/details/gtwtaozlqz.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jlsjyb.cn/Article/details/gtxceqjjeg.html

[G03] 实例属性
来源：http://dali.pengpengdd.cyou/Article/details/gtamfaaywf.html

Py:   self.name = "x"
来源：http://dali.hysaishi.cn/Article/details/gtdnutuddw.html

PHP:  public string $name = "x";
来源：http://dali.jyoumei.cn/Article/details/gtwkulvciw.html

JS:   this.name = "x";
来源：http://dali.yangfankeji.com/Article/details/gtqhhomrsn.html

TS:   name: string = "x";
来源：http://dali.cashguo.top/Article/details/gtzfgcdlmv.html

Java: private String name;
来源：http://dali.hnxiangtu.top/Article/details/gtctnynxht.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cdnleiting.top/Article/details/gtncwjkftu.html

Ruby: @name = "x"
来源：http://dali.316326.xyz/Article/details/gtwkhznpdj.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yueranfly.top/Article/details/gttslnutbe.html

[G04] 定义方法
来源：http://dali.yanxiufei.cn/Article/details/gtlkgsuffg.html

Py:   def greet(self): return self.name
来源：http://dali.pycfn.com/Article/details/gtdvavrhvb.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.gogol.net.cn/Article/details/gtuwxseohu.html

JS:   greet() { return this.name; }
来源：http://dali.jqgufenzy.top/Article/details/gthaqirtrv.html

TS:   greet(): string { return this.name; }
来源：http://dali.fengsongda.top/Article/details/gtoyztikgn.html

Java: String greet() { return name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtaassrwep.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiwlhqbqa.html

Ruby: def greet; @name; end
来源：http://dali.chenlongwang.top/Article/details/gtoeaptxgi.html

C#:   public string Greet() => Name;
来源：http://dali.tian-w.cn/Article/details/gtyndzcbac.html

[G05] 继承
来源：http://dali.xuanzx.com/Article/details/gtevsfmlrw.html

Py:   class Admin(User): pass
来源：http://dali.fengsongda.top/Article/details/gtfwkhczul.html

PHP:  class Admin extends User {}
来源：http://dali.tianlin.xyz/Article/details/gtaicbzaxb.html

JS:   class Admin extends User {}
来源：http://dali.nwbrower.top/Article/details/gtadrwnlkq.html

TS:   class Admin extends User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtgimzyagw.html

Java: class Admin extends User {}
来源：http://dali.jqgfzy.top/Article/details/gtqyifzcbg.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jlsjyb.cn/Article/details/gtbwsfqosc.html

Ruby: class Admin < User; end
来源：http://dali.hysaishi.cn/Article/details/gthjfvcegw.html

C#:   class Admin : User {}
来源：http://dali.sysykeji.top/Article/details/gtbtmysikl.html

[G06] 重写方法
来源：http://dali.yueranfly.top/Article/details/gthjwnfiob.html

Py:   def greet(self): return "admin"
来源：http://dali.9152youxi.cn/Article/details/gtprkjnmag.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtqyyitgvt.html

JS:   greet() { return "admin"; }
来源：http://dali.mhx1999.top/Article/details/gtlvurtyxt.html

TS:   greet(): string { return "admin"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtmteotuqo.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtarldywhj.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ivvv.top/Article/details/gtryuwslcw.html

Ruby: def greet; "admin"; end
来源：http://dali.smart0.xyz/Article/details/gtktbyifsr.html

C#:   public override string Greet() => "admin";
来源：http://dali.yongpay.top/Article/details/gtrwbpmnrx.html

[G07] 调用父类方法
来源：http://dali.quarkkingdee.top/Article/details/gtvgffdptt.html

Py:   super().greet()
来源：http://dali.316326.xyz/Article/details/gtqcfdburj.html

PHP:  parent::greet();
来源：http://dali.guowangkeji.top/Article/details/gtrhjnrpjo.html

JS:   super.greet();
来源：http://dali.hywenlv.cn/Article/details/gtgyrhvsrq.html

TS:   super.greet();
来源：http://dali.tianlin.xyz/Article/details/gtgjjtqcig.html

Java: super.greet();
来源：http://dali.dashuyun.cn/Article/details/gtrbqweyhu.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zycfv.cn/Article/details/gtqwkglrtr.html

Ruby: super
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwoefqile.html

C#:   base.Greet();
来源：http://dali.316326.xyz/Article/details/gtppnitbxw.html

[G08] 静态方法与属性
来源：http://dali.daria6918.cn/Article/details/gtzbkynpgg.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.guannengcc.top/Article/details/gtpvemwbym.html


<!-- 参考信息 -->