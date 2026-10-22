代发 wailian999

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.cqqwz.cn/Article/details/gt2jhlbcpyf.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhiwuduotai.top/Article/details/gt2gnhnifrd.html

Go:   // 手写 map[string][]T
来源：http://dali.cashguo.top/Article/details/gt2gibnxcop.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.ivvv.top/Article/details/gt2jimktuha.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.gotoacloud.top/Article/details/gt2fvkjqmjw.html

[D20] 统计每个元素出现次数
来源：http://dali.xinyue.icu/Article/details/gt2qwxqilwq.html

Py:   Counter(arr)
来源：http://dali.jiagoushi.top/Article/details/gt2tuaceekf.html

PHP:  array_count_values($arr);
来源：http://dali.yvedp.cn/Article/details/gt2yugbbgnq.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.mhx1999.top/Article/details/gt2nunjsciv.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.smart0.xyz/Article/details/gt2xrmdvohc.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ewnguoth.html

Go:   // 手写 map[T]int
来源：http://dali.sweek.top/Article/details/gt2wniwogoe.html

Ruby: arr.tally
来源：http://dali.zhixingplan.top/Article/details/gt2annfjkvs.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.tianlin.xyz/Article/details/gt2ggwrmvtr.html

[D21] 判断是否包含某元素
来源：http://dali.yonumen.top/Article/details/gt2rxgrwebn.html

Py:   x in arr
来源：http://dali.guowangkeji.top/Article/details/gt2jbtjcaqq.html

PHP:  in_array($x, $arr, true);
来源：http://dali.sysykeji.top/Article/details/gt2qgptqepv.html

