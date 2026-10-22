代发 wailian999

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.ybcxt.top/Article/details/gt2fsmwpnxl.html

JS:   arr.filter(x => x > 3)
来源：http://dali.haohaochexian.top/Article/details/gt2hjynpmaf.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jqgufenzy.top/Article/details/gt2mmetarjh.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jianghu66.top/Article/details/gt2rsxhqytg.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hnqzz.top/Article/details/gt2hrlezscw.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.vqdsnc.cn/Article/details/gt2vmhbutzw.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.cashguo.top/Article/details/gt2wjdokcth.html

[D14] 映射转换（每个元素变形）
来源：http://dali.316326.xyz/Article/details/gt2zccaxzdw.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.xylfe.cn/Article/details/gt2pnhylang.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.gotoacloud.top/Article/details/gt2bmixuhqg.html

JS:   arr.map(x => x * 2)
来源：http://dali.bjfxy.top/Article/details/gt2qtwfpxms.html

TS:   arr.map(x => x * 2)
来源：http://dali.316326.xyz/Article/details/gt2pcucukpe.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.iojbl.cn/Article/details/gt2zuycxcvn.html

Go:   // 手写循环
来源：http://dali.9152youxi.cn/Article/details/gt2qxzwepxc.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.sxryk.cn/Article/details/gt2zorqarkq.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.meibo888.top/Article/details/gt2mkerfasm.html

[D15] 去重
来源：http://dali.pycfn.com/Article/details/gt2chkcnghb.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jinqigufen.top/Article/details/gt2mhqnemxx.html

