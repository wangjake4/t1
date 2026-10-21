代发 wailian999

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.dianchejie.cn/Article/details/gtmsrvwxex.html

[D20] 统计每个元素出现次数
来源：http://dali.yongpay.top/Article/details/gtzkoaznkz.html

Py:   Counter(arr)
来源：http://dali.yj20258.top/Article/details/gtbwvxhpwz.html

PHP:  array_count_values($arr);
来源：http://dali.yj20258.top/Article/details/gtkmjguwmn.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.iojbl.cn/Article/details/gttxuofwxd.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.aibaodan.cn/Article/details/gthytrhnuc.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.pycfn.com/Article/details/gtdysgjurp.html

Go:   // 手写 map[T]int
来源：http://dali.bjfxy.top/Article/details/gtermyxoke.html

Ruby: arr.tally
来源：http://dali.aibaodan.cn/Article/details/gtrangtfit.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yj20258.top/Article/details/gthcsngjdf.html

[D21] 判断是否包含某元素
来源：http://dali.aizwys.cn/Article/details/gtstqjafdl.html

Py:   x in arr
来源：http://dali.aibaodan.cn/Article/details/gtzcsikgyz.html

PHP:  in_array($x, $arr, true);
来源：http://dali.gotoacloud.top/Article/details/gtfpwnowya.html

JS:   arr.includes(x)
来源：http://dali.nwbrower.top/Article/details/gtetpyfcgc.html

TS:   arr.includes(x)
来源：http://dali.haohaochexian.top/Article/details/gtgztaxwkp.html

Java: list.contains(x)
来源：http://dali.pycfn.com/Article/details/gtrqnfkciw.html

Go:   slices.Contains(arr, x)
来源：http://dali.yj20258888.top/Article/details/gtnbghhzhd.html

Ruby: arr.include?(x)
来源：http://dali.havefunace.top/Article/details/gtwhclohou.html

C#:   list.Contains(x)
来源：http://dali.yanxiufei.cn/Article/details/gtagfkxxeo.html

[D22] 复制数组（避免共享引用）
来源：http://dali.cdnleiting.top/Article/details/gtqrwlbdke.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwiayvlvv.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.fzhhl.top/Article/details/gtvsrkgulf.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.cashguo.top/Article/details/gtsqtonxfh.html

TS:   [...arr];
来源：http://dali.yj20258888.top/Article/details/gtllrneftd.html

Java: new ArrayList<>(list);
来源：http://dali.zhengqikj.top/Article/details/gtjijgjtxt.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gtmaqnvmyi.html

Ruby: arr.dup;  arr.clone
来源：http://dali.snrcjt.cn/Article/details/gtjmpiyidx.html

C#:   new List<int>(list);
来源：http://dali.xuanzx.com/Article/details/gtlgscpole.html

[D23] reduce 累积计算
来源：http://dali.havefunace.top/Article/details/gtabmvhnhv.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.andypj.xyz/Article/details/gtopzwqjlv.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.shzxlz.cn/Article/details/gtkflmsisg.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yvedp.cn/Article/details/gtquupharo.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zycfv.cn/Article/details/gtouzdxrgk.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zycfv.cn/Article/details/gttsxgdglx.html

Go:   // 手写循环
来源：http://dali.nanxuanxn.top/Article/details/gtifaeodqc.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.shuidangran.top/Article/details/gtnqiggwxy.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zycfv.cn/Article/details/gtofrlebke.html

[D24] 字典 / Map 基本操作
来源：http://dali.nwbrower.top/Article/details/gtbhvitktb.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yonumen.top/Article/details/gtjmoqofyr.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.aibaodan.cn/Article/details/gtpeoeredl.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hywenlv.cn/Article/details/gtlyyphuas.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.sufxvd.cn/Article/details/gtmkmfccgb.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jinghuilouyu.cn/Article/details/gtumdorvyz.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.xuetiantiany.cn/Article/details/gtgckmckdw.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jianghu66.top/Article/details/gtqvtqqijj.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.hnqzz.top/Article/details/gtfiozudnv.html

