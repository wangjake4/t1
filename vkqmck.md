代发 wailian999

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.nwbrower.top/Article/details/gthjvusmgt.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.daxiang520.top/Article/details/gtyotgafln.html

Go:   // 手写 map[string][]T
来源：http://dali.yangfankeji.com/Article/details/gtftgyeygn.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jqgfzy.top/Article/details/gtkzqqdejx.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jlsjyb.cn/Article/details/gtnhclaufx.html

[D20] 统计每个元素出现次数
来源：http://dali.bjfxy.top/Article/details/gtkuooxnjh.html

Py:   Counter(arr)
来源：http://dali.fzhhl.top/Article/details/gtvuormhjo.html

PHP:  array_count_values($arr);
来源：http://dali.gotoacloud.top/Article/details/gtuwqpuyky.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbruoqpbq.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xuetiantiany.cn/Article/details/gtymnsiedx.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yj20258.top/Article/details/gtlfmwwfid.html

Go:   // 手写 map[T]int
来源：http://dali.jqgufenzy.top/Article/details/gtlyahyuke.html

Ruby: arr.tally
来源：http://dali.tanke756.top/Article/details/gtslkpalid.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yanxiufei.cn/Article/details/gtvdojlgld.html

[D21] 判断是否包含某元素
来源：http://dali.wangdashe.top/Article/details/gtkoxofmbi.html

Py:   x in arr
来源：http://dali.sxryk.cn/Article/details/gtysblwdpd.html

PHP:  in_array($x, $arr, true);
来源：http://dali.pengpengdd.cyou/Article/details/gtzebxjqdw.html

JS:   arr.includes(x)
来源：http://dali.yj20258.top/Article/details/gthclfbrhm.html

TS:   arr.includes(x)
来源：http://dali.tian-w.cn/Article/details/gtdamafkji.html

Java: list.contains(x)
来源：http://dali.0kj1m.cn/Article/details/gtxfiabdff.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhoulong.xyz/Article/details/gterzdtvkf.html

Ruby: arr.include?(x)
来源：http://dali.xinyue.icu/Article/details/gthdnynune.html

C#:   list.Contains(x)
来源：http://dali.daria6918.cn/Article/details/gtophopfwj.html

[D22] 复制数组（避免共享引用）
来源：http://dali.tianlin.xyz/Article/details/gtqjedtsst.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.tianlin.xyz/Article/details/gtzbiixqvl.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yueranfly.top/Article/details/gtdalfhswj.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yj20258888.top/Article/details/gtrkqkwzyh.html

TS:   [...arr];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjxyucgmj.html

Java: new ArrayList<>(list);
来源：http://dali.sufxvd.cn/Article/details/gtpsjsetei.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.birdmap.top/Article/details/gtppsnnwbd.html

Ruby: arr.dup;  arr.clone
来源：http://dali.havefunace.top/Article/details/gtwvnvyvna.html

C#:   new List<int>(list);
来源：http://dali.guannengcc.top/Article/details/gtervsffbh.html

[D23] reduce 累积计算
来源：http://dali.bjfxy.top/Article/details/gtgfrjsxbm.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.0kj1m.cn/Article/details/gtverhvdbz.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.cashguo.top/Article/details/gtikchfrjl.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhongyouzk.top/Article/details/gtgsracshw.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jiagoushi.top/Article/details/gtdcobugcx.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zycfv.cn/Article/details/gtqrmndepq.html

Go:   // 手写循环
来源：http://dali.andypj.xyz/Article/details/gtgjispcwh.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jinghuilouyu.cn/Article/details/gtsufemnov.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfkqggxez.html

[D24] 字典 / Map 基本操作
来源：http://dali.jiagoushi.top/Article/details/gtcowcceeu.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhixingplan.top/Article/details/gttxkbkseo.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jianghu66.top/Article/details/gtxuzeuypl.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.gogol.net.cn/Article/details/gtnclosref.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.ehwqpu.com/Article/details/gtethfefed.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuxvjrykq.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.xinyue.icu/Article/details/gtckpobild.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.ivvv.top/Article/details/gtizppocop.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.xinyue.icu/Article/details/gtmuocjzfl.html

