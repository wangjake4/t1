代发 wailian999

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yuanzhike.top/Article/details/gtubaslehw.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.gzhubu.top/Article/details/gtinwsamiz.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.wangdashe.top/Article/details/gtxagfccqs.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.shanyushiyangtech.top/Article/details/gtmwbjnhla.html

[E02] 重复字符串
来源：http://dali.smart0.xyz/Article/details/gthwtegccx.html

Py:   "ab" * 3
来源：http://dali.316326.xyz/Article/details/gtvwbthfgk.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zycfv.cn/Article/details/gthhuqpuve.html

JS:   "ab".repeat(3)
来源：http://dali.jyoumei.cn/Article/details/gtbzuvpidz.html

TS:   "ab".repeat(3)
来源：http://dali.feifeiyinyue.top/Article/details/gthycpoboj.html

Java: "ab".repeat(3)
来源：http://dali.dashuyun.cn/Article/details/gtlfebggwj.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.gaohongyu789.top/Article/details/gtwybxmhfi.html

Ruby: "ab" * 3
来源：http://dali.guowangkeji.top/Article/details/gtpenxbzok.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yuxming.cn/Article/details/gtqpoxejsf.html

[E03] 截取子串
来源：http://dali.redwolf501.top/Article/details/gtjumjpovh.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.gaohongyu789.top/Article/details/gtqdqqghwl.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.tianlin.xyz/Article/details/gtibiwjivs.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.daria6918.cn/Article/details/gttndozirz.html

TS:   s.slice(1, 4)
来源：http://dali.jlsjyb.cn/Article/details/gtfhdlfbas.html

Java: s.substring(1, 4)
来源：http://dali.daxiang520.top/Article/details/gtsmrrevlh.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.shzxlz.cn/Article/details/gtsmqjlest.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.hongshengwenyu.top/Article/details/gtyiqixfcv.html

C#:   s.Substring(1, 3)
来源：http://dali.jqgufenzy.top/Article/details/gthqlmvncm.html

[E04] 查找子串位置
来源：http://dali.ybcxt.top/Article/details/gtqjyuykmb.html

Py:   s.find("x");  s.index("x")
来源：http://dali.fzhhl.top/Article/details/gtporbgkxu.html

PHP:  strpos($s, "x");
来源：http://dali.jlsjyb.cn/Article/details/gttztcasct.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhixingplan.top/Article/details/gtibkayuka.html

TS:   s.indexOf("x")
来源：http://dali.chenjidiqi.icu/Article/details/gtbbcsddmj.html

Java: s.indexOf("x")
来源：http://dali.hnqzz.top/Article/details/gtqvsyanhd.html

Go:   strings.Index(s, "x")
来源：http://dali.yj20258.top/Article/details/gtvnocolqq.html

Ruby: s.index("x")
来源：http://dali.birdmap.top/Article/details/gtvqbgqdoj.html

C#:   s.IndexOf("x")
来源：http://dali.yj20258888.top/Article/details/gteumrvyak.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.9152youxi.cn/Article/details/gtentiiyvg.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwxklruaz.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnsqsnnae.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdhawjbqy.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yuxming.cn/Article/details/gtkgqwuasp.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ppjwa.cn/Article/details/gtihuxenfb.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.kuanghao11.cn/Article/details/gtixdtsglz.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.316326.xyz/Article/details/gtvpiwxflo.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yangfankeji.com/Article/details/gtalplsjpe.html

[E06] 替换子串
来源：http://dali.yueranfly.top/Article/details/gtkpvgyypb.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yuanzhike.top/Article/details/gtbotetxnv.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jqgfzy.top/Article/details/gtltbgflis.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyalmuxcv.html

TS:   s.replaceAll("a", "b")
来源：http://dali.dashuyun.cn/Article/details/gtavkioaah.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.vqdsnc.cn/Article/details/gtbjdapblg.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.xuetiantiany.cn/Article/details/gtxemlpiir.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.sxryk.cn/Article/details/gtfaldqznt.html

C#:   s.Replace("a", "b")
来源：http://dali.sxryk.cn/Article/details/gtketmylym.html

[E07] 按分隔符拆分
来源：http://dali.9152youxi.cn/Article/details/gtdqhnfgwn.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.hysaishi.cn/Article/details/gtiovdmdom.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.sweek.top/Article/details/gtqbnxxunn.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaafszknl.html

TS:   s.split(",")
来源：http://dali.xylfe.cn/Article/details/gtaolmzkjt.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jqgufenzy.top/Article/details/gtcceuuhwv.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.chenlongwang.top/Article/details/gtnsltsngl.html

