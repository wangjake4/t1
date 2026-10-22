代发 wailian999

[D15] 去重
来源：http://dali.pengpengdd.cyou/Article/details/gt2kefwrnmz.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yuanzhike.top/Article/details/gt2sekatkeg.html

PHP:  array_unique($arr);
来源：http://dali.zhoulong.xyz/Article/details/gt2zkqtvrmh.html

JS:   [...new Set(arr)]
来源：http://dali.snrcjt.cn/Article/details/gt2jfobiuov.html

TS:   [...new Set(arr)]
来源：http://dali.jlsjyb.cn/Article/details/gt2lkevyexh.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2whlfkcol.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.xylfe.cn/Article/details/gt2sysuctat.html

Ruby: arr.uniq
来源：http://dali.yj20258888.top/Article/details/gt2tdebuqna.html

C#:   list.Distinct().ToList()
来源：http://dali.cdnleiting.top/Article/details/gt2tyumnnax.html

[D16] 求和与平均值
来源：http://dali.yvedp.cn/Article/details/gt2ajcobcuh.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gt2dgqmaphl.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhongyouzk.top/Article/details/gt2hziduvud.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yonumen.top/Article/details/gt2pcugfici.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gzhubu.top/Article/details/gt2umvkbrwo.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.316326.xyz/Article/details/gt2webgsgmt.html

Go:   // 手写循环累加
来源：http://dali.kuanghao11.cn/Article/details/gt2iowyebii.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yangfankeji.com/Article/details/gt2yveatkcg.html

C#:   list.Sum();  list.Average()
来源：http://dali.hfpthk.cn/Article/details/gt2eenbuubl.html

[D17] 最大值与最小值
来源：http://dali.xinyue.icu/Article/details/gt2lvvwomtc.html

Py:   max(arr);  min(arr)
来源：http://dali.yongpay.top/Article/details/gt2tvaumkav.html

PHP:  max($arr);  min($arr);
来源：http://dali.c1oappe.top/Article/details/gt2bbkfoeet.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hongshengwenyu.top/Article/details/gt2zvizneov.html

TS:   Math.max(...arr);
来源：http://dali.havefunace.top/Article/details/gt2pailzgkj.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.0kj1m.cn/Article/details/gt2rewrburf.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.haohaochexian.top/Article/details/gt2vqgwvsym.html

Ruby: arr.max;  arr.min
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qxmzuogb.html

C#:   list.Max();  list.Min()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yepcxcqf.html

[D18] 扁平化嵌套数组
来源：http://dali.cqqwz.cn/Article/details/gt2djmxphms.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhengqikj.top/Article/details/gt2flciltkc.html

PHP:  array_merge(...$nested);
来源：http://dali.hywenlv.cn/Article/details/gt2vofhqqdx.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jqgufenzy.top/Article/details/gt2ejtkbkbb.html

TS:   nested.flat();
来源：http://dali.guowangkeji.top/Article/details/gt2nivgknii.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.tanke756.top/Article/details/gt2jhmswcrz.html

Go:   // 手写双层循环
来源：http://dali.hammf.cn/Article/details/gt2jubkwvte.html

Ruby: nested.flatten
来源：http://dali.redwolf501.top/Article/details/gt2ndonwruv.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.sysykeji.top/Article/details/gt2sicptmjk.html

[D19] 按字段分组
来源：http://dali.wangdashe.top/Article/details/gt2vcuggcrw.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.iojbl.cn/Article/details/gt2nfoothwz.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jianghu66.top/Article/details/gt2qcdtvleb.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.hywenlv.cn/Article/details/gt2hwwgtqbd.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.hongshengwenyu.top/Article/details/gt2uwvznfjj.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jinqigfzy.top/Article/details/gt2eaxqnxwx.html

Go:   // 手写 map[string][]T
来源：http://dali.kuanghao11.cn/Article/details/gt2faloublv.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jinqigufen.top/Article/details/gt2vgbnblcd.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.aizwys.cn/Article/details/gt2ggwvjqmm.html

[D20] 统计每个元素出现次数
来源：http://dali.aibaodan.cn/Article/details/gt2olrkfwrr.html

Py:   Counter(arr)
来源：http://dali.guowangkeji.top/Article/details/gt2vmjazbyj.html