PHP:  array_unique($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gt2wiscdkjf.html

JS:   [...new Set(arr)]
来源：http://dali.dashuyun.cn/Article/details/gt2vgcxcdyq.html

TS:   [...new Set(arr)]
来源：http://dali.jianghu66.top/Article/details/gt2youfnxle.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.mhx1999.top/Article/details/gt2uxcrokkd.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.andypj.xyz/Article/details/gt2vleyzmcb.html

Ruby: arr.uniq
来源：http://dali.yangfankeji.com/Article/details/gt2qjkgopty.html

C#:   list.Distinct().ToList()
来源：http://dali.zhixingplan.top/Article/details/gt2bnrvuzet.html

[D16] 求和与平均值
来源：http://dali.shangyingyoupin.top/Article/details/gt2kfmojzbc.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.meibo888.top/Article/details/gt2aqkazqzk.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.redwolf501.top/Article/details/gt2pcouukzl.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cvfdjicg.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hywenlv.cn/Article/details/gt2moqanvds.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jqgufenzy.top/Article/details/gt2yjjcoekp.html

Go:   // 手写循环累加
来源：http://dali.kuanghao11.cn/Article/details/gt2ivwupjjf.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhixingplan.top/Article/details/gt2qlkaqhrs.html

C#:   list.Sum();  list.Average()
来源：http://dali.yonumen.top/Article/details/gt2qvoocqzk.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2vapplorj.html

Py:   max(arr);  min(arr)
来源：http://dali.yvedp.cn/Article/details/gt2ekangwdj.html

PHP:  max($arr);  min($arr);
来源：http://dali.zdqjudy.top/Article/details/gt2betvizmv.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.aizwys.cn/Article/details/gt2qkybkxlz.html

TS:   Math.max(...arr);
来源：http://dali.meibo888.top/Article/details/gt2rxgujons.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.9152youxi.cn/Article/details/gt2shbousmh.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.chenlongwang.top/Article/details/gt2abacrwri.html

Ruby: arr.max;  arr.min
来源：http://dali.xziqi.cn/Article/details/gt2vhbgtwoc.html

C#:   list.Max();  list.Min()
来源：http://dali.zdqjudy.top/Article/details/gt2qjllebsy.html

[D18] 扁平化嵌套数组
来源：http://dali.zhoulong.xyz/Article/details/gt2mqbaovhc.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jiagoushi.top/Article/details/gt2rpssvpie.html

PHP:  array_merge(...$nested);
来源：http://dali.daxiang520.top/Article/details/gt2gymnaiha.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jqgufenzy.top/Article/details/gt2bbgaugtp.html

TS:   nested.flat();
来源：http://dali.hnxiangtu.top/Article/details/gt2dusunfcy.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cqkactag.html

Go:   // 手写双层循环
来源：http://dali.sufxvd.cn/Article/details/gt2tsumexxd.html

Ruby: nested.flatten
来源：http://dali.yvedp.cn/Article/details/gt2pzclaawx.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.ppjwa.cn/Article/details/gt2hirftjfu.html

[D19] 按字段分组
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2axlbmvms.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.ehwqpu.com/Article/details/gt2bgojjnhh.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.andypj.xyz/Article/details/gt2vjilqukb.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yonumen.top/Article/details/gt2fovuwdgr.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.hywenlv.cn/Article/details/gt2swgmqewh.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.feifeiyinyue.top/Article/details/gt2biexztqs.html

Go:   // 手写 map[string][]T
来源：http://dali.yuanzhike.top/Article/details/gt2jmeesljd.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.316326.xyz/Article/details/gt2ptdypnoy.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yj202588.top/Article/details/gt2fgflkyfp.html

[D20] 统计每个元素出现次数
来源：http://dali.tianlin.xyz/Article/details/gt2rsdixcrv.html

Py:   Counter(arr)
来源：http://dali.xuanzx.com/Article/details/gt2jyjcmwtk.html

PHP:  array_count_values($arr);
来源：http://dali.pycfn.com/Article/details/gt2yrgszlin.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.chenzaomai.com/Article/details/gt2smpmfppx.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ppjwa.cn/Article/details/gt2jckrdosn.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zxtncwya.html

Go:   // 手写 map[T]int
来源：http://dali.c1oappe.top/Article/details/gt2iktfnntg.html

Ruby: arr.tally
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xpjmfyjz.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.wangshuangyany.cn/Article/details/gt2pvnonobc.html

[D21] 判断是否包含某元素
来源：http://dali.mhx1999.top/Article/details/gt2guonnasd.html

Py:   x in arr
来源：http://dali.nwbrower.top/Article/details/gt2zzdfycrs.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yanxiufei.cn/Article/details/gt2lyodlslc.html

JS:   arr.includes(x)
来源：http://dali.birdmap.top/Article/details/gt2qpsianln.html

TS:   arr.includes(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xqqbifok.html

Java: list.contains(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kovdiqos.html

Go:   slices.Contains(arr, x)
来源：http://dali.hysaishi.cn/Article/details/gt2jtlniesj.html

Ruby: arr.include?(x)
来源：http://dali.daria6918.cn/Article/details/gt2mylczgxl.html

C#:   list.Contains(x)
来源：http://dali.ivvv.top/Article/details/gt2ldzwkopt.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hnqzz.top/Article/details/gt2xckveciw.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.tianlin.xyz/Article/details/gt2famuwzdg.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.9152youxi.cn/Article/details/gt2flkxbcbc.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.tanke756.top/Article/details/gt2dbyyastm.html

TS:   [...arr];
来源：http://dali.cheryme.top/Article/details/gt2nqyitngk.html

Java: new ArrayList<>(list);
来源：http://dali.ydzc1.top/Article/details/gt2xitrvjxs.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.meibo888.top/Article/details/gt2jyqohwjg.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jyoumei.cn/Article/details/gt2nlonrfbt.html

C#:   new List<int>(list);
来源：http://dali.chenlongwang.top/Article/details/gt2wxilslcb.html

[D23] reduce 累积计算
来源：http://dali.zhongyouzk.top/Article/details/gt2jctksmfa.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhixingplan.top/Article/details/gt2bqpodikd.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.snrcjt.cn/Article/details/gt2pompvqbk.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sweek.top/Article/details/gt2ggiupfwg.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pwyctwgl.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.cqqwz.cn/Article/details/gt2wxlwwyjk.html

Go:   // 手写循环
来源：http://dali.zhengqikj.top/Article/details/gt2cgrqwbvi.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.havefunace.top/Article/details/gt2ezqyxvai.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yanxiufei.cn/Article/details/gt2bbeqgiyd.html

[D24] 字典 / Map 基本操作
来源：http://dali.chenlongwang.top/Article/details/gt2pgcqlatc.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.gzhubu.top/Article/details/gt2ecgsberz.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.shangyingyoupin.top/Article/details/gt2lyczwaav.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.guannengcc.top/Article/details/gt2rslnjaqi.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jlsjyb.cn/Article/details/gt2tbgfmfsw.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.xziqi.cn/Article/details/gt2cmjqogzr.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.kuanghao11.cn/Article/details/gt2odwbgyao.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.xuanzx.com/Article/details/gt2ujfavftz.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.nanxinkj.top/Article/details/gt2hnmhhkwd.html

[D25] Set 集合去重与交并差
来源：http://dali.hywenlv.cn/Article/details/gt2bqathdjh.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.ydzc1.top/Article/details/gt2hvtvxgjf.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.ivvv.top/Article/details/gt2tihyfchb.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2kxpyxwvz.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhiwuduotai.top/Article/details/gt2vxpznvqj.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.xziqi.cn/Article/details/gt2jonukwoe.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hammf.cn/Article/details/gt2lrshmydv.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.dashuyun.cn/Article/details/gt2qswalldu.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.tianlin.xyz/Article/details/gt2pypldyxx.html

[D26] 数组转字符串
来源：http://dali.zdqjudy.top/Article/details/gt2vlpbxzft.html

Py:   ", ".join(map(str, arr))
来源：http://dali.nwbrower.top/Article/details/gt2lzutpkbi.html

PHP:  implode(", ", $arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wyoljbhr.html

JS:   arr.join(", ")
来源：http://dali.0kj1m.cn/Article/details/gt2hzytfspw.html

TS:   arr.join(", ")
来源：http://dali.daria6918.cn/Article/details/gt2gehynnzx.html

Java: String.join(", ", list)
来源：http://dali.bjfxy.top/Article/details/gt2uophtooe.html

Go:   strings.Join(strs, ", ")
来源：http://dali.ydzc1.top/Article/details/gt2fdhmlhlz.html

Ruby: arr.join(", ")
来源：http://dali.nanxinkj.top/Article/details/gt2subpmuxw.html

C#:   string.Join(", ", list)
来源：http://dali.andypj.xyz/Article/details/gt2cwgysjrn.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2bcvnsjyy.html

E. 字符串处理
来源：http://dali.9152youxi.cn/Article/details/gt2ykoucnmj.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2sxvayvjw.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ydujmoif.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yujmhxgw.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yj20258.top/Article/details/gt2buitqzmo.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.feifeiyinyue.top/Article/details/gt2ndqpevxd.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.smart0.xyz/Article/details/gt2ahepwimj.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ketmbhrb.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhixingplan.top/Article/details/gt2uxyczkfy.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.shuidangran.top/Article/details/gt2nrznwlye.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zdqjudy.top/Article/details/gt2semuurup.html

[E02] 重复字符串
来源：http://dali.yongpay.top/Article/details/gt2dfljnfuz.html

Py:   "ab" * 3
来源：http://dali.shangyingyoupin.top/Article/details/gt2yywjqiie.html

PHP:  str_repeat("ab", 3);
来源：http://dali.haohaochexian.top/Article/details/gt2rotvjgeq.html

JS:   "ab".repeat(3)
来源：http://dali.svipenyu.cn/Article/details/gt2ztonnqdo.html

TS:   "ab".repeat(3)
来源：http://dali.tanke756.top/Article/details/gt2wqziobxl.html

Java: "ab".repeat(3)
来源：http://dali.zhiwuduotai.top/Article/details/gt2mkbemmtp.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.sufxvd.cn/Article/details/gt2shahdqfu.html

Ruby: "ab" * 3
来源：http://dali.daxiang520.top/Article/details/gt2eifyupqr.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.mhx1999.top/Article/details/gt2jjmvkrpv.html

[E03] 截取子串
来源：http://dali.daxiang520.top/Article/details/gt2nqclwlvl.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.hfpthk.cn/Article/details/gt2iocwllzx.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.chenjidiqi.icu/Article/details/gt2vnvoxpai.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.gogol.net.cn/Article/details/gt2kuxjpymg.html

TS:   s.slice(1, 4)
来源：http://dali.svipenyu.cn/Article/details/gt2newlkzra.html

Java: s.substring(1, 4)
来源：http://dali.feifeiyinyue.top/Article/details/gt2xstgjvzm.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.haohaochexian.top/Article/details/gt2wmqbjmpz.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.xuetiantiany.cn/Article/details/gt2dnzowtgv.html

C#:   s.Substring(1, 3)
来源：http://dali.ehwqpu.com/Article/details/gt2pkvazihm.html

[E04] 查找子串位置
来源：http://dali.chenjidiqi.icu/Article/details/gt2nfnwgqps.html

Py:   s.find("x");  s.index("x")
来源：http://dali.cdnleiting.top/Article/details/gt2ylduvyii.html

PHP:  strpos($s, "x");
来源：http://dali.redwolf501.top/Article/details/gt2rhetfrbw.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qgwbolde.html

TS:   s.indexOf("x")
来源：http://dali.dashuyun.cn/Article/details/gt2gdfkyrqw.html

Java: s.indexOf("x")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zqezmlyc.html

Go:   strings.Index(s, "x")
来源：http://dali.cqqwz.cn/Article/details/gt2pugrcdlr.html

Ruby: s.index("x")
来源：http://dali.zdqjudy.top/Article/details/gt2ogjyozdt.html

C#:   s.IndexOf("x")
来源：http://dali.svipenyu.cn/Article/details/gt2libqxgks.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.ydzc1.top/Article/details/gt2rfjsybmc.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.316326.xyz/Article/details/gt2kpwdfrxw.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.cashguo.top/Article/details/gt2wyvxgkcj.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2nkjuofdy.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.sweek.top/Article/details/gt2izqxsilj.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yuanzhike.top/Article/details/gt2qzxrzfvp.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.tanke756.top/Article/details/gt2ktzvrzqi.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.guannengcc.top/Article/details/gt2tedsmmht.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.cashguo.top/Article/details/gt2irflvayq.html

[E06] 替换子串
来源：http://dali.0kj1m.cn/Article/details/gt2layblyyv.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.mhx1999.top/Article/details/gt2pbfpvvhm.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhongyouzk.top/Article/details/gt2sftxxvpo.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.mhx1999.top/Article/details/gt2jghwddzn.html

TS:   s.replaceAll("a", "b")
来源：http://dali.snrcjt.cn/Article/details/gt2okrpfqsb.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hnqzz.top/Article/details/gt2qaurkxbc.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2imeapxbi.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.mhx1999.top/Article/details/gt2kwlfvjgc.html

C#:   s.Replace("a", "b")
来源：http://dali.sysykeji.top/Article/details/gt2mbptuyog.html

[E07] 按分隔符拆分
来源：http://dali.zhiwuduotai.top/Article/details/gt2eiybhlty.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.feifeiyinyue.top/Article/details/gt2bbcbixql.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gt2rvmglhux.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhiwuduotai.top/Article/details/gt2pffrlqek.html

TS:   s.split(",")
来源：http://dali.hfpthk.cn/Article/details/gt2xiwbykso.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yonumen.top/Article/details/gt2jjsseyuy.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.redwolf501.top/Article/details/gt2kxflcfzp.html

Ruby: s.split(",");  s.split
来源：http://dali.gaohongyu789.top/Article/details/gt2anrdkzbo.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.sufxvd.cn/Article/details/gt2bilopsjt.html

[E08] 数组按分隔符合并
来源：http://dali.meibo888.top/Article/details/gt2wvicdnvc.html

Py:   ",".join(items)
来源：http://dali.cheryme.top/Article/details/gt2wbkowpqc.html

PHP:  implode(",", $items);
来源：http://dali.kuanghao11.cn/Article/details/gt2tdiwiczh.html

JS:   items.join(",")
来源：http://dali.tianlin.xyz/Article/details/gt2kutytilj.html

TS:   items.join(",")
来源：http://dali.ydzc1.top/Article/details/gt2gbkmktmu.html

Java: String.join(",", items)
来源：http://dali.cheryme.top/Article/details/gt2gtuhoshh.html

Go:   strings.Join(items, ",")
来源：http://dali.daria6918.cn/Article/details/gt2skbendeu.html

Ruby: items.join(",")
来源：http://dali.chenlongwang.top/Article/details/gt2qefxjgfd.html

C#:   string.Join(",", items)
来源：http://dali.guannengcc.top/Article/details/gt2sizutvdq.html

[E09] 去除所有空白字符
来源：http://dali.gogol.net.cn/Article/details/gt2iqdtzrka.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.nwbrower.top/Article/details/gt2cngeetjb.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.wangdashe.top/Article/details/gt2aqnmlfrh.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.mhx1999.top/Article/details/gt2apoezogy.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.kuanghao11.cn/Article/details/gt2rlyaendz.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zdqjudy.top/Article/details/gt2gfsznxdq.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.hammf.cn/Article/details/gt2ypevoaij.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.nwbrower.top/Article/details/gt2hglblywz.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.ydzc1.top/Article/details/gt2zjacwmeu.html

[E10] 左侧补零 / 定长填充
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2njnarqhr.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.tianlin.xyz/Article/details/gt2ptvswqja.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.cashguo.top/Article/details/gt2nhwrlqof.html

JS:   "7".padStart(3, "0")
来源：http://dali.ehwqpu.com/Article/details/gt2nlzekcqt.html

TS:   "7".padStart(3, "0")
来源：http://dali.sxryk.cn/Article/details/gt2wfhfzldd.html

Java: String.format("%03d", 7)
来源：http://dali.dashuyun.cn/Article/details/gt2tsgpwkmt.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.chenlongwang.top/Article/details/gt2nrpabizl.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.ydzc1.top/Article/details/gt2hvmaoqcs.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yvedp.cn/Article/details/gt2hutglwpk.html

[E11] 反转字符串
来源：http://dali.316326.xyz/Article/details/gt2jkkkdfdi.html

Py:   s[::-1]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tnxibctv.html

PHP:  strrev($s);
来源：http://dali.jyoumei.cn/Article/details/gt2ftdaorlk.html

JS:   [...s].reverse().join("")
来源：http://dali.ivvv.top/Article/details/gt2xtjwlrtv.html

TS:   [...s].reverse().join("")
来源：http://dali.redwolf501.top/Article/details/gt2urltards.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.sxryk.cn/Article/details/gt2swggyqfj.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.fzhhl.top/Article/details/gt2ekfmutxf.html

Ruby: s.reverse
来源：http://dali.nwbrower.top/Article/details/gt2zjaurpws.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.kuanghao11.cn/Article/details/gt2raiiqkla.html

[E12] 统计某字符出现次数
来源：http://dali.zycfv.cn/Article/details/gt2pqeujdlb.html

Py:   s.count("a")
来源：http://dali.hysaishi.cn/Article/details/gt2jtzrustx.html

PHP:  substr_count($s, "a");
来源：http://dali.yangfankeji.com/Article/details/gt2eicftbbx.html

JS:   s.split("a").length - 1
来源：http://dali.daxiang520.top/Article/details/gt2ggkxjaji.html

TS:   s.split("a").length - 1
来源：http://dali.sxryk.cn/Article/details/gt2rypytlqf.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.haohaochexian.top/Article/details/gt2ujowhgqn.html

Go:   strings.Count(s, "a")
来源：http://dali.dianchejie.cn/Article/details/gt2ssfmbohe.html

Ruby: s.count("a")
来源：http://dali.chenjidiqi.icu/Article/details/gt2lstcnvpg.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xuetiantiany.cn/Article/details/gt2lyxrcvwz.html

[E13] 逐字符遍历
来源：http://dali.shangyingyoupin.top/Article/details/gt2gsnkdynj.html

Py:   for ch in s: print(ch)
来源：http://dali.guowangkeji.top/Article/details/gt2dxnpupnj.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.wangdashe.top/Article/details/gt2kklwsskk.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.fzhhl.top/Article/details/gt2hmlfnhmm.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xinyue.icu/Article/details/gt2wyoljtqw.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.aibaodan.cn/Article/details/gt2iftyqucc.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.cheryme.top/Article/details/gt2dewqkszs.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.nanxuanxn.top/Article/details/gt2fpjmoyiq.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hfpthk.cn/Article/details/gt2imnsosog.html

[E14] URL 编码与 Base64
来源：http://dali.zhiwuduotai.top/Article/details/gt2wwnsiexk.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yonumen.top/Article/details/gt2jytgxvhg.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jlsjyb.cn/Article/details/gt2pwudnqmx.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.chenjidiqi.icu/Article/details/gt2mhumxzli.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yongpay.top/Article/details/gt2tavjhgal.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yj202588.top/Article/details/gt2ljotudkf.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.cdnleiting.top/Article/details/gt2hkymwlfi.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.daxiang520.top/Article/details/gt2zmebsuip.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.shzxlz.cn/Article/details/gt2kifxhaud.html

[E15] HTML 转义 / 反转义
来源：http://dali.ydzc1.top/Article/details/gt2mgvfyqpx.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.ybcxt.top/Article/details/gt2mkqludkv.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.pycfn.com/Article/details/gt2wbrmhodu.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hywenlv.cn/Article/details/gt2mqyorsiu.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.gogol.net.cn/Article/details/gt2yaemtfth.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jqgfzy.top/Article/details/gt2rlspknvt.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2omlkdadr.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2aoehrwdg.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.gzhubu.top/Article/details/gt2mmfgkxal.html

[E16] 数字千分位
来源：http://dali.chenjidiqi.icu/Article/details/gt2ezejchmo.html

Py:   f"{1234567:,}"
来源：http://dali.xuetiantiany.cn/Article/details/gt2ucyrwswk.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2cswnwtmw.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ybcxt.top/Article/details/gt2jtvzhazj.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.cheryme.top/Article/details/gt2ktrahwhw.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hongshengwenyu.top/Article/details/gt2wxyfbmea.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.wangdashe.top/Article/details/gt2jmrekxwr.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.ppjwa.cn/Article/details/gt2ivutxhnt.html

C#:   1234567.ToString("N0")
来源：http://dali.hnqzz.top/Article/details/gt2pnkdinbr.html

[E17] 首字母大写
来源：http://dali.nwbrower.top/Article/details/gt2qvjxtlyk.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.316326.xyz/Article/details/gt2azprfaqa.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wytcbmnd.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.nanxuanxn.top/Article/details/gt2zaurhhmq.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hywenlv.cn/Article/details/gt2ltctmdir.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mdbcpefy.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jqgfzy.top/Article/details/gt2vxzvzksp.html

Ruby: s.capitalize
来源：http://dali.guowangkeji.top/Article/details/gt2assydskr.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.cucudq.cn/Article/details/gt2qvdhzubj.html

[E18] 模板占位符替换
来源：http://dali.ivvv.top/Article/details/gt2dsjiibqu.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.andypj.xyz/Article/details/gt2crxinupg.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yj20258888.top/Article/details/gt2fezgkjpo.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.fzhhl.top/Article/details/gt2jbsgmvpm.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eqikthyp.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xziqi.cn/Article/details/gt2gxrkvuxs.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.fengsongda.top/Article/details/gt2cpfapsml.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.aibaodan.cn/Article/details/gt2kwzfcbmn.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jqgfzy.top/Article/details/gt2bmsfyefx.html

[E19] 多行文本按行拆分
来源：http://dali.yj20258888.top/Article/details/gt2ttsnhixy.html

Py:   s.splitlines()
来源：http://dali.cheryme.top/Article/details/gt2ministzm.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.chenlongwang.top/Article/details/gt2cjikorcv.html

JS:   s.split(/\r?\n/)
来源：http://dali.jinqigfzy.top/Article/details/gt2noiehbva.html

TS:   s.split(/\r?\n/)
来源：http://dali.aizwys.cn/Article/details/gt2gfdcnqij.html

Java: s.lines().toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nraqwttf.html

Go:   strings.Split(s, "\n")
来源：http://dali.hnqzz.top/Article/details/gt2iddjbojc.html

Ruby: s.lines
来源：http://dali.gotoacloud.top/Article/details/gt2septuoze.html

C#:   s.Split('\n')
来源：http://dali.yonumen.top/Article/details/gt2xxpyftbt.html

[E20] 判断字符串是否为空
来源：http://dali.wangdashe.top/Article/details/gt2klhsrofu.html

Py:   if not s:
来源：http://dali.yj202588.top/Article/details/gt2kxywelzs.html


<!-- 参考信息 -->