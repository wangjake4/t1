代发 wailian999

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.quarkkingdee.top/Article/details/gtakkgzzlu.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hysaishi.cn/Article/details/gtectdrcyy.html

Go:   // 手写 map[string][]T
来源：http://dali.fzhhl.top/Article/details/gtrmfqxzuv.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hnxiangtu.top/Article/details/gtfcrkknmf.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.gzhubu.top/Article/details/gtatlqvedf.html

[D20] 统计每个元素出现次数
来源：http://dali.xziqi.cn/Article/details/gtywrogrxe.html

Py:   Counter(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtcqywolnb.html

PHP:  array_count_values($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtpuxfqqju.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hywenlv.cn/Article/details/gtrpazdbfd.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ydzc1.top/Article/details/gtsrgbxyoo.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.haohaochexian.top/Article/details/gtzlirtppc.html

Go:   // 手写 map[T]int
来源：http://dali.dianchejie.cn/Article/details/gtccwgarqk.html

Ruby: arr.tally
来源：http://dali.yanxiufei.cn/Article/details/gtfpryhccw.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.hfpthk.cn/Article/details/gtkyffbemo.html

[D21] 判断是否包含某元素
来源：http://dali.aibaodan.cn/Article/details/gtywdumfqp.html

Py:   x in arr
来源：http://dali.yanxiufei.cn/Article/details/gtrguclboy.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhixingplan.top/Article/details/gtanwbgzwg.html

JS:   arr.includes(x)
来源：http://dali.guowangkeji.top/Article/details/gtmljuujzp.html

TS:   arr.includes(x)
来源：http://dali.sxryk.cn/Article/details/gtxizrlbye.html

Java: list.contains(x)
来源：http://dali.zdqjudy.top/Article/details/gtiqnkcukn.html

Go:   slices.Contains(arr, x)
来源：http://dali.dianchejie.cn/Article/details/gtuoasndac.html

Ruby: arr.include?(x)
来源：http://dali.hnqzz.top/Article/details/gtspqqqsdc.html

C#:   list.Contains(x)
来源：http://dali.haohaochexian.top/Article/details/gtxwfmhdng.html

[D22] 复制数组（避免共享引用）
来源：http://dali.mhx1999.top/Article/details/gtoiofntso.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.daria6918.cn/Article/details/gtiuepughm.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.wangdashe.top/Article/details/gthpsnfnfn.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.sufxvd.cn/Article/details/gtcktjoyjc.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gtpryepzkp.html

Java: new ArrayList<>(list);
来源：http://dali.yueranfly.top/Article/details/gtictgtnyp.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.chenlongwang.top/Article/details/gtuzkgjfbg.html

Ruby: arr.dup;  arr.clone
来源：http://dali.ydzc1.top/Article/details/gtgtmsbxaf.html

C#:   new List<int>(list);
来源：http://dali.xuetiantiany.cn/Article/details/gtkekcpktw.html

[D23] reduce 累积计算
来源：http://dali.zhaomingkeji.xyz/Article/details/gtryibpdbv.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.sweek.top/Article/details/gtbqnnujgq.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.guannengcc.top/Article/details/gtaxbdscyu.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhengqikj.top/Article/details/gtgfxpixtb.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.chenzaomai.com/Article/details/gtxjpdhmje.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.nanxinkj.top/Article/details/gtwpfwigxt.html

Go:   // 手写循环
来源：http://dali.haohaochexian.top/Article/details/gtiipcqybc.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.fengsongda.top/Article/details/gtzlmjcjjz.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.chenzaomai.com/Article/details/gtcrnacdqp.html

[D24] 字典 / Map 基本操作
来源：http://dali.havefunace.top/Article/details/gtonecjwml.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.sufxvd.cn/Article/details/gtckdkdowy.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.xylfe.cn/Article/details/gtqnomhdhz.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yj20258.top/Article/details/gtntvjvwqb.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.9152youxi.cn/Article/details/gthbfapyih.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.snrcjt.cn/Article/details/gtlckpexja.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.sweek.top/Article/details/gtmibkuvvj.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.daxiang520.top/Article/details/gtlktdkrqj.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.shanyushiyangtech.top/Article/details/gtvlcrcnmz.html

[D25] Set 集合去重与交并差
来源：http://dali.cucudq.cn/Article/details/gtuicoerlt.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.nwbrower.top/Article/details/gtxgetjnfa.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yonumen.top/Article/details/gttdikivwy.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.meibo888.top/Article/details/gtmdlnulcb.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.mhx1999.top/Article/details/gtcobgwnrf.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.0kj1m.cn/Article/details/gthrxcggwj.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.gaohongyu789.top/Article/details/gtdixyhwlf.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.chenlongwang.top/Article/details/gtdotudofx.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yuanzhike.top/Article/details/gtbqeqlnwp.html

[D26] 数组转字符串
来源：http://dali.snrcjt.cn/Article/details/gtuovwvmjl.html

Py:   ", ".join(map(str, arr))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpcvltscy.html

PHP:  implode(", ", $arr);
来源：http://dali.yueranfly.top/Article/details/gtxwltzntr.html

JS:   arr.join(", ")
来源：http://dali.yangfankeji.com/Article/details/gtjegdmock.html

TS:   arr.join(", ")
来源：http://dali.guowangkeji.top/Article/details/gtwzwwnmgw.html

Java: String.join(", ", list)
来源：http://dali.aibaodan.cn/Article/details/gtuxgbqprx.html

Go:   strings.Join(strs, ", ")
来源：http://dali.aizwys.cn/Article/details/gtrxijanzl.html

Ruby: arr.join(", ")
来源：http://dali.andypj.xyz/Article/details/gtlgmlebcv.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gtzihhzptv.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtyiqeolew.html

E. 字符串处理
来源：http://dali.cucudq.cn/Article/details/gtwumkclgy.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtsgrogbev.html

[E01] 拼接字符串
来源：http://dali.aibaodan.cn/Article/details/gtulmlxhlp.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.chenjidiqi.icu/Article/details/gtfiawnwve.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zycfv.cn/Article/details/gtgoxwuoet.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hywenlv.cn/Article/details/gtiouavlsa.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.9152youxi.cn/Article/details/gtxfihdjpv.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmtcuzopc.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.wangdashe.top/Article/details/gtfkztxolp.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.daria6918.cn/Article/details/gtoauwgixo.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.gaohongyu789.top/Article/details/gtaabusahx.html

[E02] 重复字符串
来源：http://dali.zhongyouzk.top/Article/details/gtosgmngxs.html

Py:   "ab" * 3
来源：http://dali.jinqigfzy.top/Article/details/gtflmlcpmn.html

PHP:  str_repeat("ab", 3);
来源：http://dali.feifeiyinyue.top/Article/details/gttxgsagtj.html

JS:   "ab".repeat(3)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdvbfxprl.html

TS:   "ab".repeat(3)
来源：http://dali.fzhhl.top/Article/details/gtrhkhteqg.html

Java: "ab".repeat(3)
来源：http://dali.gogol.net.cn/Article/details/gtubagcpue.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zycfv.cn/Article/details/gtieqilusr.html

Ruby: "ab" * 3
来源：http://dali.bjfxy.top/Article/details/gtpupicrhm.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.quarkkingdee.top/Article/details/gtxmugvejb.html

[E03] 截取子串
来源：http://dali.xylfe.cn/Article/details/gtqtwfafbg.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yanxiufei.cn/Article/details/gtogbylqtq.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.hfpthk.cn/Article/details/gtgrzwucrc.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.meibo888.top/Article/details/gtxuzzorsi.html

TS:   s.slice(1, 4)
来源：http://dali.yj20258.top/Article/details/gtiokoxrwn.html

Java: s.substring(1, 4)
来源：http://dali.yj20258888.top/Article/details/gtuaoskuix.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.guannengcc.top/Article/details/gtrjsjtxkb.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jinyuanbaomall.cn/Article/details/gthjokpvep.html

C#:   s.Substring(1, 3)
来源：http://dali.yuanzhike.top/Article/details/gtdhnbkmor.html

[E04] 查找子串位置
来源：http://dali.cashguo.top/Article/details/gtqfmsxkig.html

Py:   s.find("x");  s.index("x")
来源：http://dali.sufxvd.cn/Article/details/gtsfmrqniz.html

PHP:  strpos($s, "x");
来源：http://dali.andypj.xyz/Article/details/gtpsbqoine.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zdqjudy.top/Article/details/gtsmizjxcd.html

TS:   s.indexOf("x")
来源：http://dali.yanxiufei.cn/Article/details/gtxwdaxmsk.html

Java: s.indexOf("x")
来源：http://dali.gotoacloud.top/Article/details/gtiyvrpizl.html

Go:   strings.Index(s, "x")
来源：http://dali.xuanzx.com/Article/details/gtujmxqjpi.html

Ruby: s.index("x")
来源：http://dali.jlsjyb.cn/Article/details/gtwdaovgsr.html

C#:   s.IndexOf("x")
来源：http://dali.ivvv.top/Article/details/gtdflkzcdd.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.gaohongyu789.top/Article/details/gttrqocizu.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.xziqi.cn/Article/details/gtfnpazrtr.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.mhx1999.top/Article/details/gtytvbpyga.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhixingplan.top/Article/details/gtkhmusawi.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.guowangkeji.top/Article/details/gturfccgqg.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.aibaodan.cn/Article/details/gtzrnalcyz.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.shuidangran.top/Article/details/gtqldewbgz.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.wangshuangyany.cn/Article/details/gtnhprjlko.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.chenzaomai.com/Article/details/gtfsxdjnyw.html

[E06] 替换子串
来源：http://dali.pycfn.com/Article/details/gtsepnxtav.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.xziqi.cn/Article/details/gtxpktvsnm.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhengqikj.top/Article/details/gtvralfowl.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gaohongyu789.top/Article/details/gtngjzxdsr.html

TS:   s.replaceAll("a", "b")
来源：http://dali.daxiang520.top/Article/details/gtwmysjsuq.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.redwolf501.top/Article/details/gtlvylfbld.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yonumen.top/Article/details/gtdtkqzeze.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkesfhwdi.html

C#:   s.Replace("a", "b")
来源：http://dali.wangdashe.top/Article/details/gtejlfbqgb.html

[E07] 按分隔符拆分
来源：http://dali.xylfe.cn/Article/details/gtdivgznyp.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.fzhhl.top/Article/details/gtbewycbsg.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jqgufenzy.top/Article/details/gtdpttdpwq.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtruvezxjh.html

TS:   s.split(",")
来源：http://dali.ydzc1.top/Article/details/gtsfeiswpn.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.0kj1m.cn/Article/details/gtznnrvmho.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtffpfmbbz.html

Ruby: s.split(",");  s.split
来源：http://dali.yuanzhike.top/Article/details/gthbrzvnec.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jqgfzy.top/Article/details/gthrmwctqw.html

[E08] 数组按分隔符合并
来源：http://dali.c1oappe.top/Article/details/gtspkoembh.html

Py:   ",".join(items)
来源：http://dali.sxryk.cn/Article/details/gtxtltrnxt.html

PHP:  implode(",", $items);
来源：http://dali.yvedp.cn/Article/details/gtrxxwqhlq.html

JS:   items.join(",")
来源：http://dali.cdnleiting.top/Article/details/gthvzkdmrw.html

TS:   items.join(",")
来源：http://dali.cheryme.top/Article/details/gtkzxqdlfu.html

Java: String.join(",", items)
来源：http://dali.ivvv.top/Article/details/gtbugdqvae.html

Go:   strings.Join(items, ",")
来源：http://dali.sweek.top/Article/details/gtpceosnif.html

Ruby: items.join(",")
来源：http://dali.gogol.net.cn/Article/details/gtsouprtxh.html

C#:   string.Join(",", items)
来源：http://dali.yvedp.cn/Article/details/gtvuzxrvwx.html

[E09] 去除所有空白字符
来源：http://dali.sysykeji.top/Article/details/gtilurluai.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.kuanghao11.cn/Article/details/gtcbylfmcf.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtcsyrxyad.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yj20258888.top/Article/details/gttriawkbj.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.sxryk.cn/Article/details/gtnvyvnknw.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.shzxlz.cn/Article/details/gtaizfczgc.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.0kj1m.cn/Article/details/gtetujlbqt.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.cashguo.top/Article/details/gttdaggttm.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.snrcjt.cn/Article/details/gtknhtbnpe.html

[E10] 左侧补零 / 定长填充
来源：http://dali.wangdashe.top/Article/details/gtpurlcodx.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.shanyushiyangtech.top/Article/details/gtmbgerrrm.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.wangdashe.top/Article/details/gtqxpyzfdz.html

JS:   "7".padStart(3, "0")
来源：http://dali.xuanzx.com/Article/details/gtkeepxepo.html

TS:   "7".padStart(3, "0")
来源：http://dali.xuanzx.com/Article/details/gtexcdszxl.html

Java: String.format("%03d", 7)
来源：http://dali.jinghuilouyu.cn/Article/details/gtksqjzdbn.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yongpay.top/Article/details/gtusrecmig.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.ivvv.top/Article/details/gtbkrclfdf.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.hnqzz.top/Article/details/gtjxbexqgz.html

[E11] 反转字符串
来源：http://dali.aibaodan.cn/Article/details/gtxmhrqbcp.html

Py:   s[::-1]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsdcxjtjc.html

PHP:  strrev($s);
来源：http://dali.ivvv.top/Article/details/gthodyyhft.html

JS:   [...s].reverse().join("")
来源：http://dali.nanxinkj.top/Article/details/gtsnfayxgd.html

TS:   [...s].reverse().join("")
来源：http://dali.haohaochexian.top/Article/details/gtczyinteb.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jinqigfzy.top/Article/details/gtqepyiten.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yj20258888.top/Article/details/gtbpyqwjhf.html

Ruby: s.reverse
来源：http://dali.yuxming.cn/Article/details/gtxfbmuikr.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.gzhubu.top/Article/details/gthdztdnfb.html

[E12] 统计某字符出现次数
来源：http://dali.yueranfly.top/Article/details/gtegfguodg.html

Py:   s.count("a")
来源：http://dali.ppjwa.cn/Article/details/gtdgomdkdn.html

PHP:  substr_count($s, "a");
来源：http://dali.wangshuangyany.cn/Article/details/gtbdgcxlds.html

JS:   s.split("a").length - 1
来源：http://dali.jyoumei.cn/Article/details/gtoxkotrxf.html

TS:   s.split("a").length - 1
来源：http://dali.dashuyun.cn/Article/details/gtkzmdvykf.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yongpay.top/Article/details/gtqvpixait.html

Go:   strings.Count(s, "a")
来源：http://dali.ppjwa.cn/Article/details/gtzqwjbnat.html

Ruby: s.count("a")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrkyiybsw.html

C#:   s.Count(c => c == 'a')
来源：http://dali.svipenyu.cn/Article/details/gtlohuxarj.html

[E13] 逐字符遍历
来源：http://dali.daria6918.cn/Article/details/gtdjqtufmu.html

Py:   for ch in s: print(ch)
来源：http://dali.xuanzx.com/Article/details/gtbkjdhrrz.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.pycfn.com/Article/details/gtrdjjxpfb.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgamccprp.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tianlin.xyz/Article/details/gttrrzsewc.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.fengsongda.top/Article/details/gtrayfvrmx.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zycfv.cn/Article/details/gtqfupljui.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yuxming.cn/Article/details/gtxjekfzqu.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.pycfn.com/Article/details/gtxlioyydg.html

[E14] URL 编码与 Base64
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqsqhgpxn.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.ydzc1.top/Article/details/gtvejacfiw.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yj20258.top/Article/details/gtwxbwlksp.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.feifeiyinyue.top/Article/details/gtbagxuwqv.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.svipenyu.cn/Article/details/gtlnjvcjxy.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhongyouzk.top/Article/details/gtbigygpss.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.wangshuangyany.cn/Article/details/gtdppnlpyl.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hywenlv.cn/Article/details/gtleyayyug.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.smart0.xyz/Article/details/gtqczbgldp.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhiwuduotai.top/Article/details/gtnzmohutw.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfmkxabsi.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.svipenyu.cn/Article/details/gtzyqvmrhw.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhixingplan.top/Article/details/gtkqztgnum.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.chenlongwang.top/Article/details/gtrsyeujak.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.9152youxi.cn/Article/details/gtojwnuzid.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yj202588.top/Article/details/gtrvseykmf.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.aibaodan.cn/Article/details/gthhfcvwvy.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.bjfxy.top/Article/details/gtvmncvzii.html

[E16] 数字千分位
来源：http://dali.zhoulong.xyz/Article/details/gtguozvfsg.html

Py:   f"{1234567:,}"
来源：http://dali.chenjidiqi.icu/Article/details/gtnlyzlmal.html

PHP:  number_format(1234567);
来源：http://dali.shangyingyoupin.top/Article/details/gtehyrwnfc.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.quarkkingdee.top/Article/details/gtklmhxqyj.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmvkngptn.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hfpthk.cn/Article/details/gtpvaqhslq.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hysaishi.cn/Article/details/gtxnjawimz.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.tianlin.xyz/Article/details/gtidwpwboc.html

C#:   1234567.ToString("N0")
来源：http://dali.jqgfzy.top/Article/details/gtzaaiqxqq.html

[E17] 首字母大写
来源：http://dali.kuanghao11.cn/Article/details/gthoqocyfl.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zdqjudy.top/Article/details/gtnnpybhqz.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.gzhubu.top/Article/details/gtgqduilsn.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shzxlz.cn/Article/details/gtsvljvsto.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnnabzcid.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yj20258.top/Article/details/gtqdcdpsgp.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.fengsongda.top/Article/details/gtempeksdu.html

Ruby: s.capitalize
来源：http://dali.yonumen.top/Article/details/gtsobjfkco.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yj202588.top/Article/details/gtufseqwhr.html

[E18] 模板占位符替换
来源：http://dali.ivvv.top/Article/details/gtrzhykiri.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.tian-w.cn/Article/details/gtefbiatdb.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.0kj1m.cn/Article/details/gtykezgajq.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.ivvv.top/Article/details/gtykycqkhe.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.xuanzx.com/Article/details/gthcgrikbs.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.fengsongda.top/Article/details/gtqcaxbhxc.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yongpay.top/Article/details/gtvnjgmacu.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jqgfzy.top/Article/details/gtxvcbqwgl.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zdqjudy.top/Article/details/gttlbtoiqr.html

[E19] 多行文本按行拆分
来源：http://dali.quarkkingdee.top/Article/details/gtwtdvbnmw.html

Py:   s.splitlines()
来源：http://dali.xuanzx.com/Article/details/gtinlyvpqe.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gtmnycnnfg.html

JS:   s.split(/\r?\n/)
来源：http://dali.birdmap.top/Article/details/gtfruerzjq.html

TS:   s.split(/\r?\n/)
来源：http://dali.yvedp.cn/Article/details/gtbdcodoon.html

Java: s.lines().toList()
来源：http://dali.yj20258.top/Article/details/gtmrmkutye.html

Go:   strings.Split(s, "\n")
来源：http://dali.jqgufenzy.top/Article/details/gtgzicpnzo.html

Ruby: s.lines
来源：http://dali.svipenyu.cn/Article/details/gtgmfgshgi.html

C#:   s.Split('\n')
来源：http://dali.hnxiangtu.top/Article/details/gtgepkcvhh.html

[E20] 判断字符串是否为空
来源：http://dali.tanke756.top/Article/details/gtrihvvvrn.html

Py:   if not s:
来源：http://dali.hongshengwenyu.top/Article/details/gtonfseapb.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.guowangkeji.top/Article/details/gtrdnogajr.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.nwbrower.top/Article/details/gthpevqrmb.html

TS:   if (s === "") {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtnqqxgzef.html

Java: if (s.isEmpty()) {}
来源：http://dali.xylfe.cn/Article/details/gtwxfalfou.html

Go:   if s == "" {}
来源：http://dali.tian-w.cn/Article/details/gtkpgfrjfz.html

Ruby: if s.empty?
来源：http://dali.nanxuanxn.top/Article/details/gteapqoqnj.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.ydzc1.top/Article/details/gtowhgoohh.html

[E21] 超长截断加省略号
来源：http://dali.smart0.xyz/Article/details/gtjnmerxiz.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yuanzhike.top/Article/details/gtktuvhrnn.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.xuetiantiany.cn/Article/details/gtaqlykive.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.daria6918.cn/Article/details/gtimqirlxs.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.aibaodan.cn/Article/details/gtgtqkqeml.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.shzxlz.cn/Article/details/gtndhlzjpf.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zycfv.cn/Article/details/gtwtuyudgz.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xuetiantiany.cn/Article/details/gtuflzwwdt.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hnxiangtu.top/Article/details/gtntesjkjl.html

[E22] 字节长度与字符长度
来源：http://dali.ivvv.top/Article/details/gthmixpmpi.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.dashuyun.cn/Article/details/gtlslflats.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yj202588.top/Article/details/gtdtytwkxz.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.quarkkingdee.top/Article/details/gtribjwyov.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xziqi.cn/Article/details/gtvjthqatn.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.shzxlz.cn/Article/details/gtmfxidbzy.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jinqigufen.top/Article/details/gtpzrxcrym.html

Ruby: s.bytesize;  s.length
来源：http://dali.sxryk.cn/Article/details/gtlrzhmkha.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.iojbl.cn/Article/details/gtsghwesdj.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gterptgjnd.html

F. 文件与目录
来源：http://dali.andypj.xyz/Article/details/gtxqfekkjf.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtrnmzsvqm.html

[F01] 读取整个文件
来源：http://dali.guannengcc.top/Article/details/gtymqfajge.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.dashuyun.cn/Article/details/gtbdisvzzf.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xylfe.cn/Article/details/gthomcsuhn.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.tian-w.cn/Article/details/gtfefwpfrl.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yj20258.top/Article/details/gtklbyytxs.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.nanxinkj.top/Article/details/gtmuqxqkwr.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.aizwys.cn/Article/details/gtmfxpqugs.html

Ruby: File.read("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtloipxvle.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gtaxaazmru.html

[F02] 逐行读取文件
来源：http://dali.smart0.xyz/Article/details/gtsjmbdxcm.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.nwbrower.top/Article/details/gttepnmbzo.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.pycfn.com/Article/details/gtwjodxhle.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.dashuyun.cn/Article/details/gtpuuqpagh.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.pycfn.com/Article/details/gtpknblihl.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.cheryme.top/Article/details/gtlryjkjjf.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yj20258.top/Article/details/gtbpedsdta.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.daxiang520.top/Article/details/gtkckxehmx.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.ehwqpu.com/Article/details/gtuvnabbuw.html

[F03] 写入文件（覆盖）
来源：http://dali.snrcjt.cn/Article/details/gtklvxbbkc.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.cashguo.top/Article/details/gtqgqgtbos.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.tanke756.top/Article/details/gtbqisexwq.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.haohaochexian.top/Article/details/gtvimhqfex.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj20258888.top/Article/details/gtugleknhv.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jyoumei.cn/Article/details/gtwbritmol.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.vqdsnc.cn/Article/details/gtvnkvjptc.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ehwqpu.com/Article/details/gtrjewwwup.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhiwuduotai.top/Article/details/gtgcpygmdo.html

[F04] 追加写入文件
来源：http://dali.pengpengdd.cyou/Article/details/gtotvyvfyy.html


<!-- 参考信息 -->