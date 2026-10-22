代发 wailian999

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.cashguo.top/Article/details/gtgicpppst.html

Go:   // 手写双层循环
来源：http://dali.jlsjyb.cn/Article/details/gtckdkphhk.html

Ruby: nested.flatten
来源：http://dali.0kj1m.cn/Article/details/gtzdrvtpsn.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.guowangkeji.top/Article/details/gtkcivnqmp.html

[D19] 按字段分组
来源：http://dali.guannengcc.top/Article/details/gtnxuzmzux.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.quarkkingdee.top/Article/details/gtqvnugunc.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.mhx1999.top/Article/details/gtspgaktip.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.hysaishi.cn/Article/details/gteirazdws.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.snrcjt.cn/Article/details/gtswjepjxs.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jiagoushi.top/Article/details/gtrmvooonf.html

Go:   // 手写 map[string][]T
来源：http://dali.gotoacloud.top/Article/details/gthgmqqlpl.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.ybcxt.top/Article/details/gtqdbfxvyg.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yangfankeji.com/Article/details/gtrxlhlirs.html

[D20] 统计每个元素出现次数
来源：http://dali.hywenlv.cn/Article/details/gtkiugbtlo.html

Py:   Counter(arr)
来源：http://dali.jianghu66.top/Article/details/gtnszwsnbp.html

PHP:  array_count_values($arr);
来源：http://dali.iojbl.cn/Article/details/gtjtwljqyh.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yonumen.top/Article/details/gtaoycpswz.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jlsjyb.cn/Article/details/gtnhnzmyko.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.iojbl.cn/Article/details/gtiqrpbvja.html

Go:   // 手写 map[T]int
来源：http://dali.hongshengwenyu.top/Article/details/gtpabjieku.html

Ruby: arr.tally
来源：http://dali.jiagoushi.top/Article/details/gtmtwrxmfh.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.iojbl.cn/Article/details/gtfszivlyb.html

[D21] 判断是否包含某元素
来源：http://dali.chenzaomai.com/Article/details/gtiiwkvcgb.html

Py:   x in arr
来源：http://dali.zhaomingkeji.xyz/Article/details/gtysqrqrnc.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hysaishi.cn/Article/details/gthdmzdukc.html

JS:   arr.includes(x)
来源：http://dali.9152youxi.cn/Article/details/gtepzvlecr.html

TS:   arr.includes(x)
来源：http://dali.yj20258888.top/Article/details/gttuyoahqo.html

Java: list.contains(x)
来源：http://dali.zhoulong.xyz/Article/details/gtuhyuccmy.html

Go:   slices.Contains(arr, x)
来源：http://dali.hysaishi.cn/Article/details/gtfomzvmmo.html

Ruby: arr.include?(x)
来源：http://dali.zhoulong.xyz/Article/details/gtfmetknzo.html

C#:   list.Contains(x)
来源：http://dali.yuxming.cn/Article/details/gtkzuwiipy.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhengqikj.top/Article/details/gtvlmfbxsr.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.havefunace.top/Article/details/gtycyszidc.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteuymqqoa.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtadiznwbv.html

TS:   [...arr];
来源：http://dali.iojbl.cn/Article/details/gtpqlllnjb.html

Java: new ArrayList<>(list);
来源：http://dali.jinghuilouyu.cn/Article/details/gtbeigpgei.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gtxblftbwo.html

Ruby: arr.dup;  arr.clone
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzunvgvld.html

C#:   new List<int>(list);
来源：http://dali.hnxiangtu.top/Article/details/gtdzpowxbd.html

[D23] reduce 累积计算
来源：http://dali.jinghuilouyu.cn/Article/details/gtmllunuos.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yvedp.cn/Article/details/gtmkfwwdvm.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdxjqliog.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.tianlin.xyz/Article/details/gtncqvfvwf.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ivvv.top/Article/details/gtoqwknogt.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jqgfzy.top/Article/details/gtantogqng.html

