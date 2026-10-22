代发 wailian999

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.snrcjt.cn/Article/details/gt2eojbiyov.html

C#:   list.Sum();  list.Average()
来源：http://dali.guannengcc.top/Article/details/gt2xpsrewdt.html

[D17] 最大值与最小值
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2osgraecq.html

Py:   max(arr);  min(arr)
来源：http://dali.hfpthk.cn/Article/details/gt2xivyqpfb.html

PHP:  max($arr);  min($arr);
来源：http://dali.daria6918.cn/Article/details/gt2vwahzizh.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.chenlongwang.top/Article/details/gt2ggwrlpld.html

TS:   Math.max(...arr);
来源：http://dali.redwolf501.top/Article/details/gt2pgodazju.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhoulong.xyz/Article/details/gt2wokxdrdq.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.havefunace.top/Article/details/gt2lqanqepx.html

Ruby: arr.max;  arr.min
来源：http://dali.ydzc1.top/Article/details/gt2mmcausvb.html

C#:   list.Max();  list.Min()
来源：http://dali.c1oappe.top/Article/details/gt2qftfunoj.html

[D18] 扁平化嵌套数组
来源：http://dali.sweek.top/Article/details/gt2ewdnrhry.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jianghu66.top/Article/details/gt2asjfskif.html

PHP:  array_merge(...$nested);
来源：http://dali.tanke756.top/Article/details/gt2twldvotq.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.hysaishi.cn/Article/details/gt2wtbwtcda.html

TS:   nested.flat();
来源：http://dali.zhoulong.xyz/Article/details/gt2veftvzpr.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhoulong.xyz/Article/details/gt2lgfqxdmi.html

Go:   // 手写双层循环
来源：http://dali.xziqi.cn/Article/details/gt2fmwxfdin.html

Ruby: nested.flatten
来源：http://dali.chenzaomai.com/Article/details/gt2mkyyzagw.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hywenlv.cn/Article/details/gt2lggeqsnt.html

[D19] 按字段分组
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2njgtostb.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.dashuyun.cn/Article/details/gt2kosnpnya.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yongpay.top/Article/details/gt2jnnjmvgp.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.shzxlz.cn/Article/details/gt2plhxflop.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.ydzc1.top/Article/details/gt2ziohwtpe.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zcadhmig.html

Go:   // 手写 map[string][]T
来源：http://dali.hongshengwenyu.top/Article/details/gt2goybxlfn.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.guowangkeji.top/Article/details/gt2qgprfael.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yanxiufei.cn/Article/details/gt2yzttpiif.html

[D20] 统计每个元素出现次数
来源：http://dali.bjfxy.top/Article/details/gt2ksxmitvo.html

Py:   Counter(arr)
来源：http://dali.havefunace.top/Article/details/gt2gsaujzue.html

PHP:  array_count_values($arr);
来源：http://dali.ydzc1.top/Article/details/gt2nparvwla.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shangyingyoupin.top/Article/details/gt2zihgnudy.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cdnleiting.top/Article/details/gt2fnbuehdu.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.ybcxt.top/Article/details/gt2cazqsusb.html

Go:   // 手写 map[T]int
来源：http://dali.sweek.top/Article/details/gt2hajadcyt.html

Ruby: arr.tally
来源：http://dali.jiagoushi.top/Article/details/gt2bhpfwrgt.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.gzhubu.top/Article/details/gt2hskilyoh.html

[D21] 判断是否包含某元素
来源：http://dali.redwolf501.top/Article/details/gt2vqalsiqz.html

Py:   x in arr
来源：http://dali.0kj1m.cn/Article/details/gt2lnnkwtgd.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ikandrhh.html

JS:   arr.includes(x)
来源：http://dali.chenlongwang.top/Article/details/gt2ivhgpnxh.html

TS:   arr.includes(x)
来源：http://dali.yj20258888.top/Article/details/gt2udxhsmwt.html

Java: list.contains(x)
来源：http://dali.jqgufenzy.top/Article/details/gt2rpalrzrr.html

Go:   slices.Contains(arr, x)
来源：http://dali.yj202588.top/Article/details/gt2rwvrfovo.html

