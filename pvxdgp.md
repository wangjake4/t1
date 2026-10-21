代发 wailian999

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yj202588.top/Article/details/gtfnleccbd.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jinqigfzy.top/Article/details/gtvmuzwuhr.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yuanzhike.top/Article/details/gtrnepjkfk.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.9152youxi.cn/Article/details/gtvjvgpuyq.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.xuanzx.com/Article/details/gtkedqstoq.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.ybcxt.top/Article/details/gtufqtlptu.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.c1oappe.top/Article/details/gtigjdxjsj.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.shzxlz.cn/Article/details/gtjlgifczv.html

[E02] 重复字符串
来源：http://dali.jqgufenzy.top/Article/details/gtnnlzesdk.html

Py:   "ab" * 3
来源：http://dali.yueranfly.top/Article/details/gthjwapscm.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gtrunysizm.html

JS:   "ab".repeat(3)
来源：http://dali.birdmap.top/Article/details/gtntuonsbm.html

TS:   "ab".repeat(3)
来源：http://dali.c1oappe.top/Article/details/gtpostjiwh.html

Java: "ab".repeat(3)
来源：http://dali.vqdsnc.cn/Article/details/gtkohfmfry.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.dianchejie.cn/Article/details/gtiudwcxri.html

Ruby: "ab" * 3
来源：http://dali.pengpengdd.cyou/Article/details/gtqvehbjcu.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yuxming.cn/Article/details/gtmgjeuzyu.html

[E03] 截取子串
来源：http://dali.shuidangran.top/Article/details/gtqotlcgaa.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.sweek.top/Article/details/gtajpqmikl.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.guannengcc.top/Article/details/gtlppitmyg.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.ehwqpu.com/Article/details/gttyovqqcn.html

TS:   s.slice(1, 4)
来源：http://dali.yuxming.cn/Article/details/gtwcqozfrc.html

Java: s.substring(1, 4)
来源：http://dali.zhiwuduotai.top/Article/details/gtjpcifuxb.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yj202588.top/Article/details/gtugiezxcy.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.feifeiyinyue.top/Article/details/gtopesjkvy.html

C#:   s.Substring(1, 3)
来源：http://dali.svipenyu.cn/Article/details/gteeiaktad.html

[E04] 查找子串位置
来源：http://dali.zhixingplan.top/Article/details/gteurnoyob.html

Py:   s.find("x");  s.index("x")
来源：http://dali.shzxlz.cn/Article/details/gtcoktwilz.html

PHP:  strpos($s, "x");
来源：http://dali.xziqi.cn/Article/details/gtjrbddehg.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhoulong.xyz/Article/details/gtmozdqdhm.html

TS:   s.indexOf("x")
来源：http://dali.hammf.cn/Article/details/gtptfeezrd.html

Java: s.indexOf("x")
来源：http://dali.yanxiufei.cn/Article/details/gtwdtcjxta.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gtetmkqerk.html

Ruby: s.index("x")
来源：http://dali.tianlin.xyz/Article/details/gtrgqikfjo.html

C#:   s.IndexOf("x")
来源：http://dali.jianghu66.top/Article/details/gtjiujarto.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.shzxlz.cn/Article/details/gtpjattxuu.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yanxiufei.cn/Article/details/gtgrqfrsqq.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.xziqi.cn/Article/details/gtfuvxnrss.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrbtexfrx.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yj20258888.top/Article/details/gtnlmpygnw.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yj202588.top/Article/details/gthevubnkl.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.cdnleiting.top/Article/details/gtyyudhwtk.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yanxiufei.cn/Article/details/gtzalgmlyr.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.cashguo.top/Article/details/gtoqlnhdzo.html

