代发 wailian999

[D19] 按字段分组
来源：http://dali.sxryk.cn/Article/details/gtwznlrljv.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.guannengcc.top/Article/details/gtetcvnbop.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.xinyue.icu/Article/details/gtzdwvecux.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.tian-w.cn/Article/details/gtmuurskym.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.hammf.cn/Article/details/gtndrvehwf.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jianghu66.top/Article/details/gtrytgpcct.html

Go:   // 手写 map[string][]T
来源：http://dali.meibo888.top/Article/details/gtrplnsmau.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jianghu66.top/Article/details/gtssdoksbt.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.sysykeji.top/Article/details/gtbeualjzy.html

[D20] 统计每个元素出现次数
来源：http://dali.xuetiantiany.cn/Article/details/gtlewuepzm.html

Py:   Counter(arr)
来源：http://dali.smart0.xyz/Article/details/gtralchpwt.html

PHP:  array_count_values($arr);
来源：http://dali.yj20258.top/Article/details/gtpbfgsqyw.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.0kj1m.cn/Article/details/gtcaxklhsv.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ydzc1.top/Article/details/gtnmlzzgwq.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.tanke756.top/Article/details/gtbxpklnbl.html

Go:   // 手写 map[T]int
来源：http://dali.aizwys.cn/Article/details/gttsyutvls.html

Ruby: arr.tally
来源：http://dali.guowangkeji.top/Article/details/gtaoxsbapt.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.nanxuanxn.top/Article/details/gtebmiuvbi.html

[D21] 判断是否包含某元素
来源：http://dali.hysaishi.cn/Article/details/gtxcqqhjtp.html

Py:   x in arr
来源：http://dali.hnqzz.top/Article/details/gtapfmftdw.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yueranfly.top/Article/details/gtzvuqigdq.html

JS:   arr.includes(x)
来源：http://dali.0kj1m.cn/Article/details/gtwhqfoplg.html

TS:   arr.includes(x)
来源：http://dali.shzxlz.cn/Article/details/gtscklmkuo.html

Java: list.contains(x)
来源：http://dali.havefunace.top/Article/details/gtjfkxdcyj.html

Go:   slices.Contains(arr, x)
来源：http://dali.sysykeji.top/Article/details/gtlzredjbs.html

Ruby: arr.include?(x)
来源：http://dali.redwolf501.top/Article/details/gtkaqnbpha.html

C#:   list.Contains(x)
来源：http://dali.shzxlz.cn/Article/details/gtlviuieyx.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jqgufenzy.top/Article/details/gtpsuywwpj.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.sysykeji.top/Article/details/gteidjgfvo.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhoulong.xyz/Article/details/gtpjtsecdr.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.nanxinkj.top/Article/details/gtevhlckfh.html

TS:   [...arr];
来源：http://dali.havefunace.top/Article/details/gtqdvlbgnw.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gtjbqwanrw.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.birdmap.top/Article/details/gtoxrbvopr.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hnxiangtu.top/Article/details/gteriahunf.html

C#:   new List<int>(list);
来源：http://dali.svipenyu.cn/Article/details/gtlzznliio.html

[D23] reduce 累积计算
来源：http://dali.yuxming.cn/Article/details/gtwewrskwd.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.gotoacloud.top/Article/details/gtiutavgbu.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.fengsongda.top/Article/details/gtekxwtqcg.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sysykeji.top/Article/details/gtamhafyaq.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cheryme.top/Article/details/gtlpyucjps.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.gaohongyu789.top/Article/details/gtnozfqhrf.html

Go:   // 手写循环
来源：http://dali.andypj.xyz/Article/details/gtmicuwdjh.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jianghu66.top/Article/details/gtvxxlbihg.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkcylxedl.html

