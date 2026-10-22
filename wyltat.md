代发 wailian999

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.shuidangran.top/Article/details/gt2liajrqug.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.smart0.xyz/Article/details/gt2bfmetfkd.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yj202588.top/Article/details/gt2iajkhytu.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhoulong.xyz/Article/details/gt2rbvrthkd.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.guowangkeji.top/Article/details/gt2xozdqxoy.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.aizwys.cn/Article/details/gt2qqkbqrhq.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.nwbrower.top/Article/details/gt2ccxrkydk.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jyoumei.cn/Article/details/gt2tsbvljdk.html

[E06] 替换子串
来源：http://dali.tian-w.cn/Article/details/gt2zmpomauw.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.mhx1999.top/Article/details/gt2tvrhiuyz.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jiagoushi.top/Article/details/gt2omusztff.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jianghu66.top/Article/details/gt2cqvppzgf.html

TS:   s.replaceAll("a", "b")
来源：http://dali.daria6918.cn/Article/details/gt2vbztvrrx.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gt2ycseuvgl.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.kuanghao11.cn/Article/details/gt2wcrnkcpu.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gt2iiturlgd.html

C#:   s.Replace("a", "b")
来源：http://dali.hongshengwenyu.top/Article/details/gt2ybgnkosf.html

[E07] 按分隔符拆分
来源：http://dali.birdmap.top/Article/details/gt2dvtlqqfx.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.vqdsnc.cn/Article/details/gt2lbyacebd.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.tanke756.top/Article/details/gt2zuosurwg.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qiigkltz.html

TS:   s.split(",")
来源：http://dali.nwbrower.top/Article/details/gt2yoohagvh.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.havefunace.top/Article/details/gt2dxhaphmo.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2frajipon.html

Ruby: s.split(",");  s.split
来源：http://dali.chenjidiqi.icu/Article/details/gt2sbhykfjr.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yanxiufei.cn/Article/details/gt2eygxidvt.html

[E08] 数组按分隔符合并
来源：http://dali.sweek.top/Article/details/gt2kxqbhdij.html

Py:   ",".join(items)
来源：http://dali.chenjidiqi.icu/Article/details/gt2gbrqbdbe.html

PHP:  implode(",", $items);
来源：http://dali.sweek.top/Article/details/gt2kaqwsjqf.html

JS:   items.join(",")
来源：http://dali.zdqjudy.top/Article/details/gt2nhljtptq.html

TS:   items.join(",")
来源：http://dali.zhiwuduotai.top/Article/details/gt2ccrbxxek.html

Java: String.join(",", items)
来源：http://dali.xinyue.icu/Article/details/gt2ybyvpxap.html

Go:   strings.Join(items, ",")
来源：http://dali.aizwys.cn/Article/details/gt2cqxeloty.html

Ruby: items.join(",")
来源：http://dali.chenzaomai.com/Article/details/gt2hqucbrck.html

C#:   string.Join(",", items)
来源：http://dali.chenlongwang.top/Article/details/gt2qylvnajn.html

[E09] 去除所有空白字符
来源：http://dali.ivvv.top/Article/details/gt2nrrbyyvh.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.nanxuanxn.top/Article/details/gt2satwvfrl.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.dianchejie.cn/Article/details/gt2vshwnzib.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhengqikj.top/Article/details/gt2bhvjgmeu.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.andypj.xyz/Article/details/gt2quxeruie.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.ppjwa.cn/Article/details/gt2alsyplcu.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.sweek.top/Article/details/gt2osiqqpmv.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.iojbl.cn/Article/details/gt2ukemaswf.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.birdmap.top/Article/details/gt2vdbvmsqe.html

[E10] 左侧补零 / 定长填充
来源：http://dali.hnqzz.top/Article/details/gt2itwtfpwp.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jqgufenzy.top/Article/details/gt2tuvrcfrp.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yj20258.top/Article/details/gt2awwhvuoq.html

