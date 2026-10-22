代发 wailian999

[D19] 按字段分组
来源：http://dali.tianlin.xyz/Article/details/gt2vzsyexbm.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.wangdashe.top/Article/details/gt2ozzbxxyb.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yongpay.top/Article/details/gt2omedrzzz.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.shzxlz.cn/Article/details/gt2rvyobehv.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.nanxuanxn.top/Article/details/gt2fqjacatb.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.ppjwa.cn/Article/details/gt2nxgqdjdu.html

Go:   // 手写 map[string][]T
来源：http://dali.aizwys.cn/Article/details/gt2fgecqddx.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.daxiang520.top/Article/details/gt2rvgkclnj.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhengqikj.top/Article/details/gt2nnqkbmrc.html

[D20] 统计每个元素出现次数
来源：http://dali.tian-w.cn/Article/details/gt2qwrkpcuo.html

Py:   Counter(arr)
来源：http://dali.tian-w.cn/Article/details/gt2wisfeebe.html

PHP:  array_count_values($arr);
来源：http://dali.yonumen.top/Article/details/gt2subthxom.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ppjwa.cn/Article/details/gt2okplsasj.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hysaishi.cn/Article/details/gt2ptpvtavs.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hywenlv.cn/Article/details/gt2mpdwefzy.html

Go:   // 手写 map[T]int
来源：http://dali.pycfn.com/Article/details/gt2mxexhxmp.html

Ruby: arr.tally
来源：http://dali.sxryk.cn/Article/details/gt2alvrmmnm.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jinqigufen.top/Article/details/gt2yaxsrgrt.html

[D21] 判断是否包含某元素
来源：http://dali.hnqzz.top/Article/details/gt2gymltsut.html

Py:   x in arr
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jfhphukg.html

PHP:  in_array($x, $arr, true);
来源：http://dali.fengsongda.top/Article/details/gt2kpulutbh.html

JS:   arr.includes(x)
来源：http://dali.jinqigufen.top/Article/details/gt2ceauknzs.html

TS:   arr.includes(x)
来源：http://dali.jinqigfzy.top/Article/details/gt2iyopzqoe.html

Java: list.contains(x)
来源：http://dali.gogol.net.cn/Article/details/gt2uazeciso.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhoulong.xyz/Article/details/gt2isgvrema.html

Ruby: arr.include?(x)
来源：http://dali.hnqzz.top/Article/details/gt2wyqhamzf.html

C#:   list.Contains(x)
来源：http://dali.vqdsnc.cn/Article/details/gt2pqxysyfl.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yanxiufei.cn/Article/details/gt2joiilcvb.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhengqikj.top/Article/details/gt2ntueazjg.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yj20258888.top/Article/details/gt2tstbnsfx.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhengqikj.top/Article/details/gt2xnylaomy.html

TS:   [...arr];
来源：http://dali.sufxvd.cn/Article/details/gt2zjefbsag.html

Java: new ArrayList<>(list);
来源：http://dali.mhx1999.top/Article/details/gt2woqcqdpg.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2beoonmsa.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zycfv.cn/Article/details/gt2kzwdgghr.html

C#:   new List<int>(list);
来源：http://dali.wangshuangyany.cn/Article/details/gt2szbvvjtr.html

[D23] reduce 累积计算
来源：http://dali.aibaodan.cn/Article/details/gt2rhuqpcww.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yuanzhike.top/Article/details/gt2qtwtnbhw.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.pycfn.com/Article/details/gt2fxaicnyg.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gt2stxnpicw.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.aibaodan.cn/Article/details/gt2afbojjwh.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.gotoacloud.top/Article/details/gt2fcurrbhm.html

Go:   // 手写循环
来源：http://dali.zhixingplan.top/Article/details/gt2movwxfqy.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.tianlin.xyz/Article/details/gt2wjwgvous.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yongpay.top/Article/details/gt2tzupqgza.html