[D24] 字典 / Map 基本操作
来源：http://dali.sysykeji.top/Article/details/gtwjbuxsut.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.birdmap.top/Article/details/gtqsalwwbz.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.xuetiantiany.cn/Article/details/gtqxzrhwsz.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.pycfn.com/Article/details/gtvonvabbl.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.snrcjt.cn/Article/details/gtsuwuouas.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhongyouzk.top/Article/details/gtpsgrmfjj.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yueranfly.top/Article/details/gtbuqavmmb.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.316326.xyz/Article/details/gtilumsxad.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.gotoacloud.top/Article/details/gtekkyqurz.html

[D25] Set 集合去重与交并差
来源：http://dali.hfpthk.cn/Article/details/gtrqvdativ.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.fengsongda.top/Article/details/gtcuaeyfdc.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.quarkkingdee.top/Article/details/gtcmlidnkp.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.chenlongwang.top/Article/details/gtjxdttrzk.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.fzhhl.top/Article/details/gtqefxonys.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.kuanghao11.cn/Article/details/gtgxdubumm.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.havefunace.top/Article/details/gtewyqofpq.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.sxryk.cn/Article/details/gtxsupkasp.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jqgfzy.top/Article/details/gtpkbsoqsc.html

[D26] 数组转字符串
来源：http://dali.jyoumei.cn/Article/details/gtopsqrwfh.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yj20258888.top/Article/details/gtmcbwnzna.html

PHP:  implode(", ", $arr);
来源：http://dali.yangfankeji.com/Article/details/gtmcmwmaxp.html

JS:   arr.join(", ")
来源：http://dali.pycfn.com/Article/details/gtdmiseagp.html

TS:   arr.join(", ")
来源：http://dali.yuxming.cn/Article/details/gtsittqaqv.html

Java: String.join(", ", list)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpyigipcn.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yj20258888.top/Article/details/gttzcuykkj.html

Ruby: arr.join(", ")
来源：http://dali.zhoulong.xyz/Article/details/gtgwssuanq.html

C#:   string.Join(", ", list)
来源：http://dali.meibo888.top/Article/details/gttcaejcgz.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtcpjkksbo.html

E. 字符串处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvucdisic.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtawgooyon.html

[E01] 拼接字符串
来源：http://dali.andypj.xyz/Article/details/gtkwdumerh.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.pycfn.com/Article/details/gtdighvuxi.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.aizwys.cn/Article/details/gtgzlwnaef.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.daria6918.cn/Article/details/gtxaaqwemi.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.aibaodan.cn/Article/details/gtnvzxrmns.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.meibo888.top/Article/details/gtwghnolju.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.quarkkingdee.top/Article/details/gtodjhvfwg.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.mhx1999.top/Article/details/gtvwdsrvjy.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yonumen.top/Article/details/gtvybtewlj.html

[E02] 重复字符串
来源：http://dali.kuanghao11.cn/Article/details/gtnbqcqeah.html

Py:   "ab" * 3
来源：http://dali.ehwqpu.com/Article/details/gtwrivlxge.html

PHP:  str_repeat("ab", 3);
来源：http://dali.gogol.net.cn/Article/details/gtsfhotbqc.html

JS:   "ab".repeat(3)
来源：http://dali.guowangkeji.top/Article/details/gtvnjvfxzm.html

TS:   "ab".repeat(3)
来源：http://dali.hnqzz.top/Article/details/gtuerxcgkj.html

Java: "ab".repeat(3)
来源：http://dali.meibo888.top/Article/details/gttknqorou.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.ybcxt.top/Article/details/gtbfqpkxww.html

Ruby: "ab" * 3
来源：http://dali.gzhubu.top/Article/details/gtlljqpsuv.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.guannengcc.top/Article/details/gtazuqucov.html

[E03] 截取子串
来源：http://dali.sysykeji.top/Article/details/gtizybroby.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.cheryme.top/Article/details/gtzojbignt.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.mhx1999.top/Article/details/gtlqyeatte.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.cqqwz.cn/Article/details/gtahddnnwn.html

TS:   s.slice(1, 4)
来源：http://dali.cashguo.top/Article/details/gtgnrouwmt.html

Java: s.substring(1, 4)
来源：http://dali.shuidangran.top/Article/details/gtidrkywrz.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.wangdashe.top/Article/details/gtapgnidwj.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.dashuyun.cn/Article/details/gtzvkofacn.html