JS:   "7".padStart(3, "0")
来源：http://dali.hfpthk.cn/Article/details/gt2slepezml.html

TS:   "7".padStart(3, "0")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kjiqmgfe.html

Java: String.format("%03d", 7)
来源：http://dali.bjfxy.top/Article/details/gt2ruvacuup.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.cdnleiting.top/Article/details/gt2fudwmhiz.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.aibaodan.cn/Article/details/gt2asexhczs.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.meibo888.top/Article/details/gt2gyqovfzs.html

[E11] 反转字符串
来源：http://dali.yuanzhike.top/Article/details/gt2euepzbpc.html

Py:   s[::-1]
来源：http://dali.jlsjyb.cn/Article/details/gt2kxhfiead.html

PHP:  strrev($s);
来源：http://dali.nanxinkj.top/Article/details/gt2kkavgjbe.html

JS:   [...s].reverse().join("")
来源：http://dali.tianlin.xyz/Article/details/gt2xvuoskaz.html

TS:   [...s].reverse().join("")
来源：http://dali.bjfxy.top/Article/details/gt2fywqjwje.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yuanzhike.top/Article/details/gt2gazvvedx.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.9152youxi.cn/Article/details/gt2xrzdrxot.html

Ruby: s.reverse
来源：http://dali.tianlin.xyz/Article/details/gt2zuyvfvhh.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.cashguo.top/Article/details/gt2nnofubir.html

[E12] 统计某字符出现次数
来源：http://dali.dianchejie.cn/Article/details/gt2gdneycum.html

Py:   s.count("a")
来源：http://dali.andypj.xyz/Article/details/gt2lulolfon.html

PHP:  substr_count($s, "a");
来源：http://dali.sufxvd.cn/Article/details/gt2rttxdrnz.html

JS:   s.split("a").length - 1
来源：http://dali.dianchejie.cn/Article/details/gt2cscxthsk.html

TS:   s.split("a").length - 1
来源：http://dali.pycfn.com/Article/details/gt2kkhptmqy.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.aizwys.cn/Article/details/gt2ybtsmzrz.html

Go:   strings.Count(s, "a")
来源：http://dali.zdqjudy.top/Article/details/gt2kzdlfwbs.html

Ruby: s.count("a")
来源：http://dali.cucudq.cn/Article/details/gt2hslmlmrb.html

C#:   s.Count(c => c == 'a')
来源：http://dali.aibaodan.cn/Article/details/gt2xwjfqups.html

[E13] 逐字符遍历
来源：http://dali.yj20258888.top/Article/details/gt2seqnikad.html

Py:   for ch in s: print(ch)
来源：http://dali.pycfn.com/Article/details/gt2dkgyxcze.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.dianchejie.cn/Article/details/gt2jpfrvorw.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.0kj1m.cn/Article/details/gt2pzfgqowm.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.kuanghao11.cn/Article/details/gt2tpcrloba.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.shuidangran.top/Article/details/gt2iqznrpnn.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.kuanghao11.cn/Article/details/gt2soxstovg.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.cheryme.top/Article/details/gt2pbceyugt.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wcyomvdi.html

[E14] URL 编码与 Base64
来源：http://dali.tianlin.xyz/Article/details/gt2yeqpqtgq.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.cqqwz.cn/Article/details/gt2xbwcemjj.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.c1oappe.top/Article/details/gt2zsgexscb.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yongpay.top/Article/details/gt2llnttaaz.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.cdnleiting.top/Article/details/gt2ntnhrown.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.tanke756.top/Article/details/gt2atvvhjin.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.meibo888.top/Article/details/gt2laoiwgxq.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.bjfxy.top/Article/details/gt2hqjuxiko.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yueranfly.top/Article/details/gt2qkueuwsr.html