[E06] 替换子串
来源：http://dali.cucudq.cn/Article/details/gtsnmfrher.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yj20258888.top/Article/details/gtvdqkjbbe.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.feifeiyinyue.top/Article/details/gtqrzarahc.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.fengsongda.top/Article/details/gtcvpmskei.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zdqjudy.top/Article/details/gtpuvjjhbn.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gtdsecccuc.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jlsjyb.cn/Article/details/gtfxtowbxr.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yuanzhike.top/Article/details/gtxtztzoiy.html

C#:   s.Replace("a", "b")
来源：http://dali.hongshengwenyu.top/Article/details/gttquvuvof.html

[E07] 按分隔符拆分
来源：http://dali.feifeiyinyue.top/Article/details/gtwaogupld.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.nanxinkj.top/Article/details/gtxeudswbp.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.aibaodan.cn/Article/details/gtexussuuk.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.sxryk.cn/Article/details/gtozptievl.html

TS:   s.split(",")
来源：http://dali.shzxlz.cn/Article/details/gtiannulxz.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhixingplan.top/Article/details/gtivxjyzbp.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.mhx1999.top/Article/details/gttuabkzjp.html

Ruby: s.split(",");  s.split
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmpxdokni.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.guannengcc.top/Article/details/gtvqangmbw.html

[E08] 数组按分隔符合并
来源：http://dali.chenjidiqi.icu/Article/details/gtntetrqph.html

Py:   ",".join(items)
来源：http://dali.vqdsnc.cn/Article/details/gthmczputi.html

PHP:  implode(",", $items);
来源：http://dali.cqqwz.cn/Article/details/gtlgfiwmqz.html

JS:   items.join(",")
来源：http://dali.gogol.net.cn/Article/details/gtwhpfrrvt.html

TS:   items.join(",")
来源：http://dali.jyoumei.cn/Article/details/gtpfastqxp.html

Java: String.join(",", items)
来源：http://dali.ppjwa.cn/Article/details/gtqyfwcggc.html

Go:   strings.Join(items, ",")
来源：http://dali.zycfv.cn/Article/details/gtpylprkyp.html

Ruby: items.join(",")
来源：http://dali.mhx1999.top/Article/details/gtdesllzko.html

C#:   string.Join(",", items)
来源：http://dali.fengsongda.top/Article/details/gtkywwkzhb.html

[E09] 去除所有空白字符
来源：http://dali.gzhubu.top/Article/details/gtvtgepdtn.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.redwolf501.top/Article/details/gtcbaoqbkt.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zdqjudy.top/Article/details/gtcbubjnaj.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.0kj1m.cn/Article/details/gtkfbndfcs.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.dashuyun.cn/Article/details/gtngqukccp.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.gotoacloud.top/Article/details/gtryhuhzod.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.ydzc1.top/Article/details/gttlntuzrs.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.xuetiantiany.cn/Article/details/gtahodqbwu.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yuanzhike.top/Article/details/gthywzfbis.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhaomingkeji.xyz/Article/details/gtesienhtj.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.guannengcc.top/Article/details/gtvnptrvfm.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yueranfly.top/Article/details/gtadyqwvxk.html

JS:   "7".padStart(3, "0")
来源：http://dali.xuanzx.com/Article/details/gtwnoulrhz.html

TS:   "7".padStart(3, "0")
来源：http://dali.shanyushiyangtech.top/Article/details/gtbwjzbevy.html

Java: String.format("%03d", 7)
来源：http://dali.zycfv.cn/Article/details/gtwqehclix.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.dashuyun.cn/Article/details/gtyeupsoez.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.gaohongyu789.top/Article/details/gtwcxkmbqg.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.birdmap.top/Article/details/gtbmkcqlzz.html

[E11] 反转字符串
来源：http://dali.snrcjt.cn/Article/details/gteqjedmxz.html

Py:   s[::-1]
来源：http://dali.tianlin.xyz/Article/details/gtgqhovdvh.html

PHP:  strrev($s);
来源：http://dali.ybcxt.top/Article/details/gtetxfjpfy.html

