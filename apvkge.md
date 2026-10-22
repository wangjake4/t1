代发 wailian999

PHP:  max($arr);  min($arr);
来源：http://dali.bjfxy.top/Article/details/gtisuzgfnh.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.nanxuanxn.top/Article/details/gtmochyxer.html

TS:   Math.max(...arr);
来源：http://dali.dianchejie.cn/Article/details/gtqiqocurj.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jinqigufen.top/Article/details/gtrycjrdwi.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jiagoushi.top/Article/details/gtezdexudj.html

Ruby: arr.max;  arr.min
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdgwgenwb.html

C#:   list.Max();  list.Min()
来源：http://dali.ybcxt.top/Article/details/gtwroaurtl.html

[D18] 扁平化嵌套数组
来源：http://dali.haohaochexian.top/Article/details/gtsnxetvja.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.mhx1999.top/Article/details/gtxygbvlvq.html

PHP:  array_merge(...$nested);
来源：http://dali.yuanzhike.top/Article/details/gtfbnvtfko.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ydzc1.top/Article/details/gtvvvznzhn.html

TS:   nested.flat();
来源：http://dali.jinqigufen.top/Article/details/gttuvhatrl.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.9152youxi.cn/Article/details/gtlweccpnf.html

Go:   // 手写双层循环
来源：http://dali.cdnleiting.top/Article/details/gtvbdgrvpr.html

Ruby: nested.flatten
来源：http://dali.dashuyun.cn/Article/details/gtbpzwpqvt.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jinqigfzy.top/Article/details/gthmohdsta.html

[D19] 按字段分组
来源：http://dali.yueranfly.top/Article/details/gtbdoqorik.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.gotoacloud.top/Article/details/gthakeptfs.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.redwolf501.top/Article/details/gtggqwsueo.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.cashguo.top/Article/details/gtgyvytzls.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.gzhubu.top/Article/details/gtgnlxtvfc.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yonumen.top/Article/details/gtdjbfstry.html

Go:   // 手写 map[string][]T
来源：http://dali.yj20258888.top/Article/details/gtpdauxlqj.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zycfv.cn/Article/details/gtwzxsxulf.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.cashguo.top/Article/details/gtyntyfijq.html

[D20] 统计每个元素出现次数
来源：http://dali.gogol.net.cn/Article/details/gtkfwrrutn.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gtbhkeozda.html

PHP:  array_count_values($arr);
来源：http://dali.jianghu66.top/Article/details/gttllczevy.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gaohongyu789.top/Article/details/gtgzpkseqz.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.andypj.xyz/Article/details/gtnebemdwv.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.gaohongyu789.top/Article/details/gteoxbigmj.html

Go:   // 手写 map[T]int
来源：http://dali.jyoumei.cn/Article/details/gtqbyqkdhs.html

Ruby: arr.tally
来源：http://dali.feifeiyinyue.top/Article/details/gtymcmybpc.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jyoumei.cn/Article/details/gtmjibuqlm.html

[D21] 判断是否包含某元素
来源：http://dali.chenjidiqi.icu/Article/details/gtsnjcgejt.html

Py:   x in arr
来源：http://dali.ehwqpu.com/Article/details/gtuvqjwtce.html

PHP:  in_array($x, $arr, true);
来源：http://dali.sxryk.cn/Article/details/gtyrjiiysl.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gtyjkvsfmk.html

TS:   arr.includes(x)
来源：http://dali.chenzaomai.com/Article/details/gtnudvtasy.html

Java: list.contains(x)
来源：http://dali.quarkkingdee.top/Article/details/gtrtjxesek.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gtvdxjdkha.html

Ruby: arr.include?(x)
来源：http://dali.andypj.xyz/Article/details/gtlsiiwsrj.html

C#:   list.Contains(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzxuoepce.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gtvxlfonbj.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yj20258888.top/Article/details/gtioojzhco.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jqgufenzy.top/Article/details/gtdbstbndy.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.nanxuanxn.top/Article/details/gtrgsgcduc.html

TS:   [...arr];
来源：http://dali.xinyue.icu/Article/details/gttmzxxcmq.html

