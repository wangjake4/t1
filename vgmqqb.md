代发 wailian999

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.316326.xyz/Article/details/gt2hvnzmavi.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.haohaochexian.top/Article/details/gt2gbuvtrtw.html

Go:   // 手写循环
来源：http://dali.meibo888.top/Article/details/gt2rotinqwx.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.hnqzz.top/Article/details/gt2rhytuphh.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.9152youxi.cn/Article/details/gt2mdljinhu.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2grkmleex.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hnxiangtu.top/Article/details/gt2hodazqeu.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.chenzaomai.com/Article/details/gt2qzuhvoxz.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pkjyysla.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.pengpengdd.cyou/Article/details/gt2pkmxiurp.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.nanxuanxn.top/Article/details/gt2qguygvda.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jqgufenzy.top/Article/details/gt2jwxfdkva.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.aibaodan.cn/Article/details/gt2ukvdsius.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.hfpthk.cn/Article/details/gt2yoefipvq.html

[D25] Set 集合去重与交并差
来源：http://dali.cqqwz.cn/Article/details/gt2yzsabcaq.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zycfv.cn/Article/details/gt2lnqkbrjv.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.pengpengdd.cyou/Article/details/gt2kyfpamds.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhixingplan.top/Article/details/gt2hfwpjema.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.chenjidiqi.icu/Article/details/gt2rrzehsvj.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.ppjwa.cn/Article/details/gt2vfxfvalt.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.nanxuanxn.top/Article/details/gt2umhnifyi.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.bjfxy.top/Article/details/gt2lzleiuhf.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2owjozpis.html

[D26] 数组转字符串
来源：http://dali.yangfankeji.com/Article/details/gt2yurvniex.html

Py:   ", ".join(map(str, arr))
来源：http://dali.tianlin.xyz/Article/details/gt2hgpxgkxq.html

PHP:  implode(", ", $arr);
来源：http://dali.zhixingplan.top/Article/details/gt2dqjndguj.html

JS:   arr.join(", ")
来源：http://dali.nanxinkj.top/Article/details/gt2ilznymjg.html

TS:   arr.join(", ")
来源：http://dali.ybcxt.top/Article/details/gt2krfcvcti.html

Java: String.join(", ", list)
来源：http://dali.chenlongwang.top/Article/details/gt2uwufgemt.html

Go:   strings.Join(strs, ", ")
来源：http://dali.bjfxy.top/Article/details/gt2ilvsgsml.html

Ruby: arr.join(", ")
来源：http://dali.fengsongda.top/Article/details/gt2ixzxsizs.html

C#:   string.Join(", ", list)
来源：http://dali.ehwqpu.com/Article/details/gt2cvbalbft.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2givmmhvq.html

E. 字符串处理
来源：http://dali.chenlongwang.top/Article/details/gt2flbnstsi.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2wnbrllfz.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2uvaqbkxy.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yuanzhike.top/Article/details/gt2mkzyynyj.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.fzhhl.top/Article/details/gt2dcalqchs.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhengqikj.top/Article/details/gt2hldtqpwz.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2tnsufsvc.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.feifeiyinyue.top/Article/details/gt2jesfcffs.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ievmceym.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yvedp.cn/Article/details/gt2jcpyslzk.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.sysykeji.top/Article/details/gt2snaxkive.html

[E02] 重复字符串
来源：http://dali.yvedp.cn/Article/details/gt2yqibcpmq.html

Py:   "ab" * 3
来源：http://dali.hammf.cn/Article/details/gt2hllnjeis.html

PHP:  str_repeat("ab", 3);
来源：http://dali.dashuyun.cn/Article/details/gt2pfaprmji.html