[D25] Set 集合去重与交并差
来源：http://dali.quarkkingdee.top/Article/details/gtmyyzgiyz.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhixingplan.top/Article/details/gtbxalwiik.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.andypj.xyz/Article/details/gtcnncslfg.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtndcujhum.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.cdnleiting.top/Article/details/gtebvbnzlj.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yanxiufei.cn/Article/details/gttkiwqbri.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.wangdashe.top/Article/details/gtbipxgeiy.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.sufxvd.cn/Article/details/gtcscjhvnc.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.tianlin.xyz/Article/details/gtkbbierff.html

[D26] 数组转字符串
来源：http://dali.yangfankeji.com/Article/details/gttatcuppv.html

Py:   ", ".join(map(str, arr))
来源：http://dali.iojbl.cn/Article/details/gtdpyilfkm.html

PHP:  implode(", ", $arr);
来源：http://dali.mhx1999.top/Article/details/gtddxufmzr.html

JS:   arr.join(", ")
来源：http://dali.havefunace.top/Article/details/gtupjexwhv.html

TS:   arr.join(", ")
来源：http://dali.pengpengdd.cyou/Article/details/gtvdumgruf.html

Java: String.join(", ", list)
来源：http://dali.nanxinkj.top/Article/details/gtpfrzuprz.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jiagoushi.top/Article/details/gtdrurhwan.html

Ruby: arr.join(", ")
来源：http://dali.yvedp.cn/Article/details/gtptkfxrwl.html

C#:   string.Join(", ", list)
来源：http://dali.meibo888.top/Article/details/gtbjmvxyqq.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtwvubcdgr.html

E. 字符串处理
来源：http://dali.ydzc1.top/Article/details/gtcmhegxmg.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtzcwotdpi.html

[E01] 拼接字符串
来源：http://dali.aibaodan.cn/Article/details/gtwrrmddxt.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.feifeiyinyue.top/Article/details/gtqwmxxfzg.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jinqigufen.top/Article/details/gtvcpttstq.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ybcxt.top/Article/details/gtmncdxyvq.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.redwolf501.top/Article/details/gtlvhcqnab.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.pycfn.com/Article/details/gtaonkmmhf.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhoulong.xyz/Article/details/gtxodrqsip.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zdqjudy.top/Article/details/gtvcllrgiu.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.fzhhl.top/Article/details/gtzdnodfva.html

[E02] 重复字符串
来源：http://dali.316326.xyz/Article/details/gtqvhkpqvy.html

Py:   "ab" * 3
来源：http://dali.yonumen.top/Article/details/gtsziddvir.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hywenlv.cn/Article/details/gteezrygwd.html

JS:   "ab".repeat(3)
来源：http://dali.iojbl.cn/Article/details/gtrauhhvop.html

TS:   "ab".repeat(3)
来源：http://dali.sufxvd.cn/Article/details/gtiuqlnyai.html

Java: "ab".repeat(3)
来源：http://dali.zhixingplan.top/Article/details/gtptviwzlm.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.ehwqpu.com/Article/details/gtcugnutxm.html

Ruby: "ab" * 3
来源：http://dali.ppjwa.cn/Article/details/gtfmolkuqp.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yanxiufei.cn/Article/details/gtgfbxkpok.html

[E03] 截取子串
来源：http://dali.gogol.net.cn/Article/details/gtwtznvifd.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yangfankeji.com/Article/details/gtuevezbmy.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.hysaishi.cn/Article/details/gtiizxbnzj.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jianghu66.top/Article/details/gtqgawqbga.html

TS:   s.slice(1, 4)
来源：http://dali.xinyue.icu/Article/details/gttoyugoml.html

Java: s.substring(1, 4)
来源：http://dali.fengsongda.top/Article/details/gtcsfnrymh.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.tian-w.cn/Article/details/gtwpijgbri.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.tanke756.top/Article/details/gtsuwrbecg.html

