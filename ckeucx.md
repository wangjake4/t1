代发 wailian999

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.tanke756.top/Article/details/gtgwhyahsb.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.guannengcc.top/Article/details/gtnsmpiaeh.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shangyingyoupin.top/Article/details/gtmmsifcjn.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.birdmap.top/Article/details/gtyqmvwlub.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhoulong.xyz/Article/details/gtubtcoeiz.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.wangdashe.top/Article/details/gtyfydeoae.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.ivvv.top/Article/details/gteahyobxx.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yj202588.top/Article/details/gtoydhzrkk.html

[E06] 替换子串
来源：http://dali.sweek.top/Article/details/gtecgrljnx.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgyafsoar.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.kuanghao11.cn/Article/details/gtlotygloe.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrflvoexy.html

TS:   s.replaceAll("a", "b")
来源：http://dali.vqdsnc.cn/Article/details/gtupiwfejs.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jianghu66.top/Article/details/gtdfkigktt.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.hnxiangtu.top/Article/details/gtaacckxzn.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.ivvv.top/Article/details/gtjxurpknt.html

C#:   s.Replace("a", "b")
来源：http://dali.sufxvd.cn/Article/details/gtjrdkrowy.html

[E07] 按分隔符拆分
来源：http://dali.pycfn.com/Article/details/gtjqzbcxdj.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsvhubrol.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtobutffwu.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.wangshuangyany.cn/Article/details/gtgbgiwpuu.html

TS:   s.split(",")
来源：http://dali.jinqigufen.top/Article/details/gtpizughwv.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.svipenyu.cn/Article/details/gtbhdjmvsf.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.dashuyun.cn/Article/details/gtkjpybbhy.html

Ruby: s.split(",");  s.split
来源：http://dali.pengpengdd.cyou/Article/details/gthpirgwpu.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.iojbl.cn/Article/details/gtzzoobgji.html

[E08] 数组按分隔符合并
来源：http://dali.yangfankeji.com/Article/details/gtlwrbsnzb.html

Py:   ",".join(items)
来源：http://dali.iojbl.cn/Article/details/gtqobcwtnn.html

PHP:  implode(",", $items);
来源：http://dali.ybcxt.top/Article/details/gtitnghuet.html

JS:   items.join(",")
来源：http://dali.chenzaomai.com/Article/details/gtjmcwnmji.html

TS:   items.join(",")
来源：http://dali.jiagoushi.top/Article/details/gtkasyefji.html

Java: String.join(",", items)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthxlxjgkd.html

Go:   strings.Join(items, ",")
来源：http://dali.hammf.cn/Article/details/gtyuxmpuqw.html

Ruby: items.join(",")
来源：http://dali.hfpthk.cn/Article/details/gtrtqcurlx.html

C#:   string.Join(",", items)
来源：http://dali.yanxiufei.cn/Article/details/gtaotqmadp.html

[E09] 去除所有空白字符
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzlrnmrnn.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.dianchejie.cn/Article/details/gtlfwvmxgo.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gtkppnkmbk.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.tianlin.xyz/Article/details/gtbjqxwhis.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hammf.cn/Article/details/gtkqgacphv.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.dianchejie.cn/Article/details/gtlqfwvgpf.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yanxiufei.cn/Article/details/gtuufprrdu.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.ivvv.top/Article/details/gtafdqztve.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.316326.xyz/Article/details/gtcesjvhab.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jinqigfzy.top/Article/details/gtenxfjdvx.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.bjfxy.top/Article/details/gtsidorjye.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yanxiufei.cn/Article/details/gtifyircty.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhixingplan.top/Article/details/gteycyijdf.html

TS:   "7".padStart(3, "0")
来源：http://dali.nanxuanxn.top/Article/details/gtcuprmmeo.html

Java: String.format("%03d", 7)
来源：http://dali.quarkkingdee.top/Article/details/gtttlggaew.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.pycfn.com/Article/details/gtjlgrbnpr.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yangfankeji.com/Article/details/gtegarirok.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.fengsongda.top/Article/details/gtycvmwjdw.html

[E11] 反转字符串
来源：http://dali.ppjwa.cn/Article/details/gtypwrwfvt.html

Py:   s[::-1]
来源：http://dali.cdnleiting.top/Article/details/gtovqucqqx.html

PHP:  strrev($s);
来源：http://dali.jianghu66.top/Article/details/gtwlesxjsl.html

JS:   [...s].reverse().join("")
来源：http://dali.nanxinkj.top/Article/details/gtcotkmjlf.html

