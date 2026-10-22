代发 wailian999

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.fzhhl.top/Article/details/gt2ngxshlkb.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uqwandon.html

JS:   arr.map(x => x * 2)
来源：http://dali.hongshengwenyu.top/Article/details/gt2folgjrnt.html

TS:   arr.map(x => x * 2)
来源：http://dali.guannengcc.top/Article/details/gt2cywwgwah.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.cqqwz.cn/Article/details/gt2tuffafad.html

Go:   // 手写循环
来源：http://dali.hysaishi.cn/Article/details/gt2zyvwticw.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.sxryk.cn/Article/details/gt2wxlhmnex.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hhecxfcn.html

[D15] 去重
来源：http://dali.hysaishi.cn/Article/details/gt2xpwjbhxj.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.xuanzx.com/Article/details/gt2yhnnclcc.html

PHP:  array_unique($arr);
来源：http://dali.yj20258888.top/Article/details/gt2xrqlhkik.html

JS:   [...new Set(arr)]
来源：http://dali.wangshuangyany.cn/Article/details/gt2junmvvqz.html

TS:   [...new Set(arr)]
来源：http://dali.hywenlv.cn/Article/details/gt2hotxcsly.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eaqbpsvx.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.shangyingyoupin.top/Article/details/gt2xjgpawpj.html

Ruby: arr.uniq
来源：http://dali.sysykeji.top/Article/details/gt2rzdafoek.html

C#:   list.Distinct().ToList()
来源：http://dali.snrcjt.cn/Article/details/gt2pzcjedar.html

[D16] 求和与平均值
来源：http://dali.birdmap.top/Article/details/gt2koeasqcn.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.mhx1999.top/Article/details/gt2jatnbbuc.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.guowangkeji.top/Article/details/gt2fzfhlegg.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yuxming.cn/Article/details/gt2ivevoiyb.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yonumen.top/Article/details/gt2iiiovbcg.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hysaishi.cn/Article/details/gt2gtusngfn.html

Go:   // 手写循环累加
来源：http://dali.xinyue.icu/Article/details/gt2eoyuqsyg.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.fengsongda.top/Article/details/gt2ssnmryvl.html

C#:   list.Sum();  list.Average()
来源：http://dali.ydzc1.top/Article/details/gt2ceysxdad.html

[D17] 最大值与最小值
来源：http://dali.yj202588.top/Article/details/gt2mxharzgh.html

Py:   max(arr);  min(arr)
来源：http://dali.xinyue.icu/Article/details/gt2xoexuyfh.html

PHP:  max($arr);  min($arr);
来源：http://dali.jinqigfzy.top/Article/details/gt2kmgerrof.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.gzhubu.top/Article/details/gt2wgyaiwhh.html

TS:   Math.max(...arr);
来源：http://dali.kuanghao11.cn/Article/details/gt2wzeyhlyf.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.nwbrower.top/Article/details/gt2fspudnfw.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.guannengcc.top/Article/details/gt2rowgylel.html

Ruby: arr.max;  arr.min
来源：http://dali.smart0.xyz/Article/details/gt2ejhnjxjx.html

C#:   list.Max();  list.Min()
来源：http://dali.yangfankeji.com/Article/details/gt2oftkdpyy.html

[D18] 扁平化嵌套数组
来源：http://dali.yonumen.top/Article/details/gt2xslotgnz.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.tianlin.xyz/Article/details/gt2lbqdauwy.html

PHP:  array_merge(...$nested);
来源：http://dali.gzhubu.top/Article/details/gt2bgixqrog.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yj20258888.top/Article/details/gt2nxbtyini.html

TS:   nested.flat();
来源：http://dali.xinyue.icu/Article/details/gt2nbqaqnce.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.guannengcc.top/Article/details/gt2uqzzdodm.html

Go:   // 手写双层循环
来源：http://dali.316326.xyz/Article/details/gt2vagrzktm.html

Ruby: nested.flatten
来源：http://dali.shzxlz.cn/Article/details/gt2jqneuyqa.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.fzhhl.top/Article/details/gt2qlefyoay.html

[D19] 按字段分组
来源：http://dali.wangdashe.top/Article/details/gt2hrswkxqz.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2pbydpbpu.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.pengpengdd.cyou/Article/details/gt2tnlrcwpz.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qmebzqtr.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhongyouzk.top/Article/details/gt2wkmdzaez.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.guannengcc.top/Article/details/gt2lcezbaqn.html