C#:   s.Substring(1, 3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrwjdrstf.html

[E04] 查找子串位置
来源：http://dali.cashguo.top/Article/details/gtnstxpvkg.html

Py:   s.find("x");  s.index("x")
来源：http://dali.ivvv.top/Article/details/gtyihlbepr.html

PHP:  strpos($s, "x");
来源：http://dali.sweek.top/Article/details/gtmkreaaqu.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gtjgemkrjl.html

TS:   s.indexOf("x")
来源：http://dali.hammf.cn/Article/details/gtqgulgkfg.html

Java: s.indexOf("x")
来源：http://dali.tianlin.xyz/Article/details/gtzbsiaskh.html

Go:   strings.Index(s, "x")
来源：http://dali.yuxming.cn/Article/details/gtzfhnyoch.html

Ruby: s.index("x")
来源：http://dali.quarkkingdee.top/Article/details/gtyutwywhx.html

C#:   s.IndexOf("x")
来源：http://dali.shangyingyoupin.top/Article/details/gtyddxfkje.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthhnoojoi.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yvedp.cn/Article/details/gtrcfdbzsw.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yj20258.top/Article/details/gtsvihxocy.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yuxming.cn/Article/details/gtopscbfis.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.kuanghao11.cn/Article/details/gtdyihqall.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ivvv.top/Article/details/gtyyrxbedb.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.chenlongwang.top/Article/details/gtvnvxpddy.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.tanke756.top/Article/details/gtdtejrdfs.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yj202588.top/Article/details/gtwjbavvjt.html

[E06] 替换子串
来源：http://dali.jinyuanbaomall.cn/Article/details/gterzpgcsl.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.guowangkeji.top/Article/details/gtxxiogejx.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.316326.xyz/Article/details/gtsnnddmbl.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yvedp.cn/Article/details/gtwvnszmhx.html

TS:   s.replaceAll("a", "b")
来源：http://dali.ivvv.top/Article/details/gtgstxrulh.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xinyue.icu/Article/details/gtfmvaqtxf.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yj202588.top/Article/details/gtfofsnfpm.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.feifeiyinyue.top/Article/details/gtpzgacaeq.html

C#:   s.Replace("a", "b")
来源：http://dali.jqgfzy.top/Article/details/gtzumxfukz.html

[E07] 按分隔符拆分
来源：http://dali.feifeiyinyue.top/Article/details/gtqwtcyejp.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.fengsongda.top/Article/details/gtpekfgztk.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jqgfzy.top/Article/details/gtneirxksx.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.chenzaomai.com/Article/details/gtcnssyxqe.html

TS:   s.split(",")
来源：http://dali.bjfxy.top/Article/details/gtwkvxajss.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.wangdashe.top/Article/details/gtkclwcevu.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtlbsnmfni.html

Ruby: s.split(",");  s.split
来源：http://dali.9152youxi.cn/Article/details/gtxbgqnppc.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhongyouzk.top/Article/details/gtytjikjyn.html

[E08] 数组按分隔符合并
来源：http://dali.bjfxy.top/Article/details/gtuhicbcsh.html

Py:   ",".join(items)
来源：http://dali.shzxlz.cn/Article/details/gtumabszze.html

PHP:  implode(",", $items);
来源：http://dali.fengsongda.top/Article/details/gtlybugpck.html

JS:   items.join(",")
来源：http://dali.zdqjudy.top/Article/details/gtpcchkghn.html

TS:   items.join(",")
来源：http://dali.ybcxt.top/Article/details/gtznsqkozf.html

Java: String.join(",", items)
来源：http://dali.cdnleiting.top/Article/details/gtgkoxvkmf.html

Go:   strings.Join(items, ",")
来源：http://dali.0kj1m.cn/Article/details/gtjhsmmtil.html

Ruby: items.join(",")
来源：http://dali.zhongyouzk.top/Article/details/gtvuoqtocq.html

C#:   string.Join(",", items)
来源：http://dali.zhoulong.xyz/Article/details/gtpjixqcsl.html

