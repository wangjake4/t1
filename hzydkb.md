代发 wailian999

C#:   list.Distinct().ToList()
来源：http://dali.xuetiantiany.cn/Article/details/gtpbxdzjtt.html

[D16] 求和与平均值
来源：http://dali.bjfxy.top/Article/details/gtkxsrfvow.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jyoumei.cn/Article/details/gtpwxchfmb.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.gotoacloud.top/Article/details/gtaofrpbki.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.9152youxi.cn/Article/details/gtrvimakjl.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yj20258.top/Article/details/gtzawpblnd.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.cqqwz.cn/Article/details/gtgmccyxnk.html

Go:   // 手写循环累加
来源：http://dali.chenlongwang.top/Article/details/gtcupixubs.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zycfv.cn/Article/details/gtyefumvcw.html

C#:   list.Sum();  list.Average()
来源：http://dali.yj20258888.top/Article/details/gtcydtkccx.html

[D17] 最大值与最小值
来源：http://dali.ybcxt.top/Article/details/gthfxkgrcx.html

Py:   max(arr);  min(arr)
来源：http://dali.jinqigufen.top/Article/details/gtvbjrwppk.html

PHP:  max($arr);  min($arr);
来源：http://dali.zycfv.cn/Article/details/gthodrwkma.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.sweek.top/Article/details/gtoctwyymx.html

TS:   Math.max(...arr);
来源：http://dali.sweek.top/Article/details/gteojaqpha.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.shanyushiyangtech.top/Article/details/gtxfnbhlvb.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.iojbl.cn/Article/details/gtwaiprrzr.html

Ruby: arr.max;  arr.min
来源：http://dali.yj20258.top/Article/details/gttwanxxol.html

C#:   list.Max();  list.Min()
来源：http://dali.xziqi.cn/Article/details/gtwfipbnnk.html

[D18] 扁平化嵌套数组
来源：http://dali.jinyuanbaomall.cn/Article/details/gtznacaxkj.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.aizwys.cn/Article/details/gtcwldqjjc.html

PHP:  array_merge(...$nested);
来源：http://dali.cdnleiting.top/Article/details/gtqvmrqczp.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jlsjyb.cn/Article/details/gtgkevuwcc.html

TS:   nested.flat();
来源：http://dali.bjfxy.top/Article/details/gtbjrxkipp.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yj20258.top/Article/details/gtnrixogbv.html

Go:   // 手写双层循环
来源：http://dali.gzhubu.top/Article/details/gtwnrgkcep.html

Ruby: nested.flatten
来源：http://dali.hywenlv.cn/Article/details/gtashmfwbz.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyqeluugc.html

[D19] 按字段分组
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdujbqhqt.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yanxiufei.cn/Article/details/gtggalqyln.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhiwuduotai.top/Article/details/gtirpqkshp.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhongyouzk.top/Article/details/gtredzvrih.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.xuetiantiany.cn/Article/details/gtkmlzeyyx.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.shangyingyoupin.top/Article/details/gtbtdgudbp.html

Go:   // 手写 map[string][]T
来源：http://dali.meibo888.top/Article/details/gtkgrdbdzm.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.chenzaomai.com/Article/details/gtewgraeob.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.snrcjt.cn/Article/details/gtdgnpweae.html

[D20] 统计每个元素出现次数
来源：http://dali.zycfv.cn/Article/details/gtuyjelxwz.html

Py:   Counter(arr)
来源：http://dali.tianlin.xyz/Article/details/gtcombhfbx.html

PHP:  array_count_values($arr);
来源：http://dali.birdmap.top/Article/details/gtcbddmdxy.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.daxiang520.top/Article/details/gtbzjemlnp.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cashguo.top/Article/details/gtldekabdo.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.cqqwz.cn/Article/details/gtvjczsxew.html

Go:   // 手写 map[T]int
来源：http://dali.smart0.xyz/Article/details/gtbypatbvy.html

Ruby: arr.tally
来源：http://dali.nanxuanxn.top/Article/details/gtesxruach.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.sxryk.cn/Article/details/gtxphcchwr.html

[D21] 判断是否包含某元素
来源：http://dali.wangdashe.top/Article/details/gtkienizer.html

