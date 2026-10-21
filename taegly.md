代发 wailian999

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtypguoraw.html

E. 字符串处理
来源：http://dali.hfpthk.cn/Article/details/gtjdcloymm.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtnsvrhpws.html

[E01] 拼接字符串
来源：http://dali.hnxiangtu.top/Article/details/gtinjpvxca.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.aibaodan.cn/Article/details/gtxfhhxnrl.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.birdmap.top/Article/details/gtbxgaeask.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinqigufen.top/Article/details/gtkaugjvyr.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yj20258888.top/Article/details/gtbcmkrybv.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.haohaochexian.top/Article/details/gtgtturhei.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.wangshuangyany.cn/Article/details/gtfxfzzrjv.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jyoumei.cn/Article/details/gtqlpxgjxb.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gtnyxmkese.html

[E02] 重复字符串
来源：http://dali.sysykeji.top/Article/details/gtmnscukbt.html

Py:   "ab" * 3
来源：http://dali.chenlongwang.top/Article/details/gtjrocegub.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhiwuduotai.top/Article/details/gtfyazpguq.html

JS:   "ab".repeat(3)
来源：http://dali.zhixingplan.top/Article/details/gtacqwognw.html

TS:   "ab".repeat(3)
来源：http://dali.yuxming.cn/Article/details/gtnlhdbtzk.html

Java: "ab".repeat(3)
来源：http://dali.hywenlv.cn/Article/details/gteokvdesr.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.andypj.xyz/Article/details/gtuwpcfceb.html

Ruby: "ab" * 3
来源：http://dali.jyoumei.cn/Article/details/gtebsascku.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.ppjwa.cn/Article/details/gtqfnhdqoy.html

[E03] 截取子串
来源：http://dali.zdqjudy.top/Article/details/gtmsjiyaro.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.gotoacloud.top/Article/details/gtdohddylv.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.shanyushiyangtech.top/Article/details/gtacslachw.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.birdmap.top/Article/details/gtaiodhxeh.html

TS:   s.slice(1, 4)
来源：http://dali.snrcjt.cn/Article/details/gtqbnxinkh.html

Java: s.substring(1, 4)
来源：http://dali.zdqjudy.top/Article/details/gtvszrndsv.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.wangshuangyany.cn/Article/details/gtzdkycmdn.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyxaxlkht.html

C#:   s.Substring(1, 3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcrrfqkuu.html

[E04] 查找子串位置
来源：http://dali.pengpengdd.cyou/Article/details/gtzbesjiqk.html

Py:   s.find("x");  s.index("x")
来源：http://dali.ppjwa.cn/Article/details/gtrdzdavwf.html

PHP:  strpos($s, "x");
来源：http://dali.316326.xyz/Article/details/gtifwunsrd.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yj202588.top/Article/details/gtmwnrgctw.html

TS:   s.indexOf("x")
来源：http://dali.wangdashe.top/Article/details/gtxzewkxfl.html

Java: s.indexOf("x")
来源：http://dali.hongshengwenyu.top/Article/details/gtmraisqtb.html

Go:   strings.Index(s, "x")
来源：http://dali.yj20258888.top/Article/details/gtwklrzzwh.html

Ruby: s.index("x")
来源：http://dali.hammf.cn/Article/details/gtkpbrdkfg.html

C#:   s.IndexOf("x")
来源：http://dali.hfpthk.cn/Article/details/gtusopznmy.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.iojbl.cn/Article/details/gteoffkayn.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhoulong.xyz/Article/details/gtyspufosp.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthuxwaugt.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xuetiantiany.cn/Article/details/gttlfweieg.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.hongshengwenyu.top/Article/details/gtpmyunjus.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yongpay.top/Article/details/gtjeyylpce.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jianghu66.top/Article/details/gtpxoykjvg.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yj202588.top/Article/details/gtsyyaawfc.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.guowangkeji.top/Article/details/gtvdtwhbvm.html