[D24] 字典 / Map 基本操作
来源：http://dali.sxryk.cn/Article/details/gt2vaevwgqt.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.fzhhl.top/Article/details/gt2kcncefto.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.shangyingyoupin.top/Article/details/gt2hnujgupt.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sjrfcnqa.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.dashuyun.cn/Article/details/gt2eyhkmrpo.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.wangshuangyany.cn/Article/details/gt2sxeltgcm.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.snrcjt.cn/Article/details/gt2lhwbsdkl.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jlsjyb.cn/Article/details/gt2mndsljnn.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.hywenlv.cn/Article/details/gt2ndrdgbfg.html

[D25] Set 集合去重与交并差
来源：http://dali.yj202588.top/Article/details/gt2gxgwhfyh.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.mhx1999.top/Article/details/gt2fibzvypu.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.smart0.xyz/Article/details/gt2ekepvjsm.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.meibo888.top/Article/details/gt2eibvhxhj.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.aizwys.cn/Article/details/gt2ahenfwjg.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ahpwmqab.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.chenlongwang.top/Article/details/gt2aynpoulo.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.bjfxy.top/Article/details/gt2umfywgst.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.tianlin.xyz/Article/details/gt2ivtduykk.html

[D26] 数组转字符串
来源：http://dali.jqgufenzy.top/Article/details/gt2jceikqqo.html

Py:   ", ".join(map(str, arr))
来源：http://dali.svipenyu.cn/Article/details/gt2otinrkxb.html

PHP:  implode(", ", $arr);
来源：http://dali.yonumen.top/Article/details/gt2vfszhbtu.html

JS:   arr.join(", ")
来源：http://dali.xuanzx.com/Article/details/gt2avcrbogo.html

TS:   arr.join(", ")
来源：http://dali.guowangkeji.top/Article/details/gt2dtsluvkt.html

Java: String.join(", ", list)
来源：http://dali.xziqi.cn/Article/details/gt2whprdoad.html

Go:   strings.Join(strs, ", ")
来源：http://dali.meibo888.top/Article/details/gt2heaeixru.html

Ruby: arr.join(", ")
来源：http://dali.jyoumei.cn/Article/details/gt2qhctarse.html

C#:   string.Join(", ", list)
来源：http://dali.nanxuanxn.top/Article/details/gt2mdmsxazi.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2ehcithdu.html

E. 字符串处理
来源：http://dali.pengpengdd.cyou/Article/details/gt2dqgyxjpd.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2wzgvnwbl.html

[E01] 拼接字符串
来源：http://dali.ppjwa.cn/Article/details/gt2ruwlnubf.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hammf.cn/Article/details/gt2erfbmauq.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.9152youxi.cn/Article/details/gt2lyfojmbf.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hywenlv.cn/Article/details/gt2fvnllwcu.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jyoumei.cn/Article/details/gt2vucxafgc.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.sufxvd.cn/Article/details/gt2drbaydpm.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.nanxuanxn.top/Article/details/gt2dwzlpdqz.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.daxiang520.top/Article/details/gt2sognjqyj.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.hfpthk.cn/Article/details/gt2ixwrxtjx.html

[E02] 重复字符串
来源：http://dali.haohaochexian.top/Article/details/gt2ifzejsoz.html

Py:   "ab" * 3
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eswcgfve.html

PHP:  str_repeat("ab", 3);
来源：http://dali.vqdsnc.cn/Article/details/gt2uacodiwn.html

JS:   "ab".repeat(3)
来源：http://dali.tian-w.cn/Article/details/gt2udmknuep.html

TS:   "ab".repeat(3)
来源：http://dali.nanxinkj.top/Article/details/gt2qruibejm.html

Java: "ab".repeat(3)
来源：http://dali.havefunace.top/Article/details/gt2dqkefcho.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.shuidangran.top/Article/details/gt2lqanfkiy.html

Ruby: "ab" * 3
来源：http://dali.jlsjyb.cn/Article/details/gt2yniltins.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yvedp.cn/Article/details/gt2vmdbvzkj.html

[E03] 截取子串
来源：http://dali.hnxiangtu.top/Article/details/gt2yfwhuxhu.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.dashuyun.cn/Article/details/gt2ynqjfqxf.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hpobtvzb.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.daxiang520.top/Article/details/gt2vixpmmky.html