Py:   x in arr
来源：http://dali.jinghuilouyu.cn/Article/details/gtzllcllae.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yangfankeji.com/Article/details/gtujpnmqeb.html

JS:   arr.includes(x)
来源：http://dali.gzhubu.top/Article/details/gtfibfjnuu.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gtqfhwjawc.html

Java: list.contains(x)
来源：http://dali.gaohongyu789.top/Article/details/gtihfmzppc.html

Go:   slices.Contains(arr, x)
来源：http://dali.ppjwa.cn/Article/details/gtbgiqnndc.html

Ruby: arr.include?(x)
来源：http://dali.hnxiangtu.top/Article/details/gtolrphqdk.html

C#:   list.Contains(x)
来源：http://dali.sweek.top/Article/details/gtlsjyovhg.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yvedp.cn/Article/details/gtxsicuccg.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtrbukhwwc.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.xziqi.cn/Article/details/gtcqzbzcmf.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.fengsongda.top/Article/details/gtobujrvph.html

TS:   [...arr];
来源：http://dali.redwolf501.top/Article/details/gtliprbshq.html

Java: new ArrayList<>(list);
来源：http://dali.birdmap.top/Article/details/gtwlqgidtg.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhengqikj.top/Article/details/gtlrkfosxo.html

Ruby: arr.dup;  arr.clone
来源：http://dali.wangdashe.top/Article/details/gtplpeajjc.html

C#:   new List<int>(list);
来源：http://dali.shzxlz.cn/Article/details/gtftsywnol.html

[D23] reduce 累积计算
来源：http://dali.xziqi.cn/Article/details/gtpzvqwkip.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.bjfxy.top/Article/details/gtwswfkkmj.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yj20258.top/Article/details/gtlsbxyhfh.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.0kj1m.cn/Article/details/gtdirpinmd.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.bjfxy.top/Article/details/gtgiasceum.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.fzhhl.top/Article/details/gtdhstspjx.html

Go:   // 手写循环
来源：http://dali.wangshuangyany.cn/Article/details/gtxqpeclef.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yuanzhike.top/Article/details/gtruflpxgh.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yongpay.top/Article/details/gtqxpcbvmw.html

[D24] 字典 / Map 基本操作
来源：http://dali.shangyingyoupin.top/Article/details/gtevyyzcso.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.kuanghao11.cn/Article/details/gtngnhwqmc.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zdqjudy.top/Article/details/gtruxgskcf.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.aizwys.cn/Article/details/gtatfcscdr.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.vqdsnc.cn/Article/details/gtpoychotq.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yj20258888.top/Article/details/gtyxppvcco.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yanxiufei.cn/Article/details/gtsklwdppo.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yueranfly.top/Article/details/gtrwsbvyjm.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.aizwys.cn/Article/details/gtnlhoxepw.html

[D25] Set 集合去重与交并差
来源：http://dali.yvedp.cn/Article/details/gtmxtarbmo.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.ppjwa.cn/Article/details/gtavnrbpky.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.fzhhl.top/Article/details/gtrmcxbtsh.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.kuanghao11.cn/Article/details/gtzvclyqjj.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.ybcxt.top/Article/details/gtzbzvudpf.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhongyouzk.top/Article/details/gtpzdgukdt.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.ydzc1.top/Article/details/gtoljpywcd.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.nanxinkj.top/Article/details/gtckrnlgeq.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.daxiang520.top/Article/details/gtxfgkdhof.html

[D26] 数组转字符串
来源：http://dali.chenzaomai.com/Article/details/gtyojddcuf.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yvedp.cn/Article/details/gtwxdsdhwx.html

PHP:  implode(", ", $arr);
来源：http://dali.dianchejie.cn/Article/details/gthznobgyo.html

JS:   arr.join(", ")
来源：http://dali.fzhhl.top/Article/details/gtvmlgsbap.html

TS:   arr.join(", ")
来源：http://dali.mhx1999.top/Article/details/gtwykgfjxj.html

Java: String.join(", ", list)
来源：http://dali.cdnleiting.top/Article/details/gtpxcqhoqf.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yonumen.top/Article/details/gtzhauadqf.html