[E06] 替换子串
来源：http://dali.dashuyun.cn/Article/details/gtnpeknmba.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jinqigfzy.top/Article/details/gtmwmbdcxb.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.iojbl.cn/Article/details/gtuzwaamco.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hywenlv.cn/Article/details/gtknaqaaus.html

TS:   s.replaceAll("a", "b")
来源：http://dali.daxiang520.top/Article/details/gtiekljyqk.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.nwbrower.top/Article/details/gtewhpggyf.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.hfpthk.cn/Article/details/gtsgchmgbj.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jiagoushi.top/Article/details/gtjucvgjmz.html

C#:   s.Replace("a", "b")
来源：http://dali.hnxiangtu.top/Article/details/gtazfxuniz.html

[E07] 按分隔符拆分
来源：http://dali.daxiang520.top/Article/details/gtuunoqtsn.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.316326.xyz/Article/details/gtcraklbeu.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.gotoacloud.top/Article/details/gtrtwmxvlu.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.svipenyu.cn/Article/details/gtsgzouzdv.html

TS:   s.split(",")
来源：http://dali.jianghu66.top/Article/details/gtouedsvma.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yj20258.top/Article/details/gtqghoycot.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yanxiufei.cn/Article/details/gtilscuuwu.html

Ruby: s.split(",");  s.split
来源：http://dali.sxryk.cn/Article/details/gtljioljrl.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhoulong.xyz/Article/details/gtujfcaitt.html

[E08] 数组按分隔符合并
来源：http://dali.hnxiangtu.top/Article/details/gtmbsqebgs.html

Py:   ",".join(items)
来源：http://dali.jianghu66.top/Article/details/gthbmoksjp.html

PHP:  implode(",", $items);
来源：http://dali.redwolf501.top/Article/details/gtwajshmcf.html

JS:   items.join(",")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgwfxllmk.html

TS:   items.join(",")
来源：http://dali.zhoulong.xyz/Article/details/gtduckkzzd.html

Java: String.join(",", items)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuolqsyow.html

Go:   strings.Join(items, ",")
来源：http://dali.xinyue.icu/Article/details/gtszsbgqdj.html

Ruby: items.join(",")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcgpknyaz.html

C#:   string.Join(",", items)
来源：http://dali.hongshengwenyu.top/Article/details/gthrmvrkaz.html

[E09] 去除所有空白字符
来源：http://dali.pengpengdd.cyou/Article/details/gtevynfjld.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.cdnleiting.top/Article/details/gtxpayhlze.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.xuetiantiany.cn/Article/details/gtghlivvxk.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.daxiang520.top/Article/details/gtwdulbbsg.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.cdnleiting.top/Article/details/gtofkbgebq.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.gzhubu.top/Article/details/gtrlipuhwl.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.svipenyu.cn/Article/details/gteslqmyuw.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yongpay.top/Article/details/gtlpwpmlwb.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yj202588.top/Article/details/gtflhfvvrc.html

[E10] 左侧补零 / 定长填充
来源：http://dali.shzxlz.cn/Article/details/gturkhkqbo.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.wangshuangyany.cn/Article/details/gtwslmyxub.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zycfv.cn/Article/details/gtirifmthm.html

JS:   "7".padStart(3, "0")
来源：http://dali.jinghuilouyu.cn/Article/details/gtvwchrfmc.html

TS:   "7".padStart(3, "0")
来源：http://dali.nanxuanxn.top/Article/details/gtqdbzmysc.html

Java: String.format("%03d", 7)
来源：http://dali.pengpengdd.cyou/Article/details/gtmpdmrdlc.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhixingplan.top/Article/details/gtijgkznzf.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.xinyue.icu/Article/details/gtksfaaiph.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.316326.xyz/Article/details/gtdntkrkqi.html

[E11] 反转字符串
来源：http://dali.ydzc1.top/Article/details/gtqjqgwomb.html

