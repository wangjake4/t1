代发 wailian999

[E10] 左侧补零 / 定长填充
来源：http://dali.daxiang520.top/Article/details/gt2jlabbrhd.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yongpay.top/Article/details/gt2hhxegohu.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.c1oappe.top/Article/details/gt2ispbfozq.html

JS:   "7".padStart(3, "0")
来源：http://dali.xinyue.icu/Article/details/gt2cvxeuytd.html

TS:   "7".padStart(3, "0")
来源：http://dali.nanxuanxn.top/Article/details/gt2lytnscyr.html

Java: String.format("%03d", 7)
来源：http://dali.aizwys.cn/Article/details/gt2tgceaofa.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.9152youxi.cn/Article/details/gt2vzmldvlz.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yangfankeji.com/Article/details/gt2exjuurln.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.ivvv.top/Article/details/gt2vejwnbdw.html

[E11] 反转字符串
来源：http://dali.nanxinkj.top/Article/details/gt2pybocnzl.html

Py:   s[::-1]
来源：http://dali.vqdsnc.cn/Article/details/gt2fuzhxydq.html

PHP:  strrev($s);
来源：http://dali.fzhhl.top/Article/details/gt2pytmtfjy.html

JS:   [...s].reverse().join("")
来源：http://dali.gotoacloud.top/Article/details/gt2atvmtomi.html

TS:   [...s].reverse().join("")
来源：http://dali.cucudq.cn/Article/details/gt2qffxrdzw.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.c1oappe.top/Article/details/gt2yrkobgot.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.smart0.xyz/Article/details/gt2xscyrakq.html

Ruby: s.reverse
来源：http://dali.fengsongda.top/Article/details/gt2aqpxanwj.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2otgnqxmz.html

[E12] 统计某字符出现次数
来源：http://dali.nwbrower.top/Article/details/gt2pcyqpwuy.html

Py:   s.count("a")
来源：http://dali.cucudq.cn/Article/details/gt2akzqdzlf.html

PHP:  substr_count($s, "a");
来源：http://dali.tanke756.top/Article/details/gt2pdtiazvd.html

JS:   s.split("a").length - 1
来源：http://dali.zhoulong.xyz/Article/details/gt2ywpkgpoi.html

TS:   s.split("a").length - 1
来源：http://dali.shangyingyoupin.top/Article/details/gt2gyvkmftw.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.redwolf501.top/Article/details/gt2ijxvhmcj.html

Go:   strings.Count(s, "a")
来源：http://dali.quarkkingdee.top/Article/details/gt2hfinhmnv.html

Ruby: s.count("a")
来源：http://dali.smart0.xyz/Article/details/gt2kqqlljqh.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jiagoushi.top/Article/details/gt2gvdardzk.html

[E13] 逐字符遍历
来源：http://dali.andypj.xyz/Article/details/gt2zhkgznek.html

Py:   for ch in s: print(ch)
来源：http://dali.quarkkingdee.top/Article/details/gt2wzwpjtrc.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.shzxlz.cn/Article/details/gt2viykzeqv.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yuxming.cn/Article/details/gt2cljzovkj.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wenecyoi.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yongpay.top/Article/details/gt2bcnzdknp.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yj20258888.top/Article/details/gt2gegimjof.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.xuetiantiany.cn/Article/details/gt2zcoyfbas.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.316326.xyz/Article/details/gt2aluafulv.html

[E14] URL 编码与 Base64
来源：http://dali.yangfankeji.com/Article/details/gt2igxvzzbz.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hfpthk.cn/Article/details/gt2jsxgmtwr.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.316326.xyz/Article/details/gt2fesbxyit.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2niwejhmf.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zdqjudy.top/Article/details/gt2hnmpilvf.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.pycfn.com/Article/details/gt2stxfpzsg.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iizujxms.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhoulong.xyz/Article/details/gt2kbnafera.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yangfankeji.com/Article/details/gt2ivuafdza.html