Ruby: arr.join(", ")
来源：http://dali.yvedp.cn/Article/details/gtplbixqfp.html

C#:   string.Join(", ", list)
来源：http://dali.shzxlz.cn/Article/details/gtfmeauaij.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtffwtgowd.html

E. 字符串处理
来源：http://dali.aizwys.cn/Article/details/gtcgwpjqxa.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gthozzsqgj.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gtqryaogkk.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.sweek.top/Article/details/gtsvgpxsmq.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jinqigfzy.top/Article/details/gtcfbsnkoa.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gaohongyu789.top/Article/details/gtgftjcsob.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.c1oappe.top/Article/details/gtltbttxbb.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.c1oappe.top/Article/details/gtpzozxyfc.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.nanxinkj.top/Article/details/gtlmgcxzys.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.nwbrower.top/Article/details/gtgxsdulqq.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhongyouzk.top/Article/details/gtyaywhlev.html

[E02] 重复字符串
来源：http://dali.daxiang520.top/Article/details/gtyjhlreko.html

Py:   "ab" * 3
来源：http://dali.jianghu66.top/Article/details/gtdjodnbxd.html

PHP:  str_repeat("ab", 3);
来源：http://dali.shuidangran.top/Article/details/gteaadgjfj.html

JS:   "ab".repeat(3)
来源：http://dali.yanxiufei.cn/Article/details/gtiatmzood.html

TS:   "ab".repeat(3)
来源：http://dali.zhengqikj.top/Article/details/gtcuyamoai.html

Java: "ab".repeat(3)
来源：http://dali.hysaishi.cn/Article/details/gtsptuhlsv.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.nwbrower.top/Article/details/gtkdrtcgud.html

Ruby: "ab" * 3
来源：http://dali.snrcjt.cn/Article/details/gtghxuwrqo.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jiagoushi.top/Article/details/gtvdicoady.html

[E03] 截取子串
来源：http://dali.shzxlz.cn/Article/details/gtesqkmeyg.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.wangshuangyany.cn/Article/details/gtforzmtgh.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yj20258.top/Article/details/gtndydxjrq.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.guannengcc.top/Article/details/gtsvhjdnaw.html

TS:   s.slice(1, 4)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrebevvfv.html

Java: s.substring(1, 4)
来源：http://dali.yanxiufei.cn/Article/details/gtnnicbjqk.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.daxiang520.top/Article/details/gtvtiizrry.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.daria6918.cn/Article/details/gtweiujocs.html

C#:   s.Substring(1, 3)
来源：http://dali.yongpay.top/Article/details/gtdrusncab.html

[E04] 查找子串位置
来源：http://dali.jiagoushi.top/Article/details/gtvfvmhtpu.html

Py:   s.find("x");  s.index("x")
来源：http://dali.sxryk.cn/Article/details/gtdfshmisz.html

PHP:  strpos($s, "x");
来源：http://dali.gzhubu.top/Article/details/gtqcghfgbe.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.andypj.xyz/Article/details/gtsgskebyw.html

TS:   s.indexOf("x")
来源：http://dali.kuanghao11.cn/Article/details/gtepzmxofz.html

Java: s.indexOf("x")
来源：http://dali.redwolf501.top/Article/details/gthwszchjd.html

Go:   strings.Index(s, "x")
来源：http://dali.sysykeji.top/Article/details/gtuoyekkxc.html

Ruby: s.index("x")
来源：http://dali.fengsongda.top/Article/details/gtcapipxux.html

C#:   s.IndexOf("x")
来源：http://dali.mhx1999.top/Article/details/gthvqxxipk.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.snrcjt.cn/Article/details/gtkebxrkzp.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.quarkkingdee.top/Article/details/gtkrcdhalo.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jinqigfzy.top/Article/details/gtavbqgzdl.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinqigfzy.top/Article/details/gtfbhskfdp.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jiagoushi.top/Article/details/gtyyhpebrf.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gogol.net.cn/Article/details/gtmsysxjdk.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.aibaodan.cn/Article/details/gtxltwkdzw.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.sysykeji.top/Article/details/gtsoreoson.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yonumen.top/Article/details/gtnvtjcxzi.html