JS:   [...s].reverse().join("")
来源：http://dali.jiagoushi.top/Article/details/gtpzqngqsp.html

TS:   [...s].reverse().join("")
来源：http://dali.meibo888.top/Article/details/gtvcmwtomk.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zdqjudy.top/Article/details/gtbrcjlbqm.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.cheryme.top/Article/details/gttsogdkzp.html

Ruby: s.reverse
来源：http://dali.nanxinkj.top/Article/details/gtpkisqsdc.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.andypj.xyz/Article/details/gtusgcnvav.html

[E12] 统计某字符出现次数
来源：http://dali.tianlin.xyz/Article/details/gtgmlabsbd.html

Py:   s.count("a")
来源：http://dali.andypj.xyz/Article/details/gtrumvosup.html

PHP:  substr_count($s, "a");
来源：http://dali.nwbrower.top/Article/details/gthqypagze.html

JS:   s.split("a").length - 1
来源：http://dali.aizwys.cn/Article/details/gtamlbmftx.html

TS:   s.split("a").length - 1
来源：http://dali.yuanzhike.top/Article/details/gtzrcinaue.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.hysaishi.cn/Article/details/gtynvfnxrp.html

Go:   strings.Count(s, "a")
来源：http://dali.daria6918.cn/Article/details/gtpfnolmtc.html

Ruby: s.count("a")
来源：http://dali.c1oappe.top/Article/details/gtdqinohpq.html

C#:   s.Count(c => c == 'a')
来源：http://dali.cucudq.cn/Article/details/gtgzycnunc.html

[E13] 逐字符遍历
来源：http://dali.zhongyouzk.top/Article/details/gtorzonlwx.html

Py:   for ch in s: print(ch)
来源：http://dali.cucudq.cn/Article/details/gtqtwrrvbv.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.cucudq.cn/Article/details/gtiocemibk.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ivvv.top/Article/details/gtqusgxjgd.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gaohongyu789.top/Article/details/gtvqonhmdm.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.ybcxt.top/Article/details/gtkuipusfl.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.vqdsnc.cn/Article/details/gtnqufurzz.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hnqzz.top/Article/details/gtmxwmdroo.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.iojbl.cn/Article/details/gtzoyaclwv.html

[E14] URL 编码与 Base64
来源：http://dali.jiagoushi.top/Article/details/gtiluajfbi.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hnqzz.top/Article/details/gtorrqwnmp.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yangfankeji.com/Article/details/gtzdzvwsui.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yangfankeji.com/Article/details/gttzosuwnm.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.andypj.xyz/Article/details/gtynolxumr.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.guannengcc.top/Article/details/gtqxsqnrin.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.xuetiantiany.cn/Article/details/gtqsljzjsp.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.gaohongyu789.top/Article/details/gthgdbkcuk.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.tanke756.top/Article/details/gtbaofyavn.html

[E15] HTML 转义 / 反转义
来源：http://dali.yongpay.top/Article/details/gtchclfvoy.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.0kj1m.cn/Article/details/gttdgebray.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.wangdashe.top/Article/details/gtdeawzkqs.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.chenzaomai.com/Article/details/gtyepstzkq.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.gogol.net.cn/Article/details/gtqgqmmpne.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gtptpxwgvy.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yj202588.top/Article/details/gtfoypevie.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.cqqwz.cn/Article/details/gtppeloblp.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yanxiufei.cn/Article/details/gtbjnnsysf.html

[E16] 数字千分位
来源：http://dali.chenlongwang.top/Article/details/gtrmteuxld.html

Py:   f"{1234567:,}"
来源：http://dali.zhongyouzk.top/Article/details/gtoyncdzjm.html

PHP:  number_format(1234567);
来源：http://dali.wangshuangyany.cn/Article/details/gtskhetxsx.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.aibaodan.cn/Article/details/gtitbacsvp.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.cqqwz.cn/Article/details/gtrrvyzppb.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.bjfxy.top/Article/details/gtirjwksho.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.ivvv.top/Article/details/gtbzhmyoug.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hfpthk.cn/Article/details/gtonhrtwqu.html

