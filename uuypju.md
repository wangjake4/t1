代发 wailian999

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhixingplan.top/Article/details/gt2twozmhvg.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sysykeji.top/Article/details/gt2bsrrxftx.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.gzhubu.top/Article/details/gt2hjurnjbi.html

Go:   // 手写循环累加
来源：http://dali.sweek.top/Article/details/gt2yarwksrm.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.birdmap.top/Article/details/gt2qshcpnyg.html

C#:   list.Sum();  list.Average()
来源：http://dali.nanxuanxn.top/Article/details/gt2ebnjawdn.html

[D17] 最大值与最小值
来源：http://dali.sxryk.cn/Article/details/gt2nkdmfrpd.html

Py:   max(arr);  min(arr)
来源：http://dali.yueranfly.top/Article/details/gt2vyccudkp.html

PHP:  max($arr);  min($arr);
来源：http://dali.xinyue.icu/Article/details/gt2ikkrlimq.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.gzhubu.top/Article/details/gt2yjgchaee.html

TS:   Math.max(...arr);
来源：http://dali.cqqwz.cn/Article/details/gt2oqnnvjww.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.xuetiantiany.cn/Article/details/gt2qlvwylax.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kkfwqllj.html

Ruby: arr.max;  arr.min
来源：http://dali.meibo888.top/Article/details/gt2amynwegz.html

C#:   list.Max();  list.Min()
来源：http://dali.hnqzz.top/Article/details/gt2zheiukap.html

[D18] 扁平化嵌套数组
来源：http://dali.xziqi.cn/Article/details/gt2mkhuxniy.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhoulong.xyz/Article/details/gt2ofarxhmp.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2hlepmdmg.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jinqigufen.top/Article/details/gt2fylbqucc.html

TS:   nested.flat();
来源：http://dali.andypj.xyz/Article/details/gt2aqczmvoz.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yueranfly.top/Article/details/gt2rpijfyqr.html

Go:   // 手写双层循环
来源：http://dali.pengpengdd.cyou/Article/details/gt2qayupund.html

Ruby: nested.flatten
来源：http://dali.feifeiyinyue.top/Article/details/gt2klfmrice.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hywenlv.cn/Article/details/gt2nrbqkbes.html

[D19] 按字段分组
来源：http://dali.wangshuangyany.cn/Article/details/gt2qyyvshfy.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.ppjwa.cn/Article/details/gt2wldjvswh.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.cqqwz.cn/Article/details/gt2bkqpqrye.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.xziqi.cn/Article/details/gt2iwuvxoqs.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.snrcjt.cn/Article/details/gt2ynmsqjay.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hysaishi.cn/Article/details/gt2ejjenstt.html

Go:   // 手写 map[string][]T
来源：http://dali.zhoulong.xyz/Article/details/gt2qmcgmfoh.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.tianlin.xyz/Article/details/gt2ndfhzlwp.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yanxiufei.cn/Article/details/gt2kmdcrqps.html

[D20] 统计每个元素出现次数
来源：http://dali.dianchejie.cn/Article/details/gt2deslbmyv.html

Py:   Counter(arr)
来源：http://dali.gotoacloud.top/Article/details/gt2pxbkgnvs.html

PHP:  array_count_values($arr);
来源：http://dali.nwbrower.top/Article/details/gt2fxgrlnuj.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hywenlv.cn/Article/details/gt2sytjcsvm.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.fzhhl.top/Article/details/gt2yvgxmemk.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.redwolf501.top/Article/details/gt2dbkyuerr.html

Go:   // 手写 map[T]int
来源：http://dali.redwolf501.top/Article/details/gt2meobjhsf.html

Ruby: arr.tally
来源：http://dali.0kj1m.cn/Article/details/gt2xnfvgggs.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yongpay.top/Article/details/gt2qotbafiy.html

[D21] 判断是否包含某元素
来源：http://dali.ybcxt.top/Article/details/gt2vtsmxnmj.html

Py:   x in arr
来源：http://dali.meibo888.top/Article/details/gt2uitrmnvm.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jiagoushi.top/Article/details/gt2coruvrri.html

JS:   arr.includes(x)
来源：http://dali.daxiang520.top/Article/details/gt2aunflimp.html

