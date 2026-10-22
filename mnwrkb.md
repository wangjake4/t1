代发 wailian999

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.andypj.xyz/Article/details/gt2vtarlnjx.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.wangshuangyany.cn/Article/details/gt2swmwtypm.html

Go:   // 手写循环
来源：http://dali.9152youxi.cn/Article/details/gt2iiqpthng.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.gogol.net.cn/Article/details/gt2igyqsggp.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.tanke756.top/Article/details/gt2vyqdbyzk.html

[D24] 字典 / Map 基本操作
来源：http://dali.aibaodan.cn/Article/details/gt2adprmcuk.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yangfankeji.com/Article/details/gt2yqadffax.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lgtcsaye.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.gogol.net.cn/Article/details/gt2mafxcled.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zycfv.cn/Article/details/gt2pfroohsn.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.mhx1999.top/Article/details/gt2eempcjrw.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.ydzc1.top/Article/details/gt2lwrhcjml.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.gzhubu.top/Article/details/gt2eqgwsnhe.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.hammf.cn/Article/details/gt2ltxfgxmv.html

[D25] Set 集合去重与交并差
来源：http://dali.zycfv.cn/Article/details/gt2vzuswdsq.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nlpnhmvy.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.dashuyun.cn/Article/details/gt2gnlxfbjq.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.shuidangran.top/Article/details/gt2qkunxxte.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.birdmap.top/Article/details/gt2oqwiuraa.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhengqikj.top/Article/details/gt2nygowogg.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zycfv.cn/Article/details/gt2vaptcqdc.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.fengsongda.top/Article/details/gt2ntlfsmyx.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhixingplan.top/Article/details/gt2hebykchg.html

[D26] 数组转字符串
来源：http://dali.316326.xyz/Article/details/gt2hfwjjebl.html

Py:   ", ".join(map(str, arr))
来源：http://dali.svipenyu.cn/Article/details/gt2xckvsnvn.html

PHP:  implode(", ", $arr);
来源：http://dali.cdnleiting.top/Article/details/gt2pzvthsqr.html

JS:   arr.join(", ")
来源：http://dali.vqdsnc.cn/Article/details/gt2remwslvq.html

TS:   arr.join(", ")
来源：http://dali.chenzaomai.com/Article/details/gt2cgizktfq.html

Java: String.join(", ", list)
来源：http://dali.gogol.net.cn/Article/details/gt2canxngwl.html

Go:   strings.Join(strs, ", ")
来源：http://dali.hysaishi.cn/Article/details/gt2lsqlnysj.html

Ruby: arr.join(", ")
来源：http://dali.fengsongda.top/Article/details/gt2chhfyijj.html

C#:   string.Join(", ", list)
来源：http://dali.ybcxt.top/Article/details/gt2hiezeblh.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2giidiejs.html

E. 字符串处理
来源：http://dali.svipenyu.cn/Article/details/gt2sclitlje.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2zcklnhiq.html

[E01] 拼接字符串
来源：http://dali.chenlongwang.top/Article/details/gt2yzliasbj.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.tanke756.top/Article/details/gt2lzbxmytn.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yuanzhike.top/Article/details/gt2naslqnfo.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yonumen.top/Article/details/gt2ritwjzkc.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cucudq.cn/Article/details/gt2cceovbrb.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ozxlzixn.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.xuetiantiany.cn/Article/details/gt2ypdetprm.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ysvqiafe.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gt2hsieoupp.html

[E02] 重复字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ekjvlscv.html

Py:   "ab" * 3
来源：http://dali.ybcxt.top/Article/details/gt2tvcgkwyj.html