Ruby: arr.include?(x)
来源：http://dali.snrcjt.cn/Article/details/gt2wsqxlres.html

C#:   list.Contains(x)
来源：http://dali.ydzc1.top/Article/details/gt2kuoyvayr.html

[D22] 复制数组（避免共享引用）
来源：http://dali.shuidangran.top/Article/details/gt2zrykzxzg.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.svipenyu.cn/Article/details/gt2avucvbsm.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.smart0.xyz/Article/details/gt2syskbbqn.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.aibaodan.cn/Article/details/gt2qckpombh.html

TS:   [...arr];
来源：http://dali.ivvv.top/Article/details/gt2dzmijcta.html

Java: new ArrayList<>(list);
来源：http://dali.pengpengdd.cyou/Article/details/gt2tnmqcmbm.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.hammf.cn/Article/details/gt2zhrnyvln.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhiwuduotai.top/Article/details/gt2rtbaeshz.html

C#:   new List<int>(list);
来源：http://dali.meibo888.top/Article/details/gt2yaeevwzl.html

[D23] reduce 累积计算
来源：http://dali.hongshengwenyu.top/Article/details/gt2lukhqgwh.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.sufxvd.cn/Article/details/gt2hrtlypep.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2werflwba.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shuidangran.top/Article/details/gt2gozsouel.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jyoumei.cn/Article/details/gt2gpjjyqzh.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.daxiang520.top/Article/details/gt2gtcpyhla.html

Go:   // 手写循环
来源：http://dali.guowangkeji.top/Article/details/gt2ihmynlnv.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.xinyue.icu/Article/details/gt2mqziyben.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.tianlin.xyz/Article/details/gt2hurcoiqd.html

[D24] 字典 / Map 基本操作
来源：http://dali.tianlin.xyz/Article/details/gt2mlaopbnx.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.ivvv.top/Article/details/gt2ivkiyati.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.wangdashe.top/Article/details/gt2xsxgucgi.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhongyouzk.top/Article/details/gt2zfkrvjbd.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jjwjtmti.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.hnxiangtu.top/Article/details/gt2mmasffgw.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yuanzhike.top/Article/details/gt2iijlezul.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jianghu66.top/Article/details/gt2jucryqhd.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.andypj.xyz/Article/details/gt2sxjyncxu.html

[D25] Set 集合去重与交并差
来源：http://dali.jlsjyb.cn/Article/details/gt2jlanrool.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.fzhhl.top/Article/details/gt2vwxkfgjy.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.smart0.xyz/Article/details/gt2vudvicot.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yj202588.top/Article/details/gt2tztxtyeg.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zycfv.cn/Article/details/gt2cnrbcviy.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.cdnleiting.top/Article/details/gt2ixpukawb.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.tianlin.xyz/Article/details/gt2knsqjmcq.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.daria6918.cn/Article/details/gt2aimkikko.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.gaohongyu789.top/Article/details/gt2kgscyffs.html

[D26] 数组转字符串
来源：http://dali.tianlin.xyz/Article/details/gt2kixzpvse.html

Py:   ", ".join(map(str, arr))
来源：http://dali.cdnleiting.top/Article/details/gt2lrpfyouc.html

PHP:  implode(", ", $arr);
来源：http://dali.andypj.xyz/Article/details/gt2awqnsvrh.html

JS:   arr.join(", ")
来源：http://dali.fzhhl.top/Article/details/gt2bipdeprv.html

TS:   arr.join(", ")
来源：http://dali.iojbl.cn/Article/details/gt2agftyjtd.html

Java: String.join(", ", list)
来源：http://dali.fengsongda.top/Article/details/gt2srfgewty.html

Go:   strings.Join(strs, ", ")
来源：http://dali.mhx1999.top/Article/details/gt2swhmxgjn.html

Ruby: arr.join(", ")
来源：http://dali.wangdashe.top/Article/details/gt2uynahgff.html

C#:   string.Join(", ", list)
来源：http://dali.9152youxi.cn/Article/details/gt2jqheozhh.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2dubehktg.html

E. 字符串处理
来源：http://dali.pycfn.com/Article/details/gt2ilklmgvz.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2bdhunvqp.html

