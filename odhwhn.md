代发 wailian999

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.dianchejie.cn/Article/details/gtqutylweo.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yonumen.top/Article/details/gtwpgcknom.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yj20258.top/Article/details/gtygpkllzm.html

Go:   // 手写 map[T]int
来源：http://dali.zhiwuduotai.top/Article/details/gtjrffgzul.html

Ruby: arr.tally
来源：http://dali.quarkkingdee.top/Article/details/gtnmaffpwy.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jinqigufen.top/Article/details/gtkeblnamj.html

[D21] 判断是否包含某元素
来源：http://dali.smart0.xyz/Article/details/gtooreztvm.html

Py:   x in arr
来源：http://dali.xinyue.icu/Article/details/gtntowbmcb.html

PHP:  in_array($x, $arr, true);
来源：http://dali.nanxinkj.top/Article/details/gtlirhxwpj.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gtxlfdkkna.html

TS:   arr.includes(x)
来源：http://dali.gogol.net.cn/Article/details/gtygyvbaxz.html

Java: list.contains(x)
来源：http://dali.9152youxi.cn/Article/details/gtplaptyai.html

Go:   slices.Contains(arr, x)
来源：http://dali.yj202588.top/Article/details/gtxjhszhfy.html

Ruby: arr.include?(x)
来源：http://dali.yangfankeji.com/Article/details/gtqktfywja.html

C#:   list.Contains(x)
来源：http://dali.yongpay.top/Article/details/gtzqcqgxbs.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yj202588.top/Article/details/gtmuhnifbw.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.ppjwa.cn/Article/details/gtbppvbgeq.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.ywan-chungtsiang.top/Article/details/gteanalcgx.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtdunkjtne.html

TS:   [...arr];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdzequwaa.html

Java: new ArrayList<>(list);
来源：http://dali.zhiwuduotai.top/Article/details/gtoguzuzgx.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.pycfn.com/Article/details/gtzvbnsnyo.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jianghu66.top/Article/details/gtpgxvgixe.html

C#:   new List<int>(list);
来源：http://dali.cucudq.cn/Article/details/gtjqbpuqqt.html

[D23] reduce 累积计算
来源：http://dali.nanxuanxn.top/Article/details/gtjhttvzcy.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.hywenlv.cn/Article/details/gtrkztlvib.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.cheryme.top/Article/details/gtfunidwmz.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cashguo.top/Article/details/gtyikmpnkl.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yonumen.top/Article/details/gtcdvumkay.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.ybcxt.top/Article/details/gtwqssopgn.html

Go:   // 手写循环
来源：http://dali.yj20258888.top/Article/details/gtbineaqly.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.xuetiantiany.cn/Article/details/gtpcatuzsl.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zdqjudy.top/Article/details/gtwojcsdgx.html

[D24] 字典 / Map 基本操作
来源：http://dali.tianlin.xyz/Article/details/gtdlgtjgmh.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.0kj1m.cn/Article/details/gtajtkmrbk.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.hysaishi.cn/Article/details/gtxmbfayje.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hysaishi.cn/Article/details/gtstmpidby.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.bjfxy.top/Article/details/gtisppsnqv.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.xziqi.cn/Article/details/gtshktyfrf.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhengqikj.top/Article/details/gtyygvqmaf.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.iojbl.cn/Article/details/gtjpiegjap.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jqgfzy.top/Article/details/gtqjkyqouz.html

[D25] Set 集合去重与交并差
来源：http://dali.yvedp.cn/Article/details/gtokpeibjg.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.fengsongda.top/Article/details/gtsnqazpml.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.sufxvd.cn/Article/details/gtidguctxr.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.daxiang520.top/Article/details/gtafymgwwi.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hywenlv.cn/Article/details/gtlhpwqdse.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtujiwnojd.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yangfankeji.com/Article/details/gtelbjafhg.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhengqikj.top/Article/details/gtdbixujcb.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.dashuyun.cn/Article/details/gtjxqzsdwp.html

