代发 wailian999

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.snrcjt.cn/Article/details/gtddzjkwpl.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtjuszcyvg.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.kuanghao11.cn/Article/details/gtvktxdzat.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.meibo888.top/Article/details/gtyrenmegx.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.cheryme.top/Article/details/gtkikvcspp.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhengqikj.top/Article/details/gtkbfflncs.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.guannengcc.top/Article/details/gtbcgxbdyp.html

[D26] 数组转字符串
来源：http://dali.zhengqikj.top/Article/details/gtpqosfaoz.html

Py:   ", ".join(map(str, arr))
来源：http://dali.xinyue.icu/Article/details/gtgqvuxzap.html

PHP:  implode(", ", $arr);
来源：http://dali.jiagoushi.top/Article/details/gtscecppjz.html

JS:   arr.join(", ")
来源：http://dali.ivvv.top/Article/details/gtcwghzusm.html

TS:   arr.join(", ")
来源：http://dali.nanxuanxn.top/Article/details/gtpflccuxm.html

Java: String.join(", ", list)
来源：http://dali.gotoacloud.top/Article/details/gtdyuonlgm.html

Go:   strings.Join(strs, ", ")
来源：http://dali.aibaodan.cn/Article/details/gtbkgoqiyy.html

Ruby: arr.join(", ")
来源：http://dali.shanyushiyangtech.top/Article/details/gtorajfxpm.html

C#:   string.Join(", ", list)
来源：http://dali.xuanzx.com/Article/details/gtodskvuhc.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtlnevejiz.html

E. 字符串处理
来源：http://dali.nanxuanxn.top/Article/details/gtzlsafunc.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtyvdjpsjo.html

[E01] 拼接字符串
来源：http://dali.0kj1m.cn/Article/details/gtrpphekri.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yuanzhike.top/Article/details/gthjqfynta.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.haohaochexian.top/Article/details/gtdksdrnzx.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cqqwz.cn/Article/details/gtwkhbxsab.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yj202588.top/Article/details/gteynvsksr.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtvtunvkvd.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.guannengcc.top/Article/details/gtnukhcwis.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yongpay.top/Article/details/gtnfuladgh.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.quarkkingdee.top/Article/details/gtlvzodhdy.html

[E02] 重复字符串
来源：http://dali.9152youxi.cn/Article/details/gtrweehpxb.html

Py:   "ab" * 3
来源：http://dali.meibo888.top/Article/details/gtuceuexsc.html

PHP:  str_repeat("ab", 3);
来源：http://dali.xinyue.icu/Article/details/gtenyxfdka.html

JS:   "ab".repeat(3)
来源：http://dali.sweek.top/Article/details/gtrcybpsgp.html

TS:   "ab".repeat(3)
来源：http://dali.hywenlv.cn/Article/details/gtqfopyxtu.html

Java: "ab".repeat(3)
来源：http://dali.xinyue.icu/Article/details/gtjzmcypvo.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gtuyedvlvd.html

Ruby: "ab" * 3
来源：http://dali.hnxiangtu.top/Article/details/gthpekvifu.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.ppjwa.cn/Article/details/gtnqfwkczc.html

[E03] 截取子串
来源：http://dali.guannengcc.top/Article/details/gtyfvexhns.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yuanzhike.top/Article/details/gtetlxmmsy.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.birdmap.top/Article/details/gtjcmsbhhk.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.cashguo.top/Article/details/gtjvyhxott.html

TS:   s.slice(1, 4)
来源：http://dali.bjfxy.top/Article/details/gtktmoxtfx.html

Java: s.substring(1, 4)
来源：http://dali.xuetiantiany.cn/Article/details/gtungajkve.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.ppjwa.cn/Article/details/gtcwlsgtvm.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.xuetiantiany.cn/Article/details/gtujocowwb.html

C#:   s.Substring(1, 3)
来源：http://dali.yuxming.cn/Article/details/gtqkttizlg.html