[E06] 替换子串
来源：http://dali.gzhubu.top/Article/details/gtgrqueoxk.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.wangshuangyany.cn/Article/details/gtvxfueozx.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.ehwqpu.com/Article/details/gtkjnmedgu.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yongpay.top/Article/details/gtvslctmjd.html

TS:   s.replaceAll("a", "b")
来源：http://dali.9152youxi.cn/Article/details/gtkevjwiqt.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.guannengcc.top/Article/details/gtmayqtbxr.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.aibaodan.cn/Article/details/gthkuqmvbv.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.shanyushiyangtech.top/Article/details/gtfsibcdbc.html

C#:   s.Replace("a", "b")
来源：http://dali.vqdsnc.cn/Article/details/gtwhwbowqt.html

[E07] 按分隔符拆分
来源：http://dali.shangyingyoupin.top/Article/details/gtabvtzobi.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.chenjidiqi.icu/Article/details/gtujwipaiv.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.cqqwz.cn/Article/details/gtedkakely.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.cashguo.top/Article/details/gtpxmfgmmm.html

TS:   s.split(",")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtouttswqt.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.snrcjt.cn/Article/details/gtqxwgujlj.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.fzhhl.top/Article/details/gtvjfkgmvx.html

Ruby: s.split(",");  s.split
来源：http://dali.andypj.xyz/Article/details/gtqpsznzpm.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yj202588.top/Article/details/gtjxjswxpd.html

[E08] 数组按分隔符合并
来源：http://dali.9152youxi.cn/Article/details/gtnqptglbm.html

Py:   ",".join(items)
来源：http://dali.zhoulong.xyz/Article/details/gtkcxergce.html

PHP:  implode(",", $items);
来源：http://dali.ybcxt.top/Article/details/gtspwkvkvh.html

JS:   items.join(",")
来源：http://dali.zhongyouzk.top/Article/details/gtroaxehrv.html

TS:   items.join(",")
来源：http://dali.jianghu66.top/Article/details/gtysivwjio.html

Java: String.join(",", items)
来源：http://dali.nanxuanxn.top/Article/details/gtxobcdwks.html

Go:   strings.Join(items, ",")
来源：http://dali.zdqjudy.top/Article/details/gtvvlagowh.html

Ruby: items.join(",")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjfczboen.html

C#:   string.Join(",", items)
来源：http://dali.zdqjudy.top/Article/details/gtgbfhlhjf.html

[E09] 去除所有空白字符
来源：http://dali.sxryk.cn/Article/details/gtcklwpvgx.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.chenzaomai.com/Article/details/gtcnmqxnnd.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yuanzhike.top/Article/details/gtijgngifn.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.0kj1m.cn/Article/details/gtwsmoissh.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.tian-w.cn/Article/details/gtirwszmzz.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.shzxlz.cn/Article/details/gtilkespsq.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.fengsongda.top/Article/details/gtyejyghib.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.aizwys.cn/Article/details/gtphhwgkdc.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jinghuilouyu.cn/Article/details/gtobmtbyll.html

[E10] 左侧补零 / 定长填充
来源：http://dali.pengpengdd.cyou/Article/details/gtrihznxud.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.havefunace.top/Article/details/gtwdgronzh.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.hysaishi.cn/Article/details/gtdttgxpyq.html

JS:   "7".padStart(3, "0")
来源：http://dali.jyoumei.cn/Article/details/gtlcfeddiy.html

TS:   "7".padStart(3, "0")
来源：http://dali.quarkkingdee.top/Article/details/gtbkxjteyq.html

Java: String.format("%03d", 7)
来源：http://dali.xziqi.cn/Article/details/gthsdjcmoh.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhengqikj.top/Article/details/gtjcbbhbba.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jianghu66.top/Article/details/gtvizfahei.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhiwuduotai.top/Article/details/gtnimfgadw.html

[E11] 反转字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlmayaskq.html

Py:   s[::-1]
来源：http://dali.jiagoushi.top/Article/details/gtoayfkosq.html