TS:   arr.includes(x)
来源：http://dali.yuanzhike.top/Article/details/gt2nyskholg.html

Java: list.contains(x)
来源：http://dali.tanke756.top/Article/details/gt2ddhorups.html

Go:   slices.Contains(arr, x)
来源：http://dali.kuanghao11.cn/Article/details/gt2ykpvaoxa.html

Ruby: arr.include?(x)
来源：http://dali.yj20258.top/Article/details/gt2xgfdlxln.html

C#:   list.Contains(x)
来源：http://dali.sweek.top/Article/details/gt2bujgtsgc.html

[D22] 复制数组（避免共享引用）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bpqwscqw.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.daria6918.cn/Article/details/gt2yvcuqklu.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.aibaodan.cn/Article/details/gt2mniqanbp.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.gotoacloud.top/Article/details/gt2smsqcizl.html

TS:   [...arr];
来源：http://dali.andypj.xyz/Article/details/gt2rgowbmge.html

Java: new ArrayList<>(list);
来源：http://dali.hnqzz.top/Article/details/gt2gwvykcwf.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jinqigfzy.top/Article/details/gt2frsysmqa.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jianghu66.top/Article/details/gt2ximbezzj.html

C#:   new List<int>(list);
来源：http://dali.andypj.xyz/Article/details/gt2ewcyfyhw.html

[D23] reduce 累积计算
来源：http://dali.havefunace.top/Article/details/gt2cwfchuxn.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.fzhhl.top/Article/details/gt2cvotwkgm.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.tianlin.xyz/Article/details/gt2wvumgdvm.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hysaishi.cn/Article/details/gt2hazyqwco.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.redwolf501.top/Article/details/gt2zjduokkf.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.mhx1999.top/Article/details/gt2tqwlkvcf.html

Go:   // 手写循环
来源：http://dali.hysaishi.cn/Article/details/gt2vkedweop.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.daria6918.cn/Article/details/gt2nizljznt.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jinqigfzy.top/Article/details/gt2mrxuxcqp.html

[D24] 字典 / Map 基本操作
来源：http://dali.dianchejie.cn/Article/details/gt2bhdjqwny.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhoulong.xyz/Article/details/gt2aajdtded.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.fzhhl.top/Article/details/gt2oyvlobra.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.xinyue.icu/Article/details/gt2nyyuwxai.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.hysaishi.cn/Article/details/gt2eojwjfbe.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.andypj.xyz/Article/details/gt2cgtaodjh.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.cdnleiting.top/Article/details/gt2uknbzqkk.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.cucudq.cn/Article/details/gt2lrxwizvt.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.ydzc1.top/Article/details/gt2handpcym.html

[D25] Set 集合去重与交并差
来源：http://dali.shangyingyoupin.top/Article/details/gt2zezagltr.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.316326.xyz/Article/details/gt2zmbapklo.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jinghuilouyu.cn/Article/details/gt2phugikhi.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ulgyfhwu.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jiagoushi.top/Article/details/gt2tptgyfxn.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.0kj1m.cn/Article/details/gt2nnzcjqml.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.316326.xyz/Article/details/gt2aylfhhzf.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.316326.xyz/Article/details/gt2xixmmkew.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.316326.xyz/Article/details/gt2bwjmjdyh.html

[D26] 数组转字符串
来源：http://dali.sxryk.cn/Article/details/gt2onckfgqs.html

Py:   ", ".join(map(str, arr))
来源：http://dali.ehwqpu.com/Article/details/gt2snwwmhex.html

PHP:  implode(", ", $arr);
来源：http://dali.sysykeji.top/Article/details/gt2ohnuptze.html

JS:   arr.join(", ")
来源：http://dali.chenlongwang.top/Article/details/gt2pwfpbbux.html

TS:   arr.join(", ")
来源：http://dali.guannengcc.top/Article/details/gt2njdnsyma.html

Java: String.join(", ", list)
来源：http://dali.xuetiantiany.cn/Article/details/gt2avzdeyll.html

Go:   strings.Join(strs, ", ")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pggipsty.html

Ruby: arr.join(", ")
来源：http://dali.jyoumei.cn/Article/details/gt2uarzgpwv.html

