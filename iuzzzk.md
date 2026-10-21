代发 wailian999

TS:   "ab".repeat(3)
来源：http://dali.smart0.xyz/Article/details/gtfyfjvshc.html

Java: "ab".repeat(3)
来源：http://dali.tianlin.xyz/Article/details/gtknbibtde.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.fengsongda.top/Article/details/gtjmrtvpge.html

Ruby: "ab" * 3
来源：http://dali.0kj1m.cn/Article/details/gtarnpjivg.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yj20258.top/Article/details/gtdkpyhlsu.html

[E03] 截取子串
来源：http://dali.sysykeji.top/Article/details/gtsmkekhpy.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yangfankeji.com/Article/details/gtuzhyjqpm.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.shzxlz.cn/Article/details/gtcxgmkkhk.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.dianchejie.cn/Article/details/gtuijygdtt.html

TS:   s.slice(1, 4)
来源：http://dali.kuanghao11.cn/Article/details/gtgwgerozu.html

Java: s.substring(1, 4)
来源：http://dali.hnqzz.top/Article/details/gtxcnhozqm.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.guannengcc.top/Article/details/gtqecrpazl.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.hysaishi.cn/Article/details/gtgcoahtpi.html

C#:   s.Substring(1, 3)
来源：http://dali.chenlongwang.top/Article/details/gtbwlbtyha.html

[E04] 查找子串位置
来源：http://dali.sysykeji.top/Article/details/gtwvaxhzrx.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hnxiangtu.top/Article/details/gtobiykcah.html

PHP:  strpos($s, "x");
来源：http://dali.xziqi.cn/Article/details/gtyguohhly.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yonumen.top/Article/details/gtpvtomwga.html

TS:   s.indexOf("x")
来源：http://dali.hnqzz.top/Article/details/gtbfskgrmu.html

Java: s.indexOf("x")
来源：http://dali.cqqwz.cn/Article/details/gtbnskfiuh.html

Go:   strings.Index(s, "x")
来源：http://dali.ppjwa.cn/Article/details/gtpzmpeezb.html

Ruby: s.index("x")
来源：http://dali.tian-w.cn/Article/details/gtanxpmaxv.html

C#:   s.IndexOf("x")
来源：http://dali.chenjidiqi.icu/Article/details/gtoodnctdp.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.gotoacloud.top/Article/details/gtkhdkxlaz.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.xinyue.icu/Article/details/gtgigijktg.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yj20258.top/Article/details/gtwqmhcxxs.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.iojbl.cn/Article/details/gtkiuwedqm.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yj202588.top/Article/details/gtmtwvwnhy.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xinyue.icu/Article/details/gtfcvmagdh.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.shangyingyoupin.top/Article/details/gtlaxdatop.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.havefunace.top/Article/details/gtvpqxsnan.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.dianchejie.cn/Article/details/gtxrugwvjy.html

[E06] 替换子串
来源：http://dali.zhongyouzk.top/Article/details/gtrvlxdjms.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.andypj.xyz/Article/details/gtziqlleib.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.cqqwz.cn/Article/details/gtasrwcqzq.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.fzhhl.top/Article/details/gtqpmkefuj.html

TS:   s.replaceAll("a", "b")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtefubujng.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shanyushiyangtech.top/Article/details/gtxcbiloqk.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.gogol.net.cn/Article/details/gtubvjogbl.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.ydzc1.top/Article/details/gtaznoagvr.html

C#:   s.Replace("a", "b")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwvowhvmp.html

[E07] 按分隔符拆分
来源：http://dali.gaohongyu789.top/Article/details/gtfpkmtfzx.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.cqqwz.cn/Article/details/gtikmhfcmn.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jyoumei.cn/Article/details/gtcoaysahv.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.tianlin.xyz/Article/details/gtnluywnpa.html

TS:   s.split(",")
来源：http://dali.chenzaomai.com/Article/details/gtoayxznnv.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhaomingkeji.xyz/Article/details/gteawdsymq.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yueranfly.top/Article/details/gtpuqjdemm.html

Ruby: s.split(",");  s.split
来源：http://dali.chenlongwang.top/Article/details/gtrdjcwjmy.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zycfv.cn/Article/details/gtjavuhipi.html

[E08] 数组按分隔符合并
来源：http://dali.yongpay.top/Article/details/gtfpqkmfdb.html

Py:   ",".join(items)
来源：http://dali.sysykeji.top/Article/details/gtjepzzjcy.html

PHP:  implode(",", $items);
来源：http://dali.c1oappe.top/Article/details/gthemycxcn.html