TS:   [...s].reverse().join("")
来源：http://dali.zycfv.cn/Article/details/gtntwncbuj.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hysaishi.cn/Article/details/gtjzljbcuk.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yj202588.top/Article/details/gtcoyxeknx.html

Ruby: s.reverse
来源：http://dali.sxryk.cn/Article/details/gthfhnzcxg.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.wangshuangyany.cn/Article/details/gtfqsmtwrk.html

[E12] 统计某字符出现次数
来源：http://dali.sweek.top/Article/details/gtubtfywgn.html

Py:   s.count("a")
来源：http://dali.zhixingplan.top/Article/details/gthiqseuvg.html

PHP:  substr_count($s, "a");
来源：http://dali.meibo888.top/Article/details/gtmvxncjei.html

JS:   s.split("a").length - 1
来源：http://dali.hfpthk.cn/Article/details/gtjxrwkwvj.html

TS:   s.split("a").length - 1
来源：http://dali.hongshengwenyu.top/Article/details/gtpijkiirk.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jinqigfzy.top/Article/details/gtbbqqspnn.html

Go:   strings.Count(s, "a")
来源：http://dali.cheryme.top/Article/details/gtmgigexsa.html

Ruby: s.count("a")
来源：http://dali.zhongyouzk.top/Article/details/gtfkqaovmw.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhixingplan.top/Article/details/gtnviopiqn.html

[E13] 逐字符遍历
来源：http://dali.ehwqpu.com/Article/details/gtnqkkstht.html

Py:   for ch in s: print(ch)
来源：http://dali.yj20258.top/Article/details/gttaumhcfg.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.aibaodan.cn/Article/details/gtsavqasbp.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtbrnrlpgq.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.quarkkingdee.top/Article/details/gtgxmhxglt.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.aizwys.cn/Article/details/gtrlrdpvyj.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.aizwys.cn/Article/details/gtfwncffkf.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.haohaochexian.top/Article/details/gtwbtwugqb.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.xinyue.icu/Article/details/gtubfntwaq.html

[E14] URL 编码与 Base64
来源：http://dali.gzhubu.top/Article/details/gtbqcjruqj.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yj20258888.top/Article/details/gtaqmztjee.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jinqigufen.top/Article/details/gtqhjzykkm.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jqgfzy.top/Article/details/gtdvnfxbwn.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.dashuyun.cn/Article/details/gtozqdycmn.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.ehwqpu.com/Article/details/gtkfcstevq.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yangfankeji.com/Article/details/gthwhzxhef.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhiwuduotai.top/Article/details/gtiaontvnh.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.sweek.top/Article/details/gtffcwgnta.html

[E15] HTML 转义 / 反转义
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoujueejt.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jlsjyb.cn/Article/details/gtboxihjyh.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhixingplan.top/Article/details/gtzclalhci.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.cucudq.cn/Article/details/gtrvbjgezf.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.cashguo.top/Article/details/gtwjwxepeh.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.havefunace.top/Article/details/gtuzwkunko.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.dianchejie.cn/Article/details/gtisyuwnzy.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.sufxvd.cn/Article/details/gtcpydrbtt.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yanxiufei.cn/Article/details/gtwdmzkoom.html

[E16] 数字千分位
来源：http://dali.zhengqikj.top/Article/details/gtabguvkeq.html

Py:   f"{1234567:,}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gthwfjjsjr.html

PHP:  number_format(1234567);
来源：http://dali.guannengcc.top/Article/details/gtzfzkkccu.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.meibo888.top/Article/details/gtjuljkxhk.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinqigfzy.top/Article/details/gtbypgvfjr.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yj202588.top/Article/details/gtsonjhiij.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhixingplan.top/Article/details/gtndrewrkx.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yangfankeji.com/Article/details/gtfzgstntt.html

C#:   1234567.ToString("N0")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcnnijptu.html

[E17] 首字母大写
来源：http://dali.kuanghao11.cn/Article/details/gtamxxxyxo.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yvedp.cn/Article/details/gthdabknmz.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yj202588.top/Article/details/gtkzuvurzr.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jqgufenzy.top/Article/details/gtkbgvcxqt.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jianghu66.top/Article/details/gtgoagyxnu.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.smart0.xyz/Article/details/gtqhhqdhdm.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.316326.xyz/Article/details/gtdlkmydfl.html

Ruby: s.capitalize
来源：http://dali.c1oappe.top/Article/details/gtwumzebkc.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.xziqi.cn/Article/details/gtrctddvqy.html

