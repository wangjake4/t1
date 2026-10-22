代发 wailian999

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yuanzhike.top/Article/details/gt2wmyhbuzd.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ehwqpu.com/Article/details/gt2sahdtkmj.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jyoumei.cn/Article/details/gt2vphexrqg.html

Go:   // 手写循环累加
来源：http://dali.yuxming.cn/Article/details/gt2uyrxfmfn.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hongshengwenyu.top/Article/details/gt2aqdrdtou.html

C#:   list.Sum();  list.Average()
来源：http://dali.mhx1999.top/Article/details/gt2pcfdrfzq.html

[D17] 最大值与最小值
来源：http://dali.jiagoushi.top/Article/details/gt2izpzsvvf.html

Py:   max(arr);  min(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gt2tbhxjlki.html

PHP:  max($arr);  min($arr);
来源：http://dali.fzhhl.top/Article/details/gt2kwwvxtzx.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.cheryme.top/Article/details/gt2nbdglube.html

TS:   Math.max(...arr);
来源：http://dali.yuanzhike.top/Article/details/gt2ooghotis.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhiwuduotai.top/Article/details/gt2uqvyfywg.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jlsjyb.cn/Article/details/gt2ikgjxxjn.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2lkrcglcj.html

C#:   list.Max();  list.Min()
来源：http://dali.havefunace.top/Article/details/gt2yxcazfuc.html

[D18] 扁平化嵌套数组
来源：http://dali.gaohongyu789.top/Article/details/gt2nvbyslad.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.316326.xyz/Article/details/gt2zcxnsjds.html

PHP:  array_merge(...$nested);
来源：http://dali.mhx1999.top/Article/details/gt2evaejzor.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.gzhubu.top/Article/details/gt2ldjwvdqy.html

TS:   nested.flat();
来源：http://dali.guannengcc.top/Article/details/gt2usgwqrcb.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yueranfly.top/Article/details/gt2fxgxirho.html

Go:   // 手写双层循环
来源：http://dali.mhx1999.top/Article/details/gt2jvqhhlmg.html

Ruby: nested.flatten
来源：http://dali.daxiang520.top/Article/details/gt2acbtxbxa.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.tanke756.top/Article/details/gt2ougnatkr.html

[D19] 按字段分组
来源：http://dali.chenzaomai.com/Article/details/gt2zmgbutrq.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.cashguo.top/Article/details/gt2ptwuxnoq.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.xuetiantiany.cn/Article/details/gt2wqwpxyyo.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bvszeveh.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jyoumei.cn/Article/details/gt2jwbutrrl.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.guannengcc.top/Article/details/gt2ptvdotcq.html

Go:   // 手写 map[string][]T
来源：http://dali.svipenyu.cn/Article/details/gt2figyzupt.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.dianchejie.cn/Article/details/gt2bkopclsk.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.pengpengdd.cyou/Article/details/gt2retsfbex.html

[D20] 统计每个元素出现次数
来源：http://dali.jiagoushi.top/Article/details/gt2qdaprowr.html

Py:   Counter(arr)
来源：http://dali.ybcxt.top/Article/details/gt2xnlfuuaq.html

PHP:  array_count_values($arr);
来源：http://dali.jqgfzy.top/Article/details/gt2xuikxfhm.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.feifeiyinyue.top/Article/details/gt2kybvqeka.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.tianlin.xyz/Article/details/gt2fkeyjgjn.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.ivvv.top/Article/details/gt2xyjlyosf.html

Go:   // 手写 map[T]int
来源：http://dali.gogol.net.cn/Article/details/gt2lsnsiyhi.html

Ruby: arr.tally
来源：http://dali.shangyingyoupin.top/Article/details/gt2qifmdups.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.aibaodan.cn/Article/details/gt2phtqbfsa.html

[D21] 判断是否包含某元素
来源：http://dali.hnxiangtu.top/Article/details/gt2ufordlbb.html

Py:   x in arr
来源：http://dali.yanxiufei.cn/Article/details/gt2mphhuymz.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jyoumei.cn/Article/details/gt2wbnvhxga.html

JS:   arr.includes(x)
来源：http://dali.9152youxi.cn/Article/details/gt2uuhktfow.html

TS:   arr.includes(x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ynersruz.html

Java: list.contains(x)
来源：http://dali.tianlin.xyz/Article/details/gt2knjixref.html

Go:   slices.Contains(arr, x)
来源：http://dali.meibo888.top/Article/details/gt2hlrwdsyp.html

Ruby: arr.include?(x)
来源：http://dali.sufxvd.cn/Article/details/gt2gxagvjjh.html

C#:   list.Contains(x)
来源：http://dali.ehwqpu.com/Article/details/gt2wtdgdyqh.html

[D22] 复制数组（避免共享引用）
来源：http://dali.xuanzx.com/Article/details/gt2pyxzovdx.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ianuercn.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhongyouzk.top/Article/details/gt2ajtxzwfy.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.cheryme.top/Article/details/gt2guheruli.html

TS:   [...arr];
来源：http://dali.jyoumei.cn/Article/details/gt2ffqrrqlc.html

Java: new ArrayList<>(list);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fddsxkzg.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jianghu66.top/Article/details/gt2ohguutkr.html

Ruby: arr.dup;  arr.clone
来源：http://dali.xuanzx.com/Article/details/gt2engitomp.html

C#:   new List<int>(list);
来源：http://dali.dashuyun.cn/Article/details/gt2ntnauqsh.html

[D23] reduce 累积计算
来源：http://dali.iojbl.cn/Article/details/gt2uurlbqra.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.snrcjt.cn/Article/details/gt2fiedfssn.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.wangdashe.top/Article/details/gt2akhmspvh.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhongyouzk.top/Article/details/gt2jmmiqxeu.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jqgfzy.top/Article/details/gt2qqxbcjdf.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.ydzc1.top/Article/details/gt2urywzucf.html

Go:   // 手写循环
来源：http://dali.meibo888.top/Article/details/gt2cozmczlk.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.nwbrower.top/Article/details/gt2ldbyxuas.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.guowangkeji.top/Article/details/gt2cjjxlwts.html

[D24] 字典 / Map 基本操作
来源：http://dali.ydzc1.top/Article/details/gt2lljtgebt.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.sweek.top/Article/details/gt2wrqkzgfe.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.chenjidiqi.icu/Article/details/gt2yjppdklc.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.havefunace.top/Article/details/gt2cvpflwqy.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yj20258888.top/Article/details/gt2agukvqag.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.birdmap.top/Article/details/gt2mqbvdegk.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhoulong.xyz/Article/details/gt2mmizyzuv.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.hongshengwenyu.top/Article/details/gt2urmgjavu.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.dianchejie.cn/Article/details/gt2jbrdbrcy.html

[D25] Set 集合去重与交并差
来源：http://dali.fengsongda.top/Article/details/gt2icxdetrn.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jinqigfzy.top/Article/details/gt2ctbnkfiv.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yangfankeji.com/Article/details/gt2sxfaxhnw.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.cheryme.top/Article/details/gt2moylftht.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.xziqi.cn/Article/details/gt2chhjqhbs.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.cheryme.top/Article/details/gt2ibhazeiv.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jlsjyb.cn/Article/details/gt2whugpnma.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fqqbsksf.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.xinyue.icu/Article/details/gt2ygbtqpzt.html

[D26] 数组转字符串
来源：http://dali.haohaochexian.top/Article/details/gt2necsbqvp.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tadzwdoy.html

PHP:  implode(", ", $arr);
来源：http://dali.jqgfzy.top/Article/details/gt2mqmutpqw.html

JS:   arr.join(", ")
来源：http://dali.jiagoushi.top/Article/details/gt2utedmacw.html

TS:   arr.join(", ")
来源：http://dali.yanxiufei.cn/Article/details/gt2yrehkjed.html

Java: String.join(", ", list)
来源：http://dali.yuanzhike.top/Article/details/gt2jleylfps.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zycfv.cn/Article/details/gt2autoohjg.html

Ruby: arr.join(", ")
来源：http://dali.ybcxt.top/Article/details/gt2bfsraamb.html

C#:   string.Join(", ", list)
来源：http://dali.snrcjt.cn/Article/details/gt2tngasnmo.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2gyortgip.html

E. 字符串处理
来源：http://dali.yj20258.top/Article/details/gt2odzetjro.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2wnblgxlq.html

[E01] 拼接字符串
来源：http://dali.tianlin.xyz/Article/details/gt2zrwmplge.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.fzhhl.top/Article/details/gt2fvtsmvlu.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.xylfe.cn/Article/details/gt2ddnomkdy.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.sxryk.cn/Article/details/gt2edjyoleb.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gzhubu.top/Article/details/gt2ermnnrlc.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hysaishi.cn/Article/details/gt2rknqobnt.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.dianchejie.cn/Article/details/gt2vtvwpuub.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.gzhubu.top/Article/details/gt2haofsago.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.guowangkeji.top/Article/details/gt2uhydulsm.html

[E02] 重复字符串
来源：http://dali.nwbrower.top/Article/details/gt2zepsubfl.html

Py:   "ab" * 3
来源：http://dali.jqgufenzy.top/Article/details/gt2ohwdhtwr.html

PHP:  str_repeat("ab", 3);
来源：http://dali.chenjidiqi.icu/Article/details/gt2afzrxmnn.html

JS:   "ab".repeat(3)
来源：http://dali.jqgufenzy.top/Article/details/gt2dcphlbaz.html

TS:   "ab".repeat(3)
来源：http://dali.xinyue.icu/Article/details/gt2qyrjgsxh.html

Java: "ab".repeat(3)
来源：http://dali.vqdsnc.cn/Article/details/gt2ppqgysxs.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.bjfxy.top/Article/details/gt2olpdovms.html

Ruby: "ab" * 3
来源：http://dali.yj20258.top/Article/details/gt2vhatuoxe.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhengqikj.top/Article/details/gt2qafbtsrf.html

[E03] 截取子串
来源：http://dali.gotoacloud.top/Article/details/gt2xvwlcnqb.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.smart0.xyz/Article/details/gt2qdfccbup.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.cucudq.cn/Article/details/gt2lehavvoh.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.mhx1999.top/Article/details/gt2gwihvjry.html

TS:   s.slice(1, 4)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bcupdkne.html

Java: s.substring(1, 4)
来源：http://dali.bjfxy.top/Article/details/gt2lklztfov.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.fzhhl.top/Article/details/gt2dczbgvfh.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.xylfe.cn/Article/details/gt2kjiexevr.html

C#:   s.Substring(1, 3)
来源：http://dali.gaohongyu789.top/Article/details/gt2dkvqssfz.html

[E04] 查找子串位置
来源：http://dali.xuanzx.com/Article/details/gt2psiwqxku.html

Py:   s.find("x");  s.index("x")
来源：http://dali.chenzaomai.com/Article/details/gt2wbgmhizc.html

PHP:  strpos($s, "x");
来源：http://dali.jqgufenzy.top/Article/details/gt2fnhptlwp.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.hnqzz.top/Article/details/gt2vionhknd.html

TS:   s.indexOf("x")
来源：http://dali.yuanzhike.top/Article/details/gt2vibbpajz.html

Java: s.indexOf("x")
来源：http://dali.0kj1m.cn/Article/details/gt2szuihfha.html

Go:   strings.Index(s, "x")
来源：http://dali.jiagoushi.top/Article/details/gt2xwkonghc.html

Ruby: s.index("x")
来源：http://dali.xziqi.cn/Article/details/gt2semnilbg.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2szsxfcxy.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.sysykeji.top/Article/details/gt2kaqkdzwl.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.shangyingyoupin.top/Article/details/gt2amgbiylz.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.meibo888.top/Article/details/gt2lbmhhxlx.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ybcxt.top/Article/details/gt2vjjsewgn.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2lfkqvtdz.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jqgufenzy.top/Article/details/gt2zauowzyj.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.iojbl.cn/Article/details/gt2mmznkrlf.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yongpay.top/Article/details/gt2xtbliisv.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.sxryk.cn/Article/details/gt2ajvgvagu.html

[E06] 替换子串
来源：http://dali.shzxlz.cn/Article/details/gt2qvbzmhmp.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.cucudq.cn/Article/details/gt2kfzhbvnt.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.feifeiyinyue.top/Article/details/gt2eqpllcgc.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.feifeiyinyue.top/Article/details/gt2sylgnibh.html

TS:   s.replaceAll("a", "b")
来源：http://dali.smart0.xyz/Article/details/gt2cfxfsokq.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.snrcjt.cn/Article/details/gt2awnrwdta.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.dianchejie.cn/Article/details/gt2grjetywr.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jyoumei.cn/Article/details/gt2vsfoimog.html

C#:   s.Replace("a", "b")
来源：http://dali.mhx1999.top/Article/details/gt2pgtkfbkx.html

[E07] 按分隔符拆分
来源：http://dali.jianghu66.top/Article/details/gt2mofbxyin.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yonumen.top/Article/details/gt2ghjxrnfe.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.xylfe.cn/Article/details/gt2hmlafpff.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.guowangkeji.top/Article/details/gt2ilosbchl.html

TS:   s.split(",")
来源：http://dali.shzxlz.cn/Article/details/gt2vwjavseg.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.ehwqpu.com/Article/details/gt2gfjnlkrs.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.fzhhl.top/Article/details/gt2hrfzxibd.html

Ruby: s.split(",");  s.split
来源：http://dali.andypj.xyz/Article/details/gt2hcdouqhr.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.sufxvd.cn/Article/details/gt2djkkeqlw.html

[E08] 数组按分隔符合并
来源：http://dali.sweek.top/Article/details/gt2ygvhnqzj.html

Py:   ",".join(items)
来源：http://dali.snrcjt.cn/Article/details/gt2lhvjzsds.html

PHP:  implode(",", $items);
来源：http://dali.fengsongda.top/Article/details/gt2rixgxldh.html

JS:   items.join(",")
来源：http://dali.ehwqpu.com/Article/details/gt2puzshuwx.html

TS:   items.join(",")
来源：http://dali.guannengcc.top/Article/details/gt2gsuaemwu.html

Java: String.join(",", items)
来源：http://dali.nwbrower.top/Article/details/gt2julpjjyp.html

Go:   strings.Join(items, ",")
来源：http://dali.nwbrower.top/Article/details/gt2rvpouljq.html

Ruby: items.join(",")
来源：http://dali.havefunace.top/Article/details/gt2hyxsflzt.html

C#:   string.Join(",", items)
来源：http://dali.meibo888.top/Article/details/gt2ojclyrov.html

[E09] 去除所有空白字符
来源：http://dali.gzhubu.top/Article/details/gt2oqmeckpj.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.aizwys.cn/Article/details/gt2iznpschc.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.pengpengdd.cyou/Article/details/gt2eaahaifr.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yj202588.top/Article/details/gt2nvyemrhx.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.shzxlz.cn/Article/details/gt2iygogiyx.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.ivvv.top/Article/details/gt2aegfqjwl.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yanxiufei.cn/Article/details/gt2mdyekxmt.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.sweek.top/Article/details/gt2vwnubglo.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.svipenyu.cn/Article/details/gt2aviawqop.html

[E10] 左侧补零 / 定长填充
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ipmhjtdu.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.gogol.net.cn/Article/details/gt2vlrzyyiz.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.xuanzx.com/Article/details/gt2kdazxjkm.html

JS:   "7".padStart(3, "0")
来源：http://dali.yuxming.cn/Article/details/gt2wkfyucui.html

TS:   "7".padStart(3, "0")
来源：http://dali.zdqjudy.top/Article/details/gt2tgyobtrr.html

Java: String.format("%03d", 7)
来源：http://dali.xylfe.cn/Article/details/gt2jwlwltns.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.bjfxy.top/Article/details/gt2fzmbpvzm.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hywenlv.cn/Article/details/gt2wjezdyra.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.ehwqpu.com/Article/details/gt2xnocuqrq.html

[E11] 反转字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2boyvmnmn.html

Py:   s[::-1]
来源：http://dali.nanxuanxn.top/Article/details/gt2ndjwkhwl.html

PHP:  strrev($s);
来源：http://dali.tian-w.cn/Article/details/gt2dgfladlo.html

JS:   [...s].reverse().join("")
来源：http://dali.zhoulong.xyz/Article/details/gt2acnluhfl.html

TS:   [...s].reverse().join("")
来源：http://dali.hnxiangtu.top/Article/details/gt2vuxcjpsh.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.xuetiantiany.cn/Article/details/gt2qgdogbpl.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yxbvgjez.html

Ruby: s.reverse
来源：http://dali.zhiwuduotai.top/Article/details/gt2raeurtnj.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yuxming.cn/Article/details/gt2mppbdqju.html

[E12] 统计某字符出现次数
来源：http://dali.gzhubu.top/Article/details/gt2xmwneegy.html

Py:   s.count("a")
来源：http://dali.ppjwa.cn/Article/details/gt2ywbmkkqn.html

PHP:  substr_count($s, "a");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ewublbvn.html

JS:   s.split("a").length - 1
来源：http://dali.tianlin.xyz/Article/details/gt2edofuuzn.html

TS:   s.split("a").length - 1
来源：http://dali.xinyue.icu/Article/details/gt2ksbgqzyo.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.wangshuangyany.cn/Article/details/gt2kyuxipkx.html

Go:   strings.Count(s, "a")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rueptzkj.html

Ruby: s.count("a")
来源：http://dali.fengsongda.top/Article/details/gt2sraqxycc.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yonumen.top/Article/details/gt2qmkganvv.html

[E13] 逐字符遍历
来源：http://dali.hywenlv.cn/Article/details/gt2ryuojykd.html

Py:   for ch in s: print(ch)
来源：http://dali.yj20258888.top/Article/details/gt2irpjzzyr.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.shzxlz.cn/Article/details/gt2wrkxteko.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.redwolf501.top/Article/details/gt2pdkasqug.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.svipenyu.cn/Article/details/gt2wihtgwkd.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.nanxinkj.top/Article/details/gt2yazudqis.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.wangdashe.top/Article/details/gt2pmaymbrc.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cqemiqmm.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.mhx1999.top/Article/details/gt2eymhtxrc.html

[E14] URL 编码与 Base64
来源：http://dali.jqgufenzy.top/Article/details/gt2mlwpdilb.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.andypj.xyz/Article/details/gt2agmpvxcl.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jlsjyb.cn/Article/details/gt2xlolqnsc.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.snrcjt.cn/Article/details/gt2kkupvmwj.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jiagoushi.top/Article/details/gt2vgjjczix.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.shangyingyoupin.top/Article/details/gt2bspugrcn.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.feifeiyinyue.top/Article/details/gt2kepfpeqw.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.0kj1m.cn/Article/details/gt2lmlvbwxi.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.shzxlz.cn/Article/details/gt2whdscvlp.html

[E15] HTML 转义 / 反转义
来源：http://dali.smart0.xyz/Article/details/gt2jumwhihz.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2cdqzmbqs.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.sweek.top/Article/details/gt2fpkovdmx.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2qblfjaby.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mejfvemc.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.nanxinkj.top/Article/details/gt2nmbghiiy.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.wangdashe.top/Article/details/gt2jhkvumud.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.mhx1999.top/Article/details/gt2oyrwxepj.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.fzhhl.top/Article/details/gt2gtaonkyw.html

[E16] 数字千分位
来源：http://dali.gogol.net.cn/Article/details/gt2hfecyzke.html

Py:   f"{1234567:,}"
来源：http://dali.daria6918.cn/Article/details/gt2roiqjtni.html

PHP:  number_format(1234567);
来源：http://dali.dianchejie.cn/Article/details/gt2cjqclasm.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.pengpengdd.cyou/Article/details/gt2taufwurm.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.andypj.xyz/Article/details/gt2vaqhxeob.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.aibaodan.cn/Article/details/gt2wjurkguu.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.pycfn.com/Article/details/gt2qtwsbbit.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rikilyxg.html

C#:   1234567.ToString("N0")
来源：http://dali.jqgufenzy.top/Article/details/gt2cnnakdbk.html

[E17] 首字母大写
来源：http://dali.nanxinkj.top/Article/details/gt2uaeuaauy.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.vqdsnc.cn/Article/details/gt2lxfsnazt.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.tanke756.top/Article/details/gt2scgabxjh.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenlongwang.top/Article/details/gt2nvenzxvh.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bdcxhhye.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.cucudq.cn/Article/details/gt2zaijowhd.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jqgfzy.top/Article/details/gt2zrmxzomr.html

Ruby: s.capitalize
来源：http://dali.chenlongwang.top/Article/details/gt2dcdgwvsc.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.nwbrower.top/Article/details/gt2gbkbzbae.html

[E18] 模板占位符替换
来源：http://dali.zhoulong.xyz/Article/details/gt2xmjglwnc.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hfpthk.cn/Article/details/gt2czdrgasd.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vyayyukd.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.bjfxy.top/Article/details/gt2xumxxnur.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.daria6918.cn/Article/details/gt2zqcmqelk.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.ybcxt.top/Article/details/gt2tllzhsrm.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.haohaochexian.top/Article/details/gt2ahlbncru.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.svipenyu.cn/Article/details/gt2ikazbznr.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jyoumei.cn/Article/details/gt2nxmgdutp.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2wvjbgobx.html

Py:   s.splitlines()
来源：http://dali.sweek.top/Article/details/gt2rofzikzt.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.sxryk.cn/Article/details/gt2oxvuenkq.html

JS:   s.split(/\r?\n/)
来源：http://dali.chenzaomai.com/Article/details/gt2wkzzvcuo.html

TS:   s.split(/\r?\n/)
来源：http://dali.yonumen.top/Article/details/gt2onunywex.html

Java: s.lines().toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nrdcyzmd.html

Go:   strings.Split(s, "\n")
来源：http://dali.iojbl.cn/Article/details/gt2kqjduoec.html

Ruby: s.lines
来源：http://dali.hnxiangtu.top/Article/details/gt2dsqpnxeu.html

C#:   s.Split('\n')
来源：http://dali.shanyushiyangtech.top/Article/details/gt2djarjkta.html

[E20] 判断字符串是否为空
来源：http://dali.jianghu66.top/Article/details/gt2hztidwxh.html

Py:   if not s:
来源：http://dali.0kj1m.cn/Article/details/gt2xqzytnwd.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.havefunace.top/Article/details/gt2bcrfbqee.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.xuanzx.com/Article/details/gt2ubhkmiww.html

TS:   if (s === "") {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2opheqozi.html

Java: if (s.isEmpty()) {}
来源：http://dali.guowangkeji.top/Article/details/gt2epwgcyjc.html

Go:   if s == "" {}
来源：http://dali.svipenyu.cn/Article/details/gt2niadmlbr.html

Ruby: if s.empty?
来源：http://dali.hongshengwenyu.top/Article/details/gt2uxpzkapi.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.daria6918.cn/Article/details/gt2djqwtwof.html

[E21] 超长截断加省略号
来源：http://dali.kuanghao11.cn/Article/details/gt2kuawxhnl.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yangfankeji.com/Article/details/gt2dktanval.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yueranfly.top/Article/details/gt2dovlywdb.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zdqjudy.top/Article/details/gt2yhrnucai.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shangyingyoupin.top/Article/details/gt2pzapeohm.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.guannengcc.top/Article/details/gt2apjvfesn.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.chenjidiqi.icu/Article/details/gt2nenesrdo.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jqgufenzy.top/Article/details/gt2pxjokiqy.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.cdnleiting.top/Article/details/gt2epjzvtuf.html

[E22] 字节长度与字符长度
来源：http://dali.yuxming.cn/Article/details/gt2zqxfgjye.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vzuwknrs.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2djywmocf.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tepyzcoy.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhoulong.xyz/Article/details/gt2zppotgmu.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jinqigfzy.top/Article/details/gt2ufkjpyqy.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.havefunace.top/Article/details/gt2spenvjft.html

Ruby: s.bytesize;  s.length
来源：http://dali.shzxlz.cn/Article/details/gt2ziwpicsc.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.cashguo.top/Article/details/gt2syqbzbrb.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2sxindrhy.html

F. 文件与目录
来源：http://dali.zhengqikj.top/Article/details/gt2npdyrzxf.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ktmgjucj.html


<!-- 参考信息 -->