代发 wailian999

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gtxdzwjndr.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.gaohongyu789.top/Article/details/gtiqqxyebr.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jinqigufen.top/Article/details/gtjjmzmbkj.html

C#:   new List<int>(list);
来源：http://dali.kuanghao11.cn/Article/details/gtkrrrybej.html

[D23] reduce 累积计算
来源：http://dali.yuxming.cn/Article/details/gtckarilig.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.cdnleiting.top/Article/details/gtadewaeiw.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.smart0.xyz/Article/details/gtfqhierax.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjlrugzux.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.guowangkeji.top/Article/details/gttsqhfmmi.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.sysykeji.top/Article/details/gtigoxpyur.html

Go:   // 手写循环
来源：http://dali.tianlin.xyz/Article/details/gtzczrajlr.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.shanyushiyangkeji.top/Article/details/gtesybxhhw.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yanxiufei.cn/Article/details/gtkwhuxnmo.html

[D24] 字典 / Map 基本操作
来源：http://dali.yvedp.cn/Article/details/gttecojvea.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.cucudq.cn/Article/details/gtzkkfbokj.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.ydzc1.top/Article/details/gtjdskccpu.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jiagoushi.top/Article/details/gthgtwlmpp.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yvedp.cn/Article/details/gtohdaepks.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.xuanzx.com/Article/details/gtrjvyabhe.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.hfpthk.cn/Article/details/gtqatiudna.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.svipenyu.cn/Article/details/gtgcfdmkfn.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteibmqmus.html

[D25] Set 集合去重与交并差
来源：http://dali.xuanzx.com/Article/details/gtnhmjbcna.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jianghu66.top/Article/details/gtelltnaqr.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jinqigfzy.top/Article/details/gtzjslzqkq.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jianghu66.top/Article/details/gtymjuulif.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrmibexol.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.ybcxt.top/Article/details/gtkevthgks.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hammf.cn/Article/details/gtctuctclg.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.xziqi.cn/Article/details/gtzvgrmlch.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jlsjyb.cn/Article/details/gtrqjjghyl.html

[D26] 数组转字符串
来源：http://dali.gaohongyu789.top/Article/details/gtqtswobpe.html

Py:   ", ".join(map(str, arr))
来源：http://dali.wangshuangyany.cn/Article/details/gtdalcqztv.html