[E15] HTML 转义 / 反转义
来源：http://dali.hnxiangtu.top/Article/details/gt2kslwujwd.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jqgfzy.top/Article/details/gt2gyviemuk.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hysaishi.cn/Article/details/gt2awhmhxab.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.ydzc1.top/Article/details/gt2lyyhbddb.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jyoumei.cn/Article/details/gt2bnkcarty.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zdqjudy.top/Article/details/gt2sttgvzry.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yuanzhike.top/Article/details/gt2lajygncy.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yvedp.cn/Article/details/gt2ujcvgouz.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhixingplan.top/Article/details/gt2iwgfcbre.html

[E16] 数字千分位
来源：http://dali.daxiang520.top/Article/details/gt2ngweveoc.html

Py:   f"{1234567:,}"
来源：http://dali.ybcxt.top/Article/details/gt2jkfbdudv.html

PHP:  number_format(1234567);
来源：http://dali.daria6918.cn/Article/details/gt2yusqrmof.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.xuanzx.com/Article/details/gt2iiwymiuv.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.tanke756.top/Article/details/gt2dsbcxegx.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.gzhubu.top/Article/details/gt2cbmtvqvz.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yongpay.top/Article/details/gt2kdtsogzh.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pbclvxwi.html

C#:   1234567.ToString("N0")
来源：http://dali.hnqzz.top/Article/details/gt2rqcydthv.html

[E17] 首字母大写
来源：http://dali.mhx1999.top/Article/details/gt2nlaqfvnk.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.xuetiantiany.cn/Article/details/gt2qehajumr.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.feifeiyinyue.top/Article/details/gt2hquibaur.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenlongwang.top/Article/details/gt2tbxlsqiw.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yvedp.cn/Article/details/gt2fwsgtvxj.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.hywenlv.cn/Article/details/gt2hzotwnne.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.daria6918.cn/Article/details/gt2jwmqaaiu.html

Ruby: s.capitalize
来源：http://dali.gaohongyu789.top/Article/details/gt2uspgcwpz.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.birdmap.top/Article/details/gt2qryrzrcu.html

[E18] 模板占位符替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rajzyjbd.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.nwbrower.top/Article/details/gt2syizfode.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yuxming.cn/Article/details/gt2kwtsjzpa.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.xinyue.icu/Article/details/gt2zjctdxad.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2alfctavo.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jqgufenzy.top/Article/details/gt2nvkzhtmt.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.iojbl.cn/Article/details/gt2eonduzxu.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.hysaishi.cn/Article/details/gt2rggmpxlf.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.cucudq.cn/Article/details/gt2fzxagcie.html

[E19] 多行文本按行拆分
来源：http://dali.smart0.xyz/Article/details/gt2oqjmyxsm.html

Py:   s.splitlines()
来源：http://dali.jinqigufen.top/Article/details/gt2nckksriw.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gt2namybkww.html

JS:   s.split(/\r?\n/)
来源：http://dali.shuidangran.top/Article/details/gt2czkojofu.html

TS:   s.split(/\r?\n/)
来源：http://dali.havefunace.top/Article/details/gt2xdztnqbt.html

Java: s.lines().toList()
来源：http://dali.sxryk.cn/Article/details/gt2zakdurcl.html

Go:   strings.Split(s, "\n")
来源：http://dali.tanke756.top/Article/details/gt2cjlmeigx.html

Ruby: s.lines
来源：http://dali.gogol.net.cn/Article/details/gt2qhotzzkf.html

C#:   s.Split('\n')
来源：http://dali.yongpay.top/Article/details/gt2udovkgoq.html

[E20] 判断字符串是否为空
来源：http://dali.cdnleiting.top/Article/details/gt2nfxziorp.html

Py:   if not s:
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mvfcmeig.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jianghu66.top/Article/details/gt2nbzdifuj.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2jevvpsxu.html

TS:   if (s === "") {}
来源：http://dali.zycfv.cn/Article/details/gt2oqnqzhaa.html

Java: if (s.isEmpty()) {}
来源：http://dali.cdnleiting.top/Article/details/gt2rbomkekz.html