C#:   s.Substring(1, 3)
来源：http://dali.dashuyun.cn/Article/details/gtgdhwhamq.html

[E04] 查找子串位置
来源：http://dali.yuanzhike.top/Article/details/gtmxqwppsv.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yangfankeji.com/Article/details/gtyecangsc.html

PHP:  strpos($s, "x");
来源：http://dali.yanxiufei.cn/Article/details/gttrwxjpbl.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jinghuilouyu.cn/Article/details/gtitfqilko.html

TS:   s.indexOf("x")
来源：http://dali.daxiang520.top/Article/details/gtdgnghvxc.html

Java: s.indexOf("x")
来源：http://dali.daria6918.cn/Article/details/gtdzivjklw.html

Go:   strings.Index(s, "x")
来源：http://dali.meibo888.top/Article/details/gtvfjppkys.html

Ruby: s.index("x")
来源：http://dali.vqdsnc.cn/Article/details/gtxfdqjkyc.html

C#:   s.IndexOf("x")
来源：http://dali.gaohongyu789.top/Article/details/gtkbjizpll.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jqgfzy.top/Article/details/gtuwellxbf.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.iojbl.cn/Article/details/gtmuienqam.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.pycfn.com/Article/details/gtkyeuvkti.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.andypj.xyz/Article/details/gtefffjgpu.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gtsfkgbjlm.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gaohongyu789.top/Article/details/gtnmyemmco.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hywenlv.cn/Article/details/gtxardfhvs.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.sysykeji.top/Article/details/gtwlbewrlo.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.pengpengdd.cyou/Article/details/gtukddjdxd.html

[E06] 替换子串
来源：http://dali.haohaochexian.top/Article/details/gtaevezxnx.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.shangyingyoupin.top/Article/details/gtrcvvhiwc.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.hywenlv.cn/Article/details/gteuurzvmw.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.feifeiyinyue.top/Article/details/gtoihuvzby.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhaomingkeji.xyz/Article/details/gthxtedizc.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xziqi.cn/Article/details/gtckzfembe.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.tian-w.cn/Article/details/gttuelmwoc.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jqgufenzy.top/Article/details/gthoucwpna.html

C#:   s.Replace("a", "b")
来源：http://dali.bjfxy.top/Article/details/gtmflpbyew.html

[E07] 按分隔符拆分
来源：http://dali.haohaochexian.top/Article/details/gtypjgyomk.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.birdmap.top/Article/details/gtjidoszia.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.tanke756.top/Article/details/gtjyrauxrl.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yj202588.top/Article/details/gtiyxrekza.html

TS:   s.split(",")
来源：http://dali.yj20258.top/Article/details/gtzxnybexe.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.bjfxy.top/Article/details/gttjfkeasr.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.cucudq.cn/Article/details/gtxcjaxmuk.html

Ruby: s.split(",");  s.split
来源：http://dali.ybcxt.top/Article/details/gtfpmlaqoa.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhiwuduotai.top/Article/details/gtdiwjgogq.html

[E08] 数组按分隔符合并
来源：http://dali.daria6918.cn/Article/details/gtlxgbsjkx.html

Py:   ",".join(items)
来源：http://dali.nwbrower.top/Article/details/gtyxdrpiyh.html

PHP:  implode(",", $items);
来源：http://dali.sweek.top/Article/details/gtbiidxfka.html

JS:   items.join(",")
来源：http://dali.bjfxy.top/Article/details/gtovexdsig.html

TS:   items.join(",")
来源：http://dali.nanxinkj.top/Article/details/gtlyddzjun.html

Java: String.join(",", items)
来源：http://dali.yongpay.top/Article/details/gtoynaympg.html

Go:   strings.Join(items, ",")
来源：http://dali.yongpay.top/Article/details/gttqnprynw.html

Ruby: items.join(",")
来源：http://dali.shangyingyoupin.top/Article/details/gtgwdbtzjh.html

