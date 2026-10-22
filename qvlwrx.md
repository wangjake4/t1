代发 wailian999

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.birdmap.top/Article/details/gt2kikoetdt.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.xinyue.icu/Article/details/gt2hhqeuqlb.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yueranfly.top/Article/details/gt2uxyfnjfp.html

[D14] 映射转换（每个元素变形）
来源：http://dali.xylfe.cn/Article/details/gt2ixrlceyu.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.ybcxt.top/Article/details/gt2znmrhasx.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.sxryk.cn/Article/details/gt2bcbxezuq.html

JS:   arr.map(x => x * 2)
来源：http://dali.tianlin.xyz/Article/details/gt2umzidnwx.html

TS:   arr.map(x => x * 2)
来源：http://dali.9152youxi.cn/Article/details/gt2ywiypxnj.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.vqdsnc.cn/Article/details/gt2egjyslsq.html

Go:   // 手写循环
来源：http://dali.jqgufenzy.top/Article/details/gt2uducbdko.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.c1oappe.top/Article/details/gt2xeatlcrj.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.tianlin.xyz/Article/details/gt2mjnohfzv.html

[D15] 去重
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gqrtjgql.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.cashguo.top/Article/details/gt2knndnoeh.html

PHP:  array_unique($arr);
来源：http://dali.chenzaomai.com/Article/details/gt2yemqmfuz.html

JS:   [...new Set(arr)]
来源：http://dali.hnqzz.top/Article/details/gt2zbcshteu.html

TS:   [...new Set(arr)]
来源：http://dali.yuanzhike.top/Article/details/gt2veshxjnl.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yanxiufei.cn/Article/details/gt2qshibnzf.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.guannengcc.top/Article/details/gt2gwsbchna.html

Ruby: arr.uniq
来源：http://dali.meibo888.top/Article/details/gt2iwmrcqgl.html

C#:   list.Distinct().ToList()
来源：http://dali.shangyingyoupin.top/Article/details/gt2hewryutq.html

[D16] 求和与平均值
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dwfswtxx.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.cucudq.cn/Article/details/gt2ktjzpgxz.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gt2jjpgqrmx.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gzhubu.top/Article/details/gt2zxhruyig.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.nanxuanxn.top/Article/details/gt2hdtvdhye.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.ppjwa.cn/Article/details/gt2ubtmlrpq.html

Go:   // 手写循环累加
来源：http://dali.jlsjyb.cn/Article/details/gt2czwpaxax.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.gzhubu.top/Article/details/gt2qnzmezoh.html

C#:   list.Sum();  list.Average()
来源：http://dali.bjfxy.top/Article/details/gt2hhoxhzvi.html

[D17] 最大值与最小值
来源：http://dali.316326.xyz/Article/details/gt2ihrhhgig.html

Py:   max(arr);  min(arr)
来源：http://dali.redwolf501.top/Article/details/gt2iyojpzad.html

PHP:  max($arr);  min($arr);
来源：http://dali.shuidangran.top/Article/details/gt2dbzjpqrq.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.smart0.xyz/Article/details/gt2zggfgayf.html

TS:   Math.max(...arr);
来源：http://dali.nanxuanxn.top/Article/details/gt2jjzynpjx.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jiagoushi.top/Article/details/gt2npnvnmdc.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wozhqqnz.html

Ruby: arr.max;  arr.min
来源：http://dali.chenzaomai.com/Article/details/gt2qsktcdsk.html

C#:   list.Max();  list.Min()
来源：http://dali.vqdsnc.cn/Article/details/gt2jzwceygi.html

[D18] 扁平化嵌套数组
来源：http://dali.zycfv.cn/Article/details/gt2rrtzowiq.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.cqqwz.cn/Article/details/gt2tneocsxi.html

PHP:  array_merge(...$nested);
来源：http://dali.tanke756.top/Article/details/gt2tolxscvi.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yonumen.top/Article/details/gt2aqcrfife.html

TS:   nested.flat();
来源：http://dali.cheryme.top/Article/details/gt2shykffzp.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhoulong.xyz/Article/details/gt2upchbnpj.html

Go:   // 手写双层循环
来源：http://dali.cdnleiting.top/Article/details/gt2ewozlkjn.html