Java: new ArrayList<>(list);
来源：http://dali.aizwys.cn/Article/details/gtrojnpmrf.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.fengsongda.top/Article/details/gtpewkvvll.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jinqigufen.top/Article/details/gtgnwlnice.html

C#:   new List<int>(list);
来源：http://dali.nanxinkj.top/Article/details/gtomjfexkp.html

[D23] reduce 累积计算
来源：http://dali.hnqzz.top/Article/details/gtvuifyymy.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.ydzc1.top/Article/details/gtomcywcct.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yj20258.top/Article/details/gtlyfagfvt.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gtlgjmxfxn.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.snrcjt.cn/Article/details/gtbeiruwsm.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.haohaochexian.top/Article/details/gtcydgwqyf.html

Go:   // 手写循环
来源：http://dali.birdmap.top/Article/details/gtdnugrbda.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.nanxuanxn.top/Article/details/gtbsmrupcg.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.sufxvd.cn/Article/details/gtoivipbbx.html

[D24] 字典 / Map 基本操作
来源：http://dali.hfpthk.cn/Article/details/gtmlmzkjyn.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.xinyue.icu/Article/details/gtjtawnvtz.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.dashuyun.cn/Article/details/gtxzxmxlki.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.ppjwa.cn/Article/details/gtruadelpr.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.aizwys.cn/Article/details/gtthtlujug.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfoclfhnm.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.quarkkingdee.top/Article/details/gtdxwpwghs.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.wangshuangyany.cn/Article/details/gteeuthhqz.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.hongshengwenyu.top/Article/details/gtsqeqefvx.html

[D25] Set 集合去重与交并差
来源：http://dali.andypj.xyz/Article/details/gtqergpnvq.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hfpthk.cn/Article/details/gtqudfcitt.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.pengpengdd.cyou/Article/details/gtyhnkkwfo.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jinqigufen.top/Article/details/gtqsijbrie.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hongshengwenyu.top/Article/details/gticdcjczj.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.fzhhl.top/Article/details/gtmwbhfona.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hysaishi.cn/Article/details/gtxqbkokuj.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.kuanghao11.cn/Article/details/gtxyxfypkv.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jyoumei.cn/Article/details/gtraazqbpn.html

[D26] 数组转字符串
来源：http://dali.jianghu66.top/Article/details/gtmkkldsjg.html

Py:   ", ".join(map(str, arr))
来源：http://dali.shuidangran.top/Article/details/gthpglehan.html

PHP:  implode(", ", $arr);
来源：http://dali.cashguo.top/Article/details/gtuodqzkwf.html

JS:   arr.join(", ")
来源：http://dali.redwolf501.top/Article/details/gtmlgnkjvl.html

TS:   arr.join(", ")
来源：http://dali.yanxiufei.cn/Article/details/gtsuoadalu.html

Java: String.join(", ", list)
来源：http://dali.fzhhl.top/Article/details/gtnoxxjlns.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttxtkkhav.html

Ruby: arr.join(", ")
来源：http://dali.zhixingplan.top/Article/details/gtgihaqthj.html

C#:   string.Join(", ", list)
来源：http://dali.sysykeji.top/Article/details/gtpztusnez.html

================================================================================
来源：http://dali.sweek.top/Article/details/gttbtlqocd.html

E. 字符串处理
来源：http://dali.shanyushiyangtech.top/Article/details/gtqapbqmzr.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtqfwkzwau.html

[E01] 拼接字符串
来源：http://dali.yvedp.cn/Article/details/gtjtsizrji.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.cashguo.top/Article/details/gtgvijeeii.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yvedp.cn/Article/details/gtamylwhbm.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cdnleiting.top/Article/details/gtvelwzvva.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.iojbl.cn/Article/details/gtkkqzdjfx.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.fzhhl.top/Article/details/gtbayiprxi.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.sysykeji.top/Article/details/gtkaurivly.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.bjfxy.top/Article/details/gthuzhpkov.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.c1oappe.top/Article/details/gtnywlwncy.html