[E01] 拼接字符串
来源：http://dali.yuanzhike.top/Article/details/gt2neoityvt.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.chenzaomai.com/Article/details/gt2uvqftuxe.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yuanzhike.top/Article/details/gt2zvnomage.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ojchtart.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yonumen.top/Article/details/gt2ncoiyxwr.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yvedp.cn/Article/details/gt2fqfluovs.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jinqigfzy.top/Article/details/gt2tzavnyqn.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.cqqwz.cn/Article/details/gt2qtawyexe.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhixingplan.top/Article/details/gt2xuctvbwe.html

[E02] 重复字符串
来源：http://dali.chenlongwang.top/Article/details/gt2iznuhqkg.html

Py:   "ab" * 3
来源：http://dali.nwbrower.top/Article/details/gt2bvhaqmzi.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yueranfly.top/Article/details/gt2zrornrpx.html

JS:   "ab".repeat(3)
来源：http://dali.guowangkeji.top/Article/details/gt2xpkqrihy.html

TS:   "ab".repeat(3)
来源：http://dali.xuanzx.com/Article/details/gt2aqrfxhck.html

Java: "ab".repeat(3)
来源：http://dali.zhixingplan.top/Article/details/gt2ucokesda.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2grrputuj.html

Ruby: "ab" * 3
来源：http://dali.sweek.top/Article/details/gt2nzhlvukr.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.shangyingyoupin.top/Article/details/gt2xngksxrw.html

[E03] 截取子串
来源：http://dali.cheryme.top/Article/details/gt2xcleidux.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.meibo888.top/Article/details/gt2imuxtgoj.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.andypj.xyz/Article/details/gt2ywtikohb.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jyoumei.cn/Article/details/gt2nagucrkk.html

TS:   s.slice(1, 4)
来源：http://dali.kuanghao11.cn/Article/details/gt2ctgeaiul.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2znrdnoum.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.9152youxi.cn/Article/details/gt2jsodctqc.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhongyouzk.top/Article/details/gt2khwbpzrg.html

C#:   s.Substring(1, 3)
来源：http://dali.shuidangran.top/Article/details/gt2bdhaanwn.html

[E04] 查找子串位置
来源：http://dali.c1oappe.top/Article/details/gt2gzlwzdam.html

Py:   s.find("x");  s.index("x")
来源：http://dali.shangyingyoupin.top/Article/details/gt2npoccjch.html

PHP:  strpos($s, "x");
来源：http://dali.guowangkeji.top/Article/details/gt2lersyggc.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.cdnleiting.top/Article/details/gt2pribqsdy.html

TS:   s.indexOf("x")
来源：http://dali.pycfn.com/Article/details/gt2sivzznuc.html

Java: s.indexOf("x")
来源：http://dali.zhengqikj.top/Article/details/gt2atjgnnbh.html

Go:   strings.Index(s, "x")
来源：http://dali.quarkkingdee.top/Article/details/gt2enmwtrap.html

Ruby: s.index("x")
来源：http://dali.yueranfly.top/Article/details/gt2vjvvqlga.html

C#:   s.IndexOf("x")
来源：http://dali.yj20258.top/Article/details/gt2tjujrukb.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.vqdsnc.cn/Article/details/gt2nxqlcnzw.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.haohaochexian.top/Article/details/gt2dmdycrlr.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hhcvyoao.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.mhx1999.top/Article/details/gt2kzpahgcd.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.wangshuangyany.cn/Article/details/gt2mhqtxyti.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhongyouzk.top/Article/details/gt2nmahguli.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.ivvv.top/Article/details/gt2cgnritbk.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.nanxuanxn.top/Article/details/gt2gvvequbh.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rrjhwmse.html

[E06] 替换子串
来源：http://dali.yanxiufei.cn/Article/details/gt2lpctxnwf.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.iojbl.cn/Article/details/gt2rbzhangj.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.ybcxt.top/Article/details/gt2qnfbltpm.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shangyingyoupin.top/Article/details/gt2lsjvhmnh.html

TS:   s.replaceAll("a", "b")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ompxnoac.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xziqi.cn/Article/details/gt2knqqoxek.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhixingplan.top/Article/details/gt2atnhhikj.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.dianchejie.cn/Article/details/gt2ppuwmxeo.html