[E18] 模板占位符替换
来源：http://dali.andypj.xyz/Article/details/gtjdunwgwl.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hnqzz.top/Article/details/gtjwizifth.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhengqikj.top/Article/details/gthmygwxyg.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.snrcjt.cn/Article/details/gtdwvmbeju.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.sxryk.cn/Article/details/gtujwciotg.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.cdnleiting.top/Article/details/gtdmztzhco.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.fengsongda.top/Article/details/gtepvpibhe.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.316326.xyz/Article/details/gtlhogfwlh.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.dianchejie.cn/Article/details/gtyqelwzdf.html

[E19] 多行文本按行拆分
来源：http://dali.snrcjt.cn/Article/details/gtgjlofiua.html

Py:   s.splitlines()
来源：http://dali.yanxiufei.cn/Article/details/gtdltaxypa.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.andypj.xyz/Article/details/gtcsxjfoef.html

JS:   s.split(/\r?\n/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxlexhvvd.html

TS:   s.split(/\r?\n/)
来源：http://dali.jlsjyb.cn/Article/details/gtptdvsfdk.html

Java: s.lines().toList()
来源：http://dali.316326.xyz/Article/details/gtdouvhbzn.html

Go:   strings.Split(s, "\n")
来源：http://dali.zycfv.cn/Article/details/gtworgjoaj.html

Ruby: s.lines
来源：http://dali.vqdsnc.cn/Article/details/gtqpjtybml.html

C#:   s.Split('\n')
来源：http://dali.jqgfzy.top/Article/details/gtmsljwgzl.html

[E20] 判断字符串是否为空
来源：http://dali.mhx1999.top/Article/details/gtiouccdqt.html

Py:   if not s:
来源：http://dali.nanxinkj.top/Article/details/gtpcxiieex.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhongyouzk.top/Article/details/gtesircxrb.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.cheryme.top/Article/details/gtbvhqmedt.html

TS:   if (s === "") {}
来源：http://dali.bjfxy.top/Article/details/gtltlyvrbr.html

Java: if (s.isEmpty()) {}
来源：http://dali.kuanghao11.cn/Article/details/gtykvcivvb.html

Go:   if s == "" {}
来源：http://dali.yj20258888.top/Article/details/gtgvtfkexc.html

Ruby: if s.empty?
来源：http://dali.jiagoushi.top/Article/details/gtcvrnzfug.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.gogol.net.cn/Article/details/gttqbeslxe.html

[E21] 超长截断加省略号
来源：http://dali.gaohongyu789.top/Article/details/gtxazgwndq.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.aibaodan.cn/Article/details/gtsbwaqklf.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hysaishi.cn/Article/details/gtoaxiuecb.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hammf.cn/Article/details/gtvnzjidyr.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.iojbl.cn/Article/details/gtsvggjsru.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zycfv.cn/Article/details/gtqsjnehth.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.pengpengdd.cyou/Article/details/gtkyrtilrg.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.0kj1m.cn/Article/details/gtarpwyenp.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhiwuduotai.top/Article/details/gthfnravvl.html

[E22] 字节长度与字符长度
来源：http://dali.havefunace.top/Article/details/gtwvrkqvic.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.andypj.xyz/Article/details/gtvxmsdlog.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xuetiantiany.cn/Article/details/gtnuyfewti.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zdqjudy.top/Article/details/gtjwwqkaxa.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hnxiangtu.top/Article/details/gtxfiymlpr.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yangfankeji.com/Article/details/gtqwcfymfe.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.feifeiyinyue.top/Article/details/gtdscoxwzm.html

Ruby: s.bytesize;  s.length
来源：http://dali.fzhhl.top/Article/details/gtqpllfcxk.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.shuidangran.top/Article/details/gtotshenrd.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkdddnict.html

F. 文件与目录
来源：http://dali.sufxvd.cn/Article/details/gtxvwqndif.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtvdsgeqpb.html

[F01] 读取整个文件
来源：http://dali.shangyingyoupin.top/Article/details/gtamzivfvv.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtejymvmev.html

PHP:  file_get_contents("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtsbvwexfh.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.sxryk.cn/Article/details/gtcguqvtoq.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.andypj.xyz/Article/details/gtpkywaofi.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.wangdashe.top/Article/details/gtwicmecfq.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.feifeiyinyue.top/Article/details/gtwikxdkfa.html

Ruby: File.read("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtimtjopjc.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yueranfly.top/Article/details/gtrgfjfnzh.html

[F02] 逐行读取文件
来源：http://dali.xziqi.cn/Article/details/gtnheopyny.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.svipenyu.cn/Article/details/gtegvgveik.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.nanxuanxn.top/Article/details/gtsobsdbiz.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shuidangran.top/Article/details/gtunpxxedw.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.redwolf501.top/Article/details/gtbcnbzlmz.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.feifeiyinyue.top/Article/details/gtudfbqtwd.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.wangdashe.top/Article/details/gtwlypqagj.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yvedp.cn/Article/details/gtwnqzmywe.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.cqqwz.cn/Article/details/gtejldeqhg.html

[F03] 写入文件（覆盖）
来源：http://dali.sysykeji.top/Article/details/gtvdikxlby.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jlsjyb.cn/Article/details/gtebkhgzku.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ppjwa.cn/Article/details/gtncaxxzyy.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.chenlongwang.top/Article/details/gtsunenajv.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zycfv.cn/Article/details/gtjxexopbo.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhixingplan.top/Article/details/gtawdzdyka.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.sufxvd.cn/Article/details/gtlezpouwi.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.iojbl.cn/Article/details/gtslezbcsw.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.wangshuangyany.cn/Article/details/gtctskrtwm.html

[F04] 追加写入文件
来源：http://dali.xinyue.icu/Article/details/gtrbavkjcz.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.vqdsnc.cn/Article/details/gteboyznej.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.havefunace.top/Article/details/gtyibnfuqp.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shangyingyoupin.top/Article/details/gtaiqcwkef.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.bjfxy.top/Article/details/gtfdikikce.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yongpay.top/Article/details/gtawarugfn.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.birdmap.top/Article/details/gtgfrsvogd.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.sweek.top/Article/details/gttcqxpmxq.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.vqdsnc.cn/Article/details/gtbqzuxmus.html

[F05] 判断文件或目录是否存在
来源：http://dali.yanxiufei.cn/Article/details/gtdmknesxs.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.nwbrower.top/Article/details/gtyjwiizsw.html

PHP:  file_exists("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtytzfyekc.html

JS:   fs.existsSync("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtjqeoiuvl.html

TS:   fs.existsSync("a.txt")
来源：http://dali.redwolf501.top/Article/details/gthfxbqsob.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hysaishi.cn/Article/details/gtudrrwuht.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.kuanghao11.cn/Article/details/gtwxnldmrr.html

Ruby: File.exist?("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtyshmmwyu.html

C#:   File.Exists("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdeoefhjz.html

[F06] 删除文件
来源：http://dali.tanke756.top/Article/details/gtbjpszqff.html

Py:   os.remove("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtihsvmdha.html

PHP:  unlink("a.txt");
来源：http://dali.daria6918.cn/Article/details/gtwcygizfr.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtspaczumw.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtomgfmrli.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.9152youxi.cn/Article/details/gtdtnvtfyb.html

Go:   os.Remove("a.txt")
来源：http://dali.cheryme.top/Article/details/gtxjqfrwic.html

Ruby: File.delete("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtevpqvejp.html

C#:   File.Delete("a.txt");
来源：http://dali.gzhubu.top/Article/details/gtjekocvyi.html

[F07] 创建目录（含多级）
来源：http://dali.snrcjt.cn/Article/details/gtonvwbycq.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hywenlv.cn/Article/details/gtbyvtudrp.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jqgufenzy.top/Article/details/gtjlbqkvbl.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shuidangran.top/Article/details/gtyjnadfzf.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hnqzz.top/Article/details/gtcpfeowtx.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhongyouzk.top/Article/details/gtaprlqxkj.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xylfe.cn/Article/details/gtcakpspjy.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yj20258888.top/Article/details/gtuatkmnrb.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xinyue.icu/Article/details/gtecldyrqm.html

[F08] 遍历目录
来源：http://dali.sweek.top/Article/details/gtqnfkxezh.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.fengsongda.top/Article/details/gtrnswnyce.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.mhx1999.top/Article/details/gtkdhhncoc.html

JS:   fs.readdirSync("dir")
来源：http://dali.jyoumei.cn/Article/details/gtdmlmunkn.html

TS:   fs.readdirSync("dir")
来源：http://dali.sufxvd.cn/Article/details/gtsbmxbftm.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.vqdsnc.cn/Article/details/gttmfguist.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.nanxinkj.top/Article/details/gtegbkjimm.html

Ruby: Dir.children("dir")
来源：http://dali.zdqjudy.top/Article/details/gttphcgcal.html

C#:   Directory.GetFiles("dir")
来源：http://dali.shuidangran.top/Article/details/gtqfrymmgv.html

[F09] 获取文件大小
来源：http://dali.xuetiantiany.cn/Article/details/gtcdpmfykt.html

Py:   os.path.getsize("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtwjxetaqd.html

PHP:  filesize("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcisxmmav.html

JS:   fs.statSync("a.txt").size
来源：http://dali.haohaochexian.top/Article/details/gtdkveotqa.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhixingplan.top/Article/details/gtqdkrcgvi.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.bjfxy.top/Article/details/gtzhdtwpuq.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.andypj.xyz/Article/details/gtrneajoyo.html

Ruby: File.size("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtwudogbmw.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jinqigufen.top/Article/details/gtcrfpkghp.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xinyue.icu/Article/details/gtinaxlyfr.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.pycfn.com/Article/details/gtqydqfvzn.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.gotoacloud.top/Article/details/gtoeyfnzqg.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xylfe.cn/Article/details/gtnyagsrtr.html

TS:   path.extname("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtkvqxuyfs.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.0kj1m.cn/Article/details/gtukwyxzvb.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtivybpwjr.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtjdlmalll.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtaywbvbqr.html

[F11] 复制与移动文件
来源：http://dali.redwolf501.top/Article/details/gthktegbgn.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xuanzx.com/Article/details/gtdlgxtygp.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.ydzc1.top/Article/details/gtkswgpyvr.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.svipenyu.cn/Article/details/gtuehmnqca.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.tianlin.xyz/Article/details/gtqcszgyrl.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hnxiangtu.top/Article/details/gtrbajmheb.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yvedp.cn/Article/details/gtihwssify.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.gotoacloud.top/Article/details/gtedlkhsjy.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xziqi.cn/Article/details/gtivdsbouk.html

[F12] CSV 读写
来源：http://dali.jinqigufen.top/Article/details/gturrssvsm.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gtpsfwycpm.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.tanke756.top/Article/details/gtigibljjt.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jinqigufen.top/Article/details/gtqudlzqwn.html

TS:   // 同上
来源：http://dali.nanxuanxn.top/Article/details/gthuvvcmcv.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.tanke756.top/Article/details/gtbbryyfgi.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhoulong.xyz/Article/details/gtdroqhzqk.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.shanyushiyangtech.top/Article/details/gtvfrgoykl.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hywenlv.cn/Article/details/gtjgtubuee.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtpgwqjdrf.html

G. 面向对象
来源：http://dali.9152youxi.cn/Article/details/gtninkhlfu.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtbgijkzwx.html

[G01] 定义类
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqjcixpst.html

Py:   class User: pass
来源：http://dali.chenzaomai.com/Article/details/gtgphoiuvu.html

PHP:  class User {}
来源：http://dali.havefunace.top/Article/details/gtmmbsdpgz.html

JS:   class User {}
来源：http://dali.gzhubu.top/Article/details/gtpmizhwec.html

TS:   class User { name: string = ""; }
来源：http://dali.sweek.top/Article/details/gtvftfhmvo.html

Java: class User {}
来源：http://dali.hammf.cn/Article/details/gtibgioada.html

Go:   type User struct { Name string }
来源：http://dali.ivvv.top/Article/details/gteqdsavfm.html

Ruby: class User; end
来源：http://dali.iojbl.cn/Article/details/gtajfzirso.html

C#:   class User {}
来源：http://dali.chenlongwang.top/Article/details/gtscjmurrh.html

[G02] 构造函数
来源：http://dali.havefunace.top/Article/details/gttwdnuihj.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.birdmap.top/Article/details/gttixvefot.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.dianchejie.cn/Article/details/gtdyldcgwm.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.quarkkingdee.top/Article/details/gtcchqwxgi.html

TS:   constructor(public name: string) {}
来源：http://dali.yangfankeji.com/Article/details/gtoivzrbax.html

Java: User(String name) { this.name = name; }
来源：http://dali.shzxlz.cn/Article/details/gtqraddqko.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.9152youxi.cn/Article/details/gtzwlvniix.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.wangshuangyany.cn/Article/details/gtnrqwpbbr.html

C#:   public User(string name) { Name = name; }
来源：http://dali.nanxinkj.top/Article/details/gterdhhkwt.html

[G03] 实例属性
来源：http://dali.chenjidiqi.icu/Article/details/gtnamjewxd.html

Py:   self.name = "x"
来源：http://dali.sweek.top/Article/details/gtxpbidndw.html

PHP:  public string $name = "x";
来源：http://dali.nanxinkj.top/Article/details/gtjdjaobdz.html

JS:   this.name = "x";
来源：http://dali.hnqzz.top/Article/details/gtkwsoqszb.html

TS:   name: string = "x";
来源：http://dali.yuanzhike.top/Article/details/gtgvwbvuuh.html

Java: private String name;
来源：http://dali.shanyushiyangtech.top/Article/details/gtsdozygtq.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.quarkkingdee.top/Article/details/gtpsffkxxo.html


<!-- 参考信息 -->