Py:   s[::-1]
来源：http://dali.feifeiyinyue.top/Article/details/gtfzlxnrjb.html

PHP:  strrev($s);
来源：http://dali.zhengqikj.top/Article/details/gtsjijhlrn.html

JS:   [...s].reverse().join("")
来源：http://dali.jianghu66.top/Article/details/gtaogvkeqd.html

TS:   [...s].reverse().join("")
来源：http://dali.haohaochexian.top/Article/details/gtsztbyzpr.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.cheryme.top/Article/details/gtepmiufco.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.0kj1m.cn/Article/details/gtmdrfatvt.html

Ruby: s.reverse
来源：http://dali.shanyushiyangtech.top/Article/details/gtjgnlsees.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.0kj1m.cn/Article/details/gtqnyzjisp.html

[E12] 统计某字符出现次数
来源：http://dali.tanke756.top/Article/details/gtsdmlmmuz.html

Py:   s.count("a")
来源：http://dali.cheryme.top/Article/details/gtsihpbzly.html

PHP:  substr_count($s, "a");
来源：http://dali.shzxlz.cn/Article/details/gtitgawljd.html

JS:   s.split("a").length - 1
来源：http://dali.wangdashe.top/Article/details/gtkrotniiv.html

TS:   s.split("a").length - 1
来源：http://dali.jinghuilouyu.cn/Article/details/gtzicmxnev.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.nanxinkj.top/Article/details/gttevjhtbx.html

Go:   strings.Count(s, "a")
来源：http://dali.hysaishi.cn/Article/details/gtylqqjdqn.html

Ruby: s.count("a")
来源：http://dali.jiagoushi.top/Article/details/gtuhazfkfn.html

C#:   s.Count(c => c == 'a')
来源：http://dali.sxryk.cn/Article/details/gtqrkswiph.html

[E13] 逐字符遍历
来源：http://dali.xuetiantiany.cn/Article/details/gtqmtohazb.html

Py:   for ch in s: print(ch)
来源：http://dali.redwolf501.top/Article/details/gttxvltkai.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.svipenyu.cn/Article/details/gtdynhhshr.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jianghu66.top/Article/details/gtibdmpkbv.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zdqjudy.top/Article/details/gtqplxofgt.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jiagoushi.top/Article/details/gtbvfziekk.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.havefunace.top/Article/details/gtqvsscgbz.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.chenjidiqi.icu/Article/details/gtbwaxiwiz.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.aibaodan.cn/Article/details/gtrjsxscgn.html

[E14] URL 编码与 Base64
来源：http://dali.sufxvd.cn/Article/details/gtolqrhazl.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yuanzhike.top/Article/details/gtxbmeicqu.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.c1oappe.top/Article/details/gtpkadymwc.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.chenzaomai.com/Article/details/gtqqvkjxno.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.guowangkeji.top/Article/details/gtotqmhnvt.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.xziqi.cn/Article/details/gtjwqwmwgh.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.aizwys.cn/Article/details/gtdqittwkr.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hysaishi.cn/Article/details/gtjuotsbtw.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zdqjudy.top/Article/details/gtuorpmmop.html

[E15] HTML 转义 / 反转义
来源：http://dali.yj202588.top/Article/details/gtcmhsbhdu.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.redwolf501.top/Article/details/gtztpwffwh.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.0kj1m.cn/Article/details/gtkaumnmrl.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.birdmap.top/Article/details/gtjohpdlzs.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.daria6918.cn/Article/details/gtmwpnmftl.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.kuanghao11.cn/Article/details/gtowuesrlk.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrvqaekao.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.ydzc1.top/Article/details/gtxxwbpbip.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.ivvv.top/Article/details/gtggwkvagm.html

[E16] 数字千分位
来源：http://dali.shangyingyoupin.top/Article/details/gtgukdnsix.html