PHP:  array_count_values($arr);
来源：http://dali.yongpay.top/Article/details/gt2aqaruuho.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pxrpcfci.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.havefunace.top/Article/details/gt2wgolnpjt.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zdqjudy.top/Article/details/gt2phncbdfu.html

Go:   // 手写 map[T]int
来源：http://dali.hysaishi.cn/Article/details/gt2jawxkhzs.html

Ruby: arr.tally
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fhtihvhq.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.cashguo.top/Article/details/gt2eenvgybj.html

[D21] 判断是否包含某元素
来源：http://dali.chenzaomai.com/Article/details/gt2dlclgjec.html

Py:   x in arr
来源：http://dali.wangdashe.top/Article/details/gt2bjidigvt.html

PHP:  in_array($x, $arr, true);
来源：http://dali.chenlongwang.top/Article/details/gt2bgcnjhwx.html

JS:   arr.includes(x)
来源：http://dali.yj20258.top/Article/details/gt2qyiapwtq.html

TS:   arr.includes(x)
来源：http://dali.cashguo.top/Article/details/gt2caanresh.html

Java: list.contains(x)
来源：http://dali.c1oappe.top/Article/details/gt2xyajbthz.html

Go:   slices.Contains(arr, x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gfiojwhx.html

Ruby: arr.include?(x)
来源：http://dali.kuanghao11.cn/Article/details/gt2nbeelqca.html

C#:   list.Contains(x)
来源：http://dali.c1oappe.top/Article/details/gt2oophjnsc.html

[D22] 复制数组（避免共享引用）
来源：http://dali.feifeiyinyue.top/Article/details/gt2wmjnrbqs.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jiagoushi.top/Article/details/gt2negwheys.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.chenlongwang.top/Article/details/gt2xpikbson.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.shuidangran.top/Article/details/gt2qjwznhzp.html

TS:   [...arr];
来源：http://dali.pengpengdd.cyou/Article/details/gt2mpfjursf.html

Java: new ArrayList<>(list);
来源：http://dali.wangshuangyany.cn/Article/details/gt2gjdlgaid.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.gotoacloud.top/Article/details/gt2idpydqak.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jqgufenzy.top/Article/details/gt2jifngvof.html

C#:   new List<int>(list);
来源：http://dali.cashguo.top/Article/details/gt2cagkvgog.html

[D23] reduce 累积计算
来源：http://dali.svipenyu.cn/Article/details/gt2adiulxgm.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.sxryk.cn/Article/details/gt2keyxtyyc.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.aibaodan.cn/Article/details/gt2fbpxkvmm.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.andypj.xyz/Article/details/gt2ubfbgiog.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.daria6918.cn/Article/details/gt2sjiejdst.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.sysykeji.top/Article/details/gt2zgtbrksa.html

Go:   // 手写循环
来源：http://dali.bjfxy.top/Article/details/gt2denbxcww.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yj20258.top/Article/details/gt2ohfgyrzg.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.svipenyu.cn/Article/details/gt2sdzpfzxv.html

[D24] 字典 / Map 基本操作
来源：http://dali.haohaochexian.top/Article/details/gt2iuvltowv.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hnqzz.top/Article/details/gt2liuxgyed.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jinqigufen.top/Article/details/gt2ngcqzmpi.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hnxiangtu.top/Article/details/gt2otjxuube.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yuxming.cn/Article/details/gt2gfjceyci.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.wangdashe.top/Article/details/gt2szdjnscc.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xqijryzs.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pzaxkayi.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhoulong.xyz/Article/details/gt2zigodfyj.html

[D25] Set 集合去重与交并差
来源：http://dali.hnqzz.top/Article/details/gt2iintisds.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2crzophpd.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.bjfxy.top/Article/details/gt2cdsmyrzl.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yongpay.top/Article/details/gt2aomfefbm.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yj20258888.top/Article/details/gt2valrlgdu.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.dashuyun.cn/Article/details/gt2bltihsgw.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.mhx1999.top/Article/details/gt2fgawjfhb.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hysaishi.cn/Article/details/gt2gnhfstii.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhongyouzk.top/Article/details/gt2jxvqybfq.html

[D26] 数组转字符串
来源：http://dali.hnxiangtu.top/Article/details/gt2gmvlmxoa.html

Py:   ", ".join(map(str, arr))
来源：http://dali.svipenyu.cn/Article/details/gt2rnrexngx.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fldmrfgq.html

JS:   arr.join(", ")
来源：http://dali.aibaodan.cn/Article/details/gt2xvjdsqrd.html

TS:   arr.join(", ")
来源：http://dali.hammf.cn/Article/details/gt2uoualirq.html

Java: String.join(", ", list)
来源：http://dali.nanxuanxn.top/Article/details/gt2yxrpnsru.html

Go:   strings.Join(strs, ", ")
来源：http://dali.haohaochexian.top/Article/details/gt2obceuhsx.html

Ruby: arr.join(", ")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tebgoeuo.html

C#:   string.Join(", ", list)
来源：http://dali.tianlin.xyz/Article/details/gt2yvovumfq.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2cajtkhwc.html

E. 字符串处理
来源：http://dali.shangyingyoupin.top/Article/details/gt2fjcdeqzj.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2hlmngivw.html

[E01] 拼接字符串
来源：http://dali.andypj.xyz/Article/details/gt2ozizcbbp.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.smart0.xyz/Article/details/gt2rxgsqdme.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yj20258.top/Article/details/gt2rtwozzkq.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yj20258888.top/Article/details/gt2orsrqrhz.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.chenlongwang.top/Article/details/gt2yincnuch.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.wangshuangyany.cn/Article/details/gt2srhtnujn.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.cashguo.top/Article/details/gt2irimdotc.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.fengsongda.top/Article/details/gt2ocxfgske.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.daxiang520.top/Article/details/gt2aisupfwm.html

[E02] 重复字符串
来源：http://dali.yongpay.top/Article/details/gt2hcmnbdmi.html

Py:   "ab" * 3
来源：http://dali.smart0.xyz/Article/details/gt2bxyqbgwu.html

PHP:  str_repeat("ab", 3);
来源：http://dali.fengsongda.top/Article/details/gt2xpofwoac.html

JS:   "ab".repeat(3)
来源：http://dali.jqgfzy.top/Article/details/gt2ucbxtqku.html

TS:   "ab".repeat(3)
来源：http://dali.bjfxy.top/Article/details/gt2tmlxjsug.html

Java: "ab".repeat(3)
来源：http://dali.jinqigufen.top/Article/details/gt2trhmzpbo.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.iojbl.cn/Article/details/gt2twlujtzz.html

Ruby: "ab" * 3
来源：http://dali.iojbl.cn/Article/details/gt2hgjhajvg.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.0kj1m.cn/Article/details/gt2cncjdaid.html

[E03] 截取子串
来源：http://dali.zhoulong.xyz/Article/details/gt2vkuiqmoi.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.redwolf501.top/Article/details/gt2cruwkzuj.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xuetiantiany.cn/Article/details/gt2rcidnahj.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.ivvv.top/Article/details/gt2jskoynzw.html

TS:   s.slice(1, 4)
来源：http://dali.hnqzz.top/Article/details/gt2xjqtnxae.html

Java: s.substring(1, 4)
来源：http://dali.ppjwa.cn/Article/details/gt2fshecgdj.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.chenzaomai.com/Article/details/gt2ndjwmwuu.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.sweek.top/Article/details/gt2sympvgbn.html

C#:   s.Substring(1, 3)
来源：http://dali.xylfe.cn/Article/details/gt2ewejkmqg.html

[E04] 查找子串位置
来源：http://dali.cucudq.cn/Article/details/gt2jgnaslwg.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zdqjudy.top/Article/details/gt2msrkirpa.html

PHP:  strpos($s, "x");
来源：http://dali.yj20258.top/Article/details/gt2jjyacpii.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.pengpengdd.cyou/Article/details/gt2vbeyzcdf.html

TS:   s.indexOf("x")
来源：http://dali.hywenlv.cn/Article/details/gt2hngfiwmu.html

Java: s.indexOf("x")
来源：http://dali.ivvv.top/Article/details/gt2cbwytywx.html

Go:   strings.Index(s, "x")
来源：http://dali.yanxiufei.cn/Article/details/gt2oynysksv.html

Ruby: s.index("x")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ucjhbcuy.html

C#:   s.IndexOf("x")
来源：http://dali.yuanzhike.top/Article/details/gt2jsvgfsyd.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.fengsongda.top/Article/details/gt2mhlqaqop.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.hysaishi.cn/Article/details/gt2ervutyab.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.ivvv.top/Article/details/gt2zcdywvai.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hywenlv.cn/Article/details/gt2tcszdcrz.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wrdgvjnd.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinqigufen.top/Article/details/gt2qudcpucp.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hnxiangtu.top/Article/details/gt2edupmnsq.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.svipenyu.cn/Article/details/gt2fkteapux.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.shuidangran.top/Article/details/gt2nhjficbs.html

[E06] 替换子串
来源：http://dali.yonumen.top/Article/details/gt2szrzlyro.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.tian-w.cn/Article/details/gt2tbkbzlun.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.daxiang520.top/Article/details/gt2wzucejco.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jianghu66.top/Article/details/gt2rvgoywqs.html

TS:   s.replaceAll("a", "b")
来源：http://dali.hongshengwenyu.top/Article/details/gt2cxzhhsgf.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zycfv.cn/Article/details/gt2jefogyxq.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2xohtutey.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.iojbl.cn/Article/details/gt2mvklhjml.html

C#:   s.Replace("a", "b")
来源：http://dali.shzxlz.cn/Article/details/gt2lwefdjnj.html

[E07] 按分隔符拆分
来源：http://dali.ydzc1.top/Article/details/gt2cvgtuqvv.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yj202588.top/Article/details/gt2irbnrvzd.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.cqqwz.cn/Article/details/gt2kjtnhmmc.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fmfrsdji.html

TS:   s.split(",")
来源：http://dali.gogol.net.cn/Article/details/gt2hpqravkf.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.havefunace.top/Article/details/gt2jnagjiqk.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.birdmap.top/Article/details/gt2ffptmcde.html

Ruby: s.split(",");  s.split
来源：http://dali.nanxuanxn.top/Article/details/gt2gcawhose.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.birdmap.top/Article/details/gt2yxzftsgg.html

[E08] 数组按分隔符合并
来源：http://dali.ydzc1.top/Article/details/gt2hnomkcst.html

Py:   ",".join(items)
来源：http://dali.dianchejie.cn/Article/details/gt2qzlkapjk.html

PHP:  implode(",", $items);
来源：http://dali.pengpengdd.cyou/Article/details/gt2ixzqqijf.html

JS:   items.join(",")
来源：http://dali.jqgfzy.top/Article/details/gt2dlyanmvv.html

TS:   items.join(",")
来源：http://dali.nwbrower.top/Article/details/gt2cvieyhqa.html

Java: String.join(",", items)
来源：http://dali.fzhhl.top/Article/details/gt2zvyastdx.html

Go:   strings.Join(items, ",")
来源：http://dali.birdmap.top/Article/details/gt2hadeqpnu.html

Ruby: items.join(",")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tcdpuhse.html

C#:   string.Join(",", items)
来源：http://dali.mhx1999.top/Article/details/gt2osprlmbx.html

[E09] 去除所有空白字符
来源：http://dali.xziqi.cn/Article/details/gt2bqujlhxr.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.gaohongyu789.top/Article/details/gt2gdgfvnhd.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jlsjyb.cn/Article/details/gt2klzoyrzc.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zycfv.cn/Article/details/gt2idvukafe.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.tanke756.top/Article/details/gt2fqwhdoot.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.xziqi.cn/Article/details/gt2shmjlytj.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.sweek.top/Article/details/gt2cxcwwiwb.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hysaishi.cn/Article/details/gt2wckerxit.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.ybcxt.top/Article/details/gt2fjydknvz.html

[E10] 左侧补零 / 定长填充
来源：http://dali.svipenyu.cn/Article/details/gt2egwcgwdx.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.0kj1m.cn/Article/details/gt2pmxivplj.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.wangdashe.top/Article/details/gt2utkhpoiq.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ktgqoigc.html

TS:   "7".padStart(3, "0")
来源：http://dali.hywenlv.cn/Article/details/gt2mzlbnjbi.html

Java: String.format("%03d", 7)
来源：http://dali.ehwqpu.com/Article/details/gt2cwrtyurk.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.feifeiyinyue.top/Article/details/gt2doadvftb.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.xziqi.cn/Article/details/gt2ngkrknpn.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.nanxinkj.top/Article/details/gt2cylgbgdr.html

[E11] 反转字符串
来源：http://dali.xylfe.cn/Article/details/gt2mecnadsv.html

Py:   s[::-1]
来源：http://dali.sysykeji.top/Article/details/gt2vwdyqdtm.html

PHP:  strrev($s);
来源：http://dali.dashuyun.cn/Article/details/gt2jbcstecm.html

JS:   [...s].reverse().join("")
来源：http://dali.shuidangran.top/Article/details/gt2zelodzcu.html

TS:   [...s].reverse().join("")
来源：http://dali.ybcxt.top/Article/details/gt2sbkqufnq.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhoulong.xyz/Article/details/gt2mzemirrn.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zhqenvte.html

Ruby: s.reverse
来源：http://dali.dianchejie.cn/Article/details/gt2apdoucyb.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vsshvcgf.html

[E12] 统计某字符出现次数
来源：http://dali.ydzc1.top/Article/details/gt2wkvyzsqy.html

Py:   s.count("a")
来源：http://dali.tanke756.top/Article/details/gt2betpsjqf.html

PHP:  substr_count($s, "a");
来源：http://dali.zhengqikj.top/Article/details/gt2lupczdol.html

JS:   s.split("a").length - 1
来源：http://dali.jinqigfzy.top/Article/details/gt2fvwbslgp.html

TS:   s.split("a").length - 1
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gbxyspqk.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yj20258888.top/Article/details/gt2rruaktve.html

Go:   strings.Count(s, "a")
来源：http://dali.guowangkeji.top/Article/details/gt2xwkqdkoh.html

Ruby: s.count("a")
来源：http://dali.zhiwuduotai.top/Article/details/gt2zsbqakst.html

C#:   s.Count(c => c == 'a')
来源：http://dali.pycfn.com/Article/details/gt2dbmsgpzf.html

[E13] 逐字符遍历
来源：http://dali.havefunace.top/Article/details/gt2imnvfhog.html

Py:   for ch in s: print(ch)
来源：http://dali.hfpthk.cn/Article/details/gt2lsafrith.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.snrcjt.cn/Article/details/gt2ukmftdeo.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwpspjya.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sufxvd.cn/Article/details/gt2fdvzzict.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.ydzc1.top/Article/details/gt2zvazurux.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.sweek.top/Article/details/gt2bbnnafhz.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.xuetiantiany.cn/Article/details/gt2vatgnpgi.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.c1oappe.top/Article/details/gt2pekkkexm.html

[E14] URL 编码与 Base64
来源：http://dali.nanxinkj.top/Article/details/gt2bwmfufkd.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.316326.xyz/Article/details/gt2qgepaozt.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.pycfn.com/Article/details/gt2ftwpridk.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.gogol.net.cn/Article/details/gt2pcfqnsvw.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.daxiang520.top/Article/details/gt2xnshwbby.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.cheryme.top/Article/details/gt2nfmlobex.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.shzxlz.cn/Article/details/gt2lekmfxuo.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.cqqwz.cn/Article/details/gt2avnyouzr.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.xuetiantiany.cn/Article/details/gt2plaavvkl.html

[E15] HTML 转义 / 反转义
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qnbzvnmb.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.sxryk.cn/Article/details/gt2aaaaplbb.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mhlieawa.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.xziqi.cn/Article/details/gt2dnknrhvq.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zycfv.cn/Article/details/gt2lluzybup.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.chenlongwang.top/Article/details/gt2bywzvzkf.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yj20258.top/Article/details/gt2tpnwilbg.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.nwbrower.top/Article/details/gt2qxebfbef.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.shzxlz.cn/Article/details/gt2wxvykoud.html

[E16] 数字千分位
来源：http://dali.nanxuanxn.top/Article/details/gt2qjuighnw.html

Py:   f"{1234567:,}"
来源：http://dali.snrcjt.cn/Article/details/gt2oqqmqjpv.html

PHP:  number_format(1234567);
来源：http://dali.zhoulong.xyz/Article/details/gt2uyasascj.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yypaoxnt.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mktizsiu.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hjqogmuz.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hongshengwenyu.top/Article/details/gt2kgwgvnwc.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yanxiufei.cn/Article/details/gt2chcmrlnb.html

C#:   1234567.ToString("N0")
来源：http://dali.gotoacloud.top/Article/details/gt2gxyqgflp.html

[E17] 首字母大写
来源：http://dali.zhengqikj.top/Article/details/gt2eywlreoo.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.vqdsnc.cn/Article/details/gt2evxalzrx.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jqgufenzy.top/Article/details/gt2axhbuvxs.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2amomkefg.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.guannengcc.top/Article/details/gt2uxkumwhf.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.svipenyu.cn/Article/details/gt2grwgueop.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.sweek.top/Article/details/gt2dffjiqnc.html

Ruby: s.capitalize
来源：http://dali.0kj1m.cn/Article/details/gt2rfftukee.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.sweek.top/Article/details/gt2fvhcggts.html

[E18] 模板占位符替换
来源：http://dali.sweek.top/Article/details/gt2tnyscvyv.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.xinyue.icu/Article/details/gt2qknvqqoz.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.fengsongda.top/Article/details/gt2zxuzkffj.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tklhgzqu.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.tianlin.xyz/Article/details/gt2coyfpzoi.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.quarkkingdee.top/Article/details/gt2bumwtmii.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.gaohongyu789.top/Article/details/gt2ilkpqefk.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.hongshengwenyu.top/Article/details/gt2vgabjfdq.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.meibo888.top/Article/details/gt2fzepxmws.html

[E19] 多行文本按行拆分
来源：http://dali.yj202588.top/Article/details/gt2popfuhsg.html

Py:   s.splitlines()
来源：http://dali.aibaodan.cn/Article/details/gt2othkjghg.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.svipenyu.cn/Article/details/gt2dvsqmrvt.html

JS:   s.split(/\r?\n/)
来源：http://dali.hongshengwenyu.top/Article/details/gt2pkrsdyla.html

TS:   s.split(/\r?\n/)
来源：http://dali.mhx1999.top/Article/details/gt2vvntqdzh.html

Java: s.lines().toList()
来源：http://dali.9152youxi.cn/Article/details/gt2wjbreyeq.html

Go:   strings.Split(s, "\n")
来源：http://dali.xylfe.cn/Article/details/gt2ioqaypbr.html

Ruby: s.lines
来源：http://dali.ppjwa.cn/Article/details/gt2ahsqahnv.html

C#:   s.Split('\n')
来源：http://dali.gotoacloud.top/Article/details/gt2exoyryrb.html

[E20] 判断字符串是否为空
来源：http://dali.aizwys.cn/Article/details/gt2wpehgblu.html

Py:   if not s:
来源：http://dali.jqgufenzy.top/Article/details/gt2vmnkgkse.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jlsjyb.cn/Article/details/gt2rrquhhcb.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yuanzhike.top/Article/details/gt2lpvnclwu.html

TS:   if (s === "") {}
来源：http://dali.vqdsnc.cn/Article/details/gt2mixfojob.html

Java: if (s.isEmpty()) {}
来源：http://dali.guannengcc.top/Article/details/gt2qlmjmkqk.html

Go:   if s == "" {}
来源：http://dali.guannengcc.top/Article/details/gt2oribyphz.html

Ruby: if s.empty?
来源：http://dali.yj202588.top/Article/details/gt2azmstbhk.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.gotoacloud.top/Article/details/gt2hfjifryy.html

[E21] 超长截断加省略号
来源：http://dali.zhiwuduotai.top/Article/details/gt2fibyusfg.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.nanxuanxn.top/Article/details/gt2etbcpnmj.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yuxming.cn/Article/details/gt2szrzowex.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sysykeji.top/Article/details/gt2gheinglc.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jyoumei.cn/Article/details/gt2rgemldpj.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.9152youxi.cn/Article/details/gt2jbflebak.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hywenlv.cn/Article/details/gt2vemkhlyj.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.birdmap.top/Article/details/gt2ckrrlzme.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhixingplan.top/Article/details/gt2dejyenxg.html


<!-- 参考信息 -->