[E15] HTML 转义 / 反转义
来源：http://dali.nanxuanxn.top/Article/details/gt2nnxympee.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dlgvjjah.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yvedp.cn/Article/details/gt2tvwpufxp.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yvedp.cn/Article/details/gt2ibspaubt.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.ybcxt.top/Article/details/gt2qcbnxkii.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.redwolf501.top/Article/details/gt2bzgipuqh.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.chenzaomai.com/Article/details/gt2fyqhjydi.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yvedp.cn/Article/details/gt2ucgfhvbn.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.xylfe.cn/Article/details/gt2twadijtx.html

[E16] 数字千分位
来源：http://dali.bjfxy.top/Article/details/gt2zgbxdshu.html

Py:   f"{1234567:,}"
来源：http://dali.nanxinkj.top/Article/details/gt2rrucvtuw.html

PHP:  number_format(1234567);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jndkehkv.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yj20258.top/Article/details/gt2leifchqh.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.pengpengdd.cyou/Article/details/gt2qwrrkykm.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jqgufenzy.top/Article/details/gt2nnvonawd.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.svipenyu.cn/Article/details/gt2xzywympl.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.xylfe.cn/Article/details/gt2sizujsxm.html

C#:   1234567.ToString("N0")
来源：http://dali.jianghu66.top/Article/details/gt2hdwiidqj.html

[E17] 首字母大写
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xndacjdm.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2shugkhkp.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jqgfzy.top/Article/details/gt2tzdydusn.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ivvv.top/Article/details/gt2shjnaluk.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.nanxuanxn.top/Article/details/gt2vkaptegn.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.aibaodan.cn/Article/details/gt2xsnngrvv.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.sysykeji.top/Article/details/gt2guraeren.html

Ruby: s.capitalize
来源：http://dali.yj20258888.top/Article/details/gt2ivxifbir.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.meibo888.top/Article/details/gt2ghoyiwye.html

[E18] 模板占位符替换
来源：http://dali.gotoacloud.top/Article/details/gt2rkmazdgc.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jyoumei.cn/Article/details/gt2eibhnyfv.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.pycfn.com/Article/details/gt2scenpakh.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hnqzz.top/Article/details/gt2qulvzejy.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jqgufenzy.top/Article/details/gt2piroraby.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xteusaav.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.nanxinkj.top/Article/details/gt2enkywbjq.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.xinyue.icu/Article/details/gt2fvfheafk.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.guowangkeji.top/Article/details/gt2cgonqlod.html

[E19] 多行文本按行拆分
来源：http://dali.xziqi.cn/Article/details/gt2swaatkrs.html

Py:   s.splitlines()
来源：http://dali.bjfxy.top/Article/details/gt2bipzyjcx.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.dashuyun.cn/Article/details/gt2grwbyqdx.html

JS:   s.split(/\r?\n/)
来源：http://dali.hnqzz.top/Article/details/gt2dbdbmcvp.html