Go:   if s == "" {}
来源：http://dali.meibo888.top/Article/details/gt2uqrbbkap.html

Ruby: if s.empty?
来源：http://dali.havefunace.top/Article/details/gt2klbkrdsz.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2bziiosty.html

[E21] 超长截断加省略号
来源：http://dali.guannengcc.top/Article/details/gt2gevbunin.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.svipenyu.cn/Article/details/gt2abgahmrf.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.birdmap.top/Article/details/gt2fnjmsqjb.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhixingplan.top/Article/details/gt2lcjjbbpk.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.guannengcc.top/Article/details/gt2erwgowhy.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.xuetiantiany.cn/Article/details/gt2sjachnvd.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.mhx1999.top/Article/details/gt2almadchs.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.ivvv.top/Article/details/gt2conpdmzi.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.xziqi.cn/Article/details/gt2cvmpycvq.html

[E22] 字节长度与字符长度
来源：http://dali.snrcjt.cn/Article/details/gt2jnryzeup.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jianghu66.top/Article/details/gt2jrfmzoxg.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.nanxinkj.top/Article/details/gt2wwwqlbzb.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinqigufen.top/Article/details/gt2rioowkld.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shangyingyoupin.top/Article/details/gt2qmeynqmy.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhoulong.xyz/Article/details/gt2emkbdkep.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yonumen.top/Article/details/gt2vqvlledy.html

Ruby: s.bytesize;  s.length
来源：http://dali.pycfn.com/Article/details/gt2mdovrqbw.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.xuanzx.com/Article/details/gt2gldqjthy.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2rjvqacmb.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2zicqnmqe.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2lxsbnncd.html

[F01] 读取整个文件
来源：http://dali.zhixingplan.top/Article/details/gt2asosnkmc.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yj20258888.top/Article/details/gt2qgazjfhm.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gt2uaekafvp.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yvedp.cn/Article/details/gt2gkdpabip.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.fzhhl.top/Article/details/gt2xadmlrfv.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hywenlv.cn/Article/details/gt2wdkgrvvh.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.xylfe.cn/Article/details/gt2oyuqjavs.html

