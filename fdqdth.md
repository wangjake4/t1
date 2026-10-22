代发 wailian999

C#:   s.Replace("a", "b")
来源：http://dali.zycfv.cn/Article/details/gt2cfgakqlf.html

[E07] 按分隔符拆分
来源：http://dali.yangfankeji.com/Article/details/gt2kqdrcynr.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.dashuyun.cn/Article/details/gt2ezdyxond.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.hnxiangtu.top/Article/details/gt2jbvtfdfs.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.sysykeji.top/Article/details/gt2fjacnjwi.html

TS:   s.split(",")
来源：http://dali.birdmap.top/Article/details/gt2wfulocfu.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.aibaodan.cn/Article/details/gt2xvnguqfz.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.quarkkingdee.top/Article/details/gt2meuzylow.html

Ruby: s.split(",");  s.split
来源：http://dali.9152youxi.cn/Article/details/gt2ybnbtxaf.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.chenjidiqi.icu/Article/details/gt2mhwrucpz.html

[E08] 数组按分隔符合并
来源：http://dali.0kj1m.cn/Article/details/gt2chxoempe.html

Py:   ",".join(items)
来源：http://dali.hammf.cn/Article/details/gt2nlhypryu.html

PHP:  implode(",", $items);
来源：http://dali.hammf.cn/Article/details/gt2kcrlbxsh.html

JS:   items.join(",")
来源：http://dali.chenzaomai.com/Article/details/gt2snwxafkv.html

TS:   items.join(",")
来源：http://dali.shangyingyoupin.top/Article/details/gt2azevnpji.html

Java: String.join(",", items)
来源：http://dali.redwolf501.top/Article/details/gt2ymacwppo.html

Go:   strings.Join(items, ",")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iewbkqjq.html

Ruby: items.join(",")
来源：http://dali.redwolf501.top/Article/details/gt2zqiffuha.html

C#:   string.Join(",", items)
来源：http://dali.cucudq.cn/Article/details/gt2cqkjknev.html

[E09] 去除所有空白字符
来源：http://dali.yuanzhike.top/Article/details/gt2lpdfamhk.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.aizwys.cn/Article/details/gt2furuulod.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.cashguo.top/Article/details/gt2rugyvbjh.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.hfpthk.cn/Article/details/gt2kxufziuw.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.cdnleiting.top/Article/details/gt2xnjuazst.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.sysykeji.top/Article/details/gt2tnnlvghn.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhixingplan.top/Article/details/gt2abfnlfng.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.dashuyun.cn/Article/details/gt2nmcmqfku.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2smfxlgkk.html

[E10] 左侧补零 / 定长填充
来源：http://dali.hnxiangtu.top/Article/details/gt2xsopwjrr.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.bjfxy.top/Article/details/gt2wczlnnlw.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.vqdsnc.cn/Article/details/gt2cvcjqzqu.html

JS:   "7".padStart(3, "0")
来源：http://dali.feifeiyinyue.top/Article/details/gt2baakqage.html

TS:   "7".padStart(3, "0")
来源：http://dali.iojbl.cn/Article/details/gt2pqposjtf.html

Java: String.format("%03d", 7)
来源：http://dali.ehwqpu.com/Article/details/gt2tlqucasq.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jqgufenzy.top/Article/details/gt2rqdxwjak.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.xylfe.cn/Article/details/gt2jhnykexo.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.sweek.top/Article/details/gt2jnsvagvg.html

[E11] 反转字符串
来源：http://dali.sufxvd.cn/Article/details/gt2coeygsuw.html

Py:   s[::-1]
来源：http://dali.aizwys.cn/Article/details/gt2xupsnuvj.html

PHP:  strrev($s);
来源：http://dali.yj20258888.top/Article/details/gt2noigdnrx.html

JS:   [...s].reverse().join("")
来源：http://dali.dashuyun.cn/Article/details/gt2fpxrisoj.html

TS:   [...s].reverse().join("")
来源：http://dali.meibo888.top/Article/details/gt2btnjasvy.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yj20258.top/Article/details/gt2ncshldxp.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.9152youxi.cn/Article/details/gt2jgqgvbsw.html

