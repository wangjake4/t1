代发 wailian999

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aiyqwxqr.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.snrcjt.cn/Article/details/gt2vmusllyt.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.nanxuanxn.top/Article/details/gt2ajytpodo.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2alpowxdl.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhoulong.xyz/Article/details/gt2rdzrlohh.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.xuanzx.com/Article/details/gt2daxhgcos.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.svipenyu.cn/Article/details/gt2obedfitr.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.mhx1999.top/Article/details/gt2xrbvbzti.html

[E06] 替换子串
来源：http://dali.yj20258888.top/Article/details/gt2pjcjlbmh.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.aizwys.cn/Article/details/gt2yfuoxbvk.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jqgfzy.top/Article/details/gt2ctybwmlc.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shangyingyoupin.top/Article/details/gt2dxizrjle.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yuanzhike.top/Article/details/gt2jekpjklg.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yongpay.top/Article/details/gt2vxgwowtk.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mksrlfcu.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.tanke756.top/Article/details/gt2ibwjcngo.html

C#:   s.Replace("a", "b")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ipxrvjsu.html

[E07] 按分隔符拆分
来源：http://dali.tanke756.top/Article/details/gt2euzrbwzo.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.iojbl.cn/Article/details/gt2jzukrvxm.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.snrcjt.cn/Article/details/gt2xevkumql.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.cqqwz.cn/Article/details/gt2ambrtayu.html

TS:   s.split(",")
来源：http://dali.wangshuangyany.cn/Article/details/gt2katqmzee.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yj20258888.top/Article/details/gt2dmhcucio.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.daria6918.cn/Article/details/gt2tkmuwuob.html

Ruby: s.split(",");  s.split
来源：http://dali.pycfn.com/Article/details/gt2hxgxzxtn.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.wangshuangyany.cn/Article/details/gt2qoxffkfz.html

[E08] 数组按分隔符合并
来源：http://dali.guowangkeji.top/Article/details/gt2suuqrxoy.html

Py:   ",".join(items)
来源：http://dali.sysykeji.top/Article/details/gt2thcklcfy.html

PHP:  implode(",", $items);
来源：http://dali.cucudq.cn/Article/details/gt2grcttzbb.html

JS:   items.join(",")
来源：http://dali.hammf.cn/Article/details/gt2vdzdodkl.html

TS:   items.join(",")
来源：http://dali.ppjwa.cn/Article/details/gt2hzdgnwyz.html

Java: String.join(",", items)
来源：http://dali.gzhubu.top/Article/details/gt2smtxxtfp.html

Go:   strings.Join(items, ",")
来源：http://dali.haohaochexian.top/Article/details/gt2cxypwepy.html

Ruby: items.join(",")
来源：http://dali.jlsjyb.cn/Article/details/gt2ejdcosjb.html

C#:   string.Join(",", items)
来源：http://dali.smart0.xyz/Article/details/gt2ahaiuqev.html

[E09] 去除所有空白字符
来源：http://dali.snrcjt.cn/Article/details/gt2naqwepnj.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.dianchejie.cn/Article/details/gt2bjawqhla.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.cdnleiting.top/Article/details/gt2atsxcctq.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.sxryk.cn/Article/details/gt2tvomjokn.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.fengsongda.top/Article/details/gt2mqexgyqe.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.ppjwa.cn/Article/details/gt2mdgyegua.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.daxiang520.top/Article/details/gt2wnhpiokb.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zitmjqug.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.nanxinkj.top/Article/details/gt2nhgqbdnf.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yuanzhike.top/Article/details/gt2gilzgros.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.shzxlz.cn/Article/details/gt2qbneaolq.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.pengpengdd.cyou/Article/details/gt2lmqgkfjy.html

JS:   "7".padStart(3, "0")
来源：http://dali.c1oappe.top/Article/details/gt2jjulecnm.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhiwuduotai.top/Article/details/gt2prjobdii.html

Java: String.format("%03d", 7)
来源：http://dali.zhixingplan.top/Article/details/gt2enolipmn.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.smart0.xyz/Article/details/gt2sklcphbv.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yj20258888.top/Article/details/gt2gzbwfrom.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yvedp.cn/Article/details/gt2uupfbvyp.html

[E11] 反转字符串
来源：http://dali.9152youxi.cn/Article/details/gt2avwdqqnp.html

Py:   s[::-1]
来源：http://dali.snrcjt.cn/Article/details/gt2bhgbjqbe.html

PHP:  strrev($s);
来源：http://dali.quarkkingdee.top/Article/details/gt2hlirourx.html

