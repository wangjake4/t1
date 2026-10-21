代发 wailian999

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhoulong.xyz/Article/details/gtdogtxwjp.html

Go:   // 手写双层循环
来源：http://dali.9152youxi.cn/Article/details/gtwgekxyti.html

Ruby: nested.flatten
来源：http://dali.yj202588.top/Article/details/gtcsjqxqnd.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.nanxuanxn.top/Article/details/gttfhfdzas.html

[D19] 按字段分组
来源：http://dali.kuanghao11.cn/Article/details/gtyhjcticr.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvpykmznj.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.chenlongwang.top/Article/details/gtfrrxpifg.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.aizwys.cn/Article/details/gtjnpuamto.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.shzxlz.cn/Article/details/gtrhumkslh.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yonumen.top/Article/details/gtayqdggxw.html

Go:   // 手写 map[string][]T
来源：http://dali.wangdashe.top/Article/details/gtuncmicra.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.shzxlz.cn/Article/details/gtjmaromyt.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfksufcln.html

[D20] 统计每个元素出现次数
来源：http://dali.nwbrower.top/Article/details/gtwjjsnsuz.html

Py:   Counter(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtikyfvsvn.html

PHP:  array_count_values($arr);
来源：http://dali.birdmap.top/Article/details/gtobthdlpo.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.andypj.xyz/Article/details/gtuoqebcnw.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.9152youxi.cn/Article/details/gtberaurbs.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yj20258.top/Article/details/gtojpdeubc.html

Go:   // 手写 map[T]int
来源：http://dali.jyoumei.cn/Article/details/gtizcxjwfc.html

Ruby: arr.tally
来源：http://dali.kuanghao11.cn/Article/details/gtecxebcto.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjulwwuze.html

[D21] 判断是否包含某元素
来源：http://dali.smart0.xyz/Article/details/gtpgvcascc.html

Py:   x in arr
来源：http://dali.zhixingplan.top/Article/details/gtbfxaqagi.html

PHP:  in_array($x, $arr, true);
来源：http://dali.sxryk.cn/Article/details/gtgylfjxyr.html

JS:   arr.includes(x)
来源：http://dali.xziqi.cn/Article/details/gtsunvhkui.html

TS:   arr.includes(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuneadhli.html

Java: list.contains(x)
来源：http://dali.daxiang520.top/Article/details/gtkumyuwzh.html

Go:   slices.Contains(arr, x)
来源：http://dali.cashguo.top/Article/details/gtlmddtkun.html

Ruby: arr.include?(x)
来源：http://dali.0kj1m.cn/Article/details/gtcmjsgzfb.html

C#:   list.Contains(x)
来源：http://dali.nanxuanxn.top/Article/details/gtopzvidaa.html

[D22] 复制数组（避免共享引用）
来源：http://dali.guowangkeji.top/Article/details/gtfwhqhomn.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.9152youxi.cn/Article/details/gtspjwffrh.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.gotoacloud.top/Article/details/gtvxygimec.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.havefunace.top/Article/details/gtxoxcduri.html

TS:   [...arr];
来源：http://dali.sysykeji.top/Article/details/gtvflagwym.html

Java: new ArrayList<>(list);
来源：http://dali.jiagoushi.top/Article/details/gtldercdzq.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhongyouzk.top/Article/details/gtcfiwnebj.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhoulong.xyz/Article/details/gtpgkutuxk.html

C#:   new List<int>(list);
来源：http://dali.vqdsnc.cn/Article/details/gtolesdcud.html

[D23] reduce 累积计算
来源：http://dali.feifeiyinyue.top/Article/details/gtbwziiswl.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jqgfzy.top/Article/details/gtrwqxqjly.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.cashguo.top/Article/details/gthknkcsfe.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.tian-w.cn/Article/details/gtzivqbbvt.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.svipenyu.cn/Article/details/gtxetxqhoz.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.svipenyu.cn/Article/details/gtaohvakog.html

Go:   // 手写循环
来源：http://dali.ybcxt.top/Article/details/gtythrahuf.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yvedp.cn/Article/details/gtvymygufl.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jqgufenzy.top/Article/details/gtqsuxefxl.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhiwuduotai.top/Article/details/gtxgmamazo.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhoulong.xyz/Article/details/gtnbwlmzfx.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.wangshuangyany.cn/Article/details/gtzlrehvdq.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jlsjyb.cn/Article/details/gttdctziro.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhengqikj.top/Article/details/gthxwejfun.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.havefunace.top/Article/details/gtdimxicrp.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yj20258888.top/Article/details/gtfabtglxe.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.smart0.xyz/Article/details/gtmafbnzxj.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.sufxvd.cn/Article/details/gtzgigrtiu.html

[D25] Set 集合去重与交并差
来源：http://dali.xziqi.cn/Article/details/gtxrppufbv.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.cucudq.cn/Article/details/gtnjtrzzho.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.chenlongwang.top/Article/details/gtvorilwjt.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.vqdsnc.cn/Article/details/gthsprcbmu.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.havefunace.top/Article/details/gtixxedimy.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.ehwqpu.com/Article/details/gtisniuqhz.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.aizwys.cn/Article/details/gtsiwfotne.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtuxrvnfmm.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.sxryk.cn/Article/details/gtpftnaknk.html

[D26] 数组转字符串
来源：http://dali.yonumen.top/Article/details/gtblgtdwsy.html

Py:   ", ".join(map(str, arr))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpsdtucne.html

PHP:  implode(", ", $arr);
来源：http://dali.sweek.top/Article/details/gtilxquulh.html

JS:   arr.join(", ")
来源：http://dali.bjfxy.top/Article/details/gtewvzdaym.html

TS:   arr.join(", ")
来源：http://dali.cheryme.top/Article/details/gtsbqpseia.html

Java: String.join(", ", list)
来源：http://dali.jyoumei.cn/Article/details/gtjnwmrosu.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zdqjudy.top/Article/details/gtgoffjpkb.html

Ruby: arr.join(", ")
来源：http://dali.jqgfzy.top/Article/details/gtovqzglwe.html

C#:   string.Join(", ", list)
来源：http://dali.xziqi.cn/Article/details/gttrhjvamd.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtrskpfkhn.html

E. 字符串处理
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsengahba.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtamscixbv.html

[E01] 拼接字符串
来源：http://dali.zhiwuduotai.top/Article/details/gtpoxqgeql.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.nanxinkj.top/Article/details/gtyohxgjfv.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hywenlv.cn/Article/details/gtvkklzvqq.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ybcxt.top/Article/details/gtchfkwypc.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.tian-w.cn/Article/details/gtaixgvlas.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yj20258888.top/Article/details/gtkieukcha.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzkcqxtmr.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.ppjwa.cn/Article/details/gtyfgadchl.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.pengpengdd.cyou/Article/details/gtxaamxahm.html

[E02] 重复字符串
来源：http://dali.gaohongyu789.top/Article/details/gtlmienvji.html

Py:   "ab" * 3
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbdgvvasd.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yangfankeji.com/Article/details/gttorymkku.html

JS:   "ab".repeat(3)
来源：http://dali.hongshengwenyu.top/Article/details/gtcclwzful.html

TS:   "ab".repeat(3)
来源：http://dali.hammf.cn/Article/details/gtajpnetaq.html

Java: "ab".repeat(3)
来源：http://dali.sufxvd.cn/Article/details/gtgvnfrmky.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.sufxvd.cn/Article/details/gtejousdor.html

Ruby: "ab" * 3
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxgzgnxza.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yueranfly.top/Article/details/gtrdlcmbut.html

[E03] 截取子串
来源：http://dali.zhoulong.xyz/Article/details/gtyhyzkoto.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jianghu66.top/Article/details/gtmyitkecu.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.gogol.net.cn/Article/details/gtxjfifhhx.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.c1oappe.top/Article/details/gtbconnkev.html

TS:   s.slice(1, 4)
来源：http://dali.haohaochexian.top/Article/details/gtxawmnjfc.html

Java: s.substring(1, 4)
来源：http://dali.jianghu66.top/Article/details/gtyacvxuvb.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.hysaishi.cn/Article/details/gtjcaidilf.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.pycfn.com/Article/details/gtwbwxmrrv.html

C#:   s.Substring(1, 3)
来源：http://dali.sysykeji.top/Article/details/gtlpwlmrcs.html

[E04] 查找子串位置
来源：http://dali.fzhhl.top/Article/details/gtwffuykza.html

Py:   s.find("x");  s.index("x")
来源：http://dali.tanke756.top/Article/details/gtuvobhafc.html

PHP:  strpos($s, "x");
来源：http://dali.9152youxi.cn/Article/details/gtnkfdwixa.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.sxryk.cn/Article/details/gtmqsxrlpl.html

TS:   s.indexOf("x")
来源：http://dali.shuidangran.top/Article/details/gtkjgbuejl.html

Java: s.indexOf("x")
来源：http://dali.quarkkingdee.top/Article/details/gtjnyusdsz.html

Go:   strings.Index(s, "x")
来源：http://dali.chenzaomai.com/Article/details/gtqfcugobs.html

Ruby: s.index("x")
来源：http://dali.yj202588.top/Article/details/gtuddfbncv.html

C#:   s.IndexOf("x")
来源：http://dali.yangfankeji.com/Article/details/gtpknyquzd.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.ybcxt.top/Article/details/gtambdnfel.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.guowangkeji.top/Article/details/gtjsrcaojv.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.cqqwz.cn/Article/details/gtaclnjrdp.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.tian-w.cn/Article/details/gtgjxihvcj.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.ppjwa.cn/Article/details/gtrqakykxk.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.svipenyu.cn/Article/details/gtvobyckvm.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjuqokzke.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.snrcjt.cn/Article/details/gtqwnscscz.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.tian-w.cn/Article/details/gtnyjuxfww.html

[E06] 替换子串
来源：http://dali.jiagoushi.top/Article/details/gthxrbmxjz.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.cucudq.cn/Article/details/gtglzxzfml.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.ybcxt.top/Article/details/gtvifixknl.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gtfjebdfbk.html

TS:   s.replaceAll("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gtoegolwbl.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yongpay.top/Article/details/gtuqjkxqpx.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.guannengcc.top/Article/details/gtjbusoiuq.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.xylfe.cn/Article/details/gttnwfbdkq.html

C#:   s.Replace("a", "b")
来源：http://dali.shuidangran.top/Article/details/gtpwacercf.html

[E07] 按分隔符拆分
来源：http://dali.zhongyouzk.top/Article/details/gtjuhbyapl.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.wangdashe.top/Article/details/gtoeqmgpww.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.kuanghao11.cn/Article/details/gtczniirqt.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jiagoushi.top/Article/details/gtkutfchwd.html

TS:   s.split(",")
来源：http://dali.yonumen.top/Article/details/gttzoqqpvl.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhongyouzk.top/Article/details/gtxkqbiabx.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.ybcxt.top/Article/details/gtzoqyalrg.html

Ruby: s.split(",");  s.split
来源：http://dali.ppjwa.cn/Article/details/gtqrstgfaq.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.sxryk.cn/Article/details/gthldwopvz.html

[E08] 数组按分隔符合并
来源：http://dali.jinghuilouyu.cn/Article/details/gtcqcgsiic.html

Py:   ",".join(items)
来源：http://dali.fengsongda.top/Article/details/gtwfkzpyfs.html

PHP:  implode(",", $items);
来源：http://dali.xuetiantiany.cn/Article/details/gtaliitpsb.html

JS:   items.join(",")
来源：http://dali.xziqi.cn/Article/details/gtnggjmaih.html

TS:   items.join(",")
来源：http://dali.haohaochexian.top/Article/details/gtgjtqpasr.html

Java: String.join(",", items)
来源：http://dali.xuanzx.com/Article/details/gtwmqrkujp.html

Go:   strings.Join(items, ",")
来源：http://dali.shangyingyoupin.top/Article/details/gtqgzwwiyq.html

Ruby: items.join(",")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuvkzmnsw.html

C#:   string.Join(",", items)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtguqtisyj.html

[E09] 去除所有空白字符
来源：http://dali.cdnleiting.top/Article/details/gtuxnxikew.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.hnxiangtu.top/Article/details/gtorapmqld.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.shzxlz.cn/Article/details/gtnsxzhzxd.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhongyouzk.top/Article/details/gtlepsfjjl.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yangfankeji.com/Article/details/gtznzwkcmb.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.fengsongda.top/Article/details/gtjkkvdnms.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jinqigfzy.top/Article/details/gtsbhfzkfy.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.gogol.net.cn/Article/details/gtnryxtfxd.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.ehwqpu.com/Article/details/gtxcgmybop.html

[E10] 左侧补零 / 定长填充
来源：http://dali.gotoacloud.top/Article/details/gtdsxdmhzn.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.nanxinkj.top/Article/details/gtitledrvt.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.haohaochexian.top/Article/details/gtiohucolp.html

JS:   "7".padStart(3, "0")
来源：http://dali.dianchejie.cn/Article/details/gtmercppdm.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhongyouzk.top/Article/details/gtejvdglfl.html

Java: String.format("%03d", 7)
来源：http://dali.hnqzz.top/Article/details/gtcyelcoji.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zycfv.cn/Article/details/gtlliyehiv.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhixingplan.top/Article/details/gtjaxmziqx.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.haohaochexian.top/Article/details/gtlqxthlte.html

[E11] 反转字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuwnokfpq.html

Py:   s[::-1]
来源：http://dali.birdmap.top/Article/details/gtiwtppdnm.html

PHP:  strrev($s);
来源：http://dali.kuanghao11.cn/Article/details/gtrwhhnacg.html

JS:   [...s].reverse().join("")
来源：http://dali.iojbl.cn/Article/details/gtwlscdhyu.html

TS:   [...s].reverse().join("")
来源：http://dali.cucudq.cn/Article/details/gtfuzvgflx.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.aizwys.cn/Article/details/gtxbeqwinu.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbxsptfny.html

Ruby: s.reverse
来源：http://dali.hnqzz.top/Article/details/gtkiwhayrl.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.birdmap.top/Article/details/gtnesnfhnb.html

[E12] 统计某字符出现次数
来源：http://dali.nwbrower.top/Article/details/gtkhsowkhk.html

Py:   s.count("a")
来源：http://dali.gotoacloud.top/Article/details/gtrswuunlh.html

PHP:  substr_count($s, "a");
来源：http://dali.nanxuanxn.top/Article/details/gtrndrrwci.html

JS:   s.split("a").length - 1
来源：http://dali.meibo888.top/Article/details/gtxuiqtlag.html

TS:   s.split("a").length - 1
来源：http://dali.gaohongyu789.top/Article/details/gteyotazom.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.hongshengwenyu.top/Article/details/gteayjtsvy.html

Go:   strings.Count(s, "a")
来源：http://dali.sweek.top/Article/details/gtyegnhjii.html

Ruby: s.count("a")
来源：http://dali.gotoacloud.top/Article/details/gtwkjoghln.html

C#:   s.Count(c => c == 'a')
来源：http://dali.ywan-chungtsiang.top/Article/details/gttewvzgod.html

[E13] 逐字符遍历
来源：http://dali.shangyingyoupin.top/Article/details/gtsxzkljpq.html

Py:   for ch in s: print(ch)
来源：http://dali.jlsjyb.cn/Article/details/gtsqaukgfi.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.daxiang520.top/Article/details/gtrpfegplb.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yongpay.top/Article/details/gtloniueez.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.aibaodan.cn/Article/details/gtsqslzbna.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.svipenyu.cn/Article/details/gtmrruacqr.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jlsjyb.cn/Article/details/gtejsnmyby.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.pycfn.com/Article/details/gtxldujnqd.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.dashuyun.cn/Article/details/gtxvlphfne.html

[E14] URL 编码与 Base64
来源：http://dali.hywenlv.cn/Article/details/gtqzgrzgwg.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yj20258.top/Article/details/gtxntwfmhl.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.ppjwa.cn/Article/details/gtylytdqac.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.xziqi.cn/Article/details/gtrqlfhkwx.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jiagoushi.top/Article/details/gtymrlyyfw.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.ehwqpu.com/Article/details/gttgltlrsc.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.ybcxt.top/Article/details/gtmlqgglqc.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yueranfly.top/Article/details/gtqtqrwsdi.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.gzhubu.top/Article/details/gtjiipuksd.html

[E15] HTML 转义 / 反转义
来源：http://dali.hongshengwenyu.top/Article/details/gtchmrbvzn.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.316326.xyz/Article/details/gtlrbdrraj.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yangfankeji.com/Article/details/gtxmuaugwt.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yanxiufei.cn/Article/details/gtsdddhlny.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yongpay.top/Article/details/gtdiyfpsxh.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.ehwqpu.com/Article/details/gtuzpthqrb.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhongyouzk.top/Article/details/gtsjtxggqx.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.andypj.xyz/Article/details/gtjocrjgek.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yuxming.cn/Article/details/gtmzgkgaqs.html

[E16] 数字千分位
来源：http://dali.yuxming.cn/Article/details/gtlxpzldwu.html

Py:   f"{1234567:,}"
来源：http://dali.c1oappe.top/Article/details/gtupgykiix.html

PHP:  number_format(1234567);
来源：http://dali.gaohongyu789.top/Article/details/gtsvhhojqh.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.hnxiangtu.top/Article/details/gtrhsaqklt.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.xuanzx.com/Article/details/gtqoulheup.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.gotoacloud.top/Article/details/gtyvnvnqze.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.guannengcc.top/Article/details/gtvxrmfgue.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.shanyushiyangkeji.top/Article/details/gtceuifuhb.html

C#:   1234567.ToString("N0")
来源：http://dali.vqdsnc.cn/Article/details/gtubmqledw.html

[E17] 首字母大写
来源：http://dali.316326.xyz/Article/details/gtwtypapxn.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yvedp.cn/Article/details/gtbrkvncjt.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.c1oappe.top/Article/details/gtxkcrmhgc.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cashguo.top/Article/details/gtmlaydegk.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hnxiangtu.top/Article/details/gtzfadymlp.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.ehwqpu.com/Article/details/gtmzrfsfsb.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.hnqzz.top/Article/details/gtuwqqaout.html

Ruby: s.capitalize
来源：http://dali.ydzc1.top/Article/details/gtdqrbspif.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.xuetiantiany.cn/Article/details/gtlsaifufo.html

[E18] 模板占位符替换
来源：http://dali.xziqi.cn/Article/details/gtgcnrfxlw.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.xylfe.cn/Article/details/gtqkillmfv.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jiagoushi.top/Article/details/gtacnyoxxz.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.gzhubu.top/Article/details/gtjqyfjqaf.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yvedp.cn/Article/details/gtflrfgsyj.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xuetiantiany.cn/Article/details/gtfypwfznz.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yj20258888.top/Article/details/gtncilhvny.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.9152youxi.cn/Article/details/gtdxvvebtv.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.svipenyu.cn/Article/details/gtaxmfrloe.html

[E19] 多行文本按行拆分
来源：http://dali.sweek.top/Article/details/gtvbyqitpx.html

Py:   s.splitlines()
来源：http://dali.xziqi.cn/Article/details/gtmlkxrkda.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jinqigufen.top/Article/details/gtovstixua.html

JS:   s.split(/\r?\n/)
来源：http://dali.cdnleiting.top/Article/details/gtbdzjsfkh.html

TS:   s.split(/\r?\n/)
来源：http://dali.yj202588.top/Article/details/gttgddcmhv.html

Java: s.lines().toList()
来源：http://dali.yonumen.top/Article/details/gtofdgtjnw.html

Go:   strings.Split(s, "\n")
来源：http://dali.sysykeji.top/Article/details/gtegwdqyav.html

Ruby: s.lines
来源：http://dali.zhixingplan.top/Article/details/gtovfizykr.html

C#:   s.Split('\n')
来源：http://dali.pengpengdd.cyou/Article/details/gtxzybwbks.html

[E20] 判断字符串是否为空
来源：http://dali.yonumen.top/Article/details/gtinqsqnxc.html

Py:   if not s:
来源：http://dali.nanxuanxn.top/Article/details/gtgcszoofu.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.cucudq.cn/Article/details/gtgugdloia.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yvedp.cn/Article/details/gtqupglwdl.html

TS:   if (s === "") {}
来源：http://dali.vqdsnc.cn/Article/details/gtfmhhjnlv.html

Java: if (s.isEmpty()) {}
来源：http://dali.sysykeji.top/Article/details/gtkwzbfzte.html

Go:   if s == "" {}
来源：http://dali.zhiwuduotai.top/Article/details/gtbhzskqqv.html

Ruby: if s.empty?
来源：http://dali.jiagoushi.top/Article/details/gtolvwbvuc.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtzojyjnbo.html

[E21] 超长截断加省略号
来源：http://dali.dianchejie.cn/Article/details/gtydimotkp.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.tian-w.cn/Article/details/gtztdykkvs.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.daria6918.cn/Article/details/gtfmhjobfu.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.fzhhl.top/Article/details/gthihtsapf.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.fzhhl.top/Article/details/gtzhodyvqq.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jqgfzy.top/Article/details/gtmfnucohn.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhoulong.xyz/Article/details/gtvilgufqv.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnlxfaudv.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.quarkkingdee.top/Article/details/gtcmaclznu.html

[E22] 字节长度与字符长度
来源：http://dali.haohaochexian.top/Article/details/gtjmzxnmbj.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.haohaochexian.top/Article/details/gtsbidnbvh.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.nanxuanxn.top/Article/details/gtustpgkjx.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sweek.top/Article/details/gtdgjrybnm.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hnqzz.top/Article/details/gtjpedokmf.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.kuanghao11.cn/Article/details/gtlijufxar.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.sysykeji.top/Article/details/gtjpgujtyv.html

Ruby: s.bytesize;  s.length
来源：http://dali.shzxlz.cn/Article/details/gtjhbrbvei.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.shangyingyoupin.top/Article/details/gttnvsrlzz.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtxcaijcnb.html

F. 文件与目录
来源：http://dali.jiagoushi.top/Article/details/gtejpzbjbq.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtoafukmet.html

[F01] 读取整个文件
来源：http://dali.bjfxy.top/Article/details/gtgzrhhfyk.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.xuetiantiany.cn/Article/details/gtwgumaofe.html

PHP:  file_get_contents("a.txt");
来源：http://dali.ydzc1.top/Article/details/gtdbkjekvt.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yj20258888.top/Article/details/gtnezxspvj.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yangfankeji.com/Article/details/gtfakttcmn.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hammf.cn/Article/details/gtlneglfzh.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yangfankeji.com/Article/details/gttokhxukj.html

Ruby: File.read("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtanhgfpwj.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gtcgvcdlqn.html

[F02] 逐行读取文件
来源：http://dali.yuanzhike.top/Article/details/gtehnrwqpf.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.chenjidiqi.icu/Article/details/gtiasrtxxt.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xziqi.cn/Article/details/gtpcsuuaoa.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yuanzhike.top/Article/details/gtuciyoqln.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xziqi.cn/Article/details/gthhzaymkm.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zdqjudy.top/Article/details/gtzlahhvpz.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.cqqwz.cn/Article/details/gtzwlpcvjy.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.haohaochexian.top/Article/details/gtrarpozey.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.shangyingyoupin.top/Article/details/gtfnnppqvh.html

[F03] 写入文件（覆盖）
来源：http://dali.sufxvd.cn/Article/details/gtuguaeheu.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.cucudq.cn/Article/details/gtaikpgqgz.html


<!-- 参考信息 -->