Go:   // 手写循环
来源：http://dali.dianchejie.cn/Article/details/gtqdquuzkj.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.9152youxi.cn/Article/details/gtfwczlrko.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jiagoushi.top/Article/details/gtoqylfuaa.html

[D24] 字典 / Map 基本操作
来源：http://dali.nanxuanxn.top/Article/details/gtnhtpzlgo.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yvedp.cn/Article/details/gtleufluca.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jlsjyb.cn/Article/details/gtttxwlnjs.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmytrtoxt.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.bjfxy.top/Article/details/gtfajvtvbo.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.c1oappe.top/Article/details/gtulnffdfm.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.0kj1m.cn/Article/details/gtdeozutls.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.0kj1m.cn/Article/details/gtmtpdlfht.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jqgufenzy.top/Article/details/gteshajzjn.html

[D25] Set 集合去重与交并差
来源：http://dali.jinghuilouyu.cn/Article/details/gtbyscknll.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yueranfly.top/Article/details/gtbaoxcbqu.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.ivvv.top/Article/details/gteonywlgo.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jianghu66.top/Article/details/gtsfchzhvs.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtisxffbvv.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.snrcjt.cn/Article/details/gtfipxnqxa.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yj202588.top/Article/details/gtxolhnkyc.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yj20258888.top/Article/details/gtnxguiira.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hnqzz.top/Article/details/gteqzckqoa.html

[D26] 数组转字符串
来源：http://dali.chenlongwang.top/Article/details/gtmgkhoban.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhixingplan.top/Article/details/gtjeyjjzrs.html

PHP:  implode(", ", $arr);
来源：http://dali.cdnleiting.top/Article/details/gtoroawutw.html

JS:   arr.join(", ")
来源：http://dali.yueranfly.top/Article/details/gtxwyelosd.html

TS:   arr.join(", ")
来源：http://dali.wangdashe.top/Article/details/gtkjazxlje.html

Java: String.join(", ", list)
来源：http://dali.pycfn.com/Article/details/gtlnosqriz.html

Go:   strings.Join(strs, ", ")
来源：http://dali.kuanghao11.cn/Article/details/gtejdvenxt.html

Ruby: arr.join(", ")
来源：http://dali.daria6918.cn/Article/details/gteasdlgqs.html

C#:   string.Join(", ", list)
来源：http://dali.chenlongwang.top/Article/details/gtdxzqrruq.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtmajvtnug.html

E. 字符串处理
来源：http://dali.hysaishi.cn/Article/details/gtrymtsdlv.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gthtguatqf.html

[E01] 拼接字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtozwxusuh.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.pengpengdd.cyou/Article/details/gtthuzlwbf.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhixingplan.top/Article/details/gtprtewosw.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.c1oappe.top/Article/details/gthvadmknb.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.nanxuanxn.top/Article/details/gtgjbyrtmg.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hfpthk.cn/Article/details/gtvsfkmlsx.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.fengsongda.top/Article/details/gtnbfllnum.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yj20258.top/Article/details/gtcwbjfypt.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhiwuduotai.top/Article/details/gtjsmmzajw.html

[E02] 重复字符串
来源：http://dali.zhoulong.xyz/Article/details/gtiripaszx.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gtciippkbx.html

PHP:  str_repeat("ab", 3);
来源：http://dali.xuanzx.com/Article/details/gtlkxnacfk.html

JS:   "ab".repeat(3)
来源：http://dali.dashuyun.cn/Article/details/gtcyadcqln.html

TS:   "ab".repeat(3)
来源：http://dali.c1oappe.top/Article/details/gtqevdjbgt.html

Java: "ab".repeat(3)
来源：http://dali.nanxinkj.top/Article/details/gtxvjafpoj.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.meibo888.top/Article/details/gtrkwspqdi.html

Ruby: "ab" * 3
来源：http://dali.9152youxi.cn/Article/details/gtfczevjop.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.ybcxt.top/Article/details/gtnljglwqy.html