[D26] 数组转字符串
来源：http://dali.haohaochexian.top/Article/details/gtyucxyzdp.html

Py:   ", ".join(map(str, arr))
来源：http://dali.snrcjt.cn/Article/details/gtdowhsyoc.html

PHP:  implode(", ", $arr);
来源：http://dali.zycfv.cn/Article/details/gtjnibdrsg.html

JS:   arr.join(", ")
来源：http://dali.yongpay.top/Article/details/gtbtctmgaz.html

TS:   arr.join(", ")
来源：http://dali.birdmap.top/Article/details/gtnzonzpel.html

Java: String.join(", ", list)
来源：http://dali.yj20258888.top/Article/details/gtkntqpfll.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jyoumei.cn/Article/details/gtcnvxuwee.html

Ruby: arr.join(", ")
来源：http://dali.svipenyu.cn/Article/details/gtfxklusbi.html

C#:   string.Join(", ", list)
来源：http://dali.316326.xyz/Article/details/gtephygysu.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtfufjzasj.html

E. 字符串处理
来源：http://dali.fzhhl.top/Article/details/gtepodlxuv.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtrwqcfgqz.html

[E01] 拼接字符串
来源：http://dali.wangdashe.top/Article/details/gtsfvnjnqj.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.mhx1999.top/Article/details/gtvsmjsxab.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yvedp.cn/Article/details/gtjiskyfli.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.birdmap.top/Article/details/gtpmvlflbj.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.vqdsnc.cn/Article/details/gtleedxttu.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jlsjyb.cn/Article/details/gtnkbhqnlu.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.havefunace.top/Article/details/gtujxotnif.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.sweek.top/Article/details/gtoetbirqg.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.nwbrower.top/Article/details/gtnaiaslsv.html

[E02] 重复字符串
来源：http://dali.guowangkeji.top/Article/details/gtltwravpi.html

Py:   "ab" * 3
来源：http://dali.fzhhl.top/Article/details/gtjkbjbrrd.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yueranfly.top/Article/details/gtpjcvdvpp.html

JS:   "ab".repeat(3)
来源：http://dali.smart0.xyz/Article/details/gtdqiklxvq.html

TS:   "ab".repeat(3)
来源：http://dali.dashuyun.cn/Article/details/gtjwxvfjeh.html

Java: "ab".repeat(3)
来源：http://dali.guannengcc.top/Article/details/gtwmzlwdez.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.fzhhl.top/Article/details/gtqslcuozq.html

Ruby: "ab" * 3
来源：http://dali.hnxiangtu.top/Article/details/gtsiljqfjd.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.daria6918.cn/Article/details/gtekdlleas.html

[E03] 截取子串
来源：http://dali.feifeiyinyue.top/Article/details/gtatrbxxjg.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.xinyue.icu/Article/details/gtwxdrdteo.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.cashguo.top/Article/details/gtibgxddik.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zdqjudy.top/Article/details/gtndkclsiz.html

TS:   s.slice(1, 4)
来源：http://dali.guowangkeji.top/Article/details/gteurbtyde.html

Java: s.substring(1, 4)
来源：http://dali.wangshuangyany.cn/Article/details/gtdefbvgyd.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jinqigfzy.top/Article/details/gtxlbryynz.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.birdmap.top/Article/details/gtjwmxauiu.html

C#:   s.Substring(1, 3)
来源：http://dali.nwbrower.top/Article/details/gtcrcfkzea.html

[E04] 查找子串位置
来源：http://dali.iojbl.cn/Article/details/gtfyjigfaz.html

Py:   s.find("x");  s.index("x")
来源：http://dali.aizwys.cn/Article/details/gtzauegdnm.html

PHP:  strpos($s, "x");
来源：http://dali.pengpengdd.cyou/Article/details/gtaeiwznkv.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.sxryk.cn/Article/details/gtwwvnusgw.html

TS:   s.indexOf("x")
来源：http://dali.chenjidiqi.icu/Article/details/gttoqmumyz.html

Java: s.indexOf("x")
来源：http://dali.guannengcc.top/Article/details/gtgflbjxfq.html

