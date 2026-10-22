代发 wailian999

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.cheryme.top/Article/details/gterfclbej.html

[E03] 截取子串
来源：http://dali.ybcxt.top/Article/details/gtwitpiajt.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcytamals.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.0kj1m.cn/Article/details/gtxpdibwxm.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.fengsongda.top/Article/details/gttpanlefq.html

TS:   s.slice(1, 4)
来源：http://dali.redwolf501.top/Article/details/gtkzagwmsr.html

Java: s.substring(1, 4)
来源：http://dali.ppjwa.cn/Article/details/gtmgsbwnpz.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.wangdashe.top/Article/details/gtlapjarim.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.mhx1999.top/Article/details/gtrypyoqfa.html

C#:   s.Substring(1, 3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtximaqpwm.html

[E04] 查找子串位置
来源：http://dali.yueranfly.top/Article/details/gtahftwqhk.html

Py:   s.find("x");  s.index("x")
来源：http://dali.aibaodan.cn/Article/details/gteblpohbv.html

PHP:  strpos($s, "x");
来源：http://dali.pengpengdd.cyou/Article/details/gtamppynar.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.cucudq.cn/Article/details/gtvfanzuec.html

TS:   s.indexOf("x")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyfipopgf.html

Java: s.indexOf("x")
来源：http://dali.chenzaomai.com/Article/details/gtgnzuiuek.html

Go:   strings.Index(s, "x")
来源：http://dali.316326.xyz/Article/details/gtnnqgskkm.html

Ruby: s.index("x")
来源：http://dali.dianchejie.cn/Article/details/gtynytdmhp.html

C#:   s.IndexOf("x")
来源：http://dali.chenlongwang.top/Article/details/gtbgibqbso.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yonumen.top/Article/details/gtgrcfxzsa.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.hysaishi.cn/Article/details/gtiuthlgfx.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jlsjyb.cn/Article/details/gtrrmpmncx.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yj20258.top/Article/details/gtsbesehik.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.cqqwz.cn/Article/details/gtrcotuoan.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.fzhhl.top/Article/details/gtlvqogyuv.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yueranfly.top/Article/details/gtgrlpizzq.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.shangyingyoupin.top/Article/details/gtgfamaawc.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.ppjwa.cn/Article/details/gtcuexuocd.html

[E06] 替换子串
来源：http://dali.jiagoushi.top/Article/details/gtualiqjxq.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.gogol.net.cn/Article/details/gtzcbwajzr.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.xuanzx.com/Article/details/gtyoukdpyz.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.chenjidiqi.icu/Article/details/gteixxjoam.html

TS:   s.replaceAll("a", "b")
来源：http://dali.tian-w.cn/Article/details/gtpuixmevl.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.svipenyu.cn/Article/details/gtdwjktlyy.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yonumen.top/Article/details/gthdfqcdnr.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gtgtccuvsw.html

C#:   s.Replace("a", "b")
来源：http://dali.shanyushiyangtech.top/Article/details/gtjpmldxyd.html

[E07] 按分隔符拆分
来源：http://dali.wangdashe.top/Article/details/gteewggege.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.pengpengdd.cyou/Article/details/gtwslqihyy.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.tian-w.cn/Article/details/gtntdlznkc.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.wangdashe.top/Article/details/gtdkcmsssd.html

TS:   s.split(",")
来源：http://dali.hnxiangtu.top/Article/details/gtwfprlzcn.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.hongshengwenyu.top/Article/details/gthdikuqvf.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.guannengcc.top/Article/details/gtlcmysewr.html

Ruby: s.split(",");  s.split
来源：http://dali.0kj1m.cn/Article/details/gtwvvxbheu.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.mhx1999.top/Article/details/gtjubtfspn.html

[E08] 数组按分隔符合并
来源：http://dali.yueranfly.top/Article/details/gtyxnpoiri.html

Py:   ",".join(items)
来源：http://dali.316326.xyz/Article/details/gtjxjdlyhd.html

PHP:  implode(",", $items);
来源：http://dali.yuanzhike.top/Article/details/gttoadmibm.html

JS:   items.join(",")
来源：http://dali.sxryk.cn/Article/details/gtbpvvxbyp.html

TS:   items.join(",")
来源：http://dali.c1oappe.top/Article/details/gtlylfkhup.html

Java: String.join(",", items)
来源：http://dali.hnxiangtu.top/Article/details/gtriagpdqj.html

Go:   strings.Join(items, ",")
来源：http://dali.ybcxt.top/Article/details/gtwoshlftl.html