[E09] 去除所有空白字符
来源：http://dali.0kj1m.cn/Article/details/gtquprmgly.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.bjfxy.top/Article/details/gtpchgpxic.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hnqzz.top/Article/details/gtedkncpwf.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.haohaochexian.top/Article/details/gtkugmywfl.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yj20258888.top/Article/details/gtemyorjsp.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.chenjidiqi.icu/Article/details/gtciinlfqy.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.shanyushiyangtech.top/Article/details/gthoxbgrzx.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.cheryme.top/Article/details/gtlyrwljug.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.c1oappe.top/Article/details/gtbdcugrnh.html

[E10] 左侧补零 / 定长填充
来源：http://dali.haohaochexian.top/Article/details/gtqbktmbtm.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.meibo888.top/Article/details/gtskabznel.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.ydzc1.top/Article/details/gtudgjtrmy.html

JS:   "7".padStart(3, "0")
来源：http://dali.yonumen.top/Article/details/gtwdqizevl.html

TS:   "7".padStart(3, "0")
来源：http://dali.pycfn.com/Article/details/gtdrxqrxex.html

Java: String.format("%03d", 7)
来源：http://dali.xinyue.icu/Article/details/gtefjigaup.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yj20258888.top/Article/details/gttsjnitev.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.cucudq.cn/Article/details/gtaualjthp.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yueranfly.top/Article/details/gthcozwfjy.html

[E11] 反转字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaxgcdrzx.html

Py:   s[::-1]
来源：http://dali.cucudq.cn/Article/details/gtepzcjyme.html

PHP:  strrev($s);
来源：http://dali.aizwys.cn/Article/details/gtlhmmcqxf.html

JS:   [...s].reverse().join("")
来源：http://dali.feifeiyinyue.top/Article/details/gthekbkhpc.html

TS:   [...s].reverse().join("")
来源：http://dali.xziqi.cn/Article/details/gtkznaigjr.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yangfankeji.com/Article/details/gtxofjxxwx.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.svipenyu.cn/Article/details/gtuxgmyoov.html

Ruby: s.reverse
来源：http://dali.hysaishi.cn/Article/details/gtfdymiwxr.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yj202588.top/Article/details/gtnykqdncj.html

[E12] 统计某字符出现次数
来源：http://dali.redwolf501.top/Article/details/gtddffrnah.html

Py:   s.count("a")
来源：http://dali.jqgufenzy.top/Article/details/gtarjofpqz.html

PHP:  substr_count($s, "a");
来源：http://dali.xuetiantiany.cn/Article/details/gtsoyiwhbs.html

JS:   s.split("a").length - 1
来源：http://dali.shuidangran.top/Article/details/gteryyxuco.html

TS:   s.split("a").length - 1
来源：http://dali.feifeiyinyue.top/Article/details/gtjsbarrun.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.smart0.xyz/Article/details/gtiduslrtt.html

Go:   strings.Count(s, "a")
来源：http://dali.daria6918.cn/Article/details/gtowigcqqp.html

Ruby: s.count("a")
来源：http://dali.pengpengdd.cyou/Article/details/gtftwcoilr.html

C#:   s.Count(c => c == 'a')
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnmaesgko.html

[E13] 逐字符遍历
来源：http://dali.cdnleiting.top/Article/details/gtoowteyub.html

Py:   for ch in s: print(ch)
来源：http://dali.shuidangran.top/Article/details/gtmmsceldx.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhengqikj.top/Article/details/gtjulyxjfr.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jiagoushi.top/Article/details/gtfjmdxgzb.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.meibo888.top/Article/details/gtpyslajtn.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.0kj1m.cn/Article/details/gtpetxqndz.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yanxiufei.cn/Article/details/gtuafcgbab.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.chenzaomai.com/Article/details/gtgncvkkod.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.iojbl.cn/Article/details/gthqxhpkmx.html

