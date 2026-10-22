代发 wailian999

Go:   strings.Join(items, ",")
来源：http://dali.hammf.cn/Article/details/gt2lonfrcog.html

Ruby: items.join(",")
来源：http://dali.daxiang520.top/Article/details/gt2ozkrsuco.html

C#:   string.Join(",", items)
来源：http://dali.vqdsnc.cn/Article/details/gt2zcsssthb.html

[E09] 去除所有空白字符
来源：http://dali.shzxlz.cn/Article/details/gt2qcebpkfm.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yj20258888.top/Article/details/gt2lrpndnap.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.daria6918.cn/Article/details/gt2cbmencua.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.xylfe.cn/Article/details/gt2vheynmfo.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.gotoacloud.top/Article/details/gt2xmoyqyse.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vqqzivkp.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.haohaochexian.top/Article/details/gt2cbmlukln.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.vqdsnc.cn/Article/details/gt2lrjpuspt.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yj20258888.top/Article/details/gt2hrdjugdm.html

[E10] 左侧补零 / 定长填充
来源：http://dali.birdmap.top/Article/details/gt2dbncvpic.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.quarkkingdee.top/Article/details/gt2mokzokgi.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.cdnleiting.top/Article/details/gt2frhswiri.html

JS:   "7".padStart(3, "0")
来源：http://dali.aizwys.cn/Article/details/gt2kwpobvhi.html

TS:   "7".padStart(3, "0")
来源：http://dali.hfpthk.cn/Article/details/gt2fwxdsuhz.html

Java: String.format("%03d", 7)
来源：http://dali.aizwys.cn/Article/details/gt2qlcqxrhc.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.aibaodan.cn/Article/details/gt2uztkmzxa.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.quarkkingdee.top/Article/details/gt2marvexjr.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.sweek.top/Article/details/gt2uvobkxvc.html

[E11] 反转字符串
来源：http://dali.jianghu66.top/Article/details/gt2gfejjxtu.html

Py:   s[::-1]
来源：http://dali.c1oappe.top/Article/details/gt2aleiqflo.html

PHP:  strrev($s);
来源：http://dali.chenjidiqi.icu/Article/details/gt2sbmemkap.html

JS:   [...s].reverse().join("")
来源：http://dali.guannengcc.top/Article/details/gt2bbkbuncy.html

TS:   [...s].reverse().join("")
来源：http://dali.meibo888.top/Article/details/gt2wershuiu.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.guowangkeji.top/Article/details/gt2mhyxpfgu.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yj20258888.top/Article/details/gt2olyajtlf.html

Ruby: s.reverse
来源：http://dali.redwolf501.top/Article/details/gt2hzwwyuva.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.dianchejie.cn/Article/details/gt2fcrlzgif.html

[E12] 统计某字符出现次数
来源：http://dali.gogol.net.cn/Article/details/gt2xjovphts.html

Py:   s.count("a")
来源：http://dali.pengpengdd.cyou/Article/details/gt2vpthgsac.html

PHP:  substr_count($s, "a");
来源：http://dali.wangshuangyany.cn/Article/details/gt2bmcichzk.html

JS:   s.split("a").length - 1
来源：http://dali.tian-w.cn/Article/details/gt2vnhhiqwl.html

TS:   s.split("a").length - 1
来源：http://dali.ybcxt.top/Article/details/gt2qvhilzir.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.chenzaomai.com/Article/details/gt2oxkdgvoa.html

Go:   strings.Count(s, "a")
来源：http://dali.hfpthk.cn/Article/details/gt2jonhgweo.html

Ruby: s.count("a")
来源：http://dali.cheryme.top/Article/details/gt2sorscbwp.html

C#:   s.Count(c => c == 'a')
来源：http://dali.sufxvd.cn/Article/details/gt2kjbyzewg.html

[E13] 逐字符遍历
来源：http://dali.jlsjyb.cn/Article/details/gt2jnkrayhg.html

