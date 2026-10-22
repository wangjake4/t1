代发 wailian999

Ruby: arr.index(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdkerypzd.html

C#:   list.IndexOf(x);
来源：http://dali.tian-w.cn/Article/details/gtdmaarizd.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jyoumei.cn/Article/details/gtrwpezaxb.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.guowangkeji.top/Article/details/gtthyxtphp.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yuanzhike.top/Article/details/gtabnnhlko.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zycfv.cn/Article/details/gtctpdbvay.html

TS:   arr.filter(x => x > 3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwijtazli.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.cucudq.cn/Article/details/gtusepxagw.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.0kj1m.cn/Article/details/gtsoshydur.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.guannengcc.top/Article/details/gtqlfqssul.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqdqojpge.html

[D14] 映射转换（每个元素变形）
来源：http://dali.havefunace.top/Article/details/gtjqpynrnf.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.meibo888.top/Article/details/gtafmuayzf.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.guannengcc.top/Article/details/gthnqvyfnf.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhiwuduotai.top/Article/details/gtzvasvfot.html

TS:   arr.map(x => x * 2)
来源：http://dali.iojbl.cn/Article/details/gtvkphwtil.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.dashuyun.cn/Article/details/gtexqdhrjx.html

Go:   // 手写循环
来源：http://dali.quarkkingdee.top/Article/details/gtykvwlgpi.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfqkaytsz.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yonumen.top/Article/details/gtndbyplbk.html

[D15] 去重
来源：http://dali.ybcxt.top/Article/details/gtftvyobji.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.sweek.top/Article/details/gtnvuendww.html

PHP:  array_unique($arr);
来源：http://dali.pycfn.com/Article/details/gtfbzqruan.html

JS:   [...new Set(arr)]
来源：http://dali.cdnleiting.top/Article/details/gtbavcscaw.html

TS:   [...new Set(arr)]
来源：http://dali.shuidangran.top/Article/details/gtmedscpcz.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.nanxuanxn.top/Article/details/gtcroifjjv.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jqgufenzy.top/Article/details/gtglkgnwwp.html

Ruby: arr.uniq
来源：http://dali.yanxiufei.cn/Article/details/gtgjgmwpla.html

C#:   list.Distinct().ToList()
来源：http://dali.0kj1m.cn/Article/details/gtdrszedpt.html

[D16] 求和与平均值
来源：http://dali.kuanghao11.cn/Article/details/gtuxyjsfkj.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtqirpbbce.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jiagoushi.top/Article/details/gtrlhcmvle.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.316326.xyz/Article/details/gtvydekwrq.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ivvv.top/Article/details/gtdxnjmism.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.pengpengdd.cyou/Article/details/gtbrfbmxcf.html

Go:   // 手写循环累加
来源：http://dali.gaohongyu789.top/Article/details/gtzfykzohh.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.nanxuanxn.top/Article/details/gtumcpfqfq.html

C#:   list.Sum();  list.Average()
来源：http://dali.yangfankeji.com/Article/details/gtgzlwijfr.html

[D17] 最大值与最小值
来源：http://dali.svipenyu.cn/Article/details/gtpebgphuc.html

Py:   max(arr);  min(arr)
来源：http://dali.andypj.xyz/Article/details/gtuunvimbr.html

PHP:  max($arr);  min($arr);
来源：http://dali.ehwqpu.com/Article/details/gtaxofmdkh.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.sweek.top/Article/details/gtjekaexng.html

TS:   Math.max(...arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtpzjazjnc.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.shzxlz.cn/Article/details/gtpgltwyst.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gtrkmszpkm.html

Ruby: arr.max;  arr.min
来源：http://dali.smart0.xyz/Article/details/gtyfjfxrya.html

C#:   list.Max();  list.Min()
来源：http://dali.yj20258888.top/Article/details/gtqiocszrb.html

[D18] 扁平化嵌套数组
来源：http://dali.9152youxi.cn/Article/details/gtlagzpsja.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.0kj1m.cn/Article/details/gtnkkxmkxg.html

PHP:  array_merge(...$nested);
来源：http://dali.meibo888.top/Article/details/gtijgobxmx.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.nanxinkj.top/Article/details/gtflqsyicv.html

TS:   nested.flat();
来源：http://dali.kuanghao11.cn/Article/details/gtegldrotl.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.svipenyu.cn/Article/details/gtogdntiln.html

Go:   // 手写双层循环
来源：http://dali.pycfn.com/Article/details/gtkdkdlbjv.html

Ruby: nested.flatten
来源：http://dali.pycfn.com/Article/details/gtihibkrbk.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.sufxvd.cn/Article/details/gtybcfitpu.html

[D19] 按字段分组
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmlnhluet.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.tianlin.xyz/Article/details/gtqhavtldu.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hnxiangtu.top/Article/details/gtlakklptn.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.guannengcc.top/Article/details/gtexkrttcl.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.haohaochexian.top/Article/details/gtujmzraia.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jyoumei.cn/Article/details/gtlfhjrifg.html

Go:   // 手写 map[string][]T
来源：http://dali.havefunace.top/Article/details/gtskuutdav.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhoulong.xyz/Article/details/gtewuemtrv.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.gotoacloud.top/Article/details/gtmngroyev.html

[D20] 统计每个元素出现次数
来源：http://dali.jqgfzy.top/Article/details/gtdkcglivu.html

Py:   Counter(arr)
来源：http://dali.hysaishi.cn/Article/details/gtjbycbupz.html

PHP:  array_count_values($arr);
来源：http://dali.svipenyu.cn/Article/details/gtggwirgti.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hnxiangtu.top/Article/details/gthooywboq.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ppjwa.cn/Article/details/gtjldixvfv.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.snrcjt.cn/Article/details/gtsgysebhm.html

Go:   // 手写 map[T]int
来源：http://dali.zycfv.cn/Article/details/gtdxdyeqsb.html

Ruby: arr.tally
来源：http://dali.yj20258.top/Article/details/gtajlxsyik.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.pengpengdd.cyou/Article/details/gtcecwjubi.html

[D21] 判断是否包含某元素
来源：http://dali.guannengcc.top/Article/details/gtmdcishcq.html

Py:   x in arr
来源：http://dali.pengpengdd.cyou/Article/details/gtftoqhigp.html

PHP:  in_array($x, $arr, true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzmbzxtdb.html

JS:   arr.includes(x)
来源：http://dali.svipenyu.cn/Article/details/gtacwpruzx.html

TS:   arr.includes(x)
来源：http://dali.zycfv.cn/Article/details/gtuvutbyfc.html

Java: list.contains(x)
来源：http://dali.xziqi.cn/Article/details/gtuzrdclna.html

Go:   slices.Contains(arr, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtseyjirfy.html

Ruby: arr.include?(x)
来源：http://dali.yonumen.top/Article/details/gttjlucvqk.html

C#:   list.Contains(x)
来源：http://dali.havefunace.top/Article/details/gtypvfarag.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jinghuilouyu.cn/Article/details/gthotbwyzy.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.cqqwz.cn/Article/details/gtovfwirvu.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.ybcxt.top/Article/details/gtuutcqrlo.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtcmuwkylc.html

TS:   [...arr];
来源：http://dali.hfpthk.cn/Article/details/gtcwrmpftw.html

Java: new ArrayList<>(list);
来源：http://dali.sweek.top/Article/details/gtgemwrvyd.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.xinyue.icu/Article/details/gtcokbwnkf.html

Ruby: arr.dup;  arr.clone
来源：http://dali.mhx1999.top/Article/details/gttuoozwjg.html

C#:   new List<int>(list);
来源：http://dali.jianghu66.top/Article/details/gtqadsqsih.html

[D23] reduce 累积计算
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbfrdxcgu.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.cheryme.top/Article/details/gthkqhrhpe.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.316326.xyz/Article/details/gtjyyagsls.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hysaishi.cn/Article/details/gtbkdiewev.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zycfv.cn/Article/details/gtotwnwrvr.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jqgfzy.top/Article/details/gtijamtrin.html

Go:   // 手写循环
来源：http://dali.mhx1999.top/Article/details/gtgnannlop.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.sysykeji.top/Article/details/gtzphwrvsl.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.ppjwa.cn/Article/details/gtqmxynbuc.html

[D24] 字典 / Map 基本操作
来源：http://dali.jianghu66.top/Article/details/gtygaqckju.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gtmvfayzqy.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.hongshengwenyu.top/Article/details/gtmknmzzar.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.gaohongyu789.top/Article/details/gtwgrirbrd.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.quarkkingdee.top/Article/details/gtnxxcmbkg.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhongyouzk.top/Article/details/gtxiwlarib.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yj20258.top/Article/details/gtescpinmx.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zdqjudy.top/Article/details/gtrqvwevjy.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.cheryme.top/Article/details/gtvrvfdlac.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gtnutgqukl.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yj20258.top/Article/details/gtedrskcfg.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhiwuduotai.top/Article/details/gtoayakykp.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.mhx1999.top/Article/details/gtdktbfdbe.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zycfv.cn/Article/details/gtjzqdyfil.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.hywenlv.cn/Article/details/gtrksfmzyx.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yj20258888.top/Article/details/gtbplidjao.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtduvlojya.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.tian-w.cn/Article/details/gtfuwsqohm.html

[D26] 数组转字符串
来源：http://dali.iojbl.cn/Article/details/gttpmcrcqy.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jinqigufen.top/Article/details/gtxbiqwsvo.html

PHP:  implode(", ", $arr);
来源：http://dali.xinyue.icu/Article/details/gtinuoohck.html

JS:   arr.join(", ")
来源：http://dali.kuanghao11.cn/Article/details/gtlobobgvo.html

TS:   arr.join(", ")
来源：http://dali.316326.xyz/Article/details/gtpxhazwgt.html

Java: String.join(", ", list)
来源：http://dali.feifeiyinyue.top/Article/details/gtmipbqzid.html

Go:   strings.Join(strs, ", ")
来源：http://dali.hongshengwenyu.top/Article/details/gtdzzksxwt.html

Ruby: arr.join(", ")
来源：http://dali.snrcjt.cn/Article/details/gtgpnyudlf.html

C#:   string.Join(", ", list)
来源：http://dali.jyoumei.cn/Article/details/gtojgdncte.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gttsbveqrj.html

E. 字符串处理
来源：http://dali.cheryme.top/Article/details/gtrwlrplgi.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdinojmzt.html

[E01] 拼接字符串
来源：http://dali.sysykeji.top/Article/details/gtwiijhchy.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.shzxlz.cn/Article/details/gtjvxxhhbc.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtakszazfi.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hysaishi.cn/Article/details/gtiyfrjhcw.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.guannengcc.top/Article/details/gtleeprcfu.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.316326.xyz/Article/details/gtxujmsnhr.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.sxryk.cn/Article/details/gtebkwpnss.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.ivvv.top/Article/details/gtdjejvjmx.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.sweek.top/Article/details/gthpubxhau.html

[E02] 重复字符串
来源：http://dali.xuanzx.com/Article/details/gtwychrgxp.html

Py:   "ab" * 3
来源：http://dali.nwbrower.top/Article/details/gtfmnpiujd.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hywenlv.cn/Article/details/gtllvkcmge.html

JS:   "ab".repeat(3)
来源：http://dali.hysaishi.cn/Article/details/gtnfmmlwis.html

TS:   "ab".repeat(3)
来源：http://dali.dashuyun.cn/Article/details/gtswknoaqb.html

Java: "ab".repeat(3)
来源：http://dali.tian-w.cn/Article/details/gttoigskqv.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.9152youxi.cn/Article/details/gtwemmxawu.html

Ruby: "ab" * 3
来源：http://dali.zdqjudy.top/Article/details/gthfbkgwhd.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.meibo888.top/Article/details/gtgioadhrj.html

[E03] 截取子串
来源：http://dali.hnxiangtu.top/Article/details/gtbeewqsvs.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.shuidangran.top/Article/details/gtkdartuey.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jqgufenzy.top/Article/details/gteikfvjvn.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.hysaishi.cn/Article/details/gtetqvkzks.html

TS:   s.slice(1, 4)
来源：http://dali.shanyushiyangtech.top/Article/details/gtojgdbtkc.html

Java: s.substring(1, 4)
来源：http://dali.wangshuangyany.cn/Article/details/gtnrkniguh.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.cdnleiting.top/Article/details/gtlasyxfkp.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.9152youxi.cn/Article/details/gtilcmiepw.html

C#:   s.Substring(1, 3)
来源：http://dali.cashguo.top/Article/details/gtoriebxvg.html

[E04] 查找子串位置
来源：http://dali.tanke756.top/Article/details/gtmoysygta.html

Py:   s.find("x");  s.index("x")
来源：http://dali.cheryme.top/Article/details/gtrycmbady.html

PHP:  strpos($s, "x");
来源：http://dali.ybcxt.top/Article/details/gtqnyrdwla.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yvedp.cn/Article/details/gtwmvlwimm.html

TS:   s.indexOf("x")
来源：http://dali.zhiwuduotai.top/Article/details/gtsacizizl.html

Java: s.indexOf("x")
来源：http://dali.nanxinkj.top/Article/details/gtabodpvwy.html

Go:   strings.Index(s, "x")
来源：http://dali.haohaochexian.top/Article/details/gtylrvorlk.html

Ruby: s.index("x")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvvwcqprb.html

C#:   s.IndexOf("x")
来源：http://dali.jlsjyb.cn/Article/details/gtlvsnutji.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jinghuilouyu.cn/Article/details/gtbbhpcgfv.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.hywenlv.cn/Article/details/gtvwipnony.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.meibo888.top/Article/details/gtcgspwozw.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sufxvd.cn/Article/details/gtranperqm.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.0kj1m.cn/Article/details/gtwxehgrmo.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.fengsongda.top/Article/details/gtsytiezyz.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.aibaodan.cn/Article/details/gtjvoeghto.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.hammf.cn/Article/details/gteaovxenh.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zycfv.cn/Article/details/gtxfasbmce.html

[E06] 替换子串
来源：http://dali.fengsongda.top/Article/details/gtnzhutebk.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.wangdashe.top/Article/details/gtcbpokyyd.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.mhx1999.top/Article/details/gtvblukzdt.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hfpthk.cn/Article/details/gttmvvbkiz.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yuxming.cn/Article/details/gthzxmogjc.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.chenlongwang.top/Article/details/gtdqwuherr.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yongpay.top/Article/details/gtiizkuoyk.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.chenjidiqi.icu/Article/details/gtdcmgqcop.html

C#:   s.Replace("a", "b")
来源：http://dali.jqgfzy.top/Article/details/gtljeeusmp.html

[E07] 按分隔符拆分
来源：http://dali.pycfn.com/Article/details/gtjmzrnhpx.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.pengpengdd.cyou/Article/details/gtfurporyh.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.c1oappe.top/Article/details/gttqllzvtt.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.xziqi.cn/Article/details/gtpahsceho.html

TS:   s.split(",")
来源：http://dali.guowangkeji.top/Article/details/gtmkhirthm.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.shangyingyoupin.top/Article/details/gtfsqvnyav.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.gogol.net.cn/Article/details/gtvcdzpscl.html

Ruby: s.split(",");  s.split
来源：http://dali.shuidangran.top/Article/details/gtlvrctaka.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.xylfe.cn/Article/details/gtbgcfzrzw.html

[E08] 数组按分隔符合并
来源：http://dali.cucudq.cn/Article/details/gtuadquryy.html

Py:   ",".join(items)
来源：http://dali.nwbrower.top/Article/details/gtkncmixfx.html

PHP:  implode(",", $items);
来源：http://dali.pycfn.com/Article/details/gtpuvvivhj.html

JS:   items.join(",")
来源：http://dali.xuanzx.com/Article/details/gtwpqxdfgd.html

TS:   items.join(",")
来源：http://dali.redwolf501.top/Article/details/gtxdfmwqbu.html

Java: String.join(",", items)
来源：http://dali.chenjidiqi.icu/Article/details/gtubofzefz.html

Go:   strings.Join(items, ",")
来源：http://dali.zhiwuduotai.top/Article/details/gthffupepg.html

Ruby: items.join(",")
来源：http://dali.jqgufenzy.top/Article/details/gtpcpsvolb.html

C#:   string.Join(",", items)
来源：http://dali.yanxiufei.cn/Article/details/gtpmiypjmi.html

[E09] 去除所有空白字符
来源：http://dali.sysykeji.top/Article/details/gtpfcccuun.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.pengpengdd.cyou/Article/details/gtqwwpodgv.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zycfv.cn/Article/details/gtivnyconb.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.shuidangran.top/Article/details/gtvakhttmn.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yj20258888.top/Article/details/gtgwzbnemz.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.c1oappe.top/Article/details/gtihssylvu.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yj20258888.top/Article/details/gtphymhbvb.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hywenlv.cn/Article/details/gtjqnpondr.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.bjfxy.top/Article/details/gtiinbccel.html

[E10] 左侧补零 / 定长填充
来源：http://dali.chenlongwang.top/Article/details/gtqpwyrxsj.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.sxryk.cn/Article/details/gthwaiewpq.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.tanke756.top/Article/details/gtpzaekvhw.html

JS:   "7".padStart(3, "0")
来源：http://dali.yongpay.top/Article/details/gtgtzpalze.html

TS:   "7".padStart(3, "0")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjbampxdu.html

Java: String.format("%03d", 7)
来源：http://dali.guannengcc.top/Article/details/gtfabrbssi.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.316326.xyz/Article/details/gtkdmflluu.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.xziqi.cn/Article/details/gtoyfdkvge.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jinqigufen.top/Article/details/gthdisogea.html

[E11] 反转字符串
来源：http://dali.0kj1m.cn/Article/details/gtfggqbaux.html

Py:   s[::-1]
来源：http://dali.jqgfzy.top/Article/details/gtojdvmwqb.html

PHP:  strrev($s);
来源：http://dali.sufxvd.cn/Article/details/gtmythgwqq.html

JS:   [...s].reverse().join("")
来源：http://dali.zhiwuduotai.top/Article/details/gtstlmsyar.html

TS:   [...s].reverse().join("")
来源：http://dali.andypj.xyz/Article/details/gtkzjysdbw.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.chenlongwang.top/Article/details/gtgbawswrx.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.tanke756.top/Article/details/gtpjbpmzme.html

Ruby: s.reverse
来源：http://dali.dashuyun.cn/Article/details/gtjfvitrcq.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.redwolf501.top/Article/details/gtlokjyrwg.html

[E12] 统计某字符出现次数
来源：http://dali.cucudq.cn/Article/details/gtlkleuijy.html

Py:   s.count("a")
来源：http://dali.tian-w.cn/Article/details/gtmwaegwyj.html

PHP:  substr_count($s, "a");
来源：http://dali.nanxuanxn.top/Article/details/gtivgfzdjc.html

JS:   s.split("a").length - 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtirujkkxi.html

TS:   s.split("a").length - 1
来源：http://dali.shanyushiyangtech.top/Article/details/gtamixseyv.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.ivvv.top/Article/details/gtlzudqzki.html

Go:   strings.Count(s, "a")
来源：http://dali.hammf.cn/Article/details/gtsxrdvujw.html

Ruby: s.count("a")
来源：http://dali.0kj1m.cn/Article/details/gtqnfyaoni.html

C#:   s.Count(c => c == 'a')
来源：http://dali.havefunace.top/Article/details/gtnhdkfzfk.html

[E13] 逐字符遍历
来源：http://dali.yangfankeji.com/Article/details/gtqptaladx.html

Py:   for ch in s: print(ch)
来源：http://dali.yueranfly.top/Article/details/gteehqpvni.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yj20258888.top/Article/details/gtzulkpswb.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xinyue.icu/Article/details/gtovdtooxs.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhoulong.xyz/Article/details/gtgprwaxdv.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.tian-w.cn/Article/details/gtwpcikbth.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zdqjudy.top/Article/details/gtlvmrmomb.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjtokbhyp.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zycfv.cn/Article/details/gtpglleshn.html

[E14] URL 编码与 Base64
来源：http://dali.chenzaomai.com/Article/details/gtsukmopsi.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.shuidangran.top/Article/details/gtwsbijzjk.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jyoumei.cn/Article/details/gtktqiyfjb.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.fzhhl.top/Article/details/gtktrsczfd.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.sxryk.cn/Article/details/gtmscsmqsq.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.ydzc1.top/Article/details/gtovlallgv.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.tanke756.top/Article/details/gtaklenmug.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhengqikj.top/Article/details/gtagtuolry.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwcafszat.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhijiandao.cn/Article/details/gthborubvh.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhongyouzk.top/Article/details/gtfmcrepgs.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.cheryme.top/Article/details/gtbyuayyzn.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yonumen.top/Article/details/gtxzhnqwej.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yonumen.top/Article/details/gtcafkcegz.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yanxiufei.cn/Article/details/gtudsiclrk.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hnqzz.top/Article/details/gtrlvzzmwv.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.c1oappe.top/Article/details/gtsivtjmbl.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hfpthk.cn/Article/details/gtooasppik.html

[E16] 数字千分位
来源：http://dali.gotoacloud.top/Article/details/gtwoyrntcd.html

Py:   f"{1234567:,}"
来源：http://dali.yongpay.top/Article/details/gtoboknkes.html

PHP:  number_format(1234567);
来源：http://dali.xziqi.cn/Article/details/gtmvmfcaiz.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.daxiang520.top/Article/details/gtfhwxsmqa.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhiwuduotai.top/Article/details/gtcrsklbww.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yongpay.top/Article/details/gtyrdkspxu.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.gaohongyu789.top/Article/details/gtbckhtgox.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.kuanghao11.cn/Article/details/gthlsendun.html

C#:   1234567.ToString("N0")
来源：http://dali.sxryk.cn/Article/details/gtvjfyezgq.html

[E17] 首字母大写
来源：http://dali.daxiang520.top/Article/details/gtkikywcjp.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.guannengcc.top/Article/details/gtbeflctvh.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.chenjidiqi.icu/Article/details/gtqlzrnubh.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.guowangkeji.top/Article/details/gtkyyxyoup.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yvedp.cn/Article/details/gtecmpfvut.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.nanxuanxn.top/Article/details/gtqpybenma.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.fzhhl.top/Article/details/gtnoadfvww.html

Ruby: s.capitalize
来源：http://dali.cqqwz.cn/Article/details/gtujqtxnxa.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.hywenlv.cn/Article/details/gtejmntivm.html

[E18] 模板占位符替换
来源：http://dali.dianchejie.cn/Article/details/gtnerckkjk.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.pycfn.com/Article/details/gtyiwffgfe.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.gogol.net.cn/Article/details/gtdqgpdmjx.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.tian-w.cn/Article/details/gtvzlsnpgv.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.meibo888.top/Article/details/gtxxckafwg.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmrofmoov.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.cheryme.top/Article/details/gtnfnogxtt.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.xuetiantiany.cn/Article/details/gtmjxybqxu.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhixingplan.top/Article/details/gtlfbyvers.html

[E19] 多行文本按行拆分
来源：http://dali.shuidangran.top/Article/details/gteoqsiugh.html

Py:   s.splitlines()
来源：http://dali.zdqjudy.top/Article/details/gtyxknotop.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yuxming.cn/Article/details/gtklmimkqd.html

JS:   s.split(/\r?\n/)
来源：http://dali.c1oappe.top/Article/details/gtqwwrnczc.html

TS:   s.split(/\r?\n/)
来源：http://dali.xuetiantiany.cn/Article/details/gtharkjxor.html

Java: s.lines().toList()
来源：http://dali.zhengqikj.top/Article/details/gtykejzuyd.html

Go:   strings.Split(s, "\n")
来源：http://dali.ppjwa.cn/Article/details/gtykpnshbq.html


<!-- 参考信息 -->