Ruby: items.join(",")
来源：http://dali.zycfv.cn/Article/details/gtjbjbanmq.html

C#:   string.Join(",", items)
来源：http://dali.shzxlz.cn/Article/details/gtihvwdlph.html

[E09] 去除所有空白字符
来源：http://dali.shanyushiyangkeji.top/Article/details/gtobnmuyrn.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhiwuduotai.top/Article/details/gttkrlfrbv.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.kuanghao11.cn/Article/details/gtlnniiigs.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.guannengcc.top/Article/details/gtkxqgjxcy.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.pycfn.com/Article/details/gtdhtjcoln.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.mhx1999.top/Article/details/gtslzvumii.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.cashguo.top/Article/details/gtaabvppav.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.dashuyun.cn/Article/details/gtiypfhdpo.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.haohaochexian.top/Article/details/gtepoqwuva.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhaomingkeji.xyz/Article/details/gtytlrtngq.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.cdnleiting.top/Article/details/gtzvycidls.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.xylfe.cn/Article/details/gtfgqlsbgs.html

JS:   "7".padStart(3, "0")
来源：http://dali.jinqigufen.top/Article/details/gtwxubbboq.html

TS:   "7".padStart(3, "0")
来源：http://dali.yangfankeji.com/Article/details/gteqllprze.html

Java: String.format("%03d", 7)
来源：http://dali.gaohongyu789.top/Article/details/gtvkbxubum.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.shanyushiyangtech.top/Article/details/gtbsufkixh.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.chenjidiqi.icu/Article/details/gtkcverjzi.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.daxiang520.top/Article/details/gtgkmjasml.html

[E11] 反转字符串
来源：http://dali.fengsongda.top/Article/details/gtgrsaaize.html

Py:   s[::-1]
来源：http://dali.tian-w.cn/Article/details/gtactzhsjc.html

PHP:  strrev($s);
来源：http://dali.nanxinkj.top/Article/details/gtwfxjivtr.html

JS:   [...s].reverse().join("")
来源：http://dali.jqgfzy.top/Article/details/gtqgitgubc.html

TS:   [...s].reverse().join("")
来源：http://dali.hywenlv.cn/Article/details/gtiepfpczy.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.ehwqpu.com/Article/details/gthawvglib.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jinqigufen.top/Article/details/gtnwotvpxa.html

Ruby: s.reverse
来源：http://dali.jqgfzy.top/Article/details/gtsqupxktx.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.mhx1999.top/Article/details/gtnklitxtc.html

[E12] 统计某字符出现次数
来源：http://dali.hnqzz.top/Article/details/gtyuqpsnue.html

Py:   s.count("a")
来源：http://dali.xinyue.icu/Article/details/gtlrnhmsxt.html

PHP:  substr_count($s, "a");
来源：http://dali.daria6918.cn/Article/details/gtrndxwfik.html

JS:   s.split("a").length - 1
来源：http://dali.aibaodan.cn/Article/details/gtlcydsvre.html

TS:   s.split("a").length - 1
来源：http://dali.shuidangran.top/Article/details/gtvvtamamr.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.iojbl.cn/Article/details/gtqvbwzapd.html

Go:   strings.Count(s, "a")
来源：http://dali.chenzaomai.com/Article/details/gtgwggjngn.html

Ruby: s.count("a")
来源：http://dali.birdmap.top/Article/details/gtnqdikiig.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhijiandao.cn/Article/details/gtudffrphf.html

[E13] 逐字符遍历
来源：http://dali.jqgufenzy.top/Article/details/gtnvthwkav.html

Py:   for ch in s: print(ch)
来源：http://dali.cdnleiting.top/Article/details/gthbxjbynf.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.hongshengwenyu.top/Article/details/gtvimufrbi.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yj20258888.top/Article/details/gtbujvjbls.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgnxykuxj.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.tianlin.xyz/Article/details/gtkdduuara.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.snrcjt.cn/Article/details/gtsbqjbnfy.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.chenlongwang.top/Article/details/gterjmfcog.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.9152youxi.cn/Article/details/gtnwdmrwjp.html

[E14] URL 编码与 Base64
来源：http://dali.shanyushiyangtech.top/Article/details/gtvlouamrh.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hysaishi.cn/Article/details/gtxivarxua.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.pengpengdd.cyou/Article/details/gtljgkxujx.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.xziqi.cn/Article/details/gtnlwyijbu.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.hfpthk.cn/Article/details/gtsaljpwaf.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yuxming.cn/Article/details/gtvmylvwyr.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.svipenyu.cn/Article/details/gtuiaitmdr.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.ivvv.top/Article/details/gtuuiiflya.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.316326.xyz/Article/details/gtzbrxmqgp.html