[D25] Set 集合去重与交并差
来源：http://dali.jqgufenzy.top/Article/details/gtajwdipqh.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.aizwys.cn/Article/details/gtagsauvso.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.nanxuanxn.top/Article/details/gtuyoarwyw.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jianghu66.top/Article/details/gtqmapynuf.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.pycfn.com/Article/details/gthsyouuvg.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.gzhubu.top/Article/details/gtezvaaivq.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zdqjudy.top/Article/details/gtcsxmxhts.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jlsjyb.cn/Article/details/gtjvdikwts.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gtprbwzmjh.html

[D26] 数组转字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzsamwxrv.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jinqigfzy.top/Article/details/gtmxegckqy.html

PHP:  implode(", ", $arr);
来源：http://dali.zycfv.cn/Article/details/gtildxlrva.html

JS:   arr.join(", ")
来源：http://dali.gotoacloud.top/Article/details/gtiqvbvldl.html

TS:   arr.join(", ")
来源：http://dali.bjfxy.top/Article/details/gtyagkfikw.html

Java: String.join(", ", list)
来源：http://dali.nanxuanxn.top/Article/details/gtbejuywmq.html

Go:   strings.Join(strs, ", ")
来源：http://dali.iojbl.cn/Article/details/gtbfnjyuzs.html

Ruby: arr.join(", ")
来源：http://dali.316326.xyz/Article/details/gtddnjujul.html

C#:   string.Join(", ", list)
来源：http://dali.hnqzz.top/Article/details/gtexzsgjto.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gthlidtuhe.html

E. 字符串处理
来源：http://dali.pengpengdd.cyou/Article/details/gtkocawzhw.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtihudjpyu.html

[E01] 拼接字符串
来源：http://dali.hnxiangtu.top/Article/details/gtnekrkqme.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.shzxlz.cn/Article/details/gtocokosxp.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.tianlin.xyz/Article/details/gtxmqmouqf.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xziqi.cn/Article/details/gtsrhctidh.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.vqdsnc.cn/Article/details/gtkqixatni.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yj202588.top/Article/details/gtnvqdpkrg.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhiwuduotai.top/Article/details/gtqobuhghk.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.meibo888.top/Article/details/gtifbpmyuq.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.daxiang520.top/Article/details/gtziqbcspr.html

[E02] 重复字符串
来源：http://dali.yuxming.cn/Article/details/gtjjlxizlr.html

Py:   "ab" * 3
来源：http://dali.cashguo.top/Article/details/gtdssggoxz.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yonumen.top/Article/details/gtyedqepuo.html

JS:   "ab".repeat(3)
来源：http://dali.yonumen.top/Article/details/gtfkiinkyk.html

TS:   "ab".repeat(3)
来源：http://dali.xylfe.cn/Article/details/gtztnnrlqy.html

Java: "ab".repeat(3)
来源：http://dali.zhoulong.xyz/Article/details/gtmvtedgqh.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jyoumei.cn/Article/details/gtdbbsxwrd.html

Ruby: "ab" * 3
来源：http://dali.cheryme.top/Article/details/gtlbqnoaqt.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.shzxlz.cn/Article/details/gtarouidec.html

[E03] 截取子串
来源：http://dali.zhaomingkeji.xyz/Article/details/gttygotake.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yueranfly.top/Article/details/gtyarbypaq.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jqgufenzy.top/Article/details/gtugtksvay.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.quarkkingdee.top/Article/details/gtngcvjibc.html

TS:   s.slice(1, 4)
来源：http://dali.wangshuangyany.cn/Article/details/gtjyuiozwg.html

Java: s.substring(1, 4)
来源：http://dali.c1oappe.top/Article/details/gttjvgzjzz.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.hnqzz.top/Article/details/gtejnqdfis.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.haohaochexian.top/Article/details/gtzoaxsynf.html

C#:   s.Substring(1, 3)
来源：http://dali.tian-w.cn/Article/details/gtcjcmctmh.html

[E04] 查找子串位置
来源：http://dali.nanxuanxn.top/Article/details/gthzgqgkgs.html

