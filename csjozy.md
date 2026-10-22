代发 wailian999

TS:   [...new Set(arr)]
来源：http://dali.gzhubu.top/Article/details/gt2syqzvjoe.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.316326.xyz/Article/details/gt2jzhfqhzg.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.sysykeji.top/Article/details/gt2oosfuphn.html

Ruby: arr.uniq
来源：http://dali.tian-w.cn/Article/details/gt2rarqkyyk.html

C#:   list.Distinct().ToList()
来源：http://dali.ivvv.top/Article/details/gt2zlbibksm.html

[D16] 求和与平均值
来源：http://dali.chenlongwang.top/Article/details/gt2hddvbepz.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.ybcxt.top/Article/details/gt2yojqrnvj.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhongyouzk.top/Article/details/gt2ggqzakwk.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sufxvd.cn/Article/details/gt2huywcrnx.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.nwbrower.top/Article/details/gt2dvqjqhwg.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hfpthk.cn/Article/details/gt2kignyklv.html

Go:   // 手写循环累加
来源：http://dali.hnxiangtu.top/Article/details/gt2dletwikx.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.ehwqpu.com/Article/details/gt2zdrkomtm.html

C#:   list.Sum();  list.Average()
来源：http://dali.chenjidiqi.icu/Article/details/gt2nzphklic.html

[D17] 最大值与最小值
来源：http://dali.jinqigfzy.top/Article/details/gt2npbiwtmt.html

Py:   max(arr);  min(arr)
来源：http://dali.svipenyu.cn/Article/details/gt2bgcyflhq.html

PHP:  max($arr);  min($arr);
来源：http://dali.shzxlz.cn/Article/details/gt2zxvkxguw.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.fengsongda.top/Article/details/gt2vgtdshod.html

TS:   Math.max(...arr);
来源：http://dali.gotoacloud.top/Article/details/gt2mpjnwzrt.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.guowangkeji.top/Article/details/gt2hhpjgpgo.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.chenlongwang.top/Article/details/gt2qjbfcxwv.html

Ruby: arr.max;  arr.min
来源：http://dali.xziqi.cn/Article/details/gt2rpoweyzv.html

C#:   list.Max();  list.Min()
来源：http://dali.jqgufenzy.top/Article/details/gt2iqoikjad.html

[D18] 扁平化嵌套数组
来源：http://dali.316326.xyz/Article/details/gt2blcvnjhb.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fnxhvfnf.html

PHP:  array_merge(...$nested);
来源：http://dali.mhx1999.top/Article/details/gt2gafxmmne.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.tianlin.xyz/Article/details/gt2nbdcniei.html

TS:   nested.flat();
来源：http://dali.iojbl.cn/Article/details/gt2cwqjqhpq.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yj20258888.top/Article/details/gt2iznybnch.html

Go:   // 手写双层循环
来源：http://dali.hammf.cn/Article/details/gt2oxszcqci.html

Ruby: nested.flatten
来源：http://dali.zhongyouzk.top/Article/details/gt2dgjonijd.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gdmriqnr.html

[D19] 按字段分组
来源：http://dali.aibaodan.cn/Article/details/gt2lxkvmptu.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.sxryk.cn/Article/details/gt2zazympao.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hywenlv.cn/Article/details/gt2zqxfzbse.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.hnxiangtu.top/Article/details/gt2swzkudjz.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.shangyingyoupin.top/Article/details/gt2qxzvarui.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.cheryme.top/Article/details/gt2pwrcdvve.html

Go:   // 手写 map[string][]T
来源：http://dali.sufxvd.cn/Article/details/gt2sasziytc.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.ybcxt.top/Article/details/gt2qzhowjkn.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhengqikj.top/Article/details/gt2njutxvbr.html

[D20] 统计每个元素出现次数
来源：http://dali.zhengqikj.top/Article/details/gt2sofynguh.html