[E03] 截取子串
来源：http://dali.hfpthk.cn/Article/details/gtlugoiwuk.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.gotoacloud.top/Article/details/gtbpeylzag.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.tian-w.cn/Article/details/gtpvvgjmun.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jiagoushi.top/Article/details/gtsqiqmxna.html

TS:   s.slice(1, 4)
来源：http://dali.cucudq.cn/Article/details/gtwacbwwjz.html

Java: s.substring(1, 4)
来源：http://dali.ivvv.top/Article/details/gtxkvkzowy.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.hammf.cn/Article/details/gtkqtpkwwh.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yvedp.cn/Article/details/gtkyxddpqd.html

C#:   s.Substring(1, 3)
来源：http://dali.cdnleiting.top/Article/details/gtnxfrdlbe.html

[E04] 查找子串位置
来源：http://dali.wangshuangyany.cn/Article/details/gtstudphyd.html

Py:   s.find("x");  s.index("x")
来源：http://dali.shuidangran.top/Article/details/gtjckztxdj.html

PHP:  strpos($s, "x");
来源：http://dali.yuanzhike.top/Article/details/gtfvpqkpru.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoyrmlhpr.html

TS:   s.indexOf("x")
来源：http://dali.ppjwa.cn/Article/details/gtkukfvuio.html

Java: s.indexOf("x")
来源：http://dali.smart0.xyz/Article/details/gtgulhdgof.html

Go:   strings.Index(s, "x")
来源：http://dali.chenzaomai.com/Article/details/gtdtzclglv.html

Ruby: s.index("x")
来源：http://dali.jinqigufen.top/Article/details/gtwrcfbxac.html

C#:   s.IndexOf("x")
来源：http://dali.smart0.xyz/Article/details/gtxgjomzmb.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.sweek.top/Article/details/gtlctatmxl.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.tian-w.cn/Article/details/gtookmowzw.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.aizwys.cn/Article/details/gtoqrnvzib.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.snrcjt.cn/Article/details/gtihmskkhg.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.feifeiyinyue.top/Article/details/gtzhnupzhc.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.bjfxy.top/Article/details/gtoxhwpozo.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.cqqwz.cn/Article/details/gtttifcogt.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhengqikj.top/Article/details/gtoernilyt.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.birdmap.top/Article/details/gtjlxmecoz.html

[E06] 替换子串
来源：http://dali.tianlin.xyz/Article/details/gtsyqcrxoo.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.daxiang520.top/Article/details/gtwbdgtyht.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.pengpengdd.cyou/Article/details/gtnckjmsma.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jianghu66.top/Article/details/gtiotwcpeb.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jianghu66.top/Article/details/gtjlnmdhap.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.wangdashe.top/Article/details/gteucwscms.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.hnqzz.top/Article/details/gtmefkhaxt.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gtmgjfucet.html

C#:   s.Replace("a", "b")
来源：http://dali.fzhhl.top/Article/details/gtgamudgyx.html

[E07] 按分隔符拆分
来源：http://dali.zhoulong.xyz/Article/details/gtistolpjs.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.hammf.cn/Article/details/gtqarqzskt.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyfchcmlp.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jiagoushi.top/Article/details/gtiwtjywid.html

TS:   s.split(",")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxsekruri.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yj20258.top/Article/details/gtgymikutl.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jyoumei.cn/Article/details/gtzleewfmo.html

Ruby: s.split(",");  s.split
来源：http://dali.yanxiufei.cn/Article/details/gttsqbrfmj.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtofdoryhp.html

[E08] 数组按分隔符合并
来源：http://dali.hongshengwenyu.top/Article/details/gtfnfeuoot.html

Py:   ",".join(items)
来源：http://dali.yonumen.top/Article/details/gtvnjguixy.html

PHP:  implode(",", $items);
来源：http://dali.smart0.xyz/Article/details/gtyomrzuys.html

JS:   items.join(",")
来源：http://dali.guowangkeji.top/Article/details/gtcbcdrjoe.html

TS:   items.join(",")
来源：http://dali.yonumen.top/Article/details/gtkrwedgqn.html