Py:   s.find("x");  s.index("x")
来源：http://dali.wangdashe.top/Article/details/gttrqfrjuj.html

PHP:  strpos($s, "x");
来源：http://dali.bjfxy.top/Article/details/gtuquazvdt.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.hammf.cn/Article/details/gtkkbpkwki.html

TS:   s.indexOf("x")
来源：http://dali.xuanzx.com/Article/details/gtkdadkhqt.html

Java: s.indexOf("x")
来源：http://dali.sufxvd.cn/Article/details/gtghbrxpjq.html

Go:   strings.Index(s, "x")
来源：http://dali.tianlin.xyz/Article/details/gtmabqzmrl.html

Ruby: s.index("x")
来源：http://dali.yueranfly.top/Article/details/gtsjxxnuyy.html

C#:   s.IndexOf("x")
来源：http://dali.bjfxy.top/Article/details/gtislgwmha.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.andypj.xyz/Article/details/gtkwzyonwb.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.iojbl.cn/Article/details/gtmlmhvjdq.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgawqchtu.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yuanzhike.top/Article/details/gtvfskmldv.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jinqigfzy.top/Article/details/gtewlstwlf.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ppjwa.cn/Article/details/gthmtztdob.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.fzhhl.top/Article/details/gtibzealup.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.guannengcc.top/Article/details/gtwnappido.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.xziqi.cn/Article/details/gtiowmfdky.html

[E06] 替换子串
来源：http://dali.gogol.net.cn/Article/details/gtazxmoggm.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.tian-w.cn/Article/details/gtjhqrnhfa.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yj202588.top/Article/details/gtwlswtnpz.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhaomingkeji.xyz/Article/details/gttbwtzzhw.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jianghu66.top/Article/details/gtldqkohyw.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.dianchejie.cn/Article/details/gtbvmfzqhm.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.ppjwa.cn/Article/details/gtsrslqgzy.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.quarkkingdee.top/Article/details/gtzxyvogzp.html

C#:   s.Replace("a", "b")
来源：http://dali.yj20258888.top/Article/details/gtlnrufreg.html

[E07] 按分隔符拆分
来源：http://dali.pycfn.com/Article/details/gtqwbguadq.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.pengpengdd.cyou/Article/details/gtttaoqkyi.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.cheryme.top/Article/details/gtpfayaazx.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yonumen.top/Article/details/gtufdkjkil.html

TS:   s.split(",")
来源：http://dali.shanyushiyangtech.top/Article/details/gttqryjnsf.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.cheryme.top/Article/details/gtvgbznsrc.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yuxming.cn/Article/details/gtamidqhks.html

Ruby: s.split(",");  s.split
来源：http://dali.yongpay.top/Article/details/gtnluwlofg.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jqgufenzy.top/Article/details/gtfeuqvfzy.html

[E08] 数组按分隔符合并
来源：http://dali.jqgufenzy.top/Article/details/gtzwmbphgw.html

Py:   ",".join(items)
来源：http://dali.ppjwa.cn/Article/details/gtgzpqbwin.html

PHP:  implode(",", $items);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlfcctqoy.html

JS:   items.join(",")
来源：http://dali.zdqjudy.top/Article/details/gtvaualqqm.html

TS:   items.join(",")
来源：http://dali.jinqigfzy.top/Article/details/gtgcxljnto.html

Java: String.join(",", items)
来源：http://dali.hfpthk.cn/Article/details/gtcpfuvzpf.html

Go:   strings.Join(items, ",")
来源：http://dali.gogol.net.cn/Article/details/gtclcoojpp.html

Ruby: items.join(",")
来源：http://dali.svipenyu.cn/Article/details/gthrzottaw.html

C#:   string.Join(",", items)
来源：http://dali.daria6918.cn/Article/details/gtfmetzwpr.html