JS:   arr.includes(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ezhzyxxl.html

TS:   arr.includes(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jjmtvnnc.html

Java: list.contains(x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2rvapkftm.html

Go:   slices.Contains(arr, x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2mtflhrme.html

Ruby: arr.include?(x)
来源：http://dali.wangshuangyany.cn/Article/details/gt2pwwbdspj.html

C#:   list.Contains(x)
来源：http://dali.vqdsnc.cn/Article/details/gt2ibuquxqn.html

[D22] 复制数组（避免共享引用）
来源：http://dali.fzhhl.top/Article/details/gt2ngeoveiq.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.guowangkeji.top/Article/details/gt2wxvquhfs.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.nanxuanxn.top/Article/details/gt2kayqhjug.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.sufxvd.cn/Article/details/gt2evlswlmk.html

TS:   [...arr];
来源：http://dali.bjfxy.top/Article/details/gt2cmxwyhtm.html

Java: new ArrayList<>(list);
来源：http://dali.jyoumei.cn/Article/details/gt2euixktaz.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jianghu66.top/Article/details/gt2rtpiuhpt.html

Ruby: arr.dup;  arr.clone
来源：http://dali.daria6918.cn/Article/details/gt2kxcboajv.html

C#:   new List<int>(list);
来源：http://dali.jinqigfzy.top/Article/details/gt2kpjupjcd.html

[D23] reduce 累积计算
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qcfmgrtc.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.ehwqpu.com/Article/details/gt2vjpzokpc.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yuanzhike.top/Article/details/gt2bmpzidof.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.0kj1m.cn/Article/details/gt2rgjcfvdw.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gt2aqfwxjtn.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vtuhelyv.html

Go:   // 手写循环
来源：http://dali.jinqigfzy.top/Article/details/gt2ybjjcfgq.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.sweek.top/Article/details/gt2fcovyfug.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.hysaishi.cn/Article/details/gt2dknkbbjj.html

[D24] 字典 / Map 基本操作
来源：http://dali.smart0.xyz/Article/details/gt2sijfrqlb.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhiwuduotai.top/Article/details/gt2fixafyve.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.daxiang520.top/Article/details/gt2ggdaderf.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.bjfxy.top/Article/details/gt2magpmhbb.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.mhx1999.top/Article/details/gt2lviddqlj.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.sufxvd.cn/Article/details/gt2dpujctpi.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhengqikj.top/Article/details/gt2csxbkrjl.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.havefunace.top/Article/details/gt2wqlcynym.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.9152youxi.cn/Article/details/gt2zidongfr.html

[D25] Set 集合去重与交并差
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2voadahkq.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jqgufenzy.top/Article/details/gt2xoafmhka.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.nwbrower.top/Article/details/gt2djaoozej.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ldqovlav.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jyoumei.cn/Article/details/gt2latlcxbu.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jinqigfzy.top/Article/details/gt2efhzepwt.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jyoumei.cn/Article/details/gt2qznjiuie.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jianghu66.top/Article/details/gt2zztewlrn.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hysaishi.cn/Article/details/gt2zsmdgobx.html

[D26] 数组转字符串
来源：http://dali.ybcxt.top/Article/details/gt2ggdvxfqp.html

Py:   ", ".join(map(str, arr))
来源：http://dali.daria6918.cn/Article/details/gt2hptmgmvc.html

PHP:  implode(", ", $arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hwnpodzt.html

JS:   arr.join(", ")
来源：http://dali.jlsjyb.cn/Article/details/gt2ushnwupt.html

TS:   arr.join(", ")
来源：http://dali.chenlongwang.top/Article/details/gt2qbupfipd.html

Java: String.join(", ", list)
来源：http://dali.daria6918.cn/Article/details/gt2xwmmvrpl.html

Go:   strings.Join(strs, ", ")
来源：http://dali.nanxinkj.top/Article/details/gt2zndtbnrj.html

Ruby: arr.join(", ")
来源：http://dali.ivvv.top/Article/details/gt2skzgboho.html

C#:   string.Join(", ", list)
来源：http://dali.yanxiufei.cn/Article/details/gt2bzyymfrl.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2pfzwokue.html

E. 字符串处理
来源：http://dali.gzhubu.top/Article/details/gt2lxqeislz.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2edszbqcm.html

[E01] 拼接字符串
来源：http://dali.yj202588.top/Article/details/gt2xhkmwoen.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.chenjidiqi.icu/Article/details/gt2zfxqopjo.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.dashuyun.cn/Article/details/gt2jnqvsobe.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hysaishi.cn/Article/details/gt2kihelhac.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hnqzz.top/Article/details/gt2lgpzaezm.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.chenlongwang.top/Article/details/gt2ueqrszdw.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.gotoacloud.top/Article/details/gt2iucoqxln.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.chenjidiqi.icu/Article/details/gt2loqlytez.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.snrcjt.cn/Article/details/gt2ekoupinz.html

[E02] 重复字符串
来源：http://dali.xziqi.cn/Article/details/gt2netvqkfb.html

Py:   "ab" * 3
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uynxqyaz.html

PHP:  str_repeat("ab", 3);
来源：http://dali.andypj.xyz/Article/details/gt2sjlxdrzt.html

JS:   "ab".repeat(3)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ksrrubzo.html

TS:   "ab".repeat(3)
来源：http://dali.hnxiangtu.top/Article/details/gt2jlluifcw.html

Java: "ab".repeat(3)
来源：http://dali.jiagoushi.top/Article/details/gt2hnspxjvh.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mqwuyqtc.html

Ruby: "ab" * 3
来源：http://dali.cheryme.top/Article/details/gt2zrycaxvq.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.dashuyun.cn/Article/details/gt2cffemnns.html

[E03] 截取子串
来源：http://dali.aizwys.cn/Article/details/gt2vuigsjvh.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhongyouzk.top/Article/details/gt2gsdlfogw.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhongyouzk.top/Article/details/gt2waojmcyb.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jinqigfzy.top/Article/details/gt2ubqorbyu.html

TS:   s.slice(1, 4)
来源：http://dali.jinqigfzy.top/Article/details/gt2srtotgmw.html

Java: s.substring(1, 4)
来源：http://dali.jiagoushi.top/Article/details/gt2ofbhfmto.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhoulong.xyz/Article/details/gt2wdrplyug.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.cqqwz.cn/Article/details/gt2grxeyunk.html

C#:   s.Substring(1, 3)
来源：http://dali.hnxiangtu.top/Article/details/gt2ojbuxklm.html

[E04] 查找子串位置
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lsktnuwv.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zdqjudy.top/Article/details/gt2qekpmzca.html

PHP:  strpos($s, "x");
来源：http://dali.hywenlv.cn/Article/details/gt2hfgzgcos.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lcxmsmoy.html

TS:   s.indexOf("x")
来源：http://dali.zycfv.cn/Article/details/gt2uxhiuplu.html

Java: s.indexOf("x")
来源：http://dali.tian-w.cn/Article/details/gt2yqgixxsf.html

Go:   strings.Index(s, "x")
来源：http://dali.ybcxt.top/Article/details/gt2nlkvgrat.html

Ruby: s.index("x")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xautarqt.html

C#:   s.IndexOf("x")
来源：http://dali.jlsjyb.cn/Article/details/gt2xjqmylkj.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.dashuyun.cn/Article/details/gt2oeehanku.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.tianlin.xyz/Article/details/gt2wbvzaybf.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.sysykeji.top/Article/details/gt2vjhqiuhs.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinqigfzy.top/Article/details/gt2clinzzkk.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.tian-w.cn/Article/details/gt2wilqvdbd.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.wangdashe.top/Article/details/gt2eausmtla.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.aibaodan.cn/Article/details/gt2houwldly.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2coblxkuc.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.xuanzx.com/Article/details/gt2ogrnyzwr.html

[E06] 替换子串
来源：http://dali.zhiwuduotai.top/Article/details/gt2kjpbuneu.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jinqigfzy.top/Article/details/gt2wtnfgxql.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.andypj.xyz/Article/details/gt2taqqwcdd.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xinyue.icu/Article/details/gt2eunabtzy.html

TS:   s.replaceAll("a", "b")
来源：http://dali.ybcxt.top/Article/details/gt2gapbvodf.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zdqjudy.top/Article/details/gt2uppyilnn.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zdqjudy.top/Article/details/gt2cvqnxlew.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yueranfly.top/Article/details/gt2oiegsbwn.html

C#:   s.Replace("a", "b")
来源：http://dali.shuidangran.top/Article/details/gt2eybarkpq.html

[E07] 按分隔符拆分
来源：http://dali.birdmap.top/Article/details/gt2ategvxwl.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.vqdsnc.cn/Article/details/gt2tfxrqqle.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.shangyingyoupin.top/Article/details/gt2jjejtjik.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.kuanghao11.cn/Article/details/gt2huziksjx.html

TS:   s.split(",")
来源：http://dali.yuxming.cn/Article/details/gt2lfafogay.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.smart0.xyz/Article/details/gt2masgdgdj.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yj20258888.top/Article/details/gt2cwgwpkfh.html

Ruby: s.split(",");  s.split
来源：http://dali.hongshengwenyu.top/Article/details/gt2fcwfeojx.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhengqikj.top/Article/details/gt2hqpjulkb.html

[E08] 数组按分隔符合并
来源：http://dali.shzxlz.cn/Article/details/gt2lbyqxmjv.html

Py:   ",".join(items)
来源：http://dali.nwbrower.top/Article/details/gt2aivdrusu.html

PHP:  implode(",", $items);
来源：http://dali.zhoulong.xyz/Article/details/gt2tpolastb.html

JS:   items.join(",")
来源：http://dali.zhongyouzk.top/Article/details/gt2kgstvzlq.html

TS:   items.join(",")
来源：http://dali.gaohongyu789.top/Article/details/gt2nsxckidn.html

Java: String.join(",", items)
来源：http://dali.tianlin.xyz/Article/details/gt2sptxuyxy.html

Go:   strings.Join(items, ",")
来源：http://dali.bjfxy.top/Article/details/gt2oojllbpv.html

Ruby: items.join(",")
来源：http://dali.9152youxi.cn/Article/details/gt2kxmistgp.html

C#:   string.Join(",", items)
来源：http://dali.0kj1m.cn/Article/details/gt2xllshlvn.html

[E09] 去除所有空白字符
来源：http://dali.quarkkingdee.top/Article/details/gt2gxpxegiu.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yanxiufei.cn/Article/details/gt2nupkhtdz.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yj20258888.top/Article/details/gt2xjrxavco.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.shzxlz.cn/Article/details/gt2yjatnczm.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wztyndjo.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.ppjwa.cn/Article/details/gt2ijzzlnsv.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.cucudq.cn/Article/details/gt2twiiccbj.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.ybcxt.top/Article/details/gt2kxwfiite.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yonumen.top/Article/details/gt2okthssrr.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yonumen.top/Article/details/gt2uhxrucdm.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.sxryk.cn/Article/details/gt2newrduei.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lvwkiohv.html

JS:   "7".padStart(3, "0")
来源：http://dali.tian-w.cn/Article/details/gt2jjpoyfbe.html

TS:   "7".padStart(3, "0")
来源：http://dali.snrcjt.cn/Article/details/gt2fdkbsoqq.html

Java: String.format("%03d", 7)
来源：http://dali.chenjidiqi.icu/Article/details/gt2jfhjvlsb.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.chenjidiqi.icu/Article/details/gt2mzluhbzv.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.gogol.net.cn/Article/details/gt2srpqffqm.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.nanxuanxn.top/Article/details/gt2aogqmwdb.html

[E11] 反转字符串
来源：http://dali.daxiang520.top/Article/details/gt2usmrtwmi.html

Py:   s[::-1]
来源：http://dali.tanke756.top/Article/details/gt2uwvmglwq.html

PHP:  strrev($s);
来源：http://dali.tanke756.top/Article/details/gt2fpdpggsb.html

JS:   [...s].reverse().join("")
来源：http://dali.nwbrower.top/Article/details/gt2zixcyuvs.html

TS:   [...s].reverse().join("")
来源：http://dali.tianlin.xyz/Article/details/gt2edlegbqr.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.316326.xyz/Article/details/gt2hxaonkru.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yj20258888.top/Article/details/gt2lfmypwcg.html

Ruby: s.reverse
来源：http://dali.zdqjudy.top/Article/details/gt2uewhljxs.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.tian-w.cn/Article/details/gt2qewpvruf.html

[E12] 统计某字符出现次数
来源：http://dali.xinyue.icu/Article/details/gt2vsgstygk.html

Py:   s.count("a")
来源：http://dali.tian-w.cn/Article/details/gt2ucrurtjx.html

PHP:  substr_count($s, "a");
来源：http://dali.wangshuangyany.cn/Article/details/gt2tmncnktu.html

JS:   s.split("a").length - 1
来源：http://dali.tanke756.top/Article/details/gt2zzqtetih.html

TS:   s.split("a").length - 1
来源：http://dali.yonumen.top/Article/details/gt2snjnvaed.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.hnxiangtu.top/Article/details/gt2zsfdrhqj.html

Go:   strings.Count(s, "a")
来源：http://dali.pycfn.com/Article/details/gt2tkwhytkz.html

Ruby: s.count("a")
来源：http://dali.yuxming.cn/Article/details/gt2zinjhuyh.html

C#:   s.Count(c => c == 'a')
来源：http://dali.dianchejie.cn/Article/details/gt2zyctizrs.html

[E13] 逐字符遍历
来源：http://dali.yongpay.top/Article/details/gt2dyzuywjw.html

Py:   for ch in s: print(ch)
来源：http://dali.pengpengdd.cyou/Article/details/gt2auxdgjys.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.fzhhl.top/Article/details/gt2rthdhypp.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yuxming.cn/Article/details/gt2fyvohvzv.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jiagoushi.top/Article/details/gt2stsdadug.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.vqdsnc.cn/Article/details/gt2xopyynsm.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jinqigfzy.top/Article/details/gt2fewcbdoi.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.vqdsnc.cn/Article/details/gt2qynkkihh.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.meibo888.top/Article/details/gt2bgegkjgz.html

[E14] URL 编码与 Base64
来源：http://dali.daxiang520.top/Article/details/gt2kzxgcrsf.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zdqjudy.top/Article/details/gt2atlxhexp.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yj202588.top/Article/details/gt2uejhntyp.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.feifeiyinyue.top/Article/details/gt2syuhepmq.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2cdfdlyyl.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.ydzc1.top/Article/details/gt2bcyequxa.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.tianlin.xyz/Article/details/gt2xfmwzozt.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.nwbrower.top/Article/details/gt2bcsppwbn.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.tanke756.top/Article/details/gt2bsukukmc.html

[E15] HTML 转义 / 反转义
来源：http://dali.yonumen.top/Article/details/gt2eagdwjcc.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yj202588.top/Article/details/gt2mijslzrg.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.cashguo.top/Article/details/gt2kyegpbgu.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.vqdsnc.cn/Article/details/gt2nsgrwzef.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hongshengwenyu.top/Article/details/gt2ctksggjt.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yj202588.top/Article/details/gt2zdymzcqt.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yuxming.cn/Article/details/gt2qfwiyapz.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2drdlosfn.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yvedp.cn/Article/details/gt2ifaqvxfs.html

[E16] 数字千分位
来源：http://dali.cheryme.top/Article/details/gt2bfnvfpmn.html

Py:   f"{1234567:,}"
来源：http://dali.nwbrower.top/Article/details/gt2tlmuuzxl.html

PHP:  number_format(1234567);
来源：http://dali.feifeiyinyue.top/Article/details/gt2swolnrvk.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.hammf.cn/Article/details/gt2jrfrsmpi.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.nanxuanxn.top/Article/details/gt2gphbsgkq.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lebpufta.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.pycfn.com/Article/details/gt2yyzufxmp.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zwzlcwdd.html

C#:   1234567.ToString("N0")
来源：http://dali.cheryme.top/Article/details/gt2rnnktoip.html

[E17] 首字母大写
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ehajmvaj.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.dashuyun.cn/Article/details/gt2vqzhbktm.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.xylfe.cn/Article/details/gt2istwqyic.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.tanke756.top/Article/details/gt2pqtawsff.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhengqikj.top/Article/details/gt2ltzrsohn.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.gzhubu.top/Article/details/gt2htspvtbo.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2yfsmsavl.html

Ruby: s.capitalize
来源：http://dali.bjfxy.top/Article/details/gt2cmeafimq.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rnffgqzl.html

[E18] 模板占位符替换
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pqufrxrd.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.shzxlz.cn/Article/details/gt2woscsdqn.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hammf.cn/Article/details/gt2egfqqkfr.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.tianlin.xyz/Article/details/gt2mpulwqjd.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.smart0.xyz/Article/details/gt2mgruoqxn.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.sysykeji.top/Article/details/gt2uajoywyj.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.nanxuanxn.top/Article/details/gt2ztjdpnli.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.sxryk.cn/Article/details/gt2lnhhcbde.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yueranfly.top/Article/details/gt2qzehhzlg.html

[E19] 多行文本按行拆分
来源：http://dali.sysykeji.top/Article/details/gt2vbgugosl.html

Py:   s.splitlines()
来源：http://dali.xuetiantiany.cn/Article/details/gt2wyoixvnj.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bpfiqvew.html

JS:   s.split(/\r?\n/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xvvwnbne.html

TS:   s.split(/\r?\n/)
来源：http://dali.yueranfly.top/Article/details/gt2sxssivoq.html

Java: s.lines().toList()
来源：http://dali.daxiang520.top/Article/details/gt2gojtuosf.html

Go:   strings.Split(s, "\n")
来源：http://dali.cdnleiting.top/Article/details/gt2bnxsttzq.html

Ruby: s.lines
来源：http://dali.cqqwz.cn/Article/details/gt2hiorrecl.html

C#:   s.Split('\n')
来源：http://dali.sweek.top/Article/details/gt2efscsklw.html

[E20] 判断字符串是否为空
来源：http://dali.xinyue.icu/Article/details/gt2rzoitrqh.html

Py:   if not s:
来源：http://dali.nanxuanxn.top/Article/details/gt2srglxhve.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.gotoacloud.top/Article/details/gt2ipvbimqd.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.cqqwz.cn/Article/details/gt2iwpdoygj.html

TS:   if (s === "") {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sffrdtdq.html

Java: if (s.isEmpty()) {}
来源：http://dali.c1oappe.top/Article/details/gt2vsijsliv.html

Go:   if s == "" {}
来源：http://dali.xziqi.cn/Article/details/gt2ntufiftb.html

Ruby: if s.empty?
来源：http://dali.iojbl.cn/Article/details/gt2wismhuec.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.mhx1999.top/Article/details/gt2ngcvvvfl.html

[E21] 超长截断加省略号
来源：http://dali.jinghuilouyu.cn/Article/details/gt2finoshnd.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.sweek.top/Article/details/gt2evqcffuq.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.guannengcc.top/Article/details/gt2sikfkszl.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xinyue.icu/Article/details/gt2flolzcwa.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.feifeiyinyue.top/Article/details/gt2zmgwpqmo.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yrbiuwbl.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.sxryk.cn/Article/details/gt2tqjrqkoo.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yongpay.top/Article/details/gt2krchjgwn.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.sweek.top/Article/details/gt2dhkmcurs.html

[E22] 字节长度与字符长度
来源：http://dali.yj20258.top/Article/details/gt2zhqshxxo.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.c1oappe.top/Article/details/gt2qnuhurue.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jianghu66.top/Article/details/gt2vtmbfehn.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hysaishi.cn/Article/details/gt2fzrexsmy.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sxryk.cn/Article/details/gt2mnybpnwl.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.pycfn.com/Article/details/gt2ukzvklcv.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.xinyue.icu/Article/details/gt2xuibkrua.html

Ruby: s.bytesize;  s.length
来源：http://dali.gaohongyu789.top/Article/details/gt2odtmimoa.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.dashuyun.cn/Article/details/gt2mnvviydr.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2twdvxlnz.html

F. 文件与目录
来源：http://dali.jinqigfzy.top/Article/details/gt2cipxxdhx.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2hbvuuauq.html

[F01] 读取整个文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2xlglpyjy.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ehwqpu.com/Article/details/gt2bwuambxa.html

PHP:  file_get_contents("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2repldkjh.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.xuanzx.com/Article/details/gt2scsgnlmx.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yj20258.top/Article/details/gt2cetbmfcy.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.fengsongda.top/Article/details/gt2nczryogp.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhiwuduotai.top/Article/details/gt2xreatufx.html

Ruby: File.read("a.txt")
来源：http://dali.tian-w.cn/Article/details/gt2dyjvgzyi.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.cucudq.cn/Article/details/gt2sqesdset.html

[F02] 逐行读取文件
来源：http://dali.dashuyun.cn/Article/details/gt2uewsoejn.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.chenzaomai.com/Article/details/gt2ssujfmem.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.andypj.xyz/Article/details/gt2gcdftsuh.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2jpelojsp.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.daxiang520.top/Article/details/gt2qnxgqdpq.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.birdmap.top/Article/details/gt2wygsmhyc.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.svipenyu.cn/Article/details/gt2zgpclukn.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yongpay.top/Article/details/gt2dykmhkah.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.kuanghao11.cn/Article/details/gt2ygrlqimx.html

[F03] 写入文件（覆盖）
来源：http://dali.snrcjt.cn/Article/details/gt2fmwvwudn.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhengqikj.top/Article/details/gt2blybhgtu.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2supvxyqt.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.mhx1999.top/Article/details/gt2rcxwlwsd.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.guowangkeji.top/Article/details/gt2vtdrwfmz.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hnqzz.top/Article/details/gt2hwbnfdaj.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.guowangkeji.top/Article/details/gt2zldoptqr.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.kuanghao11.cn/Article/details/gt2odmwvjwo.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bmjfbdqr.html

[F04] 追加写入文件
来源：http://dali.jqgufenzy.top/Article/details/gt2ldlgxlmo.html


<!-- 参考信息 -->