Py:   f"{1234567:,}"
来源：http://dali.jiagoushi.top/Article/details/gtjokdapkb.html

PHP:  number_format(1234567);
来源：http://dali.andypj.xyz/Article/details/gtdrobhzax.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yuanzhike.top/Article/details/gtxiqfwxcn.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yj20258888.top/Article/details/gtphquhmil.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zdqjudy.top/Article/details/gtuegigwjw.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.guannengcc.top/Article/details/gtfvqhyrip.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfdwlnxen.html

C#:   1234567.ToString("N0")
来源：http://dali.kuanghao11.cn/Article/details/gttdbxjiis.html

[E17] 首字母大写
来源：http://dali.jinqigfzy.top/Article/details/gtkdahqoav.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.9152youxi.cn/Article/details/gtqfmucoux.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jlsjyb.cn/Article/details/gtlnzeyfmr.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.mhx1999.top/Article/details/gtscujpkwz.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zycfv.cn/Article/details/gtnjggzlcn.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbjuluewi.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.hammf.cn/Article/details/gtatvvqpqd.html

Ruby: s.capitalize
来源：http://dali.yj202588.top/Article/details/gtckxoumpz.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhiwuduotai.top/Article/details/gtcsybetwh.html

[E18] 模板占位符替换
来源：http://dali.ydzc1.top/Article/details/gttcepkkjj.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.316326.xyz/Article/details/gtpnwhbmek.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hnxiangtu.top/Article/details/gtubxtpatu.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.ydzc1.top/Article/details/gtagcezzkg.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.cheryme.top/Article/details/gtpwvwxhdk.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.vqdsnc.cn/Article/details/gtpznvlyza.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.gzhubu.top/Article/details/gttnouhsnn.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.ydzc1.top/Article/details/gtdkwehzpg.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.9152youxi.cn/Article/details/gtldnzaqau.html

[E19] 多行文本按行拆分
来源：http://dali.cucudq.cn/Article/details/gthntyzzir.html

Py:   s.splitlines()
来源：http://dali.nanxinkj.top/Article/details/gtnhdhzgye.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.daria6918.cn/Article/details/gticexdnhq.html

JS:   s.split(/\r?\n/)
来源：http://dali.hnqzz.top/Article/details/gtgudvuteb.html

TS:   s.split(/\r?\n/)
来源：http://dali.yangfankeji.com/Article/details/gtueylvifw.html

Java: s.lines().toList()
来源：http://dali.jiagoushi.top/Article/details/gtikhivpbn.html

Go:   strings.Split(s, "\n")
来源：http://dali.andypj.xyz/Article/details/gtavoaltgd.html

Ruby: s.lines
来源：http://dali.yongpay.top/Article/details/gtodeznrki.html

C#:   s.Split('\n')
来源：http://dali.hnqzz.top/Article/details/gtdpidlqqq.html

[E20] 判断字符串是否为空
来源：http://dali.zycfv.cn/Article/details/gtttqrypye.html

Py:   if not s:
来源：http://dali.yueranfly.top/Article/details/gtrpsyriuy.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.cashguo.top/Article/details/gtsextznqe.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtihimfitd.html

TS:   if (s === "") {}
来源：http://dali.jiagoushi.top/Article/details/gtnjjvjjar.html

Java: if (s.isEmpty()) {}
来源：http://dali.hnqzz.top/Article/details/gtkiqmltzc.html

Go:   if s == "" {}
来源：http://dali.jqgfzy.top/Article/details/gteqyslzei.html

Ruby: if s.empty?
来源：http://dali.pengpengdd.cyou/Article/details/gtxxneqnzy.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhongyouzk.top/Article/details/gtuneppslx.html