Ruby: nested.flatten
来源：http://dali.ydzc1.top/Article/details/gt2lblbeqxe.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qauqmygm.html

[D19] 按字段分组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zelorhpj.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yvedp.cn/Article/details/gt2kcpjfgnc.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qslrucuz.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yonumen.top/Article/details/gt2rtzryofr.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.nanxinkj.top/Article/details/gt2odjglvng.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.quarkkingdee.top/Article/details/gt2orpexavp.html

Go:   // 手写 map[string][]T
来源：http://dali.xziqi.cn/Article/details/gt2ikoeedxg.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yj20258888.top/Article/details/gt2eeiofrln.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.svipenyu.cn/Article/details/gt2kptiejgk.html

[D20] 统计每个元素出现次数
来源：http://dali.xuetiantiany.cn/Article/details/gt2tusjhran.html

Py:   Counter(arr)
来源：http://dali.dianchejie.cn/Article/details/gt2mdjnrfdb.html

PHP:  array_count_values($arr);
来源：http://dali.ehwqpu.com/Article/details/gt2sgvcnwdy.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.nwbrower.top/Article/details/gt2wnuwolkh.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.nanxinkj.top/Article/details/gt2ombbtwcw.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhengqikj.top/Article/details/gt2ajacfzax.html

Go:   // 手写 map[T]int
来源：http://dali.jqgufenzy.top/Article/details/gt2fkulfffw.html

Ruby: arr.tally
来源：http://dali.hammf.cn/Article/details/gt2gnbmgjli.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.tanke756.top/Article/details/gt2jjycolnx.html

[D21] 判断是否包含某元素
来源：http://dali.birdmap.top/Article/details/gt2phyfaqtt.html

Py:   x in arr
来源：http://dali.jinqigfzy.top/Article/details/gt2eepxpmru.html

PHP:  in_array($x, $arr, true);
来源：http://dali.sxryk.cn/Article/details/gt2zkiqfrpa.html

JS:   arr.includes(x)
来源：http://dali.tian-w.cn/Article/details/gt2xtwpxyyj.html

TS:   arr.includes(x)
来源：http://dali.jinqigufen.top/Article/details/gt2tuykuvoj.html

Java: list.contains(x)
来源：http://dali.ybcxt.top/Article/details/gt2dwdwdpdp.html