Ruby: File.read("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uabmgtuj.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gt2kzubsysh.html

[F02] 逐行读取文件
来源：http://dali.cdnleiting.top/Article/details/gt2tlmhppjc.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.haohaochexian.top/Article/details/gt2nverwyew.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hammf.cn/Article/details/gt2qesgdfpi.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yongpay.top/Article/details/gt2lshtthdg.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jqgfzy.top/Article/details/gt2dvjqzcyd.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.nanxinkj.top/Article/details/gt2uuwxtikw.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.xziqi.cn/Article/details/gt2djtmieyt.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2koyzlmjf.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.cdnleiting.top/Article/details/gt2cwazjczp.html

[F03] 写入文件（覆盖）
来源：http://dali.zycfv.cn/Article/details/gt2npmnegho.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yangfankeji.com/Article/details/gt2fvwtltqm.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.havefunace.top/Article/details/gt2zqafgeaa.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.aizwys.cn/Article/details/gt2ohsshiph.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hysaishi.cn/Article/details/gt2wkobpliv.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.kuanghao11.cn/Article/details/gt2mxwezxgk.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.mhx1999.top/Article/details/gt2afwfitrx.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hysaishi.cn/Article/details/gt2ufahdmln.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.0kj1m.cn/Article/details/gt2qjrhtccy.html

[F04] 追加写入文件
来源：http://dali.ppjwa.cn/Article/details/gt2rzzpirfr.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.dianchejie.cn/Article/details/gt2tgxonzuf.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.redwolf501.top/Article/details/gt2ynvaiovg.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gaohongyu789.top/Article/details/gt2biqliobj.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yongpay.top/Article/details/gt2nzcpyliy.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.fengsongda.top/Article/details/gt2lgqpytdt.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.tianlin.xyz/Article/details/gt2tzbosjai.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.wangdashe.top/Article/details/gt2uhsjqnou.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.daxiang520.top/Article/details/gt2qbkwryrw.html

[F05] 判断文件或目录是否存在
来源：http://dali.hywenlv.cn/Article/details/gt2dnpbbhaz.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hnqzz.top/Article/details/gt2buitogxi.html

PHP:  file_exists("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gt2dpqvqqqh.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2kppczyog.html

TS:   fs.existsSync("a.txt")
来源：http://dali.cucudq.cn/Article/details/gt2sjmqxhtc.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hysaishi.cn/Article/details/gt2scuvetjg.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.sxryk.cn/Article/details/gt2wyvkbtda.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2atnvezri.html

C#:   File.Exists("a.txt")
来源：http://dali.jianghu66.top/Article/details/gt2cprcuwhs.html

[F06] 删除文件
来源：http://dali.bjfxy.top/Article/details/gt2skqiclzf.html

Py:   os.remove("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bweuaksv.html

PHP:  unlink("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gt2qxjhonax.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2uqdtswyw.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.xylfe.cn/Article/details/gt2cucdlzln.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.andypj.xyz/Article/details/gt2faewuucf.html

Go:   os.Remove("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2qfnvlsrz.html

Ruby: File.delete("a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2mshjogty.html

C#:   File.Delete("a.txt");
来源：http://dali.sxryk.cn/Article/details/gt2rlvfimgg.html

[F07] 创建目录（含多级）
来源：http://dali.yanxiufei.cn/Article/details/gt2kcpsjkqg.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hywenlv.cn/Article/details/gt2smabtwqk.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jinqigufen.top/Article/details/gt2achtstrd.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zycfv.cn/Article/details/gt2jtbhoosg.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cdnleiting.top/Article/details/gt2qxbmsqfx.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.aizwys.cn/Article/details/gt2fnwtahox.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hongshengwenyu.top/Article/details/gt2viiwlwpc.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yuanzhike.top/Article/details/gt2rtdkypba.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhiwuduotai.top/Article/details/gt2mryycvgh.html

[F08] 遍历目录
来源：http://dali.sxryk.cn/Article/details/gt2vevxrxyc.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.nanxinkj.top/Article/details/gt2saeluglm.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.kuanghao11.cn/Article/details/gt2wmofyqos.html

JS:   fs.readdirSync("dir")
来源：http://dali.jianghu66.top/Article/details/gt2xmmltjdw.html

TS:   fs.readdirSync("dir")
来源：http://dali.bjfxy.top/Article/details/gt2sushootm.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.wangshuangyany.cn/Article/details/gt2jqmzrfap.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ivvv.top/Article/details/gt2bkcoxnio.html

Ruby: Dir.children("dir")
来源：http://dali.meibo888.top/Article/details/gt2gxdrhien.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hammf.cn/Article/details/gt2essmpumb.html

[F09] 获取文件大小
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rnzdxcin.html

Py:   os.path.getsize("a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2awcnycpy.html

PHP:  filesize("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gt2vkqibrqs.html

JS:   fs.statSync("a.txt").size
来源：http://dali.chenzaomai.com/Article/details/gt2rvboamww.html

TS:   fs.statSync("a.txt").size
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mxeerygc.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hammf.cn/Article/details/gt2obhsrjug.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.sweek.top/Article/details/gt2nplvhiud.html

Ruby: File.size("a.txt")
来源：http://dali.yvedp.cn/Article/details/gt2wootzsxo.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jianghu66.top/Article/details/gt2lujtvmov.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.wangdashe.top/Article/details/gt2iqbfiakb.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yongpay.top/Article/details/gt2vjqhfkmu.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhengqikj.top/Article/details/gt2huncjnzv.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2zlucfekj.html

TS:   path.extname("a.txt")
来源：http://dali.cashguo.top/Article/details/gt2czvigpki.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.dianchejie.cn/Article/details/gt2grekrltf.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.tian-w.cn/Article/details/gt2ugbhbzqq.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xylfe.cn/Article/details/gt2qhoqgddn.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2qlftumnz.html

[F11] 复制与移动文件
来源：http://dali.fzhhl.top/Article/details/gt2nxjpzmrg.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2tztvhsjb.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.sysykeji.top/Article/details/gt2eavcdhvn.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yuxming.cn/Article/details/gt2rbcmsquj.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xinyue.icu/Article/details/gt2qcvtjttk.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.tianlin.xyz/Article/details/gt2ihwidkse.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jyoumei.cn/Article/details/gt2dluqcaut.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2ohvinsfa.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.nwbrower.top/Article/details/gt2rswfbvsb.html

[F12] CSV 读写
来源：http://dali.yuxming.cn/Article/details/gt2zbwkxspd.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hjoqaioc.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.dashuyun.cn/Article/details/gt2ujadydwa.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qzipqgnm.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2sroawbra.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xuanzx.com/Article/details/gt2ongozvpw.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.cucudq.cn/Article/details/gt2whgpmndw.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.quarkkingdee.top/Article/details/gt2fuoxcwjq.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jqgfzy.top/Article/details/gt2teclefgl.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2awuvcfou.html

G. 面向对象
来源：http://dali.jiagoushi.top/Article/details/gt2fgemvuog.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2gyslebwq.html

[G01] 定义类
来源：http://dali.316326.xyz/Article/details/gt2oimggtcp.html

Py:   class User: pass
来源：http://dali.daria6918.cn/Article/details/gt2brivifjr.html

PHP:  class User {}
来源：http://dali.wangdashe.top/Article/details/gt2kytylbnt.html

JS:   class User {}
来源：http://dali.tanke756.top/Article/details/gt2mizzhawf.html

TS:   class User { name: string = ""; }
来源：http://dali.jinqigufen.top/Article/details/gt2zrcnufir.html

Java: class User {}
来源：http://dali.andypj.xyz/Article/details/gt2tstpdtfa.html

Go:   type User struct { Name string }
来源：http://dali.yuanzhike.top/Article/details/gt2dgnkiwdu.html

Ruby: class User; end
来源：http://dali.jlsjyb.cn/Article/details/gt2jvnbfxaa.html

C#:   class User {}
来源：http://dali.havefunace.top/Article/details/gt2ghkrdeqj.html

[G02] 构造函数
来源：http://dali.yuxming.cn/Article/details/gt2ybjqfiic.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.iojbl.cn/Article/details/gt2zrowptbi.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yvedp.cn/Article/details/gt2rdugzvhl.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.tianlin.xyz/Article/details/gt2yrmxdues.html

TS:   constructor(public name: string) {}
来源：http://dali.nanxinkj.top/Article/details/gt2drveqtuv.html

Java: User(String name) { this.name = name; }
来源：http://dali.guannengcc.top/Article/details/gt2getxmmal.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.chenlongwang.top/Article/details/gt2xtjjpnur.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.tanke756.top/Article/details/gt2vnzgxkce.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yonumen.top/Article/details/gt2kunsunio.html

[G03] 实例属性
来源：http://dali.yueranfly.top/Article/details/gt2gowrxsqd.html

Py:   self.name = "x"
来源：http://dali.kuanghao11.cn/Article/details/gt2mcktqpjq.html

PHP:  public string $name = "x";
来源：http://dali.gaohongyu789.top/Article/details/gt2cgspmxfl.html

JS:   this.name = "x";
来源：http://dali.cheryme.top/Article/details/gt2cthtefae.html

TS:   name: string = "x";
来源：http://dali.tian-w.cn/Article/details/gt2apypbegx.html

Java: private String name;
来源：http://dali.dashuyun.cn/Article/details/gt2lfuilngt.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yj202588.top/Article/details/gt2jrwllhrq.html


<!-- 参考信息 -->