C#:   string.Join(", ", list)
来源：http://dali.jyoumei.cn/Article/details/gt2keuqlvnu.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2nuqncdcv.html

E. 字符串处理
来源：http://dali.yj202588.top/Article/details/gt2cdspeqrv.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2hzhizfyf.html

[E01] 拼接字符串
来源：http://dali.hongshengwenyu.top/Article/details/gt2fbvbhleb.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.haohaochexian.top/Article/details/gt2ujglnftr.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yonumen.top/Article/details/gt2ybklkqvt.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.vqdsnc.cn/Article/details/gt2ykzmibfn.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ybcxt.top/Article/details/gt2gljiewvc.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.sysykeji.top/Article/details/gt2ibmekwca.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.gotoacloud.top/Article/details/gt2zgehdvae.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jlsjyb.cn/Article/details/gt2echgxjpt.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.shzxlz.cn/Article/details/gt2qloyqpdm.html

[E02] 重复字符串
来源：http://dali.feifeiyinyue.top/Article/details/gt2fbpotavm.html

Py:   "ab" * 3
来源：http://dali.jiagoushi.top/Article/details/gt2lyzhiunr.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhixingplan.top/Article/details/gt2gyhvvymj.html

JS:   "ab".repeat(3)
来源：http://dali.guowangkeji.top/Article/details/gt2exfkqzji.html

TS:   "ab".repeat(3)
来源：http://dali.yj202588.top/Article/details/gt2xaularse.html

Java: "ab".repeat(3)
来源：http://dali.fzhhl.top/Article/details/gt2zbgukpga.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.snrcjt.cn/Article/details/gt2uhfxifph.html

Ruby: "ab" * 3
来源：http://dali.guannengcc.top/Article/details/gt2hgeljauq.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.xuetiantiany.cn/Article/details/gt2cmzpdmfq.html

[E03] 截取子串
来源：http://dali.wangshuangyany.cn/Article/details/gt2woqhgqqw.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.shzxlz.cn/Article/details/gt2xbjppgvp.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.snrcjt.cn/Article/details/gt2bhnlczeg.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.svipenyu.cn/Article/details/gt2zdedednv.html

TS:   s.slice(1, 4)
来源：http://dali.gaohongyu789.top/Article/details/gt2ccvqtggu.html

Java: s.substring(1, 4)
来源：http://dali.bjfxy.top/Article/details/gt2idknddyp.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.aizwys.cn/Article/details/gt2kihmbxix.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.birdmap.top/Article/details/gt2skvftlag.html

C#:   s.Substring(1, 3)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ryqlgsgs.html

[E04] 查找子串位置
来源：http://dali.jlsjyb.cn/Article/details/gt2maqgfsyt.html

Py:   s.find("x");  s.index("x")
来源：http://dali.vqdsnc.cn/Article/details/gt2unxenstm.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2cvmpkpdh.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yangfankeji.com/Article/details/gt2ehuklcne.html

TS:   s.indexOf("x")
来源：http://dali.xziqi.cn/Article/details/gt2ugmmhjyv.html

Java: s.indexOf("x")
来源：http://dali.pengpengdd.cyou/Article/details/gt2yvyvwgsr.html

Go:   strings.Index(s, "x")
来源：http://dali.zhengqikj.top/Article/details/gt2gruqztdl.html

Ruby: s.index("x")
来源：http://dali.ybcxt.top/Article/details/gt2atlhloaf.html

C#:   s.IndexOf("x")
来源：http://dali.chenzaomai.com/Article/details/gt2vzppsyup.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.redwolf501.top/Article/details/gt2pfsacwwq.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.0kj1m.cn/Article/details/gt2mcrbtrfi.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.wangshuangyany.cn/Article/details/gt2kyaeslqp.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yj20258888.top/Article/details/gt2dxnbjhef.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2ndgdsucf.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.nanxinkj.top/Article/details/gt2jwxkidro.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.chenzaomai.com/Article/details/gt2icagrcbj.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.dashuyun.cn/Article/details/gt2civmueeu.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.cashguo.top/Article/details/gt2kzshmyzc.html