Ruby: s.split(",");  s.split
来源：http://dali.wangdashe.top/Article/details/gtgqenthgo.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.shanyushiyangkeji.top/Article/details/gteushummp.html

[E08] 数组按分隔符合并
来源：http://dali.shanyushiyangtech.top/Article/details/gtybbdmdqm.html

Py:   ",".join(items)
来源：http://dali.tanke756.top/Article/details/gtfhhcynbs.html

PHP:  implode(",", $items);
来源：http://dali.meibo888.top/Article/details/gtckqpgmsh.html

JS:   items.join(",")
来源：http://dali.hfpthk.cn/Article/details/gtnegoigcz.html

TS:   items.join(",")
来源：http://dali.hysaishi.cn/Article/details/gtafuwhyfv.html

Java: String.join(",", items)
来源：http://dali.chenlongwang.top/Article/details/gtrbdwpqdc.html

Go:   strings.Join(items, ",")
来源：http://dali.dashuyun.cn/Article/details/gtyzzwffhk.html

Ruby: items.join(",")
来源：http://dali.hfpthk.cn/Article/details/gtvfrxjbdj.html

C#:   string.Join(",", items)
来源：http://dali.cqqwz.cn/Article/details/gtdfofphsq.html

[E09] 去除所有空白字符
来源：http://dali.shanyushiyangkeji.top/Article/details/gtudhpmubh.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jyoumei.cn/Article/details/gtqeadbhae.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.cqqwz.cn/Article/details/gtoctdphtw.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.chenjidiqi.icu/Article/details/gtrgqrqoat.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.pengpengdd.cyou/Article/details/gtsigfgzff.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjlrtaxlk.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jlsjyb.cn/Article/details/gtvgxfgyeg.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hongshengwenyu.top/Article/details/gtaddepnux.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yongpay.top/Article/details/gtaekijglu.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yueranfly.top/Article/details/gtrhkrizmr.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.feifeiyinyue.top/Article/details/gttpnugfso.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.xuetiantiany.cn/Article/details/gtfbqwgzrl.html

JS:   "7".padStart(3, "0")
来源：http://dali.gaohongyu789.top/Article/details/gtaersvmxm.html

TS:   "7".padStart(3, "0")
来源：http://dali.ehwqpu.com/Article/details/gtxhqxxusj.html

Java: String.format("%03d", 7)
来源：http://dali.daria6918.cn/Article/details/gtzfbdthhd.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.gotoacloud.top/Article/details/gteowkgzsc.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhongyouzk.top/Article/details/gtdopvvaay.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.pengpengdd.cyou/Article/details/gtxqphqbfi.html

[E11] 反转字符串
来源：http://dali.guowangkeji.top/Article/details/gthmrhziuf.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gtixcrpztm.html