[E14] URL 编码与 Base64
来源：http://dali.wangdashe.top/Article/details/gtcsxjgymg.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.xziqi.cn/Article/details/gtlnhtroko.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yonumen.top/Article/details/gtaikhuizk.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhijiandao.cn/Article/details/gtwitchrpc.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.cqqwz.cn/Article/details/gtrwewhegu.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.chenjidiqi.icu/Article/details/gtmiskthyy.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.sufxvd.cn/Article/details/gtodwalmln.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.c1oappe.top/Article/details/gtnvfatrfv.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.shangyingyoupin.top/Article/details/gtvbsfawpq.html

[E15] HTML 转义 / 反转义
来源：http://dali.chenlongwang.top/Article/details/gtutsxlgyt.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.sweek.top/Article/details/gteabkgmwd.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yangfankeji.com/Article/details/gtrrrorjms.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yj20258888.top/Article/details/gtyvvzizqf.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.guowangkeji.top/Article/details/gtbcvohfyy.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yanxiufei.cn/Article/details/gtyrbeyrtd.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xuanzx.com/Article/details/gtvzefindh.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.mhx1999.top/Article/details/gtolxylwwk.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.kuanghao11.cn/Article/details/gtuqgbzmeg.html

[E16] 数字千分位
来源：http://dali.jinqigfzy.top/Article/details/gtxnhvzzjm.html

Py:   f"{1234567:,}"
来源：http://dali.havefunace.top/Article/details/gtfbgynvli.html

PHP:  number_format(1234567);
来源：http://dali.hongshengwenyu.top/Article/details/gtfgpvpbuv.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yuanzhike.top/Article/details/gtmukgtcps.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jyoumei.cn/Article/details/gtkgeyfkxu.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.meibo888.top/Article/details/gtfldmkzdi.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yonumen.top/Article/details/gtttdrdcjx.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.quarkkingdee.top/Article/details/gtrvqbxtar.html

C#:   1234567.ToString("N0")
来源：http://dali.ppjwa.cn/Article/details/gtdczfansz.html

[E17] 首字母大写
来源：http://dali.bjfxy.top/Article/details/gtagfntqci.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ydzc1.top/Article/details/gtixtuptrx.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.meibo888.top/Article/details/gtqlrwholn.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj20258.top/Article/details/gtikujfjwc.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.daria6918.cn/Article/details/gtgsqmucql.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtmbqgdnfk.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.chenlongwang.top/Article/details/gtfsriqhpx.html

Ruby: s.capitalize
来源：http://dali.yj202588.top/Article/details/gtyttbxgmj.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jlsjyb.cn/Article/details/gtxlttzjfl.html

[E18] 模板占位符替换
来源：http://dali.daxiang520.top/Article/details/gtsbcjubje.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.meibo888.top/Article/details/gtlukvrsbk.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yj20258888.top/Article/details/gtzgzmeeuu.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.pengpengdd.cyou/Article/details/gtmdfqyndk.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yj20258888.top/Article/details/gtogljxjlr.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.0kj1m.cn/Article/details/gtqzpbmoqn.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.hysaishi.cn/Article/details/gtwoiskzwg.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yangfankeji.com/Article/details/gtxgtznckb.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.dashuyun.cn/Article/details/gtiitabodw.html

[E19] 多行文本按行拆分
来源：http://dali.chenjidiqi.icu/Article/details/gtqreghpie.html

Py:   s.splitlines()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlytmivlt.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.daria6918.cn/Article/details/gtgqutlpww.html

JS:   s.split(/\r?\n/)
来源：http://dali.kuanghao11.cn/Article/details/gtpipqjyrl.html

TS:   s.split(/\r?\n/)
来源：http://dali.zycfv.cn/Article/details/gtimrfwjgx.html

Java: s.lines().toList()
来源：http://dali.cucudq.cn/Article/details/gtpbtxnwgd.html

Go:   strings.Split(s, "\n")
来源：http://dali.jinqigfzy.top/Article/details/gtbzleemvx.html

Ruby: s.lines
来源：http://dali.yuxming.cn/Article/details/gtxnzwhjwq.html

C#:   s.Split('\n')
来源：http://dali.0kj1m.cn/Article/details/gtgvzgjcso.html