PHP:  strrev($s);
来源：http://dali.andypj.xyz/Article/details/gtifxqqfms.html

JS:   [...s].reverse().join("")
来源：http://dali.zhixingplan.top/Article/details/gtxtvsetwi.html

TS:   [...s].reverse().join("")
来源：http://dali.svipenyu.cn/Article/details/gtoafljmmd.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpuptzvtx.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yvedp.cn/Article/details/gttuolzfqt.html

Ruby: s.reverse
来源：http://dali.yonumen.top/Article/details/gtaoniegzk.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.xuetiantiany.cn/Article/details/gtlxnaawcv.html

[E12] 统计某字符出现次数
来源：http://dali.gzhubu.top/Article/details/gtqlbjahek.html

Py:   s.count("a")
来源：http://dali.redwolf501.top/Article/details/gtkuhminkk.html

PHP:  substr_count($s, "a");
来源：http://dali.chenjidiqi.icu/Article/details/gtuxbsrohr.html

JS:   s.split("a").length - 1
来源：http://dali.xuanzx.com/Article/details/gthimaofqe.html

TS:   s.split("a").length - 1
来源：http://dali.fzhhl.top/Article/details/gtfgelifst.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.hnqzz.top/Article/details/gtkzaglycx.html

Go:   strings.Count(s, "a")
来源：http://dali.hammf.cn/Article/details/gtefmeqfsw.html

Ruby: s.count("a")
来源：http://dali.wangdashe.top/Article/details/gtmedtghot.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yongpay.top/Article/details/gtqchycrat.html

[E13] 逐字符遍历
来源：http://dali.shanyushiyangtech.top/Article/details/gtjmllqlrd.html

Py:   for ch in s: print(ch)
来源：http://dali.ppjwa.cn/Article/details/gtsvhmktlq.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhixingplan.top/Article/details/gtzofxaypr.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrsnhavjl.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sweek.top/Article/details/gtqcefpxph.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.ehwqpu.com/Article/details/gtpatcgord.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.smart0.xyz/Article/details/gtxwigtooi.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jqgfzy.top/Article/details/gthahtexij.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gtpjqyofea.html

[E14] URL 编码与 Base64
来源：http://dali.yueranfly.top/Article/details/gtgflsvavs.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhongyouzk.top/Article/details/gtajhsdxcp.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yuxming.cn/Article/details/gtqllgyvgk.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yangfankeji.com/Article/details/gtcyuippxd.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.cheryme.top/Article/details/gtnlfcgheq.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.cashguo.top/Article/details/gtbargwuxu.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jqgufenzy.top/Article/details/gtxyfdarbe.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.mhx1999.top/Article/details/gtodbkazkv.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.svipenyu.cn/Article/details/gtuikwevip.html

[E15] HTML 转义 / 反转义
来源：http://dali.xinyue.icu/Article/details/gtbwkuemzf.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.hammf.cn/Article/details/gtcmmszptj.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.bjfxy.top/Article/details/gtgxwswxlv.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.xinyue.icu/Article/details/gtgsqjiwwj.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhoulong.xyz/Article/details/gtdfsdtzvm.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.tian-w.cn/Article/details/gtpqafhxxw.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.0kj1m.cn/Article/details/gtrazlomxv.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.cheryme.top/Article/details/gttpulglqx.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.xuanzx.com/Article/details/gtkdxzfghg.html

[E16] 数字千分位
来源：http://dali.yj20258.top/Article/details/gtcftwrsiz.html

Py:   f"{1234567:,}"
来源：http://dali.dianchejie.cn/Article/details/gtwxibouew.html

PHP:  number_format(1234567);
来源：http://dali.zhongyouzk.top/Article/details/gtnaaeevfu.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqibpncmo.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.sweek.top/Article/details/gtdzpysjjy.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.bjfxy.top/Article/details/gtxrxrquxa.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.chenjidiqi.icu/Article/details/gtgwggxfmu.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.sysykeji.top/Article/details/gtvdccipdr.html

C#:   1234567.ToString("N0")
来源：http://dali.yonumen.top/Article/details/gtfjzixypc.html