Java: String.join(",", items)
来源：http://dali.pengpengdd.cyou/Article/details/gtnpgflowl.html

Go:   strings.Join(items, ",")
来源：http://dali.yangfankeji.com/Article/details/gtrlbmihtn.html

Ruby: items.join(",")
来源：http://dali.9152youxi.cn/Article/details/gtkumyziho.html

C#:   string.Join(",", items)
来源：http://dali.kuanghao11.cn/Article/details/gtfezpyssu.html

[E09] 去除所有空白字符
来源：http://dali.yj202588.top/Article/details/gtjqgeetri.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.iojbl.cn/Article/details/gtcerrlhsj.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.shuidangran.top/Article/details/gtmyugcejn.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jianghu66.top/Article/details/gtuzvglvlj.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.xylfe.cn/Article/details/gtommdpjgh.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.ivvv.top/Article/details/gtrclvceqq.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.gzhubu.top/Article/details/gtndosqvis.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.ehwqpu.com/Article/details/gttomigymp.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.shzxlz.cn/Article/details/gtzauffqey.html

[E10] 左侧补零 / 定长填充
来源：http://dali.0kj1m.cn/Article/details/gtoeauzlas.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.smart0.xyz/Article/details/gttztnuxtd.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yj20258.top/Article/details/gtmksmwtiv.html

JS:   "7".padStart(3, "0")
来源：http://dali.mhx1999.top/Article/details/gtoowzipjx.html

TS:   "7".padStart(3, "0")
来源：http://dali.vqdsnc.cn/Article/details/gtmlqchgjy.html

Java: String.format("%03d", 7)
来源：http://dali.jinqigfzy.top/Article/details/gtfzuknwus.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.quarkkingdee.top/Article/details/gtkgnjkofc.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.ehwqpu.com/Article/details/gtopsnskid.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhixingplan.top/Article/details/gtmpbdulfr.html

[E11] 反转字符串
来源：http://dali.gotoacloud.top/Article/details/gtccbgiyce.html

Py:   s[::-1]
来源：http://dali.snrcjt.cn/Article/details/gtepiljcvk.html

PHP:  strrev($s);
来源：http://dali.yanxiufei.cn/Article/details/gtrjgnvszl.html

JS:   [...s].reverse().join("")
来源：http://dali.meibo888.top/Article/details/gtcvhiesic.html

TS:   [...s].reverse().join("")
来源：http://dali.wangshuangyany.cn/Article/details/gtiqlptiah.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.ehwqpu.com/Article/details/gtmfknetgh.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.c1oappe.top/Article/details/gtkymxxyiw.html

Ruby: s.reverse
来源：http://dali.meibo888.top/Article/details/gtcivelept.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.nwbrower.top/Article/details/gtbfdlllux.html

[E12] 统计某字符出现次数
来源：http://dali.yj202588.top/Article/details/gtsnifzljy.html

Py:   s.count("a")
来源：http://dali.zhixingplan.top/Article/details/gtiaruvqyr.html

PHP:  substr_count($s, "a");
来源：http://dali.hammf.cn/Article/details/gtlavxlzfj.html

JS:   s.split("a").length - 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgnodxzkh.html

TS:   s.split("a").length - 1
来源：http://dali.dianchejie.cn/Article/details/gtrwrltyhz.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jinqigufen.top/Article/details/gtkmnjatbj.html

Go:   strings.Count(s, "a")
来源：http://dali.cheryme.top/Article/details/gtnxvxbrcz.html

Ruby: s.count("a")
来源：http://dali.sxryk.cn/Article/details/gtubrxwqfo.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhijiandao.cn/Article/details/gtitkpjdgs.html

[E13] 逐字符遍历
来源：http://dali.shangyingyoupin.top/Article/details/gthyfstyvs.html

