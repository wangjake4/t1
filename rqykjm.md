代发 wailian999

Ruby: arr.index(x)
来源：http://dali.jianghu66.top/Article/details/gt2hbyadwll.html

C#:   list.IndexOf(x);
来源：http://dali.yj202588.top/Article/details/gt2cnlfnpmm.html

[D13] 过滤（保留满足条件的）
来源：http://dali.pengpengdd.cyou/Article/details/gt2ysjghudb.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.birdmap.top/Article/details/gt2cxccdcjo.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.pycfn.com/Article/details/gt2pbiggwdr.html

JS:   arr.filter(x => x > 3)
来源：http://dali.ppjwa.cn/Article/details/gt2xbkofmrs.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jqgufenzy.top/Article/details/gt2uwkscgrv.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.snrcjt.cn/Article/details/gt2zblneplz.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.shzxlz.cn/Article/details/gt2cemhkisn.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yangfankeji.com/Article/details/gt2rxbihhzn.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hammf.cn/Article/details/gt2fwwmlczi.html

[D14] 映射转换（每个元素变形）
来源：http://dali.guannengcc.top/Article/details/gt2qjxzfwwv.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.smart0.xyz/Article/details/gt2acdgyoyh.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.cucudq.cn/Article/details/gt2tfwjitqs.html