JS:   items.join(",")
来源：http://dali.0kj1m.cn/Article/details/gtzbypavwg.html

TS:   items.join(",")
来源：http://dali.chenlongwang.top/Article/details/gtwfupwaur.html

Java: String.join(",", items)
来源：http://dali.yj202588.top/Article/details/gtsluwzllq.html

Go:   strings.Join(items, ",")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqajeipyr.html

Ruby: items.join(",")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvzsyzgwm.html

C#:   string.Join(",", items)
来源：http://dali.cdnleiting.top/Article/details/gticfzifah.html

[E09] 去除所有空白字符
来源：http://dali.gotoacloud.top/Article/details/gtbvutqito.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.sxryk.cn/Article/details/gtwcbrbpso.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhengqikj.top/Article/details/gtvdjvuulc.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.kuanghao11.cn/Article/details/gtiqefmpfp.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.wangdashe.top/Article/details/gtwqfigdzm.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.gzhubu.top/Article/details/gtjohpeysw.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jqgufenzy.top/Article/details/gtbecpgkhe.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hysaishi.cn/Article/details/gtgmftsuzk.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.andypj.xyz/Article/details/gtsdripngh.html

[E10] 左侧补零 / 定长填充
来源：http://dali.bjfxy.top/Article/details/gtlexbqcfm.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.shuidangran.top/Article/details/gtsqcchbfy.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.nanxinkj.top/Article/details/gtfoozxwpv.html

JS:   "7".padStart(3, "0")
来源：http://dali.sysykeji.top/Article/details/gtsgtnbkta.html

TS:   "7".padStart(3, "0")
来源：http://dali.shangyingyoupin.top/Article/details/gtgvjpeafu.html

Java: String.format("%03d", 7)
来源：http://dali.andypj.xyz/Article/details/gtuaikvmhf.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.andypj.xyz/Article/details/gtuwzypxki.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.fzhhl.top/Article/details/gtlkkcawuu.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhiwuduotai.top/Article/details/gthpnqkmha.html

[E11] 反转字符串
来源：http://dali.ppjwa.cn/Article/details/gtxmsvgbed.html

Py:   s[::-1]
来源：http://dali.hywenlv.cn/Article/details/gtxwfsqvkh.html

PHP:  strrev($s);
来源：http://dali.svipenyu.cn/Article/details/gtwftipfji.html

JS:   [...s].reverse().join("")
来源：http://dali.mhx1999.top/Article/details/gtenasexsr.html

TS:   [...s].reverse().join("")
来源：http://dali.guannengcc.top/Article/details/gtgoaumjjl.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jianghu66.top/Article/details/gtqkpxnklq.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.feifeiyinyue.top/Article/details/gtnyvkqirg.html

Ruby: s.reverse
来源：http://dali.cqqwz.cn/Article/details/gtloffbzgv.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yj20258888.top/Article/details/gtyerfjicd.html

[E12] 统计某字符出现次数
来源：http://dali.zdqjudy.top/Article/details/gtnbrpffcg.html

Py:   s.count("a")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtszioqadf.html

PHP:  substr_count($s, "a");
来源：http://dali.nanxuanxn.top/Article/details/gtpslysdqm.html

JS:   s.split("a").length - 1
来源：http://dali.yanxiufei.cn/Article/details/gtrkxnuhbz.html

TS:   s.split("a").length - 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqbufwbva.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yj20258.top/Article/details/gtmfcskaet.html

Go:   strings.Count(s, "a")
来源：http://dali.nanxuanxn.top/Article/details/gtpjoxhjuc.html

Ruby: s.count("a")
来源：http://dali.tanke756.top/Article/details/gtwtqisaik.html

C#:   s.Count(c => c == 'a')
来源：http://dali.vqdsnc.cn/Article/details/gtbqinlrtd.html

[E13] 逐字符遍历
来源：http://dali.smart0.xyz/Article/details/gtpzhspvku.html

Py:   for ch in s: print(ch)
来源：http://dali.cashguo.top/Article/details/gtyonfzvtv.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhengqikj.top/Article/details/gtghhzznyh.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hnxiangtu.top/Article/details/gtvcraiyyg.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.kuanghao11.cn/Article/details/gtipdlywan.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hfpthk.cn/Article/details/gtopylsfvn.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.dianchejie.cn/Article/details/gtccmakhrh.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yonumen.top/Article/details/gtifahodpv.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.mhx1999.top/Article/details/gtqjbrazbx.html

