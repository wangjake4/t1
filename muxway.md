代发 wailian999

PHP:  implode(",", $items);
来源：http://dali.sweek.top/Article/details/gt2qvgrbazs.html

JS:   items.join(",")
来源：http://dali.jlsjyb.cn/Article/details/gt2xwpinqjc.html

TS:   items.join(",")
来源：http://dali.chenzaomai.com/Article/details/gt2eoynmehz.html

Java: String.join(",", items)
来源：http://dali.feifeiyinyue.top/Article/details/gt2cuwniakp.html

Go:   strings.Join(items, ",")
来源：http://dali.sufxvd.cn/Article/details/gt2aczlzocq.html

Ruby: items.join(",")
来源：http://dali.jiagoushi.top/Article/details/gt2rhdmbyia.html

C#:   string.Join(",", items)
来源：http://dali.yuxming.cn/Article/details/gt2gindfuht.html

[E09] 去除所有空白字符
来源：http://dali.hysaishi.cn/Article/details/gt2vaommzsf.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2uutiyrcl.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.shuidangran.top/Article/details/gt2rpnsbyob.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jiagoushi.top/Article/details/gt2mteciwup.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.dashuyun.cn/Article/details/gt2oabtswey.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.xylfe.cn/Article/details/gt2icmqrxsi.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.aizwys.cn/Article/details/gt2jwletkxo.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.chenzaomai.com/Article/details/gt2vxoqkjhm.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zycfv.cn/Article/details/gt2uttogoot.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yj20258.top/Article/details/gt2dkxcfwyo.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jqgfzy.top/Article/details/gt2qkrzcgol.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.mhx1999.top/Article/details/gt2vwmhhfip.html

JS:   "7".padStart(3, "0")
来源：http://dali.xuetiantiany.cn/Article/details/gt2oxbjvrcw.html

TS:   "7".padStart(3, "0")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2miculmkn.html

Java: String.format("%03d", 7)
来源：http://dali.hfpthk.cn/Article/details/gt2zygeeakc.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.0kj1m.cn/Article/details/gt2evrxfhtk.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.nwbrower.top/Article/details/gt2vyqppnrs.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jinqigufen.top/Article/details/gt2jdkuyvtp.html

[E11] 反转字符串
来源：http://dali.haohaochexian.top/Article/details/gt2yfumugna.html

Py:   s[::-1]
来源：http://dali.yj20258888.top/Article/details/gt2gfdyyque.html

PHP:  strrev($s);
来源：http://dali.nanxuanxn.top/Article/details/gt2wfyroyfq.html

JS:   [...s].reverse().join("")
来源：http://dali.316326.xyz/Article/details/gt2crammhsp.html

TS:   [...s].reverse().join("")
来源：http://dali.yonumen.top/Article/details/gt2avflyqnq.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.ydzc1.top/Article/details/gt2pdsxidqk.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.gogol.net.cn/Article/details/gt2orffdrdc.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2jrtzcnoi.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhixingplan.top/Article/details/gt2eqsvgxtg.html

[E12] 统计某字符出现次数
来源：http://dali.yonumen.top/Article/details/gt2owqsajgl.html

Py:   s.count("a")
来源：http://dali.zdqjudy.top/Article/details/gt2iyinhxxs.html

PHP:  substr_count($s, "a");
来源：http://dali.ppjwa.cn/Article/details/gt2wzjyvgcv.html

JS:   s.split("a").length - 1
来源：http://dali.shzxlz.cn/Article/details/gt2fvaixxle.html

TS:   s.split("a").length - 1
来源：http://dali.ydzc1.top/Article/details/gt2bpnyrpnx.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.snrcjt.cn/Article/details/gt2ygyvpspb.html

Go:   strings.Count(s, "a")
来源：http://dali.hysaishi.cn/Article/details/gt2qozhlgpr.html

Ruby: s.count("a")
来源：http://dali.meibo888.top/Article/details/gt2yreorbec.html

