代发 wailian999

PHP:  max($arr);  min($arr);
来源：http://dali.jinqigufen.top/Article/details/gt2ygfofdlf.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.shangyingyoupin.top/Article/details/gt2nipjtbbv.html

TS:   Math.max(...arr);
来源：http://dali.yangfankeji.com/Article/details/gt2rcgoqkep.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.wangdashe.top/Article/details/gt2ecqnhedy.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hnqzz.top/Article/details/gt2vqfkwxer.html

Ruby: arr.max;  arr.min
来源：http://dali.cheryme.top/Article/details/gt2sqcyoyqf.html

C#:   list.Max();  list.Min()
来源：http://dali.yj20258.top/Article/details/gt2xosdqdys.html

[D18] 扁平化嵌套数组
来源：http://dali.andypj.xyz/Article/details/gt2zzizbjgj.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yanxiufei.cn/Article/details/gt2iogdoedv.html

PHP:  array_merge(...$nested);
来源：http://dali.ehwqpu.com/Article/details/gt2oydhxoka.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.pycfn.com/Article/details/gt2ousfkdpl.html

TS:   nested.flat();
来源：http://dali.yueranfly.top/Article/details/gt2ixzfepgt.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ofyzxcki.html

Go:   // 手写双层循环
来源：http://dali.sysykeji.top/Article/details/gt2uqizqrrh.html

Ruby: nested.flatten
来源：http://dali.hammf.cn/Article/details/gt2khptoxmw.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.0kj1m.cn/Article/details/gt2aivbqwar.html

[D19] 按字段分组
来源：http://dali.sxryk.cn/Article/details/gt2ksdlgord.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zycfv.cn/Article/details/gt2uqucbdqx.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.tian-w.cn/Article/details/gt2nncjbqyy.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.316326.xyz/Article/details/gt2ymswzrrk.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.cucudq.cn/Article/details/gt2ldnuzxca.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.pycfn.com/Article/details/gt2zaduqros.html

Go:   // 手写 map[string][]T
来源：http://dali.hysaishi.cn/Article/details/gt2xdvladfd.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yueranfly.top/Article/details/gt2limsviwd.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.ehwqpu.com/Article/details/gt2yyifgcvf.html

[D20] 统计每个元素出现次数
来源：http://dali.aizwys.cn/Article/details/gt2hdlhlvxz.html

Py:   Counter(arr)
来源：http://dali.shuidangran.top/Article/details/gt2zvzwdgpa.html

PHP:  array_count_values($arr);
来源：http://dali.iojbl.cn/Article/details/gt2xularebn.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.316326.xyz/Article/details/gt2xlooejau.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj20258888.top/Article/details/gt2qnfgqmtj.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.shzxlz.cn/Article/details/gt2hgtdzeze.html

Go:   // 手写 map[T]int
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gorlzvvd.html

Ruby: arr.tally
来源：http://dali.sxryk.cn/Article/details/gt2qaklkcbs.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bjkesrnj.html

[D21] 判断是否包含某元素
来源：http://dali.zhiwuduotai.top/Article/details/gt2tocrnpuz.html

Py:   x in arr
来源：http://dali.haohaochexian.top/Article/details/gt2ojdrnuem.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yangfankeji.com/Article/details/gt2hiefufeo.html

JS:   arr.includes(x)
来源：http://dali.yonumen.top/Article/details/gt2rsobvgej.html