[E15] HTML 转义 / 反转义
来源：http://dali.xylfe.cn/Article/details/gtjifelvmv.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.shuidangran.top/Article/details/gtyddzlakx.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.daxiang520.top/Article/details/gtmbpgtiem.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.wangdashe.top/Article/details/gtmyqyokxg.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.fzhhl.top/Article/details/gtgusppgpf.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.pengpengdd.cyou/Article/details/gtahmndxan.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hnxiangtu.top/Article/details/gthfkskrux.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.shzxlz.cn/Article/details/gtjzmgipra.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.aibaodan.cn/Article/details/gtegnxeraz.html

[E16] 数字千分位
来源：http://dali.shanyushiyangkeji.top/Article/details/gtchckjatp.html

Py:   f"{1234567:,}"
来源：http://dali.sufxvd.cn/Article/details/gtullqsimd.html

PHP:  number_format(1234567);
来源：http://dali.daria6918.cn/Article/details/gtvcbsedeq.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.xuetiantiany.cn/Article/details/gtjgjjbzdp.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.redwolf501.top/Article/details/gtldscuzfm.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gtanoloubp.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.cheryme.top/Article/details/gtxnjgcpnl.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.iojbl.cn/Article/details/gtrxtklkep.html

C#:   1234567.ToString("N0")
来源：http://dali.redwolf501.top/Article/details/gtufjuwymh.html

[E17] 首字母大写
来源：http://dali.vqdsnc.cn/Article/details/gtsyiencsw.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.sufxvd.cn/Article/details/gtvonnssgx.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteprjtjti.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cucudq.cn/Article/details/gtaacfrqnb.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hywenlv.cn/Article/details/gtgyoudtjf.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtrxzhgyue.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhengqikj.top/Article/details/gtdbnoxmjz.html

Ruby: s.capitalize
来源：http://dali.tanke756.top/Article/details/gtnldkzyyo.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.mhx1999.top/Article/details/gtjxgkhbah.html

[E18] 模板占位符替换
来源：http://dali.cashguo.top/Article/details/gtzxvyjiez.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.shangyingyoupin.top/Article/details/gtbewnauub.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yvedp.cn/Article/details/gtfvohpcju.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jyoumei.cn/Article/details/gthxcbknbu.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.xuetiantiany.cn/Article/details/gtakwfutgj.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yj20258888.top/Article/details/gtuluxkrcp.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.xuetiantiany.cn/Article/details/gtkzgnhrbb.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.wangdashe.top/Article/details/gthdfrvgpb.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.svipenyu.cn/Article/details/gtjtzqmcsw.html

[E19] 多行文本按行拆分
来源：http://dali.xuetiantiany.cn/Article/details/gtieqsznwg.html

Py:   s.splitlines()
来源：http://dali.yanxiufei.cn/Article/details/gtwmieteuu.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.shzxlz.cn/Article/details/gtwlmvtbpw.html

JS:   s.split(/\r?\n/)
来源：http://dali.tanke756.top/Article/details/gtkvaxpbdz.html

TS:   s.split(/\r?\n/)
来源：http://dali.tanke756.top/Article/details/gtykwespov.html

Java: s.lines().toList()
来源：http://dali.jianghu66.top/Article/details/gtvtjmegcw.html

Go:   strings.Split(s, "\n")
来源：http://dali.birdmap.top/Article/details/gtmwfaatpc.html

Ruby: s.lines
来源：http://dali.gotoacloud.top/Article/details/gtylzjcavn.html

C#:   s.Split('\n')
来源：http://dali.jinyuanbaomall.cn/Article/details/gtixxpovgo.html

[E20] 判断字符串是否为空
来源：http://dali.yuanzhike.top/Article/details/gtvocqaadb.html

Py:   if not s:
来源：http://dali.tian-w.cn/Article/details/gtlzsmslat.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtagbwvznp.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jianghu66.top/Article/details/gtbagmqlur.html

TS:   if (s === "") {}
来源：http://dali.aibaodan.cn/Article/details/gthzldeiat.html

Java: if (s.isEmpty()) {}
来源：http://dali.c1oappe.top/Article/details/gtcbkdxnoa.html

Go:   if s == "" {}
来源：http://dali.xinyue.icu/Article/details/gthybjfocb.html

Ruby: if s.empty?
来源：http://dali.haohaochexian.top/Article/details/gtmyeigolr.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.tianlin.xyz/Article/details/gtirpkxhzi.html