[E21] 超长截断加省略号
来源：http://dali.shanyushiyangtech.top/Article/details/gtuyejnufo.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.cashguo.top/Article/details/gtunlnjdpg.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxgfcfpqz.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.tanke756.top/Article/details/gtcyxoafip.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hnqzz.top/Article/details/gteatoaqsu.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.cdnleiting.top/Article/details/gtjjdckyrz.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhixingplan.top/Article/details/gtkumxkpvx.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.nanxinkj.top/Article/details/gtmqrvlsry.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.wangdashe.top/Article/details/gtyrwlymgk.html

[E22] 字节长度与字符长度
来源：http://dali.jinghuilouyu.cn/Article/details/gttqiuzjnk.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.guowangkeji.top/Article/details/gtrsaqijnd.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.chenzaomai.com/Article/details/gtfjiuwdnj.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hysaishi.cn/Article/details/gtsbmxyfmd.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhixingplan.top/Article/details/gtaujopqju.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zycfv.cn/Article/details/gttrtxdfmv.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yj20258.top/Article/details/gtqeymlfyu.html

Ruby: s.bytesize;  s.length
来源：http://dali.jinghuilouyu.cn/Article/details/gthcrmwuwq.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhongyouzk.top/Article/details/gtwljjvmze.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtzkehwrkv.html

F. 文件与目录
来源：http://dali.mhx1999.top/Article/details/gtxxvkbewk.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtqynnznqx.html

[F01] 读取整个文件
来源：http://dali.jqgufenzy.top/Article/details/gtqsmxhabv.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.pengpengdd.cyou/Article/details/gtlbuaowel.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yj20258888.top/Article/details/gteulxjvkp.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhoulong.xyz/Article/details/gtsijvlfpx.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.havefunace.top/Article/details/gtxkvecgfd.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjtknouro.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jyoumei.cn/Article/details/gtisdxirvn.html