[E09] 去除所有空白字符
来源：http://dali.yuxming.cn/Article/details/gtvkswfqzy.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.wangdashe.top/Article/details/gtjlupempk.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.dashuyun.cn/Article/details/gtxuyodcpy.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.guowangkeji.top/Article/details/gthkvcusph.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yj202588.top/Article/details/gtswcdjpob.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yongpay.top/Article/details/gtyscixhun.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.shzxlz.cn/Article/details/gturmqnzpu.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.nanxuanxn.top/Article/details/gtxmthrwpt.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.sysykeji.top/Article/details/gtmflsbmox.html

[E10] 左侧补零 / 定长填充
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfxnmdseg.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.shuidangran.top/Article/details/gtepfsgpai.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yanxiufei.cn/Article/details/gtjlyreuov.html

JS:   "7".padStart(3, "0")
来源：http://dali.zdqjudy.top/Article/details/gtkynsldes.html

TS:   "7".padStart(3, "0")
来源：http://dali.chenzaomai.com/Article/details/gtmkqwoayt.html

Java: String.format("%03d", 7)
来源：http://dali.chenzaomai.com/Article/details/gtvxvlvzsz.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yuanzhike.top/Article/details/gtrtjxtdhi.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.aibaodan.cn/Article/details/gtmirjkmvg.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.hysaishi.cn/Article/details/gtdxspskqz.html

[E11] 反转字符串
来源：http://dali.xinyue.icu/Article/details/gtkbzqclrw.html

Py:   s[::-1]
来源：http://dali.hammf.cn/Article/details/gtyivxdamr.html

PHP:  strrev($s);
来源：http://dali.nanxinkj.top/Article/details/gtkdzqtrwu.html

JS:   [...s].reverse().join("")
来源：http://dali.yongpay.top/Article/details/gthcnubbmx.html

TS:   [...s].reverse().join("")
来源：http://dali.xziqi.cn/Article/details/gteerqwivi.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.xinyue.icu/Article/details/gtzkklrubk.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.ivvv.top/Article/details/gtdszpcfeg.html

Ruby: s.reverse
来源：http://dali.bjfxy.top/Article/details/gtemksrfzo.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.chenjidiqi.icu/Article/details/gtwbdwsejf.html

[E12] 统计某字符出现次数
来源：http://dali.shanyushiyangtech.top/Article/details/gtorvilbre.html

Py:   s.count("a")
来源：http://dali.zhixingplan.top/Article/details/gtlouxmcgg.html

PHP:  substr_count($s, "a");
来源：http://dali.andypj.xyz/Article/details/gtvcrwojrd.html

JS:   s.split("a").length - 1
来源：http://dali.daxiang520.top/Article/details/gtsgdadzkq.html

TS:   s.split("a").length - 1
来源：http://dali.yonumen.top/Article/details/gtdmxakdpf.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhengqikj.top/Article/details/gtpaghxqzo.html

Go:   strings.Count(s, "a")
来源：http://dali.xinyue.icu/Article/details/gtmeemmxcd.html

Ruby: s.count("a")
来源：http://dali.chenzaomai.com/Article/details/gtmjggilpl.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jinqigufen.top/Article/details/gtmerlxdzf.html

[E13] 逐字符遍历
来源：http://dali.zhongyouzk.top/Article/details/gtibjgwbrd.html

Py:   for ch in s: print(ch)
来源：http://dali.jlsjyb.cn/Article/details/gtrntwlott.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.snrcjt.cn/Article/details/gtkdewiiam.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shangyingyoupin.top/Article/details/gtmhhxtmtq.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jyoumei.cn/Article/details/gtvbtxgcov.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jlsjyb.cn/Article/details/gtpiniayxg.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.bjfxy.top/Article/details/gtnfqvdiqd.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhixingplan.top/Article/details/gtvqdjrwmz.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.mhx1999.top/Article/details/gtenvnrexd.html

[E14] URL 编码与 Base64
来源：http://dali.hammf.cn/Article/details/gtidebzdpj.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.ppjwa.cn/Article/details/gtumbihfyb.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhoulong.xyz/Article/details/gtazifytmh.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jyoumei.cn/Article/details/gtnybjbxlo.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.hnqzz.top/Article/details/gtmknnriig.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.fzhhl.top/Article/details/gtlcfxrdxw.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.cqqwz.cn/Article/details/gtftrbaorx.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xinyue.icu/Article/details/gtzcmmmatd.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.wangdashe.top/Article/details/gtibmwltih.html