[E21] 超长截断加省略号
来源：http://dali.c1oappe.top/Article/details/gtjpldwcaj.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhixingplan.top/Article/details/gtrenfbrpt.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.smart0.xyz/Article/details/gtokvykpco.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shanyushiyangkeji.top/Article/details/gtftgqgznt.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ybcxt.top/Article/details/gtotkezfnt.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.cucudq.cn/Article/details/gtjrwgefmn.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xinyue.icu/Article/details/gtqgmvxiwr.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.aibaodan.cn/Article/details/gtslyuaypm.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.bjfxy.top/Article/details/gtvfolpxub.html

[E22] 字节长度与字符长度
来源：http://dali.chenjidiqi.icu/Article/details/gtmsyexbok.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.haohaochexian.top/Article/details/gtihiozdfv.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yj20258888.top/Article/details/gtioiwhchd.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yuanzhike.top/Article/details/gtkfiwmaqu.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cucudq.cn/Article/details/gtqzlqlaxh.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.sweek.top/Article/details/gtlbxdcmrg.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hnqzz.top/Article/details/gtihljipjm.html

Ruby: s.bytesize;  s.length
来源：http://dali.9152youxi.cn/Article/details/gtincfroon.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.nanxinkj.top/Article/details/gtjuguuymi.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtbmvclkas.html

F. 文件与目录
来源：http://dali.feifeiyinyue.top/Article/details/gtdwcteidd.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtsjpvmpkw.html

[F01] 读取整个文件
来源：http://dali.yongpay.top/Article/details/gtlhngyrvx.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.guowangkeji.top/Article/details/gtirsksbew.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gteabikhxu.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yueranfly.top/Article/details/gtmqxzkmyr.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zdqjudy.top/Article/details/gtmxiuhtmo.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.tanke756.top/Article/details/gtqlqxtojo.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.smart0.xyz/Article/details/gtntbjwnxf.html