Py:   for ch in s: print(ch)
来源：http://dali.feifeiyinyue.top/Article/details/gt2tgjpoxar.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.fengsongda.top/Article/details/gt2tozuyzft.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shzxlz.cn/Article/details/gt2srjlbqnl.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.chenzaomai.com/Article/details/gt2dmbnzyka.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yangfankeji.com/Article/details/gt2vpeiraqu.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.xuetiantiany.cn/Article/details/gt2tfufrtra.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhoulong.xyz/Article/details/gt2tjlvgrnl.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jyoumei.cn/Article/details/gt2vtyghgyp.html

[E14] URL 编码与 Base64
来源：http://dali.guannengcc.top/Article/details/gt2afwxbflr.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.cdnleiting.top/Article/details/gt2twvtltse.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jiagoushi.top/Article/details/gt2gqsjkvwj.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.smart0.xyz/Article/details/gt2xqsfidde.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgxzjvxa.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.redwolf501.top/Article/details/gt2hrnsbtnh.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.ehwqpu.com/Article/details/gt2jysywpkx.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jiagoushi.top/Article/details/gt2kwhoabzb.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jyoumei.cn/Article/details/gt2ntfllcdr.html

[E15] HTML 转义 / 反转义
来源：http://dali.jinqigfzy.top/Article/details/gt2icgudknq.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2novgynnq.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.wangshuangyany.cn/Article/details/gt2zeyoziah.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.cucudq.cn/Article/details/gt2hanotvea.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yj20258888.top/Article/details/gt2mekkzpks.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.aizwys.cn/Article/details/gt2dxqruwie.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2pkkzplre.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jinqigufen.top/Article/details/gt2whvvllsf.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2jnpskobu.html

[E16] 数字千分位
来源：http://dali.cucudq.cn/Article/details/gt2hbajzdzc.html

Py:   f"{1234567:,}"
来源：http://dali.chenjidiqi.icu/Article/details/gt2vlacawew.html

PHP:  number_format(1234567);
来源：http://dali.tianlin.xyz/Article/details/gt2accyikrx.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jiagoushi.top/Article/details/gt2kvplihir.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.chenjidiqi.icu/Article/details/gt2ltgehyop.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhengqikj.top/Article/details/gt2awzwoaqz.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.havefunace.top/Article/details/gt2irbbbmiw.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vygpkegf.html

C#:   1234567.ToString("N0")
来源：http://dali.jlsjyb.cn/Article/details/gt2kpkcsnxz.html

[E17] 首字母大写
来源：http://dali.smart0.xyz/Article/details/gt2ufsaosdh.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.iojbl.cn/Article/details/gt2ijhrjgyc.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.gogol.net.cn/Article/details/gt2tpigyfju.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.9152youxi.cn/Article/details/gt2jlnehguc.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jlsjyb.cn/Article/details/gt2muqqxajw.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zdqjudy.top/Article/details/gt2kojpbhrf.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yanxiufei.cn/Article/details/gt2svaufybm.html

Ruby: s.capitalize
来源：http://dali.shzxlz.cn/Article/details/gt2rhhuntik.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jlsjyb.cn/Article/details/gt2xsaulroz.html

[E18] 模板占位符替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ftvuuyub.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.havefunace.top/Article/details/gt2zjowljfc.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhiwuduotai.top/Article/details/gt2voywxhla.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.cashguo.top/Article/details/gt2qbegaofv.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.bjfxy.top/Article/details/gt2obdqhkke.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tyfzpalf.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.nwbrower.top/Article/details/gt2kgokrcku.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qdcmknfo.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jyoumei.cn/Article/details/gt2zgmsuhtt.html

[E19] 多行文本按行拆分
来源：http://dali.yj20258888.top/Article/details/gt2iffyvhkt.html

Py:   s.splitlines()
来源：http://dali.yonumen.top/Article/details/gt2wwgpncpx.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yj20258888.top/Article/details/gt2agebatpx.html

JS:   s.split(/\r?\n/)
来源：http://dali.redwolf501.top/Article/details/gt2zasvlhzy.html

TS:   s.split(/\r?\n/)
来源：http://dali.haohaochexian.top/Article/details/gt2ablhaesg.html