C#:   string.Join(",", items)
来源：http://dali.aibaodan.cn/Article/details/gtenupvyrv.html

[E09] 去除所有空白字符
来源：http://dali.vqdsnc.cn/Article/details/gtwrhthkzt.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.chenjidiqi.icu/Article/details/gtoiwjaxmb.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hnqzz.top/Article/details/gtcxzlnqzb.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkzxbzvai.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hnqzz.top/Article/details/gtucopgpwg.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtytwflncp.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.sweek.top/Article/details/gtfczowmnb.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yangfankeji.com/Article/details/gtsdbtyazu.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.gaohongyu789.top/Article/details/gtfurdtbyh.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yongpay.top/Article/details/gtjjkuvgqf.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.chenlongwang.top/Article/details/gtfviwxmfo.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.hongshengwenyu.top/Article/details/gtpckhgktl.html

JS:   "7".padStart(3, "0")
来源：http://dali.smart0.xyz/Article/details/gtqwninvdr.html

TS:   "7".padStart(3, "0")
来源：http://dali.sxryk.cn/Article/details/gtpdofkngn.html

Java: String.format("%03d", 7)
来源：http://dali.ybcxt.top/Article/details/gtebkmnutb.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yuanzhike.top/Article/details/gtkwhkoona.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.quarkkingdee.top/Article/details/gtokduzcso.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.cqqwz.cn/Article/details/gtrdgkgptv.html

[E11] 反转字符串
来源：http://dali.andypj.xyz/Article/details/gtsvxithvz.html

Py:   s[::-1]
来源：http://dali.jyoumei.cn/Article/details/gttrxkohpv.html

PHP:  strrev($s);
来源：http://dali.haohaochexian.top/Article/details/gtbfjpjugc.html

JS:   [...s].reverse().join("")
来源：http://dali.tanke756.top/Article/details/gtqnhgnjkf.html

TS:   [...s].reverse().join("")
来源：http://dali.haohaochexian.top/Article/details/gtynevkwkh.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yueranfly.top/Article/details/gtavtjdlbf.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.pycfn.com/Article/details/gtoerukvqp.html

Ruby: s.reverse
来源：http://dali.tian-w.cn/Article/details/gtfuqklief.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.meibo888.top/Article/details/gtdnvunsqt.html

[E12] 统计某字符出现次数
来源：http://dali.zhiwuduotai.top/Article/details/gtbpxiwhqj.html

Py:   s.count("a")
来源：http://dali.wangdashe.top/Article/details/gthjvwfxvh.html

PHP:  substr_count($s, "a");
来源：http://dali.ydzc1.top/Article/details/gtexeocjkd.html

JS:   s.split("a").length - 1
来源：http://dali.shuidangran.top/Article/details/gtbxrwzbaj.html

TS:   s.split("a").length - 1
来源：http://dali.cdnleiting.top/Article/details/gtkkoczjtj.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jqgufenzy.top/Article/details/gtztqzrmtv.html

Go:   strings.Count(s, "a")
来源：http://dali.gotoacloud.top/Article/details/gtctowqzup.html

Ruby: s.count("a")
来源：http://dali.jyoumei.cn/Article/details/gtqrxunyod.html

C#:   s.Count(c => c == 'a')
来源：http://dali.redwolf501.top/Article/details/gtpkjyuhqq.html

[E13] 逐字符遍历
来源：http://dali.guowangkeji.top/Article/details/gtzmldlsca.html

Py:   for ch in s: print(ch)
来源：http://dali.hongshengwenyu.top/Article/details/gtmkacjihu.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.aibaodan.cn/Article/details/gtdgnbxtxb.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sysykeji.top/Article/details/gtzcoovbqj.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.bjfxy.top/Article/details/gtuhkvguqs.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.wangdashe.top/Article/details/gtszwtemcw.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yuxming.cn/Article/details/gtwiaynrky.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.ppjwa.cn/Article/details/gtnmtigdtx.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.chenzaomai.com/Article/details/gttwuvlnys.html

