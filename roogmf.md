代发 wailian999

[E06] 替换子串
来源：http://dali.c1oappe.top/Article/details/gtcwuvkfay.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.nanxuanxn.top/Article/details/gtwggoljqy.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.guannengcc.top/Article/details/gtervrmcym.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gtikymazlr.html

TS:   s.replaceAll("a", "b")
来源：http://dali.kuanghao11.cn/Article/details/gtzxwrdknl.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.iojbl.cn/Article/details/gtzqtzhrgy.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.wangdashe.top/Article/details/gtfkdrrehw.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gtlpvbtgkx.html

C#:   s.Replace("a", "b")
来源：http://dali.zhengqikj.top/Article/details/gtvwcsfbua.html

[E07] 按分隔符拆分
来源：http://dali.yj20258888.top/Article/details/gtsxemyrwy.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.fzhhl.top/Article/details/gtihccbmfl.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.chenzaomai.com/Article/details/gtcwrdusxo.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.fzhhl.top/Article/details/gtvwfilthn.html

TS:   s.split(",")
来源：http://dali.havefunace.top/Article/details/gtaglwxwqd.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.gaohongyu789.top/Article/details/gtyiqlhkja.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.cdnleiting.top/Article/details/gthltlvluk.html

Ruby: s.split(",");  s.split
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfwqymvav.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yj20258.top/Article/details/gtogqdkwoq.html

[E08] 数组按分隔符合并
来源：http://dali.9152youxi.cn/Article/details/gtojuikcyi.html

Py:   ",".join(items)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnvveddnt.html

PHP:  implode(",", $items);
来源：http://dali.cheryme.top/Article/details/gtpjmudskd.html

JS:   items.join(",")
来源：http://dali.cashguo.top/Article/details/gtcbmfqmrr.html

TS:   items.join(",")
来源：http://dali.jinqigfzy.top/Article/details/gtgbchxvvi.html

Java: String.join(",", items)
来源：http://dali.hongshengwenyu.top/Article/details/gtvgsrnymw.html

Go:   strings.Join(items, ",")
来源：http://dali.shangyingyoupin.top/Article/details/gtzjlerupu.html

Ruby: items.join(",")
来源：http://dali.daria6918.cn/Article/details/gthymmwbqy.html

C#:   string.Join(",", items)
来源：http://dali.zycfv.cn/Article/details/gtxbkxtbvl.html

[E09] 去除所有空白字符
来源：http://dali.chenzaomai.com/Article/details/gtvcsmzfds.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhoulong.xyz/Article/details/gtthtqsfdm.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.dianchejie.cn/Article/details/gtuylvixuy.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.cqqwz.cn/Article/details/gtlgjzvwcp.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.iojbl.cn/Article/details/gtvawfbfgu.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jinqigufen.top/Article/details/gthecipexh.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gtmaljreiq.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.cdnleiting.top/Article/details/gtlfekagjf.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.snrcjt.cn/Article/details/gtjgswigzf.html

[E10] 左侧补零 / 定长填充
来源：http://dali.mhx1999.top/Article/details/gtwfbxtmsl.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zycfv.cn/Article/details/gtaemlklek.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.gaohongyu789.top/Article/details/gtxivvrssn.html

JS:   "7".padStart(3, "0")
来源：http://dali.havefunace.top/Article/details/gtzewzsfwd.html

TS:   "7".padStart(3, "0")
来源：http://dali.hongshengwenyu.top/Article/details/gtnezcfsnm.html

Java: String.format("%03d", 7)
来源：http://dali.c1oappe.top/Article/details/gtedykgtwx.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.hongshengwenyu.top/Article/details/gtekzdcayo.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.pycfn.com/Article/details/gtrovflind.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.tianlin.xyz/Article/details/gtdhbkwrjd.html

[E11] 反转字符串
来源：http://dali.cheryme.top/Article/details/gtaviereat.html