[E06] 替换子串
来源：http://dali.chenjidiqi.icu/Article/details/gt2yaejzjjn.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.meibo888.top/Article/details/gt2jzamyvgo.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jyoumei.cn/Article/details/gt2kgvmsqnn.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.havefunace.top/Article/details/gt2uilqnrld.html

TS:   s.replaceAll("a", "b")
来源：http://dali.xziqi.cn/Article/details/gt2iumcysmz.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zqmljwwf.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yj20258.top/Article/details/gt2erajsgbd.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.nwbrower.top/Article/details/gt2iqlpnwoz.html

C#:   s.Replace("a", "b")
来源：http://dali.yvedp.cn/Article/details/gt2agrncowt.html

[E07] 按分隔符拆分
来源：http://dali.vqdsnc.cn/Article/details/gt2wsddokpz.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.svipenyu.cn/Article/details/gt2wsuwbxrp.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.hammf.cn/Article/details/gt2iquhyoky.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.svipenyu.cn/Article/details/gt2ksvatbce.html

TS:   s.split(",")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2idbdnjfm.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.wangdashe.top/Article/details/gt2khgcaxfr.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.cqqwz.cn/Article/details/gt2cphiqerw.html

Ruby: s.split(",");  s.split
来源：http://dali.yonumen.top/Article/details/gt2zkjxaqtq.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jyoumei.cn/Article/details/gt2klalhhyo.html

[E08] 数组按分隔符合并
来源：http://dali.cqqwz.cn/Article/details/gt2rkiezwbh.html

Py:   ",".join(items)
来源：http://dali.hnqzz.top/Article/details/gt2vwybzazb.html

PHP:  implode(",", $items);
来源：http://dali.quarkkingdee.top/Article/details/gt2nyivznal.html

JS:   items.join(",")
来源：http://dali.yj202588.top/Article/details/gt2njdaapix.html

TS:   items.join(",")
来源：http://dali.xylfe.cn/Article/details/gt2kwbtnlwn.html

Java: String.join(",", items)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lumqehii.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2zalnubay.html

Ruby: items.join(",")
来源：http://dali.bjfxy.top/Article/details/gt2rcenyjgn.html

C#:   string.Join(",", items)
来源：http://dali.nanxinkj.top/Article/details/gt2udzmfsgd.html

[E09] 去除所有空白字符
来源：http://dali.gogol.net.cn/Article/details/gt2vpsbruiu.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.sufxvd.cn/Article/details/gt2ddupgdud.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.shangyingyoupin.top/Article/details/gt2objhjfvf.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.xziqi.cn/Article/details/gt2szxfqhrw.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hnqzz.top/Article/details/gt2whdbuxaf.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.bjfxy.top/Article/details/gt2repatqid.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zycfv.cn/Article/details/gt2cpwxqktg.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.shuidangran.top/Article/details/gt2xymfkujo.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.xziqi.cn/Article/details/gt2wpsyfzdb.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yj202588.top/Article/details/gt2vxnmcftl.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hywenlv.cn/Article/details/gt2tnjwhpui.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2vpzravfp.html

JS:   "7".padStart(3, "0")
来源：http://dali.yj20258888.top/Article/details/gt2htzlrxea.html

TS:   "7".padStart(3, "0")
来源：http://dali.snrcjt.cn/Article/details/gt2iotdaqyp.html

Java: String.format("%03d", 7)
来源：http://dali.fengsongda.top/Article/details/gt2vdblqdti.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.cdnleiting.top/Article/details/gt2ipdrxvjd.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.daria6918.cn/Article/details/gt2zoolfgid.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yanxiufei.cn/Article/details/gt2gdttoogj.html

[E11] 反转字符串
来源：http://dali.ivvv.top/Article/details/gt2nzebfmih.html

Py:   s[::-1]
来源：http://dali.cashguo.top/Article/details/gt2fvcdgmri.html

PHP:  strrev($s);
来源：http://dali.zhongyouzk.top/Article/details/gt2nqnjhnol.html

JS:   [...s].reverse().join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xqtgrzcd.html