Java: s.lines().toList()
来源：http://dali.yanxiufei.cn/Article/details/gt2xbpqjctx.html

Go:   strings.Split(s, "\n")
来源：http://dali.guannengcc.top/Article/details/gt2pwuvnsjx.html

Ruby: s.lines
来源：http://dali.jlsjyb.cn/Article/details/gt2ivvsatvh.html

C#:   s.Split('\n')
来源：http://dali.pycfn.com/Article/details/gt2kfapojuy.html

[E20] 判断字符串是否为空
来源：http://dali.svipenyu.cn/Article/details/gt2rvjrswai.html

Py:   if not s:
来源：http://dali.ydzc1.top/Article/details/gt2sjjkagwm.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhixingplan.top/Article/details/gt2acebcwsh.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2dnbjvuwx.html

TS:   if (s === "") {}
来源：http://dali.yuanzhike.top/Article/details/gt2sicxwqkr.html

Java: if (s.isEmpty()) {}
来源：http://dali.yj20258888.top/Article/details/gt2ekgnreqg.html

Go:   if s == "" {}
来源：http://dali.yangfankeji.com/Article/details/gt2jmlsemkq.html

Ruby: if s.empty?
来源：http://dali.zhengqikj.top/Article/details/gt2tldyefzx.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.gzhubu.top/Article/details/gt2wrntubkb.html

[E21] 超长截断加省略号
来源：http://dali.cucudq.cn/Article/details/gt2xefgscgu.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hysaishi.cn/Article/details/gt2vwlzyqwb.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jlsjyb.cn/Article/details/gt2mkghyhch.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jlsjyb.cn/Article/details/gt2sxpdulid.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.nanxinkj.top/Article/details/gt2jtqcekzm.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yangfankeji.com/Article/details/gt2drrqbbxy.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.ppjwa.cn/Article/details/gt2yckogldi.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jqgufenzy.top/Article/details/gt2eptnjurm.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhengqikj.top/Article/details/gt2nkjvujwv.html

[E22] 字节长度与字符长度
来源：http://dali.iojbl.cn/Article/details/gt2mqldvvdm.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.sweek.top/Article/details/gt2mtrzxcla.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.dashuyun.cn/Article/details/gt2wislpkeu.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cheryme.top/Article/details/gt2ifotgslr.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xuetiantiany.cn/Article/details/gt2lptwilnb.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.birdmap.top/Article/details/gt2eaeddndz.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jinqigufen.top/Article/details/gt2hudwnwtd.html

Ruby: s.bytesize;  s.length
来源：http://dali.chenlongwang.top/Article/details/gt2flrfpmjb.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yangfankeji.com/Article/details/gt2fveqlhvy.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2zbvueirh.html

F. 文件与目录
来源：http://dali.hnqzz.top/Article/details/gt2vkihnsqj.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2tzbcogec.html

[F01] 读取整个文件
来源：http://dali.nanxuanxn.top/Article/details/gt2gfxxgaoj.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yueranfly.top/Article/details/gt2qbwufgwl.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jianghu66.top/Article/details/gt2pmzwupbc.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yuxming.cn/Article/details/gt2apemlchx.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hnqzz.top/Article/details/gt2hgrpfvpt.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.meibo888.top/Article/details/gt2avxqmbpf.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.chenlongwang.top/Article/details/gt2wepbapks.html

Ruby: File.read("a.txt")
来源：http://dali.hammf.cn/Article/details/gt2txakwdrh.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gt2pkxhylki.html

[F02] 逐行读取文件
来源：http://dali.xinyue.icu/Article/details/gt2kckidelb.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.havefunace.top/Article/details/gt2xqcpeexy.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2mhjyzwqs.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yvedp.cn/Article/details/gt2hxtoxeow.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.0kj1m.cn/Article/details/gt2eyvplxvj.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ppjwa.cn/Article/details/gt2qlamtwng.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.nanxuanxn.top/Article/details/gt2ygqwldfb.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oecpjdbe.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.sxryk.cn/Article/details/gt2fzkimrwx.html