TS:   s.split(/\r?\n/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jcyetzyd.html

Java: s.lines().toList()
来源：http://dali.meibo888.top/Article/details/gt2rurhijjb.html

Go:   strings.Split(s, "\n")
来源：http://dali.yueranfly.top/Article/details/gt2hwakxtzh.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2lbgoywqa.html

C#:   s.Split('\n')
来源：http://dali.zhixingplan.top/Article/details/gt2qxoaipfg.html

[E20] 判断字符串是否为空
来源：http://dali.chenzaomai.com/Article/details/gt2hmnruhci.html

Py:   if not s:
来源：http://dali.wangshuangyany.cn/Article/details/gt2btyfcymz.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.c1oappe.top/Article/details/gt2ucauogdf.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.sysykeji.top/Article/details/gt2stdawaqs.html

TS:   if (s === "") {}
来源：http://dali.tian-w.cn/Article/details/gt2pkmswgyg.html

Java: if (s.isEmpty()) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2biulfxgf.html

Go:   if s == "" {}
来源：http://dali.jinqigufen.top/Article/details/gt2woosjdrh.html

Ruby: if s.empty?
来源：http://dali.yj20258.top/Article/details/gt2zjycywvm.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.cqqwz.cn/Article/details/gt2jwiytyxu.html

[E21] 超长截断加省略号
来源：http://dali.ppjwa.cn/Article/details/gt2zjxbhadh.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.316326.xyz/Article/details/gt2bcdfxljx.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zycfv.cn/Article/details/gt2eyidpubc.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.dianchejie.cn/Article/details/gt2nscjwsbo.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.kuanghao11.cn/Article/details/gt2wvtxkrjb.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.c1oappe.top/Article/details/gt2rmkmxjnz.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.iojbl.cn/Article/details/gt2luthnevh.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhixingplan.top/Article/details/gt2ahwkqblx.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.fengsongda.top/Article/details/gt2vpkuwogv.html

[E22] 字节长度与字符长度
来源：http://dali.vqdsnc.cn/Article/details/gt2bpdtoopn.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.hywenlv.cn/Article/details/gt2esyqnnmf.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bgowpviw.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.0kj1m.cn/Article/details/gt2xybtlhtz.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.fengsongda.top/Article/details/gt2jkeurgzu.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hfpthk.cn/Article/details/gt2erdkiogc.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.redwolf501.top/Article/details/gt2rswpziyz.html

Ruby: s.bytesize;  s.length
来源：http://dali.hysaishi.cn/Article/details/gt2eulzuujf.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.sysykeji.top/Article/details/gt2hyrzuqno.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2zrfnigok.html

F. 文件与目录
来源：http://dali.quarkkingdee.top/Article/details/gt2exvhcilm.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2dcrxllzb.html

[F01] 读取整个文件
来源：http://dali.fzhhl.top/Article/details/gt2zftmxjfh.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.iojbl.cn/Article/details/gt2yngnvola.html

PHP:  file_get_contents("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gt2jyyhuqsw.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jlsjyb.cn/Article/details/gt2uwcksnbj.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhoulong.xyz/Article/details/gt2neopmbtq.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.feifeiyinyue.top/Article/details/gt2poeuwswi.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gjtqocjb.html

Ruby: File.read("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2oixxarhw.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gt2pumdbrkp.html

[F02] 逐行读取文件
来源：http://dali.ydzc1.top/Article/details/gt2ucxzujrt.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.sufxvd.cn/Article/details/gt2qymjhipy.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hfpthk.cn/Article/details/gt2unjiqpwa.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xuanzx.com/Article/details/gt2culigyon.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.redwolf501.top/Article/details/gt2numiztue.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.nanxinkj.top/Article/details/gt2fozoyydn.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.snrcjt.cn/Article/details/gt2xmktzmvs.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.gogol.net.cn/Article/details/gt2oujiuzpb.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2gcxyompr.html

[F03] 写入文件（覆盖）
来源：http://dali.yonumen.top/Article/details/gt2tcgsyruq.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.daxiang520.top/Article/details/gt2rfqugpbm.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhixingplan.top/Article/details/gt2pgcrwnwe.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ppjwa.cn/Article/details/gt2dxufvhlj.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.havefunace.top/Article/details/gt2hdquwayp.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yuxming.cn/Article/details/gt2pachqzqu.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.0kj1m.cn/Article/details/gt2mqdhwqke.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.tanke756.top/Article/details/gt2hghyhzto.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.tianlin.xyz/Article/details/gt2ehlxdrtv.html

[F04] 追加写入文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2efbrjqyy.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yuxming.cn/Article/details/gt2ryfchgge.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.hysaishi.cn/Article/details/gt2hbfimvwi.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.aizwys.cn/Article/details/gt2wjenbaew.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xylfe.cn/Article/details/gt2zjyqxnby.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.wangshuangyany.cn/Article/details/gt2xftbebrb.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.vqdsnc.cn/Article/details/gt2wdnppbwt.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.nwbrower.top/Article/details/gt2agcjrzbx.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.bjfxy.top/Article/details/gt2ezcgfbzg.html

[F05] 判断文件或目录是否存在
来源：http://dali.svipenyu.cn/Article/details/gt2dcdzoifj.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ppjwa.cn/Article/details/gt2qolxypwz.html

PHP:  file_exists("a.txt");
来源：http://dali.wangdashe.top/Article/details/gt2fyphwibs.html

JS:   fs.existsSync("a.txt")
来源：http://dali.nwbrower.top/Article/details/gt2pgvosbhs.html

TS:   fs.existsSync("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2qvycsnuf.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.gaohongyu789.top/Article/details/gt2qagtdrhr.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.gogol.net.cn/Article/details/gt2upvioapq.html

Ruby: File.exist?("a.txt")
来源：http://dali.andypj.xyz/Article/details/gt2qtwvchko.html

C#:   File.Exists("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2lecilffs.html

[F06] 删除文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qrisutii.html

Py:   os.remove("a.txt")
来源：http://dali.bjfxy.top/Article/details/gt2skkijcwy.html

PHP:  unlink("a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gt2rvpcknlv.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2piduiiap.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2ckjdmjvq.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.cheryme.top/Article/details/gt2ocexrowd.html

Go:   os.Remove("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2ngzitlrx.html

Ruby: File.delete("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2jyzcjrzh.html

C#:   File.Delete("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gt2kbqqswtr.html

[F07] 创建目录（含多级）
来源：http://dali.xinyue.icu/Article/details/gt2gmrhengq.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qiceunpb.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.meibo888.top/Article/details/gt2cymgeeds.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2wkgftppf.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hysaishi.cn/Article/details/gt2agxqmuoq.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.gogol.net.cn/Article/details/gt2wyuuclfa.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jianghu66.top/Article/details/gt2vbpxuyvy.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.0kj1m.cn/Article/details/gt2cbcrkfyc.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.tian-w.cn/Article/details/gt2xcaluzda.html

[F08] 遍历目录
来源：http://dali.snrcjt.cn/Article/details/gt2ibgfwkxr.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jqgufenzy.top/Article/details/gt2tdusvibb.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.ydzc1.top/Article/details/gt2jvxckwrl.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhoulong.xyz/Article/details/gt2nuuysedy.html

TS:   fs.readdirSync("dir")
来源：http://dali.ivvv.top/Article/details/gt2sefrwnhb.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.9152youxi.cn/Article/details/gt2mfzqmkts.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ydzc1.top/Article/details/gt2mxultlxc.html

Ruby: Dir.children("dir")
来源：http://dali.yongpay.top/Article/details/gt2trggjpax.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yj202588.top/Article/details/gt2qfhpmodl.html

[F09] 获取文件大小
来源：http://dali.kuanghao11.cn/Article/details/gt2rhpqulnw.html

Py:   os.path.getsize("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2gftzsbvp.html

PHP:  filesize("a.txt");
来源：http://dali.tanke756.top/Article/details/gt2mikrjzpb.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hysaishi.cn/Article/details/gt2vamnzldp.html

TS:   fs.statSync("a.txt").size
来源：http://dali.nanxuanxn.top/Article/details/gt2dyczalwk.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.sweek.top/Article/details/gt2dkkvkjmd.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yonumen.top/Article/details/gt2rrqaivrm.html

Ruby: File.size("a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2qdllcbqb.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.mhx1999.top/Article/details/gt2udazhufi.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yongpay.top/Article/details/gt2qtrumobr.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2gscqheqo.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gt2clsayndk.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yj20258888.top/Article/details/gt2ieyeqlma.html

TS:   path.extname("a.txt")
来源：http://dali.mhx1999.top/Article/details/gt2jxibyjtz.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.dianchejie.cn/Article/details/gt2sdprntec.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2bfndaqzj.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2itejyhgz.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2uhfxrvgu.html

[F11] 复制与移动文件
来源：http://dali.hysaishi.cn/Article/details/gt2lxcnawgh.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2qhxfyfej.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.quarkkingdee.top/Article/details/gt2ejknxfjx.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gzhubu.top/Article/details/gt2cnsdytnl.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2htteamvt.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zvlpkkgs.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.shanyushiyangtech.top/Article/details/gt2okptxrsb.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xuanzx.com/Article/details/gt2mkntqsfa.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shzxlz.cn/Article/details/gt2obpyvmvv.html

[F12] CSV 读写
来源：http://dali.hywenlv.cn/Article/details/gt2enxqxsju.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.daxiang520.top/Article/details/gt2vccvclwx.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.wangshuangyany.cn/Article/details/gt2qwmkcboz.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.iojbl.cn/Article/details/gt2iaksqtfc.html

TS:   // 同上
来源：http://dali.daria6918.cn/Article/details/gt2oryobpvw.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xziqi.cn/Article/details/gt2oxjdkcvp.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.gogol.net.cn/Article/details/gt2xbqkmyrz.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhengqikj.top/Article/details/gt2urxdxoeu.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.shzxlz.cn/Article/details/gt2vwtyoqwe.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2mqqivyig.html

G. 面向对象
来源：http://dali.cashguo.top/Article/details/gt2hsqjvyka.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2wuelabok.html

[G01] 定义类
来源：http://dali.jlsjyb.cn/Article/details/gt2tbhbgopb.html

Py:   class User: pass
来源：http://dali.jlsjyb.cn/Article/details/gt2zvidbvsv.html

PHP:  class User {}
来源：http://dali.birdmap.top/Article/details/gt2hchzhqcj.html

JS:   class User {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2mkepcdfm.html

TS:   class User { name: string = ""; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2isrbqqau.html

Java: class User {}
来源：http://dali.guowangkeji.top/Article/details/gt2uepryhsx.html

Go:   type User struct { Name string }
来源：http://dali.zhixingplan.top/Article/details/gt2nxfvscqo.html

Ruby: class User; end
来源：http://dali.cdnleiting.top/Article/details/gt2qfmsdzak.html

C#:   class User {}
来源：http://dali.guowangkeji.top/Article/details/gt2fppnfwws.html

[G02] 构造函数
来源：http://dali.sxryk.cn/Article/details/gt2ndnfydty.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jqgfzy.top/Article/details/gt2rfzkpjay.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2znrmadsv.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.smart0.xyz/Article/details/gt2qyjorgcp.html

TS:   constructor(public name: string) {}
来源：http://dali.yongpay.top/Article/details/gt2utrtvdoz.html

Java: User(String name) { this.name = name; }
来源：http://dali.yuanzhike.top/Article/details/gt2dpbovlar.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xinyue.icu/Article/details/gt2czrbyzif.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yuxming.cn/Article/details/gt2mspkgpxq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jinqigfzy.top/Article/details/gt2oubnedxs.html

[G03] 实例属性
来源：http://dali.mhx1999.top/Article/details/gt2poophhgi.html

Py:   self.name = "x"
来源：http://dali.xylfe.cn/Article/details/gt2zfojfugs.html

PHP:  public string $name = "x";
来源：http://dali.jianghu66.top/Article/details/gt2bkzzqgsp.html

JS:   this.name = "x";
来源：http://dali.snrcjt.cn/Article/details/gt2beenjhph.html

TS:   name: string = "x";
来源：http://dali.tian-w.cn/Article/details/gt2xusvunnb.html

Java: private String name;
来源：http://dali.yuanzhike.top/Article/details/gt2wgxpvjax.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.nanxuanxn.top/Article/details/gt2bymegrjd.html

Ruby: @name = "x"
来源：http://dali.jqgfzy.top/Article/details/gt2ikpbkmrc.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.dashuyun.cn/Article/details/gt2xlqsanke.html

[G04] 定义方法
来源：http://dali.dianchejie.cn/Article/details/gt2dqwpnhvm.html

Py:   def greet(self): return self.name
来源：http://dali.sxryk.cn/Article/details/gt2kzdxfcyc.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2umdltvhe.html

JS:   greet() { return this.name; }
来源：http://dali.zycfv.cn/Article/details/gt2tixsyege.html

TS:   greet(): string { return this.name; }
来源：http://dali.ydzc1.top/Article/details/gt2ffllgfwn.html

Java: String greet() { return name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2vapbonta.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jinqigufen.top/Article/details/gt2gjzafnjn.html

Ruby: def greet; @name; end
来源：http://dali.pycfn.com/Article/details/gt2rxjglhhk.html

C#:   public string Greet() => Name;
来源：http://dali.jianghu66.top/Article/details/gt2gtqwyyov.html

[G05] 继承
来源：http://dali.zycfv.cn/Article/details/gt2nloawkff.html

Py:   class Admin(User): pass
来源：http://dali.cashguo.top/Article/details/gt2mxxkgkzw.html

PHP:  class Admin extends User {}
来源：http://dali.316326.xyz/Article/details/gt2zqecvdag.html

JS:   class Admin extends User {}
来源：http://dali.0kj1m.cn/Article/details/gt2aprurava.html

TS:   class Admin extends User {}
来源：http://dali.birdmap.top/Article/details/gt2kdguilhx.html

Java: class Admin extends User {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2otsgqovu.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.andypj.xyz/Article/details/gt2gvwoildn.html

Ruby: class Admin < User; end
来源：http://dali.yj20258.top/Article/details/gt2ozjrusvv.html

C#:   class Admin : User {}
来源：http://dali.smart0.xyz/Article/details/gt2cvfekdyt.html

[G06] 重写方法
来源：http://dali.shuidangran.top/Article/details/gt2rkaztujg.html

Py:   def greet(self): return "admin"
来源：http://dali.dashuyun.cn/Article/details/gt2naojguti.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.nwbrower.top/Article/details/gt2xiyxsgsx.html

JS:   greet() { return "admin"; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2pybgcykd.html

TS:   greet(): string { return "admin"; }
来源：http://dali.guowangkeji.top/Article/details/gt2xwmmdikc.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.kuanghao11.cn/Article/details/gt2fszyhbpd.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.nwbrower.top/Article/details/gt2caombxrd.html

Ruby: def greet; "admin"; end
来源：http://dali.andypj.xyz/Article/details/gt2ivwoobtv.html

C#:   public override string Greet() => "admin";
来源：http://dali.yongpay.top/Article/details/gt2cdawmcut.html

[G07] 调用父类方法
来源：http://dali.chenjidiqi.icu/Article/details/gt2canfgzem.html

Py:   super().greet()
来源：http://dali.yangfankeji.com/Article/details/gt2zaonzqqv.html

PHP:  parent::greet();
来源：http://dali.ehwqpu.com/Article/details/gt2mhiybofl.html

JS:   super.greet();
来源：http://dali.haohaochexian.top/Article/details/gt2yilytaud.html

TS:   super.greet();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ilvonyea.html

Java: super.greet();
来源：http://dali.pycfn.com/Article/details/gt2ovnkjqdv.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.andypj.xyz/Article/details/gt2uytddjwv.html

Ruby: super
来源：http://dali.quarkkingdee.top/Article/details/gt2feqvunbj.html

C#:   base.Greet();
来源：http://dali.tian-w.cn/Article/details/gt2tprcmmic.html

[G08] 静态方法与属性
来源：http://dali.tianlin.xyz/Article/details/gt2fwaydygl.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.c1oappe.top/Article/details/gt2etwmpbhl.html

PHP:  public static function f() {}
来源：http://dali.jlsjyb.cn/Article/details/gt2byozbybb.html

JS:   static f() {}
来源：http://dali.yanxiufei.cn/Article/details/gt2lzmwmnqt.html

TS:   static f(): void {}
来源：http://dali.yangfankeji.com/Article/details/gt2zdbzgxuz.html

Java: static void f() {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2espcrell.html


<!-- 参考信息 -->