[E14] URL 编码与 Base64
来源：http://dali.shangyingyoupin.top/Article/details/gtoteepxsr.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.tianlin.xyz/Article/details/gtgxehxjcs.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jinqigfzy.top/Article/details/gtugpaudyp.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.havefunace.top/Article/details/gtravdjgbc.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtvtokhvnq.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.svipenyu.cn/Article/details/gtevwxqeaw.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.gogol.net.cn/Article/details/gtamtmsjln.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.cqqwz.cn/Article/details/gtfefxkpas.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.vqdsnc.cn/Article/details/gtkuumciie.html

[E15] HTML 转义 / 反转义
来源：http://dali.gaohongyu789.top/Article/details/gtsgojiszx.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yongpay.top/Article/details/gteqmgwgut.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.snrcjt.cn/Article/details/gtuelzfars.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjsntvfrs.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.feifeiyinyue.top/Article/details/gtlzabmgyt.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.daria6918.cn/Article/details/gtzmemhakp.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.fzhhl.top/Article/details/gtypflihmm.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.smart0.xyz/Article/details/gtgcprqhko.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.cheryme.top/Article/details/gtawricfop.html

[E16] 数字千分位
来源：http://dali.xziqi.cn/Article/details/gtsbubbntz.html

Py:   f"{1234567:,}"
来源：http://dali.tian-w.cn/Article/details/gtuwewnuev.html

PHP:  number_format(1234567);
来源：http://dali.yueranfly.top/Article/details/gtbieflvzn.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jqgufenzy.top/Article/details/gtmbmiaapr.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.cucudq.cn/Article/details/gtqhmlelyj.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.gaohongyu789.top/Article/details/gtcijzcgew.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hammf.cn/Article/details/gtqbydakga.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.havefunace.top/Article/details/gtgbkydbxz.html

C#:   1234567.ToString("N0")
来源：http://dali.zhengqikj.top/Article/details/gtixymadpg.html

[E17] 首字母大写
来源：http://dali.yj20258888.top/Article/details/gtrwqlmgxy.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.nwbrower.top/Article/details/gtvcfboqwq.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.cheryme.top/Article/details/gtjrjjpefa.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhengqikj.top/Article/details/gtvuunyltp.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ppjwa.cn/Article/details/gtgclvubwx.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbqfprxrw.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.sxryk.cn/Article/details/gtoyeomijg.html

Ruby: s.capitalize
来源：http://dali.yj20258888.top/Article/details/gtvlpsrhxv.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yuanzhike.top/Article/details/gtgyqpkstv.html

[E18] 模板占位符替换
来源：http://dali.jinghuilouyu.cn/Article/details/gtyaqoekod.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.xuetiantiany.cn/Article/details/gttilbxbnd.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xylfe.cn/Article/details/gtlwfdzpsw.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.xziqi.cn/Article/details/gtukmzmqho.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hfpthk.cn/Article/details/gtckenoltf.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.dashuyun.cn/Article/details/gtsfwjmpwt.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.fzhhl.top/Article/details/gtyirfcbgl.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yvedp.cn/Article/details/gtxobwfnda.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.tian-w.cn/Article/details/gtajiaafgs.html

[E19] 多行文本按行拆分
来源：http://dali.cashguo.top/Article/details/gtmulmqxci.html

Py:   s.splitlines()
来源：http://dali.jinqigufen.top/Article/details/gtzewvuark.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jlsjyb.cn/Article/details/gtyzqrbhvb.html

JS:   s.split(/\r?\n/)
来源：http://dali.yanxiufei.cn/Article/details/gtzoewxoxs.html

TS:   s.split(/\r?\n/)
来源：http://dali.jinqigufen.top/Article/details/gtqapcoiwz.html

Java: s.lines().toList()
来源：http://dali.yanxiufei.cn/Article/details/gtdhrbozyn.html

Go:   strings.Split(s, "\n")
来源：http://dali.sweek.top/Article/details/gtgkxqcnsb.html

Ruby: s.lines
来源：http://dali.sweek.top/Article/details/gttdllwslr.html

C#:   s.Split('\n')
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaynveysd.html

[E20] 判断字符串是否为空
来源：http://dali.hywenlv.cn/Article/details/gtvgylchcq.html

Py:   if not s:
来源：http://dali.cheryme.top/Article/details/gtsrdtxriv.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zdqjudy.top/Article/details/gtdbowabmc.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jqgfzy.top/Article/details/gthkqkjfgz.html

TS:   if (s === "") {}
来源：http://dali.andypj.xyz/Article/details/gtseyaimff.html