[E20] 判断字符串是否为空
来源：http://dali.xylfe.cn/Article/details/gthfmmnhho.html

Py:   if not s:
来源：http://dali.gogol.net.cn/Article/details/gtaruzculf.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yangfankeji.com/Article/details/gtzfzilgrg.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.xuanzx.com/Article/details/gtyrcwllus.html

TS:   if (s === "") {}
来源：http://dali.shzxlz.cn/Article/details/gtzkhdyiyo.html

Java: if (s.isEmpty()) {}
来源：http://dali.cheryme.top/Article/details/gtvqsqzbgd.html

Go:   if s == "" {}
来源：http://dali.sweek.top/Article/details/gtaxixvvbs.html

Ruby: if s.empty?
来源：http://dali.yanxiufei.cn/Article/details/gtxdzukexe.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.xylfe.cn/Article/details/gtqgwtxklx.html

[E21] 超长截断加省略号
来源：http://dali.zycfv.cn/Article/details/gtcfaxhaxw.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yangfankeji.com/Article/details/gtprlbdlat.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.gaohongyu789.top/Article/details/gtgikwsydc.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ppjwa.cn/Article/details/gtetyuafak.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqpueqzrz.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yj20258.top/Article/details/gtofhcrrgi.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhengqikj.top/Article/details/gtlksebqew.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jyoumei.cn/Article/details/gtpmdxqhff.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsnfshhkh.html

[E22] 字节长度与字符长度
来源：http://dali.xuetiantiany.cn/Article/details/gtqzbwvnvq.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.hnxiangtu.top/Article/details/gtzecwjbfd.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sufxvd.cn/Article/details/gtebgsflgf.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhoulong.xyz/Article/details/gtzgaxelie.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sxryk.cn/Article/details/gtvkgpewfr.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.vqdsnc.cn/Article/details/gtjeghqfsm.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.cdnleiting.top/Article/details/gtcvlpdydc.html

Ruby: s.bytesize;  s.length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvlxqpcwy.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zycfv.cn/Article/details/gtvrpnhfnn.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtdvamhclo.html

F. 文件与目录
来源：http://dali.guannengcc.top/Article/details/gtqzuvscrz.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtaqyeydiy.html

[F01] 读取整个文件
来源：http://dali.hnxiangtu.top/Article/details/gtprdmkmus.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.fengsongda.top/Article/details/gtewggtvmd.html

PHP:  file_get_contents("a.txt");
来源：http://dali.havefunace.top/Article/details/gtzpkddeht.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.cashguo.top/Article/details/gthcpbpiuq.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtphthrpqf.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cdnleiting.top/Article/details/gtpornthjn.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jinghuilouyu.cn/Article/details/gtpismxrmc.html

Ruby: File.read("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtaenwylgi.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.cucudq.cn/Article/details/gtccilryss.html

[F02] 逐行读取文件
来源：http://dali.yongpay.top/Article/details/gtgmhcyryi.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.cheryme.top/Article/details/gtncepffub.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.cqqwz.cn/Article/details/gtsbqrklsf.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.havefunace.top/Article/details/gtkfoiytjk.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtcwrsydfy.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jinqigufen.top/Article/details/gtyiicfsvd.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhiwuduotai.top/Article/details/gtogmtytil.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.gaohongyu789.top/Article/details/gtgoyktlmp.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yvedp.cn/Article/details/gtlngkppkn.html

[F03] 写入文件（覆盖）
来源：http://dali.hongshengwenyu.top/Article/details/gtjfkdijqs.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.svipenyu.cn/Article/details/gttukjdrfs.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.tianlin.xyz/Article/details/gtwlaqmnck.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cheryme.top/Article/details/gtmvkmlbdc.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdylrdorx.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxxyqwjoh.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.chenlongwang.top/Article/details/gtftictqzx.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.fzhhl.top/Article/details/gtjlszflpi.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.quarkkingdee.top/Article/details/gtqpyrgcxo.html

[F04] 追加写入文件
来源：http://dali.gotoacloud.top/Article/details/gtjdphrqds.html


<!-- 参考信息 -->