Ruby: File.read("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtwapcpyog.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdbpbfdjv.html

[F02] 逐行读取文件
来源：http://dali.fengsongda.top/Article/details/gtxxhetiqx.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yj20258888.top/Article/details/gtvmwqwyru.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.kuanghao11.cn/Article/details/gtaryanmel.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.tian-w.cn/Article/details/gtjmqiqqps.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jqgfzy.top/Article/details/gtokvscbuj.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ppjwa.cn/Article/details/gtojbkoaxl.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.birdmap.top/Article/details/gtrgvztftj.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.ydzc1.top/Article/details/gtddwpxdtf.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.pengpengdd.cyou/Article/details/gtgjzwkwlj.html

[F03] 写入文件（覆盖）
来源：http://dali.yuxming.cn/Article/details/gtdurxcpac.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.mhx1999.top/Article/details/gtjtrvyhle.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.cashguo.top/Article/details/gtlmmdbdfq.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.wangshuangyany.cn/Article/details/gtbdnwrant.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyzezlhps.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jinqigfzy.top/Article/details/gtxrxaqppj.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.dianchejie.cn/Article/details/gtxeaillrj.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.daria6918.cn/Article/details/gtzqgjpoyg.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.daxiang520.top/Article/details/gtengwbuto.html

[F04] 追加写入文件
来源：http://dali.redwolf501.top/Article/details/gteojxncya.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hnxiangtu.top/Article/details/gtvrzbuxgq.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.smart0.xyz/Article/details/gtmuuawwfc.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.redwolf501.top/Article/details/gtgaerovlq.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cheryme.top/Article/details/gtpqevtwob.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.wangshuangyany.cn/Article/details/gtrrvegvlq.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yanxiufei.cn/Article/details/gtwtpwtyak.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhixingplan.top/Article/details/gtfdhjezlk.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jlsjyb.cn/Article/details/gtkdstbque.html

[F05] 判断文件或目录是否存在
来源：http://dali.xinyue.icu/Article/details/gtojtiuozg.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.smart0.xyz/Article/details/gtsaydxejd.html

PHP:  file_exists("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlemarjvm.html

JS:   fs.existsSync("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtimfoiuaa.html

TS:   fs.existsSync("a.txt")
来源：http://dali.tian-w.cn/Article/details/gteltjticq.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jianghu66.top/Article/details/gtxhxwveqg.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.316326.xyz/Article/details/gtpbrufbav.html

Ruby: File.exist?("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtrbzkimwk.html

C#:   File.Exists("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtpjwkekak.html

[F06] 删除文件
来源：http://dali.dashuyun.cn/Article/details/gtkhbbvdvv.html

Py:   os.remove("a.txt")
来源：http://dali.yongpay.top/Article/details/gtjdvtchlk.html

PHP:  unlink("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtssojflyd.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtyplgpfvv.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ivvv.top/Article/details/gtntzmzlss.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jianghu66.top/Article/details/gtsjofbyau.html

Go:   os.Remove("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtjgkqcfhn.html

Ruby: File.delete("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtdifybmop.html

C#:   File.Delete("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gthvqbpuox.html

[F07] 创建目录（含多级）
来源：http://dali.hfpthk.cn/Article/details/gtuegvvlnf.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.feifeiyinyue.top/Article/details/gtsggngset.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hfpthk.cn/Article/details/gtaqngepoq.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.guowangkeji.top/Article/details/gtywvyuiqa.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hongshengwenyu.top/Article/details/gtporforab.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.daria6918.cn/Article/details/gtwkcesmey.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.bjfxy.top/Article/details/gtwlkjrdek.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yuanzhike.top/Article/details/gtzedpoqaa.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hammf.cn/Article/details/gtvmsnqjoq.html

[F08] 遍历目录
来源：http://dali.jinqigfzy.top/Article/details/gttpnhnwva.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.0kj1m.cn/Article/details/gtdgdihval.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.cashguo.top/Article/details/gttixcdeyt.html

JS:   fs.readdirSync("dir")
来源：http://dali.mhx1999.top/Article/details/gtaztgkjzn.html

TS:   fs.readdirSync("dir")
来源：http://dali.pycfn.com/Article/details/gtuxoujjuz.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.haohaochexian.top/Article/details/gtjwnjbihr.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.daxiang520.top/Article/details/gticnqchhp.html

Ruby: Dir.children("dir")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgtelvwsc.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hammf.cn/Article/details/gtriedcucu.html

[F09] 获取文件大小
来源：http://dali.haohaochexian.top/Article/details/gtrmgqdnuq.html

Py:   os.path.getsize("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtemnwwsub.html

PHP:  filesize("a.txt");
来源：http://dali.yuxming.cn/Article/details/gtddndhlyk.html

JS:   fs.statSync("a.txt").size
来源：http://dali.dianchejie.cn/Article/details/gtpvgbsfeg.html

TS:   fs.statSync("a.txt").size
来源：http://dali.guowangkeji.top/Article/details/gtecutjeuj.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.nanxuanxn.top/Article/details/gtthnbksri.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jqgufenzy.top/Article/details/gtyhsdaywy.html

Ruby: File.size("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtjcipyzjq.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.shzxlz.cn/Article/details/gtqtzxqniz.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.guowangkeji.top/Article/details/gtdmzyjnhq.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xziqi.cn/Article/details/gtbmfoxoiw.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.mhx1999.top/Article/details/gtxxusjdlk.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtpjkdvcho.html

TS:   path.extname("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtfrpgxgjz.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.aizwys.cn/Article/details/gttpmipije.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtcpxzgsew.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.andypj.xyz/Article/details/gtvftslzuo.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtouyqkmbo.html

[F11] 复制与移动文件
来源：http://dali.wangshuangyany.cn/Article/details/gtyclunenf.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yongpay.top/Article/details/gtzfaitigh.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.cqqwz.cn/Article/details/gtlvvjtbni.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jyoumei.cn/Article/details/gtoeoshbpz.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj20258888.top/Article/details/gtphaazbtl.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yangfankeji.com/Article/details/gtxxezyiki.html


<!-- 参考信息 -->