[E14] URL 编码与 Base64
来源：http://dali.wangdashe.top/Article/details/gtzellansp.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.nanxinkj.top/Article/details/gtyslaadsw.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jqgfzy.top/Article/details/gtokqcrocf.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jiagoushi.top/Article/details/gtxjarhihw.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.gogol.net.cn/Article/details/gtjitkynxt.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yj20258.top/Article/details/gtqokymzfo.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.sufxvd.cn/Article/details/gtdhrkxbtu.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.quarkkingdee.top/Article/details/gtgvlopgxc.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.feifeiyinyue.top/Article/details/gtgqsmizpe.html

[E15] HTML 转义 / 反转义
来源：http://dali.yj202588.top/Article/details/gtujsvezaf.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.ehwqpu.com/Article/details/gtsxijusvn.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.chenjidiqi.icu/Article/details/gtyplaitdu.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jyoumei.cn/Article/details/gtaiijvtoq.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yj202588.top/Article/details/gtyclsbjyc.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zdqjudy.top/Article/details/gtynegists.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xylfe.cn/Article/details/gtcezvqxii.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.wangdashe.top/Article/details/gtpaqacqwn.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtjuywlxno.html

[E16] 数字千分位
来源：http://dali.aibaodan.cn/Article/details/gtqwoxiusg.html

Py:   f"{1234567:,}"
来源：http://dali.daxiang520.top/Article/details/gtdewxsnww.html

PHP:  number_format(1234567);
来源：http://dali.zhongyouzk.top/Article/details/gtjevkypke.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.c1oappe.top/Article/details/gtvrbiwxbg.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.fengsongda.top/Article/details/gtqpzvldun.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.meibo888.top/Article/details/gtpwovwtop.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.nanxuanxn.top/Article/details/gtkuielihb.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hnxiangtu.top/Article/details/gtghrqkijy.html

C#:   1234567.ToString("N0")
来源：http://dali.cdnleiting.top/Article/details/gthxsqodcc.html

[E17] 首字母大写
来源：http://dali.yj20258.top/Article/details/gtbtutgtla.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hammf.cn/Article/details/gtjxwrvccc.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgepcexot.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hfpthk.cn/Article/details/gtrhnkcvzo.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtchnomctz.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjulbfehx.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.svipenyu.cn/Article/details/gtirtdxpvv.html

Ruby: s.capitalize
来源：http://dali.cashguo.top/Article/details/gtmiewdknc.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yuanzhike.top/Article/details/gtdocwtwaj.html

[E18] 模板占位符替换
来源：http://dali.jqgfzy.top/Article/details/gtcyaxtojn.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.tanke756.top/Article/details/gtxwxsebyz.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yj20258888.top/Article/details/gtcyyvwmld.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.iojbl.cn/Article/details/gtfhtagdxy.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yj20258888.top/Article/details/gtmaolfzfg.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.cashguo.top/Article/details/gtzhcrjeeh.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.haohaochexian.top/Article/details/gtvyeqvojg.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.gotoacloud.top/Article/details/gtomugtmcr.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.sweek.top/Article/details/gtvebgqype.html

[E19] 多行文本按行拆分
来源：http://dali.c1oappe.top/Article/details/gtxqtzsbbz.html

Py:   s.splitlines()
来源：http://dali.ppjwa.cn/Article/details/gtsukcjjxb.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.cucudq.cn/Article/details/gtvtpapskm.html

JS:   s.split(/\r?\n/)
来源：http://dali.dashuyun.cn/Article/details/gtraocsgrl.html

TS:   s.split(/\r?\n/)
来源：http://dali.yanxiufei.cn/Article/details/gtmnljylqh.html

Java: s.lines().toList()
来源：http://dali.chenlongwang.top/Article/details/gtwvdzwybm.html

Go:   strings.Split(s, "\n")
来源：http://dali.smart0.xyz/Article/details/gtgulyzbvw.html

Ruby: s.lines
来源：http://dali.zdqjudy.top/Article/details/gtfutozaqf.html