C#:   1234567.ToString("N0")
来源：http://dali.tanke756.top/Article/details/gtmxcdsrjg.html

[E17] 首字母大写
来源：http://dali.gzhubu.top/Article/details/gtsrmrhzji.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ivvv.top/Article/details/gtvhgzmofn.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hammf.cn/Article/details/gtcfvhbdls.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xuanzx.com/Article/details/gtkeeiwupv.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj20258.top/Article/details/gtzwfrparx.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtavpflyiv.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jinqigfzy.top/Article/details/gtwchwfnag.html

Ruby: s.capitalize
来源：http://dali.andypj.xyz/Article/details/gtzledjwri.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.fengsongda.top/Article/details/gtgwuytmgz.html

[E18] 模板占位符替换
来源：http://dali.jinqigufen.top/Article/details/gtquqypgfx.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.nanxuanxn.top/Article/details/gttupyshgt.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.c1oappe.top/Article/details/gtducfwmnx.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hysaishi.cn/Article/details/gteioigsel.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yj20258888.top/Article/details/gtooglilta.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.daria6918.cn/Article/details/gtaowxpafj.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.9152youxi.cn/Article/details/gthdxwmuqm.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhoulong.xyz/Article/details/gtgbckbbwd.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.chenjidiqi.icu/Article/details/gtevroxetp.html

[E19] 多行文本按行拆分
来源：http://dali.bjfxy.top/Article/details/gtysiaowuk.html

Py:   s.splitlines()
来源：http://dali.tian-w.cn/Article/details/gtufpaaime.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtbbefmowo.html

JS:   s.split(/\r?\n/)
来源：http://dali.chenlongwang.top/Article/details/gttngrbsbt.html

TS:   s.split(/\r?\n/)
来源：http://dali.meibo888.top/Article/details/gtvjxbqhji.html

Java: s.lines().toList()
来源：http://dali.tanke756.top/Article/details/gtvmpifzhu.html

Go:   strings.Split(s, "\n")
来源：http://dali.ehwqpu.com/Article/details/gtijurycej.html

Ruby: s.lines
来源：http://dali.pycfn.com/Article/details/gtcqahkgrg.html

C#:   s.Split('\n')
来源：http://dali.cashguo.top/Article/details/gtmsjvalbt.html

[E20] 判断字符串是否为空
来源：http://dali.ppjwa.cn/Article/details/gtmyovxofi.html

Py:   if not s:
来源：http://dali.snrcjt.cn/Article/details/gtimehoesv.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhengqikj.top/Article/details/gtwjozvewn.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.tianlin.xyz/Article/details/gtzznbuhmx.html

TS:   if (s === "") {}
来源：http://dali.yuxming.cn/Article/details/gtvdzykrgq.html

Java: if (s.isEmpty()) {}
来源：http://dali.cucudq.cn/Article/details/gtxwshwwkv.html

Go:   if s == "" {}
来源：http://dali.316326.xyz/Article/details/gtfbyvbwdx.html

Ruby: if s.empty?
来源：http://dali.kuanghao11.cn/Article/details/gtcifmqjwy.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.mhx1999.top/Article/details/gtkhmgikwj.html

[E21] 超长截断加省略号
来源：http://dali.jiagoushi.top/Article/details/gtpodcvhxw.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.gaohongyu789.top/Article/details/gtysupcwxt.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hysaishi.cn/Article/details/gtlpcyiimz.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gotoacloud.top/Article/details/gtliyvvwgl.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sxryk.cn/Article/details/gtfuudyfud.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.snrcjt.cn/Article/details/gtvjxjnmgy.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.nanxuanxn.top/Article/details/gtvlgbfmvi.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.cucudq.cn/Article/details/gtnwjwvspl.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yonumen.top/Article/details/gtnsxbygcf.html

