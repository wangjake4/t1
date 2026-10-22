代发 wailian999

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yj20258888.top/Article/details/gt2mfmoujfz.html

C#:   list.Sum();  list.Average()
来源：http://dali.hfpthk.cn/Article/details/gt2wfforzuo.html

[D17] 最大值与最小值
来源：http://dali.xylfe.cn/Article/details/gt2wrhyoiqn.html

Py:   max(arr);  min(arr)
来源：http://dali.nanxuanxn.top/Article/details/gt2lnuwhgye.html

PHP:  max($arr);  min($arr);
来源：http://dali.sysykeji.top/Article/details/gt2eivptvdx.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.haohaochexian.top/Article/details/gt2oarzhkkt.html

TS:   Math.max(...arr);
来源：http://dali.ydzc1.top/Article/details/gt2dxkfpcms.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jpxapgsz.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.cqqwz.cn/Article/details/gt2hlgcbiom.html

Ruby: arr.max;  arr.min
来源：http://dali.svipenyu.cn/Article/details/gt2jxtbstkl.html

C#:   list.Max();  list.Min()
来源：http://dali.svipenyu.cn/Article/details/gt2qgrulufc.html

[D18] 扁平化嵌套数组
来源：http://dali.zdqjudy.top/Article/details/gt2xyavkxqr.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hfpthk.cn/Article/details/gt2jeibmtbe.html

PHP:  array_merge(...$nested);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bzxzgpux.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ppjwa.cn/Article/details/gt2opxnkcmk.html

TS:   nested.flat();
来源：http://dali.chenzaomai.com/Article/details/gt2wjnojslq.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.gzhubu.top/Article/details/gt2tiltjqjz.html

Go:   // 手写双层循环
来源：http://dali.hysaishi.cn/Article/details/gt2vbgzfrva.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2xxspqnyz.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.bjfxy.top/Article/details/gt2kvanzder.html

[D19] 按字段分组
来源：http://dali.gotoacloud.top/Article/details/gt2coqtzhii.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yj202588.top/Article/details/gt2yjsvnrcg.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.snrcjt.cn/Article/details/gt2yjimxhxf.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.nanxuanxn.top/Article/details/gt2bxessbin.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.hnqzz.top/Article/details/gt2qcpeddst.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.shuidangran.top/Article/details/gt2mdvwmhts.html

Go:   // 手写 map[string][]T
来源：http://dali.snrcjt.cn/Article/details/gt2bbgnfodm.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.fzhhl.top/Article/details/gt2nmbrjrtq.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xykxabml.html

[D20] 统计每个元素出现次数
来源：http://dali.birdmap.top/Article/details/gt2wwkcjycz.html

Py:   Counter(arr)
来源：http://dali.pycfn.com/Article/details/gt2zlchcgbo.html

PHP:  array_count_values($arr);
来源：http://dali.yangfankeji.com/Article/details/gt2rhfhffvm.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.nanxinkj.top/Article/details/gt2gzwfannb.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.chenzaomai.com/Article/details/gt2wpbpooip.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.nanxuanxn.top/Article/details/gt2mkrgxyvh.html

Go:   // 手写 map[T]int
来源：http://dali.gaohongyu789.top/Article/details/gt2agfbloxw.html

Ruby: arr.tally
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ujpgbzwd.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yuanzhike.top/Article/details/gt2tbucgoip.html

[D21] 判断是否包含某元素
来源：http://dali.havefunace.top/Article/details/gt2nuzfikhd.html

Py:   x in arr
来源：http://dali.c1oappe.top/Article/details/gt2vosvdfvg.html

PHP:  in_array($x, $arr, true);
来源：http://dali.sxryk.cn/Article/details/gt2xkzfhwba.html