Java: if (s.isEmpty()) {}
来源：http://dali.shuidangran.top/Article/details/gtzkhurtrj.html

Go:   if s == "" {}
来源：http://dali.zycfv.cn/Article/details/gtccrcrtsd.html

Ruby: if s.empty?
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyjgrcemu.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.xylfe.cn/Article/details/gthmpffqhz.html

[E21] 超长截断加省略号
来源：http://dali.gogol.net.cn/Article/details/gtqddsxxex.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jqgfzy.top/Article/details/gtznonbuyi.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.daxiang520.top/Article/details/gtafzcsxgx.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zdqjudy.top/Article/details/gtmwxpcnem.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.mhx1999.top/Article/details/gtpflpgcqr.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zycfv.cn/Article/details/gtectcdfgc.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yj20258.top/Article/details/gtccikagwb.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jinqigufen.top/Article/details/gtvnmhokvo.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.0kj1m.cn/Article/details/gtmtvxsspa.html

[E22] 字节长度与字符长度
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxwfnxuqb.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.fengsongda.top/Article/details/gtsrjlxddf.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.9152youxi.cn/Article/details/gtcnsqyqnw.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinghuilouyu.cn/Article/details/gtuhzcpoay.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.bjfxy.top/Article/details/gtnsxfzosq.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.tanke756.top/Article/details/gtdxvvcakr.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yueranfly.top/Article/details/gtazijkntu.html

Ruby: s.bytesize;  s.length
来源：http://dali.nanxinkj.top/Article/details/gtivvqfnnx.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yj202588.top/Article/details/gtlzmnihvu.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqzopodjk.html

F. 文件与目录
来源：http://dali.hfpthk.cn/Article/details/gtihpelqgh.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtgdjwuxne.html

[F01] 读取整个文件
来源：http://dali.cqqwz.cn/Article/details/gtwnfxzvii.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvnniqvss.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shuidangran.top/Article/details/gthxulzwxx.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.316326.xyz/Article/details/gtjsrummgq.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.0kj1m.cn/Article/details/gtqtugkpcu.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zdqjudy.top/Article/details/gtqjtqysgn.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.shuidangran.top/Article/details/gtuxhtvucr.html