[E02] 重复字符串
来源：http://dali.cucudq.cn/Article/details/gtsmlqiccd.html

Py:   "ab" * 3
来源：http://dali.cashguo.top/Article/details/gtbpsqpebr.html

PHP:  str_repeat("ab", 3);
来源：http://dali.dianchejie.cn/Article/details/gtrgqefwpe.html

JS:   "ab".repeat(3)
来源：http://dali.xylfe.cn/Article/details/gtmjiyptjl.html

TS:   "ab".repeat(3)
来源：http://dali.xziqi.cn/Article/details/gtrvwqvltf.html

Java: "ab".repeat(3)
来源：http://dali.gaohongyu789.top/Article/details/gtcbkefvok.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.tianlin.xyz/Article/details/gtzvgmwffi.html

Ruby: "ab" * 3
来源：http://dali.sysykeji.top/Article/details/gtgoulluju.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.wangdashe.top/Article/details/gttmtgetrh.html

[E03] 截取子串
来源：http://dali.guannengcc.top/Article/details/gtdshhnqdg.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.hysaishi.cn/Article/details/gtkxzlfxpf.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yj20258.top/Article/details/gtrmsonapx.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.smart0.xyz/Article/details/gtwysvcimt.html

TS:   s.slice(1, 4)
来源：http://dali.hysaishi.cn/Article/details/gtyiepzyoh.html

Java: s.substring(1, 4)
来源：http://dali.redwolf501.top/Article/details/gtycfgmlrq.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.xziqi.cn/Article/details/gtqtcksmzc.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgxginkdl.html

C#:   s.Substring(1, 3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtucpjaicr.html

[E04] 查找子串位置
来源：http://dali.svipenyu.cn/Article/details/gtyzvbbjpe.html

Py:   s.find("x");  s.index("x")
来源：http://dali.xuetiantiany.cn/Article/details/gtozfhvpzc.html

PHP:  strpos($s, "x");
来源：http://dali.zhiwuduotai.top/Article/details/gttzajndxn.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jqgufenzy.top/Article/details/gtjxicfkuc.html

TS:   s.indexOf("x")
来源：http://dali.aizwys.cn/Article/details/gtwfquxfvg.html

Java: s.indexOf("x")
来源：http://dali.zhixingplan.top/Article/details/gtpwfqjidl.html

Go:   strings.Index(s, "x")
来源：http://dali.shuidangran.top/Article/details/gtknnpekdv.html

Ruby: s.index("x")
来源：http://dali.snrcjt.cn/Article/details/gtvrzupkas.html

C#:   s.IndexOf("x")
来源：http://dali.nanxuanxn.top/Article/details/gtgqqvbouu.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.tanke756.top/Article/details/gtiwojpjyx.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.cdnleiting.top/Article/details/gtvdbpidnr.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jqgfzy.top/Article/details/gtejsbjfdu.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yuanzhike.top/Article/details/gtsjihlmxn.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.gzhubu.top/Article/details/gtthnbilje.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.0kj1m.cn/Article/details/gtojqqgjxq.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.tanke756.top/Article/details/gtuowdqkvg.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.guowangkeji.top/Article/details/gthcjqaqcw.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.sxryk.cn/Article/details/gtqjkojrgq.html

[E06] 替换子串
来源：http://dali.vqdsnc.cn/Article/details/gtwxlhsvxs.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.ivvv.top/Article/details/gtldgmmmwu.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.bjfxy.top/Article/details/gtvnitzoal.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hysaishi.cn/Article/details/gtrrvuqyho.html

TS:   s.replaceAll("a", "b")
来源：http://dali.cdnleiting.top/Article/details/gttvlimitk.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhixingplan.top/Article/details/gtmycnwiok.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.birdmap.top/Article/details/gtxtzklbwa.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjdijylbp.html

C#:   s.Replace("a", "b")
来源：http://dali.vqdsnc.cn/Article/details/gtfpwwtvvd.html

[E07] 按分隔符拆分
来源：http://dali.tianlin.xyz/Article/details/gtellunkyt.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.fzhhl.top/Article/details/gtjfttopbx.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.daxiang520.top/Article/details/gtvrlifnwa.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthltbuhmb.html