Py:   for ch in s: print(ch)
来源：http://dali.gogol.net.cn/Article/details/gttvueloxv.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yj202588.top/Article/details/gtbryiwnnu.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xinyue.icu/Article/details/gtalcxvoyh.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xuetiantiany.cn/Article/details/gtejafamrs.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.bjfxy.top/Article/details/gtfjccahmf.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zdqjudy.top/Article/details/gtvtsvmlxz.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.fengsongda.top/Article/details/gtxjwpxyqb.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.nwbrower.top/Article/details/gtbcqnacid.html

[E14] URL 编码与 Base64
来源：http://dali.meibo888.top/Article/details/gthywticwk.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.meibo888.top/Article/details/gtyilaynem.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.guowangkeji.top/Article/details/gtltswckvk.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.xinyue.icu/Article/details/gtrwxerxku.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.cqqwz.cn/Article/details/gtdfzfftnh.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.chenzaomai.com/Article/details/gtjjkmkymf.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.daxiang520.top/Article/details/gtdrxdklbh.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.vqdsnc.cn/Article/details/gthbaevqfl.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gtgyqmkkah.html

[E15] HTML 转义 / 反转义
来源：http://dali.hywenlv.cn/Article/details/gtglmfscge.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.gaohongyu789.top/Article/details/gtppyyrymn.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.ehwqpu.com/Article/details/gthwsgmuqc.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.havefunace.top/Article/details/gtlwxddwfh.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yongpay.top/Article/details/gtrtolpkie.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hfpthk.cn/Article/details/gtkavxshjk.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.ydzc1.top/Article/details/gtnshjxfvf.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.ybcxt.top/Article/details/gtlfydghza.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.xziqi.cn/Article/details/gtdmqdalqx.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gtftixktfv.html

Py:   f"{1234567:,}"
来源：http://dali.sysykeji.top/Article/details/gtdqrewlff.html

PHP:  number_format(1234567);
来源：http://dali.dashuyun.cn/Article/details/gtmejmwrli.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gtyzktomqp.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.hnxiangtu.top/Article/details/gtmgfvckcf.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.nwbrower.top/Article/details/gttnwychqc.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hywenlv.cn/Article/details/gtxduiatlm.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yonumen.top/Article/details/gtgqxyoqhv.html

C#:   1234567.ToString("N0")
来源：http://dali.shuidangran.top/Article/details/gtkdprsemo.html

[E17] 首字母大写
来源：http://dali.dianchejie.cn/Article/details/gtpstuivvw.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.iojbl.cn/Article/details/gtomvjfzim.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.chenlongwang.top/Article/details/gtnribwxqw.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.nanxuanxn.top/Article/details/gtwjugicwu.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzzlbxvsg.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yanxiufei.cn/Article/details/gtmfklocuy.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.kuanghao11.cn/Article/details/gthkbfymws.html

Ruby: s.capitalize
来源：http://dali.ivvv.top/Article/details/gtyqhahnam.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.guowangkeji.top/Article/details/gthjigwmpa.html

[E18] 模板占位符替换
来源：http://dali.bjfxy.top/Article/details/gtqtrhdlis.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.snrcjt.cn/Article/details/gtxbxythkb.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hammf.cn/Article/details/gtrzggbidf.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zycfv.cn/Article/details/gtzyswqsxi.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.xuetiantiany.cn/Article/details/gtudevlrkd.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.kuanghao11.cn/Article/details/gtmivatkpo.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yanxiufei.cn/Article/details/gtpvkuxtfm.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.wangdashe.top/Article/details/gtfzvsbkna.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.c1oappe.top/Article/details/gtecsxigjp.html

[E19] 多行文本按行拆分
来源：http://dali.smart0.xyz/Article/details/gtvkcbeapw.html

Py:   s.splitlines()
来源：http://dali.nanxinkj.top/Article/details/gtgeclmzim.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvxvkejnw.html

JS:   s.split(/\r?\n/)
来源：http://dali.svipenyu.cn/Article/details/gtbbaxweky.html

TS:   s.split(/\r?\n/)
来源：http://dali.xylfe.cn/Article/details/gtppkntauo.html

Java: s.lines().toList()
来源：http://dali.meibo888.top/Article/details/gtzihdiwsx.html