Go:   // 手写 map[string][]T
来源：http://dali.xinyue.icu/Article/details/gt2mhzjvrdk.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhiwuduotai.top/Article/details/gt2xzlhiick.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.bjfxy.top/Article/details/gt2rsbgicql.html

[D20] 统计每个元素出现次数
来源：http://dali.gogol.net.cn/Article/details/gt2hrvtplpa.html

Py:   Counter(arr)
来源：http://dali.ydzc1.top/Article/details/gt2qjwejacr.html

PHP:  array_count_values($arr);
来源：http://dali.vqdsnc.cn/Article/details/gt2nxoqwcdo.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xuetiantiany.cn/Article/details/gt2tpdweuxq.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.aibaodan.cn/Article/details/gt2nteykhaz.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yj20258888.top/Article/details/gt2uzjityih.html

Go:   // 手写 map[T]int
来源：http://dali.shzxlz.cn/Article/details/gt2eemvgrdz.html

Ruby: arr.tally
来源：http://dali.hnqzz.top/Article/details/gt2ouapvatx.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.wangdashe.top/Article/details/gt2zjyskbjk.html

[D21] 判断是否包含某元素
来源：http://dali.nanxinkj.top/Article/details/gt2xtdkoopg.html

Py:   x in arr
来源：http://dali.daria6918.cn/Article/details/gt2vqnbvqwv.html

PHP:  in_array($x, $arr, true);
来源：http://dali.redwolf501.top/Article/details/gt2kabtxlok.html

JS:   arr.includes(x)
来源：http://dali.jiagoushi.top/Article/details/gt2engggntq.html