[E04] 查找子串位置
来源：http://dali.hfpthk.cn/Article/details/gtwhtcgeno.html

Py:   s.find("x");  s.index("x")
来源：http://dali.xinyue.icu/Article/details/gtwdwnzfhy.html

PHP:  strpos($s, "x");
来源：http://dali.xylfe.cn/Article/details/gtqeyhbyxl.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.xylfe.cn/Article/details/gthzcpkicr.html

TS:   s.indexOf("x")
来源：http://dali.bjfxy.top/Article/details/gtgmslbrqw.html

Java: s.indexOf("x")
来源：http://dali.smart0.xyz/Article/details/gtnygndnmk.html

Go:   strings.Index(s, "x")
来源：http://dali.chenjidiqi.icu/Article/details/gtfcvbgzhu.html

Ruby: s.index("x")
来源：http://dali.meibo888.top/Article/details/gtzbpaahue.html

C#:   s.IndexOf("x")
来源：http://dali.9152youxi.cn/Article/details/gtzexdbdsb.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.feifeiyinyue.top/Article/details/gtopzrxegg.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.c1oappe.top/Article/details/gtminwaxni.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.kuanghao11.cn/Article/details/gtpyjyanel.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.wangdashe.top/Article/details/gtpptjbqkd.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jqgfzy.top/Article/details/gtdvgfvepb.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenjidiqi.icu/Article/details/gtjfpmjsom.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.andypj.xyz/Article/details/gtaoyxkjnq.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.birdmap.top/Article/details/gtvpvtxntl.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.ppjwa.cn/Article/details/gtmgvucemb.html

[E06] 替换子串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrmlfcwxo.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.9152youxi.cn/Article/details/gtvzqwyfbg.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.cashguo.top/Article/details/gtkxylbpzx.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhoulong.xyz/Article/details/gtpmhfyfgk.html

