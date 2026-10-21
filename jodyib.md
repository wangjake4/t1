代发 wailian999

[D19] 按字段分组
来源：http://dali.yanxiufei.cn/Article/details/gtxgrtqdue.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbnffcimd.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yj202588.top/Article/details/gtgdknhcvs.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.cqqwz.cn/Article/details/gtnekaoeal.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.bjfxy.top/Article/details/gtzaekesiv.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.sweek.top/Article/details/gtehotmzjy.html

Go:   // 手写 map[string][]T
来源：http://dali.yj20258.top/Article/details/gtmwqbqbgs.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zycfv.cn/Article/details/gtktycpyxm.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yanxiufei.cn/Article/details/gtuftyofab.html

[D20] 统计每个元素出现次数
来源：http://dali.yangfankeji.com/Article/details/gtmjdnpjiy.html

Py:   Counter(arr)
来源：http://dali.yonumen.top/Article/details/gtgahztiyc.html

PHP:  array_count_values($arr);
来源：http://dali.xylfe.cn/Article/details/gtsewdbfzk.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj20258888.top/Article/details/gtvmecnpij.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhixingplan.top/Article/details/gtysuxltza.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hammf.cn/Article/details/gtghjvylqx.html

Go:   // 手写 map[T]int
来源：http://dali.wangdashe.top/Article/details/gtcbtmupbl.html

Ruby: arr.tally
来源：http://dali.zycfv.cn/Article/details/gtiailrsaq.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yueranfly.top/Article/details/gtblabjjiw.html

[D21] 判断是否包含某元素
来源：http://dali.xinyue.icu/Article/details/gtqiykxeeq.html

Py:   x in arr
来源：http://dali.shuidangran.top/Article/details/gtxoanpmgc.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhoulong.xyz/Article/details/gtbsqhzngg.html

JS:   arr.includes(x)
来源：http://dali.cashguo.top/Article/details/gteyirbbym.html

TS:   arr.includes(x)
来源：http://dali.pengpengdd.cyou/Article/details/gtcnjmbwzy.html

Java: list.contains(x)
来源：http://dali.kuanghao11.cn/Article/details/gtpykmwsxf.html

Go:   slices.Contains(arr, x)
来源：http://dali.chenzaomai.com/Article/details/gtovindsss.html

Ruby: arr.include?(x)
来源：http://dali.wangshuangyany.cn/Article/details/gtyoqmawaq.html

C#:   list.Contains(x)
来源：http://dali.yangfankeji.com/Article/details/gtaqlunskq.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yj20258888.top/Article/details/gtepaemfix.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtlpaeyggh.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.cqqwz.cn/Article/details/gthpkpnyqz.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jlsjyb.cn/Article/details/gtirgbmjgv.html

TS:   [...arr];
来源：http://dali.yuxming.cn/Article/details/gtyicyfcvp.html

Java: new ArrayList<>(list);
来源：http://dali.hfpthk.cn/Article/details/gthghjprrp.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.cucudq.cn/Article/details/gtpvucnstg.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhengqikj.top/Article/details/gthozgmjar.html

C#:   new List<int>(list);
来源：http://dali.chenjidiqi.icu/Article/details/gttvtzsipz.html

[D23] reduce 累积计算
来源：http://dali.yuanzhike.top/Article/details/gthiscytmw.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjihavlxx.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.cdnleiting.top/Article/details/gtocinzukb.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zycfv.cn/Article/details/gtpirpdcip.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sufxvd.cn/Article/details/gtjexicxxb.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.ppjwa.cn/Article/details/gtcekltbbe.html

Go:   // 手写循环
来源：http://dali.guannengcc.top/Article/details/gtyrtdtgbh.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.gaohongyu789.top/Article/details/gtexrhnfaw.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhongyouzk.top/Article/details/gtigpuokus.html