TS:   s.slice(1, 4)
来源：http://dali.zycfv.cn/Article/details/gt2jpckyjjj.html

Java: s.substring(1, 4)
来源：http://dali.cucudq.cn/Article/details/gt2yxqymdlv.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.dianchejie.cn/Article/details/gt2gjqqkpkj.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.vqdsnc.cn/Article/details/gt2xtaeauai.html

C#:   s.Substring(1, 3)
来源：http://dali.sxryk.cn/Article/details/gt2ltccalhs.html

[E04] 查找子串位置
来源：http://dali.wangdashe.top/Article/details/gt2csqbqooj.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhiwuduotai.top/Article/details/gt2rfvikbfj.html

PHP:  strpos($s, "x");
来源：http://dali.fengsongda.top/Article/details/gt2haqphmbb.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.xylfe.cn/Article/details/gt2dmisczwg.html

TS:   s.indexOf("x")
来源：http://dali.hfpthk.cn/Article/details/gt2pjkdsqxm.html

Java: s.indexOf("x")
来源：http://dali.jianghu66.top/Article/details/gt2jexgszyr.html

Go:   strings.Index(s, "x")
来源：http://dali.gzhubu.top/Article/details/gt2oahoqbos.html

Ruby: s.index("x")
来源：http://dali.jyoumei.cn/Article/details/gt2gzidckdi.html

C#:   s.IndexOf("x")
来源：http://dali.jiagoushi.top/Article/details/gt2ityoahdw.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.xuetiantiany.cn/Article/details/gt2srdgytkn.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.bjfxy.top/Article/details/gt2jmkbnikr.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yonumen.top/Article/details/gt2eaycfahz.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.nanxinkj.top/Article/details/gt2kcrkwbsf.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.cheryme.top/Article/details/gt2fmlqewxy.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhongyouzk.top/Article/details/gt2gbnpmqcq.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yanxiufei.cn/Article/details/gt2bbzjffzm.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.pycfn.com/Article/details/gt2zasmtfgv.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.pycfn.com/Article/details/gt2momopugk.html

[E06] 替换子串
来源：http://dali.dianchejie.cn/Article/details/gt2doaqepjy.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.xylfe.cn/Article/details/gt2onxwgbsd.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.shzxlz.cn/Article/details/gt2cgmdijzv.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gzhubu.top/Article/details/gt2aohsjlvj.html

TS:   s.replaceAll("a", "b")
来源：http://dali.ydzc1.top/Article/details/gt2kyzjfzya.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cucudq.cn/Article/details/gt2xpeoytxj.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ekuvcnjz.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gt2fohrdplq.html

C#:   s.Replace("a", "b")
来源：http://dali.hnqzz.top/Article/details/gt2kvbuliwo.html

[E07] 按分隔符拆分
来源：http://dali.dashuyun.cn/Article/details/gt2ikwcepji.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.svipenyu.cn/Article/details/gt2lbqnsech.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jinqigfzy.top/Article/details/gt2lpreacxc.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.cashguo.top/Article/details/gt2ildkrevp.html

TS:   s.split(",")
来源：http://dali.jyoumei.cn/Article/details/gt2zrebluqe.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yuxming.cn/Article/details/gt2avikctzg.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.redwolf501.top/Article/details/gt2zxpmvobm.html

Ruby: s.split(",");  s.split
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tivlznfs.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yanxiufei.cn/Article/details/gt2cavlejhd.html

[E08] 数组按分隔符合并
来源：http://dali.hnqzz.top/Article/details/gt2jthagtyv.html

Py:   ",".join(items)
来源：http://dali.chenlongwang.top/Article/details/gt2fsgzoqsy.html

PHP:  implode(",", $items);
来源：http://dali.xziqi.cn/Article/details/gt2rdzbbdpp.html

JS:   items.join(",")
来源：http://dali.wangshuangyany.cn/Article/details/gt2yidirbsd.html

TS:   items.join(",")
来源：http://dali.chenlongwang.top/Article/details/gt2sjpmhgpg.html

Java: String.join(",", items)
来源：http://dali.yangfankeji.com/Article/details/gt2pghrymay.html

