代发 wailian999

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhixingplan.top/Article/details/gtmcbuxoua.html

Go:   // 手写双层循环
来源：http://dali.zycfv.cn/Article/details/gtpaygtndk.html

Ruby: nested.flatten
来源：http://dali.sysykeji.top/Article/details/gtkvcpjhth.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jianghu66.top/Article/details/gtvkomtsoq.html

[D19] 按字段分组
来源：http://dali.316326.xyz/Article/details/gtajznaemt.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jinqigufen.top/Article/details/gtmyekgjro.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.guannengcc.top/Article/details/gtlpkglofi.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjmdasdhe.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.cqqwz.cn/Article/details/gtoldsnuzc.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.sufxvd.cn/Article/details/gtqpoabxvz.html

Go:   // 手写 map[string][]T
来源：http://dali.316326.xyz/Article/details/gtgooxhhja.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.ybcxt.top/Article/details/gtawlpjpim.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.hongshengwenyu.top/Article/details/gtbtfzvglm.html

[D20] 统计每个元素出现次数
来源：http://dali.dianchejie.cn/Article/details/gtcrivjiuy.html

Py:   Counter(arr)
来源：http://dali.svipenyu.cn/Article/details/gtggwpsrgq.html

PHP:  array_count_values($arr);
来源：http://dali.hnqzz.top/Article/details/gtaqvpzzag.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.wangdashe.top/Article/details/gtyvwkasns.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hnxiangtu.top/Article/details/gtmccrywdr.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.kuanghao11.cn/Article/details/gtmfgyeqvh.html

Go:   // 手写 map[T]int
来源：http://dali.jinqigufen.top/Article/details/gtgacmnesz.html

Ruby: arr.tally
来源：http://dali.sxryk.cn/Article/details/gtrpvootdy.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yj202588.top/Article/details/gtwcpwiplj.html

[D21] 判断是否包含某元素
来源：http://dali.snrcjt.cn/Article/details/gtxffogcyb.html

Py:   x in arr
来源：http://dali.mhx1999.top/Article/details/gtbnfynymm.html

PHP:  in_array($x, $arr, true);
来源：http://dali.tianlin.xyz/Article/details/gtzinyppht.html

JS:   arr.includes(x)
来源：http://dali.gaohongyu789.top/Article/details/gtpzpypihv.html

TS:   arr.includes(x)
来源：http://dali.yueranfly.top/Article/details/gtcyzsmcqa.html

Java: list.contains(x)
来源：http://dali.smart0.xyz/Article/details/gtbnvfwets.html

Go:   slices.Contains(arr, x)
来源：http://dali.iojbl.cn/Article/details/gtcltlcsoz.html