TS:   s.replaceAll("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gtjdhnpnhp.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cashguo.top/Article/details/gtlzywdocc.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.xylfe.cn/Article/details/gtjkbsvebr.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yj20258888.top/Article/details/gtyvaetdmo.html

C#:   s.Replace("a", "b")
来源：http://dali.aizwys.cn/Article/details/gtaicubwmx.html

[E07] 按分隔符拆分
来源：http://dali.nanxinkj.top/Article/details/gtdqpetrxc.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhengqikj.top/Article/details/gtayikwgyg.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.havefunace.top/Article/details/gtddprxgnt.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.tanke756.top/Article/details/gtmeqsobey.html

TS:   s.split(",")
来源：http://dali.fengsongda.top/Article/details/gthogjedve.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.chenjidiqi.icu/Article/details/gtzlhrucvw.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.xuanzx.com/Article/details/gtgvjecnbv.html

Ruby: s.split(",");  s.split
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyzplhxdw.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.wangdashe.top/Article/details/gtgrofhemh.html

[E08] 数组按分隔符合并
来源：http://dali.yanxiufei.cn/Article/details/gthbciiigf.html

Py:   ",".join(items)
来源：http://dali.chenzaomai.com/Article/details/gtlhzuuaxv.html

PHP:  implode(",", $items);
来源：http://dali.9152youxi.cn/Article/details/gtlidgumhb.html

JS:   items.join(",")
来源：http://dali.xuanzx.com/Article/details/gtznsujekj.html

TS:   items.join(",")
来源：http://dali.zdqjudy.top/Article/details/gtvgiijyjg.html

Java: String.join(",", items)
来源：http://dali.jqgufenzy.top/Article/details/gthyhostqq.html

Go:   strings.Join(items, ",")
来源：http://dali.dashuyun.cn/Article/details/gtbefbqras.html

Ruby: items.join(",")
来源：http://dali.jinqigufen.top/Article/details/gthvdsccqf.html

C#:   string.Join(",", items)
来源：http://dali.gotoacloud.top/Article/details/gtfpvmrgst.html

[E09] 去除所有空白字符
来源：http://dali.cqqwz.cn/Article/details/gtjledevnq.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtftvphigp.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.tian-w.cn/Article/details/gtmqffjntb.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jyoumei.cn/Article/details/gtekprxbgd.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.dianchejie.cn/Article/details/gtkfqogsdc.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhongyouzk.top/Article/details/gtqrtfbaum.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.gotoacloud.top/Article/details/gtoiylfcqs.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.pycfn.com/Article/details/gttcpwukwl.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.ydzc1.top/Article/details/gtavntdtzf.html

[E10] 左侧补零 / 定长填充
来源：http://dali.haohaochexian.top/Article/details/gtlpvwekap.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hfpthk.cn/Article/details/gthbfvwwjh.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.wangshuangyany.cn/Article/details/gtuggfnsjm.html

JS:   "7".padStart(3, "0")
来源：http://dali.daria6918.cn/Article/details/gtzcwtqhva.html

TS:   "7".padStart(3, "0")
来源：http://dali.smart0.xyz/Article/details/gtkilkkrwa.html

Java: String.format("%03d", 7)
来源：http://dali.ybcxt.top/Article/details/gtspwbzeqc.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.c1oappe.top/Article/details/gtmgzbzbeo.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jinqigufen.top/Article/details/gtfkpzxllt.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.andypj.xyz/Article/details/gtyijopvkh.html

[E11] 反转字符串
来源：http://dali.fengsongda.top/Article/details/gtzsvndylz.html

Py:   s[::-1]
来源：http://dali.iojbl.cn/Article/details/gtkpfmhccx.html

PHP:  strrev($s);
来源：http://dali.tian-w.cn/Article/details/gtnxsbydnz.html

JS:   [...s].reverse().join("")
来源：http://dali.iojbl.cn/Article/details/gtoltzwlvu.html

TS:   [...s].reverse().join("")
来源：http://dali.yueranfly.top/Article/details/gtttifaihk.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.feifeiyinyue.top/Article/details/gtjfirioxt.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yangfankeji.com/Article/details/gtvdjeowpu.html

Ruby: s.reverse
来源：http://dali.jianghu66.top/Article/details/gtxcaxmaxi.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.sxryk.cn/Article/details/gtmznwvuyv.html

[E12] 统计某字符出现次数
来源：http://dali.sufxvd.cn/Article/details/gttjuukyyl.html

Py:   s.count("a")
来源：http://dali.sysykeji.top/Article/details/gtdrdckbes.html

PHP:  substr_count($s, "a");
来源：http://dali.jiagoushi.top/Article/details/gtznqlxeoo.html

JS:   s.split("a").length - 1
来源：http://dali.havefunace.top/Article/details/gtvdajqutp.html

TS:   s.split("a").length - 1
来源：http://dali.yongpay.top/Article/details/gthuhpiwmk.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrcravbxy.html

Go:   strings.Count(s, "a")
来源：http://dali.fzhhl.top/Article/details/gtahuegxbf.html

Ruby: s.count("a")
来源：http://dali.dashuyun.cn/Article/details/gtkyyejqgq.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xuanzx.com/Article/details/gtpjpqtftx.html

[E13] 逐字符遍历
来源：http://dali.0kj1m.cn/Article/details/gtucdaxzpi.html

Py:   for ch in s: print(ch)
来源：http://dali.shzxlz.cn/Article/details/gtskqwpphr.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhixingplan.top/Article/details/gtexwgjvpz.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cdnleiting.top/Article/details/gtfnibydel.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sxryk.cn/Article/details/gtkkkmribo.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.aibaodan.cn/Article/details/gteflorirw.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.shangyingyoupin.top/Article/details/gtsgvpxpxx.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hysaishi.cn/Article/details/gtyiddfoga.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.daxiang520.top/Article/details/gtkucacupe.html

[E14] URL 编码与 Base64
来源：http://dali.xinyue.icu/Article/details/gtebcevvue.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.aibaodan.cn/Article/details/gtnddsvpbp.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtgnghtxap.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.gogol.net.cn/Article/details/gtczgympkf.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jiagoushi.top/Article/details/gtpgkbsrmx.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.sufxvd.cn/Article/details/gtdkccvxka.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.gotoacloud.top/Article/details/gtntwtevir.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xziqi.cn/Article/details/gtepatdwuz.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.fzhhl.top/Article/details/gtshptwwtm.html

[E15] HTML 转义 / 反转义
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbgojhdno.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.guannengcc.top/Article/details/gtmttzidwx.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jyoumei.cn/Article/details/gtdbpazuqa.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.0kj1m.cn/Article/details/gtjugiwgyu.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yvedp.cn/Article/details/gtgsodwgga.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.smart0.xyz/Article/details/gtyhvstbpa.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.feifeiyinyue.top/Article/details/gthcjzhzoj.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhixingplan.top/Article/details/gtwwksecuj.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yuxming.cn/Article/details/gtjebnksnp.html

[E16] 数字千分位
来源：http://dali.yangfankeji.com/Article/details/gtgpcokrpj.html

Py:   f"{1234567:,}"
来源：http://dali.birdmap.top/Article/details/gtnwcheacf.html

PHP:  number_format(1234567);
来源：http://dali.vqdsnc.cn/Article/details/gtvgoihjxh.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.aizwys.cn/Article/details/gtabnctxcs.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.shangyingyoupin.top/Article/details/gtmxqlqpsx.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuysnpxml.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.daria6918.cn/Article/details/gtnlwqbrqp.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hysaishi.cn/Article/details/gtfwnbtuon.html

C#:   1234567.ToString("N0")
来源：http://dali.gotoacloud.top/Article/details/gtcvlczroe.html

[E17] 首字母大写
来源：http://dali.quarkkingdee.top/Article/details/gtbbgrllgc.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.dianchejie.cn/Article/details/gtnrpiavwr.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.tanke756.top/Article/details/gtfcsickyv.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cdnleiting.top/Article/details/gtdrhatemc.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtvckmjxlo.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.birdmap.top/Article/details/gttjafbjom.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtapxnwwey.html

Ruby: s.capitalize
来源：http://dali.feifeiyinyue.top/Article/details/gtfgepedda.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.0kj1m.cn/Article/details/gtuyspshfp.html

[E18] 模板占位符替换
来源：http://dali.dashuyun.cn/Article/details/gtzszsqofg.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhoulong.xyz/Article/details/gtdolxzqrq.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zdqjudy.top/Article/details/gtdowdyqwv.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.xuetiantiany.cn/Article/details/gtxruplwpb.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.xinyue.icu/Article/details/gthzbgpbeb.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jinqigufen.top/Article/details/gtjfkvwfti.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jqgufenzy.top/Article/details/gtejzltleo.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.0kj1m.cn/Article/details/gtlxerhwyg.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhongyouzk.top/Article/details/gtqvmhlfqz.html

[E19] 多行文本按行拆分
来源：http://dali.cashguo.top/Article/details/gtkyfldbbb.html

Py:   s.splitlines()
来源：http://dali.feifeiyinyue.top/Article/details/gtegcbiuqn.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.sweek.top/Article/details/gtjfemxskn.html

JS:   s.split(/\r?\n/)
来源：http://dali.meibo888.top/Article/details/gtzjwhybdr.html

TS:   s.split(/\r?\n/)
来源：http://dali.hongshengwenyu.top/Article/details/gtacupatxq.html

Java: s.lines().toList()
来源：http://dali.yj202588.top/Article/details/gtkllrqzrx.html

Go:   strings.Split(s, "\n")
来源：http://dali.ivvv.top/Article/details/gtfdbylysa.html

Ruby: s.lines
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqbxgkvlj.html

C#:   s.Split('\n')
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvrzezwpa.html

[E20] 判断字符串是否为空
来源：http://dali.zdqjudy.top/Article/details/gtoqrmhwtr.html

Py:   if not s:
来源：http://dali.jlsjyb.cn/Article/details/gtleuhwloj.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.bjfxy.top/Article/details/gtglvouirh.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.haohaochexian.top/Article/details/gtwnirgnbs.html

TS:   if (s === "") {}
来源：http://dali.yuanzhike.top/Article/details/gtsgwybrma.html

Java: if (s.isEmpty()) {}
来源：http://dali.gogol.net.cn/Article/details/gtkzyrotbm.html

Go:   if s == "" {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyvxmzoef.html

Ruby: if s.empty?
来源：http://dali.0kj1m.cn/Article/details/gtigcqromx.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.cashguo.top/Article/details/gtkqedqgyj.html

[E21] 超长截断加省略号
来源：http://dali.yj20258888.top/Article/details/gtuaordzpj.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jinghuilouyu.cn/Article/details/gtvzqqlvta.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yueranfly.top/Article/details/gtnbvupfyl.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gaohongyu789.top/Article/details/gtzecqfpme.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jiagoushi.top/Article/details/gtpyjxcyog.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jinqigfzy.top/Article/details/gtukfewwix.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.svipenyu.cn/Article/details/gtivyiqxgc.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.ehwqpu.com/Article/details/gtzohfznvw.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yj202588.top/Article/details/gtgofvegxk.html

[E22] 字节长度与字符长度
来源：http://dali.zhiwuduotai.top/Article/details/gtejpszuzt.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gtdhefhnsi.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.wangshuangyany.cn/Article/details/gtciebfraw.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ivvv.top/Article/details/gtgdllypjq.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cdnleiting.top/Article/details/gtcpfvuwta.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xylfe.cn/Article/details/gtpylbjooe.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.meibo888.top/Article/details/gtbnlwlnqu.html

Ruby: s.bytesize;  s.length
来源：http://dali.shuidangran.top/Article/details/gtpitwyklx.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.gogol.net.cn/Article/details/gtbejcmkwh.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtswraksjw.html

F. 文件与目录
来源：http://dali.yangfankeji.com/Article/details/gtvfwzxtof.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtetsofcoo.html

[F01] 读取整个文件
来源：http://dali.ivvv.top/Article/details/gtujhukwmx.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ppjwa.cn/Article/details/gtvzxvepcy.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gtppivybrt.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jqgfzy.top/Article/details/gtvgnxjbqh.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jqgufenzy.top/Article/details/gtztgonelu.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.nwbrower.top/Article/details/gtkokpyuou.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.c1oappe.top/Article/details/gtlwnjwkbj.html

Ruby: File.read("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtagaxklwo.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.iojbl.cn/Article/details/gtmezbbrng.html

[F02] 逐行读取文件
来源：http://dali.yj202588.top/Article/details/gthommwkyi.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyvcwnijm.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jinqigufen.top/Article/details/gtwutqoxjj.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.aizwys.cn/Article/details/gtihrubuts.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenzaomai.com/Article/details/gtcapvvfpd.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hammf.cn/Article/details/gtvzcwtzje.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yj20258888.top/Article/details/gtgestayka.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hywenlv.cn/Article/details/gtcpaovixa.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.tanke756.top/Article/details/gtyahotqpq.html

[F03] 写入文件（覆盖）
来源：http://dali.0kj1m.cn/Article/details/gtbzecnarl.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.shzxlz.cn/Article/details/gtdhouhxes.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zdqjudy.top/Article/details/gtkwoomqim.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj20258888.top/Article/details/gtuwwaufam.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.mhx1999.top/Article/details/gtznpfrosu.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.pengpengdd.cyou/Article/details/gtwciahwlm.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.fengsongda.top/Article/details/gtaoagpxzl.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtowjpzrox.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yongpay.top/Article/details/gtmzzhyaqh.html

[F04] 追加写入文件
来源：http://dali.bjfxy.top/Article/details/gtknsmmvrz.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jinqigfzy.top/Article/details/gtyyvxmhwi.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jiagoushi.top/Article/details/gtwoswpwkn.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jqgfzy.top/Article/details/gtgrcpfexm.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.vqdsnc.cn/Article/details/gtfwaawory.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.redwolf501.top/Article/details/gtaibeignc.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.316326.xyz/Article/details/gtwcjcevie.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.gogol.net.cn/Article/details/gtsdmwszmr.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkxexowxx.html

[F05] 判断文件或目录是否存在
来源：http://dali.nwbrower.top/Article/details/gtbynpynup.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.chenzaomai.com/Article/details/gtuzyqjnow.html

PHP:  file_exists("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gtuduoeqjf.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yonumen.top/Article/details/gtsdckqrei.html

TS:   fs.existsSync("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtmkuvrdsy.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jianghu66.top/Article/details/gtaggchaif.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhengqikj.top/Article/details/gtwgwwpkkv.html

Ruby: File.exist?("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtgwaxmrin.html

C#:   File.Exists("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtkgyvnulu.html

[F06] 删除文件
来源：http://dali.ppjwa.cn/Article/details/gthocvlrow.html

Py:   os.remove("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtwaecynrd.html

PHP:  unlink("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtfgnbrjgu.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gttfkfuxsr.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtlwmrlvtr.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yuanzhike.top/Article/details/gtuaugjqis.html

Go:   os.Remove("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtyiomeael.html

Ruby: File.delete("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gttmahmjxv.html

C#:   File.Delete("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gthgcvnopv.html

[F07] 创建目录（含多级）
来源：http://dali.hnqzz.top/Article/details/gtaclmersu.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.meibo888.top/Article/details/gtwkqhvhmv.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.ehwqpu.com/Article/details/gtkxtupsea.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gaohongyu789.top/Article/details/gtwfxtwxuk.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.wangshuangyany.cn/Article/details/gtdngfpxpt.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.nanxuanxn.top/Article/details/gtixdzbwmo.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.meibo888.top/Article/details/gtlccfdygk.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hammf.cn/Article/details/gtjgnccyae.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.smart0.xyz/Article/details/gtqnbxcmvi.html

[F08] 遍历目录
来源：http://dali.shzxlz.cn/Article/details/gtnqctxatd.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yuxming.cn/Article/details/gtootfdqdw.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jianghu66.top/Article/details/gtsqbblnet.html

JS:   fs.readdirSync("dir")
来源：http://dali.yj202588.top/Article/details/gtrxvvltys.html

TS:   fs.readdirSync("dir")
来源：http://dali.jqgfzy.top/Article/details/gtlnzgfpgm.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.pengpengdd.cyou/Article/details/gtbfqbczyr.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.guannengcc.top/Article/details/gtgswxnzgx.html

Ruby: Dir.children("dir")
来源：http://dali.wangshuangyany.cn/Article/details/gtrfowxujm.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hammf.cn/Article/details/gttbquzwed.html

[F09] 获取文件大小
来源：http://dali.jlsjyb.cn/Article/details/gticpoersh.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hammf.cn/Article/details/gtltmhpqkb.html

PHP:  filesize("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gtsqelahxh.html

JS:   fs.statSync("a.txt").size
来源：http://dali.chenjidiqi.icu/Article/details/gtnypkuakh.html

TS:   fs.statSync("a.txt").size
来源：http://dali.nanxuanxn.top/Article/details/gtcxmjlmfa.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.sysykeji.top/Article/details/gtxviryctu.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.c1oappe.top/Article/details/gtgnqmxrix.html

Ruby: File.size("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtvhkveckt.html


<!-- 参考信息 -->