JS:   arr.includes(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ryyhbrxh.html

TS:   arr.includes(x)
来源：http://dali.jqgfzy.top/Article/details/gt2ipxjgtui.html

Java: list.contains(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hqcjzefu.html

Go:   slices.Contains(arr, x)
来源：http://dali.mhx1999.top/Article/details/gt2golmassd.html

Ruby: arr.include?(x)
来源：http://dali.jinqigufen.top/Article/details/gt2lhowzjxz.html

C#:   list.Contains(x)
来源：http://dali.hnqzz.top/Article/details/gt2tgxvysez.html

[D22] 复制数组（避免共享引用）
来源：http://dali.guowangkeji.top/Article/details/gt2niraveje.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.gotoacloud.top/Article/details/gt2qmqgndlh.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yuanzhike.top/Article/details/gt2uojppzff.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hywenlv.cn/Article/details/gt2smabygcn.html

TS:   [...arr];
来源：http://dali.hysaishi.cn/Article/details/gt2htthxjhl.html

Java: new ArrayList<>(list);
来源：http://dali.ehwqpu.com/Article/details/gt2bzdhmsok.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.aibaodan.cn/Article/details/gt2qoeoksxi.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yj20258.top/Article/details/gt2ambwpyiq.html

C#:   new List<int>(list);
来源：http://dali.sufxvd.cn/Article/details/gt2tmzgxmkd.html

[D23] reduce 累积计算
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xlekuilm.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.xuanzx.com/Article/details/gt2ogikanfd.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yonumen.top/Article/details/gt2ywmkbsft.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hywenlv.cn/Article/details/gt2eybwuzku.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yj20258.top/Article/details/gt2xwaxftoz.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.daria6918.cn/Article/details/gt2evtukpzj.html

Go:   // 手写循环
来源：http://dali.nanxinkj.top/Article/details/gt2kpzpklnv.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.hywenlv.cn/Article/details/gt2kkccxynh.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yuxming.cn/Article/details/gt2fdilryqt.html

[D24] 字典 / Map 基本操作
来源：http://dali.ydzc1.top/Article/details/gt2hyztkqzn.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.tian-w.cn/Article/details/gt2emwemdcp.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yj20258888.top/Article/details/gt2ktqbjrzk.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yongpay.top/Article/details/gt2qxpjxvpd.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhixingplan.top/Article/details/gt2nkbjevhp.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.shzxlz.cn/Article/details/gt2yofjbogd.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhiwuduotai.top/Article/details/gt2sblomgia.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.andypj.xyz/Article/details/gt2rpavovns.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.gogol.net.cn/Article/details/gt2rpdqndyn.html

[D25] Set 集合去重与交并差
来源：http://dali.jqgufenzy.top/Article/details/gt2nmoqtvpz.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.guowangkeji.top/Article/details/gt2dhaocith.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.pengpengdd.cyou/Article/details/gt2ggkqlaxw.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.sxryk.cn/Article/details/gt2uypdwzuv.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hongshengwenyu.top/Article/details/gt2jtesrngr.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.nanxuanxn.top/Article/details/gt2ztsjfbwd.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hammf.cn/Article/details/gt2rzjzxgsq.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.aibaodan.cn/Article/details/gt2pmfuaini.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.sufxvd.cn/Article/details/gt2wtridlpq.html

[D26] 数组转字符串
来源：http://dali.shuidangran.top/Article/details/gt2bplpsdze.html

Py:   ", ".join(map(str, arr))
来源：http://dali.aizwys.cn/Article/details/gt2iovgcjik.html

PHP:  implode(", ", $arr);
来源：http://dali.aibaodan.cn/Article/details/gt2cktzdjnh.html

JS:   arr.join(", ")
来源：http://dali.hammf.cn/Article/details/gt2tgyclsxm.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2ymhxocur.html

Java: String.join(", ", list)
来源：http://dali.haohaochexian.top/Article/details/gt2iqydwsoj.html

Go:   strings.Join(strs, ", ")
来源：http://dali.fengsongda.top/Article/details/gt2zlmtunno.html

Ruby: arr.join(", ")
来源：http://dali.hnxiangtu.top/Article/details/gt2ppxwvwdn.html

C#:   string.Join(", ", list)
来源：http://dali.yj202588.top/Article/details/gt2fjnzblcq.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2elsaovdu.html

E. 字符串处理
来源：http://dali.nwbrower.top/Article/details/gt2rzuazwdk.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2aqrsvuez.html

[E01] 拼接字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2odvhmtyd.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hongshengwenyu.top/Article/details/gt2vfqjipdv.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.shuidangran.top/Article/details/gt2jygpzbsv.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hammf.cn/Article/details/gt2kdjgvjle.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.sysykeji.top/Article/details/gt2tlzbbndm.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.dianchejie.cn/Article/details/gt2gklyifgt.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.cheryme.top/Article/details/gt2vcdjqnvw.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.pycfn.com/Article/details/gt2bltqhenc.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.shuidangran.top/Article/details/gt2swrrlkjt.html

[E02] 重复字符串
来源：http://dali.ydzc1.top/Article/details/gt2zfwkdmba.html

Py:   "ab" * 3
来源：http://dali.yj20258888.top/Article/details/gt2nbggavdo.html

PHP:  str_repeat("ab", 3);
来源：http://dali.nanxuanxn.top/Article/details/gt2mufpnbzh.html

JS:   "ab".repeat(3)
来源：http://dali.yj202588.top/Article/details/gt2ibncohhb.html

TS:   "ab".repeat(3)
来源：http://dali.daria6918.cn/Article/details/gt2qtawkfra.html

Java: "ab".repeat(3)
来源：http://dali.shzxlz.cn/Article/details/gt2kkmhzgky.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.feifeiyinyue.top/Article/details/gt2pmfcedvt.html

Ruby: "ab" * 3
来源：http://dali.chenlongwang.top/Article/details/gt2aphzqufc.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.dianchejie.cn/Article/details/gt2kyinceso.html

[E03] 截取子串
来源：http://dali.sufxvd.cn/Article/details/gt2hkepsxad.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.fengsongda.top/Article/details/gt2mknwpabu.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.hongshengwenyu.top/Article/details/gt2pzzgjetm.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.aibaodan.cn/Article/details/gt2rhvianun.html

TS:   s.slice(1, 4)
来源：http://dali.havefunace.top/Article/details/gt2ivaneypt.html

Java: s.substring(1, 4)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ewtqnscz.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zdqjudy.top/Article/details/gt2lvtuvxot.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.nanxuanxn.top/Article/details/gt2xvrptabg.html

C#:   s.Substring(1, 3)
来源：http://dali.gaohongyu789.top/Article/details/gt2zgswvhao.html

[E04] 查找子串位置
来源：http://dali.chenjidiqi.icu/Article/details/gt2hdlslueu.html

Py:   s.find("x");  s.index("x")
来源：http://dali.9152youxi.cn/Article/details/gt2qtwqjyql.html

PHP:  strpos($s, "x");
来源：http://dali.vqdsnc.cn/Article/details/gt2veibkimc.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.fengsongda.top/Article/details/gt2qmvrurjj.html

TS:   s.indexOf("x")
来源：http://dali.cqqwz.cn/Article/details/gt2zrlvkcjp.html

Java: s.indexOf("x")
来源：http://dali.jiagoushi.top/Article/details/gt2cthlepoe.html

Go:   strings.Index(s, "x")
来源：http://dali.tianlin.xyz/Article/details/gt2ywteubyd.html

Ruby: s.index("x")
来源：http://dali.zycfv.cn/Article/details/gt2ldcmyhmm.html

C#:   s.IndexOf("x")
来源：http://dali.cqqwz.cn/Article/details/gt2wxcucbmk.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yj202588.top/Article/details/gt2rihjzess.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.pengpengdd.cyou/Article/details/gt2gbfdfoyu.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.gotoacloud.top/Article/details/gt2rgojtqls.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.daxiang520.top/Article/details/gt2wizafptd.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jqgfzy.top/Article/details/gt2tvnjyarf.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yuxming.cn/Article/details/gt2btvndzuq.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.birdmap.top/Article/details/gt2zzsnffnv.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.tanke756.top/Article/details/gt2tongigyg.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.shangyingyoupin.top/Article/details/gt2ucwqgtbj.html

[E06] 替换子串
来源：http://dali.tianlin.xyz/Article/details/gt2xgxdffxi.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2xpxuoqmw.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.svipenyu.cn/Article/details/gt2nwhjohwe.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shzxlz.cn/Article/details/gt2saifypel.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jlsjyb.cn/Article/details/gt2mmtdphrv.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gzhubu.top/Article/details/gt2qnkgxtke.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.daxiang520.top/Article/details/gt2gdvrgqmw.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jinqigfzy.top/Article/details/gt2ymrfekgf.html

C#:   s.Replace("a", "b")
来源：http://dali.hnxiangtu.top/Article/details/gt2czvkzjoh.html

[E07] 按分隔符拆分
来源：http://dali.hfpthk.cn/Article/details/gt2rrvsfgzx.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.feifeiyinyue.top/Article/details/gt2xuposils.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gt2kawcqiwn.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.cdnleiting.top/Article/details/gt2qwalazct.html

TS:   s.split(",")
来源：http://dali.hfpthk.cn/Article/details/gt2vjchdogk.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.hongshengwenyu.top/Article/details/gt2vcebdfec.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sjoaemvp.html

Ruby: s.split(",");  s.split
来源：http://dali.ydzc1.top/Article/details/gt2jadcyztw.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.ybcxt.top/Article/details/gt2ayovjlur.html

[E08] 数组按分隔符合并
来源：http://dali.sweek.top/Article/details/gt2rshgrzda.html

Py:   ",".join(items)
来源：http://dali.zhengqikj.top/Article/details/gt2lyjtqfiy.html

PHP:  implode(",", $items);
来源：http://dali.pycfn.com/Article/details/gt2iamklhqi.html

JS:   items.join(",")
来源：http://dali.svipenyu.cn/Article/details/gt2cjvckrag.html

TS:   items.join(",")
来源：http://dali.yangfankeji.com/Article/details/gt2duekybty.html

Java: String.join(",", items)
来源：http://dali.tian-w.cn/Article/details/gt2kgmdknbb.html

Go:   strings.Join(items, ",")
来源：http://dali.0kj1m.cn/Article/details/gt2ghsgdtmn.html

Ruby: items.join(",")
来源：http://dali.svipenyu.cn/Article/details/gt2ylrafhid.html

C#:   string.Join(",", items)
来源：http://dali.jqgufenzy.top/Article/details/gt2rlijrhlm.html

[E09] 去除所有空白字符
来源：http://dali.jqgufenzy.top/Article/details/gt2woialkyn.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.9152youxi.cn/Article/details/gt2pieqmhjv.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jlsjyb.cn/Article/details/gt2xxrzgsbf.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.gotoacloud.top/Article/details/gt2pqvlizhv.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yuxming.cn/Article/details/gt2rarepvwr.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yonumen.top/Article/details/gt2doxmnzde.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.nanxuanxn.top/Article/details/gt2jxmrrbmu.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.shuidangran.top/Article/details/gt2gdmnkfka.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.gzhubu.top/Article/details/gt2bkdfhaef.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yj20258.top/Article/details/gt2qibmvawa.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.ppjwa.cn/Article/details/gt2cltnxkre.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.ppjwa.cn/Article/details/gt2latfkcip.html

JS:   "7".padStart(3, "0")
来源：http://dali.nanxinkj.top/Article/details/gt2yaihzhgm.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhongyouzk.top/Article/details/gt2pnwmbvmf.html

Java: String.format("%03d", 7)
来源：http://dali.yueranfly.top/Article/details/gt2yffsfbtk.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.nwbrower.top/Article/details/gt2dnzrnihm.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yueranfly.top/Article/details/gt2tevxyhqi.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.daria6918.cn/Article/details/gt2eoktvwbk.html

[E11] 反转字符串
来源：http://dali.nwbrower.top/Article/details/gt2jsvutcba.html

Py:   s[::-1]
来源：http://dali.bjfxy.top/Article/details/gt2vtwftgfd.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2cwztzeoc.html

JS:   [...s].reverse().join("")
来源：http://dali.zhengqikj.top/Article/details/gt2sgvwwxxk.html

TS:   [...s].reverse().join("")
来源：http://dali.xuetiantiany.cn/Article/details/gt2nlvnzczs.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yj202588.top/Article/details/gt2tvsvubmm.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hnxiangtu.top/Article/details/gt2gcvrorad.html

Ruby: s.reverse
来源：http://dali.yj20258888.top/Article/details/gt2tjhbgups.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yongpay.top/Article/details/gt2zdpgwjbc.html

[E12] 统计某字符出现次数
来源：http://dali.nanxuanxn.top/Article/details/gt2nlmzykab.html

Py:   s.count("a")
来源：http://dali.havefunace.top/Article/details/gt2crjyozoq.html

PHP:  substr_count($s, "a");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dykulkef.html

JS:   s.split("a").length - 1
来源：http://dali.yvedp.cn/Article/details/gt2oixvlqqj.html

TS:   s.split("a").length - 1
来源：http://dali.bjfxy.top/Article/details/gt2yrfthbkd.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.chenlongwang.top/Article/details/gt2qmdpivmu.html

Go:   strings.Count(s, "a")
来源：http://dali.guannengcc.top/Article/details/gt2eksbrrgt.html

Ruby: s.count("a")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hugfanrn.html

C#:   s.Count(c => c == 'a')
来源：http://dali.hysaishi.cn/Article/details/gt2mviiusqs.html

[E13] 逐字符遍历
来源：http://dali.pycfn.com/Article/details/gt2thwecqju.html

Py:   for ch in s: print(ch)
来源：http://dali.andypj.xyz/Article/details/gt2xvokcttt.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.sufxvd.cn/Article/details/gt2pfuqkpik.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cqqwz.cn/Article/details/gt2tivqolug.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.c1oappe.top/Article/details/gt2ynlchlok.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.c1oappe.top/Article/details/gt2lenngxvk.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.xuetiantiany.cn/Article/details/gt2pfvsywiq.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.ehwqpu.com/Article/details/gt2tlpwmzxh.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.c1oappe.top/Article/details/gt2pzplcqvn.html

[E14] URL 编码与 Base64
来源：http://dali.sufxvd.cn/Article/details/gt2cyuwoiqg.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.shzxlz.cn/Article/details/gt2tudkllbt.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.haohaochexian.top/Article/details/gt2revywmjr.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.guowangkeji.top/Article/details/gt2nxoqgrto.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yonumen.top/Article/details/gt2rqqazxcn.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.aizwys.cn/Article/details/gt2urdtvgwc.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.fzhhl.top/Article/details/gt2rsqwucwd.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.cheryme.top/Article/details/gt2fzuprdsg.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jiagoushi.top/Article/details/gt2wzpjfhyq.html

[E15] HTML 转义 / 反转义
来源：http://dali.ehwqpu.com/Article/details/gt2okoqokpx.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jyoumei.cn/Article/details/gt2dsezihes.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yongpay.top/Article/details/gt2emgzutyy.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yuanzhike.top/Article/details/gt2qxdfzsdh.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hnxiangtu.top/Article/details/gt2zaedolll.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.aizwys.cn/Article/details/gt2kzznuupw.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hnqzz.top/Article/details/gt2hyimxpuu.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.kuanghao11.cn/Article/details/gt2qjaitxbo.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.cheryme.top/Article/details/gt2pzuopjez.html

[E16] 数字千分位
来源：http://dali.jyoumei.cn/Article/details/gt2edsfdsrr.html

Py:   f"{1234567:,}"
来源：http://dali.jqgufenzy.top/Article/details/gt2ozhcikpl.html

PHP:  number_format(1234567);
来源：http://dali.dianchejie.cn/Article/details/gt2jcsuteae.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.shangyingyoupin.top/Article/details/gt2vdnbeima.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.iojbl.cn/Article/details/gt2edwjlamf.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yuxming.cn/Article/details/gt2gctmgxzn.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yangfankeji.com/Article/details/gt2haumzidq.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.gzhubu.top/Article/details/gt2jvslcfxs.html

C#:   1234567.ToString("N0")
来源：http://dali.guannengcc.top/Article/details/gt2pafdroyv.html

[E17] 首字母大写
来源：http://dali.gotoacloud.top/Article/details/gt2gxzqqauo.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.nanxuanxn.top/Article/details/gt2fnwryahc.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fxhjscze.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xuanzx.com/Article/details/gt2rvwwjdbx.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.9152youxi.cn/Article/details/gt2ytdngurr.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.nanxinkj.top/Article/details/gt2pmauzbpy.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yongpay.top/Article/details/gt2gwlqqjzp.html

Ruby: s.capitalize
来源：http://dali.jlsjyb.cn/Article/details/gt2dpeaqexg.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhiwuduotai.top/Article/details/gt2sgndblky.html

[E18] 模板占位符替换
来源：http://dali.cucudq.cn/Article/details/gt2ggbrtdkk.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.gaohongyu789.top/Article/details/gt2isstvtkh.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.gotoacloud.top/Article/details/gt2eqwnnhgf.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhoulong.xyz/Article/details/gt2cpyjfqzh.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jyoumei.cn/Article/details/gt2wulhgjsi.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.bjfxy.top/Article/details/gt2iheryphz.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.dianchejie.cn/Article/details/gt2uhzoabwz.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.xinyue.icu/Article/details/gt2zfmsyywn.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.hammf.cn/Article/details/gt2eqcuiati.html

[E19] 多行文本按行拆分
来源：http://dali.wangdashe.top/Article/details/gt2xzydpetc.html

Py:   s.splitlines()
来源：http://dali.sweek.top/Article/details/gt2sprrdmoc.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hywenlv.cn/Article/details/gt2xkpqneyf.html

JS:   s.split(/\r?\n/)
来源：http://dali.gotoacloud.top/Article/details/gt2jvysshvg.html

TS:   s.split(/\r?\n/)
来源：http://dali.tianlin.xyz/Article/details/gt2bpgpioqq.html

Java: s.lines().toList()
来源：http://dali.xuanzx.com/Article/details/gt2jfpwjgur.html

Go:   strings.Split(s, "\n")
来源：http://dali.yanxiufei.cn/Article/details/gt2cwrrgamd.html

Ruby: s.lines
来源：http://dali.haohaochexian.top/Article/details/gt2fuklszdc.html

C#:   s.Split('\n')
来源：http://dali.sysykeji.top/Article/details/gt2rngxtvmx.html

[E20] 判断字符串是否为空
来源：http://dali.andypj.xyz/Article/details/gt2whetumvr.html

Py:   if not s:
来源：http://dali.hongshengwenyu.top/Article/details/gt2sacodmaa.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.shzxlz.cn/Article/details/gt2ochwnwoy.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.guannengcc.top/Article/details/gt2ddnurtvu.html

TS:   if (s === "") {}
来源：http://dali.dianchejie.cn/Article/details/gt2zdzkijan.html

Java: if (s.isEmpty()) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2grgmjikf.html

Go:   if s == "" {}
来源：http://dali.cqqwz.cn/Article/details/gt2wbrpdbic.html

Ruby: if s.empty?
来源：http://dali.aibaodan.cn/Article/details/gt2rpenrzve.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.iojbl.cn/Article/details/gt2fjtbrzbk.html

[E21] 超长截断加省略号
来源：http://dali.tanke756.top/Article/details/gt2bpqvbiph.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.quarkkingdee.top/Article/details/gt2zkenvgca.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.dianchejie.cn/Article/details/gt2diiikomr.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.andypj.xyz/Article/details/gt2pdbhhgyb.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lzsegkxa.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hnqzz.top/Article/details/gt2rkowrtsi.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.daxiang520.top/Article/details/gt2kxngjbxy.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhongyouzk.top/Article/details/gt2bxbnuypm.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jiagoushi.top/Article/details/gt2wlnceiuc.html

[E22] 字节长度与字符长度
来源：http://dali.yuxming.cn/Article/details/gt2dtztwerc.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.gogol.net.cn/Article/details/gt2wzvhqdxh.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.0kj1m.cn/Article/details/gt2viptfpzz.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.redwolf501.top/Article/details/gt2didoztnp.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.aibaodan.cn/Article/details/gt2pjxopyim.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yongpay.top/Article/details/gt2qvetvkja.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.xuetiantiany.cn/Article/details/gt2bmfiqbrj.html

Ruby: s.bytesize;  s.length
来源：http://dali.gogol.net.cn/Article/details/gt2hrmewlec.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.birdmap.top/Article/details/gt2ucjnfqys.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2iptlguvh.html

F. 文件与目录
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kbwsfljn.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2wqdcnmpq.html

[F01] 读取整个文件
来源：http://dali.yangfankeji.com/Article/details/gt2fegyftnf.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.vqdsnc.cn/Article/details/gt2haqdxsqv.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yj20258.top/Article/details/gt2xaziuwas.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jyoumei.cn/Article/details/gt2qseinaey.html


<!-- 参考信息 -->