[E22] 字节长度与字符长度
来源：http://dali.wangshuangyany.cn/Article/details/gtcrsdrtbw.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.9152youxi.cn/Article/details/gtzetmdfjz.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.snrcjt.cn/Article/details/gtkuwpwjrp.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jiagoushi.top/Article/details/gtwnurmjtm.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yueranfly.top/Article/details/gtmzmgwhze.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xuetiantiany.cn/Article/details/gtdlkkgazw.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yvedp.cn/Article/details/gtumrnreia.html

Ruby: s.bytesize;  s.length
来源：http://dali.9152youxi.cn/Article/details/gtdjvqjzmp.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.hysaishi.cn/Article/details/gtyblxalrz.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gttjrismfd.html

F. 文件与目录
来源：http://dali.gotoacloud.top/Article/details/gtfloguruq.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtzxsvosmq.html

[F01] 读取整个文件
来源：http://dali.yanxiufei.cn/Article/details/gtpjpiibbi.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.aibaodan.cn/Article/details/gtewmeynok.html

PHP:  file_get_contents("a.txt");
来源：http://dali.pycfn.com/Article/details/gtdahorxxw.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yanxiufei.cn/Article/details/gtgtvesdbf.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.iojbl.cn/Article/details/gteqtussub.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.chenzaomai.com/Article/details/gtuwugctfb.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.sweek.top/Article/details/gtexqbjfgv.html