TS:   [...s].reverse().join("")
来源：http://dali.hysaishi.cn/Article/details/gt2reevmxkb.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.chenjidiqi.icu/Article/details/gt2aixmjrak.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.iojbl.cn/Article/details/gt2iyoayxwk.html

Ruby: s.reverse
来源：http://dali.pycfn.com/Article/details/gt2goqayzuu.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uiexwaxm.html

[E12] 统计某字符出现次数
来源：http://dali.tanke756.top/Article/details/gt2hsrzmmor.html

Py:   s.count("a")
来源：http://dali.xylfe.cn/Article/details/gt2qafxldev.html

PHP:  substr_count($s, "a");
来源：http://dali.wangdashe.top/Article/details/gt2nirimwyy.html

JS:   s.split("a").length - 1
来源：http://dali.ydzc1.top/Article/details/gt2jjnacegt.html

TS:   s.split("a").length - 1
来源：http://dali.zycfv.cn/Article/details/gt2tyukwxhq.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.hongshengwenyu.top/Article/details/gt2scntwcxk.html

Go:   strings.Count(s, "a")
来源：http://dali.nwbrower.top/Article/details/gt2zbwamlhb.html

Ruby: s.count("a")
来源：http://dali.jiagoushi.top/Article/details/gt2hicukuzw.html

C#:   s.Count(c => c == 'a')
来源：http://dali.aibaodan.cn/Article/details/gt2zwxgzbjy.html

[E13] 逐字符遍历
来源：http://dali.cqqwz.cn/Article/details/gt2gfeexbiz.html

Py:   for ch in s: print(ch)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfgtnflq.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.guowangkeji.top/Article/details/gt2iqnjgbtt.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xvygcdel.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xziqi.cn/Article/details/gt2skosmewl.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zycfv.cn/Article/details/gt2lgvknsws.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jlsjyb.cn/Article/details/gt2inwddzdw.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hfpthk.cn/Article/details/gt2ceoaqvzy.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.xylfe.cn/Article/details/gt2ethksvfd.html

[E14] URL 编码与 Base64
来源：http://dali.hammf.cn/Article/details/gt2kmntizsv.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jqgfzy.top/Article/details/gt2orzoasnv.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jqgufenzy.top/Article/details/gt2zskxhkog.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hnxiangtu.top/Article/details/gt2smcriyzz.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2jniumapa.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.iojbl.cn/Article/details/gt2sefsykrz.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.tianlin.xyz/Article/details/gt2smswqcvg.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.ehwqpu.com/Article/details/gt2ubavnnmk.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.tanke756.top/Article/details/gt2zsloggpx.html

[E15] HTML 转义 / 反转义
来源：http://dali.xylfe.cn/Article/details/gt2zzmefbse.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.guannengcc.top/Article/details/gt2ymvegnjs.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hywenlv.cn/Article/details/gt2dessxxbi.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nsecswcy.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.xziqi.cn/Article/details/gt2azdcgdju.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.cucudq.cn/Article/details/gt2gmqeexnp.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.daxiang520.top/Article/details/gt2flzjhgwu.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.aizwys.cn/Article/details/gt2pkbmiyuh.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yuxming.cn/Article/details/gt2czdhupia.html

[E16] 数字千分位
来源：http://dali.cdnleiting.top/Article/details/gt2vvgyckzj.html

Py:   f"{1234567:,}"
来源：http://dali.nwbrower.top/Article/details/gt2wmskfiof.html

PHP:  number_format(1234567);
来源：http://dali.jiagoushi.top/Article/details/gt2humycuaa.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.tian-w.cn/Article/details/gt2nuawifvs.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hkdxnxim.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jyoumei.cn/Article/details/gt2xjbzeeds.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.mhx1999.top/Article/details/gt2mnerdupl.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hnqzz.top/Article/details/gt2nbvcoiyp.html

C#:   1234567.ToString("N0")
来源：http://dali.daria6918.cn/Article/details/gt2mjrkkitq.html

[E17] 首字母大写
来源：http://dali.kuanghao11.cn/Article/details/gt2kchgyuix.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.meibo888.top/Article/details/gt2lplitwqe.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.ivvv.top/Article/details/gt2vjxyyoyv.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.andypj.xyz/Article/details/gt2zvmmpcei.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cashguo.top/Article/details/gt2fqikdtii.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.cucudq.cn/Article/details/gt2vlrddvuc.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jiagoushi.top/Article/details/gt2qfbssqhh.html