JS:   [...s].reverse().join("")
来源：http://dali.zhiwuduotai.top/Article/details/gt2rjawuwnq.html

TS:   [...s].reverse().join("")
来源：http://dali.quarkkingdee.top/Article/details/gt2uurffdob.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.fengsongda.top/Article/details/gt2rgitptku.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.chenzaomai.com/Article/details/gt2nregjfhv.html

Ruby: s.reverse
来源：http://dali.c1oappe.top/Article/details/gt2gzhliner.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.daxiang520.top/Article/details/gt2ylpcwdsz.html

[E12] 统计某字符出现次数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gqwboazb.html

Py:   s.count("a")
来源：http://dali.havefunace.top/Article/details/gt2zepyqfye.html

PHP:  substr_count($s, "a");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2feikvzef.html

JS:   s.split("a").length - 1
来源：http://dali.bjfxy.top/Article/details/gt2ldektfcm.html

TS:   s.split("a").length - 1
来源：http://dali.gzhubu.top/Article/details/gt2xpgbztor.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.chenzaomai.com/Article/details/gt2dqvujhsx.html

Go:   strings.Count(s, "a")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cpfjdriq.html

Ruby: s.count("a")
来源：http://dali.zdqjudy.top/Article/details/gt2catdjboo.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhoulong.xyz/Article/details/gt2ectagvpe.html

[E13] 逐字符遍历
来源：http://dali.jinqigfzy.top/Article/details/gt2iueeuqyv.html

Py:   for ch in s: print(ch)
来源：http://dali.jiagoushi.top/Article/details/gt2gjnjirym.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.xylfe.cn/Article/details/gt2pmenbtyk.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gotoacloud.top/Article/details/gt2gxqzglwv.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.bjfxy.top/Article/details/gt2lbfjfuvt.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhixingplan.top/Article/details/gt2bgvwiaec.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jinqigufen.top/Article/details/gt2xpmaqolv.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.pycfn.com/Article/details/gt2dooyirmj.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.shuidangran.top/Article/details/gt2wsjfxwae.html

[E14] URL 编码与 Base64
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ljsiltei.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.sweek.top/Article/details/gt2olxborhv.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.316326.xyz/Article/details/gt2wdzrijuw.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jlsjyb.cn/Article/details/gt2wtkpgxxq.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.meibo888.top/Article/details/gt2ccgvaswx.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yvedp.cn/Article/details/gt2vuqkodyx.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.mhx1999.top/Article/details/gt2ieghmjyr.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.bjfxy.top/Article/details/gt2ywxilhdk.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ascfhwxu.html

[E15] HTML 转义 / 反转义
来源：http://dali.hysaishi.cn/Article/details/gt2vndndxed.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ofgctxgc.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jinqigufen.top/Article/details/gt2vebtlzca.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jiagoushi.top/Article/details/gt2bflxazif.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.ehwqpu.com/Article/details/gt2auhfgcsj.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yuxming.cn/Article/details/gt2pxjeyvni.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qwxqsvtr.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.haohaochexian.top/Article/details/gt2gqllomsa.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.smart0.xyz/Article/details/gt2hkikyylg.html

[E16] 数字千分位
来源：http://dali.chenjidiqi.icu/Article/details/gt2xtdnvcuy.html

Py:   f"{1234567:,}"
来源：http://dali.pycfn.com/Article/details/gt2pskhfsbp.html

PHP:  number_format(1234567);
来源：http://dali.havefunace.top/Article/details/gt2xowlralw.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yvedp.cn/Article/details/gt2frhcinqh.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhengqikj.top/Article/details/gt2tderhtko.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.nanxinkj.top/Article/details/gt2vajkjqvh.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.meibo888.top/Article/details/gt2ubxagggp.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.gotoacloud.top/Article/details/gt2doolxles.html

C#:   1234567.ToString("N0")
来源：http://dali.wangshuangyany.cn/Article/details/gt2pegpssaw.html

[E17] 首字母大写
来源：http://dali.fengsongda.top/Article/details/gt2xwjlpkcy.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.daxiang520.top/Article/details/gt2nihzelym.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.aibaodan.cn/Article/details/gt2lfuacpfq.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xziqi.cn/Article/details/gt2imhrvmtz.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sxryk.cn/Article/details/gt2nosfeqml.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.cashguo.top/Article/details/gt2iaozcnpj.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.iojbl.cn/Article/details/gt2wtjbkfvr.html

Ruby: s.capitalize
来源：http://dali.yangfankeji.com/Article/details/gt2iydfhsbw.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.shzxlz.cn/Article/details/gt2opwnpsmq.html