JS:   arr.map(x => x * 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vnsknzfc.html

TS:   arr.map(x => x * 2)
来源：http://dali.wangdashe.top/Article/details/gt2wycsrimn.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.feifeiyinyue.top/Article/details/gt2yklwjxta.html

Go:   // 手写循环
来源：http://dali.jlsjyb.cn/Article/details/gt2jdxfgdeg.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.aizwys.cn/Article/details/gt2ddtatihg.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yvedp.cn/Article/details/gt2elstosqe.html

[D15] 去重
来源：http://dali.fzhhl.top/Article/details/gt2qdvygihw.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.xinyue.icu/Article/details/gt2esmnglmg.html

PHP:  array_unique($arr);
来源：http://dali.vqdsnc.cn/Article/details/gt2uqbcegvx.html

JS:   [...new Set(arr)]
来源：http://dali.mhx1999.top/Article/details/gt2vclyqaxv.html

TS:   [...new Set(arr)]
来源：http://dali.redwolf501.top/Article/details/gt2vpprartc.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.fengsongda.top/Article/details/gt2vaxotrsk.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.nanxinkj.top/Article/details/gt2ljxrgqsz.html

Ruby: arr.uniq
来源：http://dali.c1oappe.top/Article/details/gt2lkmgxyzd.html

C#:   list.Distinct().ToList()
来源：http://dali.yuanzhike.top/Article/details/gt2qrbeovka.html

[D16] 求和与平均值
来源：http://dali.hnqzz.top/Article/details/gt2oztvhxkc.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gt2xlohtqkv.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hammf.cn/Article/details/gt2vvcwtpjt.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmehmwfz.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.tian-w.cn/Article/details/gt2byvuwdoc.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.redwolf501.top/Article/details/gt2nczacvpl.html

Go:   // 手写循环累加
来源：http://dali.zhongyouzk.top/Article/details/gt2adtpzzpe.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yanxiufei.cn/Article/details/gt2pmcnggwe.html

C#:   list.Sum();  list.Average()
来源：http://dali.zycfv.cn/Article/details/gt2jytoohje.html

[D17] 最大值与最小值
来源：http://dali.gotoacloud.top/Article/details/gt2bpxdfwaq.html

Py:   max(arr);  min(arr)
来源：http://dali.guowangkeji.top/Article/details/gt2mcqwioaz.html

PHP:  max($arr);  min($arr);
来源：http://dali.aibaodan.cn/Article/details/gt2zaaliijl.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.iojbl.cn/Article/details/gt2pqraxucw.html

TS:   Math.max(...arr);
来源：http://dali.sufxvd.cn/Article/details/gt2jsnxgqtf.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yuanzhike.top/Article/details/gt2qkalmbdv.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhixingplan.top/Article/details/gt2rcapwurm.html

Ruby: arr.max;  arr.min
来源：http://dali.jiagoushi.top/Article/details/gt2xpayolva.html

C#:   list.Max();  list.Min()
来源：http://dali.guannengcc.top/Article/details/gt2cldnjuhw.html

[D18] 扁平化嵌套数组
来源：http://dali.c1oappe.top/Article/details/gt2dstjjwug.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tfkskofw.html

PHP:  array_merge(...$nested);
来源：http://dali.ybcxt.top/Article/details/gt2xszquuqb.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhengqikj.top/Article/details/gt2iczpbffs.html

TS:   nested.flat();
来源：http://dali.smart0.xyz/Article/details/gt2lkerwcje.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.ydzc1.top/Article/details/gt2krtkagtu.html

Go:   // 手写双层循环
来源：http://dali.sufxvd.cn/Article/details/gt2ptupekzs.html

Ruby: nested.flatten
来源：http://dali.mhx1999.top/Article/details/gt2itaddgyf.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yuanzhike.top/Article/details/gt2chdbfmub.html

[D19] 按字段分组
来源：http://dali.redwolf501.top/Article/details/gt2tcakmorh.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mscdiqfa.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.xylfe.cn/Article/details/gt2pdpertzo.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yuanzhike.top/Article/details/gt2bumdwbsx.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.feifeiyinyue.top/Article/details/gt2vcggncxt.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhiwuduotai.top/Article/details/gt2ofomokon.html

Go:   // 手写 map[string][]T
来源：http://dali.birdmap.top/Article/details/gt2zckoykxe.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.cheryme.top/Article/details/gt2wdympckv.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.sufxvd.cn/Article/details/gt2rnoqkpnt.html

[D20] 统计每个元素出现次数
来源：http://dali.nwbrower.top/Article/details/gt2nsxdyztq.html

Py:   Counter(arr)
来源：http://dali.guowangkeji.top/Article/details/gt2mqnbwcjy.html

PHP:  array_count_values($arr);
来源：http://dali.zycfv.cn/Article/details/gt2mdrcbhjz.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhiwuduotai.top/Article/details/gt2ylmkwtqm.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yongpay.top/Article/details/gt2uqpoisly.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.gaohongyu789.top/Article/details/gt2xtivmtex.html

Go:   // 手写 map[T]int
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mqmjwcno.html

Ruby: arr.tally
来源：http://dali.c1oappe.top/Article/details/gt2ubpnooql.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.chenjidiqi.icu/Article/details/gt2osqqqcju.html

[D21] 判断是否包含某元素
来源：http://dali.aibaodan.cn/Article/details/gt2hsypfvno.html

Py:   x in arr
来源：http://dali.yvedp.cn/Article/details/gt2zeiauyrd.html

PHP:  in_array($x, $arr, true);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kccdfdhk.html

JS:   arr.includes(x)
来源：http://dali.chenjidiqi.icu/Article/details/gt2cohmdmsu.html

TS:   arr.includes(x)
来源：http://dali.zhongyouzk.top/Article/details/gt2hvbbsrwz.html

Java: list.contains(x)
来源：http://dali.nanxinkj.top/Article/details/gt2eudgwpkn.html

Go:   slices.Contains(arr, x)
来源：http://dali.cqqwz.cn/Article/details/gt2ytklsese.html

Ruby: arr.include?(x)
来源：http://dali.hywenlv.cn/Article/details/gt2aggaijuu.html

C#:   list.Contains(x)
来源：http://dali.fzhhl.top/Article/details/gt2icauwgvm.html

[D22] 复制数组（避免共享引用）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bkhfuqqf.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.ybcxt.top/Article/details/gt2baovzbmm.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.xuetiantiany.cn/Article/details/gt2myxlwyfm.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.tianlin.xyz/Article/details/gt2awdztjnj.html

TS:   [...arr];
来源：http://dali.ydzc1.top/Article/details/gt2knvomvkq.html

Java: new ArrayList<>(list);
来源：http://dali.xylfe.cn/Article/details/gt2dulczyvr.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.nanxinkj.top/Article/details/gt2ivcfbfxq.html

Ruby: arr.dup;  arr.clone
来源：http://dali.ehwqpu.com/Article/details/gt2gipplfxi.html

C#:   new List<int>(list);
来源：http://dali.jyoumei.cn/Article/details/gt2jqcgtngg.html

[D23] reduce 累积计算
来源：http://dali.yuanzhike.top/Article/details/gt2rnifywml.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gt2mipopihd.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yj202588.top/Article/details/gt2xnsuvgvb.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yanxiufei.cn/Article/details/gt2ncyiyfcy.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhengqikj.top/Article/details/gt2tdkkirps.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hysaishi.cn/Article/details/gt2tuykhioc.html

Go:   // 手写循环
来源：http://dali.hongshengwenyu.top/Article/details/gt2wyfuchej.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.bjfxy.top/Article/details/gt2zqdxedjj.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.gogol.net.cn/Article/details/gt2zululzgh.html

[D24] 字典 / Map 基本操作
来源：http://dali.gaohongyu789.top/Article/details/gt2kgqcphlb.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.snrcjt.cn/Article/details/gt2ulrxnyho.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.tian-w.cn/Article/details/gt2lhrmthna.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yongpay.top/Article/details/gt2couerpwb.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.tian-w.cn/Article/details/gt2mepstzjj.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.sxryk.cn/Article/details/gt2xflnzwtq.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jinqigufen.top/Article/details/gt2luwzqcqg.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zdqjudy.top/Article/details/gt2vyekdmnr.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.wangshuangyany.cn/Article/details/gt2hvsfadhw.html

[D25] Set 集合去重与交并差
来源：http://dali.iojbl.cn/Article/details/gt2epljqvtp.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.tanke756.top/Article/details/gt2kwbtiptj.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hfpthk.cn/Article/details/gt2kwhkwizi.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.birdmap.top/Article/details/gt2dzicghgb.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.meibo888.top/Article/details/gt2elhefqsy.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.gzhubu.top/Article/details/gt2exhwnnjs.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.sysykeji.top/Article/details/gt2xlbraqhc.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.tian-w.cn/Article/details/gt2mwehvuei.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.cdnleiting.top/Article/details/gt2lhtivfyg.html

[D26] 数组转字符串
来源：http://dali.ydzc1.top/Article/details/gt2iumlitgh.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yj20258.top/Article/details/gt2dgvrhako.html

PHP:  implode(", ", $arr);
来源：http://dali.nanxinkj.top/Article/details/gt2iptxmolk.html

JS:   arr.join(", ")
来源：http://dali.yuanzhike.top/Article/details/gt2xpxjwfxv.html

TS:   arr.join(", ")
来源：http://dali.guowangkeji.top/Article/details/gt2utwvqstl.html

Java: String.join(", ", list)
来源：http://dali.hywenlv.cn/Article/details/gt2uadilxeb.html

Go:   strings.Join(strs, ", ")
来源：http://dali.cashguo.top/Article/details/gt2wrvoiazk.html

Ruby: arr.join(", ")
来源：http://dali.hnxiangtu.top/Article/details/gt2lwizfvfz.html

C#:   string.Join(", ", list)
来源：http://dali.dashuyun.cn/Article/details/gt2oligdmvh.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2sneeuyqz.html

E. 字符串处理
来源：http://dali.yongpay.top/Article/details/gt2vvupqziu.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2viesiwgm.html

[E01] 拼接字符串
来源：http://dali.mhx1999.top/Article/details/gt2heajoiym.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jlsjyb.cn/Article/details/gt2msdiawhp.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.ydzc1.top/Article/details/gt2yvrtavng.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.redwolf501.top/Article/details/gt2idrulkdm.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2awapmtdr.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.c1oappe.top/Article/details/gt2cfexbwii.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.nwbrower.top/Article/details/gt2yoiscdhn.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.birdmap.top/Article/details/gt2cqsrbhob.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gt2bsuhvkkt.html

[E02] 重复字符串
来源：http://dali.c1oappe.top/Article/details/gt2gxxbcnsz.html

Py:   "ab" * 3
来源：http://dali.feifeiyinyue.top/Article/details/gt2hxborsku.html

PHP:  str_repeat("ab", 3);
来源：http://dali.fengsongda.top/Article/details/gt2pelezlox.html

JS:   "ab".repeat(3)
来源：http://dali.iojbl.cn/Article/details/gt2uqlensnk.html

TS:   "ab".repeat(3)
来源：http://dali.sxryk.cn/Article/details/gt2ygykfnik.html

Java: "ab".repeat(3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ayhkfhnd.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.xinyue.icu/Article/details/gt2fxteuwea.html

Ruby: "ab" * 3
来源：http://dali.yanxiufei.cn/Article/details/gt2dotwsgeo.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zdqjudy.top/Article/details/gt2accdsqeb.html

[E03] 截取子串
来源：http://dali.smart0.xyz/Article/details/gt2yaejexkq.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jianghu66.top/Article/details/gt2xapubtps.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.9152youxi.cn/Article/details/gt2qyylbqyu.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yvedp.cn/Article/details/gt2sqlkqcql.html

TS:   s.slice(1, 4)
来源：http://dali.pycfn.com/Article/details/gt2yowwtkyf.html

Java: s.substring(1, 4)
来源：http://dali.dashuyun.cn/Article/details/gt2pokvyshd.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yj20258.top/Article/details/gt2ehonayco.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhengqikj.top/Article/details/gt2vlaqyaqs.html

C#:   s.Substring(1, 3)
来源：http://dali.ydzc1.top/Article/details/gt2hgzikphs.html

[E04] 查找子串位置
来源：http://dali.cdnleiting.top/Article/details/gt2kgbdszgo.html

Py:   s.find("x");  s.index("x")
来源：http://dali.cdnleiting.top/Article/details/gt2fwctubwm.html

PHP:  strpos($s, "x");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rlkdsjeo.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zycfv.cn/Article/details/gt2fnacavhm.html

TS:   s.indexOf("x")
来源：http://dali.sxryk.cn/Article/details/gt2snhapusi.html

Java: s.indexOf("x")
来源：http://dali.tian-w.cn/Article/details/gt2hroicpif.html

Go:   strings.Index(s, "x")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hhjfhzhp.html

Ruby: s.index("x")
来源：http://dali.gaohongyu789.top/Article/details/gt2qtggkmha.html

C#:   s.IndexOf("x")
来源：http://dali.quarkkingdee.top/Article/details/gt2wbopbxvp.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.mhx1999.top/Article/details/gt2vwcwgxmo.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2hylkthmy.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.pengpengdd.cyou/Article/details/gt2utkghwqg.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hammf.cn/Article/details/gt2njbbjegq.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.ydzc1.top/Article/details/gt2givjrusk.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zycfv.cn/Article/details/gt2qmuszjtf.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hnqzz.top/Article/details/gt2peoglbyd.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.ydzc1.top/Article/details/gt2hlmbodtm.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.ehwqpu.com/Article/details/gt2chanagej.html

[E06] 替换子串
来源：http://dali.0kj1m.cn/Article/details/gt2ledlyzff.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mkmgamuf.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nijielro.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jianghu66.top/Article/details/gt2jceujeij.html

TS:   s.replaceAll("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rqupxsog.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.wangdashe.top/Article/details/gt2phsnhwri.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.9152youxi.cn/Article/details/gt2yhmgjynp.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.fzhhl.top/Article/details/gt2epvbazvr.html

C#:   s.Replace("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gt2zpdtgmzw.html

[E07] 按分隔符拆分
来源：http://dali.jinqigufen.top/Article/details/gt2xpehxaos.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.hnqzz.top/Article/details/gt2alrexzgy.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qyzugekp.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.pengpengdd.cyou/Article/details/gt2rehghsdq.html

TS:   s.split(",")
来源：http://dali.feifeiyinyue.top/Article/details/gt2drypwive.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.sxryk.cn/Article/details/gt2xqshioeq.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.gzhubu.top/Article/details/gt2fjzarouf.html

Ruby: s.split(",");  s.split
来源：http://dali.andypj.xyz/Article/details/gt2xuziodqs.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.aibaodan.cn/Article/details/gt2fvbpfbpd.html

[E08] 数组按分隔符合并
来源：http://dali.ydzc1.top/Article/details/gt2fpvbppnz.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2eenbgbch.html

PHP:  implode(",", $items);
来源：http://dali.fengsongda.top/Article/details/gt2nqhxpyll.html

JS:   items.join(",")
来源：http://dali.yj202588.top/Article/details/gt2mlillgux.html

TS:   items.join(",")
来源：http://dali.cashguo.top/Article/details/gt2hcxiwvzc.html

Java: String.join(",", items)
来源：http://dali.pengpengdd.cyou/Article/details/gt2lqfftacs.html

Go:   strings.Join(items, ",")
来源：http://dali.sysykeji.top/Article/details/gt2wtvzxnax.html

Ruby: items.join(",")
来源：http://dali.yj20258.top/Article/details/gt2pdcpollr.html

C#:   string.Join(",", items)
来源：http://dali.mhx1999.top/Article/details/gt2lyvruomd.html

[E09] 去除所有空白字符
来源：http://dali.yj202588.top/Article/details/gt2kruecnfc.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yj202588.top/Article/details/gt2jkydnjlc.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.mhx1999.top/Article/details/gt2zufmnrel.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.ppjwa.cn/Article/details/gt2fuccmnon.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.snrcjt.cn/Article/details/gt2thnbqsxd.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.aizwys.cn/Article/details/gt2szwbgjfb.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.ppjwa.cn/Article/details/gt2jaulwbnq.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.nwbrower.top/Article/details/gt2nlvgyluc.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yuxming.cn/Article/details/gt2ixqrpvyv.html

[E10] 左侧补零 / 定长填充
来源：http://dali.tianlin.xyz/Article/details/gt2vgptuzjt.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.9152youxi.cn/Article/details/gt2jjgmvsxe.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.guowangkeji.top/Article/details/gt2mmdvscvn.html

JS:   "7".padStart(3, "0")
来源：http://dali.yj202588.top/Article/details/gt2iudqfkfz.html

TS:   "7".padStart(3, "0")
来源：http://dali.jqgufenzy.top/Article/details/gt2kckzmtds.html

Java: String.format("%03d", 7)
来源：http://dali.jlsjyb.cn/Article/details/gt2fqkvxbmm.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yonumen.top/Article/details/gt2krusrezx.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.chenlongwang.top/Article/details/gt2wpiqbyxz.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.bjfxy.top/Article/details/gt2oyyxblhk.html

[E11] 反转字符串
来源：http://dali.yanxiufei.cn/Article/details/gt2gyfevllg.html

Py:   s[::-1]
来源：http://dali.gogol.net.cn/Article/details/gt2eilmitig.html

PHP:  strrev($s);
来源：http://dali.c1oappe.top/Article/details/gt2byvgelyd.html

JS:   [...s].reverse().join("")
来源：http://dali.xuetiantiany.cn/Article/details/gt2hgetvkus.html

TS:   [...s].reverse().join("")
来源：http://dali.gzhubu.top/Article/details/gt2achqoaog.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.gaohongyu789.top/Article/details/gt2tkxclgvy.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yuxming.cn/Article/details/gt2xwepvcvu.html

Ruby: s.reverse
来源：http://dali.shuidangran.top/Article/details/gt2pzfgdqpp.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jinqigufen.top/Article/details/gt2fjxjyypj.html

[E12] 统计某字符出现次数
来源：http://dali.cdnleiting.top/Article/details/gt2kpgwoemr.html

Py:   s.count("a")
来源：http://dali.zhixingplan.top/Article/details/gt2fwbmaupg.html

PHP:  substr_count($s, "a");
来源：http://dali.yuanzhike.top/Article/details/gt2dwupiurn.html

JS:   s.split("a").length - 1
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lrhrivpz.html

TS:   s.split("a").length - 1
来源：http://dali.daxiang520.top/Article/details/gt2txfosvxs.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yanxiufei.cn/Article/details/gt2ovujxmyp.html

Go:   strings.Count(s, "a")
来源：http://dali.xuetiantiany.cn/Article/details/gt2wksaaqae.html

Ruby: s.count("a")
来源：http://dali.cqqwz.cn/Article/details/gt2jkoyrtym.html

C#:   s.Count(c => c == 'a')
来源：http://dali.ehwqpu.com/Article/details/gt2ckqenwsn.html

[E13] 逐字符遍历
来源：http://dali.316326.xyz/Article/details/gt2wneplpqj.html

Py:   for ch in s: print(ch)
来源：http://dali.zhiwuduotai.top/Article/details/gt2pkesbiok.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.svipenyu.cn/Article/details/gt2qorutkqj.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gaohongyu789.top/Article/details/gt2fdiombdb.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.smart0.xyz/Article/details/gt2bxpazbsl.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.snrcjt.cn/Article/details/gt2jeqlnisb.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.fzhhl.top/Article/details/gt2kxrfepyp.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.nanxinkj.top/Article/details/gt2kelpqwss.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.cheryme.top/Article/details/gt2dlyzbmrq.html

[E14] URL 编码与 Base64
来源：http://dali.wangdashe.top/Article/details/gt2afzzyype.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pgkltgxy.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hfpthk.cn/Article/details/gt2jcgsnfgl.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.cqqwz.cn/Article/details/gt2ykcddzga.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.tanke756.top/Article/details/gt2beaisvrm.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hnxiangtu.top/Article/details/gt2rwdjwiff.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qbpuzlkp.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.shzxlz.cn/Article/details/gt2atdcihsn.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jianghu66.top/Article/details/gt2qlcszejs.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jnowasbl.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.daxiang520.top/Article/details/gt2hrdrbaht.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hysaishi.cn/Article/details/gt2usicuctn.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2clpadiuc.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.guannengcc.top/Article/details/gt2hkpjyiqx.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zycfv.cn/Article/details/gt2vpqyptmy.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.mhx1999.top/Article/details/gt2uatgiuqk.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kbrbugzq.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.ivvv.top/Article/details/gt2yebfijio.html

[E16] 数字千分位
来源：http://dali.quarkkingdee.top/Article/details/gt2cryslepz.html

Py:   f"{1234567:,}"
来源：http://dali.pycfn.com/Article/details/gt2prooirco.html

PHP:  number_format(1234567);
来源：http://dali.hfpthk.cn/Article/details/gt2cpvijcbh.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.hongshengwenyu.top/Article/details/gt2miebjyie.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jqgufenzy.top/Article/details/gt2qsmdxwae.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.iojbl.cn/Article/details/gt2poqmeffe.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yuxming.cn/Article/details/gt2rwvscsgb.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.shanyushiyangtech.top/Article/details/gt2syzlbssc.html

C#:   1234567.ToString("N0")
来源：http://dali.iojbl.cn/Article/details/gt2etswivlf.html

[E17] 首字母大写
来源：http://dali.yuanzhike.top/Article/details/gt2zsrjgjgh.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhoulong.xyz/Article/details/gt2shvsmmjp.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jianghu66.top/Article/details/gt2ccnuzmma.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ppjwa.cn/Article/details/gt2dtinvjef.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jqgfzy.top/Article/details/gt2cqoirkpl.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.tanke756.top/Article/details/gt2ktptrbow.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.316326.xyz/Article/details/gt2vtnfaqao.html

Ruby: s.capitalize
来源：http://dali.yuxming.cn/Article/details/gt2btstbmyr.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.hammf.cn/Article/details/gt2fscgmadn.html

[E18] 模板占位符替换
来源：http://dali.dashuyun.cn/Article/details/gt2hhjjuoll.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.fzhhl.top/Article/details/gt2iqodnhbp.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.dashuyun.cn/Article/details/gt2eoxustjs.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zdqjudy.top/Article/details/gt2zpnqfqkp.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yongpay.top/Article/details/gt2vxwpshum.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.fengsongda.top/Article/details/gt2nnomsyqt.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.gzhubu.top/Article/details/gt2ljbmapgn.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yj20258888.top/Article/details/gt2tbsbsmkf.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jinqigfzy.top/Article/details/gt2xttenczu.html

[E19] 多行文本按行拆分
来源：http://dali.redwolf501.top/Article/details/gt2qebjmdtq.html

Py:   s.splitlines()
来源：http://dali.fzhhl.top/Article/details/gt2nsgecyih.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hnxiangtu.top/Article/details/gt2xszhahns.html

JS:   s.split(/\r?\n/)
来源：http://dali.bjfxy.top/Article/details/gt2zqfurabx.html

TS:   s.split(/\r?\n/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yfndbebu.html

Java: s.lines().toList()
来源：http://dali.zhongyouzk.top/Article/details/gt2xvxdefhh.html

Go:   strings.Split(s, "\n")
来源：http://dali.ehwqpu.com/Article/details/gt2qlgttrro.html


<!-- 参考信息 -->