Ruby: s.capitalize
来源：http://dali.feifeiyinyue.top/Article/details/gt2mpajcuja.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ppjwa.cn/Article/details/gt2jbuwsovt.html

[E18] 模板占位符替换
来源：http://dali.zycfv.cn/Article/details/gt2bctzhpwa.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yanxiufei.cn/Article/details/gt2gbeqeodf.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.guannengcc.top/Article/details/gt2fgybuxvl.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.haohaochexian.top/Article/details/gt2jfinuzme.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.xinyue.icu/Article/details/gt2jjhrveyp.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.ydzc1.top/Article/details/gt2vytpmhze.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.wangshuangyany.cn/Article/details/gt2yxlyewff.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.hysaishi.cn/Article/details/gt2ubowneje.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.0kj1m.cn/Article/details/gt2elfrzxrh.html

[E19] 多行文本按行拆分
来源：http://dali.iojbl.cn/Article/details/gt2hmuezhpc.html

Py:   s.splitlines()
来源：http://dali.hfpthk.cn/Article/details/gt2mnjvpesk.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.ybcxt.top/Article/details/gt2ipjvoplw.html

JS:   s.split(/\r?\n/)
来源：http://dali.xuetiantiany.cn/Article/details/gt2chaoekcc.html

TS:   s.split(/\r?\n/)
来源：http://dali.yj20258888.top/Article/details/gt2rnzsfjgq.html

Java: s.lines().toList()
来源：http://dali.yj20258888.top/Article/details/gt2jhdamosc.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ocynvtft.html

Ruby: s.lines
来源：http://dali.cqqwz.cn/Article/details/gt2sdkzluip.html

C#:   s.Split('\n')
来源：http://dali.gogol.net.cn/Article/details/gt2qhjgsqdz.html

[E20] 判断字符串是否为空
来源：http://dali.chenjidiqi.icu/Article/details/gt2fbczeujg.html

Py:   if not s:
来源：http://dali.tanke756.top/Article/details/gt2bvwasnle.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yuanzhike.top/Article/details/gt2ugmyoxtq.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.andypj.xyz/Article/details/gt2dhplbawy.html

TS:   if (s === "") {}
来源：http://dali.hfpthk.cn/Article/details/gt2zydravfy.html

Java: if (s.isEmpty()) {}
来源：http://dali.jianghu66.top/Article/details/gt2pjmnsckm.html

Go:   if s == "" {}
来源：http://dali.316326.xyz/Article/details/gt2bmxpeogy.html

Ruby: if s.empty?
来源：http://dali.hysaishi.cn/Article/details/gt2svwbsxui.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2npelwjsf.html

[E21] 超长截断加省略号
来源：http://dali.shzxlz.cn/Article/details/gt2vrecenye.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.shzxlz.cn/Article/details/gt2ivgjftrx.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.cashguo.top/Article/details/gt2nviauqxw.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.vqdsnc.cn/Article/details/gt2pnomyjsw.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zycfv.cn/Article/details/gt2uyyjlcle.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ydscyzao.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.chenlongwang.top/Article/details/gt2gebvicvv.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhiwuduotai.top/Article/details/gt2jwkyavzk.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.gotoacloud.top/Article/details/gt2wuawcybk.html

[E22] 字节长度与字符长度
来源：http://dali.0kj1m.cn/Article/details/gt2sdvgbhky.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.meibo888.top/Article/details/gt2kmusrnep.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.316326.xyz/Article/details/gt2fbjkpayu.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uzzymmgc.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhengqikj.top/Article/details/gt2mekrudoa.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hnqzz.top/Article/details/gt2jpjcceqz.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.ivvv.top/Article/details/gt2ikojsdsd.html

Ruby: s.bytesize;  s.length
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2luzmtonq.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.pycfn.com/Article/details/gt2wkzzcrqv.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2asfmcdwp.html

F. 文件与目录
来源：http://dali.chenzaomai.com/Article/details/gt2muovxkko.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yksneuyb.html


<!-- 参考信息 -->