TS:   arr.includes(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wfpiniif.html

Java: list.contains(x)
来源：http://dali.hfpthk.cn/Article/details/gt2buujbwbo.html

Go:   slices.Contains(arr, x)
来源：http://dali.nwbrower.top/Article/details/gt2wvqompbh.html

Ruby: arr.include?(x)
来源：http://dali.guannengcc.top/Article/details/gt2pymctfpj.html

C#:   list.Contains(x)
来源：http://dali.yvedp.cn/Article/details/gt2qnrfktlx.html

[D22] 复制数组（避免共享引用）
来源：http://dali.9152youxi.cn/Article/details/gt2fhaazenu.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.daria6918.cn/Article/details/gt2zwvrhvbv.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhongyouzk.top/Article/details/gt2rpvkupwj.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hpwgrgtw.html

TS:   [...arr];
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rhnqfbxg.html

Java: new ArrayList<>(list);
来源：http://dali.tianlin.xyz/Article/details/gt2gvglenoz.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.hammf.cn/Article/details/gt2wuaigswd.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jianghu66.top/Article/details/gt2yuzjflvc.html

C#:   new List<int>(list);
来源：http://dali.yuanzhike.top/Article/details/gt2ivrxrors.html

[D23] reduce 累积计算
来源：http://dali.yuanzhike.top/Article/details/gt2okacltmu.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jinqigfzy.top/Article/details/gt2tqjbgacn.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.chenjidiqi.icu/Article/details/gt2lmnyugzk.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.c1oappe.top/Article/details/gt2evjtgylh.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.redwolf501.top/Article/details/gt2zmitmjkj.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.pycfn.com/Article/details/gt2ryxqbvby.html

Go:   // 手写循环
来源：http://dali.zhixingplan.top/Article/details/gt2rpgrrysw.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jlsjyb.cn/Article/details/gt2indqybpl.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.snrcjt.cn/Article/details/gt2lywoksem.html

[D24] 字典 / Map 基本操作
来源：http://dali.nwbrower.top/Article/details/gt2xmdwfwpg.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.cheryme.top/Article/details/gt2aayoprta.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jianghu66.top/Article/details/gt2bqwfznsi.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yonumen.top/Article/details/gt2peotitol.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.xinyue.icu/Article/details/gt2ttrxvpde.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.dianchejie.cn/Article/details/gt2rxpkokob.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dgfvwgmz.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.chenjidiqi.icu/Article/details/gt2kqxceepj.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.hongshengwenyu.top/Article/details/gt2hqzoxxkp.html

[D25] Set 集合去重与交并差
来源：http://dali.ppjwa.cn/Article/details/gt2xkwoqzxd.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.cheryme.top/Article/details/gt2cdphisoh.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.meibo888.top/Article/details/gt2rdjwcvuc.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.ivvv.top/Article/details/gt2atvjgzti.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yj20258.top/Article/details/gt2ykplcxcl.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.shzxlz.cn/Article/details/gt2mqbyfioi.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.nwbrower.top/Article/details/gt2vczxwcvs.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhixingplan.top/Article/details/gt2zmmrbkro.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.cdnleiting.top/Article/details/gt2fwnntnaw.html

[D26] 数组转字符串
来源：http://dali.bjfxy.top/Article/details/gt2bvqdztkx.html

Py:   ", ".join(map(str, arr))
来源：http://dali.sxryk.cn/Article/details/gt2iabuszqi.html

PHP:  implode(", ", $arr);
来源：http://dali.wangshuangyany.cn/Article/details/gt2mjwrazxu.html

JS:   arr.join(", ")
来源：http://dali.ivvv.top/Article/details/gt2tapjkbjy.html

TS:   arr.join(", ")
来源：http://dali.vqdsnc.cn/Article/details/gt2zgtradwq.html

Java: String.join(", ", list)
来源：http://dali.guowangkeji.top/Article/details/gt2ibexnemk.html

Go:   strings.Join(strs, ", ")
来源：http://dali.ybcxt.top/Article/details/gt2aamkokwg.html

Ruby: arr.join(", ")
来源：http://dali.chenjidiqi.icu/Article/details/gt2uszfrzqi.html

C#:   string.Join(", ", list)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2crybgdov.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2nmsiorlv.html

E. 字符串处理
来源：http://dali.zhoulong.xyz/Article/details/gt2wlbghkzq.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2bskfbfpj.html

[E01] 拼接字符串
来源：http://dali.yuanzhike.top/Article/details/gt2jubjwuuq.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.andypj.xyz/Article/details/gt2daiplqlu.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.ivvv.top/Article/details/gt2vnnlhccd.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xinyue.icu/Article/details/gt2knioiogk.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cucudq.cn/Article/details/gt2ktfoueqx.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.pengpengdd.cyou/Article/details/gt2afrettel.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.meibo888.top/Article/details/gt2tbivvpod.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yanxiufei.cn/Article/details/gt2ebwecvvz.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.gotoacloud.top/Article/details/gt2jvsrqcql.html

[E02] 重复字符串
来源：http://dali.wangshuangyany.cn/Article/details/gt2ypbyoiey.html

Py:   "ab" * 3
来源：http://dali.yanxiufei.cn/Article/details/gt2qfhtmpvd.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yuxming.cn/Article/details/gt2ndiexkmh.html

JS:   "ab".repeat(3)
来源：http://dali.jlsjyb.cn/Article/details/gt2ztoczntv.html

TS:   "ab".repeat(3)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ajcoyvyf.html

Java: "ab".repeat(3)
来源：http://dali.pycfn.com/Article/details/gt2vrqwutzf.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.9152youxi.cn/Article/details/gt2cxgbdfqh.html

Ruby: "ab" * 3
来源：http://dali.sxryk.cn/Article/details/gt2jbhyvlil.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.wangshuangyany.cn/Article/details/gt2jhablnaz.html

[E03] 截取子串
来源：http://dali.hnqzz.top/Article/details/gt2iewfmgvj.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.ivvv.top/Article/details/gt2zjwlwzkn.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.0kj1m.cn/Article/details/gt2hqqwvjpq.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yanxiufei.cn/Article/details/gt2nldwrfnt.html

TS:   s.slice(1, 4)
来源：http://dali.aizwys.cn/Article/details/gt2lhgenntz.html

Java: s.substring(1, 4)
来源：http://dali.daxiang520.top/Article/details/gt2tlepnbxf.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhoulong.xyz/Article/details/gt2ekqulzuf.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vbekdeys.html

C#:   s.Substring(1, 3)
来源：http://dali.xuetiantiany.cn/Article/details/gt2eqmuoqhx.html

[E04] 查找子串位置
来源：http://dali.guowangkeji.top/Article/details/gt2vmfjjstm.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yonumen.top/Article/details/gt2qnfqzhob.html

PHP:  strpos($s, "x");
来源：http://dali.chenlongwang.top/Article/details/gt2cjfrczry.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zdqjudy.top/Article/details/gt2aeagpyvf.html

TS:   s.indexOf("x")
来源：http://dali.feifeiyinyue.top/Article/details/gt2bsgpltzq.html

Java: s.indexOf("x")
来源：http://dali.sweek.top/Article/details/gt2qllpfzhr.html

Go:   strings.Index(s, "x")
来源：http://dali.zhongyouzk.top/Article/details/gt2bxmjmeuy.html

Ruby: s.index("x")
来源：http://dali.hywenlv.cn/Article/details/gt2hxrfogxp.html

C#:   s.IndexOf("x")
来源：http://dali.cheryme.top/Article/details/gt2bjdowuez.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.nanxinkj.top/Article/details/gt2bmcqcblq.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.chenlongwang.top/Article/details/gt2lscgjmqx.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.cheryme.top/Article/details/gt2zpybiswz.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.pengpengdd.cyou/Article/details/gt2ezrodwxy.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.0kj1m.cn/Article/details/gt2amelkyde.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xuanzx.com/Article/details/gt2qxzsielw.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhengqikj.top/Article/details/gt2syiydyjx.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.9152youxi.cn/Article/details/gt2aauzarqm.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.birdmap.top/Article/details/gt2mzflcmhe.html

[E06] 替换子串
来源：http://dali.guannengcc.top/Article/details/gt2asghorzt.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.chenzaomai.com/Article/details/gt2fkerbwcw.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2repwzvuf.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ydzc1.top/Article/details/gt2nyfptvsi.html

TS:   s.replaceAll("a", "b")
来源：http://dali.gogol.net.cn/Article/details/gt2vfdylfhu.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cdnleiting.top/Article/details/gt2erpepcsf.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yvedp.cn/Article/details/gt2koxhbqnq.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.cheryme.top/Article/details/gt2zafvmfbr.html

C#:   s.Replace("a", "b")
来源：http://dali.shuidangran.top/Article/details/gt2ttlxbziu.html

[E07] 按分隔符拆分
来源：http://dali.yj20258.top/Article/details/gt2zuieaeow.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.cdnleiting.top/Article/details/gt2nmtfyasm.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.bjfxy.top/Article/details/gt2oeoyxelb.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yuxming.cn/Article/details/gt2hdalcxjh.html

TS:   s.split(",")
来源：http://dali.yanxiufei.cn/Article/details/gt2pmvvogqf.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.xinyue.icu/Article/details/gt2lmfzxqlm.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.xinyue.icu/Article/details/gt2wowadedm.html

Ruby: s.split(",");  s.split
来源：http://dali.hammf.cn/Article/details/gt2bhtrskog.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.iojbl.cn/Article/details/gt2ypaqnbpz.html

[E08] 数组按分隔符合并
来源：http://dali.fzhhl.top/Article/details/gt2wvdfpeky.html

Py:   ",".join(items)
来源：http://dali.fzhhl.top/Article/details/gt2ihtydick.html

PHP:  implode(",", $items);
来源：http://dali.nwbrower.top/Article/details/gt2jafbnsto.html

JS:   items.join(",")
来源：http://dali.kuanghao11.cn/Article/details/gt2geeupxyh.html

TS:   items.join(",")
来源：http://dali.jiagoushi.top/Article/details/gt2pwooqwru.html

Java: String.join(",", items)
来源：http://dali.jianghu66.top/Article/details/gt2dosaateo.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2ktouytnv.html

Ruby: items.join(",")
来源：http://dali.yangfankeji.com/Article/details/gt2yebbjbvb.html

C#:   string.Join(",", items)
来源：http://dali.zhixingplan.top/Article/details/gt2dmkfrfwo.html

[E09] 去除所有空白字符
来源：http://dali.cucudq.cn/Article/details/gt2nqweggeo.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.aizwys.cn/Article/details/gt2rfhevwnl.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.iojbl.cn/Article/details/gt2hxteebho.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.feifeiyinyue.top/Article/details/gt2hunmfzae.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.dashuyun.cn/Article/details/gt2japcfycz.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.aizwys.cn/Article/details/gt2mrjngqqk.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.sufxvd.cn/Article/details/gt2eeeeybkz.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.andypj.xyz/Article/details/gt2zdvhspik.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eugvmhly.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhoulong.xyz/Article/details/gt2zmfguqpd.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rpwhfxqo.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yueranfly.top/Article/details/gt2lwwlnvjs.html

JS:   "7".padStart(3, "0")
来源：http://dali.shangyingyoupin.top/Article/details/gt2hqhoqify.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhengqikj.top/Article/details/gt2rqtblmoz.html

Java: String.format("%03d", 7)
来源：http://dali.xziqi.cn/Article/details/gt2lazyppwz.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jinqigufen.top/Article/details/gt2dumhinor.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.316326.xyz/Article/details/gt2nwwggzrk.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.daria6918.cn/Article/details/gt2egsgxamg.html

[E11] 反转字符串
来源：http://dali.yvedp.cn/Article/details/gt2vdkythpw.html

Py:   s[::-1]
来源：http://dali.dashuyun.cn/Article/details/gt2mcqsamok.html

PHP:  strrev($s);
来源：http://dali.nanxuanxn.top/Article/details/gt2lbmdeuot.html

JS:   [...s].reverse().join("")
来源：http://dali.pycfn.com/Article/details/gt2xiofktfm.html

TS:   [...s].reverse().join("")
来源：http://dali.ivvv.top/Article/details/gt2cmltqgif.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hnqzz.top/Article/details/gt2mdoqeoal.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.tanke756.top/Article/details/gt2zcompuax.html

Ruby: s.reverse
来源：http://dali.sweek.top/Article/details/gt2lwrohxnv.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yueranfly.top/Article/details/gt2hvkxqfez.html

[E12] 统计某字符出现次数
来源：http://dali.yangfankeji.com/Article/details/gt2tuzucxbz.html

Py:   s.count("a")
来源：http://dali.meibo888.top/Article/details/gt2yxmhehcy.html

PHP:  substr_count($s, "a");
来源：http://dali.zhengqikj.top/Article/details/gt2jjaautnp.html

JS:   s.split("a").length - 1
来源：http://dali.yuxming.cn/Article/details/gt2emeubbgv.html

TS:   s.split("a").length - 1
来源：http://dali.gotoacloud.top/Article/details/gt2szfqgvyn.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.0kj1m.cn/Article/details/gt2ulszimxi.html

Go:   strings.Count(s, "a")
来源：http://dali.daxiang520.top/Article/details/gt2wdgwisle.html

Ruby: s.count("a")
来源：http://dali.zycfv.cn/Article/details/gt2wrsifeca.html

C#:   s.Count(c => c == 'a')
来源：http://dali.shzxlz.cn/Article/details/gt2yaxxqmmb.html

[E13] 逐字符遍历
来源：http://dali.havefunace.top/Article/details/gt2xpggtyut.html

Py:   for ch in s: print(ch)
来源：http://dali.jianghu66.top/Article/details/gt2weyfbjgy.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tmankoem.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.aizwys.cn/Article/details/gt2anfjaydg.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dxwiupha.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.pycfn.com/Article/details/gt2azegsudy.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zzzxpxqz.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.bjfxy.top/Article/details/gt2szhydvtr.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jqgfzy.top/Article/details/gt2hujgkuhj.html

[E14] URL 编码与 Base64
来源：http://dali.c1oappe.top/Article/details/gt2tbhceltr.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.wangdashe.top/Article/details/gt2lmdrkvyo.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hnqzz.top/Article/details/gt2sklcwajy.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.shuidangran.top/Article/details/gt2hipjaggy.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhengqikj.top/Article/details/gt2oojqkurn.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mqvlaggx.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.gaohongyu789.top/Article/details/gt2blpibrub.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dnjokuyt.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.gzhubu.top/Article/details/gt2qxlraayc.html

[E15] HTML 转义 / 反转义
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rhtplbef.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.0kj1m.cn/Article/details/gt2evlqjyvr.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.chenzaomai.com/Article/details/gt2lcaucaxe.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dsjlyokq.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jlsjyb.cn/Article/details/gt2oggpumuo.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.wangshuangyany.cn/Article/details/gt2tlshvaee.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.andypj.xyz/Article/details/gt2bpoyuide.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yonumen.top/Article/details/gt2rbdwisxv.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.wangdashe.top/Article/details/gt2teadmquf.html

[E16] 数字千分位
来源：http://dali.daria6918.cn/Article/details/gt2mmaaawva.html

Py:   f"{1234567:,}"
来源：http://dali.redwolf501.top/Article/details/gt2jtvmvekl.html

PHP:  number_format(1234567);
来源：http://dali.hfpthk.cn/Article/details/gt2vfimaqnd.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2bwaggaiv.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.svipenyu.cn/Article/details/gt2qiqiiafx.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yueranfly.top/Article/details/gt2ywjdftnq.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.fzhhl.top/Article/details/gt2vgajtxfi.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.iojbl.cn/Article/details/gt2cfsvvesy.html

C#:   1234567.ToString("N0")
来源：http://dali.shzxlz.cn/Article/details/gt2bhjvqmes.html

[E17] 首字母大写
来源：http://dali.hysaishi.cn/Article/details/gt2zcreinxi.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.nanxuanxn.top/Article/details/gt2tanwetxy.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.quarkkingdee.top/Article/details/gt2zqikrdry.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ratsvwgg.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.smart0.xyz/Article/details/gt2qobewgwb.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.gaohongyu789.top/Article/details/gt2shrlkfcx.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.aizwys.cn/Article/details/gt2jtmviryf.html

Ruby: s.capitalize
来源：http://dali.sysykeji.top/Article/details/gt2qnzkulgt.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.dashuyun.cn/Article/details/gt2zcklwwuj.html

[E18] 模板占位符替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oxtovfam.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.wangshuangyany.cn/Article/details/gt2cusfdhpg.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yuxming.cn/Article/details/gt2hocifnsk.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.ivvv.top/Article/details/gt2nwqvqdas.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.havefunace.top/Article/details/gt2kjkanomv.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jianghu66.top/Article/details/gt2inkatnmz.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.tianlin.xyz/Article/details/gt2pgiiqoeu.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.tanke756.top/Article/details/gt2stdhpqli.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.chenlongwang.top/Article/details/gt2auzvmllz.html

[E19] 多行文本按行拆分
来源：http://dali.dashuyun.cn/Article/details/gt2wwgmrtpg.html

Py:   s.splitlines()
来源：http://dali.hfpthk.cn/Article/details/gt2eldalqgm.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.sweek.top/Article/details/gt2idtxbexz.html

JS:   s.split(/\r?\n/)
来源：http://dali.jyoumei.cn/Article/details/gt2btlgjptq.html

TS:   s.split(/\r?\n/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vcilypxw.html

Java: s.lines().toList()
来源：http://dali.ppjwa.cn/Article/details/gt2jxzeiiuu.html

Go:   strings.Split(s, "\n")
来源：http://dali.vqdsnc.cn/Article/details/gt2xgsigvan.html

Ruby: s.lines
来源：http://dali.hnqzz.top/Article/details/gt2elsyaetm.html

C#:   s.Split('\n')
来源：http://dali.zhiwuduotai.top/Article/details/gt2uxmwxdgz.html

[E20] 判断字符串是否为空
来源：http://dali.vqdsnc.cn/Article/details/gt2pkfchyjf.html

Py:   if not s:
来源：http://dali.xinyue.icu/Article/details/gt2bogzzhpr.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.snrcjt.cn/Article/details/gt2enwvszgg.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.pycfn.com/Article/details/gt2oexeigdi.html

TS:   if (s === "") {}
来源：http://dali.0kj1m.cn/Article/details/gt2tametuka.html

Java: if (s.isEmpty()) {}
来源：http://dali.nanxinkj.top/Article/details/gt2srebzmep.html

Go:   if s == "" {}
来源：http://dali.hammf.cn/Article/details/gt2rtpziltp.html

Ruby: if s.empty?
来源：http://dali.zycfv.cn/Article/details/gt2mopfsaou.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.daxiang520.top/Article/details/gt2qtvyhjqs.html

[E21] 超长截断加省略号
来源：http://dali.gogol.net.cn/Article/details/gt2axzocgna.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.haohaochexian.top/Article/details/gt2umlwkrvu.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hysaishi.cn/Article/details/gt2kcspovdj.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cqqwz.cn/Article/details/gt2twnwrmhr.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yueranfly.top/Article/details/gt2tkhhpqbd.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.xuanzx.com/Article/details/gt2xruekdqx.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xylfe.cn/Article/details/gt2ksnmgobr.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.cheryme.top/Article/details/gt2phvqtqzo.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.daxiang520.top/Article/details/gt2dhhohkmh.html

[E22] 字节长度与字符长度
来源：http://dali.zhongyouzk.top/Article/details/gt2vtdltldc.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2hfcioxnc.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.dashuyun.cn/Article/details/gt2eybpxwfr.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.chenzaomai.com/Article/details/gt2alsxslmb.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jqgfzy.top/Article/details/gt2oostbgzz.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.tianlin.xyz/Article/details/gt2hvvnlowd.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yueranfly.top/Article/details/gt2sodkonhd.html

Ruby: s.bytesize;  s.length
来源：http://dali.cucudq.cn/Article/details/gt2totrdpiy.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ivvv.top/Article/details/gt2vwpcalgw.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sartbnso.html

F. 文件与目录
来源：http://dali.tanke756.top/Article/details/gt2lilfayuv.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2dkdvnrqe.html

[F01] 读取整个文件
来源：http://dali.sufxvd.cn/Article/details/gt2rtnouxrg.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.vqdsnc.cn/Article/details/gt2ijjonngd.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xziqi.cn/Article/details/gt2dnyckgnl.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yanxiufei.cn/Article/details/gt2iwytrgsl.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.ivvv.top/Article/details/gt2ltyqrnpz.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yj202588.top/Article/details/gt2xxgfzdfi.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.cdnleiting.top/Article/details/gt2bhkbhjos.html

Ruby: File.read("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2epyczsjk.html


<!-- 参考信息 -->