Ruby: s.reverse
来源：http://dali.xuanzx.com/Article/details/gt2xfmsoacm.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kgiipttn.html

[E12] 统计某字符出现次数
来源：http://dali.zhixingplan.top/Article/details/gt2thrrjgue.html

Py:   s.count("a")
来源：http://dali.zhiwuduotai.top/Article/details/gt2eycawunk.html

PHP:  substr_count($s, "a");
来源：http://dali.ybcxt.top/Article/details/gt2ivececwg.html

JS:   s.split("a").length - 1
来源：http://dali.jianghu66.top/Article/details/gt2ktohqhmb.html

TS:   s.split("a").length - 1
来源：http://dali.quarkkingdee.top/Article/details/gt2iwkvsshl.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.316326.xyz/Article/details/gt2iejfiucv.html

Go:   strings.Count(s, "a")
来源：http://dali.c1oappe.top/Article/details/gt2oqfakvxl.html

Ruby: s.count("a")
来源：http://dali.dianchejie.cn/Article/details/gt2vhzifvlp.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yuanzhike.top/Article/details/gt2vsntwmrn.html

[E13] 逐字符遍历
来源：http://dali.daria6918.cn/Article/details/gt2wilcvgag.html

Py:   for ch in s: print(ch)
来源：http://dali.nanxinkj.top/Article/details/gt2fdgrerex.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zdqjudy.top/Article/details/gt2uqhhqbtn.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jianghu66.top/Article/details/gt2haawekns.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.svipenyu.cn/Article/details/gt2clyoegwy.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.iojbl.cn/Article/details/gt2swapdnzu.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.quarkkingdee.top/Article/details/gt2owyhtpnn.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bkgklqnp.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.0kj1m.cn/Article/details/gt2vrivtosp.html

[E14] URL 编码与 Base64
来源：http://dali.mhx1999.top/Article/details/gt2qwzwjoku.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.mhx1999.top/Article/details/gt2cjzmuyfc.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.ppjwa.cn/Article/details/gt2ochdhsdc.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.fengsongda.top/Article/details/gt2jurcipno.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.mhx1999.top/Article/details/gt2qibnebhl.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.316326.xyz/Article/details/gt2vtpyayfb.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.snrcjt.cn/Article/details/gt2izcyaewj.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.vqdsnc.cn/Article/details/gt2xdiwtlbx.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yuanzhike.top/Article/details/gt2dilrfzci.html

[E15] HTML 转义 / 反转义
来源：http://dali.0kj1m.cn/Article/details/gt2aucnxrgx.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.fzhhl.top/Article/details/gt2clrofemo.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.daria6918.cn/Article/details/gt2xsyochml.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.dashuyun.cn/Article/details/gt2heppegrq.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yj20258.top/Article/details/gt2atpazpoh.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.wangshuangyany.cn/Article/details/gt2wvmrwinl.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jianghu66.top/Article/details/gt2tiwbshda.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.316326.xyz/Article/details/gt2nltwpmvo.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhengqikj.top/Article/details/gt2iypbkmwa.html

[E16] 数字千分位
来源：http://dali.shuidangran.top/Article/details/gt2pswsftrf.html

Py:   f"{1234567:,}"
来源：http://dali.yangfankeji.com/Article/details/gt2rwofqgnv.html

PHP:  number_format(1234567);
来源：http://dali.yuxming.cn/Article/details/gt2rvwrlpmt.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.hnqzz.top/Article/details/gt2mslouvik.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.sweek.top/Article/details/gt2xcqoapkx.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.feifeiyinyue.top/Article/details/gt2roirphpy.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.fengsongda.top/Article/details/gt2aswqbccy.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.nanxinkj.top/Article/details/gt2hswshjgs.html

C#:   1234567.ToString("N0")
来源：http://dali.xuanzx.com/Article/details/gt2kodqogxd.html

