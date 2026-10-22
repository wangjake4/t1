代发 wailian999

C#:   list.Distinct().ToList()
来源：http://dali.yueranfly.top/Article/details/gtpvfmxunf.html

[D16] 求和与平均值
来源：http://dali.dianchejie.cn/Article/details/gtyoopxyci.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtnetnbusv.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtwuoyxyge.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yuanzhike.top/Article/details/gthchxusud.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yj202588.top/Article/details/gtcujmetiv.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.shuidangran.top/Article/details/gtckpfuxwe.html

Go:   // 手写循环累加
来源：http://dali.meibo888.top/Article/details/gtprchjdzq.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jiagoushi.top/Article/details/gtvevwsvjc.html

C#:   list.Sum();  list.Average()
来源：http://dali.andypj.xyz/Article/details/gtatfpnymp.html

[D17] 最大值与最小值
来源：http://dali.zhongyouzk.top/Article/details/gtqqikdspg.html

Py:   max(arr);  min(arr)
来源：http://dali.meibo888.top/Article/details/gtfgcbnhbd.html

PHP:  max($arr);  min($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtotcycpxe.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jlsjyb.cn/Article/details/gtfbbahftq.html

TS:   Math.max(...arr);
来源：http://dali.ydzc1.top/Article/details/gtaamvbakx.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.redwolf501.top/Article/details/gtbhvsrzam.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhixingplan.top/Article/details/gthctpnwzi.html

Ruby: arr.max;  arr.min
来源：http://dali.daxiang520.top/Article/details/gtqpcemwnl.html

C#:   list.Max();  list.Min()
来源：http://dali.jiagoushi.top/Article/details/gtwpbppkvu.html

[D18] 扁平化嵌套数组
来源：http://dali.jinqigufen.top/Article/details/gtuhqnvkdq.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhongyouzk.top/Article/details/gtqyazmfih.html

PHP:  array_merge(...$nested);
来源：http://dali.dashuyun.cn/Article/details/gtyqjpgbup.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.dianchejie.cn/Article/details/gtxhpnhvvc.html

TS:   nested.flat();
来源：http://dali.jlsjyb.cn/Article/details/gthenmpdew.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zdqjudy.top/Article/details/gtmudgktrh.html

Go:   // 手写双层循环
来源：http://dali.cheryme.top/Article/details/gtxprldsxn.html

Ruby: nested.flatten
来源：http://dali.gaohongyu789.top/Article/details/gtliyrxctq.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.dashuyun.cn/Article/details/gtbkxowcjt.html

[D19] 按字段分组
来源：http://dali.yangfankeji.com/Article/details/gtylidityo.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.xylfe.cn/Article/details/gtyvwjcsse.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.0kj1m.cn/Article/details/gtevtzqxfo.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.9152youxi.cn/Article/details/gtgjppywmg.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.svipenyu.cn/Article/details/gtxvjgxrwu.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwtlwnysl.html

Go:   // 手写 map[string][]T
来源：http://dali.fzhhl.top/Article/details/gtqrzbtizq.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.shanyushiyangtech.top/Article/details/gtxkvdcrnt.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zdqjudy.top/Article/details/gtkuhyyhzl.html

[D20] 统计每个元素出现次数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmvdkjtit.html

Py:   Counter(arr)
来源：http://dali.yonumen.top/Article/details/gtskwazidj.html

PHP:  array_count_values($arr);
来源：http://dali.dianchejie.cn/Article/details/gtknfshgns.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.fengsongda.top/Article/details/gtgitajwyq.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ppjwa.cn/Article/details/gthrhgvhxz.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hnqzz.top/Article/details/gtcyegitux.html

Go:   // 手写 map[T]int
来源：http://dali.sweek.top/Article/details/gtonioeect.html

Ruby: arr.tally
来源：http://dali.ybcxt.top/Article/details/gtrtnfbtiz.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.nwbrower.top/Article/details/gtduyaqnlu.html

[D21] 判断是否包含某元素
来源：http://dali.xinyue.icu/Article/details/gtjhxuvgog.html

Py:   x in arr
来源：http://dali.dianchejie.cn/Article/details/gtsgiszjnk.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yvedp.cn/Article/details/gtqhnuncdh.html

JS:   arr.includes(x)
来源：http://dali.ivvv.top/Article/details/gtjkcnkcou.html

TS:   arr.includes(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcztnsbns.html

Java: list.contains(x)
来源：http://dali.wangshuangyany.cn/Article/details/gtnldsastk.html

Go:   slices.Contains(arr, x)
来源：http://dali.sweek.top/Article/details/gtmiblobbg.html

Ruby: arr.include?(x)
来源：http://dali.zhongyouzk.top/Article/details/gtklamdlns.html

C#:   list.Contains(x)
来源：http://dali.sysykeji.top/Article/details/gtkecxfzsa.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hysaishi.cn/Article/details/gtsgbghuaq.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jyoumei.cn/Article/details/gtogrpregc.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.sysykeji.top/Article/details/gtppfdpjuq.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.haohaochexian.top/Article/details/gtadxbysxv.html

TS:   [...arr];
来源：http://dali.shzxlz.cn/Article/details/gtgmdpdzum.html

Java: new ArrayList<>(list);
来源：http://dali.pengpengdd.cyou/Article/details/gtbkksfnxp.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jqgfzy.top/Article/details/gtgiuqcdmo.html

Ruby: arr.dup;  arr.clone
来源：http://dali.daria6918.cn/Article/details/gtxrrcujvd.html

C#:   new List<int>(list);
来源：http://dali.cashguo.top/Article/details/gtbfjfddju.html

[D23] reduce 累积计算
来源：http://dali.pengpengdd.cyou/Article/details/gtfowaygac.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.gotoacloud.top/Article/details/gtgfctrswg.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.gotoacloud.top/Article/details/gtvkwceuuh.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.redwolf501.top/Article/details/gtxymdknur.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jlsjyb.cn/Article/details/gtodazoxaf.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.aibaodan.cn/Article/details/gtwiksnyxg.html

Go:   // 手写循环
来源：http://dali.jinqigufen.top/Article/details/gtzlxlogwm.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zycfv.cn/Article/details/gtxnrnfufu.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jinqigfzy.top/Article/details/gtgcavzhkw.html

[D24] 字典 / Map 基本操作
来源：http://dali.wangshuangyany.cn/Article/details/gtvroevjfr.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjypzdpgr.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.chenzaomai.com/Article/details/gtkqjjcbgq.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yonumen.top/Article/details/gtfouvlfqb.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxnrubrwn.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.quarkkingdee.top/Article/details/gtacfuffze.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.aibaodan.cn/Article/details/gtqajfmdja.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.havefunace.top/Article/details/gtkuoowfqg.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.redwolf501.top/Article/details/gtesexxbbg.html

[D25] Set 集合去重与交并差
来源：http://dali.dashuyun.cn/Article/details/gtaxpebpun.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.shanyushiyangtech.top/Article/details/gtevdrfook.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.haohaochexian.top/Article/details/gtbbxsvqgz.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.gaohongyu789.top/Article/details/gtqhyvadqa.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.gaohongyu789.top/Article/details/gtfuvfjlts.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yj202588.top/Article/details/gtjjfizrjn.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.0kj1m.cn/Article/details/gtzrcoxkhv.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yj20258.top/Article/details/gtpzwlxvju.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gteldfpwvs.html

[D26] 数组转字符串
来源：http://dali.hammf.cn/Article/details/gtrbytuyjm.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hammf.cn/Article/details/gtxweudbra.html

PHP:  implode(", ", $arr);
来源：http://dali.redwolf501.top/Article/details/gtaugrqcgk.html

JS:   arr.join(", ")
来源：http://dali.hywenlv.cn/Article/details/gtbfqmanxs.html

TS:   arr.join(", ")
来源：http://dali.vqdsnc.cn/Article/details/gtzqdudrsu.html

Java: String.join(", ", list)
来源：http://dali.hfpthk.cn/Article/details/gtajnfmjgu.html

Go:   strings.Join(strs, ", ")
来源：http://dali.snrcjt.cn/Article/details/gtfrermhqu.html

Ruby: arr.join(", ")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdijhjsvp.html

C#:   string.Join(", ", list)
来源：http://dali.yangfankeji.com/Article/details/gtoshzhifx.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtptcbjbxs.html

E. 字符串处理
来源：http://dali.jinqigfzy.top/Article/details/gttsovsyxr.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtdhwuihhr.html

[E01] 拼接字符串
来源：http://dali.fengsongda.top/Article/details/gtmzvxjziy.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.cashguo.top/Article/details/gtwiyiogtp.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.sxryk.cn/Article/details/gtsoecztnh.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.aibaodan.cn/Article/details/gtqalixpyk.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cashguo.top/Article/details/gtxjgvqmsf.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hfpthk.cn/Article/details/gtyyeaojkr.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yj20258.top/Article/details/gttknekkur.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.quarkkingdee.top/Article/details/gtxicjjcgj.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jqgufenzy.top/Article/details/gtzepiwrol.html

[E02] 重复字符串
来源：http://dali.haohaochexian.top/Article/details/gtzflbbcya.html

Py:   "ab" * 3
来源：http://dali.yuxming.cn/Article/details/gtxfopuavw.html

PHP:  str_repeat("ab", 3);
来源：http://dali.xuetiantiany.cn/Article/details/gtygtkrkdz.html

JS:   "ab".repeat(3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttdbjjnhd.html

TS:   "ab".repeat(3)
来源：http://dali.zhiwuduotai.top/Article/details/gtdyqbqjxm.html

Java: "ab".repeat(3)
来源：http://dali.316326.xyz/Article/details/gtnyeaaffb.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.xuetiantiany.cn/Article/details/gtnvrxrqyj.html

Ruby: "ab" * 3
来源：http://dali.ywan-chungtsiang.top/Article/details/gtirwaswyu.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.hysaishi.cn/Article/details/gtgteibiuj.html

[E03] 截取子串
来源：http://dali.xziqi.cn/Article/details/gthmhsnvpk.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.gotoacloud.top/Article/details/gtzqukwsnm.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.meibo888.top/Article/details/gtcjcmfplk.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxvcavrgd.html

TS:   s.slice(1, 4)
来源：http://dali.ydzc1.top/Article/details/gtmpcjnljr.html

Java: s.substring(1, 4)
来源：http://dali.xuetiantiany.cn/Article/details/gtdcxuuzmp.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.cqqwz.cn/Article/details/gtopfldzas.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.aizwys.cn/Article/details/gtrkvwvshi.html

C#:   s.Substring(1, 3)
来源：http://dali.birdmap.top/Article/details/gtsfakvaqc.html

[E04] 查找子串位置
来源：http://dali.wangshuangyany.cn/Article/details/gtfkaazodf.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yj20258.top/Article/details/gtblxxaxoq.html

PHP:  strpos($s, "x");
来源：http://dali.hysaishi.cn/Article/details/gtufaumvnq.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jinqigfzy.top/Article/details/gteggeyeub.html

TS:   s.indexOf("x")
来源：http://dali.pycfn.com/Article/details/gtwdnzmhof.html

Java: s.indexOf("x")
来源：http://dali.gzhubu.top/Article/details/gtxyporabr.html

Go:   strings.Index(s, "x")
来源：http://dali.hongshengwenyu.top/Article/details/gtcjssbzck.html

Ruby: s.index("x")
来源：http://dali.dashuyun.cn/Article/details/gtgiyywrda.html

C#:   s.IndexOf("x")
来源：http://dali.fengsongda.top/Article/details/gtkdefhlvg.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.sysykeji.top/Article/details/gtinysgayb.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yueranfly.top/Article/details/gtnpgdvtmo.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jinghuilouyu.cn/Article/details/gtkvtqmpof.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zdqjudy.top/Article/details/gtjhckqerz.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.9152youxi.cn/Article/details/gtunjebitb.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.guowangkeji.top/Article/details/gtvknrxcsq.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hammf.cn/Article/details/gtveniuoun.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.9152youxi.cn/Article/details/gtlcojwjib.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yuanzhike.top/Article/details/gtqsjwndnz.html

[E06] 替换子串
来源：http://dali.ydzc1.top/Article/details/gtoczewebl.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.meibo888.top/Article/details/gtczxqbjkm.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jinqigufen.top/Article/details/gtqjemohfc.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cucudq.cn/Article/details/gtkxkrgiyu.html

TS:   s.replaceAll("a", "b")
来源：http://dali.sufxvd.cn/Article/details/gtsrfcgxjb.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtipndwuwj.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yuxming.cn/Article/details/gtryikjwkn.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.xuetiantiany.cn/Article/details/gtlrhkwoyr.html

C#:   s.Replace("a", "b")
来源：http://dali.jqgfzy.top/Article/details/gtncbvtisl.html

[E07] 按分隔符拆分
来源：http://dali.hnqzz.top/Article/details/gtwfbgtqlk.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.sxryk.cn/Article/details/gtuowxmtou.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gtpdjulivk.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.cheryme.top/Article/details/gtuffttkrn.html

TS:   s.split(",")
来源：http://dali.aizwys.cn/Article/details/gtqmtgxjqb.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.sweek.top/Article/details/gtscoztaxe.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.gaohongyu789.top/Article/details/gtnfondyxn.html

Ruby: s.split(",");  s.split
来源：http://dali.tianlin.xyz/Article/details/gtgovenhil.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.gogol.net.cn/Article/details/gthnyktjft.html

[E08] 数组按分隔符合并
来源：http://dali.dianchejie.cn/Article/details/gtfzcdpyob.html

Py:   ",".join(items)
来源：http://dali.shzxlz.cn/Article/details/gttukevwfp.html

PHP:  implode(",", $items);
来源：http://dali.quarkkingdee.top/Article/details/gtjjxkzgna.html

JS:   items.join(",")
来源：http://dali.iojbl.cn/Article/details/gtkzoilpff.html

TS:   items.join(",")
来源：http://dali.0kj1m.cn/Article/details/gtuhsqxagr.html

Java: String.join(",", items)
来源：http://dali.ybcxt.top/Article/details/gtruslvius.html

Go:   strings.Join(items, ",")
来源：http://dali.yj202588.top/Article/details/gtzkpanirl.html

Ruby: items.join(",")
来源：http://dali.feifeiyinyue.top/Article/details/gtdlsqqkjl.html

C#:   string.Join(",", items)
来源：http://dali.zhongyouzk.top/Article/details/gtrvkknnal.html

[E09] 去除所有空白字符
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvkwbayda.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.gaohongyu789.top/Article/details/gtxobxnipi.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.cdnleiting.top/Article/details/gtdiafkgyv.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jqgfzy.top/Article/details/gtysbnhist.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.iojbl.cn/Article/details/gtuzwsztxe.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.dianchejie.cn/Article/details/gteabcnmgq.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.havefunace.top/Article/details/gtzocjtdnh.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.tian-w.cn/Article/details/gtdekceznb.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yonumen.top/Article/details/gtryvkmwwq.html

[E10] 左侧补零 / 定长填充
来源：http://dali.tianlin.xyz/Article/details/gtlwbhalns.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.sweek.top/Article/details/gtnrgkvgvy.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yanxiufei.cn/Article/details/gtdjyreydg.html

JS:   "7".padStart(3, "0")
来源：http://dali.shuidangran.top/Article/details/gthrxgwwna.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhengqikj.top/Article/details/gteiioxeik.html

Java: String.format("%03d", 7)
来源：http://dali.guowangkeji.top/Article/details/gtffriavqb.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.haohaochexian.top/Article/details/gtghpzrdtu.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.vqdsnc.cn/Article/details/gtewktsehz.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gtblitpxjj.html

[E11] 反转字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcxmwklnr.html

Py:   s[::-1]
来源：http://dali.yueranfly.top/Article/details/gtuwjurhrk.html

PHP:  strrev($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfgdonlyo.html

JS:   [...s].reverse().join("")
来源：http://dali.daria6918.cn/Article/details/gtmseqobbt.html

TS:   [...s].reverse().join("")
来源：http://dali.hysaishi.cn/Article/details/gtrzfetrlp.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yangfankeji.com/Article/details/gtbiymvvel.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hywenlv.cn/Article/details/gtfrkhukdj.html

Ruby: s.reverse
来源：http://dali.wangshuangyany.cn/Article/details/gtlhakjrrz.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yvedp.cn/Article/details/gtthkixybv.html

[E12] 统计某字符出现次数
来源：http://dali.sweek.top/Article/details/gtuvqniavf.html

Py:   s.count("a")
来源：http://dali.yanxiufei.cn/Article/details/gtgroikfez.html

PHP:  substr_count($s, "a");
来源：http://dali.sxryk.cn/Article/details/gtlebfnltz.html

JS:   s.split("a").length - 1
来源：http://dali.dashuyun.cn/Article/details/gtfvaqdggb.html

TS:   s.split("a").length - 1
来源：http://dali.zycfv.cn/Article/details/gtmgvgteyu.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.ybcxt.top/Article/details/gtjkokpahd.html

Go:   strings.Count(s, "a")
来源：http://dali.hnqzz.top/Article/details/gtjncolvfm.html

Ruby: s.count("a")
来源：http://dali.9152youxi.cn/Article/details/gtxevbyycc.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhiwuduotai.top/Article/details/gttnpdfzul.html

[E13] 逐字符遍历
来源：http://dali.zhijiandao.cn/Article/details/gtarblwrbi.html

Py:   for ch in s: print(ch)
来源：http://dali.feifeiyinyue.top/Article/details/gtigzviveh.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.chenlongwang.top/Article/details/gtmdtshpsu.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinqigfzy.top/Article/details/gtvotjqcif.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zycfv.cn/Article/details/gtnoypxrki.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.sysykeji.top/Article/details/gthlmykjjr.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yvedp.cn/Article/details/gtntsyncvl.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhoulong.xyz/Article/details/gtacjwxpfn.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.fengsongda.top/Article/details/gtgjqhogch.html

[E14] URL 编码与 Base64
来源：http://dali.jinghuilouyu.cn/Article/details/gtqpvnhuhz.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.bjfxy.top/Article/details/gtzsaudyrn.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.quarkkingdee.top/Article/details/gtcwyalcmk.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.sufxvd.cn/Article/details/gtxthtocjn.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhixingplan.top/Article/details/gttojzfich.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.gaohongyu789.top/Article/details/gtkrczkqnh.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.cashguo.top/Article/details/gtzfxysvoo.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jiagoushi.top/Article/details/gtxcnsrbnf.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.bjfxy.top/Article/details/gtczrjoput.html

[E15] HTML 转义 / 反转义
来源：http://dali.sufxvd.cn/Article/details/gtkzhgnwux.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.guannengcc.top/Article/details/gtrjcytkkf.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.guowangkeji.top/Article/details/gtbuhukdym.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hysaishi.cn/Article/details/gtcudehchl.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.mhx1999.top/Article/details/gtxsisrdfg.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.tian-w.cn/Article/details/gtluvdxoja.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.daxiang520.top/Article/details/gtvqqdrcim.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.havefunace.top/Article/details/gtqfahknbw.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hywenlv.cn/Article/details/gtjkfxkenz.html

[E16] 数字千分位
来源：http://dali.zhoulong.xyz/Article/details/gtwzlagiwe.html

Py:   f"{1234567:,}"
来源：http://dali.zhoulong.xyz/Article/details/gtuvcyqwqi.html

PHP:  number_format(1234567);
来源：http://dali.birdmap.top/Article/details/gtdaekmjiy.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.andypj.xyz/Article/details/gtdqucbpzg.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.hnqzz.top/Article/details/gttzdklgjk.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gtbbnhpocg.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.daria6918.cn/Article/details/gttbsffnfq.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.ivvv.top/Article/details/gtnnmheuho.html

C#:   1234567.ToString("N0")
来源：http://dali.redwolf501.top/Article/details/gtqrxwwhfe.html

[E17] 首字母大写
来源：http://dali.ydzc1.top/Article/details/gtzqkddzfb.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.aibaodan.cn/Article/details/gtinjuaoys.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.chenlongwang.top/Article/details/gtauviqzrf.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.316326.xyz/Article/details/gtrtmgvnuq.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yueranfly.top/Article/details/gtbxcjdavg.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.fzhhl.top/Article/details/gtdlfgijvs.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.0kj1m.cn/Article/details/gtbaywlqpy.html

Ruby: s.capitalize
来源：http://dali.jqgufenzy.top/Article/details/gtvbcnktza.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.sxryk.cn/Article/details/gtsmoiwums.html

[E18] 模板占位符替换
来源：http://dali.316326.xyz/Article/details/gtmfxhxlah.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.guannengcc.top/Article/details/gtkbqjkzuv.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.sufxvd.cn/Article/details/gtxutagqxj.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.redwolf501.top/Article/details/gtuqajkrhn.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.shangyingyoupin.top/Article/details/gtgvexrwpn.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.ivvv.top/Article/details/gtcthlsifd.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.cucudq.cn/Article/details/gtcvydixeg.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.cheryme.top/Article/details/gttthyhtqo.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.birdmap.top/Article/details/gtlzbypmib.html

[E19] 多行文本按行拆分
来源：http://dali.nwbrower.top/Article/details/gtoqcxihcs.html

Py:   s.splitlines()
来源：http://dali.c1oappe.top/Article/details/gtesbltfiy.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.tianlin.xyz/Article/details/gtcjxroomw.html

JS:   s.split(/\r?\n/)
来源：http://dali.jyoumei.cn/Article/details/gtknlsshnj.html

TS:   s.split(/\r?\n/)
来源：http://dali.jyoumei.cn/Article/details/gtejmmdvtj.html

Java: s.lines().toList()
来源：http://dali.smart0.xyz/Article/details/gtpcpjoyaj.html

Go:   strings.Split(s, "\n")
来源：http://dali.cashguo.top/Article/details/gtuwqtfzlj.html

Ruby: s.lines
来源：http://dali.cdnleiting.top/Article/details/gtvayutfgm.html

C#:   s.Split('\n')
来源：http://dali.zycfv.cn/Article/details/gtoxabnxwx.html

[E20] 判断字符串是否为空
来源：http://dali.birdmap.top/Article/details/gtqhrwgmmt.html

Py:   if not s:
来源：http://dali.cqqwz.cn/Article/details/gtmzivtskg.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.cqqwz.cn/Article/details/gtcdbyvtxo.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhongyouzk.top/Article/details/gtlabkaiot.html

TS:   if (s === "") {}
来源：http://dali.hywenlv.cn/Article/details/gtbzduulnn.html

Java: if (s.isEmpty()) {}
来源：http://dali.snrcjt.cn/Article/details/gtfwdwfmfi.html

Go:   if s == "" {}
来源：http://dali.c1oappe.top/Article/details/gtxwtzwtto.html

Ruby: if s.empty?
来源：http://dali.chenjidiqi.icu/Article/details/gtlduzudtz.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.c1oappe.top/Article/details/gtxkpjadmt.html

[E21] 超长截断加省略号
来源：http://dali.xinyue.icu/Article/details/gtgtbulikl.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yuxming.cn/Article/details/gtonqwucwk.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yanxiufei.cn/Article/details/gtxotjcuis.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.smart0.xyz/Article/details/gtphdbvntn.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.guowangkeji.top/Article/details/gthymehrim.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrccpiebl.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.shangyingyoupin.top/Article/details/gtyicxitbm.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhengqikj.top/Article/details/gtnfvxvrsb.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.fzhhl.top/Article/details/gtwzscdxto.html

[E22] 字节长度与字符长度
来源：http://dali.mhx1999.top/Article/details/gtakpagfpe.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.pycfn.com/Article/details/gtvhjfigyk.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.iojbl.cn/Article/details/gtxaecazoq.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.quarkkingdee.top/Article/details/gtvcuzrfyq.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinqigfzy.top/Article/details/gtqcobjiut.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.mhx1999.top/Article/details/gteibcvmec.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.316326.xyz/Article/details/gtvjjniygf.html

Ruby: s.bytesize;  s.length
来源：http://dali.ydzc1.top/Article/details/gthojmauqs.html


<!-- 参考信息 -->