Go:   strings.Index(s, "x")
来源：http://dali.tanke756.top/Article/details/gtbwbcivwd.html

Ruby: s.index("x")
来源：http://dali.snrcjt.cn/Article/details/gtapdrgtzd.html

C#:   s.IndexOf("x")
来源：http://dali.0kj1m.cn/Article/details/gtkzggduvl.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.gzhubu.top/Article/details/gtfejuekkq.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yonumen.top/Article/details/gtwlpqbbzv.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.hammf.cn/Article/details/gtegopyhjk.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenjidiqi.icu/Article/details/gtletmihab.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yangfankeji.com/Article/details/gthojavsku.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.nwbrower.top/Article/details/gtahlikczx.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.feifeiyinyue.top/Article/details/gtatcgmahl.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.vqdsnc.cn/Article/details/gthgzshanm.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.fengsongda.top/Article/details/gttyuwjhkx.html

[E06] 替换子串
来源：http://dali.0kj1m.cn/Article/details/gtcqxhbkmx.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.guowangkeji.top/Article/details/gtdixjejfw.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.bjfxy.top/Article/details/gtafcpcjsq.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zycfv.cn/Article/details/gtjhselwsm.html

TS:   s.replaceAll("a", "b")
来源：http://dali.guannengcc.top/Article/details/gthbgfhnpp.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yueranfly.top/Article/details/gtvuyefefg.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jiagoushi.top/Article/details/gtbhcigdke.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.chenjidiqi.icu/Article/details/gturgpbzba.html

C#:   s.Replace("a", "b")
来源：http://dali.guannengcc.top/Article/details/gtillmiquw.html

[E07] 按分隔符拆分
来源：http://dali.andypj.xyz/Article/details/gtrvxzjlew.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.aibaodan.cn/Article/details/gtowfesufh.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.tianlin.xyz/Article/details/gtiynvwhvv.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jlsjyb.cn/Article/details/gttfeswwri.html

TS:   s.split(",")
来源：http://dali.xziqi.cn/Article/details/gtyfprwqvp.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.xuanzx.com/Article/details/gtazqmcfar.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.chenlongwang.top/Article/details/gtnywbuzge.html

Ruby: s.split(",");  s.split
来源：http://dali.hfpthk.cn/Article/details/gtlecrcoiv.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.cheryme.top/Article/details/gtoyujbtxc.html

[E08] 数组按分隔符合并
来源：http://dali.hywenlv.cn/Article/details/gtqyyytblr.html

Py:   ",".join(items)
来源：http://dali.aizwys.cn/Article/details/gtzmusforl.html

PHP:  implode(",", $items);
来源：http://dali.c1oappe.top/Article/details/gtkunxlhqb.html

JS:   items.join(",")
来源：http://dali.xziqi.cn/Article/details/gtrylrwunv.html

TS:   items.join(",")
来源：http://dali.zycfv.cn/Article/details/gtamcvxpqs.html

Java: String.join(",", items)
来源：http://dali.yangfankeji.com/Article/details/gtldlsoegk.html

Go:   strings.Join(items, ",")
来源：http://dali.hnxiangtu.top/Article/details/gtzmdncbzo.html

Ruby: items.join(",")
来源：http://dali.vqdsnc.cn/Article/details/gtnvvvgrhj.html

C#:   string.Join(",", items)
来源：http://dali.gotoacloud.top/Article/details/gtjkrabcvk.html

[E09] 去除所有空白字符
来源：http://dali.daxiang520.top/Article/details/gtzyxinwax.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.dashuyun.cn/Article/details/gtutxoxetx.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.cheryme.top/Article/details/gthcotunra.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.daxiang520.top/Article/details/gtaxqliaem.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.dianchejie.cn/Article/details/gtwtlpeakf.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.cqqwz.cn/Article/details/gtjmnovxec.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.cqqwz.cn/Article/details/gthzzfyhwq.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaylamfqn.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.andypj.xyz/Article/details/gtrkxskpey.html