Py:   Counter(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rfkyludk.html

PHP:  array_count_values($arr);
来源：http://dali.iojbl.cn/Article/details/gt2mjrgdvpm.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cucudq.cn/Article/details/gt2yviyxunk.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.fzhhl.top/Article/details/gt2pqmrbioj.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.daria6918.cn/Article/details/gt2vakgiudn.html

Go:   // 手写 map[T]int
来源：http://dali.9152youxi.cn/Article/details/gt2xjsfefxy.html

Ruby: arr.tally
来源：http://dali.gaohongyu789.top/Article/details/gt2patlkzsg.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jqgufenzy.top/Article/details/gt2cnlaywgw.html

[D21] 判断是否包含某元素
来源：http://dali.hongshengwenyu.top/Article/details/gt2vcqjrjns.html

Py:   x in arr
来源：http://dali.xylfe.cn/Article/details/gt2nplddscd.html

PHP:  in_array($x, $arr, true);
来源：http://dali.daxiang520.top/Article/details/gt2iynwzalu.html

JS:   arr.includes(x)
来源：http://dali.ehwqpu.com/Article/details/gt2nkwqbjmt.html

TS:   arr.includes(x)
来源：http://dali.jinqigufen.top/Article/details/gt2kagslubf.html

Java: list.contains(x)
来源：http://dali.yangfankeji.com/Article/details/gt2efwgmnsc.html

Go:   slices.Contains(arr, x)
来源：http://dali.wangdashe.top/Article/details/gt2mzrsyilh.html

Ruby: arr.include?(x)
来源：http://dali.yj20258.top/Article/details/gt2reyxwfbd.html

C#:   list.Contains(x)
来源：http://dali.redwolf501.top/Article/details/gt2gixsioht.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hongshengwenyu.top/Article/details/gt2uhsvkfmu.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.sweek.top/Article/details/gt2idgtqprx.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.dashuyun.cn/Article/details/gt2dcqiktnj.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.pycfn.com/Article/details/gt2jtbnwtlo.html

TS:   [...arr];
来源：http://dali.ppjwa.cn/Article/details/gt2tcilnhid.html

Java: new ArrayList<>(list);
来源：http://dali.xuetiantiany.cn/Article/details/gt2ejibwbxr.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.pycfn.com/Article/details/gt2lknwagwh.html

Ruby: arr.dup;  arr.clone
来源：http://dali.xuanzx.com/Article/details/gt2lsihcabx.html

C#:   new List<int>(list);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pbejkbqf.html

[D23] reduce 累积计算
来源：http://dali.xuetiantiany.cn/Article/details/gt2kokdnrzu.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.nwbrower.top/Article/details/gt2teulfvxs.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.fengsongda.top/Article/details/gt2nbjdrluc.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.kuanghao11.cn/Article/details/gt2yotnzmvk.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.gaohongyu789.top/Article/details/gt2loolkyuj.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.xinyue.icu/Article/details/gt2zmpetgsw.html

Go:   // 手写循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xhkixjja.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.316326.xyz/Article/details/gt2bkgdffnf.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.sufxvd.cn/Article/details/gt2ysfwdnid.html

[D24] 字典 / Map 基本操作
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vxgowozt.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.ydzc1.top/Article/details/gt2vgauhiaq.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yj20258.top/Article/details/gt2idozhuju.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.mhx1999.top/Article/details/gt2bvsejwjq.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.wangdashe.top/Article/details/gt2smxbdpku.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.nanxuanxn.top/Article/details/gt2ibdtkbzu.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yonumen.top/Article/details/gt2xjkolrkg.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.cucudq.cn/Article/details/gt2vpsshfhy.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.0kj1m.cn/Article/details/gt2jdqdelyg.html

[D25] Set 集合去重与交并差
来源：http://dali.nwbrower.top/Article/details/gt2jqnkykij.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.feifeiyinyue.top/Article/details/gt2jwfoeesq.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.kuanghao11.cn/Article/details/gt2oirmnxrp.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.daxiang520.top/Article/details/gt2unsmnoni.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.fzhhl.top/Article/details/gt2fcxuufgz.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.chenzaomai.com/Article/details/gt2yetpbmog.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.snrcjt.cn/Article/details/gt2wwwdhemd.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.nwbrower.top/Article/details/gt2bteztumy.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.bjfxy.top/Article/details/gt2wvlsecsn.html

[D26] 数组转字符串
来源：http://dali.jinqigfzy.top/Article/details/gt2jgvsjdmz.html

Py:   ", ".join(map(str, arr))
来源：http://dali.snrcjt.cn/Article/details/gt2fdrzfuxl.html

PHP:  implode(", ", $arr);
来源：http://dali.xinyue.icu/Article/details/gt2ofinryky.html

JS:   arr.join(", ")
来源：http://dali.meibo888.top/Article/details/gt2xacajndw.html

TS:   arr.join(", ")
来源：http://dali.jianghu66.top/Article/details/gt2ecrhsjbu.html

Java: String.join(", ", list)
来源：http://dali.sufxvd.cn/Article/details/gt2nxxtjqgp.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2xqxqbgko.html

Ruby: arr.join(", ")
来源：http://dali.tanke756.top/Article/details/gt2ycrwqzhq.html

C#:   string.Join(", ", list)
来源：http://dali.yuxming.cn/Article/details/gt2lcojwktb.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2uvaecxtw.html

E. 字符串处理
来源：http://dali.hnqzz.top/Article/details/gt2zfytjhzy.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2nmhbgalp.html

[E01] 拼接字符串
来源：http://dali.tian-w.cn/Article/details/gt2dvuevyyc.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.andypj.xyz/Article/details/gt2eqrwftzb.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.andypj.xyz/Article/details/gt2gnppiuij.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yangfankeji.com/Article/details/gt2dvfwjllv.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cashguo.top/Article/details/gt2prbcbfso.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.xinyue.icu/Article/details/gt2hfgopmoc.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.hongshengwenyu.top/Article/details/gt2egnectjs.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.xziqi.cn/Article/details/gt2xyqvatok.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zycfv.cn/Article/details/gt2ezrbvnem.html

[E02] 重复字符串
来源：http://dali.dashuyun.cn/Article/details/gt2axyazfzi.html

Py:   "ab" * 3
来源：http://dali.yj20258888.top/Article/details/gt2xymjdpdw.html

PHP:  str_repeat("ab", 3);
来源：http://dali.xuanzx.com/Article/details/gt2imztjuye.html

JS:   "ab".repeat(3)
来源：http://dali.gaohongyu789.top/Article/details/gt2zuldnbve.html

TS:   "ab".repeat(3)
来源：http://dali.ybcxt.top/Article/details/gt2nrnfxigk.html

Java: "ab".repeat(3)
来源：http://dali.jinqigufen.top/Article/details/gt2odwnpmpy.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.cucudq.cn/Article/details/gt2ywrcxdks.html

Ruby: "ab" * 3
来源：http://dali.jyoumei.cn/Article/details/gt2gooyvhmg.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.wangshuangyany.cn/Article/details/gt2efiqmaln.html

[E03] 截取子串
来源：http://dali.yj202588.top/Article/details/gt2amncgkge.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.9152youxi.cn/Article/details/gt2exlxmcns.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cnmavbix.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.tanke756.top/Article/details/gt2ermvvsck.html

TS:   s.slice(1, 4)
来源：http://dali.birdmap.top/Article/details/gt2aloyofnn.html

Java: s.substring(1, 4)
来源：http://dali.haohaochexian.top/Article/details/gt2zfmujayr.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yvedp.cn/Article/details/gt2lmiizlpi.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.chenjidiqi.icu/Article/details/gt2qmdzlpnh.html

C#:   s.Substring(1, 3)
来源：http://dali.shangyingyoupin.top/Article/details/gt2vqwyjsbj.html

[E04] 查找子串位置
来源：http://dali.zhongyouzk.top/Article/details/gt2uhnugpbh.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yj202588.top/Article/details/gt2tlvbpaon.html

PHP:  strpos($s, "x");
来源：http://dali.xziqi.cn/Article/details/gt2ikxekzsz.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jiagoushi.top/Article/details/gt2stskfteh.html

TS:   s.indexOf("x")
来源：http://dali.jqgfzy.top/Article/details/gt2hrezxgbp.html

Java: s.indexOf("x")
来源：http://dali.dianchejie.cn/Article/details/gt2murghfqv.html

Go:   strings.Index(s, "x")
来源：http://dali.zycfv.cn/Article/details/gt2xgkkzdrh.html

Ruby: s.index("x")
来源：http://dali.hywenlv.cn/Article/details/gt2ektiityw.html

C#:   s.IndexOf("x")
来源：http://dali.chenlongwang.top/Article/details/gt2twdrthwc.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.ybcxt.top/Article/details/gt2nbunhklv.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jinqigufen.top/Article/details/gt2ncjqrpzy.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.hongshengwenyu.top/Article/details/gt2pvcxdehu.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gaohongyu789.top/Article/details/gt2kebmooec.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yangfankeji.com/Article/details/gt2bffrwzzy.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zycfv.cn/Article/details/gt2jlcpcihw.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.cqqwz.cn/Article/details/gt2qpksemrb.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jyoumei.cn/Article/details/gt2lktbaxdu.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yangfankeji.com/Article/details/gt2okoerlri.html

[E06] 替换子串
来源：http://dali.hysaishi.cn/Article/details/gt2bsvlzitg.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ijacutse.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yongpay.top/Article/details/gt2erhitmqu.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jlsjyb.cn/Article/details/gt2rumdtprz.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gt2yhokomkf.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.316326.xyz/Article/details/gt2numztbvs.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.dianchejie.cn/Article/details/gt2wydqghts.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.quarkkingdee.top/Article/details/gt2kobpvmwc.html

C#:   s.Replace("a", "b")
来源：http://dali.birdmap.top/Article/details/gt2zwhjdigl.html

[E07] 按分隔符拆分
来源：http://dali.zhongyouzk.top/Article/details/gt2iwcoxbfe.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jiagoushi.top/Article/details/gt2jeyiidrg.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.hfpthk.cn/Article/details/gt2tlwgfdje.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.316326.xyz/Article/details/gt2xwfeyzvg.html

TS:   s.split(",")
来源：http://dali.aizwys.cn/Article/details/gt2qreclvlj.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.fengsongda.top/Article/details/gt2ctdeqzaf.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.guowangkeji.top/Article/details/gt2uagpelfl.html

Ruby: s.split(",");  s.split
来源：http://dali.smart0.xyz/Article/details/gt2kkbkejwk.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.dashuyun.cn/Article/details/gt2vazxrwfv.html

[E08] 数组按分隔符合并
来源：http://dali.daria6918.cn/Article/details/gt2wtzrxptv.html

Py:   ",".join(items)
来源：http://dali.jqgufenzy.top/Article/details/gt2soooymiu.html

PHP:  implode(",", $items);
来源：http://dali.yuanzhike.top/Article/details/gt2cknwnmvu.html

JS:   items.join(",")
来源：http://dali.pycfn.com/Article/details/gt2diyqwfkl.html

TS:   items.join(",")
来源：http://dali.wangdashe.top/Article/details/gt2aqjwxkek.html

Java: String.join(",", items)
来源：http://dali.c1oappe.top/Article/details/gt2hdgygcja.html

Go:   strings.Join(items, ",")
来源：http://dali.zhixingplan.top/Article/details/gt2gvdirgul.html

Ruby: items.join(",")
来源：http://dali.sxryk.cn/Article/details/gt2axlgsuaq.html

C#:   string.Join(",", items)
来源：http://dali.mhx1999.top/Article/details/gt2dmjlugkq.html

[E09] 去除所有空白字符
来源：http://dali.yuxming.cn/Article/details/gt2dqhxodba.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.sysykeji.top/Article/details/gt2ntvjottp.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhiwuduotai.top/Article/details/gt2hovtdqcl.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.mhx1999.top/Article/details/gt2iupnwaqo.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.ydzc1.top/Article/details/gt2mfrusgqf.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jqgfzy.top/Article/details/gt2wmiocmkh.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhiwuduotai.top/Article/details/gt2giluvtjk.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yvedp.cn/Article/details/gt2aipkhgcn.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.mhx1999.top/Article/details/gt2hzxpaipm.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jianghu66.top/Article/details/gt2hteufwzd.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yongpay.top/Article/details/gt2uhhfuxet.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.c1oappe.top/Article/details/gt2bupbvumj.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhiwuduotai.top/Article/details/gt2ymwilymq.html

TS:   "7".padStart(3, "0")
来源：http://dali.yueranfly.top/Article/details/gt2rncazcad.html

Java: String.format("%03d", 7)
来源：http://dali.nanxinkj.top/Article/details/gt2hzkupemt.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.snrcjt.cn/Article/details/gt2mxyxtgmx.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.shuidangran.top/Article/details/gt2rrjtrtqj.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.birdmap.top/Article/details/gt2fmoamowv.html

[E11] 反转字符串
来源：http://dali.ivvv.top/Article/details/gt2rpkxbvuw.html

Py:   s[::-1]
来源：http://dali.jinqigufen.top/Article/details/gt2lwgktttn.html

PHP:  strrev($s);
来源：http://dali.chenlongwang.top/Article/details/gt2qmhoxlhh.html

JS:   [...s].reverse().join("")
来源：http://dali.iojbl.cn/Article/details/gt2irsxwvxa.html

TS:   [...s].reverse().join("")
来源：http://dali.yonumen.top/Article/details/gt2jvwgsgye.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhiwuduotai.top/Article/details/gt2dtanvqma.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yonumen.top/Article/details/gt2zvtwikse.html

Ruby: s.reverse
来源：http://dali.yanxiufei.cn/Article/details/gt2zqarcqma.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.haohaochexian.top/Article/details/gt2jaychcwf.html

[E12] 统计某字符出现次数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pxftxxtk.html

Py:   s.count("a")
来源：http://dali.birdmap.top/Article/details/gt2hpvakuqf.html

PHP:  substr_count($s, "a");
来源：http://dali.hammf.cn/Article/details/gt2iwjxlppa.html

JS:   s.split("a").length - 1
来源：http://dali.pengpengdd.cyou/Article/details/gt2tmwksvcm.html

TS:   s.split("a").length - 1
来源：http://dali.zhixingplan.top/Article/details/gt2opxqyuph.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yanxiufei.cn/Article/details/gt2sefprkuw.html

Go:   strings.Count(s, "a")
来源：http://dali.vqdsnc.cn/Article/details/gt2iewmaqcv.html

Ruby: s.count("a")
来源：http://dali.xziqi.cn/Article/details/gt2vnehrmng.html

C#:   s.Count(c => c == 'a')
来源：http://dali.nanxuanxn.top/Article/details/gt2mblvboyk.html

[E13] 逐字符遍历
来源：http://dali.kuanghao11.cn/Article/details/gt2fnlxohzn.html

Py:   for ch in s: print(ch)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cbxlrghl.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.gaohongyu789.top/Article/details/gt2sjnantgz.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cheryme.top/Article/details/gt2juqgcqws.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhoulong.xyz/Article/details/gt2exohfebi.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.meibo888.top/Article/details/gt2vcyzagnm.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.guannengcc.top/Article/details/gt2kywuqwgd.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.fengsongda.top/Article/details/gt2dpavzckp.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.vqdsnc.cn/Article/details/gt2jlmsnhbt.html

[E14] URL 编码与 Base64
来源：http://dali.jinqigfzy.top/Article/details/gt2xjfkgncu.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.gaohongyu789.top/Article/details/gt2ijcbxbhn.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.nanxinkj.top/Article/details/gt2tdtjpxnq.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jyoumei.cn/Article/details/gt2ezztclfj.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.bjfxy.top/Article/details/gt2hdrnyhdc.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yonumen.top/Article/details/gt2qfltsdxy.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.0kj1m.cn/Article/details/gt2ualuhpkd.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.chenjidiqi.icu/Article/details/gt2xzxmvdgv.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jiagoushi.top/Article/details/gt2jvgxgofj.html

[E15] HTML 转义 / 反转义
来源：http://dali.daria6918.cn/Article/details/gt2vryxbnkh.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.bjfxy.top/Article/details/gt2bczefghy.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.tian-w.cn/Article/details/gt2zbxujtmg.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yongpay.top/Article/details/gt2hsqtvikf.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.sxryk.cn/Article/details/gt2pgxsitkj.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yueranfly.top/Article/details/gt2tohcztoa.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.ppjwa.cn/Article/details/gt2chbgxnmc.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.9152youxi.cn/Article/details/gt2sfywlyrb.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.meibo888.top/Article/details/gt2htlhiuus.html

[E16] 数字千分位
来源：http://dali.hnxiangtu.top/Article/details/gt2cjuixwdv.html

Py:   f"{1234567:,}"
来源：http://dali.gzhubu.top/Article/details/gt2ypaqgohg.html

PHP:  number_format(1234567);
来源：http://dali.zhengqikj.top/Article/details/gt2qlxvyztw.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jiagoushi.top/Article/details/gt2ctmmgmay.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.cqqwz.cn/Article/details/gt2ksbfylrp.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.havefunace.top/Article/details/gt2ihoxbavn.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vmdqozxd.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.c1oappe.top/Article/details/gt2bvamzorv.html

C#:   1234567.ToString("N0")
来源：http://dali.hysaishi.cn/Article/details/gt2zentwpxi.html

[E17] 首字母大写
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qesomyxn.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.bjfxy.top/Article/details/gt2fdfvxuwx.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.tanke756.top/Article/details/gt2lnvgmtzb.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.birdmap.top/Article/details/gt2ihpzzria.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.guannengcc.top/Article/details/gt2fzwmnejl.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yanxiufei.cn/Article/details/gt2uzwbrfme.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jyoumei.cn/Article/details/gt2jpfnefld.html

Ruby: s.capitalize
来源：http://dali.yonumen.top/Article/details/gt2yruvusbu.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.bjfxy.top/Article/details/gt2lgxwnzfm.html

[E18] 模板占位符替换
来源：http://dali.yongpay.top/Article/details/gt2feemrnsb.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.xziqi.cn/Article/details/gt2ncfftxlm.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jianghu66.top/Article/details/gt2doagerlr.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jianghu66.top/Article/details/gt2dswldjsw.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yonumen.top/Article/details/gt2wlwpiwiv.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.cqqwz.cn/Article/details/gt2rpywstoi.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.birdmap.top/Article/details/gt2bvufzblw.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.ppjwa.cn/Article/details/gt2lqulcfdq.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.snrcjt.cn/Article/details/gt2vjvwbial.html

[E19] 多行文本按行拆分
来源：http://dali.chenzaomai.com/Article/details/gt2rhmeqzrb.html

Py:   s.splitlines()
来源：http://dali.jqgfzy.top/Article/details/gt2vefqtjrc.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uzbewrnh.html

JS:   s.split(/\r?\n/)
来源：http://dali.tianlin.xyz/Article/details/gt2fcxngroa.html

TS:   s.split(/\r?\n/)
来源：http://dali.xuetiantiany.cn/Article/details/gt2aovbwhms.html

Java: s.lines().toList()
来源：http://dali.c1oappe.top/Article/details/gt2brlavyzm.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cfnecfqt.html

Ruby: s.lines
来源：http://dali.iojbl.cn/Article/details/gt2lqndwswr.html

C#:   s.Split('\n')
来源：http://dali.shuidangran.top/Article/details/gt2kwdrbxcg.html

[E20] 判断字符串是否为空
来源：http://dali.zhiwuduotai.top/Article/details/gt2aqyjmbsr.html

Py:   if not s:
来源：http://dali.fzhhl.top/Article/details/gt2xeeflnns.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tdwimhat.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.aizwys.cn/Article/details/gt2grvwivoc.html

TS:   if (s === "") {}
来源：http://dali.aibaodan.cn/Article/details/gt2wlazczhc.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhengqikj.top/Article/details/gt2qjsjmqjd.html

Go:   if s == "" {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kuvwdmun.html

Ruby: if s.empty?
来源：http://dali.zhixingplan.top/Article/details/gt2uwupjolr.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hywenlv.cn/Article/details/gt2zistxtbv.html

[E21] 超长截断加省略号
来源：http://dali.kuanghao11.cn/Article/details/gt2nliioaro.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.vqdsnc.cn/Article/details/gt2qzpsauqg.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhongyouzk.top/Article/details/gt2rduuiaiu.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.dianchejie.cn/Article/details/gt2onbdkjkl.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hysaishi.cn/Article/details/gt2nfruzugr.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.feifeiyinyue.top/Article/details/gt2dkdxdmwd.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hywenlv.cn/Article/details/gt2kancfvjc.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2tejfxuxz.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lxhcanpy.html

[E22] 字节长度与字符长度
来源：http://dali.c1oappe.top/Article/details/gt2uzfjheuh.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.tian-w.cn/Article/details/gt2mbroylpz.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yj202588.top/Article/details/gt2qdnuiuwt.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.mhx1999.top/Article/details/gt2usehrieo.html


<!-- 参考信息 -->