C#:   s.Split('\n')
来源：http://dali.hnxiangtu.top/Article/details/gtsbdbgxrv.html

[E20] 判断字符串是否为空
来源：http://dali.jqgufenzy.top/Article/details/gtoemxkhce.html

Py:   if not s:
来源：http://dali.jqgfzy.top/Article/details/gtujeayxet.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtycwklxes.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hnxiangtu.top/Article/details/gtytzlswrd.html

TS:   if (s === "") {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbhuxtpeo.html

Java: if (s.isEmpty()) {}
来源：http://dali.daxiang520.top/Article/details/gtfdegdrjx.html

Go:   if s == "" {}
来源：http://dali.bjfxy.top/Article/details/gtykswparv.html

Ruby: if s.empty?
来源：http://dali.smart0.xyz/Article/details/gtxdhhcrcu.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jqgufenzy.top/Article/details/gtwcqocrif.html

[E21] 超长截断加省略号
来源：http://dali.zhoulong.xyz/Article/details/gtuzbhdqqc.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.wangshuangyany.cn/Article/details/gtfgnexmbn.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.ivvv.top/Article/details/gthrulzsxu.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hongshengwenyu.top/Article/details/gtotwejuqq.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jlsjyb.cn/Article/details/gtysqzrnsw.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ehwqpu.com/Article/details/gtsfmsojgi.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.pycfn.com/Article/details/gtfydcdyzv.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jqgufenzy.top/Article/details/gtjudytkzp.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yj20258888.top/Article/details/gtoeylamgn.html

[E22] 字节长度与字符长度
来源：http://dali.daxiang520.top/Article/details/gtxojuzfxq.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xylfe.cn/Article/details/gtesmmnkds.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hysaishi.cn/Article/details/gtzakrtuib.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hfpthk.cn/Article/details/gtnbfyottt.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shangyingyoupin.top/Article/details/gtlreyvebj.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.quarkkingdee.top/Article/details/gtdyxrnjft.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jinqigufen.top/Article/details/gtvqrumbol.html

Ruby: s.bytesize;  s.length
来源：http://dali.gogol.net.cn/Article/details/gtudgydrrn.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.c1oappe.top/Article/details/gttlyxlszi.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzqfehqji.html

F. 文件与目录
来源：http://dali.hongshengwenyu.top/Article/details/gtvijwcyzz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtzdbhbcwi.html

[F01] 读取整个文件
来源：http://dali.yonumen.top/Article/details/gtqtkhzmkk.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yonumen.top/Article/details/gtibeztqcd.html

PHP:  file_get_contents("a.txt");
来源：http://dali.ydzc1.top/Article/details/gtguvtwbxy.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hnqzz.top/Article/details/gtikvmggkb.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.316326.xyz/Article/details/gtefawhhlm.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.sufxvd.cn/Article/details/gtibeozefo.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.bjfxy.top/Article/details/gtwvrfgbdg.html

Ruby: File.read("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtavrgdcjp.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gtmaxgqmxt.html

[F02] 逐行读取文件
来源：http://dali.xuetiantiany.cn/Article/details/gtqzljppdr.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.mhx1999.top/Article/details/gtqbhiairg.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.pycfn.com/Article/details/gtvvgkptjd.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj20258.top/Article/details/gtglcgniem.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xylfe.cn/Article/details/gtkcpdrkfj.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.xylfe.cn/Article/details/gttmcpibzq.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.dianchejie.cn/Article/details/gtcivdzdoc.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.ybcxt.top/Article/details/gtvqxwfhvs.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jinqigufen.top/Article/details/gttlrzrzsn.html

[F03] 写入文件（覆盖）
来源：http://dali.meibo888.top/Article/details/gtqyxonchy.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.vqdsnc.cn/Article/details/gtfjhnvsns.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yuanzhike.top/Article/details/gtzabinhkx.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hongshengwenyu.top/Article/details/gtsfzepicd.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gthpzkshja.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jyoumei.cn/Article/details/gthmqpravv.html


<!-- 参考信息 -->