JS:   "ab".repeat(3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mpuginvy.html

TS:   "ab".repeat(3)
来源：http://dali.chenjidiqi.icu/Article/details/gt2mozlvyrx.html

Java: "ab".repeat(3)
来源：http://dali.sysykeji.top/Article/details/gt2vksewpuh.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.tian-w.cn/Article/details/gt2zitegswa.html

Ruby: "ab" * 3
来源：http://dali.sufxvd.cn/Article/details/gt2thocspeb.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.haohaochexian.top/Article/details/gt2fmpusgmt.html

[E03] 截取子串
来源：http://dali.cheryme.top/Article/details/gt2ylqviwlg.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.redwolf501.top/Article/details/gt2bmsbptit.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.chenjidiqi.icu/Article/details/gt2rjfhbufa.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jlsjyb.cn/Article/details/gt2hymswkgm.html

TS:   s.slice(1, 4)
来源：http://dali.yuanzhike.top/Article/details/gt2rgkcxhjn.html

Java: s.substring(1, 4)
来源：http://dali.hnqzz.top/Article/details/gt2ivmcvwue.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.cheryme.top/Article/details/gt2skzasitm.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jinqigufen.top/Article/details/gt2quaytqon.html

C#:   s.Substring(1, 3)
来源：http://dali.tanke756.top/Article/details/gt2hhtrfwrp.html

[E04] 查找子串位置
来源：http://dali.jinqigufen.top/Article/details/gt2pubxqrwf.html

Py:   s.find("x");  s.index("x")
来源：http://dali.nanxinkj.top/Article/details/gt2tduyzjsf.html

PHP:  strpos($s, "x");
来源：http://dali.wangshuangyany.cn/Article/details/gt2pslvyexz.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.chenlongwang.top/Article/details/gt2endjxiqq.html

TS:   s.indexOf("x")
来源：http://dali.birdmap.top/Article/details/gt2azbjnfjq.html

Java: s.indexOf("x")
来源：http://dali.cdnleiting.top/Article/details/gt2esamqkwg.html

Go:   strings.Index(s, "x")
来源：http://dali.yj20258888.top/Article/details/gt2ippfrjey.html

Ruby: s.index("x")
来源：http://dali.cheryme.top/Article/details/gt2lkdlwngq.html

C#:   s.IndexOf("x")
来源：http://dali.sweek.top/Article/details/gt2zfrhkduc.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.birdmap.top/Article/details/gt2ubvvfyxn.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jinqigfzy.top/Article/details/gt2pdwolykl.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.chenlongwang.top/Article/details/gt2hiptorpq.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.daxiang520.top/Article/details/gt2majfdads.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yangfankeji.com/Article/details/gt2qrbvolly.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hysaishi.cn/Article/details/gt2vvvivqaw.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hnqzz.top/Article/details/gt2edpnnhfq.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.gzhubu.top/Article/details/gt2adeizzpo.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yj20258888.top/Article/details/gt2tprkshgf.html

[E06] 替换子串
来源：http://dali.redwolf501.top/Article/details/gt2okyytllz.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yonumen.top/Article/details/gt2hcwkjcsd.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.ppjwa.cn/Article/details/gt2wojyxjel.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinqigufen.top/Article/details/gt2pmqpniys.html

TS:   s.replaceAll("a", "b")
来源：http://dali.wangdashe.top/Article/details/gt2vgkgmqsk.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jianghu66.top/Article/details/gt2laphgjuv.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.gogol.net.cn/Article/details/gt2vtggpnfr.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yj20258.top/Article/details/gt2pbnfenax.html

C#:   s.Replace("a", "b")
来源：http://dali.tanke756.top/Article/details/gt2ygzkmcbn.html

[E07] 按分隔符拆分
来源：http://dali.xinyue.icu/Article/details/gt2jkflnuse.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.cucudq.cn/Article/details/gt2idesvymi.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhoulong.xyz/Article/details/gt2uvkgyghe.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.fzhhl.top/Article/details/gt2plobkmmk.html

TS:   s.split(",")
来源：http://dali.birdmap.top/Article/details/gt2rjwgiroc.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.andypj.xyz/Article/details/gt2tfopnuii.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2pugtcyjj.html

Ruby: s.split(",");  s.split
来源：http://dali.dianchejie.cn/Article/details/gt2ojrxvxdr.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yongpay.top/Article/details/gt2upvmodep.html

[E08] 数组按分隔符合并
来源：http://dali.yongpay.top/Article/details/gt2xcvmmgee.html

Py:   ",".join(items)
来源：http://dali.jinqigufen.top/Article/details/gt2vddycdec.html

PHP:  implode(",", $items);
来源：http://dali.fzhhl.top/Article/details/gt2grnyzswm.html

JS:   items.join(",")
来源：http://dali.bjfxy.top/Article/details/gt2kdaovtdw.html

TS:   items.join(",")
来源：http://dali.guowangkeji.top/Article/details/gt2hyqokeis.html

Java: String.join(",", items)
来源：http://dali.chenlongwang.top/Article/details/gt2kafnxsat.html

Go:   strings.Join(items, ",")
来源：http://dali.hfpthk.cn/Article/details/gt2kwaabjds.html

Ruby: items.join(",")
来源：http://dali.zhiwuduotai.top/Article/details/gt2xtbmhenp.html

C#:   string.Join(",", items)
来源：http://dali.yj20258.top/Article/details/gt2xoaeygdl.html

[E09] 去除所有空白字符
来源：http://dali.mhx1999.top/Article/details/gt2uxeepqnl.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhongyouzk.top/Article/details/gt2qccuwari.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jinqigufen.top/Article/details/gt2bkhrwlud.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.ydzc1.top/Article/details/gt2asvumzyt.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhoulong.xyz/Article/details/gt2jrcyrbvz.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.mhx1999.top/Article/details/gt2kbrttcgs.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.gzhubu.top/Article/details/gt2fdwahuxn.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.vqdsnc.cn/Article/details/gt2hnnylnvv.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.cqqwz.cn/Article/details/gt2jdgyzjcw.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yj202588.top/Article/details/gt2ikakbitu.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.sysykeji.top/Article/details/gt2nqdnwphu.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yongpay.top/Article/details/gt2wrkdmurx.html

JS:   "7".padStart(3, "0")
来源：http://dali.shuidangran.top/Article/details/gt2epayayir.html

TS:   "7".padStart(3, "0")
来源：http://dali.c1oappe.top/Article/details/gt2iykarijx.html

Java: String.format("%03d", 7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pthztlwo.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.nwbrower.top/Article/details/gt2zodvyjgk.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.iojbl.cn/Article/details/gt2mwncbtej.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.ppjwa.cn/Article/details/gt2amdluzrm.html

[E11] 反转字符串
来源：http://dali.zhongyouzk.top/Article/details/gt2ooxazliv.html

Py:   s[::-1]
来源：http://dali.mhx1999.top/Article/details/gt2hnvrgrhb.html

PHP:  strrev($s);
来源：http://dali.cashguo.top/Article/details/gt2qmvhgwcp.html

JS:   [...s].reverse().join("")
来源：http://dali.zycfv.cn/Article/details/gt2gbhbtzet.html

TS:   [...s].reverse().join("")
来源：http://dali.hongshengwenyu.top/Article/details/gt2qitnlpnm.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.gogol.net.cn/Article/details/gt2copwmian.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yuanzhike.top/Article/details/gt2skiyyipm.html

Ruby: s.reverse
来源：http://dali.xylfe.cn/Article/details/gt2gxmcljlp.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.shangyingyoupin.top/Article/details/gt2kbbdawhn.html

[E12] 统计某字符出现次数
来源：http://dali.tian-w.cn/Article/details/gt2gkigdums.html

Py:   s.count("a")
来源：http://dali.sufxvd.cn/Article/details/gt2mbwrstxj.html

PHP:  substr_count($s, "a");
来源：http://dali.yj202588.top/Article/details/gt2phnsbzcp.html

JS:   s.split("a").length - 1
来源：http://dali.tian-w.cn/Article/details/gt2xvzrqogc.html

TS:   s.split("a").length - 1
来源：http://dali.haohaochexian.top/Article/details/gt2ehlhasek.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.mhx1999.top/Article/details/gt2lnetulal.html

Go:   strings.Count(s, "a")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iteqizra.html

Ruby: s.count("a")
来源：http://dali.guowangkeji.top/Article/details/gt2okzbbelp.html

C#:   s.Count(c => c == 'a')
来源：http://dali.sxryk.cn/Article/details/gt2ztjjcndu.html

[E13] 逐字符遍历
来源：http://dali.shzxlz.cn/Article/details/gt2uviznjdw.html

Py:   for ch in s: print(ch)
来源：http://dali.sweek.top/Article/details/gt2iisccltp.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.9152youxi.cn/Article/details/gt2utvmqygf.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.meibo888.top/Article/details/gt2ffjjuric.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.nanxuanxn.top/Article/details/gt2vjeyapek.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.cashguo.top/Article/details/gt2swaiimla.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.snrcjt.cn/Article/details/gt2uuummmjh.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.feifeiyinyue.top/Article/details/gt2exmswjsn.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.fzhhl.top/Article/details/gt2lkygbgyz.html

[E14] URL 编码与 Base64
来源：http://dali.cheryme.top/Article/details/gt2tzaoupvv.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yuanzhike.top/Article/details/gt2wpyxxmvd.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.chenzaomai.com/Article/details/gt2kjmsuqms.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.kuanghao11.cn/Article/details/gt2pzbxapta.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhixingplan.top/Article/details/gt2doogfkoy.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.sweek.top/Article/details/gt2ddtahfvp.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.smart0.xyz/Article/details/gt2imhfjxak.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.daria6918.cn/Article/details/gt2ugcydvvo.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.nanxuanxn.top/Article/details/gt2krspfwqg.html

[E15] HTML 转义 / 反转义
来源：http://dali.xuetiantiany.cn/Article/details/gt2kcrmdqqo.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2muroadvg.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.chenzaomai.com/Article/details/gt2rfdxaenv.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.ehwqpu.com/Article/details/gt2dvpxjexv.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.guowangkeji.top/Article/details/gt2pygfacqx.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.snrcjt.cn/Article/details/gt2pnkswyyb.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jyoumei.cn/Article/details/gt2cxgubgng.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.snrcjt.cn/Article/details/gt2oowgwftc.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hywenlv.cn/Article/details/gt2dbodiust.html

[E16] 数字千分位
来源：http://dali.feifeiyinyue.top/Article/details/gt2dxevukby.html

Py:   f"{1234567:,}"
来源：http://dali.cheryme.top/Article/details/gt2mjzwjfip.html

PHP:  number_format(1234567);
来源：http://dali.c1oappe.top/Article/details/gt2dymjfruq.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.gotoacloud.top/Article/details/gt2xjvzyduw.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.ivvv.top/Article/details/gt2rgkmwpai.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.cdnleiting.top/Article/details/gt2zbpekokk.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.svipenyu.cn/Article/details/gt2jefdpqkv.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhiwuduotai.top/Article/details/gt2igggemdp.html

C#:   1234567.ToString("N0")
来源：http://dali.yuxming.cn/Article/details/gt2kgfscdzp.html

[E17] 首字母大写
来源：http://dali.yuanzhike.top/Article/details/gt2nybahsab.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hywenlv.cn/Article/details/gt2xbskcvak.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.guowangkeji.top/Article/details/gt2cgxfpokd.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2glipkyik.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinqigfzy.top/Article/details/gt2yqidvzcw.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhixingplan.top/Article/details/gt2vzmvqpjy.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.guannengcc.top/Article/details/gt2uwhyqotd.html

Ruby: s.capitalize
来源：http://dali.vqdsnc.cn/Article/details/gt2nngqezbu.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.0kj1m.cn/Article/details/gt2xvluulau.html

[E18] 模板占位符替换
来源：http://dali.jianghu66.top/Article/details/gt2ceyznnns.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2swrfupky.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cyjsatci.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.redwolf501.top/Article/details/gt2nxpcgwnq.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yongpay.top/Article/details/gt2fegqeapk.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hnxiangtu.top/Article/details/gt2vrfamesh.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.ybcxt.top/Article/details/gt2zebttwcn.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.quarkkingdee.top/Article/details/gt2nphrsodk.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.ehwqpu.com/Article/details/gt2jmovwudm.html

[E19] 多行文本按行拆分
来源：http://dali.jinqigfzy.top/Article/details/gt2yacpkird.html

Py:   s.splitlines()
来源：http://dali.yueranfly.top/Article/details/gt2rlsooail.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rnuivelz.html

JS:   s.split(/\r?\n/)
来源：http://dali.dianchejie.cn/Article/details/gt2yqepvotj.html

TS:   s.split(/\r?\n/)
来源：http://dali.yanxiufei.cn/Article/details/gt2zuyflptr.html

Java: s.lines().toList()
来源：http://dali.snrcjt.cn/Article/details/gt2klwjtpob.html

Go:   strings.Split(s, "\n")
来源：http://dali.yueranfly.top/Article/details/gt2tfqglrme.html

Ruby: s.lines
来源：http://dali.pengpengdd.cyou/Article/details/gt2sewfhbis.html

C#:   s.Split('\n')
来源：http://dali.zhengqikj.top/Article/details/gt2sziprhuw.html

[E20] 判断字符串是否为空
来源：http://dali.mhx1999.top/Article/details/gt2suzkckhf.html

Py:   if not s:
来源：http://dali.birdmap.top/Article/details/gt2nnuqgcby.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.shuidangran.top/Article/details/gt2fsvvdjbj.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2tearvahj.html

TS:   if (s === "") {}
来源：http://dali.gotoacloud.top/Article/details/gt2sgomhear.html

Java: if (s.isEmpty()) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2xoedqull.html

Go:   if s == "" {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2icdowzvs.html

Ruby: if s.empty?
来源：http://dali.ehwqpu.com/Article/details/gt2jnkkhefy.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.gotoacloud.top/Article/details/gt2cgniowny.html

[E21] 超长截断加省略号
来源：http://dali.yuanzhike.top/Article/details/gt2ybtrlwou.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lnlzurxo.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jlsjyb.cn/Article/details/gt2yyuufhhh.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhiwuduotai.top/Article/details/gt2ofaufwdf.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hammf.cn/Article/details/gt2qammcikm.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ztzbljon.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hongshengwenyu.top/Article/details/gt2nnimmiqf.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.meibo888.top/Article/details/gt2vpugmryw.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.ydzc1.top/Article/details/gt2rxbcjqcq.html

[E22] 字节长度与字符长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2znltxfdb.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2fvwghqrt.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.dianchejie.cn/Article/details/gt2nuxoiopu.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.daxiang520.top/Article/details/gt2yoyjkjwe.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.nwbrower.top/Article/details/gt2cwwuolfw.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2blbezenp.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.cheryme.top/Article/details/gt2qzkcdwno.html

Ruby: s.bytesize;  s.length
来源：http://dali.cucudq.cn/Article/details/gt2wmmuehnr.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhoulong.xyz/Article/details/gt2wfujvtvb.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hyudaxak.html

F. 文件与目录
来源：http://dali.smart0.xyz/Article/details/gt2qpctwhpn.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2pcvcqxvr.html

[F01] 读取整个文件
来源：http://dali.andypj.xyz/Article/details/gt2fllionmw.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.tanke756.top/Article/details/gt2yjywyxwp.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zycfv.cn/Article/details/gt2tfuxkkly.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jinqigfzy.top/Article/details/gt2bfigylik.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.shuidangran.top/Article/details/gt2yrcagvsv.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yj202588.top/Article/details/gt2mipgmmfr.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vzdnofue.html

Ruby: File.read("a.txt")
来源：http://dali.xylfe.cn/Article/details/gt2ylemgipg.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gt2wogniurx.html

[F02] 逐行读取文件
来源：http://dali.nwbrower.top/Article/details/gt2cuulxvlu.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.pycfn.com/Article/details/gt2dlsygbet.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.quarkkingdee.top/Article/details/gt2tcjgunpx.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2ibutnfkc.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.tian-w.cn/Article/details/gt2cghzsptu.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.cashguo.top/Article/details/gt2oqufkkkp.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yj202588.top/Article/details/gt2ikuiwlyj.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.svipenyu.cn/Article/details/gt2aysmtkrj.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.svipenyu.cn/Article/details/gt2vpqmwngb.html

[F03] 写入文件（覆盖）
来源：http://dali.chenzaomai.com/Article/details/gt2fvfjengc.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.sweek.top/Article/details/gt2beafblff.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.fengsongda.top/Article/details/gt2midwlfuf.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhoulong.xyz/Article/details/gt2baybreky.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinqigufen.top/Article/details/gt2cvjegzhg.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yj202588.top/Article/details/gt2nbdixgfx.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.aibaodan.cn/Article/details/gt2doxyeyrk.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.guannengcc.top/Article/details/gt2hnmxusnw.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jiagoushi.top/Article/details/gt2prenejjd.html

[F04] 追加写入文件
来源：http://dali.fzhhl.top/Article/details/gt2kclsgbkg.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pwahbrxt.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.ybcxt.top/Article/details/gt2ziifokmz.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zycfv.cn/Article/details/gt2kdfqhiam.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hfpthk.cn/Article/details/gt2ghnbumrp.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhiwuduotai.top/Article/details/gt2bnyjcgmi.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhoulong.xyz/Article/details/gt2ieimbfao.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jinqigufen.top/Article/details/gt2xhrexxyu.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.vqdsnc.cn/Article/details/gt2gckrjbeo.html

[F05] 判断文件或目录是否存在
来源：http://dali.chenzaomai.com/Article/details/gt2vwqdxaqm.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yonumen.top/Article/details/gt2totlajvm.html

PHP:  file_exists("a.txt");
来源：http://dali.mhx1999.top/Article/details/gt2gxodhbxe.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hammf.cn/Article/details/gt2vpgvklrx.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2giyjyeeh.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hysaishi.cn/Article/details/gt2znedcyga.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.sxryk.cn/Article/details/gt2eminvcjl.html

Ruby: File.exist?("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2zzvforeg.html

C#:   File.Exists("a.txt")
来源：http://dali.yj202588.top/Article/details/gt2pnogjkee.html

[F06] 删除文件
来源：http://dali.wangshuangyany.cn/Article/details/gt2wztetyny.html

Py:   os.remove("a.txt")
来源：http://dali.yj202588.top/Article/details/gt2yaoorqwz.html

PHP:  unlink("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gt2tmzuoptf.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2qnxwdyej.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2ajlmfrqb.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.316326.xyz/Article/details/gt2rjjifzos.html

Go:   os.Remove("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2dudlgudz.html

Ruby: File.delete("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2xxfmjczi.html

C#:   File.Delete("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gt2hxdhiltv.html

[F07] 创建目录（含多级）
来源：http://dali.iojbl.cn/Article/details/gt2oryzohge.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.quarkkingdee.top/Article/details/gt2omgulpxc.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.kuanghao11.cn/Article/details/gt2gdvxxtqa.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cheryme.top/Article/details/gt2tyodtmiq.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ivvv.top/Article/details/gt2srdbnufo.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.sxryk.cn/Article/details/gt2koceeeli.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ivvv.top/Article/details/gt2gdsmyulv.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jianghu66.top/Article/details/gt2jalvcexv.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yangfankeji.com/Article/details/gt2aevhdtlm.html

[F08] 遍历目录
来源：http://dali.tian-w.cn/Article/details/gt2kqdzqnwb.html


<!-- 参考信息 -->