C#:   s.Replace("a", "b")
来源：http://dali.meibo888.top/Article/details/gt2qrswzgea.html

[E07] 按分隔符拆分
来源：http://dali.316326.xyz/Article/details/gt2wijkclot.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.316326.xyz/Article/details/gt2hsqfmjzu.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jianghu66.top/Article/details/gt2erewvupp.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xpkkbdhb.html

TS:   s.split(",")
来源：http://dali.pycfn.com/Article/details/gt2ezufvlsd.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.pycfn.com/Article/details/gt2ydqmherf.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2cmskrcyu.html

Ruby: s.split(",");  s.split
来源：http://dali.dianchejie.cn/Article/details/gt2yxtwgzly.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hfpthk.cn/Article/details/gt2fmhsjgsd.html

[E08] 数组按分隔符合并
来源：http://dali.dianchejie.cn/Article/details/gt2gnoanzjy.html

Py:   ",".join(items)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2skonleme.html

PHP:  implode(",", $items);
来源：http://dali.gotoacloud.top/Article/details/gt2opnmrgog.html

JS:   items.join(",")
来源：http://dali.svipenyu.cn/Article/details/gt2uvgmnpmh.html

TS:   items.join(",")
来源：http://dali.chenlongwang.top/Article/details/gt2xoogajpk.html

Java: String.join(",", items)
来源：http://dali.jinqigufen.top/Article/details/gt2jtybphyc.html

Go:   strings.Join(items, ",")
来源：http://dali.yueranfly.top/Article/details/gt2vlbghvmp.html

Ruby: items.join(",")
来源：http://dali.aibaodan.cn/Article/details/gt2mtybetmy.html

C#:   string.Join(",", items)
来源：http://dali.aibaodan.cn/Article/details/gt2aiihreuw.html

[E09] 去除所有空白字符
来源：http://dali.wangdashe.top/Article/details/gt2kjszdxbq.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.xziqi.cn/Article/details/gt2iomjlikq.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.shzxlz.cn/Article/details/gt2lretcvhz.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jinqigfzy.top/Article/details/gt2tqptzyaq.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.nanxinkj.top/Article/details/gt2jmgwpluz.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yj20258888.top/Article/details/gt2wcthoqjk.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.sweek.top/Article/details/gt2lunpigcl.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.chenzaomai.com/Article/details/gt2whayamcr.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.xylfe.cn/Article/details/gt2xjagdybe.html

[E10] 左侧补零 / 定长填充
来源：http://dali.redwolf501.top/Article/details/gt2stcfvdgj.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.kuanghao11.cn/Article/details/gt2hznvsbka.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.xylfe.cn/Article/details/gt2huvzccab.html

JS:   "7".padStart(3, "0")
来源：http://dali.jqgufenzy.top/Article/details/gt2tomimwdk.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2abfmnlhi.html

Java: String.format("%03d", 7)
来源：http://dali.xuetiantiany.cn/Article/details/gt2zacnoexp.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vbphhhuw.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yvedp.cn/Article/details/gt2irigudya.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fwohmlbm.html

[E11] 反转字符串
来源：http://dali.tanke756.top/Article/details/gt2aqybwegf.html

Py:   s[::-1]
来源：http://dali.gogol.net.cn/Article/details/gt2tsbeycsa.html

PHP:  strrev($s);
来源：http://dali.yvedp.cn/Article/details/gt2ofsfvvpt.html

JS:   [...s].reverse().join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bxztnlle.html

TS:   [...s].reverse().join("")
来源：http://dali.dianchejie.cn/Article/details/gt2hlfxjxys.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.dianchejie.cn/Article/details/gt2rpxyruth.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.bjfxy.top/Article/details/gt2icsvgndx.html

Ruby: s.reverse
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2neocggrp.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.guowangkeji.top/Article/details/gt2vxssxaqs.html

[E12] 统计某字符出现次数
来源：http://dali.daria6918.cn/Article/details/gt2htyjfeyo.html

Py:   s.count("a")
来源：http://dali.shuidangran.top/Article/details/gt2hkbxyato.html