Ruby: File.read("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtcycukqaj.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.gotoacloud.top/Article/details/gthhjbehws.html

[F02] 逐行读取文件
来源：http://dali.daria6918.cn/Article/details/gttivehdts.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jinqigfzy.top/Article/details/gteiuflrzf.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.gotoacloud.top/Article/details/gtvnzlkdfv.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yuanzhike.top/Article/details/gtsguhjccl.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yvedp.cn/Article/details/gtzjaoadrn.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.wangshuangyany.cn/Article/details/gtdghpsutw.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.sufxvd.cn/Article/details/gtkcvchikg.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yj20258888.top/Article/details/gtwguodzou.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.316326.xyz/Article/details/gtmsklbosj.html

[F03] 写入文件（覆盖）
来源：http://dali.tanke756.top/Article/details/gttwxfpyat.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.ybcxt.top/Article/details/gttdemauxl.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xuanzx.com/Article/details/gtgnudzctd.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj202588.top/Article/details/gtmulzkiwy.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jiagoushi.top/Article/details/gtapylnsmu.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.pycfn.com/Article/details/gtxkeuaabi.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoumzezmk.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtudwqqmgf.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtreiookwm.html

[F04] 追加写入文件
来源：http://dali.jiagoushi.top/Article/details/gtmtyzothj.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.daxiang520.top/Article/details/gtmpdcnqah.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.tianlin.xyz/Article/details/gtcdrfbfif.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtabugxmyj.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hysaishi.cn/Article/details/gtlouvfbdh.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfmzhoazj.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.nwbrower.top/Article/details/gthjbymcvx.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.ppjwa.cn/Article/details/gtellipwvl.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.birdmap.top/Article/details/gtpjqjqsvp.html

[F05] 判断文件或目录是否存在
来源：http://dali.jlsjyb.cn/Article/details/gtjycxobsa.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.c1oappe.top/Article/details/gtuogjiyvq.html

PHP:  file_exists("a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gtodbftkve.html

JS:   fs.existsSync("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtgenllehc.html

TS:   fs.existsSync("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtensnalqk.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.ybcxt.top/Article/details/gtfowrjxgi.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.nanxinkj.top/Article/details/gtdgvsawrb.html

Ruby: File.exist?("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gthwjudvbk.html

C#:   File.Exists("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtxwbdajrr.html

[F06] 删除文件
来源：http://dali.hnqzz.top/Article/details/gtaiyivtrb.html

Py:   os.remove("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtuouxkhvg.html

PHP:  unlink("a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gtrozzgvvk.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.sweek.top/Article/details/gtysyerskx.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.cheryme.top/Article/details/gteodidehu.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.haohaochexian.top/Article/details/gtsrrlpmxo.html

Go:   os.Remove("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtqmvpbmls.html

Ruby: File.delete("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtstjcnhfq.html

C#:   File.Delete("a.txt");
来源：http://dali.cucudq.cn/Article/details/gtoliozbcr.html

[F07] 创建目录（含多级）
来源：http://dali.jlsjyb.cn/Article/details/gtaixbwhxa.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jianghu66.top/Article/details/gtdgsnefuh.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.wangdashe.top/Article/details/gtwmofnxco.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.haohaochexian.top/Article/details/gtodgaovqr.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.meibo888.top/Article/details/gtnaofjtqg.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.0kj1m.cn/Article/details/gtydnrvrjx.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jinghuilouyu.cn/Article/details/gtncgkaubz.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hywenlv.cn/Article/details/gtnxbmadgj.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.vqdsnc.cn/Article/details/gtfiisnsfg.html

[F08] 遍历目录
来源：http://dali.aibaodan.cn/Article/details/gttlvwruwz.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.tianlin.xyz/Article/details/gtyghbuygp.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hongshengwenyu.top/Article/details/gtubqopnmc.html

JS:   fs.readdirSync("dir")
来源：http://dali.gzhubu.top/Article/details/gtqrbayyyg.html

TS:   fs.readdirSync("dir")
来源：http://dali.birdmap.top/Article/details/gtygxnnzsy.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhongyouzk.top/Article/details/gtywixtgzx.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpxoagfiy.html

Ruby: Dir.children("dir")
来源：http://dali.quarkkingdee.top/Article/details/gtsimefhxn.html

C#:   Directory.GetFiles("dir")
来源：http://dali.xziqi.cn/Article/details/gtaekchxyw.html

[F09] 获取文件大小
来源：http://dali.cheryme.top/Article/details/gtkrkwpfxx.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtjvjqidbo.html

PHP:  filesize("a.txt");
来源：http://dali.yonumen.top/Article/details/gtufpkmmqc.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ppjwa.cn/Article/details/gtidoqzuzh.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hammf.cn/Article/details/gtmyhvbkfb.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.nwbrower.top/Article/details/gtmqbbxuez.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.cqqwz.cn/Article/details/gtumshdnnx.html

Ruby: File.size("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtjgkmeaua.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.guowangkeji.top/Article/details/gtamfjtmih.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hammf.cn/Article/details/gtxapqqtjp.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ydzc1.top/Article/details/gtlpbtvctg.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gtvhkevmbl.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.havefunace.top/Article/details/gthcsmjxjj.html

TS:   path.extname("a.txt")
来源：http://dali.bjfxy.top/Article/details/gthspwdpuj.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.fzhhl.top/Article/details/gtntjxrffa.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgftnbihe.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtszmaaqrd.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtpjolzial.html

[F11] 复制与移动文件
来源：http://dali.sxryk.cn/Article/details/gtbtbcyllv.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xziqi.cn/Article/details/gthfgypnli.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hfpthk.cn/Article/details/gtfpvsuroq.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gzhubu.top/Article/details/gtplzivdwq.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenzaomai.com/Article/details/gtmsiqueid.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jyoumei.cn/Article/details/gtcwfvygjq.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jiagoushi.top/Article/details/gtsvshyiee.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.chenzaomai.com/Article/details/gtzhtqugtt.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jianghu66.top/Article/details/gtbnliksng.html

[F12] CSV 读写
来源：http://dali.xylfe.cn/Article/details/gtvqghupyo.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xuanzx.com/Article/details/gtipxwfiuy.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.gotoacloud.top/Article/details/gtdlkmneqh.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.gzhubu.top/Article/details/gtzkldhmtr.html

TS:   // 同上
来源：http://dali.xuanzx.com/Article/details/gtnkirdate.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yuxming.cn/Article/details/gtpglgkmns.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hfpthk.cn/Article/details/gtgadtkiod.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ehwqpu.com/Article/details/gtbmetgeuq.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yonumen.top/Article/details/gtwiyrocgn.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtuylfedrp.html

G. 面向对象
来源：http://dali.gzhubu.top/Article/details/gtrexiuzkp.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtohumsvtb.html

[G01] 定义类
来源：http://dali.zhongyouzk.top/Article/details/gtamvpyats.html

Py:   class User: pass
来源：http://dali.pengpengdd.cyou/Article/details/gtodhqpqjv.html

PHP:  class User {}
来源：http://dali.mhx1999.top/Article/details/gtnqdosojw.html

JS:   class User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtcephgiob.html

TS:   class User { name: string = ""; }
来源：http://dali.zhiwuduotai.top/Article/details/gttodonwzf.html


<!-- 参考信息 -->