Go:   slices.Contains(arr, x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ezoqaxny.html

Ruby: arr.include?(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iadjxcqt.html

C#:   list.Contains(x)
来源：http://dali.yongpay.top/Article/details/gt2vhpkckdr.html

[D22] 复制数组（避免共享引用）
来源：http://dali.daria6918.cn/Article/details/gt2wtedegzh.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yvedp.cn/Article/details/gt2wojnxwfq.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.cqqwz.cn/Article/details/gt2yrnxcsrw.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yj202588.top/Article/details/gt2fsdgfxvi.html

TS:   [...arr];
来源：http://dali.yongpay.top/Article/details/gt2trwhtnoy.html

Java: new ArrayList<>(list);
来源：http://dali.chenjidiqi.icu/Article/details/gt2bcqqdhli.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zdqjudy.top/Article/details/gt2mleyijjo.html

Ruby: arr.dup;  arr.clone
来源：http://dali.sufxvd.cn/Article/details/gt2wnoxirls.html

C#:   new List<int>(list);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2giqzxnxt.html

[D23] reduce 累积计算
来源：http://dali.daxiang520.top/Article/details/gt2xdbqptuo.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gt2zlhsuzya.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.pycfn.com/Article/details/gt2auanemop.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qtooyebe.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yonumen.top/Article/details/gt2xucfmhtv.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yueranfly.top/Article/details/gt2lgzkzgqc.html

Go:   // 手写循环
来源：http://dali.wangdashe.top/Article/details/gt2nknxlcxs.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jlsjyb.cn/Article/details/gt2hftnrayg.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.shzxlz.cn/Article/details/gt2wiaafyuo.html

[D24] 字典 / Map 基本操作
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dejabkss.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.shangyingyoupin.top/Article/details/gt2eesvqokr.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.chenzaomai.com/Article/details/gt2eoycbzbd.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.chenlongwang.top/Article/details/gt2jivlifvi.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yoesrgna.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jqgfzy.top/Article/details/gt2cixnctxx.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.aizwys.cn/Article/details/gt2bvcgqooi.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yanxiufei.cn/Article/details/gt2ofembutn.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gkifsmza.html

[D25] Set 集合去重与交并差
来源：http://dali.cucudq.cn/Article/details/gt2grytrbqx.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yvedp.cn/Article/details/gt2siedzfyv.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yueranfly.top/Article/details/gt2ntzorcpr.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.mhx1999.top/Article/details/gt2ibnugvju.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.nanxuanxn.top/Article/details/gt2uojmzjbh.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.meibo888.top/Article/details/gt2hmieofks.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.xuetiantiany.cn/Article/details/gt2uxdmgudp.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.sufxvd.cn/Article/details/gt2dqpwnkhg.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.chenlongwang.top/Article/details/gt2cmzrsklp.html

[D26] 数组转字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eshviefs.html

Py:   ", ".join(map(str, arr))
来源：http://dali.havefunace.top/Article/details/gt2skdezcns.html

PHP:  implode(", ", $arr);
来源：http://dali.gotoacloud.top/Article/details/gt2uzcixnnm.html

JS:   arr.join(", ")
来源：http://dali.vqdsnc.cn/Article/details/gt2znvjopta.html

TS:   arr.join(", ")
来源：http://dali.jianghu66.top/Article/details/gt2tubysyan.html

Java: String.join(", ", list)
来源：http://dali.jinqigfzy.top/Article/details/gt2jajkwhnp.html

Go:   strings.Join(strs, ", ")
来源：http://dali.svipenyu.cn/Article/details/gt2qbmrtczr.html

Ruby: arr.join(", ")
来源：http://dali.zycfv.cn/Article/details/gt2vkzztgtq.html

C#:   string.Join(", ", list)
来源：http://dali.gaohongyu789.top/Article/details/gt2dclxfsus.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2sbleofzp.html

E. 字符串处理
来源：http://dali.xuanzx.com/Article/details/gt2cebjwkzs.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2nahznmne.html

[E01] 拼接字符串
来源：http://dali.hywenlv.cn/Article/details/gt2bxcfrrvy.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhixingplan.top/Article/details/gt2vtiqnvsd.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.9152youxi.cn/Article/details/gt2rahjfndq.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xziqi.cn/Article/details/gt2flwburrm.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hfpthk.cn/Article/details/gt2jzamnvds.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.svipenyu.cn/Article/details/gt2ncktuwix.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.kuanghao11.cn/Article/details/gt2wurnwjau.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.snrcjt.cn/Article/details/gt2emifibhg.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yivnptcg.html

[E02] 重复字符串
来源：http://dali.ivvv.top/Article/details/gt2nrazoyro.html

Py:   "ab" * 3
来源：http://dali.nanxinkj.top/Article/details/gt2axtgyfgp.html

PHP:  str_repeat("ab", 3);
来源：http://dali.shuidangran.top/Article/details/gt2bpjypfda.html

JS:   "ab".repeat(3)
来源：http://dali.smart0.xyz/Article/details/gt2vxlrxlxf.html

TS:   "ab".repeat(3)
来源：http://dali.yuxming.cn/Article/details/gt2ppihxvof.html

Java: "ab".repeat(3)
来源：http://dali.vqdsnc.cn/Article/details/gt2yiebnoqy.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.9152youxi.cn/Article/details/gt2mtojshsv.html

Ruby: "ab" * 3
来源：http://dali.ydzc1.top/Article/details/gt2ilzlfxec.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.gzhubu.top/Article/details/gt2xiqjzbpx.html

[E03] 截取子串
来源：http://dali.gaohongyu789.top/Article/details/gt2knusyhqf.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ocjqybtm.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.hysaishi.cn/Article/details/gt2qhnltrqq.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kgmrtxak.html

TS:   s.slice(1, 4)
来源：http://dali.yuxming.cn/Article/details/gt2fdifmgjr.html

Java: s.substring(1, 4)
来源：http://dali.fengsongda.top/Article/details/gt2qwkffdmy.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.cashguo.top/Article/details/gt2cmlfejza.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.cheryme.top/Article/details/gt2tikqwcwg.html

C#:   s.Substring(1, 3)
来源：http://dali.hongshengwenyu.top/Article/details/gt2jujxgrov.html

[E04] 查找子串位置
来源：http://dali.hnqzz.top/Article/details/gt2rmvkesjp.html

Py:   s.find("x");  s.index("x")
来源：http://dali.mhx1999.top/Article/details/gt2iajkvipe.html

PHP:  strpos($s, "x");
来源：http://dali.kuanghao11.cn/Article/details/gt2bkcfklpj.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.hongshengwenyu.top/Article/details/gt2elqxgymd.html

TS:   s.indexOf("x")
来源：http://dali.xziqi.cn/Article/details/gt2sbcnevir.html

Java: s.indexOf("x")
来源：http://dali.c1oappe.top/Article/details/gt2psrlvhjt.html

Go:   strings.Index(s, "x")
来源：http://dali.zdqjudy.top/Article/details/gt2dgjzkyjb.html

Ruby: s.index("x")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jfrfhahw.html

C#:   s.IndexOf("x")
来源：http://dali.9152youxi.cn/Article/details/gt2pzuwyojb.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.sufxvd.cn/Article/details/gt2ocmnwqdm.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yanxiufei.cn/Article/details/gt2qtexvrma.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhongyouzk.top/Article/details/gt2yelapnpj.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nakyrlww.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jyoumei.cn/Article/details/gt2zcfbiwna.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yongpay.top/Article/details/gt2jnugjquv.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.sysykeji.top/Article/details/gt2cifwuclq.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.chenlongwang.top/Article/details/gt2fqslscaz.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhoulong.xyz/Article/details/gt2hnnuakjk.html

[E06] 替换子串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2chldkbpt.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jyoumei.cn/Article/details/gt2zrnfppgg.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.cashguo.top/Article/details/gt2szzxliqr.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.c1oappe.top/Article/details/gt2mhpdcdnc.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zdqjudy.top/Article/details/gt2rtfeqccs.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gt2pmkuyxze.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.bjfxy.top/Article/details/gt2emrqqvmx.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.0kj1m.cn/Article/details/gt2hnynifqr.html

C#:   s.Replace("a", "b")
来源：http://dali.yangfankeji.com/Article/details/gt2lafyqpbd.html

[E07] 按分隔符拆分
来源：http://dali.sxryk.cn/Article/details/gt2ansgsoye.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.svipenyu.cn/Article/details/gt2frewrhse.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yj20258.top/Article/details/gt2lyiksuqn.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jqgfzy.top/Article/details/gt2uehqhasb.html

TS:   s.split(",")
来源：http://dali.nwbrower.top/Article/details/gt2zfaecjfs.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.pengpengdd.cyou/Article/details/gt2jtciabod.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.nanxinkj.top/Article/details/gt2iakfrben.html

Ruby: s.split(",");  s.split
来源：http://dali.jqgufenzy.top/Article/details/gt2oxgrqpys.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hnqzz.top/Article/details/gt2qbxdmopj.html

[E08] 数组按分隔符合并
来源：http://dali.9152youxi.cn/Article/details/gt2gnpziecg.html

Py:   ",".join(items)
来源：http://dali.yueranfly.top/Article/details/gt2xzuqkzby.html

PHP:  implode(",", $items);
来源：http://dali.snrcjt.cn/Article/details/gt2loidhxkd.html

JS:   items.join(",")
来源：http://dali.meibo888.top/Article/details/gt2fxpotgvv.html

TS:   items.join(",")
来源：http://dali.quarkkingdee.top/Article/details/gt2peacaunc.html

Java: String.join(",", items)
来源：http://dali.yvedp.cn/Article/details/gt2jxwniuvm.html

Go:   strings.Join(items, ",")
来源：http://dali.ehwqpu.com/Article/details/gt2zelkjygj.html

Ruby: items.join(",")
来源：http://dali.chenlongwang.top/Article/details/gt2ikddwurc.html

C#:   string.Join(",", items)
来源：http://dali.daria6918.cn/Article/details/gt2bgptcrrs.html

[E09] 去除所有空白字符
来源：http://dali.ybcxt.top/Article/details/gt2lzayorle.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bkpqduej.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jqgfzy.top/Article/details/gt2gpkvleuu.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.kuanghao11.cn/Article/details/gt2dccowdqj.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.9152youxi.cn/Article/details/gt2hiuvnjfb.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.ppjwa.cn/Article/details/gt2creqsljs.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ziwpahli.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jiagoushi.top/Article/details/gt2furfuvbt.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhiwuduotai.top/Article/details/gt2iuzfvchz.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yuxming.cn/Article/details/gt2nywebiam.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.nanxuanxn.top/Article/details/gt2tzgwgeld.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.aibaodan.cn/Article/details/gt2zqwhqcgy.html

JS:   "7".padStart(3, "0")
来源：http://dali.jyoumei.cn/Article/details/gt2nndfyfmx.html

TS:   "7".padStart(3, "0")
来源：http://dali.meibo888.top/Article/details/gt2bvmmbyjs.html

Java: String.format("%03d", 7)
来源：http://dali.jiagoushi.top/Article/details/gt2qgbfbdnc.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.sufxvd.cn/Article/details/gt2esplgknx.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jinqigufen.top/Article/details/gt2jfjqlhiz.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.haohaochexian.top/Article/details/gt2vdspgqqq.html

[E11] 反转字符串
来源：http://dali.sufxvd.cn/Article/details/gt2exdvnafk.html

Py:   s[::-1]
来源：http://dali.ybcxt.top/Article/details/gt2xiefnhfm.html

PHP:  strrev($s);
来源：http://dali.cdnleiting.top/Article/details/gt2kvmvkxam.html

JS:   [...s].reverse().join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vbqaaqfr.html

TS:   [...s].reverse().join("")
来源：http://dali.zhoulong.xyz/Article/details/gt2qjknoyex.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhoulong.xyz/Article/details/gt2dxkparzh.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yueranfly.top/Article/details/gt2ilgjfvjy.html

Ruby: s.reverse
来源：http://dali.guowangkeji.top/Article/details/gt2zajemeqg.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.xziqi.cn/Article/details/gt2cwvubujq.html

[E12] 统计某字符出现次数
来源：http://dali.jinqigfzy.top/Article/details/gt2kkvkdaxk.html

Py:   s.count("a")
来源：http://dali.xziqi.cn/Article/details/gt2egmbdocd.html

PHP:  substr_count($s, "a");
来源：http://dali.tian-w.cn/Article/details/gt2kgsfmdvg.html

JS:   s.split("a").length - 1
来源：http://dali.chenjidiqi.icu/Article/details/gt2btjequzk.html

TS:   s.split("a").length - 1
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ixxyjcsq.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yongpay.top/Article/details/gt2obuwcyhf.html

Go:   strings.Count(s, "a")
来源：http://dali.316326.xyz/Article/details/gt2qgcyvtfu.html

Ruby: s.count("a")
来源：http://dali.c1oappe.top/Article/details/gt2lraqnuix.html

C#:   s.Count(c => c == 'a')
来源：http://dali.svipenyu.cn/Article/details/gt2hbzriavu.html

[E13] 逐字符遍历
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xgwxmzsq.html

Py:   for ch in s: print(ch)
来源：http://dali.jinqigfzy.top/Article/details/gt2pypqbhkg.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.nwbrower.top/Article/details/gt2mamhyels.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sweek.top/Article/details/gt2tlotvaha.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ivvv.top/Article/details/gt2zyfnkggl.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.andypj.xyz/Article/details/gt2hwhpopaa.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ppjwa.cn/Article/details/gt2iwxeedfh.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hnqzz.top/Article/details/gt2yhxzpwbd.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.gzhubu.top/Article/details/gt2gzqiqgfz.html

[E14] URL 编码与 Base64
来源：http://dali.sxryk.cn/Article/details/gt2bdkpyosh.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bmyslrud.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.nanxuanxn.top/Article/details/gt2oewcpjra.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.kuanghao11.cn/Article/details/gt2mthyszmb.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.tanke756.top/Article/details/gt2qmjbilsv.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jinqigufen.top/Article/details/gt2nqbafcoz.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.mhx1999.top/Article/details/gt2fmupiegp.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.haohaochexian.top/Article/details/gt2ejuwaytm.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.nanxuanxn.top/Article/details/gt2foxbqhhn.html

[E15] HTML 转义 / 反转义
来源：http://dali.redwolf501.top/Article/details/gt2fhvqinyy.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2tisloqda.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.sysykeji.top/Article/details/gt2vqkvifyh.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.guannengcc.top/Article/details/gt2rbrwrceg.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.svipenyu.cn/Article/details/gt2sqfbcgxk.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.kuanghao11.cn/Article/details/gt2xnbwenrf.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.gzhubu.top/Article/details/gt2mojypaul.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hnqzz.top/Article/details/gt2pvsqberc.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2ckpaxkhz.html

[E16] 数字千分位
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wykyzouw.html

Py:   f"{1234567:,}"
来源：http://dali.xuanzx.com/Article/details/gt2ypjkeptt.html

PHP:  number_format(1234567);
来源：http://dali.sweek.top/Article/details/gt2gyremgix.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yangfankeji.com/Article/details/gt2ryxmrahx.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.xylfe.cn/Article/details/gt2ncinoxod.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jinqigufen.top/Article/details/gt2asrmwssf.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.iojbl.cn/Article/details/gt2xtljbfne.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.ehwqpu.com/Article/details/gt2esrdxkvc.html

C#:   1234567.ToString("N0")
来源：http://dali.shuidangran.top/Article/details/gt2uxjnckjr.html

[E17] 首字母大写
来源：http://dali.yuxming.cn/Article/details/gt2bhvtoqpu.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hnxiangtu.top/Article/details/gt2xgxlgyuy.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.c1oappe.top/Article/details/gt2ebhbnmni.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2zgawalrp.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ulewkjcn.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.quarkkingdee.top/Article/details/gt2uqaqhbho.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yueranfly.top/Article/details/gt2syuunugs.html

Ruby: s.capitalize
来源：http://dali.fengsongda.top/Article/details/gt2ndccdhcs.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.chenjidiqi.icu/Article/details/gt2hyjaksux.html

[E18] 模板占位符替换
来源：http://dali.iojbl.cn/Article/details/gt2mlzcsssi.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.feifeiyinyue.top/Article/details/gt2nllrosxc.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xuetiantiany.cn/Article/details/gt2ufqhuvnl.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhongyouzk.top/Article/details/gt2gcckpxjn.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.sweek.top/Article/details/gt2xbkcfjfv.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.sysykeji.top/Article/details/gt2ztkjugku.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.redwolf501.top/Article/details/gt2tpvqlqhi.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yvedp.cn/Article/details/gt2umbtbexr.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.hammf.cn/Article/details/gt2sjhwxncu.html

[E19] 多行文本按行拆分
来源：http://dali.gzhubu.top/Article/details/gt2sxjxcpak.html

Py:   s.splitlines()
来源：http://dali.chenzaomai.com/Article/details/gt2uvkksujz.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hswbtgia.html

JS:   s.split(/\r?\n/)
来源：http://dali.nanxuanxn.top/Article/details/gt2wyxnklvj.html

TS:   s.split(/\r?\n/)
来源：http://dali.cheryme.top/Article/details/gt2dziejeha.html

Java: s.lines().toList()
来源：http://dali.xuetiantiany.cn/Article/details/gt2fxgrbfgm.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhixingplan.top/Article/details/gt2gpsxqvig.html

Ruby: s.lines
来源：http://dali.aibaodan.cn/Article/details/gt2utcdtvzv.html

C#:   s.Split('\n')
来源：http://dali.dianchejie.cn/Article/details/gt2nlfyzeqb.html

[E20] 判断字符串是否为空
来源：http://dali.yuanzhike.top/Article/details/gt2xcxluqhz.html

Py:   if not s:
来源：http://dali.meibo888.top/Article/details/gt2rlrcwdqk.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.chenzaomai.com/Article/details/gt2yiskxwfv.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.sweek.top/Article/details/gt2rjbptsih.html

TS:   if (s === "") {}
来源：http://dali.kuanghao11.cn/Article/details/gt2kuuoiorw.html

Java: if (s.isEmpty()) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2guusvibm.html


<!-- 参考信息 -->