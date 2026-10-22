代发 wailian999

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hfpthk.cn/Article/details/gt2gymxpkpa.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sysykeji.top/Article/details/gt2lniegzbt.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.daxiang520.top/Article/details/gt2lpwtnxjv.html

Go:   // 手写 map[T]int
来源：http://dali.zhoulong.xyz/Article/details/gt2eumsejsg.html

Ruby: arr.tally
来源：http://dali.316326.xyz/Article/details/gt2wuzvfnzg.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jianghu66.top/Article/details/gt2oyfoozyb.html

[D21] 判断是否包含某元素
来源：http://dali.snrcjt.cn/Article/details/gt2hwxzqqht.html

Py:   x in arr
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dgmrhjwr.html

PHP:  in_array($x, $arr, true);
来源：http://dali.fengsongda.top/Article/details/gt2viacbcxl.html

JS:   arr.includes(x)
来源：http://dali.yanxiufei.cn/Article/details/gt2etjvvlfk.html

TS:   arr.includes(x)
来源：http://dali.bjfxy.top/Article/details/gt2kxaowwrf.html

Java: list.contains(x)
来源：http://dali.cashguo.top/Article/details/gt2vygdayjv.html

Go:   slices.Contains(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gt2dfmixrlv.html

Ruby: arr.include?(x)
来源：http://dali.birdmap.top/Article/details/gt2ztjzlsnd.html

C#:   list.Contains(x)
来源：http://dali.yongpay.top/Article/details/gt2wsknhrfn.html

[D22] 复制数组（避免共享引用）
来源：http://dali.haohaochexian.top/Article/details/gt2fnjgdzth.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.cashguo.top/Article/details/gt2fspsibjg.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.gogol.net.cn/Article/details/gt2zmtnyviz.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ttqrbycz.html

TS:   [...arr];
来源：http://dali.zhongyouzk.top/Article/details/gt2ykyzksuo.html

Java: new ArrayList<>(list);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mnombdmo.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjvhxtni.html

Ruby: arr.dup;  arr.clone
来源：http://dali.aibaodan.cn/Article/details/gt2gdfxdibj.html

C#:   new List<int>(list);
来源：http://dali.yuxming.cn/Article/details/gt2plyfeipz.html

[D23] reduce 累积计算
来源：http://dali.nwbrower.top/Article/details/gt2lwwaldpa.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jqgufenzy.top/Article/details/gt2ybgmydsk.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.ybcxt.top/Article/details/gt2xmmbqxlf.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cucudq.cn/Article/details/gt2klkvvfkz.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yuanzhike.top/Article/details/gt2gxwfmydt.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yuxming.cn/Article/details/gt2nceocacc.html

Go:   // 手写循环
来源：http://dali.yangfankeji.com/Article/details/gt2dsiserbp.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yongpay.top/Article/details/gt2taneqewl.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2amduczwu.html

[D24] 字典 / Map 基本操作
来源：http://dali.yanxiufei.cn/Article/details/gt2sbffzkhr.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.havefunace.top/Article/details/gt2sifovpug.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yanxiufei.cn/Article/details/gt2ppwxeiqo.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jqgufenzy.top/Article/details/gt2pztcgywy.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhengqikj.top/Article/details/gt2bnalwmdk.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.birdmap.top/Article/details/gt2asahqhla.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhongyouzk.top/Article/details/gt2ouvvgviw.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.tianlin.xyz/Article/details/gt2mgyonxob.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.birdmap.top/Article/details/gt2wuftmzto.html

[D25] Set 集合去重与交并差
来源：http://dali.fzhhl.top/Article/details/gt2bygwvojc.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.cucudq.cn/Article/details/gt2coadqlzf.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.0kj1m.cn/Article/details/gt2hrxvrpiz.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.vqdsnc.cn/Article/details/gt2teuitqri.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yanxiufei.cn/Article/details/gt2buefiidh.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gvykbynt.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sqxoztkc.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jinqigufen.top/Article/details/gt2slgwhude.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.havefunace.top/Article/details/gt2bqkzqzca.html

[D26] 数组转字符串
来源：http://dali.jqgfzy.top/Article/details/gt2tusdlnkz.html

Py:   ", ".join(map(str, arr))
来源：http://dali.0kj1m.cn/Article/details/gt2yeemzgdu.html

PHP:  implode(", ", $arr);
来源：http://dali.mhx1999.top/Article/details/gt2ujjcbtyb.html

JS:   arr.join(", ")
来源：http://dali.cqqwz.cn/Article/details/gt2yfbwphme.html

TS:   arr.join(", ")
来源：http://dali.hfpthk.cn/Article/details/gt2qthvqrjv.html

Java: String.join(", ", list)
来源：http://dali.gaohongyu789.top/Article/details/gt2ufbqagof.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jinqigfzy.top/Article/details/gt2yvejtzfz.html

Ruby: arr.join(", ")
来源：http://dali.gaohongyu789.top/Article/details/gt2uuqylbse.html

C#:   string.Join(", ", list)
来源：http://dali.yj202588.top/Article/details/gt2aqqvonjw.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2tuftavpz.html

E. 字符串处理
来源：http://dali.vqdsnc.cn/Article/details/gt2lxgvelss.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2wbpwwkdg.html

[E01] 拼接字符串
来源：http://dali.xylfe.cn/Article/details/gt2sugocity.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhiwuduotai.top/Article/details/gt2uazouukv.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.tianlin.xyz/Article/details/gt2gcwfmygl.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhengqikj.top/Article/details/gt2vyohuewp.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.redwolf501.top/Article/details/gt2gxntkcrj.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.xinyue.icu/Article/details/gt2uqmizbew.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.cashguo.top/Article/details/gt2jnfbymdq.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.xuanzx.com/Article/details/gt2ysyeqvpi.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.shuidangran.top/Article/details/gt2xmeairmt.html

[E02] 重复字符串
来源：http://dali.zhoulong.xyz/Article/details/gt2fcddaxum.html

Py:   "ab" * 3
来源：http://dali.fzhhl.top/Article/details/gt2tltvkvkl.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hammf.cn/Article/details/gt2dapggreh.html

JS:   "ab".repeat(3)
来源：http://dali.tianlin.xyz/Article/details/gt2dlfeffgu.html

TS:   "ab".repeat(3)
来源：http://dali.yj20258888.top/Article/details/gt2nfeijbod.html

Java: "ab".repeat(3)
来源：http://dali.jlsjyb.cn/Article/details/gt2fwbjgctd.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yongpay.top/Article/details/gt2dymtehqq.html

Ruby: "ab" * 3
来源：http://dali.shuidangran.top/Article/details/gt2aqsrjltp.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhoulong.xyz/Article/details/gt2vrwgwdcp.html

[E03] 截取子串
来源：http://dali.hywenlv.cn/Article/details/gt2gmjtfdxs.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.tanke756.top/Article/details/gt2rddsaial.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.nanxuanxn.top/Article/details/gt2tyurbzhn.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.guowangkeji.top/Article/details/gt2jyyopvou.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2auzxzlno.html

Java: s.substring(1, 4)
来源：http://dali.tanke756.top/Article/details/gt2gnfmpcgi.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ukigielx.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.chenzaomai.com/Article/details/gt2ianxxhpc.html

C#:   s.Substring(1, 3)
来源：http://dali.smart0.xyz/Article/details/gt2pavvytls.html

[E04] 查找子串位置
来源：http://dali.xinyue.icu/Article/details/gt2xgofdsal.html

Py:   s.find("x");  s.index("x")
来源：http://dali.quarkkingdee.top/Article/details/gt2vacbbple.html

PHP:  strpos($s, "x");
来源：http://dali.snrcjt.cn/Article/details/gt2jiikipbl.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yj20258888.top/Article/details/gt2teovyubl.html

TS:   s.indexOf("x")
来源：http://dali.jqgufenzy.top/Article/details/gt2kphcptys.html

Java: s.indexOf("x")
来源：http://dali.havefunace.top/Article/details/gt2purjixde.html

Go:   strings.Index(s, "x")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ribybznz.html

Ruby: s.index("x")
来源：http://dali.smart0.xyz/Article/details/gt2tbougrmy.html

C#:   s.IndexOf("x")
来源：http://dali.yuxming.cn/Article/details/gt2jjyqlyye.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.ivvv.top/Article/details/gt2ypinizgf.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.guannengcc.top/Article/details/gt2skwovjux.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.gogol.net.cn/Article/details/gt2kasjhmzs.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gogol.net.cn/Article/details/gt2kcirhcyl.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.ybcxt.top/Article/details/gt2klmtewde.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gzhubu.top/Article/details/gt2nqpbdwep.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2owtbxhle.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yonumen.top/Article/details/gt2equphtrh.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jyoumei.cn/Article/details/gt2ajkwcnnf.html

[E06] 替换子串
来源：http://dali.chenzaomai.com/Article/details/gt2pwcdmmrj.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.kuanghao11.cn/Article/details/gt2hbauqeha.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yangfankeji.com/Article/details/gt2ukoodoce.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cdnleiting.top/Article/details/gt2batszeih.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yongpay.top/Article/details/gt2guxvxjcu.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.redwolf501.top/Article/details/gt2cdrzqvms.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.fzhhl.top/Article/details/gt2ieqneouy.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jyoumei.cn/Article/details/gt2jjztcoqw.html

C#:   s.Replace("a", "b")
来源：http://dali.gzhubu.top/Article/details/gt2nhpracqy.html

[E07] 按分隔符拆分
来源：http://dali.xuanzx.com/Article/details/gt2tsukyvac.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.ydzc1.top/Article/details/gt2fnumecvw.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.hnxiangtu.top/Article/details/gt2qfmyqoqd.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.snrcjt.cn/Article/details/gt2hezayfuy.html

TS:   s.split(",")
来源：http://dali.cqqwz.cn/Article/details/gt2jixbwsnh.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhiwuduotai.top/Article/details/gt2vpanwxpn.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2abnpbece.html

Ruby: s.split(",");  s.split
来源：http://dali.hnqzz.top/Article/details/gt2yyzuivgj.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zycfv.cn/Article/details/gt2nfbugkqt.html

[E08] 数组按分隔符合并
来源：http://dali.jinqigfzy.top/Article/details/gt2oqeawzwt.html

Py:   ",".join(items)
来源：http://dali.yj20258888.top/Article/details/gt2krowvcoy.html

PHP:  implode(",", $items);
来源：http://dali.yanxiufei.cn/Article/details/gt2vgzwegoi.html

JS:   items.join(",")
来源：http://dali.yj20258.top/Article/details/gt2dzoytfnw.html

TS:   items.join(",")
来源：http://dali.sufxvd.cn/Article/details/gt2nblnqnhi.html

Java: String.join(",", items)
来源：http://dali.xuetiantiany.cn/Article/details/gt2saiussqe.html

Go:   strings.Join(items, ",")
来源：http://dali.snrcjt.cn/Article/details/gt2exftzdiu.html

Ruby: items.join(",")
来源：http://dali.jlsjyb.cn/Article/details/gt2usgmhifv.html

C#:   string.Join(",", items)
来源：http://dali.hongshengwenyu.top/Article/details/gt2qjnxodqh.html

[E09] 去除所有空白字符
来源：http://dali.pycfn.com/Article/details/gt2zqpizlbv.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.316326.xyz/Article/details/gt2wwkssdat.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zycfv.cn/Article/details/gt2gwyglzbd.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.tanke756.top/Article/details/gt2nbghagcs.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.pengpengdd.cyou/Article/details/gt2haxqjbtb.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.nanxinkj.top/Article/details/gt2hwuqrrxj.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yangfankeji.com/Article/details/gt2pgdysxer.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.sysykeji.top/Article/details/gt2nmmlxudx.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.sxryk.cn/Article/details/gt2zrqgmnky.html

[E10] 左侧补零 / 定长填充
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wfwwpfzy.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yangfankeji.com/Article/details/gt2wymlqnhf.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.cdnleiting.top/Article/details/gt2swnjeyic.html

JS:   "7".padStart(3, "0")
来源：http://dali.aizwys.cn/Article/details/gt2vkmngpkc.html

TS:   "7".padStart(3, "0")
来源：http://dali.wangdashe.top/Article/details/gt2umokxcru.html

Java: String.format("%03d", 7)
来源：http://dali.shzxlz.cn/Article/details/gt2ahvmmjkw.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.bjfxy.top/Article/details/gt2ddoclhxz.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhixingplan.top/Article/details/gt2lzzycpjn.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.birdmap.top/Article/details/gt2mgutfxqv.html

[E11] 反转字符串
来源：http://dali.zhongyouzk.top/Article/details/gt2rmubhrtk.html

Py:   s[::-1]
来源：http://dali.wangdashe.top/Article/details/gt2uuhljycj.html

PHP:  strrev($s);
来源：http://dali.hfpthk.cn/Article/details/gt2iaptthtn.html

JS:   [...s].reverse().join("")
来源：http://dali.xuanzx.com/Article/details/gt2xcaynoqn.html

TS:   [...s].reverse().join("")
来源：http://dali.hnxiangtu.top/Article/details/gt2kggxosir.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.vqdsnc.cn/Article/details/gt2bvxkegqc.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.cheryme.top/Article/details/gt2qjhaphmv.html

Ruby: s.reverse
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wjjttkvh.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kktmrehz.html

[E12] 统计某字符出现次数
来源：http://dali.cheryme.top/Article/details/gt2ocsprhxf.html

Py:   s.count("a")
来源：http://dali.bjfxy.top/Article/details/gt2lcjdjymg.html

PHP:  substr_count($s, "a");
来源：http://dali.yj20258888.top/Article/details/gt2vgelqiud.html

JS:   s.split("a").length - 1
来源：http://dali.xziqi.cn/Article/details/gt2sjhhbkbx.html

TS:   s.split("a").length - 1
来源：http://dali.cucudq.cn/Article/details/gt2cmvbyhqy.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xziqi.cn/Article/details/gt2sezrhqyx.html

Go:   strings.Count(s, "a")
来源：http://dali.yj20258888.top/Article/details/gt2lgkvvcvv.html

Ruby: s.count("a")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2elpdujuo.html

C#:   s.Count(c => c == 'a')
来源：http://dali.dashuyun.cn/Article/details/gt2xlvxsucc.html

[E13] 逐字符遍历
来源：http://dali.cucudq.cn/Article/details/gt2cnhnidfh.html

Py:   for ch in s: print(ch)
来源：http://dali.yj20258888.top/Article/details/gt2xvtuewbb.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.daria6918.cn/Article/details/gt2xeqmuoqm.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ybcxt.top/Article/details/gt2qysarmzq.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.pycfn.com/Article/details/gt2kwyiixoh.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.meibo888.top/Article/details/gt2budmouks.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.nanxinkj.top/Article/details/gt2mhhepykd.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.andypj.xyz/Article/details/gt2qipvtxxn.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.aibaodan.cn/Article/details/gt2xljaqhqk.html

[E14] URL 编码与 Base64
来源：http://dali.sufxvd.cn/Article/details/gt2ewzstffo.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yvedp.cn/Article/details/gt2nygcsnzw.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.pengpengdd.cyou/Article/details/gt2kantyqnt.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hammf.cn/Article/details/gt2yvqoicfo.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yuxming.cn/Article/details/gt2ypkkarqw.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.c1oappe.top/Article/details/gt2cqlcfmmt.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.birdmap.top/Article/details/gt2ttzqitgc.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.chenlongwang.top/Article/details/gt2unkpvjoc.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.nanxuanxn.top/Article/details/gt2wqjcpqph.html

[E15] HTML 转义 / 反转义
来源：http://dali.sufxvd.cn/Article/details/gt2jeqoaviv.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhixingplan.top/Article/details/gt2bfrlnzno.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jlsjyb.cn/Article/details/gt2kanjaeul.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.cheryme.top/Article/details/gt2tlhauyja.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.gotoacloud.top/Article/details/gt2szsnlgwb.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.birdmap.top/Article/details/gt2aoxcmhsp.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hammf.cn/Article/details/gt2qnxvjqww.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.9152youxi.cn/Article/details/gt2ygngtnee.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2tvdzpyip.html

[E16] 数字千分位
来源：http://dali.0kj1m.cn/Article/details/gt2dmkxlgnm.html

Py:   f"{1234567:,}"
来源：http://dali.yangfankeji.com/Article/details/gt2ujdutcqu.html

PHP:  number_format(1234567);
来源：http://dali.aibaodan.cn/Article/details/gt2qekfqbuh.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.nanxuanxn.top/Article/details/gt2firgtfcf.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.hfpthk.cn/Article/details/gt2krndqdbh.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhongyouzk.top/Article/details/gt2zodltnvj.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yj20258.top/Article/details/gt2nvrknlzl.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.gogol.net.cn/Article/details/gt2mvhwkhre.html

C#:   1234567.ToString("N0")
来源：http://dali.chenzaomai.com/Article/details/gt2zutubdcr.html

[E17] 首字母大写
来源：http://dali.xinyue.icu/Article/details/gt2cbmgzyxh.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.316326.xyz/Article/details/gt2gzbfwdfi.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.gogol.net.cn/Article/details/gt2wzpkximf.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mofaufod.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2acdidjkg.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yvedp.cn/Article/details/gt2lcubpgxp.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.nanxinkj.top/Article/details/gt2mijombcc.html

Ruby: s.capitalize
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iaiykayx.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.pengpengdd.cyou/Article/details/gt2luhscgqb.html

[E18] 模板占位符替换
来源：http://dali.quarkkingdee.top/Article/details/gt2mvgatole.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hysaishi.cn/Article/details/gt2bgzpflvg.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.aibaodan.cn/Article/details/gt2ipvtuacq.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yangfankeji.com/Article/details/gt2vvnkppmg.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.aizwys.cn/Article/details/gt2mbseubeu.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhiwuduotai.top/Article/details/gt2hxraynjj.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhoulong.xyz/Article/details/gt2cqrdvwwd.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yj20258.top/Article/details/gt2bcrzxhgp.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.xuanzx.com/Article/details/gt2cccvbxpc.html

[E19] 多行文本按行拆分
来源：http://dali.jlsjyb.cn/Article/details/gt2xqvzttdn.html

Py:   s.splitlines()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pzqnpyne.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.ehwqpu.com/Article/details/gt2ikpxgzcj.html

JS:   s.split(/\r?\n/)
来源：http://dali.hnxiangtu.top/Article/details/gt2kebzzzln.html

TS:   s.split(/\r?\n/)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lxxcycwq.html

Java: s.lines().toList()
来源：http://dali.hysaishi.cn/Article/details/gt2nlvjrbgp.html

Go:   strings.Split(s, "\n")
来源：http://dali.tian-w.cn/Article/details/gt2pulkipca.html

Ruby: s.lines
来源：http://dali.guannengcc.top/Article/details/gt2yujydkrq.html

C#:   s.Split('\n')
来源：http://dali.gaohongyu789.top/Article/details/gt2ldqbhkhy.html

[E20] 判断字符串是否为空
来源：http://dali.hywenlv.cn/Article/details/gt2forpedzz.html

Py:   if not s:
来源：http://dali.tanke756.top/Article/details/gt2voqvxibf.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.ydzc1.top/Article/details/gt2zlroylmx.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2wwxeugji.html

TS:   if (s === "") {}
来源：http://dali.gogol.net.cn/Article/details/gt2whnladkq.html

Java: if (s.isEmpty()) {}
来源：http://dali.hysaishi.cn/Article/details/gt2ibqptkaw.html

Go:   if s == "" {}
来源：http://dali.hnxiangtu.top/Article/details/gt2dpzifptl.html

Ruby: if s.empty?
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ovppaddu.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2tsskpatr.html

[E21] 超长截断加省略号
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dxcthfyn.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.chenlongwang.top/Article/details/gt2ruxzukln.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.tianlin.xyz/Article/details/gt2nhfchrnf.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yvedp.cn/Article/details/gt2pfkbfxty.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.feifeiyinyue.top/Article/details/gt2nxnoqvyy.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yj202588.top/Article/details/gt2piuadmcl.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.svipenyu.cn/Article/details/gt2kfnqfbmg.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jqgufenzy.top/Article/details/gt2tyvypyjt.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yj20258.top/Article/details/gt2ykdqxkte.html

[E22] 字节长度与字符长度
来源：http://dali.ydzc1.top/Article/details/gt2djtmblgj.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.aibaodan.cn/Article/details/gt2eerowgbv.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.kuanghao11.cn/Article/details/gt2iwgdnnrv.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ybcxt.top/Article/details/gt2kmxfxtos.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sufxvd.cn/Article/details/gt2ufbhhlct.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.daxiang520.top/Article/details/gt2uawiyeuk.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yuxming.cn/Article/details/gt2zzmgbght.html

Ruby: s.bytesize;  s.length
来源：http://dali.sufxvd.cn/Article/details/gt2kjhgihss.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.nanxinkj.top/Article/details/gt2wtlbrsmo.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2oidaklse.html

F. 文件与目录
来源：http://dali.smart0.xyz/Article/details/gt2cpdvwtbm.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2wvduugxc.html

[F01] 读取整个文件
来源：http://dali.gzhubu.top/Article/details/gt2laybkmjd.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.shuidangran.top/Article/details/gt2fcwercdp.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gt2fgxguvxy.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yuxming.cn/Article/details/gt2aupagzul.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.quarkkingdee.top/Article/details/gt2pfysapgy.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.bjfxy.top/Article/details/gt2zviihxgh.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zdqjudy.top/Article/details/gt2ppqpwdkf.html

Ruby: File.read("a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2mhynnpnd.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gt2izmqdygk.html

[F02] 逐行读取文件
来源：http://dali.yvedp.cn/Article/details/gt2zaqvwwno.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.andypj.xyz/Article/details/gt2syxhwdua.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.tian-w.cn/Article/details/gt2bgngovkt.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ydzc1.top/Article/details/gt2atfqumkh.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aeiferqp.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.snrcjt.cn/Article/details/gt2yxjbjkyv.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.feifeiyinyue.top/Article/details/gt2uihchwjd.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.pycfn.com/Article/details/gt2fumdoocz.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.havefunace.top/Article/details/gt2thovlxkc.html

[F03] 写入文件（覆盖）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xjtomoni.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.gogol.net.cn/Article/details/gt2gjdzinhs.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.gogol.net.cn/Article/details/gt2pqiyhjiv.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xylfe.cn/Article/details/gt2izupnpqs.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yuxming.cn/Article/details/gt2fjbbmbvn.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.guannengcc.top/Article/details/gt2ukkmraxx.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.fzhhl.top/Article/details/gt2rdvpacmu.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.c1oappe.top/Article/details/gt2aiwfnsmm.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhoulong.xyz/Article/details/gt2jsqtcdbd.html

[F04] 追加写入文件
来源：http://dali.jiagoushi.top/Article/details/gt2uqxouyox.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jlsjyb.cn/Article/details/gt2wdftxhzj.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.tianlin.xyz/Article/details/gt2tvvnzvkm.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yvedp.cn/Article/details/gt2zzhjlalx.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gzhubu.top/Article/details/gt2tbedmstz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jiagoushi.top/Article/details/gt2lyhdloeh.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yangfankeji.com/Article/details/gt2zdnnytwx.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vwplpmbb.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhongyouzk.top/Article/details/gt2dmgvkeey.html


<!-- 参考信息 -->