[E15] HTML 转义 / 反转义
来源：http://dali.yuanzhike.top/Article/details/gtcpojyezm.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yj20258.top/Article/details/gttakqoojy.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jlsjyb.cn/Article/details/gtkryzdksk.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.nanxuanxn.top/Article/details/gttlmyvgxo.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jiagoushi.top/Article/details/gtjqwvohqd.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.wangshuangyany.cn/Article/details/gtkmkwrkkq.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xuanzx.com/Article/details/gtgkrikrem.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtvtrlcaam.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhengqikj.top/Article/details/gthilmihyr.html

[E16] 数字千分位
来源：http://dali.shzxlz.cn/Article/details/gtdoyguweo.html

Py:   f"{1234567:,}"
来源：http://dali.daria6918.cn/Article/details/gtphbumafj.html

PHP:  number_format(1234567);
来源：http://dali.shzxlz.cn/Article/details/gtwvhtpfcv.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jqgfzy.top/Article/details/gtlavluaij.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yj20258888.top/Article/details/gtungffqie.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.guowangkeji.top/Article/details/gtvzsmoiyc.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.tianlin.xyz/Article/details/gtkdpmarfs.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.chenlongwang.top/Article/details/gtglljwzpi.html

C#:   1234567.ToString("N0")
来源：http://dali.hnqzz.top/Article/details/gtiufduxan.html

[E17] 首字母大写
来源：http://dali.yvedp.cn/Article/details/gtedewgvhj.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.wangshuangyany.cn/Article/details/gtwamqewzj.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jlsjyb.cn/Article/details/gttcdjbcao.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.dashuyun.cn/Article/details/gtwyimtgjw.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.316326.xyz/Article/details/gtqwhrbwfz.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yj202588.top/Article/details/gtaotfmoqr.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.gogol.net.cn/Article/details/gtsebsjxix.html

Ruby: s.capitalize
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrvceplky.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.pengpengdd.cyou/Article/details/gtmyrvpupn.html

[E18] 模板占位符替换
来源：http://dali.daxiang520.top/Article/details/gteulybewj.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.andypj.xyz/Article/details/gtpwdpknsq.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.wangshuangyany.cn/Article/details/gthomxybpo.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hammf.cn/Article/details/gtmtkxmdxu.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.tian-w.cn/Article/details/gtglgavvos.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.tianlin.xyz/Article/details/gtoeypuewm.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.cdnleiting.top/Article/details/gtuglwdznj.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.tanke756.top/Article/details/gtjxwpkixm.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.dianchejie.cn/Article/details/gtnidqrvsz.html

[E19] 多行文本按行拆分
来源：http://dali.quarkkingdee.top/Article/details/gtfujboiem.html

Py:   s.splitlines()
来源：http://dali.hysaishi.cn/Article/details/gtahvehmlb.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmphdsvpc.html

JS:   s.split(/\r?\n/)
来源：http://dali.wangdashe.top/Article/details/gtzcfjdarg.html

TS:   s.split(/\r?\n/)
来源：http://dali.c1oappe.top/Article/details/gtkiddbbbd.html

Java: s.lines().toList()
来源：http://dali.jianghu66.top/Article/details/gtdzaxnjbv.html

Go:   strings.Split(s, "\n")
来源：http://dali.snrcjt.cn/Article/details/gtkacvngiw.html

Ruby: s.lines
来源：http://dali.quarkkingdee.top/Article/details/gthsklsrja.html

C#:   s.Split('\n')
来源：http://dali.zhiwuduotai.top/Article/details/gtooldmcqq.html

[E20] 判断字符串是否为空
来源：http://dali.yj20258.top/Article/details/gtzeokogtz.html

Py:   if not s:
来源：http://dali.jianghu66.top/Article/details/gtvhkakeui.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.dashuyun.cn/Article/details/gtpzydiaon.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yangfankeji.com/Article/details/gtrzbbeomr.html