[E17] 首字母大写
来源：http://dali.xylfe.cn/Article/details/gt2orpskcjg.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.dashuyun.cn/Article/details/gt2ewwoxpfc.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jyoumei.cn/Article/details/gt2maezvfcj.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xziqi.cn/Article/details/gt2lhrcmfsc.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.quarkkingdee.top/Article/details/gt2otqztlta.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.andypj.xyz/Article/details/gt2hkfzfjty.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.mhx1999.top/Article/details/gt2rzbacnfm.html

Ruby: s.capitalize
来源：http://dali.bjfxy.top/Article/details/gt2rlydzajy.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.dianchejie.cn/Article/details/gt2anfhptqr.html

[E18] 模板占位符替换
来源：http://dali.yonumen.top/Article/details/gt2rtmcsabn.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yanxiufei.cn/Article/details/gt2nuycsiso.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.ybcxt.top/Article/details/gt2mzghpsqa.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yonumen.top/Article/details/gt2ggnfurcy.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.sweek.top/Article/details/gt2cuueanrx.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hammf.cn/Article/details/gt2mgwlsroo.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jianghu66.top/Article/details/gt2xkhnzsmm.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhoulong.xyz/Article/details/gt2gsuqcoks.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.aizwys.cn/Article/details/gt2hzildurk.html

[E19] 多行文本按行拆分
来源：http://dali.shuidangran.top/Article/details/gt2fzfgolcs.html

Py:   s.splitlines()
来源：http://dali.nwbrower.top/Article/details/gt2sknwlqrs.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.andypj.xyz/Article/details/gt2qxmsdvys.html

JS:   s.split(/\r?\n/)
来源：http://dali.gogol.net.cn/Article/details/gt2yaozdokw.html

TS:   s.split(/\r?\n/)
来源：http://dali.birdmap.top/Article/details/gt2rfuaohyq.html

Java: s.lines().toList()
来源：http://dali.jyoumei.cn/Article/details/gt2jzaicfdq.html

Go:   strings.Split(s, "\n")
来源：http://dali.gaohongyu789.top/Article/details/gt2vndrmpvy.html

Ruby: s.lines
来源：http://dali.kuanghao11.cn/Article/details/gt2mbxgnpyp.html

C#:   s.Split('\n')
来源：http://dali.aibaodan.cn/Article/details/gt2bvvslsiw.html

[E20] 判断字符串是否为空
来源：http://dali.guowangkeji.top/Article/details/gt2zqilpfjy.html

Py:   if not s:
来源：http://dali.cashguo.top/Article/details/gt2rdkxzoma.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.cheryme.top/Article/details/gt2uhbhcvhe.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yj20258.top/Article/details/gt2hxmyscaf.html

TS:   if (s === "") {}
来源：http://dali.xuanzx.com/Article/details/gt2slmzxkhl.html

Java: if (s.isEmpty()) {}
来源：http://dali.hnqzz.top/Article/details/gt2fypcurmj.html

Go:   if s == "" {}
来源：http://dali.xuanzx.com/Article/details/gt2rwmtximy.html

Ruby: if s.empty?
来源：http://dali.xinyue.icu/Article/details/gt2jyetrnvz.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2ssexigvp.html

[E21] 超长截断加省略号
来源：http://dali.ybcxt.top/Article/details/gt2gsndfilx.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.cucudq.cn/Article/details/gt2gyzzuwxq.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mtrqvnbn.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.redwolf501.top/Article/details/gt2lvpuacrp.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yj20258888.top/Article/details/gt2pnmnbkri.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2keueywhu.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2sfoqxkzn.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.sysykeji.top/Article/details/gt2zoanyztj.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.pycfn.com/Article/details/gt2ligtgdsn.html

[E22] 字节长度与字符长度
来源：http://dali.jqgufenzy.top/Article/details/gt2ifasxgkh.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.c1oappe.top/Article/details/gt2gsjddnbc.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.daxiang520.top/Article/details/gt2pvtugzad.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yongpay.top/Article/details/gt2tbdchgdq.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xziqi.cn/Article/details/gt2fecxbrvb.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.sweek.top/Article/details/gt2giqvjuty.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.dashuyun.cn/Article/details/gt2vcvqpmgr.html