TS:   s.split(",")
来源：http://dali.jianghu66.top/Article/details/gtpkfituap.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.quarkkingdee.top/Article/details/gtipdprbdk.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.0kj1m.cn/Article/details/gtfrieoijc.html

Ruby: s.split(",");  s.split
来源：http://dali.hfpthk.cn/Article/details/gteialnmai.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jinqigufen.top/Article/details/gtckjszhsb.html

[E08] 数组按分隔符合并
来源：http://dali.meibo888.top/Article/details/gtjadfgfyg.html

Py:   ",".join(items)
来源：http://dali.yongpay.top/Article/details/gtntrptyla.html

PHP:  implode(",", $items);
来源：http://dali.yj20258888.top/Article/details/gtpiofsolm.html

JS:   items.join(",")
来源：http://dali.ivvv.top/Article/details/gtohgetcbp.html

TS:   items.join(",")
来源：http://dali.aizwys.cn/Article/details/gtlmdynswp.html

Java: String.join(",", items)
来源：http://dali.316326.xyz/Article/details/gtgvxgczgd.html

Go:   strings.Join(items, ",")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtknktjqsb.html

Ruby: items.join(",")
来源：http://dali.yonumen.top/Article/details/gtcdwbcnrw.html

C#:   string.Join(",", items)
来源：http://dali.yanxiufei.cn/Article/details/gtonyrbvha.html

[E09] 去除所有空白字符
来源：http://dali.gaohongyu789.top/Article/details/gtkdckihkj.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.shzxlz.cn/Article/details/gtdeoxvpgs.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.cashguo.top/Article/details/gtcpqrebxc.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gtcieyepdf.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.aizwys.cn/Article/details/gtnqfeedaw.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yj20258.top/Article/details/gtqyyzlpoc.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jyoumei.cn/Article/details/gtdnckcdka.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.cheryme.top/Article/details/gtdsejlgdp.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.svipenyu.cn/Article/details/gtsejloqov.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhengqikj.top/Article/details/gtnbenxcqt.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.nanxinkj.top/Article/details/gtbzctecfb.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yonumen.top/Article/details/gtuubrhmeh.html

JS:   "7".padStart(3, "0")
来源：http://dali.cdnleiting.top/Article/details/gtwjnusnwf.html

TS:   "7".padStart(3, "0")
来源：http://dali.jinghuilouyu.cn/Article/details/gttytzffsp.html

Java: String.format("%03d", 7)
来源：http://dali.chenjidiqi.icu/Article/details/gtvbdhmhfe.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.svipenyu.cn/Article/details/gtyvaxtgjw.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.guannengcc.top/Article/details/gtcuyaowdk.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.gzhubu.top/Article/details/gteiprwkiv.html

[E11] 反转字符串
来源：http://dali.chenlongwang.top/Article/details/gtjesfxaqm.html

Py:   s[::-1]
来源：http://dali.sweek.top/Article/details/gtcwchdsvx.html

PHP:  strrev($s);
来源：http://dali.chenjidiqi.icu/Article/details/gtrvrfccrv.html

JS:   [...s].reverse().join("")
来源：http://dali.jqgfzy.top/Article/details/gtviqykgsp.html

TS:   [...s].reverse().join("")
来源：http://dali.xziqi.cn/Article/details/gtbuszjqyu.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.shzxlz.cn/Article/details/gtofimcnge.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.birdmap.top/Article/details/gtuyqixtuy.html

Ruby: s.reverse
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxsktenpi.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.dianchejie.cn/Article/details/gtxbcrmvik.html

[E12] 统计某字符出现次数
来源：http://dali.andypj.xyz/Article/details/gtrgqkeiji.html

Py:   s.count("a")
来源：http://dali.cqqwz.cn/Article/details/gtsecmdsvd.html

PHP:  substr_count($s, "a");
来源：http://dali.nanxinkj.top/Article/details/gtywjrnscu.html

JS:   s.split("a").length - 1
来源：http://dali.nanxuanxn.top/Article/details/gtxdvdkfbx.html