Py:   s[::-1]
来源：http://dali.hnxiangtu.top/Article/details/gtuopjpmup.html

PHP:  strrev($s);
来源：http://dali.xuanzx.com/Article/details/gtblbegboa.html

JS:   [...s].reverse().join("")
来源：http://dali.sysykeji.top/Article/details/gtfjtujkzy.html

TS:   [...s].reverse().join("")
来源：http://dali.ehwqpu.com/Article/details/gtrisjhwvv.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jqgufenzy.top/Article/details/gtfnevtnhv.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.shangyingyoupin.top/Article/details/gtyxysvnvv.html

Ruby: s.reverse
来源：http://dali.cqqwz.cn/Article/details/gtpjlmloxt.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yuanzhike.top/Article/details/gtcsiuvyzo.html

[E12] 统计某字符出现次数
来源：http://dali.haohaochexian.top/Article/details/gtpnsfiopc.html

Py:   s.count("a")
来源：http://dali.ydzc1.top/Article/details/gtzmurlymn.html

PHP:  substr_count($s, "a");
来源：http://dali.xuetiantiany.cn/Article/details/gtgmmjaius.html

JS:   s.split("a").length - 1
来源：http://dali.zdqjudy.top/Article/details/gthasjvgno.html

TS:   s.split("a").length - 1
来源：http://dali.sufxvd.cn/Article/details/gtaogpaooz.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkluongda.html

Go:   strings.Count(s, "a")
来源：http://dali.hnxiangtu.top/Article/details/gtecyopsvd.html

Ruby: s.count("a")
来源：http://dali.yj20258888.top/Article/details/gtigvlhshn.html

C#:   s.Count(c => c == 'a')
来源：http://dali.redwolf501.top/Article/details/gtlrylbgpf.html

[E13] 逐字符遍历
来源：http://dali.shzxlz.cn/Article/details/gttiokxada.html

Py:   for ch in s: print(ch)
来源：http://dali.nanxuanxn.top/Article/details/gtcoaszako.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.kuanghao11.cn/Article/details/gtuqiydfux.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.dashuyun.cn/Article/details/gtsslgjgwp.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xziqi.cn/Article/details/gtxjdnhzcp.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhongyouzk.top/Article/details/gtydvkzukk.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.sxryk.cn/Article/details/gtwrrsebjc.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.tanke756.top/Article/details/gtcgimqpij.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.shzxlz.cn/Article/details/gtepuytnks.html

[E14] URL 编码与 Base64
来源：http://dali.smart0.xyz/Article/details/gttpttttji.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.kuanghao11.cn/Article/details/gtxgrkykxo.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.birdmap.top/Article/details/gtzenjsccs.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhijiandao.cn/Article/details/gtxezjhsgg.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.daria6918.cn/Article/details/gtzdvcyilu.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.aibaodan.cn/Article/details/gtjuiwgtad.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yuxming.cn/Article/details/gtgltmfkui.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.ivvv.top/Article/details/gtqoudzwgm.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.cdnleiting.top/Article/details/gtzjfoqvar.html

[E15] HTML 转义 / 反转义
来源：http://dali.xinyue.icu/Article/details/gtvvsmqdzm.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.hammf.cn/Article/details/gtomimenyv.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.tianlin.xyz/Article/details/gttrrfxufg.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtpcjkoxxu.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yvedp.cn/Article/details/gtjeijksfo.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yuanzhike.top/Article/details/gtwygtjiie.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xziqi.cn/Article/details/gtksnwshkw.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jianghu66.top/Article/details/gtedlpuhyk.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.redwolf501.top/Article/details/gtwpbzvvnj.html

[E16] 数字千分位
来源：http://dali.mhx1999.top/Article/details/gtrjhzscwk.html

Py:   f"{1234567:,}"
来源：http://dali.hongshengwenyu.top/Article/details/gthwfufqnt.html