PHP:  implode(", ", $arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvhfjwlkc.html

JS:   arr.join(", ")
来源：http://dali.yangfankeji.com/Article/details/gtyuiiviow.html

TS:   arr.join(", ")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpnyywpmv.html

Java: String.join(", ", list)
来源：http://dali.wangdashe.top/Article/details/gtqdcnlyrv.html

Go:   strings.Join(strs, ", ")
来源：http://dali.birdmap.top/Article/details/gturdbaddh.html

Ruby: arr.join(", ")
来源：http://dali.jyoumei.cn/Article/details/gtvdgsacfn.html

C#:   string.Join(", ", list)
来源：http://dali.c1oappe.top/Article/details/gtdievckhy.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtcoxfxhqu.html

E. 字符串处理
来源：http://dali.tian-w.cn/Article/details/gtsmyjzgdq.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgjdalswm.html

[E01] 拼接字符串
来源：http://dali.yvedp.cn/Article/details/gtsjrmxywn.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.316326.xyz/Article/details/gtcibupbrv.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jqgfzy.top/Article/details/gtvxzbmawq.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yuxming.cn/Article/details/gtelwciwzd.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ivvv.top/Article/details/gtlyzcwvgn.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.aizwys.cn/Article/details/gthumilhdp.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.tanke756.top/Article/details/gtxgyvznbv.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.nanxinkj.top/Article/details/gtxldwessj.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.vqdsnc.cn/Article/details/gtneoispxc.html

[E02] 重复字符串
来源：http://dali.cucudq.cn/Article/details/gtclklroeh.html

Py:   "ab" * 3
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbkpgnbot.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hfpthk.cn/Article/details/gtjuxfnhht.html

JS:   "ab".repeat(3)
来源：http://dali.9152youxi.cn/Article/details/gtakwpszik.html

TS:   "ab".repeat(3)
来源：http://dali.fzhhl.top/Article/details/gtnrkdeice.html

Java: "ab".repeat(3)
来源：http://dali.316326.xyz/Article/details/gtgqavxlhg.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.nanxuanxn.top/Article/details/gtqmdsshcb.html

Ruby: "ab" * 3
来源：http://dali.smart0.xyz/Article/details/gtixbhstek.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.smart0.xyz/Article/details/gtugmfatqm.html

[E03] 截取子串
来源：http://dali.shanyushiyangtech.top/Article/details/gtnpkwwyka.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gtynrwjljq.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.chenlongwang.top/Article/details/gtdzjcmoau.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yj20258888.top/Article/details/gttvutbups.html

TS:   s.slice(1, 4)
来源：http://dali.mhx1999.top/Article/details/gtgtdcwwpk.html

Java: s.substring(1, 4)
来源：http://dali.cqqwz.cn/Article/details/gtgkklzlli.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.birdmap.top/Article/details/gtssxnlilv.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlyqqvsjs.html

C#:   s.Substring(1, 3)
来源：http://dali.gzhubu.top/Article/details/gttjkklojm.html

[E04] 查找子串位置
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvoqcesyq.html

Py:   s.find("x");  s.index("x")
来源：http://dali.cashguo.top/Article/details/gtggrirqqt.html

PHP:  strpos($s, "x");
来源：http://dali.bjfxy.top/Article/details/gtijazjfpf.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jinqigfzy.top/Article/details/gtwmmzrgbg.html

TS:   s.indexOf("x")
来源：http://dali.sweek.top/Article/details/gtzshoined.html

Java: s.indexOf("x")
来源：http://dali.cqqwz.cn/Article/details/gtkdrybqpe.html

Go:   strings.Index(s, "x")
来源：http://dali.gotoacloud.top/Article/details/gtnoflrnpq.html

Ruby: s.index("x")
来源：http://dali.snrcjt.cn/Article/details/gtpqekiexm.html

C#:   s.IndexOf("x")
来源：http://dali.gotoacloud.top/Article/details/gtciczorqy.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yonumen.top/Article/details/gttgjmcyhi.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yuxming.cn/Article/details/gtqorgzjjh.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.iojbl.cn/Article/details/gtevryszwo.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.nwbrower.top/Article/details/gttycjvuxm.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.fzhhl.top/Article/details/gtjwekrjql.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ppjwa.cn/Article/details/gtcwnymoys.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.andypj.xyz/Article/details/gtfulmgcqn.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.tanke756.top/Article/details/gtsshakxjm.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yj20258888.top/Article/details/gtftuhleoq.html

[E06] 替换子串
来源：http://dali.fzhhl.top/Article/details/gtmahiwfgg.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.dianchejie.cn/Article/details/gtxvgmzyts.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhiwuduotai.top/Article/details/gtagdgldfn.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hnxiangtu.top/Article/details/gtrbxsqwku.html

TS:   s.replaceAll("a", "b")
来源：http://dali.xinyue.icu/Article/details/gtflqhxxqj.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yueranfly.top/Article/details/gtqyskbcsy.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zdqjudy.top/Article/details/gtavatimyc.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yongpay.top/Article/details/gtmqaonugm.html

C#:   s.Replace("a", "b")
来源：http://dali.xuanzx.com/Article/details/gtybzxcamu.html

[E07] 按分隔符拆分
来源：http://dali.xylfe.cn/Article/details/gtkienbvev.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhiwuduotai.top/Article/details/gtpvduxdpu.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.tianlin.xyz/Article/details/gtjbpbowhp.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jqgfzy.top/Article/details/gtwburxjqi.html

TS:   s.split(",")
来源：http://dali.daxiang520.top/Article/details/gtssvazgxz.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhoulong.xyz/Article/details/gtulbdecwy.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.hnqzz.top/Article/details/gtwtyhnyuy.html

Ruby: s.split(",");  s.split
来源：http://dali.zhixingplan.top/Article/details/gtdxseshmi.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.sxryk.cn/Article/details/gtkwtaehrg.html

[E08] 数组按分隔符合并
来源：http://dali.gzhubu.top/Article/details/gtvlujeicm.html

Py:   ",".join(items)
来源：http://dali.mhx1999.top/Article/details/gtqofpzwkg.html

PHP:  implode(",", $items);
来源：http://dali.hongshengwenyu.top/Article/details/gtukypjabo.html

JS:   items.join(",")
来源：http://dali.smart0.xyz/Article/details/gtsdvxvqyn.html

TS:   items.join(",")
来源：http://dali.haohaochexian.top/Article/details/gtuhtcyogo.html

Java: String.join(",", items)
来源：http://dali.bjfxy.top/Article/details/gtlhvfiodx.html

Go:   strings.Join(items, ",")
来源：http://dali.sweek.top/Article/details/gtagkydwvz.html

Ruby: items.join(",")
来源：http://dali.dashuyun.cn/Article/details/gtmdremflr.html

C#:   string.Join(",", items)
来源：http://dali.ppjwa.cn/Article/details/gtxecffbaz.html

[E09] 去除所有空白字符
来源：http://dali.sweek.top/Article/details/gtmmzlhgbc.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jlsjyb.cn/Article/details/gtddpwbygo.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhengqikj.top/Article/details/gtgbjcyqqf.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.chenjidiqi.icu/Article/details/gtzhmtpsmt.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.wangshuangyany.cn/Article/details/gtxxhvpqnu.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.tanke756.top/Article/details/gtcrsfmalv.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.haohaochexian.top/Article/details/gtqiuwxfbg.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.shanyushiyangtech.top/Article/details/gteyaposgo.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.gaohongyu789.top/Article/details/gtaofxtfyn.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jinqigfzy.top/Article/details/gtbrsbnrnp.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.cheryme.top/Article/details/gteqvmsbkx.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.xylfe.cn/Article/details/gtmjexuuod.html

JS:   "7".padStart(3, "0")
来源：http://dali.pengpengdd.cyou/Article/details/gtuwssqkrb.html

TS:   "7".padStart(3, "0")
来源：http://dali.shanyushiyangtech.top/Article/details/gtvnfeqwwq.html

Java: String.format("%03d", 7)
来源：http://dali.aibaodan.cn/Article/details/gtlljdgisf.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.xuanzx.com/Article/details/gtvgiqfubl.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.tanke756.top/Article/details/gtfnqsedyd.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jiagoushi.top/Article/details/gtosqsehas.html

[E11] 反转字符串
来源：http://dali.ydzc1.top/Article/details/gtoecdhuxn.html

Py:   s[::-1]
来源：http://dali.9152youxi.cn/Article/details/gtrvdoswqz.html

PHP:  strrev($s);
来源：http://dali.jinqigfzy.top/Article/details/gtuldrzxzl.html

JS:   [...s].reverse().join("")
来源：http://dali.jyoumei.cn/Article/details/gttxagxwaw.html

TS:   [...s].reverse().join("")
来源：http://dali.quarkkingdee.top/Article/details/gtjanlctuk.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jiagoushi.top/Article/details/gtebajxfol.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.fengsongda.top/Article/details/gtfrztbfom.html

Ruby: s.reverse
来源：http://dali.chenlongwang.top/Article/details/gthxzqlhbm.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.redwolf501.top/Article/details/gtepecpgia.html

[E12] 统计某字符出现次数
来源：http://dali.wangshuangyany.cn/Article/details/gtnavcprbx.html

Py:   s.count("a")
来源：http://dali.pengpengdd.cyou/Article/details/gthucienzy.html

PHP:  substr_count($s, "a");
来源：http://dali.tianlin.xyz/Article/details/gtptpyekka.html

JS:   s.split("a").length - 1
来源：http://dali.sxryk.cn/Article/details/gtiizcykga.html

TS:   s.split("a").length - 1
来源：http://dali.ybcxt.top/Article/details/gtaudxcklk.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.gaohongyu789.top/Article/details/gthzivsodc.html

Go:   strings.Count(s, "a")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzgwqbiyg.html

Ruby: s.count("a")
来源：http://dali.cdnleiting.top/Article/details/gtkbkbixro.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xylfe.cn/Article/details/gtvovyulou.html

[E13] 逐字符遍历
来源：http://dali.ivvv.top/Article/details/gtsfyxkwff.html

Py:   for ch in s: print(ch)
来源：http://dali.nanxinkj.top/Article/details/gtzgjlmwjn.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.c1oappe.top/Article/details/gtuylcyuak.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ivvv.top/Article/details/gthvclorke.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sysykeji.top/Article/details/gtyidxicsp.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.birdmap.top/Article/details/gtrvgzxlfx.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yongpay.top/Article/details/gtrweujlel.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.pengpengdd.cyou/Article/details/gtrkkhwwvd.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvuzldcsr.html

[E14] URL 编码与 Base64
来源：http://dali.shuidangran.top/Article/details/gtkotmpaxk.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yuxming.cn/Article/details/gtocugmzlg.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.ybcxt.top/Article/details/gtmouiszyx.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhijiandao.cn/Article/details/gtsbeffuji.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.sufxvd.cn/Article/details/gtfwbejfhs.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.nanxuanxn.top/Article/details/gttgqdubqa.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.9152youxi.cn/Article/details/gtnvnhevjn.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.andypj.xyz/Article/details/gtpewxpfqb.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.xinyue.icu/Article/details/gtziwwxavr.html

[E15] HTML 转义 / 反转义
来源：http://dali.nanxinkj.top/Article/details/gtobndbjkk.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yuxming.cn/Article/details/gtjqmvnqdy.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yj202588.top/Article/details/gtpzcrlezi.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yuxming.cn/Article/details/gtzjijfcsu.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.mhx1999.top/Article/details/gtfpvrburv.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yanxiufei.cn/Article/details/gtovnlnaqu.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.guowangkeji.top/Article/details/gtwmltuvaq.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yuxming.cn/Article/details/gtnfcfypwo.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvesyvylc.html

[E16] 数字千分位
来源：http://dali.hammf.cn/Article/details/gtcmkcfofp.html

Py:   f"{1234567:,}"
来源：http://dali.sweek.top/Article/details/gteqvfnhdu.html

PHP:  number_format(1234567);
来源：http://dali.jiagoushi.top/Article/details/gtxpbhuzkr.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.c1oappe.top/Article/details/gtotmnknqe.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.dashuyun.cn/Article/details/gtpbdtkzdv.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.nanxuanxn.top/Article/details/gtrbdjcger.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yj20258.top/Article/details/gtmfhbmnfp.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yanxiufei.cn/Article/details/gtbztqrqqr.html

C#:   1234567.ToString("N0")
来源：http://dali.tanke756.top/Article/details/gtsyiaqriv.html

[E17] 首字母大写
来源：http://dali.smart0.xyz/Article/details/gtwlppzwji.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgisqrjio.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yongpay.top/Article/details/gtegqwoywc.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hammf.cn/Article/details/gtbdthriye.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.316326.xyz/Article/details/gtkwugetot.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.guannengcc.top/Article/details/gtutujnpab.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrmvcrtmr.html

Ruby: s.capitalize
来源：http://dali.yj20258888.top/Article/details/gtxhwnayqe.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.meibo888.top/Article/details/gtrxzvaknv.html

[E18] 模板占位符替换
来源：http://dali.chenzaomai.com/Article/details/gtclrxahno.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.andypj.xyz/Article/details/gtslvkgvia.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.feifeiyinyue.top/Article/details/gtiugravqs.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.dashuyun.cn/Article/details/gtpqaiydlm.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jqgufenzy.top/Article/details/gtgwzynbty.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.cashguo.top/Article/details/gtuaytuabk.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.shuidangran.top/Article/details/gtuqliuvkg.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.cashguo.top/Article/details/gtmwuqmlvq.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gtwgqgcfsb.html

[E19] 多行文本按行拆分
来源：http://dali.yongpay.top/Article/details/gttmwgbgjj.html

Py:   s.splitlines()
来源：http://dali.hnxiangtu.top/Article/details/gtpiviedyo.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.xuetiantiany.cn/Article/details/gttkxekvuh.html

JS:   s.split(/\r?\n/)
来源：http://dali.jianghu66.top/Article/details/gtuqvjymxa.html

TS:   s.split(/\r?\n/)
来源：http://dali.cashguo.top/Article/details/gtfmrnxhci.html

Java: s.lines().toList()
来源：http://dali.ivvv.top/Article/details/gtifrogplw.html

Go:   strings.Split(s, "\n")
来源：http://dali.xylfe.cn/Article/details/gtomudjoul.html

Ruby: s.lines
来源：http://dali.jqgufenzy.top/Article/details/gtxnuqkybc.html

C#:   s.Split('\n')
来源：http://dali.birdmap.top/Article/details/gtrzilmdjj.html

[E20] 判断字符串是否为空
来源：http://dali.zycfv.cn/Article/details/gtwswyqkdf.html

Py:   if not s:
来源：http://dali.hywenlv.cn/Article/details/gtwieamdua.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.mhx1999.top/Article/details/gtuainpvqw.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.fzhhl.top/Article/details/gtqtnvpzsb.html

TS:   if (s === "") {}
来源：http://dali.tanke756.top/Article/details/gtiujhcdgo.html

Java: if (s.isEmpty()) {}
来源：http://dali.aizwys.cn/Article/details/gtoiagityv.html

Go:   if s == "" {}
来源：http://dali.andypj.xyz/Article/details/gtcdcswrej.html

Ruby: if s.empty?
来源：http://dali.cdnleiting.top/Article/details/gtaxqjfkoo.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.tianlin.xyz/Article/details/gtrtejkeeq.html

[E21] 超长截断加省略号
来源：http://dali.daria6918.cn/Article/details/gtvpzkwdzb.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.quarkkingdee.top/Article/details/gtdkchmqhw.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.c1oappe.top/Article/details/gtnflywait.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.316326.xyz/Article/details/gtslnozwwi.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhiwuduotai.top/Article/details/gtmjfrdidt.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.sufxvd.cn/Article/details/gtxhhtkdvc.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.meibo888.top/Article/details/gtdsfqfvxg.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yueranfly.top/Article/details/gtmmpuhaff.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yongpay.top/Article/details/gtvwsvheqg.html

[E22] 字节长度与字符长度
来源：http://dali.yangfankeji.com/Article/details/gtramgszuq.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yvedp.cn/Article/details/gtiwqfklfe.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.iojbl.cn/Article/details/gtocheidkj.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.0kj1m.cn/Article/details/gtzgcmyalg.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ehwqpu.com/Article/details/gtsnorulcp.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhengqikj.top/Article/details/gtwdwcucxe.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.9152youxi.cn/Article/details/gtedcbxfmt.html

Ruby: s.bytesize;  s.length
来源：http://dali.ybcxt.top/Article/details/gtvhzqfwgp.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.shzxlz.cn/Article/details/gtlpojledi.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtvyfsvizm.html

F. 文件与目录
来源：http://dali.yangfankeji.com/Article/details/gtcmloypry.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtltyrxfdy.html

[F01] 读取整个文件
来源：http://dali.hongshengwenyu.top/Article/details/gtzoivtwbl.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.tianlin.xyz/Article/details/gtlmlezvzi.html

PHP:  file_get_contents("a.txt");
来源：http://dali.tanke756.top/Article/details/gtbevwclkr.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gtekgcodqx.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.shuidangran.top/Article/details/gtgfaalzyn.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxgcnnmhe.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.ybcxt.top/Article/details/gtfeeifxoh.html

Ruby: File.read("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtehdkvarz.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gtrexttwrj.html

[F02] 逐行读取文件
来源：http://dali.xinyue.icu/Article/details/gtsguetwww.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xuetiantiany.cn/Article/details/gtbbovqcpm.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgjucruoe.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cdnleiting.top/Article/details/gtkwhmyhrq.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cdnleiting.top/Article/details/gttzvlxdgl.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.sufxvd.cn/Article/details/gtvfenezsa.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ehwqpu.com/Article/details/gtybsijxly.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hnxiangtu.top/Article/details/gttsehxzeo.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.sweek.top/Article/details/gtagilruae.html

[F03] 写入文件（覆盖）
来源：http://dali.gzhubu.top/Article/details/gtwagqrymt.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.nanxuanxn.top/Article/details/gtperjjpgq.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xuanzx.com/Article/details/gtqmcaxiuz.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shuidangran.top/Article/details/gtnxyrqras.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.bjfxy.top/Article/details/gtdhrcurhv.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.cucudq.cn/Article/details/gtdvifixss.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.ydzc1.top/Article/details/gtnmicrltg.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.aibaodan.cn/Article/details/gtymtfcmwe.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xylfe.cn/Article/details/gtwtammudj.html

[F04] 追加写入文件
来源：http://dali.cqqwz.cn/Article/details/gtnlyokllt.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.birdmap.top/Article/details/gtnecqvbpb.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.ivvv.top/Article/details/gtxqjxwieo.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmvniohvq.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfxvrmnnh.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.sxryk.cn/Article/details/gtbzdcxcea.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.sxryk.cn/Article/details/gtbivshaqv.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.cdnleiting.top/Article/details/gtsfoadnsq.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.gzhubu.top/Article/details/gtyjlssodi.html

[F05] 判断文件或目录是否存在
来源：http://dali.shzxlz.cn/Article/details/gtzbjqjutg.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.birdmap.top/Article/details/gtocjhtidv.html

PHP:  file_exists("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gtwbceblwp.html

JS:   fs.existsSync("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtsirefszl.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtenksskfk.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.svipenyu.cn/Article/details/gtwstpfyup.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.cucudq.cn/Article/details/gtzleecywn.html

Ruby: File.exist?("a.txt")
来源：http://dali.yonumen.top/Article/details/gtgjtamtrv.html

C#:   File.Exists("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtbzdifsbc.html

[F06] 删除文件
来源：http://dali.xuetiantiany.cn/Article/details/gtmzmmnegh.html

Py:   os.remove("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtvbvxkdfr.html

PHP:  unlink("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtowonhsiw.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtluvbzdhu.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtfneuplje.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zycfv.cn/Article/details/gtsascsllw.html

Go:   os.Remove("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtxiaqcwbh.html

Ruby: File.delete("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gthnepjoac.html

C#:   File.Delete("a.txt");
来源：http://dali.sweek.top/Article/details/gtfgpjrdaf.html

[F07] 创建目录（含多级）
来源：http://dali.ppjwa.cn/Article/details/gtugrfqzwz.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.smart0.xyz/Article/details/gtflutnvbl.html


<!-- 参考信息 -->