[E10] 左侧补零 / 定长填充
来源：http://dali.guowangkeji.top/Article/details/gtvcijxqjy.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.cashguo.top/Article/details/gttokwktkq.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.daxiang520.top/Article/details/gtsninoidk.html

JS:   "7".padStart(3, "0")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdybdhqxy.html

TS:   "7".padStart(3, "0")
来源：http://dali.wangdashe.top/Article/details/gtdltzpybq.html

Java: String.format("%03d", 7)
来源：http://dali.tian-w.cn/Article/details/gtvzjhliza.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.cheryme.top/Article/details/gtqlsiohbb.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.gzhubu.top/Article/details/gtutyszmea.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.chenlongwang.top/Article/details/gtijhgqqmd.html

[E11] 反转字符串
来源：http://dali.jqgufenzy.top/Article/details/gtrmjtgjje.html

Py:   s[::-1]
来源：http://dali.yangfankeji.com/Article/details/gtdalkhihw.html

PHP:  strrev($s);
来源：http://dali.feifeiyinyue.top/Article/details/gtpapsmktj.html

JS:   [...s].reverse().join("")
来源：http://dali.snrcjt.cn/Article/details/gtjigqckao.html

TS:   [...s].reverse().join("")
来源：http://dali.cheryme.top/Article/details/gtcnybgjpk.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhongyouzk.top/Article/details/gtvmufqrtq.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yangfankeji.com/Article/details/gtpymwlvks.html

Ruby: s.reverse
来源：http://dali.yvedp.cn/Article/details/gtobuzkenz.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.iojbl.cn/Article/details/gtlcxjdnfc.html

[E12] 统计某字符出现次数
来源：http://dali.pengpengdd.cyou/Article/details/gtbaoohhlr.html

Py:   s.count("a")
来源：http://dali.zhixingplan.top/Article/details/gtgjvtridv.html

PHP:  substr_count($s, "a");
来源：http://dali.cashguo.top/Article/details/gtsownrztg.html

JS:   s.split("a").length - 1
来源：http://dali.dianchejie.cn/Article/details/gtjtahdgtn.html

TS:   s.split("a").length - 1
来源：http://dali.fengsongda.top/Article/details/gtifpftnte.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.tianlin.xyz/Article/details/gtlzfiedik.html

Go:   strings.Count(s, "a")
来源：http://dali.cheryme.top/Article/details/gtaejpbznc.html

Ruby: s.count("a")
来源：http://dali.jiagoushi.top/Article/details/gtlyrzgljt.html

C#:   s.Count(c => c == 'a')
来源：http://dali.snrcjt.cn/Article/details/gtcdeliefi.html

[E13] 逐字符遍历
来源：http://dali.iojbl.cn/Article/details/gtticmlcya.html

Py:   for ch in s: print(ch)
来源：http://dali.daria6918.cn/Article/details/gtmrempiof.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.shuidangran.top/Article/details/gtxaxbqayp.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hongshengwenyu.top/Article/details/gtuqwlgtfb.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.guowangkeji.top/Article/details/gtnwnbtbfb.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyeucozeu.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ppjwa.cn/Article/details/gtqtpmvist.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.gaohongyu789.top/Article/details/gtwoxcdoou.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.aibaodan.cn/Article/details/gtzkujcyrg.html

[E14] URL 编码与 Base64
来源：http://dali.fzhhl.top/Article/details/gtwbhxjvpe.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zdqjudy.top/Article/details/gttjvfuesk.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yuanzhike.top/Article/details/gtuzovqhwz.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.pycfn.com/Article/details/gtvanfradu.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtukywliti.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.dianchejie.cn/Article/details/gtmjctehcp.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.pycfn.com/Article/details/gtgwttlwlr.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jinqigfzy.top/Article/details/gtkowylkft.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.tianlin.xyz/Article/details/gtspiahsna.html