[E17] 首字母大写
来源：http://dali.zdqjudy.top/Article/details/gttaxhppdy.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhixingplan.top/Article/details/gtfscyydgd.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjurofpmx.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xylfe.cn/Article/details/gtwqndxsyn.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gogol.net.cn/Article/details/gtmvkvmchk.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.chenzaomai.com/Article/details/gttmjygwvl.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yangfankeji.com/Article/details/gtpxqxubyt.html

Ruby: s.capitalize
来源：http://dali.tian-w.cn/Article/details/gttvnyigxm.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhiwuduotai.top/Article/details/gtuzkqueio.html

[E18] 模板占位符替换
来源：http://dali.c1oappe.top/Article/details/gtyonmstdn.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhengqikj.top/Article/details/gtuusuncds.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xuetiantiany.cn/Article/details/gteglnkmvu.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.c1oappe.top/Article/details/gtvwaenntw.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yuanzhike.top/Article/details/gtlqlxcgwd.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.quarkkingdee.top/Article/details/gtwrkzwraq.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.shangyingyoupin.top/Article/details/gtqrqevlie.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.aibaodan.cn/Article/details/gtjmityjez.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yanxiufei.cn/Article/details/gtldvhoobz.html

[E19] 多行文本按行拆分
来源：http://dali.ehwqpu.com/Article/details/gtmersyaeb.html

Py:   s.splitlines()
来源：http://dali.bjfxy.top/Article/details/gtvdlaboci.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gtchbalajs.html

JS:   s.split(/\r?\n/)
来源：http://dali.nwbrower.top/Article/details/gtahhlamij.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhiwuduotai.top/Article/details/gtxmdkgwyq.html

Java: s.lines().toList()
来源：http://dali.jyoumei.cn/Article/details/gtumjwrbgs.html

Go:   strings.Split(s, "\n")
来源：http://dali.daxiang520.top/Article/details/gtpdppffpa.html

Ruby: s.lines
来源：http://dali.nwbrower.top/Article/details/gtzcfgejtq.html

C#:   s.Split('\n')
来源：http://dali.zdqjudy.top/Article/details/gtvwvwjfpa.html

[E20] 判断字符串是否为空
来源：http://dali.nanxinkj.top/Article/details/gtlifjdugt.html

Py:   if not s:
来源：http://dali.meibo888.top/Article/details/gtoaquvmaj.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.xziqi.cn/Article/details/gtlwyfiptd.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yj20258888.top/Article/details/gtokbazedw.html

TS:   if (s === "") {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtemoqmoyf.html

Java: if (s.isEmpty()) {}
来源：http://dali.jiagoushi.top/Article/details/gtpczgkwaa.html

Go:   if s == "" {}
来源：http://dali.zhengqikj.top/Article/details/gtbatrkbut.html

Ruby: if s.empty?
来源：http://dali.feifeiyinyue.top/Article/details/gtfrnperis.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.fzhhl.top/Article/details/gtwwtkkdtl.html

[E21] 超长截断加省略号
来源：http://dali.pycfn.com/Article/details/gtxkvdzvhu.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.cheryme.top/Article/details/gtucbngnth.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.feifeiyinyue.top/Article/details/gtiugsiywz.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jyoumei.cn/Article/details/gtiwdyeyke.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.dianchejie.cn/Article/details/gtnphhlmvo.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jianghu66.top/Article/details/gtzgnmczhg.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.ehwqpu.com/Article/details/gttrgdsddy.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.hfpthk.cn/Article/details/gtxemlrlay.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.cqqwz.cn/Article/details/gtfgpfdrit.html

[E22] 字节长度与字符长度
来源：http://dali.guannengcc.top/Article/details/gtoeqerckt.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.vqdsnc.cn/Article/details/gtfhtlwczw.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ivvv.top/Article/details/gtzzmocyqd.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.c1oappe.top/Article/details/gtvsnabekd.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.dianchejie.cn/Article/details/gtzahqkjip.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yj20258.top/Article/details/gtcyybjfvk.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jyoumei.cn/Article/details/gtpeobcgcx.html

Ruby: s.bytesize;  s.length
来源：http://dali.dianchejie.cn/Article/details/gtxmleykew.html


<!-- 参考信息 -->