[F03] 写入文件（覆盖）
来源：http://dali.chenlongwang.top/Article/details/gt2czjuipgo.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.bjfxy.top/Article/details/gt2fnckitzj.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yuanzhike.top/Article/details/gt2fmpqsrei.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj202588.top/Article/details/gt2zhfbcdzd.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shuidangran.top/Article/details/gt2kyovdnnq.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.aizwys.cn/Article/details/gt2dntcvxia.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xinyue.icu/Article/details/gt2gdzfzawy.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.cashguo.top/Article/details/gt2zhkftgfd.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.smart0.xyz/Article/details/gt2khncmhxf.html

[F04] 追加写入文件
来源：http://dali.cqqwz.cn/Article/details/gt2ypxnzgud.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ftraydkm.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.ppjwa.cn/Article/details/gt2bmlyxghz.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sxryk.cn/Article/details/gt2eoghdfvc.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eykbuusr.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.nanxinkj.top/Article/details/gt2rdglobog.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.ydzc1.top/Article/details/gt2koskqrgr.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.birdmap.top/Article/details/gt2mjbiubno.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.kuanghao11.cn/Article/details/gt2ctsisyhj.html

[F05] 判断文件或目录是否存在
来源：http://dali.shuidangran.top/Article/details/gt2dgazllbl.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jqgufenzy.top/Article/details/gt2twdgiwmu.html