Go:   strings.Join(items, ",")
来源：http://dali.ivvv.top/Article/details/gt2ujrxzjfe.html

Ruby: items.join(",")
来源：http://dali.bjfxy.top/Article/details/gt2ewhnslcx.html

C#:   string.Join(",", items)
来源：http://dali.yanxiufei.cn/Article/details/gt2bdgflasw.html

[E09] 去除所有空白字符
来源：http://dali.xziqi.cn/Article/details/gt2idzfkkmp.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ippjecdk.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.aibaodan.cn/Article/details/gt2jlhzxqkt.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.sweek.top/Article/details/gt2nlgxxymf.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.bjfxy.top/Article/details/gt2jolbbeoz.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.haohaochexian.top/Article/details/gt2hmdvmapq.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yuxming.cn/Article/details/gt2ppuwlilo.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yangfankeji.com/Article/details/gt2mcyciicf.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhiwuduotai.top/Article/details/gt2pjeriykb.html

[E10] 左侧补零 / 定长填充
来源：http://dali.dianchejie.cn/Article/details/gt2ggcvvgxx.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yj20258.top/Article/details/gt2rculgyiz.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.feifeiyinyue.top/Article/details/gt2fpdtmuxv.html

JS:   "7".padStart(3, "0")
来源：http://dali.hnqzz.top/Article/details/gt2grrsmbtm.html

TS:   "7".padStart(3, "0")
来源：http://dali.ivvv.top/Article/details/gt2ztmqjvow.html

Java: String.format("%03d", 7)
来源：http://dali.tianlin.xyz/Article/details/gt2uouddgdv.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.xziqi.cn/Article/details/gt2uhwvuulk.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jinqigufen.top/Article/details/gt2ksvqthsu.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.xinyue.icu/Article/details/gt2eskewysp.html

[E11] 反转字符串
来源：http://dali.chenlongwang.top/Article/details/gt2agcibtcv.html

Py:   s[::-1]
来源：http://dali.vqdsnc.cn/Article/details/gt2zktpijvb.html

PHP:  strrev($s);
来源：http://dali.quarkkingdee.top/Article/details/gt2ozycuofs.html

JS:   [...s].reverse().join("")
来源：http://dali.dianchejie.cn/Article/details/gt2hqnnkftx.html

TS:   [...s].reverse().join("")
来源：http://dali.haohaochexian.top/Article/details/gt2fyetkwln.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.ydzc1.top/Article/details/gt2hdhfkmpy.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yanxiufei.cn/Article/details/gt2axjclvon.html

Ruby: s.reverse
来源：http://dali.shzxlz.cn/Article/details/gt2hsbjnyks.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hywenlv.cn/Article/details/gt2pkhqnuss.html

[E12] 统计某字符出现次数
来源：http://dali.birdmap.top/Article/details/gt2wuqizzbh.html

Py:   s.count("a")
来源：http://dali.nwbrower.top/Article/details/gt2irahkjnx.html

PHP:  substr_count($s, "a");
来源：http://dali.bjfxy.top/Article/details/gt2rmxwpedi.html

JS:   s.split("a").length - 1
来源：http://dali.zycfv.cn/Article/details/gt2meppvefe.html

TS:   s.split("a").length - 1
来源：http://dali.snrcjt.cn/Article/details/gt2xfhothov.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.fzhhl.top/Article/details/gt2ocsmtxgn.html

Go:   strings.Count(s, "a")
来源：http://dali.quarkkingdee.top/Article/details/gt2ihettexw.html

Ruby: s.count("a")
来源：http://dali.smart0.xyz/Article/details/gt2uevcvzvb.html

C#:   s.Count(c => c == 'a')
来源：http://dali.nanxinkj.top/Article/details/gt2mffqdbhk.html

[E13] 逐字符遍历
来源：http://dali.yueranfly.top/Article/details/gt2vstcstxo.html

