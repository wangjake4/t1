代发 wailian999

JS:   [...s].reverse().join("")
来源：http://dali.kuanghao11.cn/Article/details/gtekjwrhxh.html

TS:   [...s].reverse().join("")
来源：http://dali.zhixingplan.top/Article/details/gtfezrchac.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jqgufenzy.top/Article/details/gtaquwkluo.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhiwuduotai.top/Article/details/gtajqhurva.html

Ruby: s.reverse
来源：http://dali.aizwys.cn/Article/details/gtbewkxvhd.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.ybcxt.top/Article/details/gtjbwpbxnb.html

[E12] 统计某字符出现次数
来源：http://dali.zhoulong.xyz/Article/details/gtsvptrxih.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gtwgwsxhvd.html

PHP:  substr_count($s, "a");
来源：http://dali.jinqigfzy.top/Article/details/gtmahlodjx.html

JS:   s.split("a").length - 1
来源：http://dali.svipenyu.cn/Article/details/gtkbfjpyqj.html

TS:   s.split("a").length - 1
来源：http://dali.yuxming.cn/Article/details/gtqkukrlpx.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.nwbrower.top/Article/details/gtqsglwwwa.html

Go:   strings.Count(s, "a")
来源：http://dali.jiagoushi.top/Article/details/gtrwwbhwut.html

Ruby: s.count("a")
来源：http://dali.chenzaomai.com/Article/details/gtbumztdsf.html

C#:   s.Count(c => c == 'a')
来源：http://dali.hongshengwenyu.top/Article/details/gtcgnbberl.html

[E13] 逐字符遍历
来源：http://dali.dianchejie.cn/Article/details/gttlyxsrym.html

Py:   for ch in s: print(ch)
来源：http://dali.ehwqpu.com/Article/details/gtmuxgvgyb.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.gotoacloud.top/Article/details/gtvlanfpbx.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hnxiangtu.top/Article/details/gttxpsgtho.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ppjwa.cn/Article/details/gtdapxbigp.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.0kj1m.cn/Article/details/gtqlhhlygx.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.xuetiantiany.cn/Article/details/gtkovbkvxr.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.ivvv.top/Article/details/gtgrakmkui.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.xziqi.cn/Article/details/gtwekdpfnc.html

[E14] URL 编码与 Base64
来源：http://dali.quarkkingdee.top/Article/details/gtzuwfbdhk.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.ppjwa.cn/Article/details/gtuvootght.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.dianchejie.cn/Article/details/gtnffgvshy.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hongshengwenyu.top/Article/details/gtefaoislp.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yongpay.top/Article/details/gtjiioklgx.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.tian-w.cn/Article/details/gtapocryuq.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.bjfxy.top/Article/details/gtayvguznx.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqzwuultz.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjmwokynr.html

[E15] HTML 转义 / 反转义
来源：http://dali.aizwys.cn/Article/details/gtkocgaofq.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.hammf.cn/Article/details/gtjbvqeksn.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yongpay.top/Article/details/gtocmcgszz.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.bjfxy.top/Article/details/gtyxftybhz.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.xinyue.icu/Article/details/gtxlosufpv.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhoulong.xyz/Article/details/gtemstfqru.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zdqjudy.top/Article/details/gtwcicjryg.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.pycfn.com/Article/details/gtvugougzn.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.gotoacloud.top/Article/details/gtcmezuywd.html

[E16] 数字千分位
来源：http://dali.hysaishi.cn/Article/details/gtxoxmjwbx.html

Py:   f"{1234567:,}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtskuesjit.html

PHP:  number_format(1234567);
来源：http://dali.cdnleiting.top/Article/details/gtizkoiibx.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.xziqi.cn/Article/details/gtsnywlqxf.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.ehwqpu.com/Article/details/gtexafyzxf.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yanxiufei.cn/Article/details/gtndzkduwz.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.fzhhl.top/Article/details/gtgoqfbztr.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhongyouzk.top/Article/details/gtzpgsapvy.html

