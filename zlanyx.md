代发 wailian999

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.quarkkingdee.top/Article/details/gtybvpedxh.html

Go:   // 手写双层循环
来源：http://dali.zdqjudy.top/Article/details/gtlleiiqtv.html

Ruby: nested.flatten
来源：http://dali.dianchejie.cn/Article/details/gtivgmugsq.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hnxiangtu.top/Article/details/gtrwjnnxed.html

[D19] 按字段分组
来源：http://dali.hongshengwenyu.top/Article/details/gtpvnbwhip.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.dashuyun.cn/Article/details/gtpagdmvdh.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.chenzaomai.com/Article/details/gtmryrpnkb.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.hfpthk.cn/Article/details/gtsmacyawz.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.dianchejie.cn/Article/details/gtmffmcgoi.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhengqikj.top/Article/details/gtezvynjro.html

Go:   // 手写 map[string][]T
来源：http://dali.nanxinkj.top/Article/details/gtsljpntjz.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hfpthk.cn/Article/details/gtwyjxaqpi.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.pycfn.com/Article/details/gtsjwnktff.html

[D20] 统计每个元素出现次数
来源：http://dali.nanxinkj.top/Article/details/gtbvdaitic.html

Py:   Counter(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtulmolqhj.html

PHP:  array_count_values($arr);
来源：http://dali.zycfv.cn/Article/details/gtxpnfrwqw.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jqgufenzy.top/Article/details/gtiknyebii.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhengqikj.top/Article/details/gtdthbsckp.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jqgfzy.top/Article/details/gtbiwvhxal.html

Go:   // 手写 map[T]int
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqacsiscy.html

Ruby: arr.tally
来源：http://dali.gogol.net.cn/Article/details/gtktwlaeqq.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jinghuilouyu.cn/Article/details/gtosophbyv.html

[D21] 判断是否包含某元素
来源：http://dali.feifeiyinyue.top/Article/details/gtjcgdlkgt.html

Py:   x in arr
来源：http://dali.jianghu66.top/Article/details/gtzrcpieio.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jiagoushi.top/Article/details/gtbfykjlsy.html

JS:   arr.includes(x)
来源：http://dali.jlsjyb.cn/Article/details/gtxaqdmsjc.html

TS:   arr.includes(x)
来源：http://dali.ybcxt.top/Article/details/gtprvqlqpu.html

Java: list.contains(x)
来源：http://dali.daria6918.cn/Article/details/gtytgxuwvs.html

Go:   slices.Contains(arr, x)
来源：http://dali.cucudq.cn/Article/details/gtxhiteyjz.html

Ruby: arr.include?(x)
来源：http://dali.jinqigufen.top/Article/details/gtfqdrvsip.html

C#:   list.Contains(x)
来源：http://dali.vqdsnc.cn/Article/details/gtsqtigerj.html

[D22] 复制数组（避免共享引用）
来源：http://dali.andypj.xyz/Article/details/gtvrkrvrnm.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.cashguo.top/Article/details/gtbsfsjste.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yueranfly.top/Article/details/gttwvcrfqz.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtskfmkhqu.html

TS:   [...arr];
来源：http://dali.guowangkeji.top/Article/details/gtwpsqxuod.html

Java: new ArrayList<>(list);
来源：http://dali.zdqjudy.top/Article/details/gtvmnljekz.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.dianchejie.cn/Article/details/gtrbiarmjd.html

Ruby: arr.dup;  arr.clone
来源：http://dali.cqqwz.cn/Article/details/gthbmcyxmc.html

C#:   new List<int>(list);
来源：http://dali.svipenyu.cn/Article/details/gtgdhlcqxb.html

[D23] reduce 累积计算
来源：http://dali.yanxiufei.cn/Article/details/gtofomarxg.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzdgvcvko.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yongpay.top/Article/details/gtlqhescxy.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.kuanghao11.cn/Article/details/gttjyxtbhx.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.fzhhl.top/Article/details/gtybfggmsb.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.vqdsnc.cn/Article/details/gtaznpzaag.html

Go:   // 手写循环
来源：http://dali.pengpengdd.cyou/Article/details/gtqkgobgya.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.ydzc1.top/Article/details/gtspczzhnj.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.xinyue.icu/Article/details/gtsyuvnlwi.html

[D24] 字典 / Map 基本操作
来源：http://dali.havefunace.top/Article/details/gtrqzyupbo.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.quarkkingdee.top/Article/details/gtevoffadk.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yonumen.top/Article/details/gtmyhrsszd.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.meibo888.top/Article/details/gtrlwxelkk.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.guowangkeji.top/Article/details/gtctkbuqlr.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.fengsongda.top/Article/details/gteyaplbvl.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.ybcxt.top/Article/details/gtbsxyrqad.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.chenjidiqi.icu/Article/details/gtaokrkvjg.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yongpay.top/Article/details/gtavcjtygs.html

[D25] Set 集合去重与交并差
来源：http://dali.sxryk.cn/Article/details/gtlxyugqbx.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yuxming.cn/Article/details/gtfouaaupr.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yuxming.cn/Article/details/gttdnkgako.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.haohaochexian.top/Article/details/gttwofvmuu.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhongyouzk.top/Article/details/gtlqrstvya.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.andypj.xyz/Article/details/gtpcfsjzhm.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.ivvv.top/Article/details/gtsfvggogy.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.xylfe.cn/Article/details/gtxhioterz.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.shzxlz.cn/Article/details/gtyogpnowy.html

[D26] 数组转字符串
来源：http://dali.hfpthk.cn/Article/details/gtemypeios.html

Py:   ", ".join(map(str, arr))
来源：http://dali.havefunace.top/Article/details/gtpvdylwpj.html

PHP:  implode(", ", $arr);
来源：http://dali.yvedp.cn/Article/details/gtqcvannsm.html

JS:   arr.join(", ")
来源：http://dali.nanxuanxn.top/Article/details/gtzmqoxrob.html

TS:   arr.join(", ")
来源：http://dali.xuanzx.com/Article/details/gtzavhplwd.html

Java: String.join(", ", list)
来源：http://dali.cqqwz.cn/Article/details/gtvsiyqiij.html

Go:   strings.Join(strs, ", ")
来源：http://dali.daxiang520.top/Article/details/gtgfgjsvzi.html

Ruby: arr.join(", ")
来源：http://dali.hammf.cn/Article/details/gtqnowfhac.html

C#:   string.Join(", ", list)
来源：http://dali.jiagoushi.top/Article/details/gtdvqzgdml.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtwuffndaw.html

E. 字符串处理
来源：http://dali.316326.xyz/Article/details/gtqlnxwkrw.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gthcvqjfhq.html

[E01] 拼接字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtyvhucwpd.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.sufxvd.cn/Article/details/gtyrnrbkjz.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.kuanghao11.cn/Article/details/gtizsammzm.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.fengsongda.top/Article/details/gttwynoysw.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcxtdwzoj.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.chenzaomai.com/Article/details/gtpuudaupf.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.hammf.cn/Article/details/gtsyvzwydq.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhongyouzk.top/Article/details/gtfsiztgeo.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhixingplan.top/Article/details/gtouzoylfn.html

[E02] 重复字符串
来源：http://dali.cheryme.top/Article/details/gtngmaqmvl.html

Py:   "ab" * 3
来源：http://dali.ybcxt.top/Article/details/gtygrlsqce.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yongpay.top/Article/details/gtqvyzwibu.html

JS:   "ab".repeat(3)
来源：http://dali.nanxuanxn.top/Article/details/gtzbgcntvp.html

TS:   "ab".repeat(3)
来源：http://dali.zhengqikj.top/Article/details/gtypabydke.html

Java: "ab".repeat(3)
来源：http://dali.xinyue.icu/Article/details/gtdezmxrdj.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yueranfly.top/Article/details/gtthnaoqls.html

Ruby: "ab" * 3
来源：http://dali.shuidangran.top/Article/details/gtshpypcpj.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.mhx1999.top/Article/details/gtceylbrma.html

[E03] 截取子串
来源：http://dali.redwolf501.top/Article/details/gtqewespkc.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.quarkkingdee.top/Article/details/gtlsreupdm.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yueranfly.top/Article/details/gtpvtvobsy.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmpnyaxgx.html

TS:   s.slice(1, 4)
来源：http://dali.ppjwa.cn/Article/details/gtknhkkdqu.html

Java: s.substring(1, 4)
来源：http://dali.quarkkingdee.top/Article/details/gtgnhctfkc.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.316326.xyz/Article/details/gtaifzqwng.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.nanxinkj.top/Article/details/gtxxxwozzx.html

C#:   s.Substring(1, 3)
来源：http://dali.nanxinkj.top/Article/details/gtzjfuufym.html

[E04] 查找子串位置
来源：http://dali.smart0.xyz/Article/details/gtwkrqdfwk.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsuwqgbdy.html

PHP:  strpos($s, "x");
来源：http://dali.pengpengdd.cyou/Article/details/gtdnyqxsfg.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.cdnleiting.top/Article/details/gtzfgdxcns.html

TS:   s.indexOf("x")
来源：http://dali.birdmap.top/Article/details/gtgpaigeht.html

Java: s.indexOf("x")
来源：http://dali.zhongyouzk.top/Article/details/gtnyedpmml.html

Go:   strings.Index(s, "x")
来源：http://dali.tanke756.top/Article/details/gtxkxmlzko.html

Ruby: s.index("x")
来源：http://dali.9152youxi.cn/Article/details/gtjoxdovuy.html

C#:   s.IndexOf("x")
来源：http://dali.c1oappe.top/Article/details/gtgcsqmret.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.wangdashe.top/Article/details/gtxpvngtdd.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.ivvv.top/Article/details/gtibnrfgym.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yj20258888.top/Article/details/gtbjrkfsop.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.pycfn.com/Article/details/gtfiulhjtc.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jqgufenzy.top/Article/details/gthslxajll.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinqigufen.top/Article/details/gtsidojarn.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yuxming.cn/Article/details/gtxapsmffg.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.xziqi.cn/Article/details/gtphfvjtqr.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.9152youxi.cn/Article/details/gtciflemsa.html

[E06] 替换子串
来源：http://dali.mhx1999.top/Article/details/gtqdwvilos.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.svipenyu.cn/Article/details/gtgfunxoos.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gtytqbxowe.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xuanzx.com/Article/details/gtvkxwlcig.html

TS:   s.replaceAll("a", "b")
来源：http://dali.gotoacloud.top/Article/details/gtwskwjaxh.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.dianchejie.cn/Article/details/gtlqhoiuxa.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtffgtktmx.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhiwuduotai.top/Article/details/gtlywttykg.html

C#:   s.Replace("a", "b")
来源：http://dali.gaohongyu789.top/Article/details/gtnsslmtfc.html

[E07] 按分隔符拆分
来源：http://dali.kuanghao11.cn/Article/details/gtvjwzupol.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.gzhubu.top/Article/details/gtzjyzlfzq.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yuxming.cn/Article/details/gtmyicvoge.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.iojbl.cn/Article/details/gtirpaszug.html

TS:   s.split(",")
来源：http://dali.jinqigfzy.top/Article/details/gtgwsqckkf.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.cqqwz.cn/Article/details/gtgmeggexi.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.guannengcc.top/Article/details/gtaqussseq.html

Ruby: s.split(",");  s.split
来源：http://dali.tanke756.top/Article/details/gtvjxgceic.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yanxiufei.cn/Article/details/gtkjjmagpz.html

[E08] 数组按分隔符合并
来源：http://dali.hnqzz.top/Article/details/gtpcwewyxq.html

Py:   ",".join(items)
来源：http://dali.jianghu66.top/Article/details/gtzsoabbht.html

PHP:  implode(",", $items);
来源：http://dali.xylfe.cn/Article/details/gtzzxhlcqz.html

JS:   items.join(",")
来源：http://dali.feifeiyinyue.top/Article/details/gtexqwqrfs.html

TS:   items.join(",")
来源：http://dali.ydzc1.top/Article/details/gtbzcnmovq.html

Java: String.join(",", items)
来源：http://dali.gaohongyu789.top/Article/details/gtpbahwkst.html

Go:   strings.Join(items, ",")
来源：http://dali.ivvv.top/Article/details/gtithfrkru.html

Ruby: items.join(",")
来源：http://dali.hnqzz.top/Article/details/gtkzutnknn.html

C#:   string.Join(",", items)
来源：http://dali.feifeiyinyue.top/Article/details/gtiqtrdtvk.html

[E09] 去除所有空白字符
来源：http://dali.zhongyouzk.top/Article/details/gtdoudziol.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yanxiufei.cn/Article/details/gtsiqgyzts.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.ydzc1.top/Article/details/gtrrfewaor.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.haohaochexian.top/Article/details/gtmlidjryh.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jiagoushi.top/Article/details/gtavrxadaq.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtftivzjee.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.hongshengwenyu.top/Article/details/gtznrzdzuy.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.cashguo.top/Article/details/gtidjdwpcu.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.cucudq.cn/Article/details/gthyshddrb.html

[E10] 左侧补零 / 定长填充
来源：http://dali.svipenyu.cn/Article/details/gtoixgrpzo.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hongshengwenyu.top/Article/details/gtxnyxpgmc.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.nanxuanxn.top/Article/details/gtpjrtqicp.html

JS:   "7".padStart(3, "0")
来源：http://dali.jqgufenzy.top/Article/details/gtqcqyhygx.html

TS:   "7".padStart(3, "0")
来源：http://dali.feifeiyinyue.top/Article/details/gtropoumnd.html

Java: String.format("%03d", 7)
来源：http://dali.yongpay.top/Article/details/gtjqqxhnys.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.chenjidiqi.icu/Article/details/gttsgtszsj.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jyoumei.cn/Article/details/gtaiibkfqj.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqleevgov.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gttcrqfxdr.html

Py:   s[::-1]
来源：http://dali.aizwys.cn/Article/details/gtnrxqjguy.html

PHP:  strrev($s);
来源：http://dali.yanxiufei.cn/Article/details/gtqdgxdyvb.html

JS:   [...s].reverse().join("")
来源：http://dali.zdqjudy.top/Article/details/gtdnolnogi.html

TS:   [...s].reverse().join("")
来源：http://dali.xziqi.cn/Article/details/gtbewdjsjt.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.gogol.net.cn/Article/details/gtiluzbefx.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.0kj1m.cn/Article/details/gtwsxryyih.html

Ruby: s.reverse
来源：http://dali.jinqigfzy.top/Article/details/gtgeukbfnq.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.snrcjt.cn/Article/details/gttvmohwen.html

[E12] 统计某字符出现次数
来源：http://dali.cdnleiting.top/Article/details/gtpatupgnf.html

Py:   s.count("a")
来源：http://dali.cdnleiting.top/Article/details/gttihnuajj.html

PHP:  substr_count($s, "a");
来源：http://dali.chenjidiqi.icu/Article/details/gtlgpxpnas.html

JS:   s.split("a").length - 1
来源：http://dali.shanyushiyangtech.top/Article/details/gtnmdmqzqb.html

TS:   s.split("a").length - 1
来源：http://dali.sweek.top/Article/details/gtowpctyot.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jqgufenzy.top/Article/details/gtedsgxdzy.html

Go:   strings.Count(s, "a")
来源：http://dali.jinghuilouyu.cn/Article/details/gtdrlkznqn.html

Ruby: s.count("a")
来源：http://dali.pycfn.com/Article/details/gttfiyqxwo.html

C#:   s.Count(c => c == 'a')
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgxhzwjfe.html

[E13] 逐字符遍历
来源：http://dali.daria6918.cn/Article/details/gtxlmjrzxi.html

Py:   for ch in s: print(ch)
来源：http://dali.redwolf501.top/Article/details/gtqizpczry.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtokrmnxpp.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtygoovqtc.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.pycfn.com/Article/details/gtoxvpvhyl.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.316326.xyz/Article/details/gtqeudltqh.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.pycfn.com/Article/details/gtasnpmnek.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.tianlin.xyz/Article/details/gtveuydkuc.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jiagoushi.top/Article/details/gtayezwdde.html

[E14] URL 编码与 Base64
来源：http://dali.nwbrower.top/Article/details/gtozrazzkw.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yangfankeji.com/Article/details/gtoljxxqvj.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.guannengcc.top/Article/details/gtwzbfucnt.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.ppjwa.cn/Article/details/gtldwsvkfr.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jinqigufen.top/Article/details/gtmmftzfsi.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.bjfxy.top/Article/details/gtfkvagqtm.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jianghu66.top/Article/details/gtmlzjfxwz.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yj202588.top/Article/details/gtjbmqkdba.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhixingplan.top/Article/details/gtbehqwhkq.html

[E15] HTML 转义 / 反转义
来源：http://dali.aibaodan.cn/Article/details/gtjktzewmu.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.gotoacloud.top/Article/details/gthlsmgksn.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtwsluizby.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.nanxinkj.top/Article/details/gtnjrtkpzn.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxezzzqhw.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.nwbrower.top/Article/details/gtkbkledqk.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzheuilcp.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hywenlv.cn/Article/details/gtzaqhfuzv.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.haohaochexian.top/Article/details/gtftbgelsv.html

[E16] 数字千分位
来源：http://dali.mhx1999.top/Article/details/gtkhklbusl.html

Py:   f"{1234567:,}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttwjygnij.html

PHP:  number_format(1234567);
来源：http://dali.wangshuangyany.cn/Article/details/gtxcoktqdj.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.shzxlz.cn/Article/details/gtwcjihqhz.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.vqdsnc.cn/Article/details/gthdziqype.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.fengsongda.top/Article/details/gtkteiocyq.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.andypj.xyz/Article/details/gtvjadjfch.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.iojbl.cn/Article/details/gtckymhcgo.html

C#:   1234567.ToString("N0")
来源：http://dali.shangyingyoupin.top/Article/details/gtkdbsxjuc.html

[E17] 首字母大写
来源：http://dali.yj202588.top/Article/details/gtxexypkwu.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.sufxvd.cn/Article/details/gtkbcwnpaa.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.cucudq.cn/Article/details/gtissqzlot.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sxryk.cn/Article/details/gtmmymjfpw.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtclljjiqi.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.shzxlz.cn/Article/details/gtogipysib.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zdqjudy.top/Article/details/gtgudocedu.html

Ruby: s.capitalize
来源：http://dali.vqdsnc.cn/Article/details/gtipkxyzoj.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.gotoacloud.top/Article/details/gtkofdduuj.html

[E18] 模板占位符替换
来源：http://dali.hysaishi.cn/Article/details/gtzaxjxsia.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.quarkkingdee.top/Article/details/gtcrvcgctb.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yuanzhike.top/Article/details/gtvrxxgeyy.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jiagoushi.top/Article/details/gtdhnaqbas.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.9152youxi.cn/Article/details/gtezogfflq.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.sweek.top/Article/details/gtxqykbzyj.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.daxiang520.top/Article/details/gtmwgkqryn.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.hnxiangtu.top/Article/details/gtynxtiffw.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.chenjidiqi.icu/Article/details/gtralcxgno.html

[E19] 多行文本按行拆分
来源：http://dali.0kj1m.cn/Article/details/gtgrqjgbry.html

Py:   s.splitlines()
来源：http://dali.svipenyu.cn/Article/details/gtevnhpopl.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhongyouzk.top/Article/details/gtedjfcrri.html

JS:   s.split(/\r?\n/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuaksttts.html

TS:   s.split(/\r?\n/)
来源：http://dali.shzxlz.cn/Article/details/gtotgsqeur.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gtrfpzfylk.html

Go:   strings.Split(s, "\n")
来源：http://dali.iojbl.cn/Article/details/gtwvgtychn.html

Ruby: s.lines
来源：http://dali.jianghu66.top/Article/details/gttbztpuey.html

C#:   s.Split('\n')
来源：http://dali.nwbrower.top/Article/details/gtdsckfigx.html

[E20] 判断字符串是否为空
来源：http://dali.tian-w.cn/Article/details/gtmjttypeb.html

Py:   if not s:
来源：http://dali.zhaomingkeji.xyz/Article/details/gtspzesovr.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.havefunace.top/Article/details/gtrhllbdtv.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.xziqi.cn/Article/details/gtgzocbvcy.html

TS:   if (s === "") {}
来源：http://dali.yj202588.top/Article/details/gtylagkqny.html

Java: if (s.isEmpty()) {}
来源：http://dali.iojbl.cn/Article/details/gtwjctkocf.html

Go:   if s == "" {}
来源：http://dali.cdnleiting.top/Article/details/gtgkvrgirn.html

Ruby: if s.empty?
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbatomwqx.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.cqqwz.cn/Article/details/gtzzjkimmk.html

[E21] 超长截断加省略号
来源：http://dali.yj202588.top/Article/details/gtsogmxycj.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.ppjwa.cn/Article/details/gtwixlttyj.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhixingplan.top/Article/details/gtjmalxwik.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cheryme.top/Article/details/gtwdtvbhbc.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sysykeji.top/Article/details/gtrbectqid.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.feifeiyinyue.top/Article/details/gthhpcmify.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.chenzaomai.com/Article/details/gtqfrvoray.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yueranfly.top/Article/details/gtmqexezru.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.guannengcc.top/Article/details/gtoftaqpoj.html

[E22] 字节长度与字符长度
来源：http://dali.snrcjt.cn/Article/details/gtmlhvkyah.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.dashuyun.cn/Article/details/gtkcblvztr.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.tian-w.cn/Article/details/gtlqzzfloz.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cdnleiting.top/Article/details/gtqbmylhhz.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yj20258888.top/Article/details/gtyznkancz.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.cucudq.cn/Article/details/gtjivivijf.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.chenjidiqi.icu/Article/details/gtqptvjuaz.html

Ruby: s.bytesize;  s.length
来源：http://dali.fengsongda.top/Article/details/gtxnoklviv.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.daxiang520.top/Article/details/gtdyomucam.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtawiykhav.html

F. 文件与目录
来源：http://dali.zycfv.cn/Article/details/gtbaxsjhvx.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtrtehlxry.html

[F01] 读取整个文件
来源：http://dali.shangyingyoupin.top/Article/details/gtndailgud.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yueranfly.top/Article/details/gtsrkleolu.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwipghqtp.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.pycfn.com/Article/details/gtdhtmlpwi.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.9152youxi.cn/Article/details/gtniluzpup.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.kuanghao11.cn/Article/details/gtsuuuqyzl.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.ppjwa.cn/Article/details/gtwdkaehlr.html

Ruby: File.read("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtrtqmjpwe.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jianghu66.top/Article/details/gtngmzhixi.html

[F02] 逐行读取文件
来源：http://dali.mhx1999.top/Article/details/gtibmmkldm.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hysaishi.cn/Article/details/gtdupzkhth.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.meibo888.top/Article/details/gtduyymwgq.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hfpthk.cn/Article/details/gtpialtgdu.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhoulong.xyz/Article/details/gtojaranio.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jqgfzy.top/Article/details/gtaepchrnn.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.xylfe.cn/Article/details/gtarevrsqe.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.cucudq.cn/Article/details/gtbqlezziq.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yj20258.top/Article/details/gtlmxadwtk.html

[F03] 写入文件（覆盖）
来源：http://dali.chenzaomai.com/Article/details/gtolpawvev.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhiwuduotai.top/Article/details/gttjhltuqi.html


<!-- 参考信息 -->