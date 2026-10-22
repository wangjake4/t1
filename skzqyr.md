代发 wailian999

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.andypj.xyz/Article/details/gt2tsgdlfxg.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.c1oappe.top/Article/details/gt2wocyiteq.html

Go:   // 手写 map[string][]T
来源：http://dali.yonumen.top/Article/details/gt2usuzvuxk.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhengqikj.top/Article/details/gt2jwulrsjl.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.chenzaomai.com/Article/details/gt2uwlrmdkv.html

[D20] 统计每个元素出现次数
来源：http://dali.ppjwa.cn/Article/details/gt2gewxmscj.html

Py:   Counter(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gt2hctvgpxt.html

PHP:  array_count_values($arr);
来源：http://dali.jinqigfzy.top/Article/details/gt2slmajlry.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xuetiantiany.cn/Article/details/gt2dfwsnqke.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.feifeiyinyue.top/Article/details/gt2rggwfeoe.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jqgfzy.top/Article/details/gt2welafqeb.html

Go:   // 手写 map[T]int
来源：http://dali.svipenyu.cn/Article/details/gt2fpbvujwa.html

Ruby: arr.tally
来源：http://dali.daxiang520.top/Article/details/gt2vmjafftj.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.kuanghao11.cn/Article/details/gt2xnpvxmmt.html

[D21] 判断是否包含某元素
来源：http://dali.gogol.net.cn/Article/details/gt2tkgfgxav.html

Py:   x in arr
来源：http://dali.pycfn.com/Article/details/gt2mvtbhrsq.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhoulong.xyz/Article/details/gt2tyhaelrx.html

JS:   arr.includes(x)
来源：http://dali.sxryk.cn/Article/details/gt2jgvjsplw.html

TS:   arr.includes(x)
来源：http://dali.yangfankeji.com/Article/details/gt2ajtonjdx.html

Java: list.contains(x)
来源：http://dali.tian-w.cn/Article/details/gt2flamzllt.html

Go:   slices.Contains(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ntufnwlm.html

Ruby: arr.include?(x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2evktmryd.html

C#:   list.Contains(x)
来源：http://dali.jqgufenzy.top/Article/details/gt2qkefoaln.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhiwuduotai.top/Article/details/gt2wxgyxdlx.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.cdnleiting.top/Article/details/gt2xnwpnfcw.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.tanke756.top/Article/details/gt2ewidszuj.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhongyouzk.top/Article/details/gt2puvswwyx.html

TS:   [...arr];
来源：http://dali.cashguo.top/Article/details/gt2xacrzqcj.html

Java: new ArrayList<>(list);
来源：http://dali.chenjidiqi.icu/Article/details/gt2ffaqhoto.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.sxryk.cn/Article/details/gt2hglupweh.html

Ruby: arr.dup;  arr.clone
来源：http://dali.cucudq.cn/Article/details/gt2yinntnqb.html

C#:   new List<int>(list);
来源：http://dali.9152youxi.cn/Article/details/gt2rfzjqbsl.html

[D23] reduce 累积计算
来源：http://dali.jlsjyb.cn/Article/details/gt2mgfbewbf.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jlsjyb.cn/Article/details/gt2mhvtfwmj.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.0kj1m.cn/Article/details/gt2kpzgscfc.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.c1oappe.top/Article/details/gt2kjhmmcrf.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yj20258888.top/Article/details/gt2udspvpts.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jqgfzy.top/Article/details/gt2edlcgegk.html

Go:   // 手写循环
来源：http://dali.wangdashe.top/Article/details/gt2vyqzohkq.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.daria6918.cn/Article/details/gt2axydixcg.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.chenlongwang.top/Article/details/gt2mthgoqyp.html

[D24] 字典 / Map 基本操作
来源：http://dali.dianchejie.cn/Article/details/gt2pjsppuei.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.feifeiyinyue.top/Article/details/gt2lucyuhmc.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhongyouzk.top/Article/details/gt2saeqacrl.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yuxming.cn/Article/details/gt2tqcuetcs.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.fzhhl.top/Article/details/gt2dfbbtgck.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.redwolf501.top/Article/details/gt2wobvrggx.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.xziqi.cn/Article/details/gt2pkkvezin.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.316326.xyz/Article/details/gt2bedybenm.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.chenzaomai.com/Article/details/gt2nmmvqfze.html

[D25] Set 集合去重与交并差
来源：http://dali.tianlin.xyz/Article/details/gt2uitqzlnq.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yj20258888.top/Article/details/gt2kprefesk.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhengqikj.top/Article/details/gt2sztfjiec.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.daria6918.cn/Article/details/gt2bajljkox.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.meibo888.top/Article/details/gt2iwxwxocd.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.ybcxt.top/Article/details/gt2kizvmklk.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.xinyue.icu/Article/details/gt2wpsdllrz.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2xjfsgpzk.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.tanke756.top/Article/details/gt2tmqnszgm.html

[D26] 数组转字符串
来源：http://dali.yanxiufei.cn/Article/details/gt2pmxwdmwx.html

Py:   ", ".join(map(str, arr))
来源：http://dali.ydzc1.top/Article/details/gt2fxbpnwir.html

PHP:  implode(", ", $arr);
来源：http://dali.wangshuangyany.cn/Article/details/gt2njagxcjb.html

JS:   arr.join(", ")
来源：http://dali.hnxiangtu.top/Article/details/gt2aawrnmge.html

TS:   arr.join(", ")
来源：http://dali.xinyue.icu/Article/details/gt2moalqmio.html

Java: String.join(", ", list)
来源：http://dali.jlsjyb.cn/Article/details/gt2nsggphdf.html

Go:   strings.Join(strs, ", ")
来源：http://dali.mhx1999.top/Article/details/gt2hmbnvndr.html

Ruby: arr.join(", ")
来源：http://dali.fzhhl.top/Article/details/gt2jrmfncya.html

C#:   string.Join(", ", list)
来源：http://dali.sysykeji.top/Article/details/gt2vupktohh.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2jjzimzlc.html

E. 字符串处理
来源：http://dali.shzxlz.cn/Article/details/gt2nuwqbiqk.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2hplxiafw.html

[E01] 拼接字符串
来源：http://dali.sysykeji.top/Article/details/gt2hnvgljxt.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hnqzz.top/Article/details/gt2wbkhnsig.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.shangyingyoupin.top/Article/details/gt2wfqgdyub.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gzhubu.top/Article/details/gt2dbehnmjp.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.havefunace.top/Article/details/gt2ppceuqfc.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jyoumei.cn/Article/details/gt2ehrsmtgs.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.hnxiangtu.top/Article/details/gt2haoqpkpe.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.snrcjt.cn/Article/details/gt2flgybukp.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.sysykeji.top/Article/details/gt2kaxlelru.html

[E02] 重复字符串
来源：http://dali.nanxuanxn.top/Article/details/gt2qxuxvpvg.html

Py:   "ab" * 3
来源：http://dali.xylfe.cn/Article/details/gt2xugbbsye.html

PHP:  str_repeat("ab", 3);
来源：http://dali.sxryk.cn/Article/details/gt2metgcnzb.html

JS:   "ab".repeat(3)
来源：http://dali.jinqigfzy.top/Article/details/gt2zwwdhlbs.html

TS:   "ab".repeat(3)
来源：http://dali.yuanzhike.top/Article/details/gt2gtzjfemb.html

Java: "ab".repeat(3)
来源：http://dali.sysykeji.top/Article/details/gt2jzongrsi.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.nwbrower.top/Article/details/gt2uypjylqh.html

Ruby: "ab" * 3
来源：http://dali.nanxinkj.top/Article/details/gt2aijduoga.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.nanxinkj.top/Article/details/gt2enbjglpi.html

[E03] 截取子串
来源：http://dali.sweek.top/Article/details/gt2szfkzwff.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.daxiang520.top/Article/details/gt2rdzosjhw.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.wangshuangyany.cn/Article/details/gt2ehkzokzq.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.shuidangran.top/Article/details/gt2hfyybewa.html

TS:   s.slice(1, 4)
来源：http://dali.gogol.net.cn/Article/details/gt2ijctjzmu.html

Java: s.substring(1, 4)
来源：http://dali.jiagoushi.top/Article/details/gt2fqjhfovd.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.chenjidiqi.icu/Article/details/gt2feynjwoc.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.hnxiangtu.top/Article/details/gt2xadyueyu.html

C#:   s.Substring(1, 3)
来源：http://dali.quarkkingdee.top/Article/details/gt2dumdmmxw.html

[E04] 查找子串位置
来源：http://dali.iojbl.cn/Article/details/gt2hhysmdyt.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhongyouzk.top/Article/details/gt2rpdwbsgd.html

PHP:  strpos($s, "x");
来源：http://dali.cqqwz.cn/Article/details/gt2jazoehqn.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.gotoacloud.top/Article/details/gt2bidcxwqe.html

TS:   s.indexOf("x")
来源：http://dali.ivvv.top/Article/details/gt2bogwhdre.html

Java: s.indexOf("x")
来源：http://dali.fzhhl.top/Article/details/gt2ejlbhika.html

Go:   strings.Index(s, "x")
来源：http://dali.dianchejie.cn/Article/details/gt2qwdloobe.html

Ruby: s.index("x")
来源：http://dali.hfpthk.cn/Article/details/gt2ehqrjyrk.html

C#:   s.IndexOf("x")
来源：http://dali.shangyingyoupin.top/Article/details/gt2mmyksuxq.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jqgufenzy.top/Article/details/gt2cnzowvxe.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.aizwys.cn/Article/details/gt2jnhuqnri.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yuxming.cn/Article/details/gt2yihsfmxy.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hnqzz.top/Article/details/gt2epgyjgxv.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yongpay.top/Article/details/gt2fvepjojq.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.wangdashe.top/Article/details/gt2qezxhmlq.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.0kj1m.cn/Article/details/gt2rkdyzgrs.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2owfypwne.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yanxiufei.cn/Article/details/gt2ufjcbzdp.html

[E06] 替换子串
来源：http://dali.nwbrower.top/Article/details/gt2waalthuk.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yvedp.cn/Article/details/gt2dqyrcpwj.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qxjngwaj.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hfpthk.cn/Article/details/gt2xaratbag.html

TS:   s.replaceAll("a", "b")
来源：http://dali.mhx1999.top/Article/details/gt2rutssbqq.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jqgufenzy.top/Article/details/gt2jxmqhlbd.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.andypj.xyz/Article/details/gt2sbolsrxe.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.kuanghao11.cn/Article/details/gt2tsfgpsmv.html

C#:   s.Replace("a", "b")
来源：http://dali.feifeiyinyue.top/Article/details/gt2weyowiug.html

[E07] 按分隔符拆分
来源：http://dali.feifeiyinyue.top/Article/details/gt2adschjcd.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yj202588.top/Article/details/gt2pxghcxyy.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yonumen.top/Article/details/gt2yhehdhpx.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.cashguo.top/Article/details/gt2jjrpopib.html

TS:   s.split(",")
来源：http://dali.mhx1999.top/Article/details/gt2hncvziln.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.xziqi.cn/Article/details/gt2ahngflcc.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.tian-w.cn/Article/details/gt2lrhsdzmm.html

Ruby: s.split(",");  s.split
来源：http://dali.fzhhl.top/Article/details/gt2qauzbiss.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jyoumei.cn/Article/details/gt2yuljcwpn.html

[E08] 数组按分隔符合并
来源：http://dali.redwolf501.top/Article/details/gt2rdfdtmqa.html

Py:   ",".join(items)
来源：http://dali.xinyue.icu/Article/details/gt2cyareilz.html

PHP:  implode(",", $items);
来源：http://dali.daria6918.cn/Article/details/gt2fgbvalwp.html

JS:   items.join(",")
来源：http://dali.smart0.xyz/Article/details/gt2oovbtdyd.html

TS:   items.join(",")
来源：http://dali.birdmap.top/Article/details/gt2pujgwcwb.html

Java: String.join(",", items)
来源：http://dali.sxryk.cn/Article/details/gt2xbmpycul.html

Go:   strings.Join(items, ",")
来源：http://dali.bjfxy.top/Article/details/gt2zwqrmddv.html

Ruby: items.join(",")
来源：http://dali.redwolf501.top/Article/details/gt2lpqvexbw.html

C#:   string.Join(",", items)
来源：http://dali.guannengcc.top/Article/details/gt2ndmulvhr.html

[E09] 去除所有空白字符
来源：http://dali.yvedp.cn/Article/details/gt2fbpulwhx.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.cucudq.cn/Article/details/gt2bozzvxcx.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2untjodka.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2etvmnxau.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.guannengcc.top/Article/details/gt2hliroyrl.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mhidsjuq.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.dashuyun.cn/Article/details/gt2ggxqtzaf.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.wangshuangyany.cn/Article/details/gt2rhuwqava.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.cheryme.top/Article/details/gt2ibqxolhe.html

[E10] 左侧补零 / 定长填充
来源：http://dali.cdnleiting.top/Article/details/gt2ugwjsgkg.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhoulong.xyz/Article/details/gt2nmbfgues.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhixingplan.top/Article/details/gt2puxeblne.html

JS:   "7".padStart(3, "0")
来源：http://dali.andypj.xyz/Article/details/gt2ijsexokf.html

TS:   "7".padStart(3, "0")
来源：http://dali.tian-w.cn/Article/details/gt2xrivnugd.html

Java: String.format("%03d", 7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cbeqlabg.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.gogol.net.cn/Article/details/gt2tkwwisax.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.guannengcc.top/Article/details/gt2tklooxhj.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.ehwqpu.com/Article/details/gt2zzdgkqgl.html

[E11] 反转字符串
来源：http://dali.gogol.net.cn/Article/details/gt2unqdkbfh.html

Py:   s[::-1]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fagusxhq.html

PHP:  strrev($s);
来源：http://dali.cashguo.top/Article/details/gt2ylglvigo.html

JS:   [...s].reverse().join("")
来源：http://dali.gzhubu.top/Article/details/gt2ilsxlrrj.html

TS:   [...s].reverse().join("")
来源：http://dali.andypj.xyz/Article/details/gt2tbcmpegt.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.cucudq.cn/Article/details/gt2adhfivzf.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hysaishi.cn/Article/details/gt2vaedxzcv.html

Ruby: s.reverse
来源：http://dali.hongshengwenyu.top/Article/details/gt2suqmtgvp.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hnqzz.top/Article/details/gt2fnnrvemv.html

[E12] 统计某字符出现次数
来源：http://dali.snrcjt.cn/Article/details/gt2ftutrgck.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2snzjjkac.html

PHP:  substr_count($s, "a");
来源：http://dali.tanke756.top/Article/details/gt2oajupige.html

JS:   s.split("a").length - 1
来源：http://dali.daxiang520.top/Article/details/gt2cnsybgnu.html

TS:   s.split("a").length - 1
来源：http://dali.yj20258888.top/Article/details/gt2shiusmeu.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yuxming.cn/Article/details/gt2kfqyjgan.html

Go:   strings.Count(s, "a")
来源：http://dali.snrcjt.cn/Article/details/gt2bgplrbhi.html

Ruby: s.count("a")
来源：http://dali.yj20258.top/Article/details/gt2dhchdjzb.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jyoumei.cn/Article/details/gt2xtjqhxry.html

[E13] 逐字符遍历
来源：http://dali.c1oappe.top/Article/details/gt2cdvkdpxj.html

Py:   for ch in s: print(ch)
来源：http://dali.zdqjudy.top/Article/details/gt2jzykqmeh.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yonumen.top/Article/details/gt2ebjpqouk.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hxookyys.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yj20258.top/Article/details/gt2umyhxrlc.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.nanxuanxn.top/Article/details/gt2niadfdrh.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jiagoushi.top/Article/details/gt2dazwntdb.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.wangshuangyany.cn/Article/details/gt2bmqierlw.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yuanzhike.top/Article/details/gt2jpqxtlpp.html

[E14] URL 编码与 Base64
来源：http://dali.sxryk.cn/Article/details/gt2jvxhlvbx.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.ppjwa.cn/Article/details/gt2qfbiyhgv.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.aibaodan.cn/Article/details/gt2mxezvxqe.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jhkmohcw.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jiagoushi.top/Article/details/gt2vhnpffod.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.cucudq.cn/Article/details/gt2ziijldwu.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.ivvv.top/Article/details/gt2utokijes.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.ybcxt.top/Article/details/gt2rqhpopeu.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhongyouzk.top/Article/details/gt2zasndgqx.html

[E15] HTML 转义 / 反转义
来源：http://dali.fengsongda.top/Article/details/gt2hkqwfzmm.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.kuanghao11.cn/Article/details/gt2vocgtnpl.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hammf.cn/Article/details/gt2raapbjta.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zycfv.cn/Article/details/gt2nmsxvexl.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.sxryk.cn/Article/details/gt2ijkrsdgd.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhoulong.xyz/Article/details/gt2vznurkal.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mttztpxh.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.wangdashe.top/Article/details/gt2gjtjsuyd.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hfpthk.cn/Article/details/gt2mcrubtce.html

[E16] 数字千分位
来源：http://dali.ybcxt.top/Article/details/gt2suipddgt.html

Py:   f"{1234567:,}"
来源：http://dali.cheryme.top/Article/details/gt2mxxlljwa.html

PHP:  number_format(1234567);
来源：http://dali.birdmap.top/Article/details/gt2conasmhw.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.cheryme.top/Article/details/gt2uegejanx.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.snrcjt.cn/Article/details/gt2cxfeyipf.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yj20258888.top/Article/details/gt2iovprymr.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.andypj.xyz/Article/details/gt2hriyhthf.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhixingplan.top/Article/details/gt2bwvtksco.html

C#:   1234567.ToString("N0")
来源：http://dali.mhx1999.top/Article/details/gt2tgsuqftc.html

[E17] 首字母大写
来源：http://dali.aizwys.cn/Article/details/gt2zckpuhwj.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.snrcjt.cn/Article/details/gt2buafldvq.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.wangdashe.top/Article/details/gt2lwfqwgdh.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhongyouzk.top/Article/details/gt2uvrivkna.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ybcxt.top/Article/details/gt2qvetfkrt.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rarwleeu.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jianghu66.top/Article/details/gt2zgofqtwl.html

Ruby: s.capitalize
来源：http://dali.zhiwuduotai.top/Article/details/gt2emkeisoi.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.chenzaomai.com/Article/details/gt2kwyqcnti.html

[E18] 模板占位符替换
来源：http://dali.zhoulong.xyz/Article/details/gt2zfrpypug.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yj20258888.top/Article/details/gt2zysakimy.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.bjfxy.top/Article/details/gt2nickcuxb.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.andypj.xyz/Article/details/gt2witqljln.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.pycfn.com/Article/details/gt2bsevwsrh.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.snrcjt.cn/Article/details/gt2sizvqwzp.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zdqjudy.top/Article/details/gt2caqdzyzn.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yj20258.top/Article/details/gt2ppacgwzo.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.svipenyu.cn/Article/details/gt2csqlxcwk.html

[E19] 多行文本按行拆分
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cclslood.html

Py:   s.splitlines()
来源：http://dali.zdqjudy.top/Article/details/gt2gapflvau.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.pengpengdd.cyou/Article/details/gt2nsmrgbtr.html

JS:   s.split(/\r?\n/)
来源：http://dali.havefunace.top/Article/details/gt2hjkbpvpa.html

TS:   s.split(/\r?\n/)
来源：http://dali.havefunace.top/Article/details/gt2qseuctpi.html

Java: s.lines().toList()
来源：http://dali.sxryk.cn/Article/details/gt2yjcouxtu.html

Go:   strings.Split(s, "\n")
来源：http://dali.redwolf501.top/Article/details/gt2glszgtpk.html

Ruby: s.lines
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jlyjbyro.html

C#:   s.Split('\n')
来源：http://dali.xinyue.icu/Article/details/gt2lbhwglxl.html

[E20] 判断字符串是否为空
来源：http://dali.cdnleiting.top/Article/details/gt2nwtdsreq.html

Py:   if not s:
来源：http://dali.xuanzx.com/Article/details/gt2sncomvlj.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.tianlin.xyz/Article/details/gt2shzgwrob.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.dashuyun.cn/Article/details/gt2hgvougiv.html

TS:   if (s === "") {}
来源：http://dali.yuxming.cn/Article/details/gt2whqgpwvp.html

Java: if (s.isEmpty()) {}
来源：http://dali.aizwys.cn/Article/details/gt2nwdndwll.html

Go:   if s == "" {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2ellnbvwr.html

Ruby: if s.empty?
来源：http://dali.gzhubu.top/Article/details/gt2dlpnktpr.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.gogol.net.cn/Article/details/gt2hwfxhizz.html

[E21] 超长截断加省略号
来源：http://dali.xuetiantiany.cn/Article/details/gt2lnthhijl.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.sweek.top/Article/details/gt2awqtapug.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.c1oappe.top/Article/details/gt2hhmkayxl.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jiagoushi.top/Article/details/gt2voimxwwm.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yvedp.cn/Article/details/gt2ehkcmast.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.pycfn.com/Article/details/gt2vzoqvdre.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yongpay.top/Article/details/gt2leflkdsx.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yj20258888.top/Article/details/gt2scywemmv.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.tanke756.top/Article/details/gt2fbvvajjn.html

[E22] 字节长度与字符长度
来源：http://dali.sysykeji.top/Article/details/gt2ezelnlfb.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jianghu66.top/Article/details/gt2epfmbqkk.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yongpay.top/Article/details/gt2dobziqht.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gotoacloud.top/Article/details/gt2vwpghvga.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinghuilouyu.cn/Article/details/gt2idnvonge.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.aizwys.cn/Article/details/gt2evlzlors.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.bjfxy.top/Article/details/gt2qxghmeot.html

Ruby: s.bytesize;  s.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qktrxzxy.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jyoumei.cn/Article/details/gt2clrascgo.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2vvepeeuk.html

F. 文件与目录
来源：http://dali.zhongyouzk.top/Article/details/gt2jlchgoyx.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2stjbsroa.html

[F01] 读取整个文件
来源：http://dali.gaohongyu789.top/Article/details/gt2uxotyule.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jyoumei.cn/Article/details/gt2jwwjojos.html

PHP:  file_get_contents("a.txt");
来源：http://dali.cucudq.cn/Article/details/gt2umhbzmtj.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.feifeiyinyue.top/Article/details/gt2lzasxbdl.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yuanzhike.top/Article/details/gt2jrnsnuxo.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.shzxlz.cn/Article/details/gt2ygevubql.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.shzxlz.cn/Article/details/gt2dkyzrtxs.html

Ruby: File.read("a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2vurrwxjo.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.nwbrower.top/Article/details/gt2ximiknrj.html

[F02] 逐行读取文件
来源：http://dali.yongpay.top/Article/details/gt2izipsicy.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yj20258.top/Article/details/gt2xdngapgq.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.vqdsnc.cn/Article/details/gt2momerkau.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jqgfzy.top/Article/details/gt2gjeewvkp.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinqigufen.top/Article/details/gt2wwzjrpxd.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2hisfykbh.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.wangdashe.top/Article/details/gt2mkdwolxh.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.shangyingyoupin.top/Article/details/gt2xmhaikpf.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2taopgcms.html

[F03] 写入文件（覆盖）
来源：http://dali.cucudq.cn/Article/details/gt2zdpwrlak.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hywenlv.cn/Article/details/gt2nroughpa.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bswlreiy.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.wangshuangyany.cn/Article/details/gt2ebpyegpc.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yvedp.cn/Article/details/gt2nyplqvvi.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhongyouzk.top/Article/details/gt2dwdouovi.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yonumen.top/Article/details/gt2druchian.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.cdnleiting.top/Article/details/gt2gmlvvkjh.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.tianlin.xyz/Article/details/gt2nqyfvpgj.html

[F04] 追加写入文件
来源：http://dali.cqqwz.cn/Article/details/gt2aezxpszx.html


<!-- 参考信息 -->