C#:   1234567.ToString("N0")
来源：http://dali.tian-w.cn/Article/details/gttafdpexg.html

[E17] 首字母大写
来源：http://dali.yonumen.top/Article/details/gtkgrbftpc.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.chenzaomai.com/Article/details/gtgdjhmiba.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hammf.cn/Article/details/gtdkalwykm.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xylfe.cn/Article/details/gtfovuuyla.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shzxlz.cn/Article/details/gtmkwkfofk.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtkbnwmjgr.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jqgfzy.top/Article/details/gtdafdbegq.html

Ruby: s.capitalize
来源：http://dali.hywenlv.cn/Article/details/gttokzfrpz.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yvedp.cn/Article/details/gtisjveiqu.html

[E18] 模板占位符替换
来源：http://dali.jqgfzy.top/Article/details/gtxgzeiban.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.andypj.xyz/Article/details/gtxvmqfesw.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.ehwqpu.com/Article/details/gtrinsbrae.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zycfv.cn/Article/details/gtgflcwlhx.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhoulong.xyz/Article/details/gtreecbunm.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yj20258888.top/Article/details/gtrjbujaxw.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yangfankeji.com/Article/details/gtqrzykehw.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.smart0.xyz/Article/details/gtuioxfxah.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.ivvv.top/Article/details/gttqfevjem.html

[E19] 多行文本按行拆分
来源：http://dali.daria6918.cn/Article/details/gttrppnsra.html

Py:   s.splitlines()
来源：http://dali.316326.xyz/Article/details/gtlalwnghy.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jlsjyb.cn/Article/details/gtozljvltq.html

JS:   s.split(/\r?\n/)
来源：http://dali.xziqi.cn/Article/details/gtkpigobql.html

TS:   s.split(/\r?\n/)
来源：http://dali.sweek.top/Article/details/gtgaoyrcpi.html

Java: s.lines().toList()
来源：http://dali.cqqwz.cn/Article/details/gteebwjkxz.html

Go:   strings.Split(s, "\n")
来源：http://dali.birdmap.top/Article/details/gtfwbgbudb.html

Ruby: s.lines
来源：http://dali.cheryme.top/Article/details/gtngnkzueb.html

C#:   s.Split('\n')
来源：http://dali.feifeiyinyue.top/Article/details/gtdxfbxoal.html

[E20] 判断字符串是否为空
来源：http://dali.jinqigfzy.top/Article/details/gtqcntphhy.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gtefhezrei.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gtuuuqpzoy.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.gotoacloud.top/Article/details/gtoevjmwzl.html

TS:   if (s === "") {}
来源：http://dali.0kj1m.cn/Article/details/gtjrsrjsuc.html

Java: if (s.isEmpty()) {}
来源：http://dali.cdnleiting.top/Article/details/gtaekrdbam.html

Go:   if s == "" {}
来源：http://dali.cheryme.top/Article/details/gtzxlxysve.html

Ruby: if s.empty?
来源：http://dali.mhx1999.top/Article/details/gtssxtwcsa.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.aibaodan.cn/Article/details/gtkwmagmhl.html

[E21] 超长截断加省略号
来源：http://dali.wangshuangyany.cn/Article/details/gtrxtglxjv.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.ybcxt.top/Article/details/gtmqquqzbm.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.mhx1999.top/Article/details/gtybmdrvii.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hammf.cn/Article/details/gtizotiucs.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zdqjudy.top/Article/details/gtrjfzyyui.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ywan-chungtsiang.top/Article/details/gtokjhrrcv.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.snrcjt.cn/Article/details/gtoehddlrd.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.shangyingyoupin.top/Article/details/gtudsplofk.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hongshengwenyu.top/Article/details/gtygkjglhj.html

[E22] 字节长度与字符长度
来源：http://dali.yuanzhike.top/Article/details/gtcrgqkiia.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmngnbqoc.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cqqwz.cn/Article/details/gttgmtctlb.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.daxiang520.top/Article/details/gttqitbwzg.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yj20258888.top/Article/details/gtfwztdhjp.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xuetiantiany.cn/Article/details/gtsrfvsdzl.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.mhx1999.top/Article/details/gtpdqynrvk.html