TS:   s.split("a").length - 1
来源：http://dali.fengsongda.top/Article/details/gttcnsuoge.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.gaohongyu789.top/Article/details/gtnnxsasse.html

Go:   strings.Count(s, "a")
来源：http://dali.guannengcc.top/Article/details/gtgjgxtvhx.html

Ruby: s.count("a")
来源：http://dali.yvedp.cn/Article/details/gtgvfbbnbm.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jyoumei.cn/Article/details/gtedufseiz.html

[E13] 逐字符遍历
来源：http://dali.haohaochexian.top/Article/details/gtfydfagpx.html

Py:   for ch in s: print(ch)
来源：http://dali.dianchejie.cn/Article/details/gtwpmtrjkn.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yuxming.cn/Article/details/gtxuhiflbs.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hywenlv.cn/Article/details/gtweaovmlo.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jlsjyb.cn/Article/details/gtxnbowybn.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.wangshuangyany.cn/Article/details/gtqqpfusup.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.dianchejie.cn/Article/details/gtklptznpc.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.cucudq.cn/Article/details/gtuwzruzks.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yangfankeji.com/Article/details/gtmwxfhuax.html

[E14] URL 编码与 Base64
来源：http://dali.iojbl.cn/Article/details/gtyqnyctvb.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.redwolf501.top/Article/details/gtflikunwl.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yuxming.cn/Article/details/gtflzmrlww.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.9152youxi.cn/Article/details/gtcnvjkbwi.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.xuanzx.com/Article/details/gtlnygseni.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.cqqwz.cn/Article/details/gtzrzazscv.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.meibo888.top/Article/details/gthimhmazr.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yj20258.top/Article/details/gtbwdxwrel.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.guannengcc.top/Article/details/gtwmxvshdc.html

[E15] HTML 转义 / 反转义
来源：http://dali.sweek.top/Article/details/gtcqgdzutm.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.vqdsnc.cn/Article/details/gtjkhewaif.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.gaohongyu789.top/Article/details/gtpzdlqfol.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.ppjwa.cn/Article/details/gtwjibliux.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.9152youxi.cn/Article/details/gtzrgngrut.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.ehwqpu.com/Article/details/gttvwocbhb.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.dianchejie.cn/Article/details/gtmkxfjyhz.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.shzxlz.cn/Article/details/gtcrkaszhv.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.snrcjt.cn/Article/details/gtwtjtjeov.html

[E16] 数字千分位
来源：http://dali.dianchejie.cn/Article/details/gtrinuqoyw.html

Py:   f"{1234567:,}"
来源：http://dali.hnxiangtu.top/Article/details/gtjdhaokrk.html

PHP:  number_format(1234567);
来源：http://dali.birdmap.top/Article/details/gtqdbklohu.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.cqqwz.cn/Article/details/gthlniuslt.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.hnqzz.top/Article/details/gtbjfwehss.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.cucudq.cn/Article/details/gtsmgpbwgu.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hfpthk.cn/Article/details/gtavskiqda.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.chenlongwang.top/Article/details/gtjjedveei.html

C#:   1234567.ToString("N0")
来源：http://dali.zhixingplan.top/Article/details/gtxlxtwzrh.html

[E17] 首字母大写
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcnosfain.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yongpay.top/Article/details/gtfatqhnjd.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.vqdsnc.cn/Article/details/gtwfhctztr.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cqqwz.cn/Article/details/gtfirnjfrr.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sxryk.cn/Article/details/gtiylihfat.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yongpay.top/Article/details/gtttkggalj.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.shanyushiyangtech.top/Article/details/gtppvzlpaw.html

Ruby: s.capitalize
来源：http://dali.shuidangran.top/Article/details/gtpwmtgimr.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.chenzaomai.com/Article/details/gtixlnvlor.html

[E18] 模板占位符替换
来源：http://dali.jqgufenzy.top/Article/details/gtdehkffnw.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.guowangkeji.top/Article/details/gtrpkyjwmu.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhoulong.xyz/Article/details/gtvaaxmprd.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.cdnleiting.top/Article/details/gtabnoirvq.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinqigufen.top/Article/details/gtruxjvmdi.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hnxiangtu.top/Article/details/gtfenptweg.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.nanxuanxn.top/Article/details/gtaytksuem.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zycfv.cn/Article/details/gtjjpdroam.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.cashguo.top/Article/details/gtzkowpooz.html