PHP:  substr_count($s, "a");
来源：http://dali.316326.xyz/Article/details/gt2xzkgnilt.html

JS:   s.split("a").length - 1
来源：http://dali.jyoumei.cn/Article/details/gt2pqvbfixl.html

TS:   s.split("a").length - 1
来源：http://dali.shangyingyoupin.top/Article/details/gt2ryommhav.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.c1oappe.top/Article/details/gt2kfbnchwv.html

Go:   strings.Count(s, "a")
来源：http://dali.daria6918.cn/Article/details/gt2vracvceg.html

Ruby: s.count("a")
来源：http://dali.gzhubu.top/Article/details/gt2wbykoewe.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xylfe.cn/Article/details/gt2mzarylzp.html

[E13] 逐字符遍历
来源：http://dali.yanxiufei.cn/Article/details/gt2fdbldbtw.html

Py:   for ch in s: print(ch)
来源：http://dali.xinyue.icu/Article/details/gt2cqnpajkv.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ukawsdne.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.fengsongda.top/Article/details/gt2vbmlaurl.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.havefunace.top/Article/details/gt2rnwljvkd.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.cheryme.top/Article/details/gt2ijotrtzv.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.haohaochexian.top/Article/details/gt2autlgfzz.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nkgmsgzl.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.ivvv.top/Article/details/gt2kqerxncj.html

[E14] URL 编码与 Base64
来源：http://dali.0kj1m.cn/Article/details/gt2lvlsnyqi.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.pengpengdd.cyou/Article/details/gt2iokagllq.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jlsjyb.cn/Article/details/gt2udijlfmg.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.dianchejie.cn/Article/details/gt2gugxavhf.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yuanzhike.top/Article/details/gt2jrscwdgf.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhengqikj.top/Article/details/gt2mfmsuhcj.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.0kj1m.cn/Article/details/gt2xiybxwwn.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2omhpnxgk.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jinqigufen.top/Article/details/gt2aapxihma.html

[E15] HTML 转义 / 反转义
来源：http://dali.snrcjt.cn/Article/details/gt2rwvlwgol.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.iojbl.cn/Article/details/gt2ibvkwwwk.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.sufxvd.cn/Article/details/gt2rzbmobnx.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yj202588.top/Article/details/gt2ttpovbjd.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.xylfe.cn/Article/details/gt2wipygefa.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.chenzaomai.com/Article/details/gt2eclczeht.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.gogol.net.cn/Article/details/gt2rhlcxgbt.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hysaishi.cn/Article/details/gt2dqeiecnf.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.vqdsnc.cn/Article/details/gt2oudiduln.html

[E16] 数字千分位
来源：http://dali.cashguo.top/Article/details/gt2rwbqfmga.html

Py:   f"{1234567:,}"
来源：http://dali.havefunace.top/Article/details/gt2qvuqlogx.html

PHP:  number_format(1234567);
来源：http://dali.xuetiantiany.cn/Article/details/gt2pvsumpcg.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yj20258.top/Article/details/gt2hcmurxfx.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yongpay.top/Article/details/gt2qhfuxviu.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.cdnleiting.top/Article/details/gt2jwjqjxvp.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2murryotb.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hnqzz.top/Article/details/gt2ahbpqery.html

C#:   1234567.ToString("N0")
来源：http://dali.yuanzhike.top/Article/details/gt2pnqjkict.html

[E17] 首字母大写
来源：http://dali.pycfn.com/Article/details/gt2ikyznjrk.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.mhx1999.top/Article/details/gt2iplwuyvg.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.meibo888.top/Article/details/gt2icgayosp.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenzaomai.com/Article/details/gt2vcwcbgfa.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cucudq.cn/Article/details/gt2fhivdlsw.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.cdnleiting.top/Article/details/gt2jcsfolzh.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.shuidangran.top/Article/details/gt2xqpbsrdf.html

Ruby: s.capitalize
来源：http://dali.dianchejie.cn/Article/details/gt2pklxonyu.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.gzhubu.top/Article/details/gt2myulvtfj.html