TS:   if (s === "") {}
来源：http://dali.fengsongda.top/Article/details/gtzkhfjiih.html

Java: if (s.isEmpty()) {}
来源：http://dali.xuanzx.com/Article/details/gtszljxhdu.html

Go:   if s == "" {}
来源：http://dali.cdnleiting.top/Article/details/gthfftxizm.html

Ruby: if s.empty?
来源：http://dali.pengpengdd.cyou/Article/details/gtokfzyjgt.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.dashuyun.cn/Article/details/gtilbtmlmq.html

[E21] 超长截断加省略号
来源：http://dali.xinyue.icu/Article/details/gtusllhwsg.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jyoumei.cn/Article/details/gtjtapiiwr.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.snrcjt.cn/Article/details/gtwyjkgbjn.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdremkgup.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gogol.net.cn/Article/details/gtxnkiqzpp.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.birdmap.top/Article/details/gtgppuamnx.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.nwbrower.top/Article/details/gtkrkxkgrp.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.guowangkeji.top/Article/details/gtcouiiwwz.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jinyuanbaomall.cn/Article/details/gtawiqzfgm.html

[E22] 字节长度与字符长度
来源：http://dali.fengsongda.top/Article/details/gtasgecxcy.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.cashguo.top/Article/details/gthddtxrsd.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ywan-chungtsiang.top/Article/details/gthmbuyyjx.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yanxiufei.cn/Article/details/gtxwnwifiq.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jyoumei.cn/Article/details/gtiidfkhfx.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.daxiang520.top/Article/details/gtdgdtxyqt.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.cqqwz.cn/Article/details/gtxezobxta.html

Ruby: s.bytesize;  s.length
来源：http://dali.birdmap.top/Article/details/gtegilehdm.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.birdmap.top/Article/details/gtxwpeqrkv.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtmmbbpnoi.html

F. 文件与目录
来源：http://dali.yj20258.top/Article/details/gtpuuuzvzq.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtmoozahnd.html

[F01] 读取整个文件
来源：http://dali.sweek.top/Article/details/gtfstdujha.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.shuidangran.top/Article/details/gtudlsfbcy.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gtoisktwrk.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.xziqi.cn/Article/details/gtpubkchbz.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.quarkkingdee.top/Article/details/gtahkslaur.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hfpthk.cn/Article/details/gtzvzxnfzc.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.andypj.xyz/Article/details/gthxdmmvsl.html

Ruby: File.read("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtaxfyfebi.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.redwolf501.top/Article/details/gtuuhhyiso.html

[F02] 逐行读取文件
来源：http://dali.dashuyun.cn/Article/details/gtfjiozdeb.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.andypj.xyz/Article/details/gtjczchjwh.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hywenlv.cn/Article/details/gthzxwxvqi.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cashguo.top/Article/details/gtwswfqpjs.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.316326.xyz/Article/details/gtrpxebfgp.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.0kj1m.cn/Article/details/gttigxhcsd.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jqgfzy.top/Article/details/gtmnxzrslt.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.ydzc1.top/Article/details/gtoiukxohn.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.guowangkeji.top/Article/details/gtjhkbxtot.html

[F03] 写入文件（覆盖）
来源：http://dali.yueranfly.top/Article/details/gtnkckzmsk.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.cashguo.top/Article/details/gtimlaaiuy.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.gogol.net.cn/Article/details/gthdsatbbs.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj20258888.top/Article/details/gtrudmzick.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xuetiantiany.cn/Article/details/gtmfifwocz.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.xuanzx.com/Article/details/gtditxtpju.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.hysaishi.cn/Article/details/gtpwxkmavu.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.tanke756.top/Article/details/gtdcrfnsby.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.shuidangran.top/Article/details/gtospncwfl.html

[F04] 追加写入文件
来源：http://dali.jianghu66.top/Article/details/gtnkblbahu.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hfpthk.cn/Article/details/gtaezmpdqb.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.316326.xyz/Article/details/gtyxnmvewv.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yonumen.top/Article/details/gtwaiaakle.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xziqi.cn/Article/details/gtheglnxou.html


<!-- 参考信息 -->