[D24] 字典 / Map 基本操作
来源：http://dali.ehwqpu.com/Article/details/gtsqluhpkk.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.cdnleiting.top/Article/details/gtfdqqnprl.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.wangdashe.top/Article/details/gtbyjazqql.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxpcchhur.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrcdnvtde.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.quarkkingdee.top/Article/details/gtmtwvoygq.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.gotoacloud.top/Article/details/gtzwsvbvgq.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.gotoacloud.top/Article/details/gtsuhotdlv.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yanxiufei.cn/Article/details/gtpvrhojkr.html

[D25] Set 集合去重与交并差
来源：http://dali.jyoumei.cn/Article/details/gtdbtmmihh.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.shzxlz.cn/Article/details/gtjdlzhbvh.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.gotoacloud.top/Article/details/gtkttyxlqz.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.andypj.xyz/Article/details/gtkvfkejco.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jqgufenzy.top/Article/details/gtixnucdjt.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfwggfppu.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.sweek.top/Article/details/gtpskqfepa.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.mhx1999.top/Article/details/gtfsvhbela.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yonumen.top/Article/details/gtifsuufoi.html

[D26] 数组转字符串
来源：http://dali.haohaochexian.top/Article/details/gtdmjgtckq.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yueranfly.top/Article/details/gtcyvotpgq.html

