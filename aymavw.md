代发 wailian999

TS:   [...new Set(arr)]
来源：http://dali.zhongyouzk.top/Article/details/gt2hkblbqlh.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.hnqzz.top/Article/details/gt2neafbqtg.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hongshengwenyu.top/Article/details/gt2cxseydfp.html

Ruby: arr.uniq
来源：http://dali.yj20258.top/Article/details/gt2jzmjzdca.html

C#:   list.Distinct().ToList()
来源：http://dali.andypj.xyz/Article/details/gt2ahklyztn.html

[D16] 求和与平均值
来源：http://dali.tanke756.top/Article/details/gt2cjstyplk.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.mhx1999.top/Article/details/gt2zqrsvipp.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2knfknpkd.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinqigufen.top/Article/details/gt2panuyhat.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sufxvd.cn/Article/details/gt2xyuewjmk.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.xuetiantiany.cn/Article/details/gt2jwszyjph.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2cfilyrhi.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.ehwqpu.com/Article/details/gt2wdgsooai.html

C#:   list.Sum();  list.Average()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jvmvogmo.html

[D17] 最大值与最小值
来源：http://dali.xziqi.cn/Article/details/gt2nzsxrwfz.html

Py:   max(arr);  min(arr)
来源：http://dali.ivvv.top/Article/details/gt2yoqldade.html

PHP:  max($arr);  min($arr);
来源：http://dali.nwbrower.top/Article/details/gt2tzhgcutu.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.haohaochexian.top/Article/details/gt2tlgxxzng.html

TS:   Math.max(...arr);
来源：http://dali.yj202588.top/Article/details/gt2spbzkbpd.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhoulong.xyz/Article/details/gt2ljovkeat.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yangfankeji.com/Article/details/gt2spgwxwaa.html

Ruby: arr.max;  arr.min
来源：http://dali.hysaishi.cn/Article/details/gt2dggyvell.html

C#:   list.Max();  list.Min()
来源：http://dali.svipenyu.cn/Article/details/gt2pwbkrgid.html

[D18] 扁平化嵌套数组
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dqasofwg.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yuanzhike.top/Article/details/gt2tobvbulm.html

PHP:  array_merge(...$nested);
来源：http://dali.havefunace.top/Article/details/gt2gfyddwcj.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.wangdashe.top/Article/details/gt2fqwunewr.html

TS:   nested.flat();
来源：http://dali.yj20258.top/Article/details/gt2umqxqgqr.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhixingplan.top/Article/details/gt2rdisjmfu.html

Go:   // 手写双层循环
来源：http://dali.havefunace.top/Article/details/gt2hbggmkrd.html

Ruby: nested.flatten
来源：http://dali.xziqi.cn/Article/details/gt2sdsnfsst.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.guowangkeji.top/Article/details/gt2tqpdlqcz.html

[D19] 按字段分组
来源：http://dali.yuanzhike.top/Article/details/gt2gbnppyra.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.sweek.top/Article/details/gt2eeddidac.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.cdnleiting.top/Article/details/gt2wlmjalaj.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.xuetiantiany.cn/Article/details/gt2qffhqpoe.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xfvlugwv.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.tianlin.xyz/Article/details/gt2gneyvpvq.html

Go:   // 手写 map[string][]T
来源：http://dali.xinyue.icu/Article/details/gt2mweutwcp.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.andypj.xyz/Article/details/gt2uneztywb.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.chenlongwang.top/Article/details/gt2gwuzmael.html

[D20] 统计每个元素出现次数
来源：http://dali.smart0.xyz/Article/details/gt2qalvslcs.html

Py:   Counter(arr)
来源：http://dali.yj20258888.top/Article/details/gt2tiovzfur.html

PHP:  array_count_values($arr);
来源：http://dali.ehwqpu.com/Article/details/gt2tbaucljw.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zycfv.cn/Article/details/gt2abdvjynk.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xziqi.cn/Article/details/gt2ynuywxal.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.meibo888.top/Article/details/gt2ydknhbgp.html

Go:   // 手写 map[T]int
来源：http://dali.wangdashe.top/Article/details/gt2khotteaf.html

Ruby: arr.tally
来源：http://dali.jinqigfzy.top/Article/details/gt2pedfsrsb.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wivvgfmy.html