C#:   s.Count(c => c == 'a')
来源：http://dali.aibaodan.cn/Article/details/gt2gyqcxtkt.html

[E13] 逐字符遍历
来源：http://dali.xziqi.cn/Article/details/gt2tpgqtoax.html

Py:   for ch in s: print(ch)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2docpsivu.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.mhx1999.top/Article/details/gt2jplvxnfb.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eulvptgr.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hywenlv.cn/Article/details/gt2wmqfhgtp.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sgnydyxc.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.guannengcc.top/Article/details/gt2qnhuspxy.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yj20258.top/Article/details/gt2pavgqwza.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.cashguo.top/Article/details/gt2lwpkklvs.html

[E14] URL 编码与 Base64
来源：http://dali.xinyue.icu/Article/details/gt2gxfyfxgh.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.pengpengdd.cyou/Article/details/gt2ulocrhvh.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.cqqwz.cn/Article/details/gt2ojzkmqsh.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.smart0.xyz/Article/details/gt2zbdnlsja.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vwcpugwh.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.aibaodan.cn/Article/details/gt2vuwpravm.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.gogol.net.cn/Article/details/gt2wjvwggmh.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jlsjyb.cn/Article/details/gt2usvbpncy.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.pycfn.com/Article/details/gt2soctdarf.html

[E15] HTML 转义 / 反转义
来源：http://dali.aizwys.cn/Article/details/gt2iwqhnoac.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ebucioip.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.shuidangran.top/Article/details/gt2ctjldsat.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.mhx1999.top/Article/details/gt2oxpgtvpd.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.fengsongda.top/Article/details/gt2bvihdjkl.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jugkrnqj.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.gzhubu.top/Article/details/gt2eyyfgjkk.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.svipenyu.cn/Article/details/gt2rfxrmzms.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.nwbrower.top/Article/details/gt2mpoowwps.html

[E16] 数字千分位
来源：http://dali.cashguo.top/Article/details/gt2yswxpuor.html

Py:   f"{1234567:,}"
来源：http://dali.yuanzhike.top/Article/details/gt2umbfwdaw.html

PHP:  number_format(1234567);
来源：http://dali.cashguo.top/Article/details/gt2wpudxwjc.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.cqqwz.cn/Article/details/gt2rtdtijxn.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.ydzc1.top/Article/details/gt2bhnhonjh.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.aizwys.cn/Article/details/gt2uajltddr.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yuanzhike.top/Article/details/gt2jelzosos.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.shuidangran.top/Article/details/gt2pbrycsmo.html

C#:   1234567.ToString("N0")
来源：http://dali.hywenlv.cn/Article/details/gt2giaoqmts.html

[E17] 首字母大写
来源：http://dali.gaohongyu789.top/Article/details/gt2mxqvlrwu.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yuanzhike.top/Article/details/gt2xqwazxda.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hysaishi.cn/Article/details/gt2icvyivvv.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ppjwa.cn/Article/details/gt2zlwsktmz.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yongpay.top/Article/details/gt2ghdmarab.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2uedhgshv.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.sufxvd.cn/Article/details/gt2nugwrzwg.html

Ruby: s.capitalize
来源：http://dali.yueranfly.top/Article/details/gt2yfwkiych.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.cashguo.top/Article/details/gt2zaurntgf.html

[E18] 模板占位符替换
来源：http://dali.gotoacloud.top/Article/details/gt2zrxcyqzh.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.0kj1m.cn/Article/details/gt2eytmmgpc.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhengqikj.top/Article/details/gt2zsnpzcba.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fcdpxlxg.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.tanke756.top/Article/details/gt2lsohmnsu.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.fengsongda.top/Article/details/gt2lnthscqr.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jinqigfzy.top/Article/details/gt2jwpgxvnn.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.dashuyun.cn/Article/details/gt2hdlpmkpb.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.gogol.net.cn/Article/details/gt2ebifqqtm.html

[E19] 多行文本按行拆分
来源：http://dali.quarkkingdee.top/Article/details/gt2wjgwhevu.html