[E18] 模板占位符替换
来源：http://dali.yonumen.top/Article/details/gt2zzopkmoh.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tzashnbx.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.ppjwa.cn/Article/details/gt2wnhlyhom.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.havefunace.top/Article/details/gt2ibrnouxc.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lzpzyznz.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.ehwqpu.com/Article/details/gt2lfvftpjm.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.ydzc1.top/Article/details/gt2sicdlrrv.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.redwolf501.top/Article/details/gt2tizgloie.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.cdnleiting.top/Article/details/gt2wamyamia.html

[E19] 多行文本按行拆分
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ncvckxik.html

Py:   s.splitlines()
来源：http://dali.jianghu66.top/Article/details/gt2lgzdxdqr.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qicilpxf.html

JS:   s.split(/\r?\n/)
来源：http://dali.cashguo.top/Article/details/gt2gcerchwt.html

TS:   s.split(/\r?\n/)
来源：http://dali.jlsjyb.cn/Article/details/gt2gftfzbyb.html

Java: s.lines().toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mmhzrfke.html

Go:   strings.Split(s, "\n")
来源：http://dali.nanxinkj.top/Article/details/gt2fnyjonqa.html

Ruby: s.lines
来源：http://dali.ehwqpu.com/Article/details/gt2hzodltnz.html

C#:   s.Split('\n')
来源：http://dali.yonumen.top/Article/details/gt2wviwailm.html

[E20] 判断字符串是否为空
来源：http://dali.yvedp.cn/Article/details/gt2rgpvfsar.html

Py:   if not s:
来源：http://dali.xylfe.cn/Article/details/gt2lijkwsnr.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.sweek.top/Article/details/gt2hhnrscfi.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jinqigufen.top/Article/details/gt2gomymxgi.html

TS:   if (s === "") {}
来源：http://dali.pycfn.com/Article/details/gt2predaecs.html

Java: if (s.isEmpty()) {}
来源：http://dali.redwolf501.top/Article/details/gt2oggldyzv.html

Go:   if s == "" {}
来源：http://dali.gotoacloud.top/Article/details/gt2zuwzldja.html

Ruby: if s.empty?
来源：http://dali.dianchejie.cn/Article/details/gt2twrseeeh.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.birdmap.top/Article/details/gt2hugcawvx.html

[E21] 超长截断加省略号
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2loklzgbo.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hnqzz.top/Article/details/gt2qhyijpgn.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.tianlin.xyz/Article/details/gt2zyitpaul.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.pengpengdd.cyou/Article/details/gt2egqtvlia.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sweek.top/Article/details/gt2wijqozdo.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hysaishi.cn/Article/details/gt2fiukiabg.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.chenjidiqi.icu/Article/details/gt2iwafmepi.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.daxiang520.top/Article/details/gt2qdynogbk.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jianghu66.top/Article/details/gt2yubdlgkv.html

[E22] 字节长度与字符长度
来源：http://dali.hongshengwenyu.top/Article/details/gt2ukuwoiqf.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.sysykeji.top/Article/details/gt2raqxneja.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xylfe.cn/Article/details/gt2boqgzwmn.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.fzhhl.top/Article/details/gt2xsqbnpyd.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cashguo.top/Article/details/gt2gmhzeplx.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.bjfxy.top/Article/details/gt2krjdgnqx.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.fengsongda.top/Article/details/gt2qubhunro.html

Ruby: s.bytesize;  s.length
来源：http://dali.havefunace.top/Article/details/gt2qvroedoo.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.nanxuanxn.top/Article/details/gt2yqeqjbwr.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2wkwbakzw.html

F. 文件与目录
来源：http://dali.ehwqpu.com/Article/details/gt2uduktfju.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2qlqhcweu.html

[F01] 读取整个文件
来源：http://dali.sufxvd.cn/Article/details/gt2srdplqwk.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jlsjyb.cn/Article/details/gt2pgmejdns.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uisidpzn.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.kuanghao11.cn/Article/details/gt2dsldfehs.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.tian-w.cn/Article/details/gt2aenkxgge.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hcfbubge.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2ehxueeuz.html