PHP:  number_format(1234567);
来源：http://dali.yanxiufei.cn/Article/details/gtpmlvmwpj.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.aizwys.cn/Article/details/gtqvsedbbv.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.hysaishi.cn/Article/details/gtbhchaxwu.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.tian-w.cn/Article/details/gtgrwinnhc.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.c1oappe.top/Article/details/gtpzypevjh.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.tanke756.top/Article/details/gtyfbpcqcr.html

C#:   1234567.ToString("N0")
来源：http://dali.0kj1m.cn/Article/details/gttdeyhvos.html

[E17] 首字母大写
来源：http://dali.cheryme.top/Article/details/gtidjsghrn.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.9152youxi.cn/Article/details/gtvkwfmbeh.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.nanxinkj.top/Article/details/gtoqxrgcmb.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtefchqcud.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xuanzx.com/Article/details/gtayyrccry.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.nanxinkj.top/Article/details/gtkjougqgw.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.gotoacloud.top/Article/details/gtprdetuik.html

Ruby: s.capitalize
来源：http://dali.guannengcc.top/Article/details/gtrmwteeho.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.guowangkeji.top/Article/details/gtkgewviha.html

[E18] 模板占位符替换
来源：http://dali.nwbrower.top/Article/details/gtqqrvzwmm.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.cashguo.top/Article/details/gtnpigevrk.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhoulong.xyz/Article/details/gtsfnkrjnp.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hfpthk.cn/Article/details/gtfdvvdmhm.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.316326.xyz/Article/details/gtrmheyicr.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.gzhubu.top/Article/details/gtpzruszgb.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtscjuwvse.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yonumen.top/Article/details/gtxuifgxqw.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zycfv.cn/Article/details/gtvodugaak.html

[E19] 多行文本按行拆分
来源：http://dali.hysaishi.cn/Article/details/gtjnxhxwfc.html

Py:   s.splitlines()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvtrhxhdb.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.birdmap.top/Article/details/gtvuvypwic.html

JS:   s.split(/\r?\n/)
来源：http://dali.gotoacloud.top/Article/details/gtuyxlpyrg.html

TS:   s.split(/\r?\n/)
来源：http://dali.cqqwz.cn/Article/details/gtbecjgsqi.html

Java: s.lines().toList()
来源：http://dali.gaohongyu789.top/Article/details/gtiloyearn.html

Go:   strings.Split(s, "\n")
来源：http://dali.wangdashe.top/Article/details/gtjhakzebl.html

Ruby: s.lines
来源：http://dali.yvedp.cn/Article/details/gtauluceoq.html

C#:   s.Split('\n')
来源：http://dali.xinyue.icu/Article/details/gtiqhteqxr.html

[E20] 判断字符串是否为空
来源：http://dali.yonumen.top/Article/details/gtwxnypyfv.html

Py:   if not s:
来源：http://dali.wangshuangyany.cn/Article/details/gtfsxhmxoc.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yj202588.top/Article/details/gtipgglxwh.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yueranfly.top/Article/details/gtaglpbzmz.html

TS:   if (s === "") {}
来源：http://dali.sxryk.cn/Article/details/gtdfqeskfp.html

Java: if (s.isEmpty()) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcehmjsci.html

Go:   if s == "" {}
来源：http://dali.jqgufenzy.top/Article/details/gtlmamalgj.html

Ruby: if s.empty?
来源：http://dali.haohaochexian.top/Article/details/gtnxosvyhq.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.daxiang520.top/Article/details/gtvvzckqsq.html

[E21] 超长截断加省略号
来源：http://dali.zhiwuduotai.top/Article/details/gtpzlubgic.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.tianlin.xyz/Article/details/gtkxqltpua.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yanxiufei.cn/Article/details/gtiakbczeb.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinqigufen.top/Article/details/gtckobufzj.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yj20258888.top/Article/details/gtemmrcsex.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yj202588.top/Article/details/gtuorviwxc.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhoulong.xyz/Article/details/gtclxbazax.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.ybcxt.top/Article/details/gtnljexvhf.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.shangyingyoupin.top/Article/details/gtcpstigko.html