[E15] HTML 转义 / 反转义
来源：http://dali.nwbrower.top/Article/details/gtlsdpmuzu.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.svipenyu.cn/Article/details/gtrxsvnphu.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.birdmap.top/Article/details/gthxnkzpkl.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.sweek.top/Article/details/gtjvqpfmlj.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yuxming.cn/Article/details/gtsvkxhrtu.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.gaohongyu789.top/Article/details/gtctdqkucy.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.andypj.xyz/Article/details/gtzalafjye.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.nanxinkj.top/Article/details/gtzsmdqtne.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hysaishi.cn/Article/details/gtmqprhjgn.html

[E16] 数字千分位
来源：http://dali.sxryk.cn/Article/details/gtsuifzpbq.html

Py:   f"{1234567:,}"
来源：http://dali.hfpthk.cn/Article/details/gtqvgjvapf.html

PHP:  number_format(1234567);
来源：http://dali.aibaodan.cn/Article/details/gtcyahmumn.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.hysaishi.cn/Article/details/gtazjmwmge.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.haohaochexian.top/Article/details/gtqwchbilp.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.316326.xyz/Article/details/gtppjnjjer.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.ydzc1.top/Article/details/gtjurvsrjc.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.pengpengdd.cyou/Article/details/gtwpyacfqt.html

C#:   1234567.ToString("N0")
来源：http://dali.zhixingplan.top/Article/details/gtepygique.html

[E17] 首字母大写
来源：http://dali.andypj.xyz/Article/details/gtwzvhclfz.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdkfqfukb.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.birdmap.top/Article/details/gtjcdfsdth.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ydzc1.top/Article/details/gtvgkpubzv.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.guowangkeji.top/Article/details/gtwndopezr.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yj20258.top/Article/details/gtctaimysq.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhengqikj.top/Article/details/gtmgmhxzkh.html

Ruby: s.capitalize
来源：http://dali.haohaochexian.top/Article/details/gtjldhbxew.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvkexxpsr.html

[E18] 模板占位符替换
来源：http://dali.cucudq.cn/Article/details/gtacpydpnp.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.316326.xyz/Article/details/gtghzdqjoc.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yueranfly.top/Article/details/gtrgarjiux.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.shanyushiyangtech.top/Article/details/gtakoatubf.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.cheryme.top/Article/details/gtiqbdzjdp.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhoulong.xyz/Article/details/gttwkwdkjy.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.daria6918.cn/Article/details/gtsxuopxob.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zdqjudy.top/Article/details/gtrprxybxr.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.gzhubu.top/Article/details/gtqluzkaoy.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gtrzbklqqk.html

Py:   s.splitlines()
来源：http://dali.sxryk.cn/Article/details/gtitwxnanu.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gtrkahvoyp.html

JS:   s.split(/\r?\n/)
来源：http://dali.ydzc1.top/Article/details/gtutnwxevn.html

TS:   s.split(/\r?\n/)
来源：http://dali.hywenlv.cn/Article/details/gtkozvkuef.html

Java: s.lines().toList()
来源：http://dali.cqqwz.cn/Article/details/gtaxtbmaml.html

Go:   strings.Split(s, "\n")
来源：http://dali.jiagoushi.top/Article/details/gtenglabcu.html

Ruby: s.lines
来源：http://dali.meibo888.top/Article/details/gtwlfnsobi.html

C#:   s.Split('\n')
来源：http://dali.yj20258.top/Article/details/gtwxflxfft.html

[E20] 判断字符串是否为空
来源：http://dali.smart0.xyz/Article/details/gtpcabmykd.html

Py:   if not s:
来源：http://dali.gogol.net.cn/Article/details/gtepvlczac.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.sysykeji.top/Article/details/gtobyaysqk.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.xuanzx.com/Article/details/gtblsivfjd.html

TS:   if (s === "") {}
来源：http://dali.bjfxy.top/Article/details/gtkglwtlgt.html

Java: if (s.isEmpty()) {}
来源：http://dali.meibo888.top/Article/details/gtzleyzvxj.html

Go:   if s == "" {}
来源：http://dali.zhoulong.xyz/Article/details/gtunkodflb.html