[E18] 模板占位符替换
来源：http://dali.gotoacloud.top/Article/details/gt2exyahpqe.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hywenlv.cn/Article/details/gt2jeolrdky.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.havefunace.top/Article/details/gt2lwfrrpmp.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.cucudq.cn/Article/details/gt2pmtwxevm.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.ydzc1.top/Article/details/gt2ppuqzbcn.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.wangdashe.top/Article/details/gt2gvlbtpyq.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.ivvv.top/Article/details/gt2xxoraasp.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.meibo888.top/Article/details/gt2xqdpsdhl.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.shuidangran.top/Article/details/gt2uyjhdgqr.html

[E19] 多行文本按行拆分
来源：http://dali.hongshengwenyu.top/Article/details/gt2fjtqktzn.html

Py:   s.splitlines()
来源：http://dali.guannengcc.top/Article/details/gt2wqzdkzti.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.mhx1999.top/Article/details/gt2nqmilsny.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhixingplan.top/Article/details/gt2avxuhqmh.html

TS:   s.split(/\r?\n/)
来源：http://dali.9152youxi.cn/Article/details/gt2lukkhumg.html

Java: s.lines().toList()
来源：http://dali.iojbl.cn/Article/details/gt2ieyugzcq.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhoulong.xyz/Article/details/gt2wfqmjqfe.html

Ruby: s.lines
来源：http://dali.zhoulong.xyz/Article/details/gt2pbfozfai.html

C#:   s.Split('\n')
来源：http://dali.jinqigufen.top/Article/details/gt2wlvmmkpz.html

[E20] 判断字符串是否为空
来源：http://dali.pengpengdd.cyou/Article/details/gt2niyfbvls.html

Py:   if not s:
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mwbbltop.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.gogol.net.cn/Article/details/gt2kwoslgiq.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.havefunace.top/Article/details/gt2ktwvjkmb.html

TS:   if (s === "") {}
来源：http://dali.fengsongda.top/Article/details/gt2vsnoedvt.html

Java: if (s.isEmpty()) {}
来源：http://dali.mhx1999.top/Article/details/gt2gvcahbkd.html

Go:   if s == "" {}
来源：http://dali.dianchejie.cn/Article/details/gt2ukpjdgzi.html

Ruby: if s.empty?
来源：http://dali.cdnleiting.top/Article/details/gt2uxwlcbfg.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.svipenyu.cn/Article/details/gt2wzxdlmtb.html

[E21] 超长截断加省略号
来源：http://dali.yongpay.top/Article/details/gt2bohigcey.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.cheryme.top/Article/details/gt2wlqzlgut.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.nanxuanxn.top/Article/details/gt2hkmhhalq.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sysykeji.top/Article/details/gt2bihemayc.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.daxiang520.top/Article/details/gt2dtnsrcjn.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.tianlin.xyz/Article/details/gt2sihmjwve.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.wangdashe.top/Article/details/gt2bgpwptvc.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.c1oappe.top/Article/details/gt2fniftvgm.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.smart0.xyz/Article/details/gt2uudklyht.html

[E22] 字节长度与字符长度
来源：http://dali.jyoumei.cn/Article/details/gt2ljnsnjfw.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.hnqzz.top/Article/details/gt2hjplxubr.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sxryk.cn/Article/details/gt2jeptzmdx.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shzxlz.cn/Article/details/gt2calwffwf.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ybcxt.top/Article/details/gt2cydrdzuu.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hywenlv.cn/Article/details/gt2ifqfvxju.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hnqzz.top/Article/details/gt2bzahqnle.html

Ruby: s.bytesize;  s.length
来源：http://dali.c1oappe.top/Article/details/gt2fnedfnpo.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.pengpengdd.cyou/Article/details/gt2qlczcgos.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2wrlpwsxe.html

F. 文件与目录
来源：http://dali.yvedp.cn/Article/details/gt2bjjwjnlh.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2nsrlzgup.html

[F01] 读取整个文件
来源：http://dali.yvedp.cn/Article/details/gt2iupmuzvx.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.aibaodan.cn/Article/details/gt2uqxjymrq.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xziqi.cn/Article/details/gt2yyjgikti.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.daxiang520.top/Article/details/gt2dsaxnwal.html


<!-- 参考信息 -->