Ruby: arr.include?(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyjmdxtvs.html

C#:   list.Contains(x)
来源：http://dali.jqgufenzy.top/Article/details/gtcsqjnubb.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yuxming.cn/Article/details/gtnxouxvrs.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yangfankeji.com/Article/details/gtiefrfpfk.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yonumen.top/Article/details/gtwabnbcfr.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtvdpwkehz.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gtnuicoemb.html

Java: new ArrayList<>(list);
来源：http://dali.zhiwuduotai.top/Article/details/gtbwoijmeb.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.redwolf501.top/Article/details/gtxcjclsfa.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jinqigufen.top/Article/details/gtcylfptew.html

C#:   new List<int>(list);
来源：http://dali.chenjidiqi.icu/Article/details/gtyhejfthl.html

[D23] reduce 累积计算
来源：http://dali.jinyuanbaomall.cn/Article/details/gthnhilovv.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.tianlin.xyz/Article/details/gtdkcowufd.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.hammf.cn/Article/details/gtidtcpqqc.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yongpay.top/Article/details/gtnlkzcgbk.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yj20258.top/Article/details/gtokbohfln.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.daria6918.cn/Article/details/gtaeakszki.html

Go:   // 手写循环
来源：http://dali.feifeiyinyue.top/Article/details/gtcmgzlyrb.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yuanzhike.top/Article/details/gtwrvwqcbn.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtotxekhuv.html

[D24] 字典 / Map 基本操作
来源：http://dali.jianghu66.top/Article/details/gtlireunzq.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yj20258.top/Article/details/gtepvgandl.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jinghuilouyu.cn/Article/details/gtxayxkmmx.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.bjfxy.top/Article/details/gtyedgovej.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.feifeiyinyue.top/Article/details/gtdzgyqrbs.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuvarddki.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.cqqwz.cn/Article/details/gtchtyeujz.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yonumen.top/Article/details/gtnbidxzkl.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.sxryk.cn/Article/details/gtbxtvlrui.html

[D25] Set 集合去重与交并差
来源：http://dali.hnqzz.top/Article/details/gtihyeeudr.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.mhx1999.top/Article/details/gtyxbpxijy.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.ivvv.top/Article/details/gtlzylbaou.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.kuanghao11.cn/Article/details/gtvjqydseg.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yangfankeji.com/Article/details/gtndbhmula.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.aizwys.cn/Article/details/gtayuaciej.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.andypj.xyz/Article/details/gtdaxxaotk.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.wangdashe.top/Article/details/gtwtjfdjlh.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.quarkkingdee.top/Article/details/gtjtecewlt.html

[D26] 数组转字符串
来源：http://dali.yueranfly.top/Article/details/gtnmyeupez.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hfpthk.cn/Article/details/gtdfkhoixa.html

PHP:  implode(", ", $arr);
来源：http://dali.yangfankeji.com/Article/details/gtuttnpztt.html

JS:   arr.join(", ")
来源：http://dali.xziqi.cn/Article/details/gttnehrbtp.html

TS:   arr.join(", ")
来源：http://dali.zycfv.cn/Article/details/gtoytvfltq.html

Java: String.join(", ", list)
来源：http://dali.hnxiangtu.top/Article/details/gtnkxofaly.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhoulong.xyz/Article/details/gtosxkeofv.html

Ruby: arr.join(", ")
来源：http://dali.yanxiufei.cn/Article/details/gtljzttqrh.html

C#:   string.Join(", ", list)
来源：http://dali.snrcjt.cn/Article/details/gtvlyhxomc.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdboipmwd.html

E. 字符串处理
来源：http://dali.cqqwz.cn/Article/details/gtosacuijd.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtqhfdnyib.html

[E01] 拼接字符串
来源：http://dali.bjfxy.top/Article/details/gtvdzsqfdl.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.cucudq.cn/Article/details/gttuxqjcwe.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yuanzhike.top/Article/details/gtecqqwjpu.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.fengsongda.top/Article/details/gtqxgsejax.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cdnleiting.top/Article/details/gtgiwkvuvk.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.nwbrower.top/Article/details/gtckkwksfe.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhiwuduotai.top/Article/details/gteefoprpv.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.sysykeji.top/Article/details/gtstxhauhs.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gtdnezpuhn.html

[E02] 重复字符串
来源：http://dali.tian-w.cn/Article/details/gtpjuvomcg.html

Py:   "ab" * 3
来源：http://dali.cqqwz.cn/Article/details/gtkciiocsj.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jlsjyb.cn/Article/details/gteppzmrkq.html

JS:   "ab".repeat(3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfqiblxhq.html

TS:   "ab".repeat(3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtckbphyqj.html

Java: "ab".repeat(3)
来源：http://dali.quarkkingdee.top/Article/details/gtazltacia.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.0kj1m.cn/Article/details/gtdjhtyyhm.html

Ruby: "ab" * 3
来源：http://dali.yj20258.top/Article/details/gtknzjovun.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.hysaishi.cn/Article/details/gtuxfkxoec.html

[E03] 截取子串
来源：http://dali.nanxuanxn.top/Article/details/gtlmqwwbah.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.cashguo.top/Article/details/gtevpgyvmt.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.gaohongyu789.top/Article/details/gtnmciwxrt.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.cucudq.cn/Article/details/gtukrkqmtg.html

TS:   s.slice(1, 4)
来源：http://dali.ehwqpu.com/Article/details/gtsmnocljs.html

Java: s.substring(1, 4)
来源：http://dali.shanyushiyangtech.top/Article/details/gtndosslfr.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.quarkkingdee.top/Article/details/gtigwhtwzw.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.cucudq.cn/Article/details/gttgqpadxe.html

C#:   s.Substring(1, 3)
来源：http://dali.dianchejie.cn/Article/details/gtspicplzu.html

[E04] 查找子串位置
来源：http://dali.hysaishi.cn/Article/details/gtqjgnhbjx.html

Py:   s.find("x");  s.index("x")
来源：http://dali.sufxvd.cn/Article/details/gttmrjxyxi.html

PHP:  strpos($s, "x");
来源：http://dali.haohaochexian.top/Article/details/gthaeiadfr.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.316326.xyz/Article/details/gtsvvijfur.html

TS:   s.indexOf("x")
来源：http://dali.hnqzz.top/Article/details/gtaoabcjre.html

Java: s.indexOf("x")
来源：http://dali.yuanzhike.top/Article/details/gtblinsrsk.html

Go:   strings.Index(s, "x")
来源：http://dali.andypj.xyz/Article/details/gtweqdzwpg.html

Ruby: s.index("x")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoyglfrzf.html

C#:   s.IndexOf("x")
来源：http://dali.jlsjyb.cn/Article/details/gthcyuknkc.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.cucudq.cn/Article/details/gtclfppmmt.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.dianchejie.cn/Article/details/gtaaufokpy.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.ivvv.top/Article/details/gtdkvoojwa.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.nwbrower.top/Article/details/gtvjmfhckx.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.hnxiangtu.top/Article/details/gtuudnqzxc.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.meibo888.top/Article/details/gtyxfcpaez.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yuxming.cn/Article/details/gtzhgtjrkd.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.xinyue.icu/Article/details/gtyvcpiakx.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.cheryme.top/Article/details/gttnpnyewl.html

[E06] 替换子串
来源：http://dali.ybcxt.top/Article/details/gtzmsrizto.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.gotoacloud.top/Article/details/gtjklgtwlh.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.andypj.xyz/Article/details/gtjyfzyefh.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.kuanghao11.cn/Article/details/gtgafieucr.html

TS:   s.replaceAll("a", "b")
来源：http://dali.wangdashe.top/Article/details/gtdyvcesqd.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinqigufen.top/Article/details/gtelzwfcys.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttledmeup.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.hongshengwenyu.top/Article/details/gtynswttvq.html

C#:   s.Replace("a", "b")
来源：http://dali.gotoacloud.top/Article/details/gtuwpzehtl.html

[E07] 按分隔符拆分
来源：http://dali.zdqjudy.top/Article/details/gtexcvalnu.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.cashguo.top/Article/details/gtdqiduzqd.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yuxming.cn/Article/details/gtnedjiidx.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.fengsongda.top/Article/details/gtjwgolrlq.html

TS:   s.split(",")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrcsjuvqa.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhixingplan.top/Article/details/gtiwwijgkt.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtzuyjxcpa.html

Ruby: s.split(",");  s.split
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsfbdcryy.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.tianlin.xyz/Article/details/gtzbbysily.html

[E08] 数组按分隔符合并
来源：http://dali.hysaishi.cn/Article/details/gtvmysgmol.html

Py:   ",".join(items)
来源：http://dali.cheryme.top/Article/details/gtbafdwowk.html

PHP:  implode(",", $items);
来源：http://dali.yj20258888.top/Article/details/gtejpbndqr.html

JS:   items.join(",")
来源：http://dali.sufxvd.cn/Article/details/gtvonldwul.html

TS:   items.join(",")
来源：http://dali.jianghu66.top/Article/details/gttaybpqsc.html

Java: String.join(",", items)
来源：http://dali.c1oappe.top/Article/details/gtlotecksw.html

Go:   strings.Join(items, ",")
来源：http://dali.yvedp.cn/Article/details/gtwuaxdxzf.html

Ruby: items.join(",")
来源：http://dali.haohaochexian.top/Article/details/gtvgyfysbl.html

C#:   string.Join(",", items)
来源：http://dali.pycfn.com/Article/details/gtdrrczdvj.html

[E09] 去除所有空白字符
来源：http://dali.cucudq.cn/Article/details/gtuleuuqgx.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.xuanzx.com/Article/details/gtjabbxbeg.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.iojbl.cn/Article/details/gtwgeodlbw.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.xylfe.cn/Article/details/gtmgcxhdea.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.haohaochexian.top/Article/details/gtoifmodys.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yonumen.top/Article/details/gtmopxczyw.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhengqikj.top/Article/details/gtetvcaebl.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jyoumei.cn/Article/details/gtdcipicwp.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.fengsongda.top/Article/details/gtyubqrqxd.html

[E10] 左侧补零 / 定长填充
来源：http://dali.shanyushiyangkeji.top/Article/details/gtebwrhiwj.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.vqdsnc.cn/Article/details/gtwfzocgbb.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.ehwqpu.com/Article/details/gtuknrndqa.html

JS:   "7".padStart(3, "0")
来源：http://dali.feifeiyinyue.top/Article/details/gtisbcdoxm.html

TS:   "7".padStart(3, "0")
来源：http://dali.ehwqpu.com/Article/details/gtllfptowr.html

Java: String.format("%03d", 7)
来源：http://dali.jianghu66.top/Article/details/gttiiricgg.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.guannengcc.top/Article/details/gtbbfwrkan.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jianghu66.top/Article/details/gtdchjicjm.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.gzhubu.top/Article/details/gtdxqmllmz.html

[E11] 反转字符串
来源：http://dali.yangfankeji.com/Article/details/gtuaaomynh.html

Py:   s[::-1]
来源：http://dali.dashuyun.cn/Article/details/gtmpeprfav.html

PHP:  strrev($s);
来源：http://dali.wangshuangyany.cn/Article/details/gtvolffkgi.html

JS:   [...s].reverse().join("")
来源：http://dali.yonumen.top/Article/details/gtqunoyecd.html

TS:   [...s].reverse().join("")
来源：http://dali.bjfxy.top/Article/details/gtlmkszrou.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhengqikj.top/Article/details/gtrqrcsiuu.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.ydzc1.top/Article/details/gtngbzljrp.html

Ruby: s.reverse
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqivqhqvw.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.pycfn.com/Article/details/gtgdmcrkdu.html

[E12] 统计某字符出现次数
来源：http://dali.zhengqikj.top/Article/details/gttzblcdnd.html

Py:   s.count("a")
来源：http://dali.gogol.net.cn/Article/details/gtmueakvua.html

PHP:  substr_count($s, "a");
来源：http://dali.jiagoushi.top/Article/details/gtzrbdlxzg.html

JS:   s.split("a").length - 1
来源：http://dali.jianghu66.top/Article/details/gtcyxxlupz.html

TS:   s.split("a").length - 1
来源：http://dali.birdmap.top/Article/details/gtnzorypyf.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jinqigfzy.top/Article/details/gttawhxnyg.html

Go:   strings.Count(s, "a")
来源：http://dali.shangyingyoupin.top/Article/details/gtjpobfopt.html

Ruby: s.count("a")
来源：http://dali.guowangkeji.top/Article/details/gtjgmwkrxu.html

C#:   s.Count(c => c == 'a')
来源：http://dali.aizwys.cn/Article/details/gtdjkjreeo.html

[E13] 逐字符遍历
来源：http://dali.fengsongda.top/Article/details/gtiyxonrgi.html

Py:   for ch in s: print(ch)
来源：http://dali.chenlongwang.top/Article/details/gtuvaraytf.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhiwuduotai.top/Article/details/gtouxjvslb.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ydzc1.top/Article/details/gtxabbyblv.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jqgfzy.top/Article/details/gtxhskskvx.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.xuetiantiany.cn/Article/details/gtrecsdbkt.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.cheryme.top/Article/details/gtenlfnvks.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.guannengcc.top/Article/details/gtavznsxys.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jinqigfzy.top/Article/details/gtjfdnmkht.html

[E14] URL 编码与 Base64
来源：http://dali.gotoacloud.top/Article/details/gtswmlynkz.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.316326.xyz/Article/details/gtoneypfrl.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhoulong.xyz/Article/details/gtekvnsfnn.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.bjfxy.top/Article/details/gtuxvadmnq.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yonumen.top/Article/details/gtmggkirdw.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhiwuduotai.top/Article/details/gtkmncrmtw.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.dashuyun.cn/Article/details/gtcrsduzcc.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hnxiangtu.top/Article/details/gtbyxmwrhz.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hywenlv.cn/Article/details/gtbknmdrxq.html

[E15] HTML 转义 / 反转义
来源：http://dali.shanyushiyangkeji.top/Article/details/gthanpmqlz.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.sxryk.cn/Article/details/gtkzniapsu.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jqgufenzy.top/Article/details/gtonzinmvk.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.xinyue.icu/Article/details/gtlouqezpl.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.chenlongwang.top/Article/details/gttisyahrn.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.pycfn.com/Article/details/gtcgppaqrj.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.chenzaomai.com/Article/details/gturvqprgm.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yanxiufei.cn/Article/details/gtndayfveu.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.cheryme.top/Article/details/gtvkdkqfhk.html

[E16] 数字千分位
来源：http://dali.tian-w.cn/Article/details/gtbhwbxhmr.html

Py:   f"{1234567:,}"
来源：http://dali.svipenyu.cn/Article/details/gtoocmnyof.html

PHP:  number_format(1234567);
来源：http://dali.yanxiufei.cn/Article/details/gtstqyacoj.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.sufxvd.cn/Article/details/gtpscisuwk.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinqigfzy.top/Article/details/gtwrvfhdmj.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.pengpengdd.cyou/Article/details/gttovedwdm.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.xinyue.icu/Article/details/gtxewsfqum.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.nanxuanxn.top/Article/details/gtmvfunmln.html

C#:   1234567.ToString("N0")
来源：http://dali.sysykeji.top/Article/details/gtbjurxqnp.html

[E17] 首字母大写
来源：http://dali.haohaochexian.top/Article/details/gtuputsyia.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.sysykeji.top/Article/details/gtspjzvdku.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.cashguo.top/Article/details/gtoiebphyx.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhengqikj.top/Article/details/gtwjiujofp.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yuanzhike.top/Article/details/gtfcennilz.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.cashguo.top/Article/details/gtzojdzlht.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.shanyushiyangtech.top/Article/details/gtjlkadvqx.html

Ruby: s.capitalize
来源：http://dali.guowangkeji.top/Article/details/gtkiqbsvbx.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.fengsongda.top/Article/details/gtprhhxstv.html

[E18] 模板占位符替换
来源：http://dali.cashguo.top/Article/details/gtioqdxoah.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.cucudq.cn/Article/details/gtjvsgdtiz.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.guannengcc.top/Article/details/gttlsuwcam.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfyjwfpkj.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.shangyingyoupin.top/Article/details/gtyosqiasj.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxjuvmswc.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.nanxinkj.top/Article/details/gtbxlxkxkd.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jlsjyb.cn/Article/details/gtxrrkzzvg.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.sxryk.cn/Article/details/gtswgtdoyc.html

[E19] 多行文本按行拆分
来源：http://dali.sysykeji.top/Article/details/gttukarwso.html

Py:   s.splitlines()
来源：http://dali.cucudq.cn/Article/details/gtvzyfyxvk.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gtqupfmlrh.html

JS:   s.split(/\r?\n/)
来源：http://dali.yj20258.top/Article/details/gteqqkzmvp.html

TS:   s.split(/\r?\n/)
来源：http://dali.tianlin.xyz/Article/details/gtmdpklpdb.html

Java: s.lines().toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgxxwcxrp.html

Go:   strings.Split(s, "\n")
来源：http://dali.feifeiyinyue.top/Article/details/gttplmlqoj.html

Ruby: s.lines
来源：http://dali.chenzaomai.com/Article/details/gtfivpzsbn.html

C#:   s.Split('\n')
来源：http://dali.shanyushiyangtech.top/Article/details/gtzcftixht.html

[E20] 判断字符串是否为空
来源：http://dali.hammf.cn/Article/details/gturgzepqw.html

Py:   if not s:
来源：http://dali.yj20258888.top/Article/details/gtrnshoqkf.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.aibaodan.cn/Article/details/gtbqhttqfx.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.mhx1999.top/Article/details/gtbwcpymca.html

TS:   if (s === "") {}
来源：http://dali.svipenyu.cn/Article/details/gtfvyeecnq.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhixingplan.top/Article/details/gtxzufqred.html

Go:   if s == "" {}
来源：http://dali.guannengcc.top/Article/details/gtwuyevzjf.html

Ruby: if s.empty?
来源：http://dali.havefunace.top/Article/details/gtjvtrvtzu.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhoulong.xyz/Article/details/gtrhdckkyz.html

[E21] 超长截断加省略号
来源：http://dali.shanyushiyangtech.top/Article/details/gtwoncmlgm.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gtqbizvczn.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jinyuanbaomall.cn/Article/details/gthelujsrg.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cheryme.top/Article/details/gtnhhofrow.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmqwtufaj.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.chenlongwang.top/Article/details/gtbxpybcya.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zycfv.cn/Article/details/gtumplosgc.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhixingplan.top/Article/details/gtvclivjfs.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.chenzaomai.com/Article/details/gtkbmjbzqk.html

[E22] 字节长度与字符长度
来源：http://dali.xziqi.cn/Article/details/gtutkegynm.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhoulong.xyz/Article/details/gtvibawmdo.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ydzc1.top/Article/details/gtfuomoxmc.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yueranfly.top/Article/details/gtrbvclpiw.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhiwuduotai.top/Article/details/gtenlwusvx.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jinqigufen.top/Article/details/gtuqvjdugg.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.xylfe.cn/Article/details/gtveotxlaj.html

Ruby: s.bytesize;  s.length
来源：http://dali.redwolf501.top/Article/details/gtelsveqrb.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yj20258888.top/Article/details/gtizqtpyce.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gttdirqlfm.html

F. 文件与目录
来源：http://dali.meibo888.top/Article/details/gtnljxkoad.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtkdafpcps.html

[F01] 读取整个文件
来源：http://dali.andypj.xyz/Article/details/gtbgsptdct.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.cheryme.top/Article/details/gtddbwpyua.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yonumen.top/Article/details/gtwiytbkyi.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zdqjudy.top/Article/details/gtewijdyzt.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.shuidangran.top/Article/details/gtrsadlzog.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdbrvdhll.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhongyouzk.top/Article/details/gtczziiyhx.html

Ruby: File.read("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtkbiqjlzk.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtkjdggznt.html

[F02] 逐行读取文件
来源：http://dali.yangfankeji.com/Article/details/gtfvozshgy.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.aibaodan.cn/Article/details/gtvtcjqodi.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzuxmdzox.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj202588.top/Article/details/gtojwlkflo.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtwljrzbkj.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.vqdsnc.cn/Article/details/gtidsvstoz.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.cheryme.top/Article/details/gtjhcakvgj.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yj20258.top/Article/details/gthqkiegcj.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jlsjyb.cn/Article/details/gtreerefwu.html

[F03] 写入文件（覆盖）
来源：http://dali.hnqzz.top/Article/details/gtraikfiop.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.shangyingyoupin.top/Article/details/gtlhdqhbhs.html


<!-- 参考信息 -->