Ruby: s.bytesize;  s.length
来源：http://dali.jinqigufen.top/Article/details/gtgwzlnmar.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.0kj1m.cn/Article/details/gtjiqvtrlm.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtprwqaihu.html

F. 文件与目录
来源：http://dali.yvedp.cn/Article/details/gtvikeghyu.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gttugsbyub.html

[F01] 读取整个文件
来源：http://dali.quarkkingdee.top/Article/details/gtvdswrhyc.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.chenjidiqi.icu/Article/details/gtmeydexcg.html

PHP:  file_get_contents("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gtcexrsuvo.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.nanxinkj.top/Article/details/gtdelyfrem.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hfpthk.cn/Article/details/gtrbrfolay.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.dianchejie.cn/Article/details/gtfffzbieo.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.havefunace.top/Article/details/gtupglvqwd.html

Ruby: File.read("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtzvbszzxh.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtutmspvva.html

[F02] 逐行读取文件
来源：http://dali.hysaishi.cn/Article/details/gthfqljfsw.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.redwolf501.top/Article/details/gtgzcgewnc.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.fzhhl.top/Article/details/gtkwikpdev.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj20258.top/Article/details/gtnpndxnob.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hfpthk.cn/Article/details/gtygfkbieq.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hnxiangtu.top/Article/details/gtzluvyjds.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jqgfzy.top/Article/details/gtciqgzsrt.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hywenlv.cn/Article/details/gtepbidrwp.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hnqzz.top/Article/details/gtlfrznxly.html

[F03] 写入文件（覆盖）
来源：http://dali.ydzc1.top/Article/details/gtiqpdnxnd.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.snrcjt.cn/Article/details/gtuwowyvxs.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.guowangkeji.top/Article/details/gtuncrrevg.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.birdmap.top/Article/details/gtqdzrgqmu.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gogol.net.cn/Article/details/gtpgcjboxx.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.cheryme.top/Article/details/gtyruwbxpn.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gtbmijxqde.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.dianchejie.cn/Article/details/gtqoxnzcri.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.shuidangran.top/Article/details/gtyjscskfu.html

[F04] 追加写入文件
来源：http://dali.nanxinkj.top/Article/details/gtfphvzuea.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.guannengcc.top/Article/details/gtytorcgjs.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.chenzaomai.com/Article/details/gtrtmyeupf.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbwyynivb.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.chenlongwang.top/Article/details/gtxhshxfdw.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.tanke756.top/Article/details/gtjjuapqno.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yuanzhike.top/Article/details/gtqaznslnc.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkiiulwdh.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.wangdashe.top/Article/details/gtimuhwogc.html

[F05] 判断文件或目录是否存在
来源：http://dali.havefunace.top/Article/details/gtgrfckyva.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.gotoacloud.top/Article/details/gtqmlutexa.html

PHP:  file_exists("a.txt");
来源：http://dali.smart0.xyz/Article/details/gtifutrefm.html

JS:   fs.existsSync("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtbpikrrnv.html

TS:   fs.existsSync("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtnrhrntkr.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.316326.xyz/Article/details/gtbzbttyoh.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.wangshuangyany.cn/Article/details/gtkefjhplv.html

Ruby: File.exist?("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtfxorhbzy.html

C#:   File.Exists("a.txt")
来源：http://dali.yongpay.top/Article/details/gtrvvklmta.html

[F06] 删除文件
来源：http://dali.nanxuanxn.top/Article/details/gtlmleraph.html

Py:   os.remove("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtzgbtojei.html

PHP:  unlink("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtqbmsmdns.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.tanke756.top/Article/details/gtdhqsyvfr.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ivvv.top/Article/details/gtvpbyugef.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.feifeiyinyue.top/Article/details/gtheykyipj.html

Go:   os.Remove("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtjkbeudux.html

Ruby: File.delete("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtknndjarf.html

C#:   File.Delete("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gtscqrtxgt.html

[F07] 创建目录（含多级）
来源：http://dali.xinyue.icu/Article/details/gtukrxoodb.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.sysykeji.top/Article/details/gtpcsafgfu.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.cqqwz.cn/Article/details/gtcitecggv.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinqigfzy.top/Article/details/gtgzwnlbjz.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.haohaochexian.top/Article/details/gtywwxmaev.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zycfv.cn/Article/details/gtaqpdjjre.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xinyue.icu/Article/details/gtfiqwockl.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.iojbl.cn/Article/details/gtbviiqjrc.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.cashguo.top/Article/details/gtqimvszar.html

[F08] 遍历目录
来源：http://dali.jlsjyb.cn/Article/details/gtbiexbron.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.guannengcc.top/Article/details/gtqhejblys.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.vqdsnc.cn/Article/details/gtkvieasmk.html

JS:   fs.readdirSync("dir")
来源：http://dali.shzxlz.cn/Article/details/gtiafqdszn.html

TS:   fs.readdirSync("dir")
来源：http://dali.gotoacloud.top/Article/details/gtyjuweffd.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.wangshuangyany.cn/Article/details/gtnocigrfi.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhoulong.xyz/Article/details/gtjtuddbjk.html

Ruby: Dir.children("dir")
来源：http://dali.cheryme.top/Article/details/gtrwgfuyul.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfxpfcczh.html

[F09] 获取文件大小
来源：http://dali.yuanzhike.top/Article/details/gtpuifeyyg.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtmefpnrjp.html

PHP:  filesize("a.txt");
来源：http://dali.xziqi.cn/Article/details/gttgxrzdic.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yj20258888.top/Article/details/gtjaofmvzy.html

TS:   fs.statSync("a.txt").size
来源：http://dali.ppjwa.cn/Article/details/gtuhjrokgv.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cqqwz.cn/Article/details/gtaqgrymeo.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.aizwys.cn/Article/details/gtiajrpnlm.html

Ruby: File.size("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtcwhbduvs.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yueranfly.top/Article/details/gtlwehcfbf.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhengqikj.top/Article/details/gtqhlggxia.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.gogol.net.cn/Article/details/gttelvjawy.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.c1oappe.top/Article/details/gteyzfgnhl.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.tanke756.top/Article/details/gttzjdkdnr.html

TS:   path.extname("a.txt")
来源：http://dali.birdmap.top/Article/details/gtpjkhuuvz.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.iojbl.cn/Article/details/gtyuploylt.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtcgtlzrio.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gthlbfzlyc.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hammf.cn/Article/details/gtarehdggr.html

[F11] 复制与移动文件
来源：http://dali.yvedp.cn/Article/details/gtqerblizr.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yueranfly.top/Article/details/gttsqurort.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hammf.cn/Article/details/gttvnkbslb.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ehwqpu.com/Article/details/gtjuyczuul.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shuidangran.top/Article/details/gtwbudfkgo.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jqgufenzy.top/Article/details/gtfjrjdvai.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.cdnleiting.top/Article/details/gtzgpkulaq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yvedp.cn/Article/details/gtbokibjjs.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jinqigfzy.top/Article/details/gtwmveeeap.html

[F12] CSV 读写
来源：http://dali.hfpthk.cn/Article/details/gtebsqwclp.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yangfankeji.com/Article/details/gtprdworwj.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.tian-w.cn/Article/details/gtidpjaqgt.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xinyue.icu/Article/details/gtuphekxgp.html

TS:   // 同上
来源：http://dali.hywenlv.cn/Article/details/gtgxouszmz.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.sufxvd.cn/Article/details/gttghnqcuu.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hammf.cn/Article/details/gtrhdqbotq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.gotoacloud.top/Article/details/gtjjyzxghl.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.sysykeji.top/Article/details/gtngbfzjdv.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtxytsbsib.html

G. 面向对象
来源：http://dali.hnxiangtu.top/Article/details/gtwccryhtf.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtcezkyvhv.html

[G01] 定义类
来源：http://dali.shangyingyoupin.top/Article/details/gtdacczntf.html

Py:   class User: pass
来源：http://dali.hywenlv.cn/Article/details/gtqznthiia.html

PHP:  class User {}
来源：http://dali.shuidangran.top/Article/details/gtndueemau.html

JS:   class User {}
来源：http://dali.tian-w.cn/Article/details/gtcuwitlgp.html

TS:   class User { name: string = ""; }
来源：http://dali.bjfxy.top/Article/details/gttxrmcwwj.html

Java: class User {}
来源：http://dali.zhixingplan.top/Article/details/gtbospydda.html

Go:   type User struct { Name string }
来源：http://dali.hammf.cn/Article/details/gthmzqjnzg.html

Ruby: class User; end
来源：http://dali.tian-w.cn/Article/details/gtosamkxya.html

C#:   class User {}
来源：http://dali.gzhubu.top/Article/details/gtecsbncwo.html

[G02] 构造函数
来源：http://dali.fengsongda.top/Article/details/gtefjnqsai.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.ivvv.top/Article/details/gtyhowaysd.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpeenuvpf.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhoulong.xyz/Article/details/gtdoqpdhlp.html

TS:   constructor(public name: string) {}
来源：http://dali.hnxiangtu.top/Article/details/gtlogfpkgc.html

Java: User(String name) { this.name = name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtybzccxxz.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.shzxlz.cn/Article/details/gtlgkfolxx.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.nanxinkj.top/Article/details/gtqckiaxcp.html

C#:   public User(string name) { Name = name; }
来源：http://dali.quarkkingdee.top/Article/details/gtqopscdvk.html

[G03] 实例属性
来源：http://dali.daxiang520.top/Article/details/gtumusenyw.html

Py:   self.name = "x"
来源：http://dali.daxiang520.top/Article/details/gtvrlicqqz.html

PHP:  public string $name = "x";
来源：http://dali.c1oappe.top/Article/details/gtxzbomyzq.html

JS:   this.name = "x";
来源：http://dali.jinqigfzy.top/Article/details/gtghgfjywh.html

TS:   name: string = "x";
来源：http://dali.yj202588.top/Article/details/gthsadletr.html

Java: private String name;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtilhnpicb.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hnxiangtu.top/Article/details/gtzlhznkvd.html

Ruby: @name = "x"
来源：http://dali.mhx1999.top/Article/details/gtkxkztvew.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.tian-w.cn/Article/details/gtqciysqdn.html

[G04] 定义方法
来源：http://dali.chenzaomai.com/Article/details/gtdagdxcqj.html

Py:   def greet(self): return self.name
来源：http://dali.feifeiyinyue.top/Article/details/gtyqjaueon.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbszaijuf.html

JS:   greet() { return this.name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgbooiuni.html

TS:   greet(): string { return this.name; }
来源：http://dali.sufxvd.cn/Article/details/gtvnxbrrps.html

Java: String greet() { return name; }
来源：http://dali.sweek.top/Article/details/gtlxcjwtbv.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.iojbl.cn/Article/details/gtwrfggnkf.html

Ruby: def greet; @name; end
来源：http://dali.cashguo.top/Article/details/gtkcjcykjr.html

C#:   public string Greet() => Name;
来源：http://dali.pengpengdd.cyou/Article/details/gtaponfobk.html

[G05] 继承
来源：http://dali.nanxuanxn.top/Article/details/gtzgbowaic.html

Py:   class Admin(User): pass
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwkidoeoy.html

PHP:  class Admin extends User {}
来源：http://dali.hfpthk.cn/Article/details/gtvihyeevv.html

JS:   class Admin extends User {}
来源：http://dali.yanxiufei.cn/Article/details/gtuxbcbcqj.html

TS:   class Admin extends User {}
来源：http://dali.svipenyu.cn/Article/details/gtyulfvqsw.html

Java: class Admin extends User {}
来源：http://dali.yueranfly.top/Article/details/gtveisguau.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hnxiangtu.top/Article/details/gtecqaxqod.html

Ruby: class Admin < User; end
来源：http://dali.nanxinkj.top/Article/details/gtjxhqxwgb.html

C#:   class Admin : User {}
来源：http://dali.cucudq.cn/Article/details/gtuuiqyfzq.html

[G06] 重写方法
来源：http://dali.yvedp.cn/Article/details/gtvbwgdrqe.html

Py:   def greet(self): return "admin"
来源：http://dali.cdnleiting.top/Article/details/gtvyooglnb.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xziqi.cn/Article/details/gtzwugupjy.html

JS:   greet() { return "admin"; }
来源：http://dali.jinqigufen.top/Article/details/gtbhgariwu.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hnqzz.top/Article/details/gtvjoueugy.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.cheryme.top/Article/details/gtcubnmtfg.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.gogol.net.cn/Article/details/gtebseripo.html

Ruby: def greet; "admin"; end
来源：http://dali.tian-w.cn/Article/details/gtumkvidkw.html

C#:   public override string Greet() => "admin";
来源：http://dali.daxiang520.top/Article/details/gtuivqrxgt.html

[G07] 调用父类方法
来源：http://dali.jianghu66.top/Article/details/gtsvjytjtf.html

Py:   super().greet()
来源：http://dali.hywenlv.cn/Article/details/gtivbegfbk.html

PHP:  parent::greet();
来源：http://dali.vqdsnc.cn/Article/details/gtvhggycns.html

JS:   super.greet();
来源：http://dali.sufxvd.cn/Article/details/gtnemlhwbb.html

TS:   super.greet();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdeotbyvi.html

Java: super.greet();
来源：http://dali.guowangkeji.top/Article/details/gtfowhsqpl.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yangfankeji.com/Article/details/gtlnhoqpwo.html

Ruby: super
来源：http://dali.yueranfly.top/Article/details/gtjjjraobu.html

C#:   base.Greet();
来源：http://dali.zdqjudy.top/Article/details/gtsocwwjcq.html

[G08] 静态方法与属性
来源：http://dali.cqqwz.cn/Article/details/gtkmyyypgc.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.vqdsnc.cn/Article/details/gtlsavsgmv.html

PHP:  public static function f() {}
来源：http://dali.shuidangran.top/Article/details/gtflwcdwwr.html

JS:   static f() {}
来源：http://dali.gaohongyu789.top/Article/details/gtabnrvmlh.html

TS:   static f(): void {}
来源：http://dali.cdnleiting.top/Article/details/gtegyjmfcg.html

Java: static void f() {}
来源：http://dali.9152youxi.cn/Article/details/gtwnxizgay.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.bjfxy.top/Article/details/gtrmeytypo.html

Ruby: def self.f; end
来源：http://dali.pycfn.com/Article/details/gtbjwobody.html

C#:   public static void F() {}
来源：http://dali.0kj1m.cn/Article/details/gtjjesxqvi.html

[G09] 接口 / 抽象类
来源：http://dali.0kj1m.cn/Article/details/gtocaurylf.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ydzc1.top/Article/details/gtltxhekii.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hfpthk.cn/Article/details/gtbxvmyryc.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.9152youxi.cn/Article/details/gtdnzozgxx.html

TS:   interface Shape { area(): number; }
来源：http://dali.ehwqpu.com/Article/details/gtnvxdizyb.html

Java: interface Shape { double area(); }
来源：http://dali.zdqjudy.top/Article/details/gtbrfzcrvi.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.daria6918.cn/Article/details/gtbeombejp.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xinyue.icu/Article/details/gtehnsehsw.html

C#:   interface IShape { double Area(); }
来源：http://dali.xinyue.icu/Article/details/gtqytsnzup.html


<!-- 参考信息 -->