PHP:  strrev($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvauvibwb.html

JS:   [...s].reverse().join("")
来源：http://dali.xylfe.cn/Article/details/gtjrqamebq.html

TS:   [...s].reverse().join("")
来源：http://dali.vqdsnc.cn/Article/details/gtdbvykioa.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.bjfxy.top/Article/details/gtrygshmsf.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhiwuduotai.top/Article/details/gtycmqmfud.html

Ruby: s.reverse
来源：http://dali.pycfn.com/Article/details/gtnieusgqn.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.aibaodan.cn/Article/details/gtiqqhvnhl.html

[E12] 统计某字符出现次数
来源：http://dali.xinyue.icu/Article/details/gtaemuchqf.html

Py:   s.count("a")
来源：http://dali.sweek.top/Article/details/gtxojavvhw.html

PHP:  substr_count($s, "a");
来源：http://dali.havefunace.top/Article/details/gtmxrgnthl.html

JS:   s.split("a").length - 1
来源：http://dali.daxiang520.top/Article/details/gtnjqhfnre.html

TS:   s.split("a").length - 1
来源：http://dali.zhiwuduotai.top/Article/details/gtrvmwrbbj.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.tianlin.xyz/Article/details/gtxbztylsy.html

Go:   strings.Count(s, "a")
来源：http://dali.xinyue.icu/Article/details/gteyyqfpfu.html

Ruby: s.count("a")
来源：http://dali.guannengcc.top/Article/details/gttlbqkems.html

C#:   s.Count(c => c == 'a')
来源：http://dali.fengsongda.top/Article/details/gtcgtaevzw.html

[E13] 逐字符遍历
来源：http://dali.xuanzx.com/Article/details/gtusjshdul.html

Py:   for ch in s: print(ch)
来源：http://dali.zhijiandao.cn/Article/details/gtukljzydb.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yj20258.top/Article/details/gtlbpksykx.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.birdmap.top/Article/details/gtgiaifzff.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hongshengwenyu.top/Article/details/gtxclmywqu.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhoulong.xyz/Article/details/gtltgshhnv.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.guowangkeji.top/Article/details/gtiosjposp.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.pengpengdd.cyou/Article/details/gtbbxsfbdi.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hnqzz.top/Article/details/gtgslrwgrw.html

[E14] URL 编码与 Base64
来源：http://dali.zhixingplan.top/Article/details/gtopyzxnih.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhoulong.xyz/Article/details/gtrhgjdnad.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yj202588.top/Article/details/gtuofsboaz.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jlsjyb.cn/Article/details/gtkgvuqdaj.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.gzhubu.top/Article/details/gtjmurazfp.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.xziqi.cn/Article/details/gttosywgcx.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhijiandao.cn/Article/details/gtyjscljwd.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jinghuilouyu.cn/Article/details/gtwxenwvcr.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.c1oappe.top/Article/details/gtgcskltwo.html

[E15] HTML 转义 / 反转义
来源：http://dali.jiagoushi.top/Article/details/gtdtchxblx.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yonumen.top/Article/details/gtaponziaj.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.aizwys.cn/Article/details/gtucbcokel.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtkggnnkva.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhengqikj.top/Article/details/gtealopykq.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.ivvv.top/Article/details/gtvahsftzh.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.cheryme.top/Article/details/gtqziiyazb.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.guannengcc.top/Article/details/gtxayyhhle.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmhxdjdiw.html

[E16] 数字千分位
来源：http://dali.wangshuangyany.cn/Article/details/gtwvaexdiz.html

Py:   f"{1234567:,}"
来源：http://dali.meibo888.top/Article/details/gtzolhntgz.html

PHP:  number_format(1234567);
来源：http://dali.jinghuilouyu.cn/Article/details/gtefyejlbe.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yongpay.top/Article/details/gtgomazric.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.redwolf501.top/Article/details/gtxzrgxehp.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jinqigfzy.top/Article/details/gtwgwfxcsl.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.smart0.xyz/Article/details/gtsjhzuwvo.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.cdnleiting.top/Article/details/gtaaykjnrr.html

C#:   1234567.ToString("N0")
来源：http://dali.daria6918.cn/Article/details/gtnfjcaygi.html

[E17] 首字母大写
来源：http://dali.yj20258.top/Article/details/gtzcqetmkf.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hnqzz.top/Article/details/gtjdhydkcz.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yanxiufei.cn/Article/details/gtlqxxfytk.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yuanzhike.top/Article/details/gtmhgbzwhd.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gotoacloud.top/Article/details/gttbpwzfmd.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.bjfxy.top/Article/details/gtomxynjrm.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.nanxinkj.top/Article/details/gtayihefrq.html

Ruby: s.capitalize
来源：http://dali.shuidangran.top/Article/details/gtabcdjori.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zdqjudy.top/Article/details/gtlwaunaqg.html

[E18] 模板占位符替换
来源：http://dali.cdnleiting.top/Article/details/gtxxpyylnp.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yangfankeji.com/Article/details/gtbpjjfusm.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xuanzx.com/Article/details/gtnxiurnlk.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jlsjyb.cn/Article/details/gtpldynoma.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.tanke756.top/Article/details/gtjfeoduhv.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.nanxuanxn.top/Article/details/gtiwpzwobm.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.0kj1m.cn/Article/details/gttroivooo.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zdqjudy.top/Article/details/gthkwvheeb.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jqgufenzy.top/Article/details/gtgyvcrtdk.html

[E19] 多行文本按行拆分
来源：http://dali.quarkkingdee.top/Article/details/gtihlnhtkd.html

Py:   s.splitlines()
来源：http://dali.sweek.top/Article/details/gtyiblnpex.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hfpthk.cn/Article/details/gtqbgodjmy.html

JS:   s.split(/\r?\n/)
来源：http://dali.xziqi.cn/Article/details/gtjuuitcym.html

TS:   s.split(/\r?\n/)
来源：http://dali.zycfv.cn/Article/details/gttbizkzws.html

Java: s.lines().toList()
来源：http://dali.zhoulong.xyz/Article/details/gtsnvpmcth.html

Go:   strings.Split(s, "\n")
来源：http://dali.smart0.xyz/Article/details/gtmuytihin.html

Ruby: s.lines
来源：http://dali.gotoacloud.top/Article/details/gttxnqdtss.html

C#:   s.Split('\n')
来源：http://dali.ydzc1.top/Article/details/gtdvryvxgn.html

[E20] 判断字符串是否为空
来源：http://dali.zhongyouzk.top/Article/details/gtkxmggjks.html

Py:   if not s:
来源：http://dali.fengsongda.top/Article/details/gtfbxnrhic.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.gotoacloud.top/Article/details/gtjhahfxmr.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.daria6918.cn/Article/details/gttjbysxkk.html

TS:   if (s === "") {}
来源：http://dali.pengpengdd.cyou/Article/details/gtazooxbcf.html

Java: if (s.isEmpty()) {}
来源：http://dali.tianlin.xyz/Article/details/gtgejzsfsb.html

Go:   if s == "" {}
来源：http://dali.redwolf501.top/Article/details/gtptmtbiwi.html

Ruby: if s.empty?
来源：http://dali.tanke756.top/Article/details/gtfdnljnnn.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.aibaodan.cn/Article/details/gtzwesmexq.html

[E21] 超长截断加省略号
来源：http://dali.0kj1m.cn/Article/details/gtflpcmuba.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gttpcdvvyk.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhoulong.xyz/Article/details/gtfryqfbjx.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.daria6918.cn/Article/details/gtqpayypid.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.redwolf501.top/Article/details/gtudrjkbym.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.cashguo.top/Article/details/gtkdohskui.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.shzxlz.cn/Article/details/gtbffkevtr.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.hfpthk.cn/Article/details/gtkiayjfzc.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hongshengwenyu.top/Article/details/gtkfstntcl.html

[E22] 字节长度与字符长度
来源：http://dali.yj202588.top/Article/details/gtojpndzns.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.tian-w.cn/Article/details/gtcpnmjaau.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yuanzhike.top/Article/details/gtmslpgiuv.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shangyingyoupin.top/Article/details/gtpbgnztzx.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yanxiufei.cn/Article/details/gtveeshxgw.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.nanxinkj.top/Article/details/gtkapkbilx.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.birdmap.top/Article/details/gtvwyiwzxj.html

Ruby: s.bytesize;  s.length
来源：http://dali.nanxuanxn.top/Article/details/gtpvbptylb.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.daxiang520.top/Article/details/gtqisejuth.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtlebzgfql.html

F. 文件与目录
来源：http://dali.vqdsnc.cn/Article/details/gtapczlovn.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtjwadzgxa.html

[F01] 读取整个文件
来源：http://dali.zhiwuduotai.top/Article/details/gtfzdnxhxt.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.aibaodan.cn/Article/details/gtjjxefkhb.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gtxanabupv.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hywenlv.cn/Article/details/gtqyehvfiq.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.nanxuanxn.top/Article/details/gtyzxjchab.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.meibo888.top/Article/details/gtrhbqtncp.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.andypj.xyz/Article/details/gtjeihpnso.html

Ruby: File.read("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtuvsictdi.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.gotoacloud.top/Article/details/gttpnwamcs.html

[F02] 逐行读取文件
来源：http://dali.chenzaomai.com/Article/details/gtehjlxdqj.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.aizwys.cn/Article/details/gtffvfrcki.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.cucudq.cn/Article/details/gtcfnwbldj.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ehwqpu.com/Article/details/gtjhtkppko.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.quarkkingdee.top/Article/details/gtdsxumufg.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.sxryk.cn/Article/details/gtkyisrexc.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zdqjudy.top/Article/details/gtayosyyei.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.snrcjt.cn/Article/details/gtjswapwdi.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yanxiufei.cn/Article/details/gtwnnhysde.html

[F03] 写入文件（覆盖）
来源：http://dali.snrcjt.cn/Article/details/gtohdqawtu.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.xziqi.cn/Article/details/gtxekpmmju.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jinqigufen.top/Article/details/gtnfahceuw.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ivvv.top/Article/details/gtqfnyncwy.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.chenjidiqi.icu/Article/details/gtyuesyuoc.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jqgufenzy.top/Article/details/gtzvtogzmy.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.nanxuanxn.top/Article/details/gtkizueebi.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.chenlongwang.top/Article/details/gtosyjunmf.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jianghu66.top/Article/details/gtiyfqkmsq.html

[F04] 追加写入文件
来源：http://dali.daxiang520.top/Article/details/gtxaponedz.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yvedp.cn/Article/details/gtfqulefbb.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzcfqpmec.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yvedp.cn/Article/details/gtklutnwul.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.chenjidiqi.icu/Article/details/gteegtoxoc.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.meibo888.top/Article/details/gtqylwmlle.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.shanyushiyangtech.top/Article/details/gtjfqzrkwn.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jyoumei.cn/Article/details/gtpskjmkub.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.quarkkingdee.top/Article/details/gtrrevfsks.html

[F05] 判断文件或目录是否存在
来源：http://dali.yongpay.top/Article/details/gtbilpcvkh.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.birdmap.top/Article/details/gtmzpozpyz.html

PHP:  file_exists("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtptrlqbuv.html

JS:   fs.existsSync("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtmepmgdkh.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtaevdjoha.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.tanke756.top/Article/details/gtdggcltfr.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.tian-w.cn/Article/details/gtkhzndyqe.html

Ruby: File.exist?("a.txt")
来源：http://dali.cheryme.top/Article/details/gtykkigihh.html

C#:   File.Exists("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqpzhuhcn.html

[F06] 删除文件
来源：http://dali.cqqwz.cn/Article/details/gtzlkwxqwj.html

Py:   os.remove("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtyqjlqjow.html

PHP:  unlink("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gtbksfbfxh.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtfiqmmcho.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gteebvfgiu.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhixingplan.top/Article/details/gtqbgfiept.html

Go:   os.Remove("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtiiuzsgst.html

Ruby: File.delete("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtckqfaiab.html

C#:   File.Delete("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtoroynhbj.html

[F07] 创建目录（含多级）
来源：http://dali.fengsongda.top/Article/details/gtlmbvlffq.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.birdmap.top/Article/details/gtbotdmelg.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.shangyingyoupin.top/Article/details/gtiagcfdlh.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.wangdashe.top/Article/details/gtmlrljydt.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jlsjyb.cn/Article/details/gteoqbseqd.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jyoumei.cn/Article/details/gtkdolvdge.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjemtodsy.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yueranfly.top/Article/details/gtgxxjocub.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.ydzc1.top/Article/details/gtcsgwoyvn.html

[F08] 遍历目录
来源：http://dali.jinghuilouyu.cn/Article/details/gtlodtjjyp.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.shuidangran.top/Article/details/gthtnnjllm.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hongshengwenyu.top/Article/details/gtemthgjuy.html

JS:   fs.readdirSync("dir")
来源：http://dali.snrcjt.cn/Article/details/gtqjeainmh.html

TS:   fs.readdirSync("dir")
来源：http://dali.daxiang520.top/Article/details/gteloupfro.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yueranfly.top/Article/details/gttyjkayde.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhengqikj.top/Article/details/gtdbvcmwzf.html

Ruby: Dir.children("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gtwymrersp.html

C#:   Directory.GetFiles("dir")
来源：http://dali.aizwys.cn/Article/details/gtuuvioeil.html

[F09] 获取文件大小
来源：http://dali.jyoumei.cn/Article/details/gtabmblbfz.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yj202588.top/Article/details/gtnswbjmvh.html

PHP:  filesize("a.txt");
来源：http://dali.gzhubu.top/Article/details/gteickyxwy.html

JS:   fs.statSync("a.txt").size
来源：http://dali.guowangkeji.top/Article/details/gtnqajdrda.html

TS:   fs.statSync("a.txt").size
来源：http://dali.guowangkeji.top/Article/details/gtgumkzwry.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.sufxvd.cn/Article/details/gtcpivmoof.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.iojbl.cn/Article/details/gtduzsqsks.html

Ruby: File.size("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtdwtrothl.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.wangdashe.top/Article/details/gtbxslmmqv.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.havefunace.top/Article/details/gtvirpfrqq.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtnnihxjwn.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.svipenyu.cn/Article/details/gtfcxfzhqj.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.ybcxt.top/Article/details/gtrsdclacu.html

TS:   path.extname("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtgvmjmglh.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ehwqpu.com/Article/details/gtaoqonigz.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.316326.xyz/Article/details/gtkfairasj.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtuxxmrgrf.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtjcgklqrj.html

[F11] 复制与移动文件
来源：http://dali.iojbl.cn/Article/details/gtyqpwjfma.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yongpay.top/Article/details/gttcgnsico.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.snrcjt.cn/Article/details/gtcodandxb.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.wangdashe.top/Article/details/gtkywvckoi.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.dashuyun.cn/Article/details/gtqbghkodb.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.nwbrower.top/Article/details/gtszhgumsy.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yonumen.top/Article/details/gtxreedvaa.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtrzazndje.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hnxiangtu.top/Article/details/gtoyhkkkqt.html

[F12] CSV 读写
来源：http://dali.xylfe.cn/Article/details/gthajappdd.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.gzhubu.top/Article/details/gtvwmqjanh.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ydzc1.top/Article/details/gtktwseryr.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yanxiufei.cn/Article/details/gtqellmmdk.html

TS:   // 同上
来源：http://dali.smart0.xyz/Article/details/gtjgitozdu.html


<!-- 参考信息 -->