[E22] 字节长度与字符长度
来源：http://dali.zhengqikj.top/Article/details/gtodjtrbyo.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.gaohongyu789.top/Article/details/gtpvvlouyu.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jyoumei.cn/Article/details/gtivtqzygk.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhongyouzk.top/Article/details/gtfzjqjtvf.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.kuanghao11.cn/Article/details/gtxddqaqif.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.sweek.top/Article/details/gthrbdufsg.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jiagoushi.top/Article/details/gttmlmwlgc.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhoulong.xyz/Article/details/gtdkwkyrnt.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ivvv.top/Article/details/gtadhuqmzk.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtirwzddag.html

F. 文件与目录
来源：http://dali.yangfankeji.com/Article/details/gtxocxrons.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtaaioggta.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gtevphfawt.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.daria6918.cn/Article/details/gteaaznbon.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xziqi.cn/Article/details/gthwnkpssx.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.quarkkingdee.top/Article/details/gtmyhoqfah.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.daxiang520.top/Article/details/gthtormgla.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhongyouzk.top/Article/details/gtjzftnqil.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.gzhubu.top/Article/details/gtxvqddakd.html

Ruby: File.read("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtmvftoozs.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtkmygdewu.html

[F02] 逐行读取文件
来源：http://dali.hnxiangtu.top/Article/details/gtymicawiz.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.nanxinkj.top/Article/details/gtsxrbvnur.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jyoumei.cn/Article/details/gtatccboff.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xinyue.icu/Article/details/gtmcjjveud.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.havefunace.top/Article/details/gtqoqsxnma.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpzvfkaky.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.wangdashe.top/Article/details/gtzqeqipue.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jianghu66.top/Article/details/gtaodyhfqu.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.gotoacloud.top/Article/details/gteuwditnx.html

[F03] 写入文件（覆盖）
来源：http://dali.xziqi.cn/Article/details/gtfjursian.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.wangdashe.top/Article/details/gtvbhwfqln.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.nanxuanxn.top/Article/details/gtqupnufyo.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.nanxinkj.top/Article/details/gtyaqjntzo.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cheryme.top/Article/details/gthwdetchb.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.ehwqpu.com/Article/details/gtijtpfzys.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhongyouzk.top/Article/details/gtoyxbozgk.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.cashguo.top/Article/details/gtsgldcpkm.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.guannengcc.top/Article/details/gtbxuhemdw.html

[F04] 追加写入文件
来源：http://dali.tian-w.cn/Article/details/gtwrhvuzjg.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hammf.cn/Article/details/gtvsrzjxsr.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.redwolf501.top/Article/details/gtttnfpjnv.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.iojbl.cn/Article/details/gtklkrmnag.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yuanzhike.top/Article/details/gtibstknlr.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yanxiufei.cn/Article/details/gtkoainbyy.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yangfankeji.com/Article/details/gtzgszbwab.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.daxiang520.top/Article/details/gtefmxsall.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhoulong.xyz/Article/details/gtmqmytovk.html

[F05] 判断文件或目录是否存在
来源：http://dali.dashuyun.cn/Article/details/gtqiybfmym.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yangfankeji.com/Article/details/gtcyttcdto.html

PHP:  file_exists("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gtcecsqrwq.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yj202588.top/Article/details/gtguiaabhy.html

TS:   fs.existsSync("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtavkswxcv.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.shuidangran.top/Article/details/gtmsbsntkw.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.wangshuangyany.cn/Article/details/gtjasmavqz.html

Ruby: File.exist?("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtgkofhjuf.html

C#:   File.Exists("a.txt")
来源：http://dali.daria6918.cn/Article/details/gttduqmpgn.html

[F06] 删除文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyvaatrbg.html

Py:   os.remove("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtcppfbqxt.html

PHP:  unlink("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtcupvvmbj.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtvuvyrxsz.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtwqrulpiu.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.sysykeji.top/Article/details/gtghctrkej.html

Go:   os.Remove("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtcwblkfkp.html

Ruby: File.delete("a.txt")
来源：http://dali.meibo888.top/Article/details/gtfelefbzv.html

C#:   File.Delete("a.txt");
来源：http://dali.ydzc1.top/Article/details/gtevjyqiuv.html

[F07] 创建目录（含多级）
来源：http://dali.shangyingyoupin.top/Article/details/gtrzmxaruh.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zycfv.cn/Article/details/gtgazqnbft.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.aizwys.cn/Article/details/gtahpguniw.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhoulong.xyz/Article/details/gtkslxdfty.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.aizwys.cn/Article/details/gthpcdtunp.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.cucudq.cn/Article/details/gtmdtcwlem.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.daria6918.cn/Article/details/gtdswnmtrz.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.aizwys.cn/Article/details/gtgdfodxrg.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jqgufenzy.top/Article/details/gtwtzmxfpx.html

[F08] 遍历目录
来源：http://dali.ydzc1.top/Article/details/gthigamoev.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.redwolf501.top/Article/details/gtkkfhnbem.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.aizwys.cn/Article/details/gtmvkuzqpt.html

JS:   fs.readdirSync("dir")
来源：http://dali.9152youxi.cn/Article/details/gtfkeevvdn.html

TS:   fs.readdirSync("dir")
来源：http://dali.nanxuanxn.top/Article/details/gtmpqixosc.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.wangdashe.top/Article/details/gtcnyxeude.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yvedp.cn/Article/details/gtkayexdim.html

Ruby: Dir.children("dir")
来源：http://dali.jiagoushi.top/Article/details/gtmfwojdxv.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zdqjudy.top/Article/details/gtjelczqoz.html

[F09] 获取文件大小
来源：http://dali.shanyushiyangtech.top/Article/details/gtmqqwpeuh.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtepmwqyhv.html

PHP:  filesize("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gtriurvoht.html

JS:   fs.statSync("a.txt").size
来源：http://dali.shuidangran.top/Article/details/gtnhxptmsr.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hnqzz.top/Article/details/gtsolyfzty.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zdqjudy.top/Article/details/gtsvrrsfek.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.gotoacloud.top/Article/details/gtrbdkqcjy.html

Ruby: File.size("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtxfrlftib.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwdkthhle.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.dashuyun.cn/Article/details/gtpuhqfwmt.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.gzhubu.top/Article/details/gtcsuwadzy.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hnqzz.top/Article/details/gtxiekfyhz.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtmpjkzwiw.html

TS:   path.extname("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtvdlknlzt.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.bjfxy.top/Article/details/gtfoapbxpo.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.c1oappe.top/Article/details/gtfehgtlpb.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.nwbrower.top/Article/details/gtvmnmeggn.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.havefunace.top/Article/details/gtifyudztm.html

[F11] 复制与移动文件
来源：http://dali.jqgufenzy.top/Article/details/gtlvrvouuf.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.andypj.xyz/Article/details/gtsbvrzpbe.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.sysykeji.top/Article/details/gtwaosdlsg.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.snrcjt.cn/Article/details/gtmzvualqr.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj20258888.top/Article/details/gtvhrptfhf.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zycfv.cn/Article/details/gtpfknbkmp.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.cucudq.cn/Article/details/gtonrqusta.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhongyouzk.top/Article/details/gteazopmfj.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.ehwqpu.com/Article/details/gtwhzcvgij.html

[F12] CSV 读写
来源：http://dali.sweek.top/Article/details/gtgnqhzzgy.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hammf.cn/Article/details/gttjhgoctw.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.tianlin.xyz/Article/details/gtdfpcvkqm.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.gogol.net.cn/Article/details/gtpodgyfgy.html

TS:   // 同上
来源：http://dali.xinyue.icu/Article/details/gttbtlgzqg.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yangfankeji.com/Article/details/gtswfvckrx.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.mhx1999.top/Article/details/gtagbuqjji.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhongyouzk.top/Article/details/gtjiunkjzz.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.iojbl.cn/Article/details/gtarqieaux.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtxhlazglz.html

G. 面向对象
来源：http://dali.nanxuanxn.top/Article/details/gtwifzooud.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtuisyouyq.html

[G01] 定义类
来源：http://dali.zhixingplan.top/Article/details/gtmlkqxdwx.html

Py:   class User: pass
来源：http://dali.gogol.net.cn/Article/details/gteqszbhfn.html

PHP:  class User {}
来源：http://dali.gotoacloud.top/Article/details/gtmqtfxefc.html

JS:   class User {}
来源：http://dali.jqgufenzy.top/Article/details/gtmnrjakgt.html

TS:   class User { name: string = ""; }
来源：http://dali.hnqzz.top/Article/details/gtaydygcrw.html

Java: class User {}
来源：http://dali.yonumen.top/Article/details/gtpcrvyijn.html

Go:   type User struct { Name string }
来源：http://dali.zycfv.cn/Article/details/gttfvucbue.html

Ruby: class User; end
来源：http://dali.cashguo.top/Article/details/gtckjctxiu.html

C#:   class User {}
来源：http://dali.jianghu66.top/Article/details/gtvvaaxydi.html

[G02] 构造函数
来源：http://dali.cashguo.top/Article/details/gtryecgmmu.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.c1oappe.top/Article/details/gtnqrbmsuy.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtucmyheni.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jiagoushi.top/Article/details/gtkczqttbx.html

TS:   constructor(public name: string) {}
来源：http://dali.yj20258.top/Article/details/gtrjvrhjcs.html

Java: User(String name) { this.name = name; }
来源：http://dali.ydzc1.top/Article/details/gtrrqproib.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cucudq.cn/Article/details/gthtprekti.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.tanke756.top/Article/details/gtiwciaxdg.html

C#:   public User(string name) { Name = name; }
来源：http://dali.nwbrower.top/Article/details/gtyxshpppv.html

[G03] 实例属性
来源：http://dali.andypj.xyz/Article/details/gtjdcgxuwk.html

Py:   self.name = "x"
来源：http://dali.tanke756.top/Article/details/gtlewowezn.html

PHP:  public string $name = "x";
来源：http://dali.fengsongda.top/Article/details/gtzlrmaadq.html

JS:   this.name = "x";
来源：http://dali.jiagoushi.top/Article/details/gtejvmqtjr.html

TS:   name: string = "x";
来源：http://dali.zhongyouzk.top/Article/details/gtpdepdwzv.html

Java: private String name;
来源：http://dali.jyoumei.cn/Article/details/gtvdaeemsw.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.tanke756.top/Article/details/gtuhvwllww.html

Ruby: @name = "x"
来源：http://dali.xinyue.icu/Article/details/gtbgqtmyfu.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zycfv.cn/Article/details/gtzjamzlrj.html

[G04] 定义方法
来源：http://dali.jinyuanbaomall.cn/Article/details/gtizpriujv.html

Py:   def greet(self): return self.name
来源：http://dali.ppjwa.cn/Article/details/gtcexwjybw.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jyoumei.cn/Article/details/gtitysudqz.html

JS:   greet() { return this.name; }
来源：http://dali.jqgfzy.top/Article/details/gtuoyijbvb.html

TS:   greet(): string { return this.name; }
来源：http://dali.tanke756.top/Article/details/gtseddpqma.html

Java: String greet() { return name; }
来源：http://dali.yuanzhike.top/Article/details/gtlllbjypg.html


<!-- 参考信息 -->