Go:   strings.Split(s, "\n")
来源：http://dali.yvedp.cn/Article/details/gtjrnumaky.html

Ruby: s.lines
来源：http://dali.sweek.top/Article/details/gtifliyvls.html

C#:   s.Split('\n')
来源：http://dali.nanxuanxn.top/Article/details/gtfqyrhqwo.html

[E20] 判断字符串是否为空
来源：http://dali.tianlin.xyz/Article/details/gteihztypf.html

Py:   if not s:
来源：http://dali.zhoulong.xyz/Article/details/gtckitdqjz.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.redwolf501.top/Article/details/gtjlfcicto.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yj20258888.top/Article/details/gtdpqvyqaf.html

TS:   if (s === "") {}
来源：http://dali.nanxinkj.top/Article/details/gtiujgszmo.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhongyouzk.top/Article/details/gtfpwquheg.html

Go:   if s == "" {}
来源：http://dali.9152youxi.cn/Article/details/gtslgxwuzz.html

Ruby: if s.empty?
来源：http://dali.guannengcc.top/Article/details/gtlfmmlukn.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yj202588.top/Article/details/gtzpbbmzfi.html

[E21] 超长截断加省略号
来源：http://dali.shzxlz.cn/Article/details/gtfsuvokax.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zdqjudy.top/Article/details/gtkkkscaak.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.shzxlz.cn/Article/details/gtbzhzekuo.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.meibo888.top/Article/details/gtlflsnvbl.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.daria6918.cn/Article/details/gtfeoglzev.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.nanxinkj.top/Article/details/gtwgywkyto.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xziqi.cn/Article/details/gtdqndbzrc.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.shzxlz.cn/Article/details/gtvkywzbtq.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.wangshuangyany.cn/Article/details/gtzmolpnug.html

[E22] 字节长度与字符长度
来源：http://dali.pengpengdd.cyou/Article/details/gtmwfwfvel.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yueranfly.top/Article/details/gtjmywedts.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xinyue.icu/Article/details/gtmohtipoe.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jqgfzy.top/Article/details/gtgnipfyfp.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.feifeiyinyue.top/Article/details/gthsamkogk.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yuxming.cn/Article/details/gtikuruygv.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yueranfly.top/Article/details/gttkxhacyr.html

Ruby: s.bytesize;  s.length
来源：http://dali.cqqwz.cn/Article/details/gtncqdgfgn.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yj202588.top/Article/details/gtprwiipik.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtownzofav.html

F. 文件与目录
来源：http://dali.nanxinkj.top/Article/details/gthmukfnqf.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtbovofdhb.html

[F01] 读取整个文件
来源：http://dali.hywenlv.cn/Article/details/gtdjkftzqo.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.smart0.xyz/Article/details/gtuarvqdql.html

PHP:  file_get_contents("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtprojdayt.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jinqigufen.top/Article/details/gtbdrxephw.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.xziqi.cn/Article/details/gtroeasfmk.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhongyouzk.top/Article/details/gtnufjebcd.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jiagoushi.top/Article/details/gtiffmildk.html

Ruby: File.read("a.txt")
来源：http://dali.yj20258.top/Article/details/gtuszyafye.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwuweovao.html

[F02] 逐行读取文件
来源：http://dali.zhengqikj.top/Article/details/gtvgeczjfk.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xylfe.cn/Article/details/gtkvufohth.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtpwrdnvsx.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cucudq.cn/Article/details/gtyeggkxne.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.birdmap.top/Article/details/gtodvstolp.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zdqjudy.top/Article/details/gtfjnexkyi.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.shanyushiyangtech.top/Article/details/gtiunokhlz.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.redwolf501.top/Article/details/gtryscqcgm.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.9152youxi.cn/Article/details/gtonbxqbjw.html

[F03] 写入文件（覆盖）
来源：http://dali.fzhhl.top/Article/details/gtmzagrigk.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yuanzhike.top/Article/details/gtukospbxu.html


<!-- 参考信息 -->