PHP:  str_repeat("ab", 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ecjtceru.html

JS:   "ab".repeat(3)
来源：http://dali.chenlongwang.top/Article/details/gt2nrwfwjdc.html

TS:   "ab".repeat(3)
来源：http://dali.yonumen.top/Article/details/gt2vsmczigt.html

Java: "ab".repeat(3)
来源：http://dali.hongshengwenyu.top/Article/details/gt2bzzazfos.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vbjzfzqo.html

Ruby: "ab" * 3
来源：http://dali.dianchejie.cn/Article/details/gt2tlxotlnk.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yj20258.top/Article/details/gt2qdxwnrny.html

[E03] 截取子串
来源：http://dali.tian-w.cn/Article/details/gt2kjwwudwp.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jinqigufen.top/Article/details/gt2tugswocz.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.daxiang520.top/Article/details/gt2musfbyfu.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.316326.xyz/Article/details/gt2prrwvcmr.html

TS:   s.slice(1, 4)
来源：http://dali.zdqjudy.top/Article/details/gt2irvzuovp.html

Java: s.substring(1, 4)
来源：http://dali.feifeiyinyue.top/Article/details/gt2zbdidkff.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.hywenlv.cn/Article/details/gt2hzvdpeja.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.wangshuangyany.cn/Article/details/gt2gamycdfo.html

C#:   s.Substring(1, 3)
来源：http://dali.sweek.top/Article/details/gt2oleqrjje.html

[E04] 查找子串位置
来源：http://dali.chenzaomai.com/Article/details/gt2abaxvtne.html

Py:   s.find("x");  s.index("x")
来源：http://dali.guannengcc.top/Article/details/gt2tgsolitk.html

PHP:  strpos($s, "x");
来源：http://dali.yangfankeji.com/Article/details/gt2kuucscrb.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.gaohongyu789.top/Article/details/gt2pwptzuuy.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2zdwbifzr.html

Java: s.indexOf("x")
来源：http://dali.yuanzhike.top/Article/details/gt2ytazlfkz.html

Go:   strings.Index(s, "x")
来源：http://dali.yangfankeji.com/Article/details/gt2wcdlcmkm.html

Ruby: s.index("x")
来源：http://dali.0kj1m.cn/Article/details/gt2upssrjos.html

C#:   s.IndexOf("x")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ovsdokoa.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.316326.xyz/Article/details/gt2ltrewlpc.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.vqdsnc.cn/Article/details/gt2enelrewq.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.chenjidiqi.icu/Article/details/gt2iujfpjje.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.fengsongda.top/Article/details/gt2ghafzaqb.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yonumen.top/Article/details/gt2zvvytcjx.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yuanzhike.top/Article/details/gt2dgphlwkj.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jiagoushi.top/Article/details/gt2tiaovxvw.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.chenlongwang.top/Article/details/gt2awaamqoo.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.gaohongyu789.top/Article/details/gt2bupwtdjs.html

[E06] 替换子串
来源：http://dali.dashuyun.cn/Article/details/gt2lgvjdwmu.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jdzvpzxa.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.shuidangran.top/Article/details/gt2sboqhggu.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.havefunace.top/Article/details/gt2ctlcbwft.html

TS:   s.replaceAll("a", "b")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uhxtqwct.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhoulong.xyz/Article/details/gt2vfzowhpj.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yj20258.top/Article/details/gt2fjfhvume.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.wangdashe.top/Article/details/gt2kghfmfaz.html

C#:   s.Replace("a", "b")
来源：http://dali.quarkkingdee.top/Article/details/gt2nfkqjbmt.html

[E07] 按分隔符拆分
来源：http://dali.daxiang520.top/Article/details/gt2mhchvteh.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yongpay.top/Article/details/gt2wmzrilni.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yvedp.cn/Article/details/gt2otkrsoen.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jqgfzy.top/Article/details/gt2djakywzn.html

TS:   s.split(",")
来源：http://dali.zhengqikj.top/Article/details/gt2xuxgdtlg.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.hongshengwenyu.top/Article/details/gt2walvhdai.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2sfxntdtc.html

Ruby: s.split(",");  s.split
来源：http://dali.xuanzx.com/Article/details/gt2ffpqzeda.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.dashuyun.cn/Article/details/gt2vfzbmbit.html

[E08] 数组按分隔符合并
来源：http://dali.hfpthk.cn/Article/details/gt2purghjge.html

Py:   ",".join(items)
来源：http://dali.zycfv.cn/Article/details/gt2ztciqlmc.html

PHP:  implode(",", $items);
来源：http://dali.smart0.xyz/Article/details/gt2obzrbnwy.html

JS:   items.join(",")
来源：http://dali.tanke756.top/Article/details/gt2yadasoxl.html

TS:   items.join(",")
来源：http://dali.yuanzhike.top/Article/details/gt2syjqoshb.html

Java: String.join(",", items)
来源：http://dali.jinqigufen.top/Article/details/gt2nxycuazy.html

Go:   strings.Join(items, ",")
来源：http://dali.guowangkeji.top/Article/details/gt2qoixusda.html

Ruby: items.join(",")
来源：http://dali.hnxiangtu.top/Article/details/gt2ziweemti.html

C#:   string.Join(",", items)
来源：http://dali.redwolf501.top/Article/details/gt2frsrvphj.html

[E09] 去除所有空白字符
来源：http://dali.cdnleiting.top/Article/details/gt2tefgvocr.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yongpay.top/Article/details/gt2hkaawjcz.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.c1oappe.top/Article/details/gt2emaouyjw.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.hammf.cn/Article/details/gt2qgaviguu.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.xuanzx.com/Article/details/gt2vpvypgsk.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.gotoacloud.top/Article/details/gt2xbgdsrji.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yuxming.cn/Article/details/gt2eckysncx.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.dianchejie.cn/Article/details/gt2catiyscx.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yj20258888.top/Article/details/gt2uvidytvy.html

[E10] 左侧补零 / 定长填充
来源：http://dali.wangdashe.top/Article/details/gt2akexwxxc.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yj20258.top/Article/details/gt2fmztjtqo.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.gotoacloud.top/Article/details/gt2miuwxvjy.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhixingplan.top/Article/details/gt2fvyuwxwj.html

TS:   "7".padStart(3, "0")
来源：http://dali.ehwqpu.com/Article/details/gt2ggvubzgv.html

Java: String.format("%03d", 7)
来源：http://dali.zhixingplan.top/Article/details/gt2kipdtkyn.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.xuanzx.com/Article/details/gt2lwwhgbiq.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhixingplan.top/Article/details/gt2qarwkvif.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jqgufenzy.top/Article/details/gt2wllgozzz.html

[E11] 反转字符串
来源：http://dali.xziqi.cn/Article/details/gt2pdzpqjkg.html

Py:   s[::-1]
来源：http://dali.meibo888.top/Article/details/gt2hefdljtg.html

PHP:  strrev($s);
来源：http://dali.wangdashe.top/Article/details/gt2muuhzquw.html

JS:   [...s].reverse().join("")
来源：http://dali.yj20258.top/Article/details/gt2wttlqzwg.html

TS:   [...s].reverse().join("")
来源：http://dali.havefunace.top/Article/details/gt2ruedgcur.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jlsjyb.cn/Article/details/gt2aukcmfxj.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.redwolf501.top/Article/details/gt2qrvndufb.html

Ruby: s.reverse
来源：http://dali.smart0.xyz/Article/details/gt2ihxannjy.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.xziqi.cn/Article/details/gt2lupkfqxg.html

[E12] 统计某字符出现次数
来源：http://dali.zhiwuduotai.top/Article/details/gt2iccjmqjo.html

Py:   s.count("a")
来源：http://dali.chenjidiqi.icu/Article/details/gt2rdjuexca.html

PHP:  substr_count($s, "a");
来源：http://dali.cucudq.cn/Article/details/gt2rlknlpht.html

JS:   s.split("a").length - 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qergnlxx.html

TS:   s.split("a").length - 1
来源：http://dali.sufxvd.cn/Article/details/gt2ubsenjwe.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.hongshengwenyu.top/Article/details/gt2tcjmrhyk.html

Go:   strings.Count(s, "a")
来源：http://dali.jinqigfzy.top/Article/details/gt2fnntmrkw.html

Ruby: s.count("a")
来源：http://dali.ivvv.top/Article/details/gt2xjhiuhml.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhixingplan.top/Article/details/gt2ckuctzvv.html

[E13] 逐字符遍历
来源：http://dali.yvedp.cn/Article/details/gt2cwsgjepr.html

Py:   for ch in s: print(ch)
来源：http://dali.zycfv.cn/Article/details/gt2jlpmxwxa.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.dianchejie.cn/Article/details/gt2ivfcxjyb.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinqigfzy.top/Article/details/gt2ulxlmmvu.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ydzc1.top/Article/details/gt2bogshkxr.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.tanke756.top/Article/details/gt2ldolvpam.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hysaishi.cn/Article/details/gt2snuwekdg.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yueranfly.top/Article/details/gt2yvmryuzw.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.gogol.net.cn/Article/details/gt2nbzpdggo.html

[E14] URL 编码与 Base64
来源：http://dali.gotoacloud.top/Article/details/gt2ihvwhecj.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.pengpengdd.cyou/Article/details/gt2kyohmufp.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.chenzaomai.com/Article/details/gt2zblkacnm.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.0kj1m.cn/Article/details/gt2cstagqgl.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2wxcdvcti.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hywenlv.cn/Article/details/gt2yinibmop.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.xuanzx.com/Article/details/gt2axmcnhll.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.fengsongda.top/Article/details/gt2xpiquqnx.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.nanxinkj.top/Article/details/gt2xbdfiwjt.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhijiandao.cn/Article/details/gt2rgunqhiy.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.fzhhl.top/Article/details/gt2vlmysqlz.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yuanzhike.top/Article/details/gt2dxrvpign.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.daria6918.cn/Article/details/gt2ofbqqxkv.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jiagoushi.top/Article/details/gt2dmwdtpto.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.sweek.top/Article/details/gt2tgsfrinl.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.ybcxt.top/Article/details/gt2dzgpemur.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xylfe.cn/Article/details/gt2vezkwido.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2vlgdpkfq.html

[E16] 数字千分位
来源：http://dali.gaohongyu789.top/Article/details/gt2faoipdcr.html

Py:   f"{1234567:,}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wbiwgqkf.html

PHP:  number_format(1234567);
来源：http://dali.zhongyouzk.top/Article/details/gt2hkpgmncy.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.daxiang520.top/Article/details/gt2cnclnhvo.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.chenzaomai.com/Article/details/gt2hvfwmcxv.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.0kj1m.cn/Article/details/gt2wkagwwer.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.fengsongda.top/Article/details/gt2bvhdmzla.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.shangyingyoupin.top/Article/details/gt2dehewlpa.html

C#:   1234567.ToString("N0")
来源：http://dali.dianchejie.cn/Article/details/gt2dvdlanln.html

[E17] 首字母大写
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ejpbbqny.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.nanxinkj.top/Article/details/gt2cgxjimdp.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yuxming.cn/Article/details/gt2mppdqgao.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sufxvd.cn/Article/details/gt2qeidvros.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gotoacloud.top/Article/details/gt2krsxlrfp.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.daria6918.cn/Article/details/gt2uyevotzw.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.kuanghao11.cn/Article/details/gt2otrzrurf.html

Ruby: s.capitalize
来源：http://dali.tianlin.xyz/Article/details/gt2mcsqkqcg.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.dianchejie.cn/Article/details/gt2siyoiktr.html

[E18] 模板占位符替换
来源：http://dali.pycfn.com/Article/details/gt2qdswwvgb.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhengqikj.top/Article/details/gt2segyvinm.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.0kj1m.cn/Article/details/gt2qwhaafrj.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ecqzbmla.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhixingplan.top/Article/details/gt2phjmqmtx.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.cucudq.cn/Article/details/gt2ongvhmpn.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.ydzc1.top/Article/details/gt2yhtjjujf.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.xziqi.cn/Article/details/gt2uirnzoza.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.cheryme.top/Article/details/gt2cvfqmzwu.html

[E19] 多行文本按行拆分
来源：http://dali.ydzc1.top/Article/details/gt2qpoeoozi.html

Py:   s.splitlines()
来源：http://dali.yangfankeji.com/Article/details/gt2gtbovggg.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.sufxvd.cn/Article/details/gt2osmdcdkg.html

JS:   s.split(/\r?\n/)
来源：http://dali.ydzc1.top/Article/details/gt2cxzkvgph.html

TS:   s.split(/\r?\n/)
来源：http://dali.xziqi.cn/Article/details/gt2vhyttlpj.html

Java: s.lines().toList()
来源：http://dali.cashguo.top/Article/details/gt2meozzzam.html

Go:   strings.Split(s, "\n")
来源：http://dali.jinqigufen.top/Article/details/gt2hqihnkwr.html

Ruby: s.lines
来源：http://dali.sxryk.cn/Article/details/gt2tqzkehui.html

C#:   s.Split('\n')
来源：http://dali.nwbrower.top/Article/details/gt2tujmwvvv.html

[E20] 判断字符串是否为空
来源：http://dali.hnqzz.top/Article/details/gt2wpuhudgv.html

Py:   if not s:
来源：http://dali.iojbl.cn/Article/details/gt2cgguevjt.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.ehwqpu.com/Article/details/gt2qyqnvrge.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.guowangkeji.top/Article/details/gt2dfdafudz.html

TS:   if (s === "") {}
来源：http://dali.gaohongyu789.top/Article/details/gt2hbsbxofc.html

Java: if (s.isEmpty()) {}
来源：http://dali.guannengcc.top/Article/details/gt2dnzdxtwv.html

Go:   if s == "" {}
来源：http://dali.pycfn.com/Article/details/gt2vvuxjlfo.html

Ruby: if s.empty?
来源：http://dali.jqgfzy.top/Article/details/gt2xewcljeo.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hysaishi.cn/Article/details/gt2hfudexpi.html

[E21] 超长截断加省略号
来源：http://dali.jinqigufen.top/Article/details/gt2wxcyqjzm.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hfpthk.cn/Article/details/gt2ppgmitaa.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.316326.xyz/Article/details/gt2rzvfszxm.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pnyjehbj.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ydzc1.top/Article/details/gt2jhwzmqlw.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.guowangkeji.top/Article/details/gt2zlnkcsyg.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cashguo.top/Article/details/gt2eiilusbj.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.hnqzz.top/Article/details/gt2xqifgmlr.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.316326.xyz/Article/details/gt2wygoaxrf.html

[E22] 字节长度与字符长度
来源：http://dali.hnqzz.top/Article/details/gt2aasuqiss.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2uojlhhxn.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jyoumei.cn/Article/details/gt2jdfakhil.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cucudq.cn/Article/details/gt2qygggkvt.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinqigfzy.top/Article/details/gt2rzlivove.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.aizwys.cn/Article/details/gt2fygknqwv.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.xuanzx.com/Article/details/gt2hwgbpoyi.html

Ruby: s.bytesize;  s.length
来源：http://dali.ydzc1.top/Article/details/gt2qwwwtkkk.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.svipenyu.cn/Article/details/gt2rehlgter.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2rduumqgs.html

F. 文件与目录
来源：http://dali.iojbl.cn/Article/details/gt2sdyilftw.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2ososrzut.html

[F01] 读取整个文件
来源：http://dali.guowangkeji.top/Article/details/gt2qviafhox.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ybcxt.top/Article/details/gt2qhfgbqvq.html

PHP:  file_get_contents("a.txt");
来源：http://dali.iojbl.cn/Article/details/gt2xwckovbw.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.guannengcc.top/Article/details/gt2egotzsgu.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.xinyue.icu/Article/details/gt2huvqeeti.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yj202588.top/Article/details/gt2zcmosmni.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yueranfly.top/Article/details/gt2yifdwdmt.html

Ruby: File.read("a.txt")
来源：http://dali.yj20258.top/Article/details/gt2idloibiw.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yueranfly.top/Article/details/gt2njplymkd.html

[F02] 逐行读取文件
来源：http://dali.daxiang520.top/Article/details/gt2akputhgf.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.haohaochexian.top/Article/details/gt2vhqmzwgd.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.sweek.top/Article/details/gt2ygsupguh.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenzaomai.com/Article/details/gt2cdhnbzbj.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2zdwgitnp.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.bjfxy.top/Article/details/gt2qqiswbda.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.cqqwz.cn/Article/details/gt2anazoidf.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.316326.xyz/Article/details/gt2fbwgxaul.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhongyouzk.top/Article/details/gt2uedkehae.html

[F03] 写入文件（覆盖）
来源：http://dali.yonumen.top/Article/details/gt2rimxzxbh.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.c1oappe.top/Article/details/gt2fshrwyug.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xuanzx.com/Article/details/gt2oruzenkv.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.kuanghao11.cn/Article/details/gt2cxxosgvx.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cqhcjmmu.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.tanke756.top/Article/details/gt2ascnwdtn.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.c1oappe.top/Article/details/gt2lvnvvctm.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ydzc1.top/Article/details/gt2alunpzlb.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.fzhhl.top/Article/details/gt2lfrovzrs.html

[F04] 追加写入文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jyltsfye.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yj202588.top/Article/details/gt2inlpejrv.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.daxiang520.top/Article/details/gt2jieyotbl.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cucudq.cn/Article/details/gt2qvjpotgd.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2meyiifqc.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhoulong.xyz/Article/details/gt2xwearnjx.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.guannengcc.top/Article/details/gt2qmassmur.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2unbsitxi.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2jckfjlni.html

[F05] 判断文件或目录是否存在
来源：http://dali.daxiang520.top/Article/details/gt2tgtkrjdz.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zdqjudy.top/Article/details/gt2ctjsjyze.html

PHP:  file_exists("a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gt2mvzejvwi.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2yhgzacun.html

TS:   fs.existsSync("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2hwrkmfon.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.nwbrower.top/Article/details/gt2peijaouf.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.svipenyu.cn/Article/details/gt2vxmwcydj.html

Ruby: File.exist?("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2nvkthnjx.html

C#:   File.Exists("a.txt")
来源：http://dali.birdmap.top/Article/details/gt2gatvzihw.html

[F06] 删除文件
来源：http://dali.dianchejie.cn/Article/details/gt2wuxnxzmx.html

Py:   os.remove("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2wzazqife.html

PHP:  unlink("a.txt");
来源：http://dali.havefunace.top/Article/details/gt2afqnzoge.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.aizwys.cn/Article/details/gt2eojolcmt.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.xinyue.icu/Article/details/gt2gypmxiin.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.cdnleiting.top/Article/details/gt2hkwoahim.html

Go:   os.Remove("a.txt")
来源：http://dali.yongpay.top/Article/details/gt2jrlwijyc.html

Ruby: File.delete("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2fbhymycw.html

C#:   File.Delete("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gt2fsrmhopz.html

[F07] 创建目录（含多级）
来源：http://dali.dashuyun.cn/Article/details/gt2xspwyjif.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.shuidangran.top/Article/details/gt2eqfaavdn.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yj20258888.top/Article/details/gt2pojaxfhx.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gzhubu.top/Article/details/gt2epjrnibi.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2stettwcq.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jinqigfzy.top/Article/details/gt2skbemowg.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yuxming.cn/Article/details/gt2welnawyd.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.guowangkeji.top/Article/details/gt2vnwijoqs.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.ydzc1.top/Article/details/gt2uzjphlca.html

[F08] 遍历目录
来源：http://dali.zycfv.cn/Article/details/gt2uklpvapr.html


<!-- 参考信息 -->