TS:   arr.includes(x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2evseemnf.html

Java: list.contains(x)
来源：http://dali.fzhhl.top/Article/details/gt2uvafnqso.html

Go:   slices.Contains(arr, x)
来源：http://dali.tanke756.top/Article/details/gt2zwxnajam.html

Ruby: arr.include?(x)
来源：http://dali.zdqjudy.top/Article/details/gt2tcustelo.html

C#:   list.Contains(x)
来源：http://dali.haohaochexian.top/Article/details/gt2nyhjdpfx.html

[D22] 复制数组（避免共享引用）
来源：http://dali.feifeiyinyue.top/Article/details/gt2ycihkadz.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.tanke756.top/Article/details/gt2kwqtyekr.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhoulong.xyz/Article/details/gt2gkwifuzk.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.cucudq.cn/Article/details/gt2htsifhnc.html

TS:   [...arr];
来源：http://dali.tian-w.cn/Article/details/gt2drzvmyom.html

Java: new ArrayList<>(list);
来源：http://dali.redwolf501.top/Article/details/gt2stqeeepe.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.chenlongwang.top/Article/details/gt2kalkmfip.html

Ruby: arr.dup;  arr.clone
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oqzkarwh.html

C#:   new List<int>(list);
来源：http://dali.zhixingplan.top/Article/details/gt2bqbadrwx.html

[D23] reduce 累积计算
来源：http://dali.ydzc1.top/Article/details/gt2qkkgjswr.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jqgufenzy.top/Article/details/gt2pajsudnd.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.iojbl.cn/Article/details/gt2uryiuoyr.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ivvv.top/Article/details/gt2tfsvawqj.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cheryme.top/Article/details/gt2ajqbilpx.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.iojbl.cn/Article/details/gt2ukfwrczz.html

Go:   // 手写循环
来源：http://dali.hnxiangtu.top/Article/details/gt2rncztlhu.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yuxming.cn/Article/details/gt2fujccnls.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.xylfe.cn/Article/details/gt2jzmlcdlh.html

[D24] 字典 / Map 基本操作
来源：http://dali.cucudq.cn/Article/details/gt2uftjavob.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.guannengcc.top/Article/details/gt2xnntfpdm.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.ivvv.top/Article/details/gt2rvgludcr.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.chenzaomai.com/Article/details/gt2enradzpn.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yj20258.top/Article/details/gt2rhhbtgrh.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cxipeatc.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.ydzc1.top/Article/details/gt2dzpuwten.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.daria6918.cn/Article/details/gt2dtqtwrqy.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yongpay.top/Article/details/gt2pmtmdoyh.html

[D25] Set 集合去重与交并差
来源：http://dali.zhiwuduotai.top/Article/details/gt2kruqgskw.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.ydzc1.top/Article/details/gt2lnarkfcy.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.redwolf501.top/Article/details/gt2stuqnmub.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.bjfxy.top/Article/details/gt2ztyvifec.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.sufxvd.cn/Article/details/gt2kjiimccj.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yj20258.top/Article/details/gt2qpspuesa.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.xziqi.cn/Article/details/gt2dodvdcyv.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.sweek.top/Article/details/gt2hzqljynq.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jyoumei.cn/Article/details/gt2lwceypwf.html

[D26] 数组转字符串
来源：http://dali.yj20258.top/Article/details/gt2rplaslnh.html

Py:   ", ".join(map(str, arr))
来源：http://dali.ybcxt.top/Article/details/gt2ejgojhrq.html

PHP:  implode(", ", $arr);
来源：http://dali.yonumen.top/Article/details/gt2elurnxxh.html

JS:   arr.join(", ")
来源：http://dali.jyoumei.cn/Article/details/gt2quctgzxs.html

TS:   arr.join(", ")
来源：http://dali.yj20258888.top/Article/details/gt2zsntkdgf.html

Java: String.join(", ", list)
来源：http://dali.daria6918.cn/Article/details/gt2lzxzypif.html

Go:   strings.Join(strs, ", ")
来源：http://dali.cucudq.cn/Article/details/gt2cnbelcua.html

Ruby: arr.join(", ")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ddbsvjqx.html

C#:   string.Join(", ", list)
来源：http://dali.xuanzx.com/Article/details/gt2rdeglgqt.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2bsimhjpt.html

E. 字符串处理
来源：http://dali.andypj.xyz/Article/details/gt2lcchngfs.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2yuwscdkg.html

[E01] 拼接字符串
来源：http://dali.xuetiantiany.cn/Article/details/gt2nyxyzhhc.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jinqigfzy.top/Article/details/gt2jtuopmgr.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.cqqwz.cn/Article/details/gt2znpuxfra.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2dtytgsbd.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xuanzx.com/Article/details/gt2gbybxslr.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hysaishi.cn/Article/details/gt2quftifze.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhoulong.xyz/Article/details/gt2ozhamqqo.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yueranfly.top/Article/details/gt2hehnkumn.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.sweek.top/Article/details/gt2qatsctno.html

[E02] 重复字符串
来源：http://dali.jinqigfzy.top/Article/details/gt2cymeymoe.html

Py:   "ab" * 3
来源：http://dali.xuetiantiany.cn/Article/details/gt2kysmzmij.html

PHP:  str_repeat("ab", 3);
来源：http://dali.wangshuangyany.cn/Article/details/gt2vxrzgklw.html

JS:   "ab".repeat(3)
来源：http://dali.gogol.net.cn/Article/details/gt2xdmujvgk.html

TS:   "ab".repeat(3)
来源：http://dali.xuanzx.com/Article/details/gt2vbocznad.html

Java: "ab".repeat(3)
来源：http://dali.ybcxt.top/Article/details/gt2ydzwdnlh.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.xziqi.cn/Article/details/gt2cflwguth.html

Ruby: "ab" * 3
来源：http://dali.ybcxt.top/Article/details/gt2ertssrog.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.gzhubu.top/Article/details/gt2ngwmlsgb.html

[E03] 截取子串
来源：http://dali.pengpengdd.cyou/Article/details/gt2zxejfirb.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yuanzhike.top/Article/details/gt2hbojpbto.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.cashguo.top/Article/details/gt2gqrccktj.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jinqigufen.top/Article/details/gt2nqjtaphs.html

TS:   s.slice(1, 4)
来源：http://dali.sweek.top/Article/details/gt2esgahizr.html

Java: s.substring(1, 4)
来源：http://dali.yangfankeji.com/Article/details/gt2ymwvkkir.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.fengsongda.top/Article/details/gt2umbhgjmr.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.0kj1m.cn/Article/details/gt2atxfqntz.html

C#:   s.Substring(1, 3)
来源：http://dali.yuanzhike.top/Article/details/gt2ehonynaw.html

[E04] 查找子串位置
来源：http://dali.cashguo.top/Article/details/gt2ztowldwd.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jianghu66.top/Article/details/gt2bnjkytzq.html

PHP:  strpos($s, "x");
来源：http://dali.chenjidiqi.icu/Article/details/gt2mozwyweo.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.daria6918.cn/Article/details/gt2ymvtkhnn.html

TS:   s.indexOf("x")
来源：http://dali.gaohongyu789.top/Article/details/gt2cdwdzslx.html

Java: s.indexOf("x")
来源：http://dali.hysaishi.cn/Article/details/gt2alybfcgm.html

Go:   strings.Index(s, "x")
来源：http://dali.daxiang520.top/Article/details/gt2zxnbfisg.html

Ruby: s.index("x")
来源：http://dali.jlsjyb.cn/Article/details/gt2ffsebcbh.html

C#:   s.IndexOf("x")
来源：http://dali.gotoacloud.top/Article/details/gt2nxdfyyey.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yuanzhike.top/Article/details/gt2syfdfjkj.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jinqigfzy.top/Article/details/gt2nakbewcn.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.xziqi.cn/Article/details/gt2bzmhrnyi.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shangyingyoupin.top/Article/details/gt2llfedzae.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.xuetiantiany.cn/Article/details/gt2prahoikq.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.kuanghao11.cn/Article/details/gt2masgizlv.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.vqdsnc.cn/Article/details/gt2sbevzwnx.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhongyouzk.top/Article/details/gt2zipfnvhh.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yj202588.top/Article/details/gt2mpsozrxq.html

[E06] 替换子串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lsdlravn.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.fengsongda.top/Article/details/gt2gukdoxwp.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.ppjwa.cn/Article/details/gt2pjvgkefd.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zdqjudy.top/Article/details/gt2dluluhwj.html

TS:   s.replaceAll("a", "b")
来源：http://dali.sxryk.cn/Article/details/gt2ktwyktcl.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhongyouzk.top/Article/details/gt2dolbgoyt.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.xinyue.icu/Article/details/gt2jkaecjfj.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.9152youxi.cn/Article/details/gt2ntbgruxw.html

C#:   s.Replace("a", "b")
来源：http://dali.ivvv.top/Article/details/gt2imuerxvv.html

[E07] 按分隔符拆分
来源：http://dali.cucudq.cn/Article/details/gt2sjougxes.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.fzhhl.top/Article/details/gt2fzorwjoo.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.nanxinkj.top/Article/details/gt2mrbfcjeu.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.hammf.cn/Article/details/gt2jdyzliig.html

TS:   s.split(",")
来源：http://dali.tanke756.top/Article/details/gt2caykozpz.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.birdmap.top/Article/details/gt2wlxbqjgx.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.dashuyun.cn/Article/details/gt2chqvgbin.html

Ruby: s.split(",");  s.split
来源：http://dali.yanxiufei.cn/Article/details/gt2xhaguwzr.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.cucudq.cn/Article/details/gt2mlpxjblr.html

[E08] 数组按分隔符合并
来源：http://dali.gaohongyu789.top/Article/details/gt2tgnticmb.html

Py:   ",".join(items)
来源：http://dali.xuetiantiany.cn/Article/details/gt2shcfpghi.html

PHP:  implode(",", $items);
来源：http://dali.sxryk.cn/Article/details/gt2xqybcltb.html

JS:   items.join(",")
来源：http://dali.hysaishi.cn/Article/details/gt2bzuvltrk.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2tjtliaop.html

Java: String.join(",", items)
来源：http://dali.guowangkeji.top/Article/details/gt2lakfprak.html

Go:   strings.Join(items, ",")
来源：http://dali.fzhhl.top/Article/details/gt2xfsntyir.html

Ruby: items.join(",")
来源：http://dali.nanxuanxn.top/Article/details/gt2yubrgxif.html

C#:   string.Join(",", items)
来源：http://dali.sysykeji.top/Article/details/gt2tnrzrdyj.html

[E09] 去除所有空白字符
来源：http://dali.daxiang520.top/Article/details/gt2pnkwqfky.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.hywenlv.cn/Article/details/gt2ydicrftr.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.dashuyun.cn/Article/details/gt2izkzqlzp.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kmvobykd.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.mhx1999.top/Article/details/gt2qmbirzte.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhoulong.xyz/Article/details/gt2pzcudghj.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oljgrnsw.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pdojwdbq.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.cqqwz.cn/Article/details/gt2lytfzcwp.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jiagoushi.top/Article/details/gt2urjtauie.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yonumen.top/Article/details/gt2uuvprjtm.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yuxming.cn/Article/details/gt2hkzgutsa.html

JS:   "7".padStart(3, "0")
来源：http://dali.snrcjt.cn/Article/details/gt2nbykigah.html

TS:   "7".padStart(3, "0")
来源：http://dali.haohaochexian.top/Article/details/gt2bmfrjsqb.html

Java: String.format("%03d", 7)
来源：http://dali.dashuyun.cn/Article/details/gt2xigfpgyk.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.hongshengwenyu.top/Article/details/gt2onuoykhn.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hongshengwenyu.top/Article/details/gt2vuqbeore.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.hnxiangtu.top/Article/details/gt2fybowysk.html

[E11] 反转字符串
来源：http://dali.snrcjt.cn/Article/details/gt2wiepjkik.html

Py:   s[::-1]
来源：http://dali.daria6918.cn/Article/details/gt2gcoesgxv.html

PHP:  strrev($s);
来源：http://dali.aizwys.cn/Article/details/gt2kopgxqcb.html

JS:   [...s].reverse().join("")
来源：http://dali.zdqjudy.top/Article/details/gt2qkuabweh.html

TS:   [...s].reverse().join("")
来源：http://dali.xuanzx.com/Article/details/gt2dlilnmxq.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.fengsongda.top/Article/details/gt2lodqmwlz.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.nanxinkj.top/Article/details/gt2rqvhbxbf.html

Ruby: s.reverse
来源：http://dali.xuanzx.com/Article/details/gt2qzxdxisr.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.iojbl.cn/Article/details/gt2ajxqvisn.html

[E12] 统计某字符出现次数
来源：http://dali.vqdsnc.cn/Article/details/gt2iiwzhbrj.html

Py:   s.count("a")
来源：http://dali.316326.xyz/Article/details/gt2kgmxhohp.html

PHP:  substr_count($s, "a");
来源：http://dali.hysaishi.cn/Article/details/gt2ywltokzo.html

JS:   s.split("a").length - 1
来源：http://dali.kuanghao11.cn/Article/details/gt2hbotbpdy.html

TS:   s.split("a").length - 1
来源：http://dali.nwbrower.top/Article/details/gt2tetwskny.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.daria6918.cn/Article/details/gt2tzefjzjd.html

Go:   strings.Count(s, "a")
来源：http://dali.dashuyun.cn/Article/details/gt2hghrycns.html

Ruby: s.count("a")
来源：http://dali.smart0.xyz/Article/details/gt2yznjzcbb.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yuxming.cn/Article/details/gt2zznmzlxp.html

[E13] 逐字符遍历
来源：http://dali.gzhubu.top/Article/details/gt2yugmfbqg.html

Py:   for ch in s: print(ch)
来源：http://dali.yueranfly.top/Article/details/gt2cqnzpaxo.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.chenzaomai.com/Article/details/gt2vlhonrfi.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tanke756.top/Article/details/gt2ffnseign.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yuanzhike.top/Article/details/gt2nppdkqro.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jqgfzy.top/Article/details/gt2kqvxepqw.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.shuidangran.top/Article/details/gt2uyzbaypy.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.nanxuanxn.top/Article/details/gt2mluiodrd.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.cdnleiting.top/Article/details/gt2rxypcpak.html

[E14] URL 编码与 Base64
来源：http://dali.jqgfzy.top/Article/details/gt2hjvlgzao.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sklqccul.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.nanxinkj.top/Article/details/gt2rrpbrtmm.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.shuidangran.top/Article/details/gt2upxaogfy.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2preasias.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hnxiangtu.top/Article/details/gt2tyjgzgmz.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jqgufenzy.top/Article/details/gt2zgrdgvuz.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ljgjkkmd.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.shuidangran.top/Article/details/gt2ptieuiuf.html

[E15] HTML 转义 / 反转义
来源：http://dali.jiagoushi.top/Article/details/gt2tcktbycv.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.316326.xyz/Article/details/gt2vlsnnmyc.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhiwuduotai.top/Article/details/gt2hlwtoqoh.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zdqjudy.top/Article/details/gt2mtjnvpmq.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.9152youxi.cn/Article/details/gt2ejdsdnag.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.dashuyun.cn/Article/details/gt2hhozvipi.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zycfv.cn/Article/details/gt2rhapxqzs.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wbbfmymr.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2rnhnadym.html

[E16] 数字千分位
来源：http://dali.zhixingplan.top/Article/details/gt2rsumupgd.html

Py:   f"{1234567:,}"
来源：http://dali.nanxuanxn.top/Article/details/gt2tduqmkuf.html

PHP:  number_format(1234567);
来源：http://dali.sysykeji.top/Article/details/gt2rrardtfc.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yanxiufei.cn/Article/details/gt2iajinnxa.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.birdmap.top/Article/details/gt2pfvagdmv.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yj20258888.top/Article/details/gt2mzqqyold.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hfpthk.cn/Article/details/gt2uvyoqpvy.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jqgufenzy.top/Article/details/gt2vshaivfh.html

C#:   1234567.ToString("N0")
来源：http://dali.zhiwuduotai.top/Article/details/gt2flxdkmhv.html

[E17] 首字母大写
来源：http://dali.ehwqpu.com/Article/details/gt2reexkzku.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vxyplopd.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.bjfxy.top/Article/details/gt2mwwkvgft.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hnqzz.top/Article/details/gt2rwyaewwt.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.tianlin.xyz/Article/details/gt2khhsbqez.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.guowangkeji.top/Article/details/gt2tblwxvpq.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jlsjyb.cn/Article/details/gt2hexrqndm.html

Ruby: s.capitalize
来源：http://dali.wangdashe.top/Article/details/gt2jovyszra.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yanxiufei.cn/Article/details/gt2uedobyeb.html

[E18] 模板占位符替换
来源：http://dali.yuxming.cn/Article/details/gt2kjftjpzd.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.cheryme.top/Article/details/gt2dmemyrtz.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.aibaodan.cn/Article/details/gt2kajxlgtw.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.ybcxt.top/Article/details/gt2gvqmfodr.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hongshengwenyu.top/Article/details/gt2sizmjpkv.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.mhx1999.top/Article/details/gt2alylkclg.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhengqikj.top/Article/details/gt2jbgyhniy.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.ivvv.top/Article/details/gt2glhylryo.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.shuidangran.top/Article/details/gt2gfietufy.html

[E19] 多行文本按行拆分
来源：http://dali.sufxvd.cn/Article/details/gt2azzyichm.html

Py:   s.splitlines()
来源：http://dali.andypj.xyz/Article/details/gt2azeuszoe.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yangfankeji.com/Article/details/gt2apxsvurt.html

JS:   s.split(/\r?\n/)
来源：http://dali.nwbrower.top/Article/details/gt2ffdhispz.html

TS:   s.split(/\r?\n/)
来源：http://dali.zdqjudy.top/Article/details/gt2qdwlqbxz.html

Java: s.lines().toList()
来源：http://dali.ydzc1.top/Article/details/gt2fjzeiptj.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2krrxqswo.html

Ruby: s.lines
来源：http://dali.cdnleiting.top/Article/details/gt2rsngnmqz.html

C#:   s.Split('\n')
来源：http://dali.birdmap.top/Article/details/gt2nvdlrvhr.html

[E20] 判断字符串是否为空
来源：http://dali.iojbl.cn/Article/details/gt2yroqspip.html

Py:   if not s:
来源：http://dali.hammf.cn/Article/details/gt2duuycjya.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.xinyue.icu/Article/details/gt2tshfaopa.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mxwzbvyz.html

TS:   if (s === "") {}
来源：http://dali.c1oappe.top/Article/details/gt2lgzfbdfz.html

Java: if (s.isEmpty()) {}
来源：http://dali.iojbl.cn/Article/details/gt2mwgepsrk.html

Go:   if s == "" {}
来源：http://dali.daxiang520.top/Article/details/gt2qqotutof.html

Ruby: if s.empty?
来源：http://dali.hammf.cn/Article/details/gt2axpbqmpm.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2ejnnehui.html

[E21] 超长截断加省略号
来源：http://dali.yueranfly.top/Article/details/gt2xhrykqjr.html


<!-- 参考信息 -->