Ruby: s.bytesize;  s.length
来源：http://dali.yongpay.top/Article/details/gt2ohceggxr.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.hammf.cn/Article/details/gt2eakfrpfa.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2enututsi.html

F. 文件与目录
来源：http://dali.hnxiangtu.top/Article/details/gt2cayczwna.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2ifgcandc.html

[F01] 读取整个文件
来源：http://dali.jqgfzy.top/Article/details/gt2jsoopnux.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jinqigfzy.top/Article/details/gt2iruyzzue.html

PHP:  file_get_contents("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gt2sovlzcft.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.sxryk.cn/Article/details/gt2ehsijahu.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.kuanghao11.cn/Article/details/gt2uvkbmccu.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.tian-w.cn/Article/details/gt2tbkcbcfb.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yj20258888.top/Article/details/gt2vefzhefx.html

Ruby: File.read("a.txt")
来源：http://dali.wangdashe.top/Article/details/gt2rbqeiwur.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.nwbrower.top/Article/details/gt2efbicozp.html

[F02] 逐行读取文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bqvbxzmk.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.shzxlz.cn/Article/details/gt2dtbrskhq.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xuanzx.com/Article/details/gt2odfpltio.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.smart0.xyz/Article/details/gt2fnuwhelq.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2unaydtul.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.quarkkingdee.top/Article/details/gt2zyhjwbri.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.nanxuanxn.top/Article/details/gt2jpjjupxb.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.xuanzx.com/Article/details/gt2wooyptvv.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.gogol.net.cn/Article/details/gt2kahlgzbd.html

[F03] 写入文件（覆盖）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pifccoos.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.c1oappe.top/Article/details/gt2plmjeona.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2tzwshjhb.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.fengsongda.top/Article/details/gt2tiyozjtz.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.vqdsnc.cn/Article/details/gt2sgbeysvd.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.tianlin.xyz/Article/details/gt2avvtjhzy.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.9152youxi.cn/Article/details/gt2hrjxitqx.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yongpay.top/Article/details/gt2yhohzqpb.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yanxiufei.cn/Article/details/gt2vcuphkgd.html

[F04] 追加写入文件
来源：http://dali.svipenyu.cn/Article/details/gt2jzhpugzm.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jinqigufen.top/Article/details/gt2bvgfwnlj.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xylfe.cn/Article/details/gt2clukxqie.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sufxvd.cn/Article/details/gt2fbgckctf.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dopjwebh.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hongshengwenyu.top/Article/details/gt2dziqjcco.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.snrcjt.cn/Article/details/gt2isydlcll.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.9152youxi.cn/Article/details/gt2sastlhhz.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.pycfn.com/Article/details/gt2rcmzbskj.html

[F05] 判断文件或目录是否存在
来源：http://dali.hysaishi.cn/Article/details/gt2nczzxgtb.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.kuanghao11.cn/Article/details/gt2abbzbldn.html

PHP:  file_exists("a.txt");
来源：http://dali.aizwys.cn/Article/details/gt2rojfoxui.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2wmwfnekf.html

TS:   fs.existsSync("a.txt")
来源：http://dali.sysykeji.top/Article/details/gt2bvhcbyui.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.birdmap.top/Article/details/gt2dhvmqdow.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ppjwa.cn/Article/details/gt2iwxwmhmf.html

Ruby: File.exist?("a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2wrndulmx.html

C#:   File.Exists("a.txt")
来源：http://dali.birdmap.top/Article/details/gt2jtydifzm.html

[F06] 删除文件
来源：http://dali.nanxuanxn.top/Article/details/gt2rifbfavy.html

Py:   os.remove("a.txt")
来源：http://dali.bjfxy.top/Article/details/gt2cyqsatyi.html

PHP:  unlink("a.txt");
来源：http://dali.wangdashe.top/Article/details/gt2njtbrqdh.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.pycfn.com/Article/details/gt2wzmxbmvk.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yj20258.top/Article/details/gt2rrfzkgqz.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.guowangkeji.top/Article/details/gt2eezfkogc.html

Go:   os.Remove("a.txt")
来源：http://dali.sweek.top/Article/details/gt2oerirqcy.html

Ruby: File.delete("a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2jdiazotr.html

C#:   File.Delete("a.txt");
来源：http://dali.daria6918.cn/Article/details/gt2tozelgba.html

[F07] 创建目录（含多级）
来源：http://dali.vqdsnc.cn/Article/details/gt2wqhgnydm.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.9152youxi.cn/Article/details/gt2lgiezdiz.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xziqi.cn/Article/details/gt2eluxizjs.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.pycfn.com/Article/details/gt2wnolzwcq.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.guowangkeji.top/Article/details/gt2gdwjpeuw.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hywenlv.cn/Article/details/gt2dmokutld.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yj20258.top/Article/details/gt2evskpxtw.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hfpthk.cn/Article/details/gt2iiytcbhh.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.guannengcc.top/Article/details/gt2udegdtxb.html

[F08] 遍历目录
来源：http://dali.chenzaomai.com/Article/details/gt2dptpargf.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yj20258888.top/Article/details/gt2dkmbnqnf.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.fengsongda.top/Article/details/gt2mswjpqpv.html

JS:   fs.readdirSync("dir")
来源：http://dali.aibaodan.cn/Article/details/gt2rmkhbkzu.html

TS:   fs.readdirSync("dir")
来源：http://dali.gogol.net.cn/Article/details/gt2ysrefkyd.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.gogol.net.cn/Article/details/gt2mqonthtn.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.guannengcc.top/Article/details/gt2ozuqkwkv.html

Ruby: Dir.children("dir")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2anjvsypr.html

C#:   Directory.GetFiles("dir")
来源：http://dali.kuanghao11.cn/Article/details/gt2uqchitve.html

[F09] 获取文件大小
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vtouqddr.html

Py:   os.path.getsize("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2whzvdnzz.html

PHP:  filesize("a.txt");
来源：http://dali.hnqzz.top/Article/details/gt2ixseetcf.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jqgfzy.top/Article/details/gt2znhufifu.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zycfv.cn/Article/details/gt2omofleqc.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bjjacubr.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hysaishi.cn/Article/details/gt2svcukshk.html

Ruby: File.size("a.txt")
来源：http://dali.sweek.top/Article/details/gt2axuiwfdj.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hysaishi.cn/Article/details/gt2xhyvbmbh.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.shzxlz.cn/Article/details/gt2ylakovvk.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2fmuwoaqu.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zycfv.cn/Article/details/gt2jglmcwom.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2qrntvlpe.html

TS:   path.extname("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wgoxrmzu.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yj20258888.top/Article/details/gt2weqgwoxl.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2pakldgbg.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2ngpfuurm.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.bjfxy.top/Article/details/gt2zxxcdvku.html

[F11] 复制与移动文件
来源：http://dali.guowangkeji.top/Article/details/gt2eyvlgxqr.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2hvlpfuxy.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yuxming.cn/Article/details/gt2jkxzidgc.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.bjfxy.top/Article/details/gt2ivrdmgiy.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2rczzpepj.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hnqzz.top/Article/details/gt2skoadwex.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.quarkkingdee.top/Article/details/gt2xrzivnix.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2ctwpockt.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.nanxinkj.top/Article/details/gt2qmgceete.html

[F12] CSV 读写
来源：http://dali.svipenyu.cn/Article/details/gt2anqpmuge.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hywenlv.cn/Article/details/gt2tdxrsubh.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.sufxvd.cn/Article/details/gt2jbwarvsa.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.pycfn.com/Article/details/gt2majgcxhw.html

TS:   // 同上
来源：http://dali.hnqzz.top/Article/details/gt2pcabkiwn.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xuanzx.com/Article/details/gt2eycgdrmv.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xinyue.icu/Article/details/gt2lcdmgagm.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ydzc1.top/Article/details/gt2ajjvrbfd.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.guowangkeji.top/Article/details/gt2vzztqckj.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2wwdsemds.html

G. 面向对象
来源：http://dali.0kj1m.cn/Article/details/gt2wtlapumi.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2thygavgz.html

[G01] 定义类
来源：http://dali.yangfankeji.com/Article/details/gt2cwwnuyos.html

Py:   class User: pass
来源：http://dali.yj20258.top/Article/details/gt2gpqnvggc.html

PHP:  class User {}
来源：http://dali.havefunace.top/Article/details/gt2acbkvgzb.html

JS:   class User {}
来源：http://dali.zhengqikj.top/Article/details/gt2tktgrrfg.html

TS:   class User { name: string = ""; }
来源：http://dali.yuanzhike.top/Article/details/gt2flrzafvi.html

Java: class User {}
来源：http://dali.mhx1999.top/Article/details/gt2prtoeoql.html

Go:   type User struct { Name string }
来源：http://dali.wangshuangyany.cn/Article/details/gt2iirzzazx.html

Ruby: class User; end
来源：http://dali.yongpay.top/Article/details/gt2abpybqwd.html

C#:   class User {}
来源：http://dali.dianchejie.cn/Article/details/gt2ajrmutwq.html

[G02] 构造函数
来源：http://dali.ppjwa.cn/Article/details/gt2rtsajopi.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.ppjwa.cn/Article/details/gt2ioaopoox.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zycfv.cn/Article/details/gt2afeaqumd.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yj20258888.top/Article/details/gt2fihupsud.html

TS:   constructor(public name: string) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2sbtpzumj.html

Java: User(String name) { this.name = name; }
来源：http://dali.smart0.xyz/Article/details/gt2applsnya.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.316326.xyz/Article/details/gt2hucbycdv.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.sxryk.cn/Article/details/gt2poervkls.html

C#:   public User(string name) { Name = name; }
来源：http://dali.cqqwz.cn/Article/details/gt2jvjecalw.html

[G03] 实例属性
来源：http://dali.ybcxt.top/Article/details/gt2liqjmjzx.html

Py:   self.name = "x"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uksxmsok.html

PHP:  public string $name = "x";
来源：http://dali.yongpay.top/Article/details/gt2eqpjxotf.html

JS:   this.name = "x";
来源：http://dali.havefunace.top/Article/details/gt2uioesybp.html

TS:   name: string = "x";
来源：http://dali.yj202588.top/Article/details/gt2colmaaqs.html

Java: private String name;
来源：http://dali.fzhhl.top/Article/details/gt2qmujkrki.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.wangshuangyany.cn/Article/details/gt2usjmdifl.html

Ruby: @name = "x"
来源：http://dali.nanxuanxn.top/Article/details/gt2pbokbvrn.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.dashuyun.cn/Article/details/gt2meovmyvn.html

[G04] 定义方法
来源：http://dali.wangdashe.top/Article/details/gt2xaasmbgn.html

Py:   def greet(self): return self.name
来源：http://dali.chenlongwang.top/Article/details/gt2nvlthocc.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jiagoushi.top/Article/details/gt2orgacobd.html

JS:   greet() { return this.name; }
来源：http://dali.haohaochexian.top/Article/details/gt2ayzjxejs.html

TS:   greet(): string { return this.name; }
来源：http://dali.meibo888.top/Article/details/gt2skuvojzn.html

Java: String greet() { return name; }
来源：http://dali.jyoumei.cn/Article/details/gt2urespbxb.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.shangyingyoupin.top/Article/details/gt2uwktlpoo.html

Ruby: def greet; @name; end
来源：http://dali.ybcxt.top/Article/details/gt2llixqvfd.html

C#:   public string Greet() => Name;
来源：http://dali.wangdashe.top/Article/details/gt2rwcupuuq.html

[G05] 继承
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mteabrsl.html

Py:   class Admin(User): pass
来源：http://dali.jinqigfzy.top/Article/details/gt2cmpjnohh.html

PHP:  class Admin extends User {}
来源：http://dali.316326.xyz/Article/details/gt2swzmoeut.html

JS:   class Admin extends User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zcuwzkad.html

TS:   class Admin extends User {}
来源：http://dali.gaohongyu789.top/Article/details/gt2qbiwxugt.html


<!-- 参考信息 -->