PHP:  file_exists("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gt2brroquum.html

JS:   fs.existsSync("a.txt")
来源：http://dali.cashguo.top/Article/details/gt2ukslgxlu.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2ijdeixhy.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.pengpengdd.cyou/Article/details/gt2wasbzrei.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.andypj.xyz/Article/details/gt2rjypuhre.html

Ruby: File.exist?("a.txt")
来源：http://dali.c1oappe.top/Article/details/gt2mbglhoyx.html

C#:   File.Exists("a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2szsvcjre.html

[F06] 删除文件
来源：http://dali.birdmap.top/Article/details/gt2ihjxdscs.html

Py:   os.remove("a.txt")
来源：http://dali.yj20258888.top/Article/details/gt2muwwlucy.html

PHP:  unlink("a.txt");
来源：http://dali.yongpay.top/Article/details/gt2fzamzwgw.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2vedvltsu.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2gnitcejc.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.redwolf501.top/Article/details/gt2nwffzhjl.html

Go:   os.Remove("a.txt")
来源：http://dali.sweek.top/Article/details/gt2quifsaut.html

Ruby: File.delete("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2exoqzjkf.html

C#:   File.Delete("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gt2nomjrngg.html

[F07] 创建目录（含多级）
来源：http://dali.hammf.cn/Article/details/gt2pfytqqlv.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.guowangkeji.top/Article/details/gt2tfwuitxy.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.quarkkingdee.top/Article/details/gt2zxegvvpl.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cqqwz.cn/Article/details/gt2zeyhwnbf.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xuetiantiany.cn/Article/details/gt2hcajvhnz.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.cashguo.top/Article/details/gt2aywhdunk.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.chenzaomai.com/Article/details/gt2drcttceu.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.daxiang520.top/Article/details/gt2hpcwkkum.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wsoqgbzs.html

[F08] 遍历目录
来源：http://dali.havefunace.top/Article/details/gt2hxxchabr.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.smart0.xyz/Article/details/gt2gltlgqek.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.ehwqpu.com/Article/details/gt2jepykfbp.html

JS:   fs.readdirSync("dir")
来源：http://dali.zdqjudy.top/Article/details/gt2imdosjfz.html

TS:   fs.readdirSync("dir")
来源：http://dali.yueranfly.top/Article/details/gt2rnwlvfyk.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.mhx1999.top/Article/details/gt2wmosxgpo.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.cheryme.top/Article/details/gt2wjxvcefc.html

Ruby: Dir.children("dir")
来源：http://dali.cheryme.top/Article/details/gt2swntwkvw.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jlsjyb.cn/Article/details/gt2gcezvjwb.html

[F09] 获取文件大小
来源：http://dali.tianlin.xyz/Article/details/gt2ngmqdopx.html

Py:   os.path.getsize("a.txt")
来源：http://dali.sysykeji.top/Article/details/gt2mqmlcfeu.html

PHP:  filesize("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gt2eadhfbfu.html

JS:   fs.statSync("a.txt").size
来源：http://dali.sxryk.cn/Article/details/gt2wfmbyksj.html

TS:   fs.statSync("a.txt").size
来源：http://dali.9152youxi.cn/Article/details/gt2hfskepyp.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xinyue.icu/Article/details/gt2gctrglug.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jqgufenzy.top/Article/details/gt2kptqnypx.html

Ruby: File.size("a.txt")
来源：http://dali.yj202588.top/Article/details/gt2kmntprbw.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.shzxlz.cn/Article/details/gt2wohbiwji.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.kuanghao11.cn/Article/details/gt2vxsmcxgh.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2gprgbmjx.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.cashguo.top/Article/details/gt2iltfqwki.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.wangdashe.top/Article/details/gt2ygpgutpu.html

TS:   path.extname("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hyonmqky.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhongyouzk.top/Article/details/gt2lzfeirfb.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.havefunace.top/Article/details/gt2pyocnuzd.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2aknjbgzd.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2zwhutwxz.html

[F11] 复制与移动文件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jqxctwdm.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2zbsfpfmf.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.gaohongyu789.top/Article/details/gt2iyqicrjh.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.guannengcc.top/Article/details/gt2bjcyghgy.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2bkiuqlfp.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hysaishi.cn/Article/details/gt2kbosedur.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.sufxvd.cn/Article/details/gt2vvcjhxgg.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.havefunace.top/Article/details/gt2otmrxucp.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.nwbrower.top/Article/details/gt2vthlmikd.html

[F12] CSV 读写
来源：http://dali.jqgfzy.top/Article/details/gt2fglrglui.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hammf.cn/Article/details/gt2ayyokuvu.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hnqzz.top/Article/details/gt2mwqbkjci.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hfpthk.cn/Article/details/gt2kfuytmfc.html

TS:   // 同上
来源：http://dali.hywenlv.cn/Article/details/gt2mcxjwzue.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jinqigfzy.top/Article/details/gt2tmuvhjyd.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.shuidangran.top/Article/details/gt2rvsfnftg.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jiagoushi.top/Article/details/gt2snzumsxh.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jqgfzy.top/Article/details/gt2kvixzzos.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2seaiwnkk.html

G. 面向对象
来源：http://dali.chenjidiqi.icu/Article/details/gt2tuyjvfnf.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2utyclefx.html

[G01] 定义类
来源：http://dali.jqgufenzy.top/Article/details/gt2urhyeheq.html

Py:   class User: pass
来源：http://dali.jinqigufen.top/Article/details/gt2tznlcmyn.html

PHP:  class User {}
来源：http://dali.quarkkingdee.top/Article/details/gt2ptdeikyq.html

JS:   class User {}
来源：http://dali.gzhubu.top/Article/details/gt2vztnhnkw.html

TS:   class User { name: string = ""; }
来源：http://dali.hfpthk.cn/Article/details/gt2rkxogfkh.html

Java: class User {}
来源：http://dali.dianchejie.cn/Article/details/gt2xazmelpd.html

Go:   type User struct { Name string }
来源：http://dali.zhixingplan.top/Article/details/gt2amirvsgh.html

Ruby: class User; end
来源：http://dali.hnqzz.top/Article/details/gt2wzlktgvy.html

C#:   class User {}
来源：http://dali.9152youxi.cn/Article/details/gt2uszmgiag.html

[G02] 构造函数
来源：http://dali.cucudq.cn/Article/details/gt2svrnxnnc.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.daria6918.cn/Article/details/gt2waffrhcp.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xgfvmcxq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hnqzz.top/Article/details/gt2rdahcazr.html

TS:   constructor(public name: string) {}
来源：http://dali.sufxvd.cn/Article/details/gt2kahnklwf.html

Java: User(String name) { this.name = name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2mggguoko.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ydzc1.top/Article/details/gt2xlilehou.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zycfv.cn/Article/details/gt2tbhoiyzg.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jinqigufen.top/Article/details/gt2opclbldf.html

[G03] 实例属性
来源：http://dali.vqdsnc.cn/Article/details/gt2tyzmtpro.html

Py:   self.name = "x"
来源：http://dali.kuanghao11.cn/Article/details/gt2hqztehkz.html

PHP:  public string $name = "x";
来源：http://dali.zhengqikj.top/Article/details/gt2bswghiao.html

JS:   this.name = "x";
来源：http://dali.kuanghao11.cn/Article/details/gt2fnmvbxrd.html

TS:   name: string = "x";
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iyhypqmr.html

Java: private String name;
来源：http://dali.redwolf501.top/Article/details/gt2klqlwely.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zycfv.cn/Article/details/gt2rsijfbjq.html

Ruby: @name = "x"
来源：http://dali.hysaishi.cn/Article/details/gt2zmcctggb.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.birdmap.top/Article/details/gt2miwgwcvm.html

[G04] 定义方法
来源：http://dali.zycfv.cn/Article/details/gt2xxpswvpd.html

Py:   def greet(self): return self.name
来源：http://dali.dashuyun.cn/Article/details/gt2hisgbmdq.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.shzxlz.cn/Article/details/gt2costvhzb.html

JS:   greet() { return this.name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2cpfbbwol.html

TS:   greet(): string { return this.name; }
来源：http://dali.ehwqpu.com/Article/details/gt2tncdjxfw.html

Java: String greet() { return name; }
来源：http://dali.aizwys.cn/Article/details/gt2oeezlwmi.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zdqjudy.top/Article/details/gt2wqesdwzd.html

Ruby: def greet; @name; end
来源：http://dali.chenlongwang.top/Article/details/gt2ciuuumoz.html

C#:   public string Greet() => Name;
来源：http://dali.vqdsnc.cn/Article/details/gt2cwnpwcai.html

[G05] 继承
来源：http://dali.cheryme.top/Article/details/gt2xmaamgby.html

Py:   class Admin(User): pass
来源：http://dali.zhixingplan.top/Article/details/gt2lujwrrps.html

PHP:  class Admin extends User {}
来源：http://dali.nwbrower.top/Article/details/gt2tvthsbuf.html

JS:   class Admin extends User {}
来源：http://dali.smart0.xyz/Article/details/gt2hejegowp.html

TS:   class Admin extends User {}
来源：http://dali.cheryme.top/Article/details/gt2aqiuveam.html

Java: class Admin extends User {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2alyjqtmn.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.sysykeji.top/Article/details/gt2rlwhmrbu.html

Ruby: class Admin < User; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2smmuknwu.html

C#:   class Admin : User {}
来源：http://dali.sweek.top/Article/details/gt2aqvyslnk.html

[G06] 重写方法
来源：http://dali.0kj1m.cn/Article/details/gt2edaaqkdz.html

Py:   def greet(self): return "admin"
来源：http://dali.xinyue.icu/Article/details/gt2uwhakygr.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2jvhkugjb.html

JS:   greet() { return "admin"; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2tvpyojks.html

TS:   greet(): string { return "admin"; }
来源：http://dali.fzhhl.top/Article/details/gt2qlmlfexj.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.aizwys.cn/Article/details/gt2ertutmgz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.daria6918.cn/Article/details/gt2djzootea.html

Ruby: def greet; "admin"; end
来源：http://dali.andypj.xyz/Article/details/gt2imyfyqjz.html

C#:   public override string Greet() => "admin";
来源：http://dali.wangdashe.top/Article/details/gt2aywniucv.html

[G07] 调用父类方法
来源：http://dali.dianchejie.cn/Article/details/gt2zgizvwgq.html

Py:   super().greet()
来源：http://dali.tianlin.xyz/Article/details/gt2qfsvbzsl.html

PHP:  parent::greet();
来源：http://dali.nanxuanxn.top/Article/details/gt2skoxkhsu.html


<!-- 参考信息 -->