[D21] 判断是否包含某元素
来源：http://dali.jyoumei.cn/Article/details/gt2tgokgopt.html

Py:   x in arr
来源：http://dali.aibaodan.cn/Article/details/gt2hwclding.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yanxiufei.cn/Article/details/gt2svuurvkg.html

JS:   arr.includes(x)
来源：http://dali.yj20258888.top/Article/details/gt2zubyjmth.html

TS:   arr.includes(x)
来源：http://dali.jyoumei.cn/Article/details/gt2exbyxmix.html

Java: list.contains(x)
来源：http://dali.guowangkeji.top/Article/details/gt2bdygwafh.html

Go:   slices.Contains(arr, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mkcbktag.html

Ruby: arr.include?(x)
来源：http://dali.yueranfly.top/Article/details/gt2xkitdgbw.html

C#:   list.Contains(x)
来源：http://dali.fengsongda.top/Article/details/gt2jmwzggwq.html

[D22] 复制数组（避免共享引用）
来源：http://dali.iojbl.cn/Article/details/gt2oasmpyes.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.guannengcc.top/Article/details/gt2aawdvoxr.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.birdmap.top/Article/details/gt2dhairnqy.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.meibo888.top/Article/details/gt2slweddnx.html

TS:   [...arr];
来源：http://dali.c1oappe.top/Article/details/gt2oogycvkx.html

Java: new ArrayList<>(list);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2koidctie.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhongyouzk.top/Article/details/gt2jkuekkfr.html

Ruby: arr.dup;  arr.clone
来源：http://dali.guowangkeji.top/Article/details/gt2vwfgvgjd.html

C#:   new List<int>(list);
来源：http://dali.guannengcc.top/Article/details/gt2binxvytv.html

[D23] reduce 累积计算
来源：http://dali.jqgufenzy.top/Article/details/gt2xvsfhito.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.cdnleiting.top/Article/details/gt2uvqekger.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yanxiufei.cn/Article/details/gt2oiemuovh.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.birdmap.top/Article/details/gt2oagkyjmj.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhongyouzk.top/Article/details/gt2ptbhattb.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jlsjyb.cn/Article/details/gt2wkvrjwzr.html

Go:   // 手写循环
来源：http://dali.jyoumei.cn/Article/details/gt2hkmvetfi.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.meibo888.top/Article/details/gt2ucpfxhdp.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jlsjyb.cn/Article/details/gt2jdfmxzuj.html

[D24] 字典 / Map 基本操作
来源：http://dali.fengsongda.top/Article/details/gt2zbjxetne.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.cqqwz.cn/Article/details/gt2ffmvqula.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhixingplan.top/Article/details/gt2vscmnhrj.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.ehwqpu.com/Article/details/gt2wiuvxdgf.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.hysaishi.cn/Article/details/gt2ozohhdwo.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.iojbl.cn/Article/details/gt2fjsntuxi.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ekpeuezq.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.cdnleiting.top/Article/details/gt2egngfbna.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.hnqzz.top/Article/details/gt2bgpegbxf.html

[D25] Set 集合去重与交并差
来源：http://dali.cdnleiting.top/Article/details/gt2vcdtdyfb.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jyoumei.cn/Article/details/gt2tptwwvcl.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hammf.cn/Article/details/gt2icsakghz.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.sufxvd.cn/Article/details/gt2ybzwkfcy.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yj20258.top/Article/details/gt2ajueyjgf.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.guowangkeji.top/Article/details/gt2cbapxfxh.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yj202588.top/Article/details/gt2ovnpajga.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jinqigufen.top/Article/details/gt2uiouhegn.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.vqdsnc.cn/Article/details/gt2kbduqsam.html

[D26] 数组转字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aaggvgqv.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jyoumei.cn/Article/details/gt2pckjsxdl.html

PHP:  implode(", ", $arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wfypmuoc.html

JS:   arr.join(", ")
来源：http://dali.wangdashe.top/Article/details/gt2zglvteyl.html

TS:   arr.join(", ")
来源：http://dali.gaohongyu789.top/Article/details/gt2mrpuzghb.html

Java: String.join(", ", list)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wjyprlwt.html

Go:   strings.Join(strs, ", ")
来源：http://dali.dianchejie.cn/Article/details/gt2dgviqvgr.html

Ruby: arr.join(", ")
来源：http://dali.sufxvd.cn/Article/details/gt2oqwmzcch.html

C#:   string.Join(", ", list)
来源：http://dali.quarkkingdee.top/Article/details/gt2ngehqsou.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2gyhbxhhr.html

E. 字符串处理
来源：http://dali.bjfxy.top/Article/details/gt2mbpkwtka.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2ovkzufzx.html

[E01] 拼接字符串
来源：http://dali.sweek.top/Article/details/gt2tpzlhrdm.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.ydzc1.top/Article/details/gt2dgemxgqr.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jinqigufen.top/Article/details/gt2ljudmlpc.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zdqjudy.top/Article/details/gt2prxjzkwu.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jianghu66.top/Article/details/gt2oryadqad.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hywenlv.cn/Article/details/gt2pxgtvnlw.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhixingplan.top/Article/details/gt2lcvqfyrv.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.tianlin.xyz/Article/details/gt2brdfeloa.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.cdnleiting.top/Article/details/gt2gcbaxdsn.html

[E02] 重复字符串
来源：http://dali.yanxiufei.cn/Article/details/gt2lnfltrnq.html

Py:   "ab" * 3
来源：http://dali.daxiang520.top/Article/details/gt2tsucmzxz.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hywenlv.cn/Article/details/gt2qvvscagz.html

JS:   "ab".repeat(3)
来源：http://dali.jinqigfzy.top/Article/details/gt2qvixcyjc.html

TS:   "ab".repeat(3)
来源：http://dali.ivvv.top/Article/details/gt2pmcklqoq.html

Java: "ab".repeat(3)
来源：http://dali.zycfv.cn/Article/details/gt2strcxhxc.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.wangdashe.top/Article/details/gt2lfbzmbdj.html

Ruby: "ab" * 3
来源：http://dali.dashuyun.cn/Article/details/gt2ajpunwll.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.aizwys.cn/Article/details/gt2xryknckf.html

[E03] 截取子串
来源：http://dali.316326.xyz/Article/details/gt2jcdacacs.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.tianlin.xyz/Article/details/gt2gydmehjy.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xylfe.cn/Article/details/gt2akpazmno.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.guowangkeji.top/Article/details/gt2ddfpzfxq.html

TS:   s.slice(1, 4)
来源：http://dali.ppjwa.cn/Article/details/gt2dszdwfev.html

Java: s.substring(1, 4)
来源：http://dali.yvedp.cn/Article/details/gt2qubplblp.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.redwolf501.top/Article/details/gt2ettmgbik.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.nwbrower.top/Article/details/gt2flftgfda.html

C#:   s.Substring(1, 3)
来源：http://dali.dianchejie.cn/Article/details/gt2btntersi.html

[E04] 查找子串位置
来源：http://dali.ehwqpu.com/Article/details/gt2vazxvotv.html

Py:   s.find("x");  s.index("x")
来源：http://dali.wangshuangyany.cn/Article/details/gt2mdaxxjmg.html

PHP:  strpos($s, "x");
来源：http://dali.ivvv.top/Article/details/gt2dxghamqr.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.tianlin.xyz/Article/details/gt2cvwoorti.html

TS:   s.indexOf("x")
来源：http://dali.sufxvd.cn/Article/details/gt2gacemyow.html

Java: s.indexOf("x")
来源：http://dali.hammf.cn/Article/details/gt2bsyqzvev.html

Go:   strings.Index(s, "x")
来源：http://dali.yonumen.top/Article/details/gt2rbacmprq.html

Ruby: s.index("x")
来源：http://dali.jqgufenzy.top/Article/details/gt2oqtptokn.html

C#:   s.IndexOf("x")
来源：http://dali.hfpthk.cn/Article/details/gt2vwztayuu.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.kuanghao11.cn/Article/details/gt2ogtqtafr.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yongpay.top/Article/details/gt2uhaoetev.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.hywenlv.cn/Article/details/gt2xfadgiol.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hnxiangtu.top/Article/details/gt2owvvemov.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.gotoacloud.top/Article/details/gt2dvqdsnxd.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hnxiangtu.top/Article/details/gt2mcjnecke.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.nwbrower.top/Article/details/gt2sbdwuzqq.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.sysykeji.top/Article/details/gt2dtqllvyi.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.hnxiangtu.top/Article/details/gt2lziqaukq.html

[E06] 替换子串
来源：http://dali.sysykeji.top/Article/details/gt2qdikdizp.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.ivvv.top/Article/details/gt2mgxijszb.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yuanzhike.top/Article/details/gt2fkshjbum.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.birdmap.top/Article/details/gt2olkfwmlg.html

TS:   s.replaceAll("a", "b")
来源：http://dali.aizwys.cn/Article/details/gt2vvfcuxyb.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jlsjyb.cn/Article/details/gt2paozcqvm.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.chenzaomai.com/Article/details/gt2ugdavhzv.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.pengpengdd.cyou/Article/details/gt2qurjszyn.html

C#:   s.Replace("a", "b")
来源：http://dali.jqgfzy.top/Article/details/gt2xykijfyr.html

[E07] 按分隔符拆分
来源：http://dali.jqgfzy.top/Article/details/gt2qciejzme.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.snrcjt.cn/Article/details/gt2umfifprr.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yj202588.top/Article/details/gt2ugursyee.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jinqigfzy.top/Article/details/gt2quiucqsp.html

TS:   s.split(",")
来源：http://dali.pycfn.com/Article/details/gt2uzgdpliq.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.cashguo.top/Article/details/gt2qktbjloj.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.kuanghao11.cn/Article/details/gt2ktughsoj.html

Ruby: s.split(",");  s.split
来源：http://dali.zhongyouzk.top/Article/details/gt2qphykoyy.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.ppjwa.cn/Article/details/gt2exyjfgqa.html

[E08] 数组按分隔符合并
来源：http://dali.dashuyun.cn/Article/details/gt2ajfuxsrj.html

Py:   ",".join(items)
来源：http://dali.gogol.net.cn/Article/details/gt2setspiij.html

PHP:  implode(",", $items);
来源：http://dali.ppjwa.cn/Article/details/gt2bfaxwgpo.html

JS:   items.join(",")
来源：http://dali.zdqjudy.top/Article/details/gt2glqtjyhz.html

TS:   items.join(",")
来源：http://dali.vqdsnc.cn/Article/details/gt2biujjboc.html

Java: String.join(",", items)
来源：http://dali.jyoumei.cn/Article/details/gt2hpyieyvi.html

Go:   strings.Join(items, ",")
来源：http://dali.gotoacloud.top/Article/details/gt2hedogjpq.html

Ruby: items.join(",")
来源：http://dali.bjfxy.top/Article/details/gt2pngmemcl.html

C#:   string.Join(",", items)
来源：http://dali.kuanghao11.cn/Article/details/gt2afsyalfd.html

[E09] 去除所有空白字符
来源：http://dali.yvedp.cn/Article/details/gt2ixepjtpr.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jyoumei.cn/Article/details/gt2tcvluthy.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hammf.cn/Article/details/gt2ddgdjpau.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.birdmap.top/Article/details/gt2bnsiytto.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hfpthk.cn/Article/details/gt2xfeqsgvb.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.dashuyun.cn/Article/details/gt2kbfdhgkc.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2apsufyfm.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.bjfxy.top/Article/details/gt2kdnetxei.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jiagoushi.top/Article/details/gt2szajiomy.html

[E10] 左侧补零 / 定长填充
来源：http://dali.havefunace.top/Article/details/gt2vycokvta.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.quarkkingdee.top/Article/details/gt2tckublpx.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yuanzhike.top/Article/details/gt2zhfhodfe.html

JS:   "7".padStart(3, "0")
来源：http://dali.haohaochexian.top/Article/details/gt2ozksvjth.html

TS:   "7".padStart(3, "0")
来源：http://dali.hfpthk.cn/Article/details/gt2ujyuumta.html

Java: String.format("%03d", 7)
来源：http://dali.jiagoushi.top/Article/details/gt2vhffuckm.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhoulong.xyz/Article/details/gt2jyrwinpi.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hnqzz.top/Article/details/gt2qlmkziyi.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yueranfly.top/Article/details/gt2rqfcckbd.html

[E11] 反转字符串
来源：http://dali.cqqwz.cn/Article/details/gt2unrohxbn.html

Py:   s[::-1]
来源：http://dali.wangdashe.top/Article/details/gt2rgdoaudj.html

PHP:  strrev($s);
来源：http://dali.cqqwz.cn/Article/details/gt2gmgkvgzq.html

JS:   [...s].reverse().join("")
来源：http://dali.nanxuanxn.top/Article/details/gt2cocsnpec.html

TS:   [...s].reverse().join("")
来源：http://dali.jyoumei.cn/Article/details/gt2jasnbkrs.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.9152youxi.cn/Article/details/gt2impqoigi.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fjndyuev.html

Ruby: s.reverse
来源：http://dali.yvedp.cn/Article/details/gt2psufomis.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.pycfn.com/Article/details/gt2jqfjbsrv.html

[E12] 统计某字符出现次数
来源：http://dali.daxiang520.top/Article/details/gt2uuupniad.html

Py:   s.count("a")
来源：http://dali.ydzc1.top/Article/details/gt2dvfvnrhr.html

PHP:  substr_count($s, "a");
来源：http://dali.chenlongwang.top/Article/details/gt2mkurkilr.html

JS:   s.split("a").length - 1
来源：http://dali.nanxinkj.top/Article/details/gt2vegblkgb.html

TS:   s.split("a").length - 1
来源：http://dali.316326.xyz/Article/details/gt2hjmetkrf.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.pycfn.com/Article/details/gt2bcyvwczw.html

Go:   strings.Count(s, "a")
来源：http://dali.hongshengwenyu.top/Article/details/gt2lwdkneua.html

Ruby: s.count("a")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rncdixfc.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yangfankeji.com/Article/details/gt2vzjjmbot.html

[E13] 逐字符遍历
来源：http://dali.zhiwuduotai.top/Article/details/gt2hwkmntlx.html

Py:   for ch in s: print(ch)
来源：http://dali.hnqzz.top/Article/details/gt2vhzderbq.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.guowangkeji.top/Article/details/gt2gnxxyrtv.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ppjwa.cn/Article/details/gt2bgjetuee.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cashguo.top/Article/details/gt2bxegszvj.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yvedp.cn/Article/details/gt2jiznfauk.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.chenjidiqi.icu/Article/details/gt2salkerep.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.fzhhl.top/Article/details/gt2xiobfpjt.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jqgufenzy.top/Article/details/gt2soungrfn.html

[E14] URL 编码与 Base64
来源：http://dali.316326.xyz/Article/details/gt2ituwhqpe.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jqgfzy.top/Article/details/gt2htjvfjpg.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.pycfn.com/Article/details/gt2hhseqdva.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.c1oappe.top/Article/details/gt2wxyoqtyl.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.ivvv.top/Article/details/gt2bjmnikue.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jianghu66.top/Article/details/gt2trdlvuqz.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.cheryme.top/Article/details/gt2gjprlbdl.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xuetiantiany.cn/Article/details/gt2cpifggle.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jlsjyb.cn/Article/details/gt2lzraskba.html

[E15] HTML 转义 / 反转义
来源：http://dali.hnxiangtu.top/Article/details/gt2iunfmjww.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yuxming.cn/Article/details/gt2mkpnglsk.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.snrcjt.cn/Article/details/gt2ylcsrnol.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rhbulehz.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hywenlv.cn/Article/details/gt2ozmmohst.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tsddllpq.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.sxryk.cn/Article/details/gt2rinvglvp.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2bgbqhlxd.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pooksqxf.html

[E16] 数字千分位
来源：http://dali.fzhhl.top/Article/details/gt2gldzyvij.html

Py:   f"{1234567:,}"
来源：http://dali.pycfn.com/Article/details/gt2hwuyflcn.html

PHP:  number_format(1234567);
来源：http://dali.xuetiantiany.cn/Article/details/gt2hnzucduq.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.xziqi.cn/Article/details/gt2adfminka.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.9152youxi.cn/Article/details/gt2wgtlxqjp.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.chenlongwang.top/Article/details/gt2vekgxvde.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jlsjyb.cn/Article/details/gt2yibchfqb.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jqgufenzy.top/Article/details/gt2rxghgqyq.html

C#:   1234567.ToString("N0")
来源：http://dali.andypj.xyz/Article/details/gt2payhaddk.html

[E17] 首字母大写
来源：http://dali.cdnleiting.top/Article/details/gt2anlhioeq.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jyoumei.cn/Article/details/gt2tbnzmihl.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yj202588.top/Article/details/gt2wliqdpbz.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.guannengcc.top/Article/details/gt2tpqacjgh.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zdqjudy.top/Article/details/gt2ojbqikno.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.hnxiangtu.top/Article/details/gt2oguffyto.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.hnxiangtu.top/Article/details/gt2zdmipalg.html

Ruby: s.capitalize
来源：http://dali.wangshuangyany.cn/Article/details/gt2sedeznhc.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2acvtlhyh.html

[E18] 模板占位符替换
来源：http://dali.yj202588.top/Article/details/gt2mywsdujn.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.chenlongwang.top/Article/details/gt2mjzssfhj.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.fengsongda.top/Article/details/gt2eddhxzpc.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.316326.xyz/Article/details/gt2ezivebam.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.snrcjt.cn/Article/details/gt2ajvnkoyg.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.pengpengdd.cyou/Article/details/gt2qjnsyhlc.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jlsjyb.cn/Article/details/gt2usrldznl.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.smart0.xyz/Article/details/gt2ovzifnti.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yj20258.top/Article/details/gt2gwyqbzaw.html

[E19] 多行文本按行拆分
来源：http://dali.svipenyu.cn/Article/details/gt2fljvdeml.html

Py:   s.splitlines()
来源：http://dali.chenlongwang.top/Article/details/gt2hehjnqkq.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.xylfe.cn/Article/details/gt2osulqjqu.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhiwuduotai.top/Article/details/gt2okzmvycd.html

TS:   s.split(/\r?\n/)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ipudlcck.html

Java: s.lines().toList()
来源：http://dali.xuetiantiany.cn/Article/details/gt2fxmphrbw.html

Go:   strings.Split(s, "\n")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2owklrscr.html

Ruby: s.lines
来源：http://dali.iojbl.cn/Article/details/gt2jsyicthq.html

C#:   s.Split('\n')
来源：http://dali.wangshuangyany.cn/Article/details/gt2cdbcahby.html

[E20] 判断字符串是否为空
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gohgiigd.html

Py:   if not s:
来源：http://dali.tanke756.top/Article/details/gt2widbdhbf.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.xuanzx.com/Article/details/gt2zjcuaqfz.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yj20258888.top/Article/details/gt2bcnwrpqq.html

TS:   if (s === "") {}
来源：http://dali.jqgfzy.top/Article/details/gt2ztyxkslo.html

Java: if (s.isEmpty()) {}
来源：http://dali.tianlin.xyz/Article/details/gt2enbskogb.html

Go:   if s == "" {}
来源：http://dali.ivvv.top/Article/details/gt2nuzxnpmp.html

Ruby: if s.empty?
来源：http://dali.yj20258.top/Article/details/gt2snnrrzle.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jiagoushi.top/Article/details/gt2rvqrdgqf.html

[E21] 超长截断加省略号
来源：http://dali.wangdashe.top/Article/details/gt2ehkuskvf.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.daria6918.cn/Article/details/gt2tulzshnm.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.chenzaomai.com/Article/details/gt2wwewthxy.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yongpay.top/Article/details/gt2lcrzfrtv.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.mhx1999.top/Article/details/gt2dqocbder.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yvedp.cn/Article/details/gt2wcochmgi.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jyoumei.cn/Article/details/gt2sjokehbr.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.fzhhl.top/Article/details/gt2aqtackwy.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.svipenyu.cn/Article/details/gt2lsvhnjqu.html

[E22] 字节长度与字符长度
来源：http://dali.jyoumei.cn/Article/details/gt2foppwpeq.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xziqi.cn/Article/details/gt2xomonmds.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yuxming.cn/Article/details/gt2rdgsnnvo.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hywenlv.cn/Article/details/gt2ickkgeno.html


<!-- 参考信息 -->