Py:   for ch in s: print(ch)
来源：http://dali.gogol.net.cn/Article/details/gt2tdakmwdp.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.cqqwz.cn/Article/details/gt2bqlhddlt.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinqigfzy.top/Article/details/gt2cdwzxmal.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lzzpgmdi.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhengqikj.top/Article/details/gt2upazdebg.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.meibo888.top/Article/details/gt2vijixqbf.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.gotoacloud.top/Article/details/gt2cewxvvyk.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.xylfe.cn/Article/details/gt2dfcnhhmi.html

[E14] URL 编码与 Base64
来源：http://dali.wangdashe.top/Article/details/gt2yidpypdd.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.pengpengdd.cyou/Article/details/gt2ybrvgmms.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.snrcjt.cn/Article/details/gt2sadsihsc.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.c1oappe.top/Article/details/gt2gremtelp.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.hammf.cn/Article/details/gt2vmjcauqr.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.guannengcc.top/Article/details/gt2mlinaibs.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.xylfe.cn/Article/details/gt2cueyerba.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.316326.xyz/Article/details/gt2kfqepzif.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.redwolf501.top/Article/details/gt2blaxpsrh.html

[E15] HTML 转义 / 反转义
来源：http://dali.yj20258.top/Article/details/gt2jvdekogl.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ifttmccd.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hammf.cn/Article/details/gt2hoiknoef.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.aibaodan.cn/Article/details/gt2irrdfcyt.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.nwbrower.top/Article/details/gt2ftufhkac.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yonumen.top/Article/details/gt2dmgklywb.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xuanzx.com/Article/details/gt2izolnxoq.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.shuidangran.top/Article/details/gt2dirmuyfy.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ltpvgefa.html

[E16] 数字千分位
来源：http://dali.aizwys.cn/Article/details/gt2oarsjukw.html

Py:   f"{1234567:,}"
来源：http://dali.gaohongyu789.top/Article/details/gt2ocgkmbse.html

PHP:  number_format(1234567);
来源：http://dali.nanxuanxn.top/Article/details/gt2pthzwlaj.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.cashguo.top/Article/details/gt2lqxntdli.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.chenzaomai.com/Article/details/gt2nwchbpri.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.sweek.top/Article/details/gt2prbqlaya.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jqgfzy.top/Article/details/gt2bwzsuboc.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yj20258.top/Article/details/gt2etpfgbto.html

C#:   1234567.ToString("N0")
来源：http://dali.cdnleiting.top/Article/details/gt2kazebrsk.html

[E17] 首字母大写
来源：http://dali.xylfe.cn/Article/details/gt2kuqfrnpl.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hammf.cn/Article/details/gt2amjdralz.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.birdmap.top/Article/details/gt2pexhmpfc.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ordtmwoo.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.vqdsnc.cn/Article/details/gt2awaluhtp.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.cqqwz.cn/Article/details/gt2knpeeqlt.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.cheryme.top/Article/details/gt2isovenoc.html

Ruby: s.capitalize
来源：http://dali.yuxming.cn/Article/details/gt2ezrjkxxc.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.redwolf501.top/Article/details/gt2vdpknecy.html

[E18] 模板占位符替换
来源：http://dali.jinqigfzy.top/Article/details/gt2gpdyftyy.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gpymhssh.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.redwolf501.top/Article/details/gt2sgcwceal.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yangfankeji.com/Article/details/gt2leiwaili.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yongpay.top/Article/details/gt2rslvwsit.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.wangdashe.top/Article/details/gt2zurtaiwx.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.gotoacloud.top/Article/details/gt2rsbtfebi.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jqgufenzy.top/Article/details/gt2onzsoklu.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.xinyue.icu/Article/details/gt2jtjeqnie.html

[E19] 多行文本按行拆分
来源：http://dali.wangshuangyany.cn/Article/details/gt2becxdlsm.html

Py:   s.splitlines()
来源：http://dali.aibaodan.cn/Article/details/gt2srgmfepb.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jlivkndn.html

JS:   s.split(/\r?\n/)
来源：http://dali.jqgfzy.top/Article/details/gt2hndvubbw.html

TS:   s.split(/\r?\n/)
来源：http://dali.yj20258.top/Article/details/gt2dgywexnq.html

Java: s.lines().toList()
来源：http://dali.feifeiyinyue.top/Article/details/gt2tgjgxeec.html