PHP:  implode(", ", $arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtryfbxful.html

JS:   arr.join(", ")
来源：http://dali.yanxiufei.cn/Article/details/gtvupqwsdj.html

TS:   arr.join(", ")
来源：http://dali.daria6918.cn/Article/details/gtewpddhzx.html

Java: String.join(", ", list)
来源：http://dali.redwolf501.top/Article/details/gttalqjuxg.html

Go:   strings.Join(strs, ", ")
来源：http://dali.meibo888.top/Article/details/gtgsfbqttm.html

Ruby: arr.join(", ")
来源：http://dali.gotoacloud.top/Article/details/gtyaoujyzq.html

C#:   string.Join(", ", list)
来源：http://dali.yongpay.top/Article/details/gtmhpefoiq.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtsnumzwza.html

E. 字符串处理
来源：http://dali.cqqwz.cn/Article/details/gtxuiypejl.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtwirjrsnm.html

[E01] 拼接字符串
来源：http://dali.hywenlv.cn/Article/details/gtckknnvuw.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.fengsongda.top/Article/details/gtxxflyyzb.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jinqigfzy.top/Article/details/gtywclmoog.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.nanxuanxn.top/Article/details/gtdxuovbpv.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.sysykeji.top/Article/details/gtzirrrymx.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.sufxvd.cn/Article/details/gtrearhmgp.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.xuetiantiany.cn/Article/details/gtqdasrjvx.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.aibaodan.cn/Article/details/gtqartgkqu.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.bjfxy.top/Article/details/gtmoutjour.html

[E02] 重复字符串
来源：http://dali.wangdashe.top/Article/details/gtevjdfrwl.html

Py:   "ab" * 3
来源：http://dali.jyoumei.cn/Article/details/gtzjfzvkwb.html

PHP:  str_repeat("ab", 3);
来源：http://dali.iojbl.cn/Article/details/gtracvcdos.html

JS:   "ab".repeat(3)
来源：http://dali.aizwys.cn/Article/details/gtvavagenc.html

TS:   "ab".repeat(3)
来源：http://dali.cucudq.cn/Article/details/gtczorzijo.html

Java: "ab".repeat(3)
来源：http://dali.gogol.net.cn/Article/details/gttwbtoisp.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.tian-w.cn/Article/details/gtotfkkvbg.html

Ruby: "ab" * 3
来源：http://dali.daxiang520.top/Article/details/gtqgxjrxlq.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.gotoacloud.top/Article/details/gtjbtriflp.html

[E03] 截取子串
来源：http://dali.pengpengdd.cyou/Article/details/gtxykfcend.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.316326.xyz/Article/details/gtagvoxoib.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.wangshuangyany.cn/Article/details/gtrddbvsvl.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.cdnleiting.top/Article/details/gtfanfyycb.html

TS:   s.slice(1, 4)
来源：http://dali.nanxuanxn.top/Article/details/gtwmxlkkoc.html

Java: s.substring(1, 4)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzwnujaem.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.aibaodan.cn/Article/details/gtdqqztewx.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.wangshuangyany.cn/Article/details/gtochgkikl.html

C#:   s.Substring(1, 3)
来源：http://dali.ppjwa.cn/Article/details/gthmlsgrdu.html

[E04] 查找子串位置
来源：http://dali.smart0.xyz/Article/details/gtcxtwheiu.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yangfankeji.com/Article/details/gtubddtnib.html

PHP:  strpos($s, "x");
来源：http://dali.hongshengwenyu.top/Article/details/gttzqescmy.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.dianchejie.cn/Article/details/gtfoscspcj.html

TS:   s.indexOf("x")
来源：http://dali.wangdashe.top/Article/details/gtvgcjuswn.html

Java: s.indexOf("x")
来源：http://dali.shuidangran.top/Article/details/gtvpioylin.html

Go:   strings.Index(s, "x")
来源：http://dali.shangyingyoupin.top/Article/details/gtaoprtvqt.html

Ruby: s.index("x")
来源：http://dali.nwbrower.top/Article/details/gthllwpxqq.html

C#:   s.IndexOf("x")
来源：http://dali.jinqigufen.top/Article/details/gtxsenwawd.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.quarkkingdee.top/Article/details/gtzulfsjjv.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.tanke756.top/Article/details/gthcgpowom.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.cheryme.top/Article/details/gtnatggtrz.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cashguo.top/Article/details/gtohtwljxl.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.aizwys.cn/Article/details/gtfigcgrzv.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvjpiwzqh.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.shzxlz.cn/Article/details/gtzahpqpxo.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.wangshuangyany.cn/Article/details/gterkiqohi.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.ybcxt.top/Article/details/gtpcpgajzv.html

[E06] 替换子串
来源：http://dali.jyoumei.cn/Article/details/gtiyvhyeph.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.nwbrower.top/Article/details/gtoofnqwhw.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.sufxvd.cn/Article/details/gtdjjsewsr.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.birdmap.top/Article/details/gtrvumidve.html

TS:   s.replaceAll("a", "b")
来源：http://dali.tanke756.top/Article/details/gtoqrrzfvm.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sweek.top/Article/details/gtvonrliuc.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.feifeiyinyue.top/Article/details/gtagnjxsax.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jinqigufen.top/Article/details/gtgxssezxm.html

C#:   s.Replace("a", "b")
来源：http://dali.jinqigufen.top/Article/details/gtsphakfti.html

[E07] 按分隔符拆分
来源：http://dali.yanxiufei.cn/Article/details/gtkyvtmuld.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.fengsongda.top/Article/details/gtzykugtdb.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.hysaishi.cn/Article/details/gtkmgcbthl.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.guowangkeji.top/Article/details/gtjjdwlkko.html

TS:   s.split(",")
来源：http://dali.jinghuilouyu.cn/Article/details/gtnwtbsaie.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.dashuyun.cn/Article/details/gtmlujyjrh.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.cucudq.cn/Article/details/gtryedzlzi.html

Ruby: s.split(",");  s.split
来源：http://dali.xuetiantiany.cn/Article/details/gtaywzufoz.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.ehwqpu.com/Article/details/gtrbqhmpsb.html

[E08] 数组按分隔符合并
来源：http://dali.fzhhl.top/Article/details/gtlmyeggme.html

Py:   ",".join(items)
来源：http://dali.zhengqikj.top/Article/details/gtfysrgnow.html

PHP:  implode(",", $items);
来源：http://dali.andypj.xyz/Article/details/gtcbidexgh.html

JS:   items.join(",")
来源：http://dali.daxiang520.top/Article/details/gtuxfwshdd.html

TS:   items.join(",")
来源：http://dali.316326.xyz/Article/details/gttqlvcctj.html

Java: String.join(",", items)
来源：http://dali.yonumen.top/Article/details/gtmyezdmcp.html

Go:   strings.Join(items, ",")
来源：http://dali.jqgfzy.top/Article/details/gtgbdjaugl.html

Ruby: items.join(",")
来源：http://dali.birdmap.top/Article/details/gthqjmgbld.html

C#:   string.Join(",", items)
来源：http://dali.jlsjyb.cn/Article/details/gtqzqhtlab.html

[E09] 去除所有空白字符
来源：http://dali.sufxvd.cn/Article/details/gtusvfzlza.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzuefdace.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.cashguo.top/Article/details/gtbbypaevi.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.guannengcc.top/Article/details/gtgdhcnyjj.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jiagoushi.top/Article/details/gtnkbwpxen.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.ehwqpu.com/Article/details/gtunyiclof.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.sxryk.cn/Article/details/gtidzdxfbg.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhongyouzk.top/Article/details/gthzjmwciu.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.haohaochexian.top/Article/details/gttbnojhua.html

[E10] 左侧补零 / 定长填充
来源：http://dali.svipenyu.cn/Article/details/gtrurwincx.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yj202588.top/Article/details/gtcapmcjws.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.hywenlv.cn/Article/details/gtupzlkbve.html

JS:   "7".padStart(3, "0")
来源：http://dali.hfpthk.cn/Article/details/gtorhtozae.html

TS:   "7".padStart(3, "0")
来源：http://dali.chenzaomai.com/Article/details/gtachaodel.html

Java: String.format("%03d", 7)
来源：http://dali.yangfankeji.com/Article/details/gtdwtdusme.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yanxiufei.cn/Article/details/gtjbwcvhtj.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jiagoushi.top/Article/details/gtlcpefbdp.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jinqigfzy.top/Article/details/gtvgoivyzm.html

[E11] 反转字符串
来源：http://dali.316326.xyz/Article/details/gtgivdvfkf.html

Py:   s[::-1]
来源：http://dali.andypj.xyz/Article/details/gtufacucsg.html

PHP:  strrev($s);
来源：http://dali.guowangkeji.top/Article/details/gtmmddqjen.html

JS:   [...s].reverse().join("")
来源：http://dali.sweek.top/Article/details/gtenqfojqy.html

TS:   [...s].reverse().join("")
来源：http://dali.jyoumei.cn/Article/details/gtlnczbiyo.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yj20258888.top/Article/details/gtslyogrlk.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.shangyingyoupin.top/Article/details/gtuhjogdpx.html

Ruby: s.reverse
来源：http://dali.zhiwuduotai.top/Article/details/gtgqihtdnp.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jinqigfzy.top/Article/details/gtqzokpnpn.html

[E12] 统计某字符出现次数
来源：http://dali.daria6918.cn/Article/details/gtztfiiuzw.html

Py:   s.count("a")
来源：http://dali.chenzaomai.com/Article/details/gtcckbkjmw.html

PHP:  substr_count($s, "a");
来源：http://dali.vqdsnc.cn/Article/details/gtuvcsmcla.html

JS:   s.split("a").length - 1
来源：http://dali.jyoumei.cn/Article/details/gtpdggbioh.html

TS:   s.split("a").length - 1
来源：http://dali.nanxuanxn.top/Article/details/gtiuzuawsg.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yongpay.top/Article/details/gthxxjsmbx.html

Go:   strings.Count(s, "a")
来源：http://dali.hywenlv.cn/Article/details/gtnmztwcwg.html

Ruby: s.count("a")
来源：http://dali.gotoacloud.top/Article/details/gtzbdcqxpx.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zycfv.cn/Article/details/gtbxnjzcht.html

[E13] 逐字符遍历
来源：http://dali.yvedp.cn/Article/details/gtzhkwdoaq.html

Py:   for ch in s: print(ch)
来源：http://dali.jinqigfzy.top/Article/details/gtaajiuxha.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.aibaodan.cn/Article/details/gtcxnlvpny.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xuanzx.com/Article/details/gtyasvqxpg.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hysaishi.cn/Article/details/gtlyeqkvba.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.aibaodan.cn/Article/details/gtuglqrpku.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.gotoacloud.top/Article/details/gtqgqvdean.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.guowangkeji.top/Article/details/gtbuvesyta.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.xinyue.icu/Article/details/gtlsuagdjp.html

[E14] URL 编码与 Base64
来源：http://dali.fzhhl.top/Article/details/gtkpsvcvjy.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcrmaykrb.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.nanxuanxn.top/Article/details/gtzobuwdrh.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yueranfly.top/Article/details/gtthqhympc.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtfucctkjg.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.fzhhl.top/Article/details/gtwlvlxyjx.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.xylfe.cn/Article/details/gthsjjyvqa.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.fzhhl.top/Article/details/gtdmhoiqcs.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jinqigufen.top/Article/details/gthhnfhzst.html

[E15] HTML 转义 / 反转义
来源：http://dali.yueranfly.top/Article/details/gtdnnvalmr.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.nwbrower.top/Article/details/gtkewapixl.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.dashuyun.cn/Article/details/gtrhbpnblu.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gtzesmovky.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hysaishi.cn/Article/details/gtwbymhcau.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.sweek.top/Article/details/gthnciujvk.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hywenlv.cn/Article/details/gtmawdwbuo.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.havefunace.top/Article/details/gtxamxpnvb.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.wangdashe.top/Article/details/gtvzuxndbu.html

[E16] 数字千分位
来源：http://dali.jqgfzy.top/Article/details/gtrvcaeqbd.html

Py:   f"{1234567:,}"
来源：http://dali.zhengqikj.top/Article/details/gteibfwxnr.html

PHP:  number_format(1234567);
来源：http://dali.shangyingyoupin.top/Article/details/gtxgidfgue.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhoulong.xyz/Article/details/gtarcpnihd.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.quarkkingdee.top/Article/details/gtagkovjwq.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.ehwqpu.com/Article/details/gtbkjkryek.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hongshengwenyu.top/Article/details/gtflxaftwc.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hywenlv.cn/Article/details/gtgpmjgzyu.html

C#:   1234567.ToString("N0")
来源：http://dali.hnxiangtu.top/Article/details/gtujgrowuv.html

[E17] 首字母大写
来源：http://dali.cqqwz.cn/Article/details/gtcyrzkznw.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.feifeiyinyue.top/Article/details/gtchsyfdsj.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.tanke756.top/Article/details/gtpxndavfz.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenzaomai.com/Article/details/gtdvsckcyf.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ehwqpu.com/Article/details/gtwgjqhtjs.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jqgufenzy.top/Article/details/gtweruxstp.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.wangshuangyany.cn/Article/details/gtqhnqyxwp.html

Ruby: s.capitalize
来源：http://dali.sweek.top/Article/details/gtuekiukkv.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jyoumei.cn/Article/details/gtvfwhkial.html

[E18] 模板占位符替换
来源：http://dali.zhixingplan.top/Article/details/gtcoesrsks.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jlsjyb.cn/Article/details/gtbbarwoqp.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.ybcxt.top/Article/details/gtuxipxkfy.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.xuanzx.com/Article/details/gtsfdtjbio.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.cqqwz.cn/Article/details/gtdrmislud.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.havefunace.top/Article/details/gthqruaqcp.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.chenjidiqi.icu/Article/details/gtxynewokx.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.chenjidiqi.icu/Article/details/gtsrseecgv.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.xziqi.cn/Article/details/gtvtshwyzs.html

[E19] 多行文本按行拆分
来源：http://dali.kuanghao11.cn/Article/details/gtktzbmusc.html

Py:   s.splitlines()
来源：http://dali.tianlin.xyz/Article/details/gtbpiycgtw.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.dianchejie.cn/Article/details/gtvkseoyej.html

JS:   s.split(/\r?\n/)
来源：http://dali.smart0.xyz/Article/details/gtbummtern.html

TS:   s.split(/\r?\n/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttzyfagwx.html

Java: s.lines().toList()
来源：http://dali.vqdsnc.cn/Article/details/gtaznfeowv.html

Go:   strings.Split(s, "\n")
来源：http://dali.sufxvd.cn/Article/details/gtawwewapo.html

Ruby: s.lines
来源：http://dali.jinqigfzy.top/Article/details/gtcexzqguz.html

C#:   s.Split('\n')
来源：http://dali.jinqigufen.top/Article/details/gtusxbcego.html

[E20] 判断字符串是否为空
来源：http://dali.gogol.net.cn/Article/details/gtyzseyela.html

Py:   if not s:
来源：http://dali.gzhubu.top/Article/details/gthocgwhre.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.chenzaomai.com/Article/details/gtrfwthekg.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.svipenyu.cn/Article/details/gtrgxnfvqg.html

TS:   if (s === "") {}
来源：http://dali.yuxming.cn/Article/details/gtgngupuwb.html

Java: if (s.isEmpty()) {}
来源：http://dali.hysaishi.cn/Article/details/gtnhyyolab.html

Go:   if s == "" {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtkkdtadia.html

Ruby: if s.empty?
来源：http://dali.xziqi.cn/Article/details/gtplpcrqgj.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.xuanzx.com/Article/details/gtpqdnorus.html

[E21] 超长截断加省略号
来源：http://dali.chenjidiqi.icu/Article/details/gtrvwmffxx.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hfpthk.cn/Article/details/gtkmjjppgr.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.svipenyu.cn/Article/details/gtohqwxbru.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yueranfly.top/Article/details/gtbciwsyyg.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jianghu66.top/Article/details/gtejmtfxqw.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jlsjyb.cn/Article/details/gtoojydjkr.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.9152youxi.cn/Article/details/gtsfrwuuzi.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.vqdsnc.cn/Article/details/gtktdbymsn.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yueranfly.top/Article/details/gtrejbgwoi.html

[E22] 字节长度与字符长度
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwrzallng.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.snrcjt.cn/Article/details/gtfqfpllwv.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sufxvd.cn/Article/details/gtnrsyxmdu.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.nanxinkj.top/Article/details/gtbakdhxvv.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hywenlv.cn/Article/details/gtafjcvccd.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.nwbrower.top/Article/details/gtqturmjbf.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.cucudq.cn/Article/details/gtrjjyfyxt.html

Ruby: s.bytesize;  s.length
来源：http://dali.svipenyu.cn/Article/details/gtjryqpwds.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.cashguo.top/Article/details/gtgmjijhzn.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtyokfvpen.html

F. 文件与目录
来源：http://dali.yanxiufei.cn/Article/details/gtidiewssz.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtdsmcwrqt.html

[F01] 读取整个文件
来源：http://dali.hfpthk.cn/Article/details/gtupgiiukf.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yuanzhike.top/Article/details/gtvaiuilfu.html

PHP:  file_get_contents("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtfwjxsdbk.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.bjfxy.top/Article/details/gtguphfcma.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.shangyingyoupin.top/Article/details/gtsftpnqmq.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhiwuduotai.top/Article/details/gtjiapgabi.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.tian-w.cn/Article/details/gtztudokec.html

Ruby: File.read("a.txt")
来源：http://dali.316326.xyz/Article/details/gtxuxdajqk.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gtjbsashxv.html

[F02] 逐行读取文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbfejhyvu.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yangfankeji.com/Article/details/gtcmhvgfuo.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.chenzaomai.com/Article/details/gtxeqdeejr.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.daxiang520.top/Article/details/gtyxjkpmzq.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtdqvgwcrn.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.quarkkingdee.top/Article/details/gttoagotwi.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yonumen.top/Article/details/gtcqpihepz.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.daxiang520.top/Article/details/gtlnjncbnc.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.0kj1m.cn/Article/details/gtokwxckit.html

[F03] 写入文件（覆盖）
来源：http://dali.xuetiantiany.cn/Article/details/gtvgphfqki.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.wangdashe.top/Article/details/gtpdoewsbp.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.hfpthk.cn/Article/details/gtcohulora.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gzhubu.top/Article/details/gtzcxuvnpx.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cheryme.top/Article/details/gtffiohkxi.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcrylxlcg.html


<!-- 参考信息 -->