Ruby: File.read("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtrhuznarr.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gtzoronsgd.html

[F02] 逐行读取文件
来源：http://dali.sweek.top/Article/details/gtriktweqj.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yj202588.top/Article/details/gtajfksfuf.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.0kj1m.cn/Article/details/gtqzebqiwz.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.tanke756.top/Article/details/gtphzgfmzo.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gttpfnipqd.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpmolbxxg.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.shzxlz.cn/Article/details/gthtdkafbj.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hfpthk.cn/Article/details/gtycnpurfo.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.cqqwz.cn/Article/details/gtzzunsjvc.html

[F03] 写入文件（覆盖）
来源：http://dali.cqqwz.cn/Article/details/gtkjfixjoi.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhiwuduotai.top/Article/details/gtdnwvbgkx.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.hywenlv.cn/Article/details/gtjntiaodo.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shuidangran.top/Article/details/gtpkotplmb.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.haohaochexian.top/Article/details/gteexaznix.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.svipenyu.cn/Article/details/gtbfykmsxi.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.9152youxi.cn/Article/details/gtkmcygjnn.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.tianlin.xyz/Article/details/gtzcjbwdpd.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhengqikj.top/Article/details/gtxwrifjay.html

[F04] 追加写入文件
来源：http://dali.zhiwuduotai.top/Article/details/gtungwlqqu.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yuxming.cn/Article/details/gtqhgbjfli.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.cucudq.cn/Article/details/gtmkjrugph.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hongshengwenyu.top/Article/details/gtexjcstdh.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinghuilouyu.cn/Article/details/gtughqsspw.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.shangyingyoupin.top/Article/details/gtdfohroqs.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.c1oappe.top/Article/details/gtaehtgqnv.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.birdmap.top/Article/details/gtgsxhafua.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.kuanghao11.cn/Article/details/gtisxpncrx.html

[F05] 判断文件或目录是否存在
来源：http://dali.meibo888.top/Article/details/gtzhtnzgtz.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.316326.xyz/Article/details/gtphphewrp.html

PHP:  file_exists("a.txt");
来源：http://dali.yj20258.top/Article/details/gtytmwyfyr.html

JS:   fs.existsSync("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtafvbasgf.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtdetmdain.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jqgfzy.top/Article/details/gtjptwtoxz.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zdqjudy.top/Article/details/gttmrlbmwv.html

Ruby: File.exist?("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtgrpngwvs.html

C#:   File.Exists("a.txt")
来源：http://dali.cashguo.top/Article/details/gtyiugegyj.html

[F06] 删除文件
来源：http://dali.jinqigfzy.top/Article/details/gtryztnbie.html

Py:   os.remove("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtjvdbcthu.html

PHP:  unlink("a.txt");
来源：http://dali.pycfn.com/Article/details/gttkvbiqmj.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtwbloquip.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.pycfn.com/Article/details/gtewnbnejb.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.wangdashe.top/Article/details/gtmpanhhxq.html

Go:   os.Remove("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtdjwnnxdk.html

Ruby: File.delete("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtnpxblvua.html

C#:   File.Delete("a.txt");
来源：http://dali.cucudq.cn/Article/details/gthoztzxnp.html

[F07] 创建目录（含多级）
来源：http://dali.yuanzhike.top/Article/details/gtzepnresl.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.chenzaomai.com/Article/details/gtsseojutv.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hfpthk.cn/Article/details/gthgootqku.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.pengpengdd.cyou/Article/details/gtidirfczj.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtokxgfsvo.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.dianchejie.cn/Article/details/gtdvemulkb.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.sweek.top/Article/details/gtuazuvunt.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.haohaochexian.top/Article/details/gthfsdnwyg.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.chenlongwang.top/Article/details/gtmfmwhujq.html

[F08] 遍历目录
来源：http://dali.wangshuangyany.cn/Article/details/gttflvvsdt.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hnxiangtu.top/Article/details/gtscrsqnnh.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.wangdashe.top/Article/details/gtbcjlpjpv.html

JS:   fs.readdirSync("dir")
来源：http://dali.shzxlz.cn/Article/details/gtbahmmzpk.html

TS:   fs.readdirSync("dir")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyqpxbipt.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.wangdashe.top/Article/details/gtxjrathna.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jqgfzy.top/Article/details/gtmkrqmlbp.html

Ruby: Dir.children("dir")
来源：http://dali.hongshengwenyu.top/Article/details/gtaovcqjde.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yanxiufei.cn/Article/details/gtiopqstpd.html

[F09] 获取文件大小
来源：http://dali.hysaishi.cn/Article/details/gtohkpngcv.html

Py:   os.path.getsize("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtpyidckwm.html

PHP:  filesize("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gtcysirsep.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yanxiufei.cn/Article/details/gtteoryuve.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jqgfzy.top/Article/details/gtbkhohtyd.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.shzxlz.cn/Article/details/gtkvdxdnvi.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xuetiantiany.cn/Article/details/gtatvhwehn.html

Ruby: File.size("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtlhruaycf.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.ydzc1.top/Article/details/gtxouchqza.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.shuidangran.top/Article/details/gtkdiomezo.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtztdkamab.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtijrdvikg.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtliawjyym.html

TS:   path.extname("a.txt")
来源：http://dali.pycfn.com/Article/details/gtuggpzzoj.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.xuanzx.com/Article/details/gtuvvuaehv.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtropsktvh.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.smart0.xyz/Article/details/gtrffnjtcc.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.smart0.xyz/Article/details/gtozjlmomy.html

[F11] 复制与移动文件
来源：http://dali.hnqzz.top/Article/details/gtyrtaopsu.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yj20258888.top/Article/details/gtzxaraxyd.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.ydzc1.top/Article/details/gtwqsoaghc.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.redwolf501.top/Article/details/gtgdfdedmf.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.haohaochexian.top/Article/details/gtkipymbpd.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.dianchejie.cn/Article/details/gtvgassuqd.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jianghu66.top/Article/details/gtvmaidnqv.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtffxsvgbu.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.guowangkeji.top/Article/details/gtbzucxjol.html

[F12] CSV 读写
来源：http://dali.chenzaomai.com/Article/details/gtybmwuoxc.html


<!-- 参考信息 -->