Ruby: File.read("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2tgibcwjv.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gt2fytaared.html

[F02] 逐行读取文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ysmkrror.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hammf.cn/Article/details/gt2gphlluhg.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ambjsefw.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ppjwa.cn/Article/details/gt2jsejzmlt.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.tanke756.top/Article/details/gt2vxkiuqfe.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yvedp.cn/Article/details/gt2ycvjfgyz.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.shangyingyoupin.top/Article/details/gt2pubyixst.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.gzhubu.top/Article/details/gt2qvfkacoh.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jiagoushi.top/Article/details/gt2guwxydwr.html

[F03] 写入文件（覆盖）
来源：http://dali.yuxming.cn/Article/details/gt2hkolcwrv.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hongshengwenyu.top/Article/details/gt2sfncqwwz.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jlsjyb.cn/Article/details/gt2rhmbctzq.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.nanxuanxn.top/Article/details/gt2wlllrucw.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xuanzx.com/Article/details/gt2fvwyqfcw.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.chenlongwang.top/Article/details/gt2nnenbjyr.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.wangdashe.top/Article/details/gt2riucrgxw.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jiagoushi.top/Article/details/gt2pjmaeeaq.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.gogol.net.cn/Article/details/gt2cmafrzwg.html

[F04] 追加写入文件
来源：http://dali.gzhubu.top/Article/details/gt2jikdgjuw.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ybcxt.top/Article/details/gt2gpfqnqri.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.wangshuangyany.cn/Article/details/gt2xnuotcze.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.redwolf501.top/Article/details/gt2fdzzltcf.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nanxuanxn.top/Article/details/gt2qawiaxme.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.gotoacloud.top/Article/details/gt2btxczxcs.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.gzhubu.top/Article/details/gt2cbnozozh.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.316326.xyz/Article/details/gt2yuvxnmuk.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.meibo888.top/Article/details/gt2idzirkdt.html

[F05] 判断文件或目录是否存在
来源：http://dali.wangdashe.top/Article/details/gt2iyqhwvmg.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ydzc1.top/Article/details/gt2wdxfjfll.html

PHP:  file_exists("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gt2waetnsmv.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kqgagdia.html

TS:   fs.existsSync("a.txt")
来源：http://dali.daxiang520.top/Article/details/gt2twuisorg.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hysaishi.cn/Article/details/gt2jjnsfsrx.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.wangshuangyany.cn/Article/details/gt2pozciztl.html

Ruby: File.exist?("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2eahiifsj.html

C#:   File.Exists("a.txt")
来源：http://dali.meibo888.top/Article/details/gt2yzzozllw.html

[F06] 删除文件
来源：http://dali.cheryme.top/Article/details/gt2ximwuigy.html

Py:   os.remove("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uxrkmedl.html

PHP:  unlink("a.txt");
来源：http://dali.cheryme.top/Article/details/gt2jkxepfzo.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2ltwmwojr.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2jxwzwneg.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.chenzaomai.com/Article/details/gt2djtqhykc.html

Go:   os.Remove("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2mpnwpidi.html

Ruby: File.delete("a.txt")
来源：http://dali.aizwys.cn/Article/details/gt2bgmknvin.html

C#:   File.Delete("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gt2xmodajgo.html

[F07] 创建目录（含多级）
来源：http://dali.sweek.top/Article/details/gt2szcddcjv.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.svipenyu.cn/Article/details/gt2excnidpd.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.quarkkingdee.top/Article/details/gt2stxcrhhk.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yonumen.top/Article/details/gt2ujgibewo.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hysaishi.cn/Article/details/gt2sppuoyrj.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.cheryme.top/Article/details/gt2xswcxapf.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hammf.cn/Article/details/gt2uiqaehig.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.andypj.xyz/Article/details/gt2ftfmifpl.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.snrcjt.cn/Article/details/gt2nsjhvjqk.html

[F08] 遍历目录
来源：http://dali.daxiang520.top/Article/details/gt2kszconor.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2brrtmlvo.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.cashguo.top/Article/details/gt2bdkhxudk.html

JS:   fs.readdirSync("dir")
来源：http://dali.yuxming.cn/Article/details/gt2jkuuidlg.html

TS:   fs.readdirSync("dir")
来源：http://dali.pengpengdd.cyou/Article/details/gt2qwzgvvzd.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.bjfxy.top/Article/details/gt2hdcazini.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.bjfxy.top/Article/details/gt2pxsmewfg.html

Ruby: Dir.children("dir")
来源：http://dali.aibaodan.cn/Article/details/gt2gsfjgwee.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eualuhuh.html

[F09] 获取文件大小
来源：http://dali.gogol.net.cn/Article/details/gt2vemupkxm.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yj202588.top/Article/details/gt2cnaagbpg.html

PHP:  filesize("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ikeccxaz.html

JS:   fs.statSync("a.txt").size
来源：http://dali.shanyushiyangtech.top/Article/details/gt2btaadvvq.html

TS:   fs.statSync("a.txt").size
来源：http://dali.wangdashe.top/Article/details/gt2sgbbctdd.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vmoxyafo.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.snrcjt.cn/Article/details/gt2cvxrntkg.html

Ruby: File.size("a.txt")
来源：http://dali.mhx1999.top/Article/details/gt2smsdwgla.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yj20258.top/Article/details/gt2zqplxgtb.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jqgufenzy.top/Article/details/gt2hkdrlqdi.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2ngupmttf.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.9152youxi.cn/Article/details/gt2xdfwfjph.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2trhlknfh.html

TS:   path.extname("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2qwvgxyxk.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.tian-w.cn/Article/details/gt2nprwvifs.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2rbpeuxpt.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.meibo888.top/Article/details/gt2qozwpjtz.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zloiwcnm.html

[F11] 复制与移动文件
来源：http://dali.xziqi.cn/Article/details/gt2lphakyzs.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.nwbrower.top/Article/details/gt2lghjqpqw.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.bjfxy.top/Article/details/gt2rjetekvg.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yonumen.top/Article/details/gt2zdmtrlhm.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kdgffqur.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.cashguo.top/Article/details/gt2rneptegi.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.haohaochexian.top/Article/details/gt2qrbhfokj.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2stpgmjft.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.haohaochexian.top/Article/details/gt2ivoboqhb.html

[F12] CSV 读写
来源：http://dali.aizwys.cn/Article/details/gt2keuzugmj.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.nanxinkj.top/Article/details/gt2bsidvbdd.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.meibo888.top/Article/details/gt2dwvqpqfg.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.havefunace.top/Article/details/gt2rnzlujyr.html

TS:   // 同上
来源：http://dali.zdqjudy.top/Article/details/gt2fohxzkpm.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xinyue.icu/Article/details/gt2yheoqqxo.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zdqjudy.top/Article/details/gt2cibyykbs.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.sysykeji.top/Article/details/gt2dbvondjw.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.bjfxy.top/Article/details/gt2sudhfdpn.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2chqyqoel.html

G. 面向对象
来源：http://dali.vqdsnc.cn/Article/details/gt2dksmbbhn.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2usdezhpe.html

[G01] 定义类
来源：http://dali.ydzc1.top/Article/details/gt2grphsfvy.html

Py:   class User: pass
来源：http://dali.iojbl.cn/Article/details/gt2ddxzytut.html

PHP:  class User {}
来源：http://dali.gzhubu.top/Article/details/gt2bioqvvjf.html

JS:   class User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dntaayph.html

TS:   class User { name: string = ""; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rjpzhler.html

Java: class User {}
来源：http://dali.c1oappe.top/Article/details/gt2bbkwcwsx.html

Go:   type User struct { Name string }
来源：http://dali.wangshuangyany.cn/Article/details/gt2tjhfxhlf.html

Ruby: class User; end
来源：http://dali.birdmap.top/Article/details/gt2iuuguiaz.html

C#:   class User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gvxjjkat.html

[G02] 构造函数
来源：http://dali.zhixingplan.top/Article/details/gt2rkpnobmd.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yuxming.cn/Article/details/gt2cjqsvuji.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2luohvbvj.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.dashuyun.cn/Article/details/gt2yhmqynzm.html

TS:   constructor(public name: string) {}
来源：http://dali.sxryk.cn/Article/details/gt2lwzxkqlq.html

Java: User(String name) { this.name = name; }
来源：http://dali.sysykeji.top/Article/details/gt2vjqztmhs.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.wangshuangyany.cn/Article/details/gt2pxwiqrpe.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.wangdashe.top/Article/details/gt2acnzjlzl.html

C#:   public User(string name) { Name = name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nvhifxwi.html

[G03] 实例属性
来源：http://dali.daxiang520.top/Article/details/gt2nyrcuxtf.html

Py:   self.name = "x"
来源：http://dali.fengsongda.top/Article/details/gt2qnhozbsf.html

PHP:  public string $name = "x";
来源：http://dali.yuanzhike.top/Article/details/gt2dxlwzexo.html

JS:   this.name = "x";
来源：http://dali.chenjidiqi.icu/Article/details/gt2rakpefob.html

TS:   name: string = "x";
来源：http://dali.ydzc1.top/Article/details/gt2btykdijl.html

Java: private String name;
来源：http://dali.tanke756.top/Article/details/gt2bnlimbrm.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.tianlin.xyz/Article/details/gt2aknidqij.html


<!-- 参考信息 -->