Py:   s.splitlines()
来源：http://dali.xylfe.cn/Article/details/gt2wmojbrrj.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.dianchejie.cn/Article/details/gt2gannvjln.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ypyoszyf.html

TS:   s.split(/\r?\n/)
来源：http://dali.svipenyu.cn/Article/details/gt2sysnjavm.html

Java: s.lines().toList()
来源：http://dali.cdnleiting.top/Article/details/gt2nafvzwgl.html

Go:   strings.Split(s, "\n")
来源：http://dali.tanke756.top/Article/details/gt2ztnctzpo.html

Ruby: s.lines
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sklhlanx.html

C#:   s.Split('\n')
来源：http://dali.xuetiantiany.cn/Article/details/gt2vxuimzpj.html

[E20] 判断字符串是否为空
来源：http://dali.vqdsnc.cn/Article/details/gt2dzpolnkt.html

Py:   if not s:
来源：http://dali.yangfankeji.com/Article/details/gt2aulhfjdz.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hzyjzyqh.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2zlzgyqoe.html

TS:   if (s === "") {}
来源：http://dali.snrcjt.cn/Article/details/gt2dhzeyxbd.html

Java: if (s.isEmpty()) {}
来源：http://dali.meibo888.top/Article/details/gt2zufvncpq.html

Go:   if s == "" {}
来源：http://dali.guowangkeji.top/Article/details/gt2eafjbwbl.html

Ruby: if s.empty?
来源：http://dali.hysaishi.cn/Article/details/gt2ijfxhzna.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.svipenyu.cn/Article/details/gt2ohigdrfh.html

[E21] 超长截断加省略号
来源：http://dali.jqgfzy.top/Article/details/gt2iyrtfjth.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.wangshuangyany.cn/Article/details/gt2cliidgyz.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.dianchejie.cn/Article/details/gt2vxvqlufh.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zycfv.cn/Article/details/gt2lzvqzoro.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gaohongyu789.top/Article/details/gt2uxflfzix.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.vqdsnc.cn/Article/details/gt2aygmpvaa.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.aizwys.cn/Article/details/gt2dfthoecf.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.nwbrower.top/Article/details/gt2sepdrhqd.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.dianchejie.cn/Article/details/gt2yauoiowa.html

[E22] 字节长度与字符长度
来源：http://dali.nanxuanxn.top/Article/details/gt2qudvqztk.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2drewiofz.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.nanxuanxn.top/Article/details/gt2tfbmifck.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.chenlongwang.top/Article/details/gt2kxsmpwcq.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.kuanghao11.cn/Article/details/gt2uwaagvdg.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jinqigfzy.top/Article/details/gt2eombmjsh.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.tian-w.cn/Article/details/gt2fynwjfkf.html

Ruby: s.bytesize;  s.length
来源：http://dali.shuidangran.top/Article/details/gt2dvfnnqbr.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.chenjidiqi.icu/Article/details/gt2roktunle.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2cyeikngg.html

F. 文件与目录
来源：http://dali.snrcjt.cn/Article/details/gt2afqgylfj.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2soowubok.html

[F01] 读取整个文件
来源：http://dali.chenjidiqi.icu/Article/details/gt2oyelngye.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oxmhfvgm.html

PHP:  file_get_contents("a.txt");
来源：http://dali.fengsongda.top/Article/details/gt2vibxyroc.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.cheryme.top/Article/details/gt2lfjofrpi.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yuanzhike.top/Article/details/gt2cemswouz.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.smart0.xyz/Article/details/gt2lawnqhqi.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jqgfzy.top/Article/details/gt2ajuximtq.html