[E19] 多行文本按行拆分
来源：http://dali.daxiang520.top/Article/details/gtvhrawwvu.html

Py:   s.splitlines()
来源：http://dali.jinqigfzy.top/Article/details/gtlmvidcqk.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.ydzc1.top/Article/details/gtbkyrgkak.html

JS:   s.split(/\r?\n/)
来源：http://dali.sxryk.cn/Article/details/gtofcnjued.html

TS:   s.split(/\r?\n/)
来源：http://dali.gotoacloud.top/Article/details/gtmtrkujfs.html

Java: s.lines().toList()
来源：http://dali.aizwys.cn/Article/details/gttwstiwql.html

Go:   strings.Split(s, "\n")
来源：http://dali.jianghu66.top/Article/details/gtecqsbiai.html

Ruby: s.lines
来源：http://dali.shuidangran.top/Article/details/gtopjajnch.html

C#:   s.Split('\n')
来源：http://dali.tian-w.cn/Article/details/gtqulsbirt.html

[E20] 判断字符串是否为空
来源：http://dali.tanke756.top/Article/details/gtvqjcdfts.html

Py:   if not s:
来源：http://dali.ybcxt.top/Article/details/gtpvolqdab.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.wangdashe.top/Article/details/gtgfmscyqa.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jqgufenzy.top/Article/details/gtvvlvblmc.html

TS:   if (s === "") {}
来源：http://dali.cheryme.top/Article/details/gtzoamjqbi.html

Java: if (s.isEmpty()) {}
来源：http://dali.quarkkingdee.top/Article/details/gtmomqinxb.html

Go:   if s == "" {}
来源：http://dali.guannengcc.top/Article/details/gtjblpuify.html

Ruby: if s.empty?
来源：http://dali.redwolf501.top/Article/details/gtivdtybhg.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.guannengcc.top/Article/details/gtzvomafrk.html

[E21] 超长截断加省略号
来源：http://dali.aizwys.cn/Article/details/gtkutiohba.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.nanxinkj.top/Article/details/gtllfcosev.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.shangyingyoupin.top/Article/details/gtonuzwgfr.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jqgufenzy.top/Article/details/gtgdbynkft.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sysykeji.top/Article/details/gtllwotcah.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.nwbrower.top/Article/details/gtqwrxtkyx.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.aibaodan.cn/Article/details/gtxwyednfr.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.cqqwz.cn/Article/details/gtrfktzepk.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.pengpengdd.cyou/Article/details/gtbtogbmst.html

[E22] 字节长度与字符长度
来源：http://dali.shanyushiyangtech.top/Article/details/gtecdgaggj.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.guannengcc.top/Article/details/gtkoenvito.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cashguo.top/Article/details/gtwbfxgyfj.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yj20258888.top/Article/details/gtgaqwzmnd.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shangyingyoupin.top/Article/details/gtetbbgfaw.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.andypj.xyz/Article/details/gtvxofxdcj.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmpjljytk.html

Ruby: s.bytesize;  s.length
来源：http://dali.cheryme.top/Article/details/gtzuscuhrt.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.xuetiantiany.cn/Article/details/gtfewlcszn.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtedbvqawz.html

F. 文件与目录
来源：http://dali.hnxiangtu.top/Article/details/gtbpdvofzs.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gthnjqdcbs.html

[F01] 读取整个文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtsuwrlrjy.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.cucudq.cn/Article/details/gtytxdxiif.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpluzfwzm.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.nanxinkj.top/Article/details/gtjeuswyxb.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yj20258888.top/Article/details/gtwrayzntq.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.wangshuangyany.cn/Article/details/gtomltriwb.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.chenjidiqi.icu/Article/details/gtiqmzniyj.html

Ruby: File.read("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtxukgcxwj.html


<!-- 参考信息 -->