Go:   strings.Split(s, "\n")
来源：http://dali.sweek.top/Article/details/gt2pllsjonr.html

Ruby: s.lines
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2coajdcpw.html

C#:   s.Split('\n')
来源：http://dali.kuanghao11.cn/Article/details/gt2hdgtypxs.html

[E20] 判断字符串是否为空
来源：http://dali.yj20258.top/Article/details/gt2zscovimu.html

Py:   if not s:
来源：http://dali.hnxiangtu.top/Article/details/gt2sfgvyvbp.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.chenlongwang.top/Article/details/gt2ikkkggag.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.ivvv.top/Article/details/gt2xxmyoidq.html

TS:   if (s === "") {}
来源：http://dali.bjfxy.top/Article/details/gt2gjxcaihp.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2otcvllge.html

Go:   if s == "" {}
来源：http://dali.xuanzx.com/Article/details/gt2zdgwmdcn.html

Ruby: if s.empty?
来源：http://dali.jyoumei.cn/Article/details/gt2ncwomghd.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2vxitvais.html

[E21] 超长截断加省略号
来源：http://dali.tianlin.xyz/Article/details/gt2hoimyxhm.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.bjfxy.top/Article/details/gt2qbjibfey.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.316326.xyz/Article/details/gt2qeqwcgog.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yj20258.top/Article/details/gt2thuyyrmm.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hysaishi.cn/Article/details/gt2rlehenwi.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.cucudq.cn/Article/details/gt2pfpqvazz.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yj202588.top/Article/details/gt2jmaezsmq.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xuanzx.com/Article/details/gt2qyrmphll.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.ppjwa.cn/Article/details/gt2tvmvzraa.html

[E22] 字节长度与字符长度
来源：http://dali.yj20258888.top/Article/details/gt2samqllvq.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xziqi.cn/Article/details/gt2hldjwqug.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gaohongyu789.top/Article/details/gt2javkchmh.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sxryk.cn/Article/details/gt2ugqkweeo.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shangyingyoupin.top/Article/details/gt2jrhuidls.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.birdmap.top/Article/details/gt2wdxwakzm.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.dianchejie.cn/Article/details/gt2pofenlfr.html

Ruby: s.bytesize;  s.length
来源：http://dali.316326.xyz/Article/details/gt2tuhkhhye.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.hfpthk.cn/Article/details/gt2iamkfuso.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2svjeaagg.html

F. 文件与目录
来源：http://dali.aizwys.cn/Article/details/gt2gltiuuhf.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2yloytscy.html

[F01] 读取整个文件
来源：http://dali.xziqi.cn/Article/details/gt2ncjhetih.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yuanzhike.top/Article/details/gt2fkezkjpj.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gt2dkneihsa.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhongyouzk.top/Article/details/gt2efpvfdfp.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.gaohongyu789.top/Article/details/gt2dbcukfbn.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.svipenyu.cn/Article/details/gt2sytbuewo.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.birdmap.top/Article/details/gt2vhovqsej.html

Ruby: File.read("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2gcfyxigs.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gt2cqdsoqsg.html

[F02] 逐行读取文件
来源：http://dali.xziqi.cn/Article/details/gt2srcnwtum.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.316326.xyz/Article/details/gt2lidftfvy.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2svjojsmc.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.bjfxy.top/Article/details/gt2niozjrsk.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shzxlz.cn/Article/details/gt2usutsptk.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.xylfe.cn/Article/details/gt2ateazflm.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yj20258.top/Article/details/gt2tdnokoer.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yjvgaesz.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xinyue.icu/Article/details/gt2ebnhzcep.html

[F03] 写入文件（覆盖）
来源：http://dali.ehwqpu.com/Article/details/gt2tpvneiip.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.chenlongwang.top/Article/details/gt2gjysugbn.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ybcxt.top/Article/details/gt2sjcryxeg.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.guannengcc.top/Article/details/gt2cadojozu.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinqigufen.top/Article/details/gt2lnlbtwue.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.cqqwz.cn/Article/details/gt2qzbdrmgs.html


<!-- 参考信息 -->