Ruby: File.read("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2clgvsgdc.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gt2mehfvbgx.html

[F02] 逐行读取文件
来源：http://dali.chenzaomai.com/Article/details/gt2iirdnuwt.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lfyneqng.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hfpthk.cn/Article/details/gt2pkuvlqrm.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hfpthk.cn/Article/details/gt2yrzfgsdv.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.9152youxi.cn/Article/details/gt2czqaqxss.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.snrcjt.cn/Article/details/gt2imgssext.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.gogol.net.cn/Article/details/gt2sgclcwik.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.chenjidiqi.icu/Article/details/gt2ravegypl.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.c1oappe.top/Article/details/gt2icqhyzad.html

[F03] 写入文件（覆盖）
来源：http://dali.jqgfzy.top/Article/details/gt2wyhtbxvu.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hysaishi.cn/Article/details/gt2ehzqzjau.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.shuidangran.top/Article/details/gt2agszamme.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shzxlz.cn/Article/details/gt2zsxxtrfe.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.aibaodan.cn/Article/details/gt2ezcqavmn.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.cucudq.cn/Article/details/gt2nzpassvo.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.ybcxt.top/Article/details/gt2sfsibgpw.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.tianlin.xyz/Article/details/gt2qfrxbhvz.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.shzxlz.cn/Article/details/gt2xeqvienj.html

[F04] 追加写入文件
来源：http://dali.jinqigufen.top/Article/details/gt2msmyikcf.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.guannengcc.top/Article/details/gt2ecqphpnj.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.wangshuangyany.cn/Article/details/gt2oteilulu.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bjncatdp.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.chenzaomai.com/Article/details/gt2bhzrafgl.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.cheryme.top/Article/details/gt2wbojgowb.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2awarkbcq.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.chenlongwang.top/Article/details/gt2pklqfumj.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.vqdsnc.cn/Article/details/gt2jsalthgs.html

[F05] 判断文件或目录是否存在
来源：http://dali.dashuyun.cn/Article/details/gt2rmxcvvir.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.iojbl.cn/Article/details/gt2vsyvfeji.html

PHP:  file_exists("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gt2pvculblr.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2ejvuiinc.html

TS:   fs.existsSync("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2mstuiqiw.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jiagoushi.top/Article/details/gt2krhzfxbw.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jiagoushi.top/Article/details/gt2ngriehtp.html

Ruby: File.exist?("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2lemjeuae.html

C#:   File.Exists("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2budrtrqr.html

[F06] 删除文件
来源：http://dali.hnxiangtu.top/Article/details/gt2eazqdwzs.html

Py:   os.remove("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2pvygnqqf.html

PHP:  unlink("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ebysowwo.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.cheryme.top/Article/details/gt2sxgkjizd.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2ipnflyfb.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.ydzc1.top/Article/details/gt2oyigtnck.html

Go:   os.Remove("a.txt")
来源：http://dali.havefunace.top/Article/details/gt2ymbblzuk.html

Ruby: File.delete("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2eoxomnre.html

C#:   File.Delete("a.txt");
来源：http://dali.xylfe.cn/Article/details/gt2dcbqljyj.html

[F07] 创建目录（含多级）
来源：http://dali.fengsongda.top/Article/details/gt2zizhunuc.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jlsjyb.cn/Article/details/gt2mvoutlma.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.chenjidiqi.icu/Article/details/gt2geucwbrs.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinqigufen.top/Article/details/gt2qvyczjqs.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cheryme.top/Article/details/gt2qymqbtds.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.xuanzx.com/Article/details/gt2uihyxxga.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.daxiang520.top/Article/details/gt2oulzfvto.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.c1oappe.top/Article/details/gt2xbqosnqb.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nwbpvtab.html

[F08] 遍历目录
来源：http://dali.zdqjudy.top/Article/details/gt2fduonzhq.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.birdmap.top/Article/details/gt2goshqfep.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qcszattx.html

JS:   fs.readdirSync("dir")
来源：http://dali.chenlongwang.top/Article/details/gt2tjheiokx.html

TS:   fs.readdirSync("dir")
来源：http://dali.zdqjudy.top/Article/details/gt2gicflfmq.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.cheryme.top/Article/details/gt2goklvvwc.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yuanzhike.top/Article/details/gt2kqxvxvzw.html

Ruby: Dir.children("dir")
来源：http://dali.hywenlv.cn/Article/details/gt2hhgnrmqz.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhiwuduotai.top/Article/details/gt2ahskawrg.html

[F09] 获取文件大小
来源：http://dali.0kj1m.cn/Article/details/gt2xnaoqsmw.html

Py:   os.path.getsize("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2mwrgzurk.html

PHP:  filesize("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gt2hsdpkfyr.html

JS:   fs.statSync("a.txt").size
来源：http://dali.sufxvd.cn/Article/details/gt2gfyjlxht.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yongpay.top/Article/details/gt2ncgukkgb.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.aibaodan.cn/Article/details/gt2robikwcr.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yj202588.top/Article/details/gt2syyqoipf.html

Ruby: File.size("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2ntkflfba.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jyoumei.cn/Article/details/gt2klwihzno.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xziqi.cn/Article/details/gt2ltbxgwls.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jianghu66.top/Article/details/gt2duwgyctl.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gt2irpoocjy.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2unneqymg.html

TS:   path.extname("a.txt")
来源：http://dali.yonumen.top/Article/details/gt2qldosbfp.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.dianchejie.cn/Article/details/gt2lmrnpqte.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2yegldnmy.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2fbigpjkd.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yueranfly.top/Article/details/gt2cvmmcwcv.html

[F11] 复制与移动文件
来源：http://dali.guannengcc.top/Article/details/gt2uzpxkdlh.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2asqvbbiq.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.chenlongwang.top/Article/details/gt2ftpreyst.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2ftzdovra.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cucudq.cn/Article/details/gt2dwfpjrxz.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yj202588.top/Article/details/gt2ietfrzxe.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.dashuyun.cn/Article/details/gt2vtuesnjc.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2dnzzovxc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.redwolf501.top/Article/details/gt2pjalvuxz.html

[F12] CSV 读写
来源：http://dali.svipenyu.cn/Article/details/gt2ramyvxud.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.kuanghao11.cn/Article/details/gt2uqbwylfc.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.gotoacloud.top/Article/details/gt2fqliexac.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zdqjudy.top/Article/details/gt2pribqoij.html

TS:   // 同上
来源：http://dali.havefunace.top/Article/details/gt2etgucqzp.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.gotoacloud.top/Article/details/gt2gkjnyytv.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.sxryk.cn/Article/details/gt2eoobuciz.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yuanzhike.top/Article/details/gt2onsntgio.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hysaishi.cn/Article/details/gt2uljfbron.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2znvhmimn.html

G. 面向对象
来源：http://dali.jyoumei.cn/Article/details/gt2rdugzxzi.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fxlxcnwz.html

[G01] 定义类
来源：http://dali.sweek.top/Article/details/gt2lwzqayak.html

Py:   class User: pass
来源：http://dali.9152youxi.cn/Article/details/gt2mwvnhyzr.html

PHP:  class User {}
来源：http://dali.ppjwa.cn/Article/details/gt2sraqdgzl.html

JS:   class User {}
来源：http://dali.svipenyu.cn/Article/details/gt2jqxehakh.html

TS:   class User { name: string = ""; }
来源：http://dali.guowangkeji.top/Article/details/gt2rffssand.html

Java: class User {}
来源：http://dali.ydzc1.top/Article/details/gt2whnlqcxq.html

Go:   type User struct { Name string }
来源：http://dali.guowangkeji.top/Article/details/gt2svtulnye.html

Ruby: class User; end
来源：http://dali.hongshengwenyu.top/Article/details/gt2jtwaoylw.html

C#:   class User {}
来源：http://dali.daria6918.cn/Article/details/gt2xvihcdno.html

[G02] 构造函数
来源：http://dali.c1oappe.top/Article/details/gt2byywxytk.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jlsjyb.cn/Article/details/gt2hrwgimlk.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.nanxinkj.top/Article/details/gt2sfrwrooa.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2igvteuhv.html

TS:   constructor(public name: string) {}
来源：http://dali.zhengqikj.top/Article/details/gt2fhalmiqw.html

Java: User(String name) { this.name = name; }
来源：http://dali.yvedp.cn/Article/details/gt2xkfbwhry.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.kuanghao11.cn/Article/details/gt2ikgetaha.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jqgfzy.top/Article/details/gt2czudxgzl.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yongpay.top/Article/details/gt2botnckum.html

[G03] 实例属性
来源：http://dali.guannengcc.top/Article/details/gt2chjoxpek.html

Py:   self.name = "x"
来源：http://dali.0kj1m.cn/Article/details/gt2ojtzrjau.html

PHP:  public string $name = "x";
来源：http://dali.yueranfly.top/Article/details/gt2uyxgfedb.html

JS:   this.name = "x";
来源：http://dali.zhengqikj.top/Article/details/gt2razkoooz.html

TS:   name: string = "x";
来源：http://dali.guannengcc.top/Article/details/gt2nnjcgmel.html

Java: private String name;
来源：http://dali.nwbrower.top/Article/details/gt2hldvgpar.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.tian-w.cn/Article/details/gt2atnlkieh.html

Ruby: @name = "x"
来源：http://dali.ybcxt.top/Article/details/gt2lkgivvua.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.quarkkingdee.top/Article/details/gt2hjrshwag.html

[G04] 定义方法
来源：http://dali.quarkkingdee.top/Article/details/gt2naelkttb.html

Py:   def greet(self): return self.name
来源：http://dali.smart0.xyz/Article/details/gt2jltjfden.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hywenlv.cn/Article/details/gt2jpostnnf.html

JS:   greet() { return this.name; }
来源：http://dali.dianchejie.cn/Article/details/gt2cjxqsblk.html

TS:   greet(): string { return this.name; }
来源：http://dali.bjfxy.top/Article/details/gt2htgeelhn.html

Java: String greet() { return name; }
来源：http://dali.xinyue.icu/Article/details/gt2tezauvkm.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.redwolf501.top/Article/details/gt2oufzxpwl.html

Ruby: def greet; @name; end
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ulainboq.html

C#:   public string Greet() => Name;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iqwzxpgf.html

[G05] 继承
来源：http://dali.yangfankeji.com/Article/details/gt2hbnvugal.html

Py:   class Admin(User): pass
来源：http://dali.sufxvd.cn/Article/details/gt2cehsmgcj.html

PHP:  class Admin extends User {}
来源：http://dali.xziqi.cn/Article/details/gt2obvafpqo.html

JS:   class Admin extends User {}
来源：http://dali.hfpthk.cn/Article/details/gt2kypziwtw.html

TS:   class Admin extends User {}
来源：http://dali.jinqigufen.top/Article/details/gt2spomgors.html

Java: class Admin extends User {}
来源：http://dali.chenlongwang.top/Article/details/gt2lquhdmjm.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.vqdsnc.cn/Article/details/gt2bnqpcvch.html

Ruby: class Admin < User; end
来源：http://dali.guowangkeji.top/Article/details/gt2scubhjzz.html

C#:   class Admin : User {}
来源：http://dali.sysykeji.top/Article/details/gt2fnovvpgn.html

[G06] 重写方法
来源：http://dali.fzhhl.top/Article/details/gt2gmvudjdn.html

Py:   def greet(self): return "admin"
来源：http://dali.wangdashe.top/Article/details/gt2qfracnqy.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2ohbmrepv.html

JS:   greet() { return "admin"; }
来源：http://dali.yj20258888.top/Article/details/gt2qcenogsw.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hysaishi.cn/Article/details/gt2indnzcvv.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.316326.xyz/Article/details/gt2grdwmtlb.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.0kj1m.cn/Article/details/gt2yxsybnlr.html

Ruby: def greet; "admin"; end
来源：http://dali.shzxlz.cn/Article/details/gt2gqaxxyjy.html


<!-- 参考信息 -->