Ruby: if s.empty?
来源：http://dali.chenjidiqi.icu/Article/details/gtgstktxdu.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.pycfn.com/Article/details/gttoirbjgz.html

[E21] 超长截断加省略号
来源：http://dali.gotoacloud.top/Article/details/gtvgkjixhy.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.fzhhl.top/Article/details/gtclsnwsmp.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.dianchejie.cn/Article/details/gtkoudfuuj.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.0kj1m.cn/Article/details/gtrdwqucrc.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.feifeiyinyue.top/Article/details/gtyjotgejw.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.bjfxy.top/Article/details/gtlaybpfpy.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hfpthk.cn/Article/details/gtxjzpooyk.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.daxiang520.top/Article/details/gtvjdwltax.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.cdnleiting.top/Article/details/gtudbbojxk.html

[E22] 字节长度与字符长度
来源：http://dali.zhoulong.xyz/Article/details/gtkjweiczz.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.gotoacloud.top/Article/details/gtrbpwieee.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gogol.net.cn/Article/details/gtsvmvdvll.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfzisynfj.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yj20258.top/Article/details/gtvioyviol.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.tian-w.cn/Article/details/gtjifjkcbq.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.ppjwa.cn/Article/details/gtxzldidzu.html

Ruby: s.bytesize;  s.length
来源：http://dali.chenzaomai.com/Article/details/gtinpptbne.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yonumen.top/Article/details/gtjjmoomox.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtefantwhx.html

F. 文件与目录
来源：http://dali.gotoacloud.top/Article/details/gtiezocgcn.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtzvbxjprn.html

[F01] 读取整个文件
来源：http://dali.sxryk.cn/Article/details/gtwltumsrx.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.guowangkeji.top/Article/details/gtkqjwrlix.html

PHP:  file_get_contents("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtcgsioxrb.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.dashuyun.cn/Article/details/gtyxzmyebo.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.dashuyun.cn/Article/details/gtyivjeylo.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gtweowmlmn.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.shzxlz.cn/Article/details/gtozlahmkm.html

Ruby: File.read("a.txt")
来源：http://dali.ivvv.top/Article/details/gtsyrixftb.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gtbulftvev.html

[F02] 逐行读取文件
来源：http://dali.dashuyun.cn/Article/details/gtkzrxsrjm.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhengqikj.top/Article/details/gtrzdavtee.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yuanzhike.top/Article/details/gttrmjukmt.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yueranfly.top/Article/details/gtauzayajq.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cucudq.cn/Article/details/gtvvhpbtay.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.guowangkeji.top/Article/details/gtpywwqqzj.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.wangdashe.top/Article/details/gtfqplzcyv.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.aizwys.cn/Article/details/gtvemwausy.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.shzxlz.cn/Article/details/gtltjqcquu.html

[F03] 写入文件（覆盖）
来源：http://dali.chenjidiqi.icu/Article/details/gtctqpogoo.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.shuidangran.top/Article/details/gtuqgxrcbi.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yuxming.cn/Article/details/gtqbuhkdza.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hnxiangtu.top/Article/details/gtmhfdzyqb.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuidrkqkk.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.9152youxi.cn/Article/details/gtninttspf.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.gotoacloud.top/Article/details/gtcbfblwbd.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.chenlongwang.top/Article/details/gtxhhdllld.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hfpthk.cn/Article/details/gtzbaetrpf.html

[F04] 追加写入文件
来源：http://dali.fzhhl.top/Article/details/gtdhipwgic.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.smart0.xyz/Article/details/gttrewteen.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.andypj.xyz/Article/details/gtjlxxtebb.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.dianchejie.cn/Article/details/gtgdmrxtux.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.vqdsnc.cn/Article/details/gtrufvpear.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.cheryme.top/Article/details/gtdjaqehqt.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.chenjidiqi.icu/Article/details/gtczosxjan.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yuxming.cn/Article/details/gtyrziujiz.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhiwuduotai.top/Article/details/gtnljotzbr.html


<!-- 参考信息 -->