Ruby: File.read("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtzzvpffxe.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gtmwwiqhvr.html

[F02] 逐行读取文件
来源：http://dali.zhiwuduotai.top/Article/details/gtjaqzqkak.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.dianchejie.cn/Article/details/gtdafbbbqn.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yueranfly.top/Article/details/gtaeivptgk.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gzhubu.top/Article/details/gtqclsmlzt.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jlsjyb.cn/Article/details/gtaaorumpo.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.havefunace.top/Article/details/gtmakmfqmo.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jinqigufen.top/Article/details/gtrpvoekof.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jianghu66.top/Article/details/gtrlohhszj.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtxtsxwjie.html

[F03] 写入文件（覆盖）
来源：http://dali.svipenyu.cn/Article/details/gtaxlzxref.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yangfankeji.com/Article/details/gtuvacsmbi.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhongyouzk.top/Article/details/gtrogscnqp.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hfpthk.cn/Article/details/gtgzfoilxi.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.haohaochexian.top/Article/details/gtkwapsbpy.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.sxryk.cn/Article/details/gtkolhchyp.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.gaohongyu789.top/Article/details/gtxdkhkfgg.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.vqdsnc.cn/Article/details/gtogalccxo.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.chenlongwang.top/Article/details/gtflzcyart.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gtezylquyy.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.chenlongwang.top/Article/details/gtuxcoumia.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.guowangkeji.top/Article/details/gtqmtmshgx.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nanxinkj.top/Article/details/gtxqpvxkby.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hnxiangtu.top/Article/details/gteougamxa.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.guowangkeji.top/Article/details/gtnfmxpqxa.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.tianlin.xyz/Article/details/gtvpigifyc.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.nanxuanxn.top/Article/details/gtthgcbdsf.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yj20258888.top/Article/details/gtxvlkcqao.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhoulong.xyz/Article/details/gtnkchsrux.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhoulong.xyz/Article/details/gtzxbkugfv.html

PHP:  file_exists("a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gtoqwvkfso.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtfagkvbtm.html

TS:   fs.existsSync("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gttimkvpzp.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.0kj1m.cn/Article/details/gthuuihfym.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jqgfzy.top/Article/details/gtcunggtav.html

Ruby: File.exist?("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtodblqdlh.html

C#:   File.Exists("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gthodrzboj.html

[F06] 删除文件
来源：http://dali.zhongyouzk.top/Article/details/gtmrenemec.html

Py:   os.remove("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gthkcvdodx.html

PHP:  unlink("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gtisaomdhv.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xziqi.cn/Article/details/gthgdrectq.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtkavfgrgf.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.gotoacloud.top/Article/details/gtszvybsdc.html

Go:   os.Remove("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtpsnnrsrx.html

Ruby: File.delete("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtyiyvrnfd.html

C#:   File.Delete("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gteyttmowl.html

[F07] 创建目录（含多级）
来源：http://dali.fengsongda.top/Article/details/gtwiirbfbp.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.dianchejie.cn/Article/details/gtqdhvguuy.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hammf.cn/Article/details/gtyqpfdmhs.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jianghu66.top/Article/details/gthvbatgco.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jiagoushi.top/Article/details/gtgmlsehgz.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.xziqi.cn/Article/details/gtxjiifaty.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.cdnleiting.top/Article/details/gtiqephkac.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yangfankeji.com/Article/details/gtozxhkxne.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.chenzaomai.com/Article/details/gtruksgfek.html

[F08] 遍历目录
来源：http://dali.jinghuilouyu.cn/Article/details/gtmdmuykgu.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhiwuduotai.top/Article/details/gttxlbjwue.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hnxiangtu.top/Article/details/gtxmycphbh.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhixingplan.top/Article/details/gtemjcmsha.html

TS:   fs.readdirSync("dir")
来源：http://dali.ehwqpu.com/Article/details/gtuvlngzmz.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hammf.cn/Article/details/gtxjntpwfn.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.guannengcc.top/Article/details/gturnvgbpm.html

Ruby: Dir.children("dir")
来源：http://dali.guowangkeji.top/Article/details/gtbnnaodop.html

C#:   Directory.GetFiles("dir")
来源：http://dali.guannengcc.top/Article/details/gtfafogfpx.html

[F09] 获取文件大小
来源：http://dali.nanxinkj.top/Article/details/gtettylvcy.html

Py:   os.path.getsize("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtknlminnf.html

PHP:  filesize("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gthojyhxma.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yongpay.top/Article/details/gtytazempc.html

TS:   fs.statSync("a.txt").size
来源：http://dali.smart0.xyz/Article/details/gthaacuekv.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xuanzx.com/Article/details/gtjchlizlu.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xuanzx.com/Article/details/gtnkjgymkx.html

Ruby: File.size("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrydchrru.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xuanzx.com/Article/details/gtullpfmtw.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yuanzhike.top/Article/details/gtshuazhaa.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ivvv.top/Article/details/gtffvrypjt.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtnzcklgxr.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.guannengcc.top/Article/details/gtectbgrbr.html

TS:   path.extname("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtlmycmbww.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.dashuyun.cn/Article/details/gtlpluwpln.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.wangdashe.top/Article/details/gthdbtomsd.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.gzhubu.top/Article/details/gtxdfynqpy.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtcshexhpp.html

[F11] 复制与移动文件
来源：http://dali.jyoumei.cn/Article/details/gtliddwezp.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hnqzz.top/Article/details/gtqaxccyhy.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.ydzc1.top/Article/details/gtrtqldbse.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yuanzhike.top/Article/details/gtbiuinpuh.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shzxlz.cn/Article/details/gtnkmqxthb.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yuxming.cn/Article/details/gtphyewoik.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yj202588.top/Article/details/gtsyvrpmcw.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhixingplan.top/Article/details/gtohxlmnsg.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yonumen.top/Article/details/gthkbbghuh.html

[F12] CSV 读写
来源：http://dali.dashuyun.cn/Article/details/gtjgadmxku.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.daxiang520.top/Article/details/gtjkdoolke.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.c1oappe.top/Article/details/gtkkoddvze.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.cucudq.cn/Article/details/gtfxldlgtm.html

TS:   // 同上
来源：http://dali.pycfn.com/Article/details/gtrglmsftc.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.wangdashe.top/Article/details/gtkqatydxy.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.shanyushiyangtech.top/Article/details/gteantvvao.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.wangshuangyany.cn/Article/details/gthefqznow.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.sufxvd.cn/Article/details/gtglqoqvsk.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtduxgdxwi.html

G. 面向对象
来源：http://dali.hfpthk.cn/Article/details/gtyfnlfgck.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtdtmciwtv.html

[G01] 定义类
来源：http://dali.wangdashe.top/Article/details/gtpqwtxptu.html


<!-- 参考信息 -->