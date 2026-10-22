代发 wailian999

Go:   // 无重载：用不同函数名
来源：http://dali.shangyingyoupin.top/Article/details/gtvxktlawh.html

Ruby: # 无重载：靠动态参数
来源：http://dali.chenzaomai.com/Article/details/gtxiipjunc.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.shuidangran.top/Article/details/gtclscftvo.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyaptwvrm.html

D. 数组 / 列表 / 集合
来源：http://dali.hfpthk.cn/Article/details/gtsbixhxfr.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtwerxeewy.html

[D01] 创建数组 / 列表
来源：http://dali.jinqigfzy.top/Article/details/gtgdqlrexw.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.kuanghao11.cn/Article/details/gtxhgzayfv.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.guowangkeji.top/Article/details/gtnzfkdbcr.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.xylfe.cn/Article/details/gtcftsabbv.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jlsjyb.cn/Article/details/gtlxaxhzjw.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jinqigfzy.top/Article/details/gtzkwbobun.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.guowangkeji.top/Article/details/gtwbphmiju.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhiwuduotai.top/Article/details/gtemmytgwl.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zdqjudy.top/Article/details/gtlbyknnyr.html

[D02] 追加元素到末尾
来源：http://dali.ybcxt.top/Article/details/gtkbdlapku.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.shuidangran.top/Article/details/gtrkskmpee.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jqgfzy.top/Article/details/gtseltenvb.html

JS:   arr.push(4);
来源：http://dali.shanyushiyangtech.top/Article/details/gtsejoeqhk.html

TS:   arr.push(4);
来源：http://dali.yangfankeji.com/Article/details/gtgoomkxzh.html

Java: list.add(4);
来源：http://dali.fengsongda.top/Article/details/gtioolcgfp.html

Go:   arr = append(arr, 4)
来源：http://dali.nanxuanxn.top/Article/details/gtgjbvfueq.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.pycfn.com/Article/details/gtnszjuwgx.html

C#:   list.Add(4);
来源：http://dali.smart0.xyz/Article/details/gtlpdkujsa.html

[D03] 在指定位置插入元素
来源：http://dali.yonumen.top/Article/details/gtywjafono.html

Py:   arr.insert(0, 0)
来源：http://dali.shzxlz.cn/Article/details/gtdsdndehh.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.chenlongwang.top/Article/details/gtsfcbpbho.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.pycfn.com/Article/details/gtnstdojsn.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.andypj.xyz/Article/details/gtgjdhvzai.html

Java: list.add(0, 0);
来源：http://dali.wangdashe.top/Article/details/gteyulgllk.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.iojbl.cn/Article/details/gtxhuzzenw.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.cdnleiting.top/Article/details/gtyutjmnav.html

C#:   list.Insert(0, 0);
来源：http://dali.dashuyun.cn/Article/details/gtmmuzlcvb.html

[D04] 删除元素
来源：http://dali.gotoacloud.top/Article/details/gtdgaplzfq.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.fengsongda.top/Article/details/gtblhbofcy.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.svipenyu.cn/Article/details/gtwsxjoozh.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.daria6918.cn/Article/details/gtkbdvlswj.html

TS:   arr.splice(0, 1);
来源：http://dali.dashuyun.cn/Article/details/gthzhikmqc.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.mhx1999.top/Article/details/gtleqbgpzd.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.shzxlz.cn/Article/details/gtgdvdbxew.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.wangdashe.top/Article/details/gtgfltwabm.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yonumen.top/Article/details/gtuepkpltv.html

[D05] 访问与修改元素
来源：http://dali.iojbl.cn/Article/details/gtguorkmqi.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shuidangran.top/Article/details/gtiijvjqqf.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.xinyue.icu/Article/details/gtfsgrulde.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yj20258.top/Article/details/gtkvooajga.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yvedp.cn/Article/details/gtozxwqfhl.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yj202588.top/Article/details/gtwutrnign.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhoulong.xyz/Article/details/gtmvpsyitb.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yongpay.top/Article/details/gtjdwwmuue.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yangfankeji.com/Article/details/gtqigihyxb.html

[D06] 数组长度
来源：http://dali.xuanzx.com/Article/details/gtdwyceikh.html

Py:   len(arr)
来源：http://dali.yvedp.cn/Article/details/gtrrniepnf.html

PHP:  count($arr);
来源：http://dali.pycfn.com/Article/details/gtcuvrikgc.html

JS:   arr.length
来源：http://dali.cdnleiting.top/Article/details/gtjixkprmf.html

TS:   arr.length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmosulxdl.html

Java: list.size();
来源：http://dali.snrcjt.cn/Article/details/gtqdrvcxba.html

Go:   len(arr)
来源：http://dali.hfpthk.cn/Article/details/gtwdjihzsy.html

Ruby: arr.length; arr.size
来源：http://dali.yj20258888.top/Article/details/gttgcnycch.html

C#:   list.Count;
来源：http://dali.iojbl.cn/Article/details/gtytqmplfs.html

[D07] 切片 / 取子数组
来源：http://dali.yj20258.top/Article/details/gtszkvjbqo.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.havefunace.top/Article/details/gtosuqevnq.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.xuanzx.com/Article/details/gtovrufkbt.html

JS:   arr.slice(1, 4);
来源：http://dali.zdqjudy.top/Article/details/gtfmwwttjd.html

TS:   arr.slice(1, 4);
来源：http://dali.hfpthk.cn/Article/details/gtmmsfjurm.html

Java: list.subList(1, 4);
来源：http://dali.gzhubu.top/Article/details/gtbwgynvjh.html

Go:   arr[1:4]
来源：http://dali.xinyue.icu/Article/details/gtoleibyfx.html

Ruby: arr[1, 3]
来源：http://dali.gotoacloud.top/Article/details/gtrmwhkxie.html

C#:   list.GetRange(1, 3);
来源：http://dali.xylfe.cn/Article/details/gtxfnlbjzh.html

[D08] 合并两个数组
来源：http://dali.havefunace.top/Article/details/gtpgalknbx.html

Py:   a + b;  a.extend(b)
来源：http://dali.iojbl.cn/Article/details/gtfikxvlyd.html

PHP:  array_merge($a, $b);
来源：http://dali.shuidangran.top/Article/details/gtrnljcwvm.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.feifeiyinyue.top/Article/details/gtuzffitrt.html

TS:   [...a, ...b];
来源：http://dali.zdqjudy.top/Article/details/gtosxzoifk.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.daria6918.cn/Article/details/gtogptbvrs.html

Go:   append(a, b...)
来源：http://dali.jianghu66.top/Article/details/gtmoixwgpf.html

Ruby: a + b;  a.concat(b)
来源：http://dali.xylfe.cn/Article/details/gtmbiivdsr.html

C#:   a.Concat(b).ToList()
来源：http://dali.c1oappe.top/Article/details/gtdxwhtdyb.html

[D09] 排序（升序）
来源：http://dali.chenjidiqi.icu/Article/details/gtddiaaxma.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hnqzz.top/Article/details/gtbeedbdye.html

PHP:  sort($arr);
来源：http://dali.yj20258.top/Article/details/gtcxtfgfpw.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jiagoushi.top/Article/details/gtxioqzzxy.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhengqikj.top/Article/details/gtzsgbgvzy.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmzvyyqae.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtftrrmclw.html

Ruby: arr.sort
来源：http://dali.zhixingplan.top/Article/details/gtyosqiihn.html

C#:   list.Sort();
来源：http://dali.shanyushiyangtech.top/Article/details/gtzjfdknzu.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.shuidangran.top/Article/details/gtenfrxpli.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.chenzaomai.com/Article/details/gtfrstwdev.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.chenlongwang.top/Article/details/gtnjflrbyf.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.pycfn.com/Article/details/gtobiyajjl.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj20258.top/Article/details/gtqyjmryrf.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.havefunace.top/Article/details/gtmcvniegt.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.sweek.top/Article/details/gtlxzadvrc.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.sweek.top/Article/details/gtvzqwxopw.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.meibo888.top/Article/details/gtqglkjder.html

[D11] 反转数组
来源：http://dali.zhongyouzk.top/Article/details/gtrkdngape.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.xylfe.cn/Article/details/gtxyzpbkus.html

PHP:  array_reverse($arr);
来源：http://dali.tanke756.top/Article/details/gtyifzdntu.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.meibo888.top/Article/details/gtvfpcldmb.html

TS:   [...arr].reverse();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwzsyxygx.html

Java: Collections.reverse(list);
来源：http://dali.hysaishi.cn/Article/details/gtprnvddxu.html

Go:   slices.Reverse(arr)
来源：http://dali.cucudq.cn/Article/details/gtaggnmapw.html

Ruby: arr.reverse
来源：http://dali.andypj.xyz/Article/details/gtisxfmxsh.html

C#:   list.Reverse();
来源：http://dali.hnxiangtu.top/Article/details/gthemfaeqk.html

[D12] 查找元素下标
来源：http://dali.nanxuanxn.top/Article/details/gtsrrfbrdq.html

Py:   arr.index(x);  x in arr
来源：http://dali.meibo888.top/Article/details/gtbkgpbdkr.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtkwtetfzo.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yj20258888.top/Article/details/gtloxsobju.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ivvv.top/Article/details/gtleyhlzjt.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yuanzhike.top/Article/details/gtgxthhigd.html

Go:   slices.Index(arr, x)
来源：http://dali.redwolf501.top/Article/details/gtiwhpdkiw.html

Ruby: arr.index(x)
来源：http://dali.birdmap.top/Article/details/gtzbzsntar.html

C#:   list.IndexOf(x);
来源：http://dali.shuidangran.top/Article/details/gtsvkyejci.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yvedp.cn/Article/details/gtcujuishr.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jyoumei.cn/Article/details/gtkiusahqf.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.sweek.top/Article/details/gtosyamskq.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jiagoushi.top/Article/details/gtebtzdvmd.html

TS:   arr.filter(x => x > 3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtonwfnwtt.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.smart0.xyz/Article/details/gtdrwmxvrz.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkdelzfls.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.cheryme.top/Article/details/gtiukryutk.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtayocwwjc.html

[D14] 映射转换（每个元素变形）
来源：http://dali.pycfn.com/Article/details/gtkumwriew.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.9152youxi.cn/Article/details/gtzvgzfpwf.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gttrpnwyul.html

JS:   arr.map(x => x * 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtpyiqffxy.html

TS:   arr.map(x => x * 2)
来源：http://dali.jlsjyb.cn/Article/details/gtodvlkagm.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdhsnrzww.html

Go:   // 手写循环
来源：http://dali.ybcxt.top/Article/details/gteucauurq.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.shangyingyoupin.top/Article/details/gtvzgiizqr.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yanxiufei.cn/Article/details/gtuuwrmyfr.html

[D15] 去重
来源：http://dali.sysykeji.top/Article/details/gtujkyoynz.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.guannengcc.top/Article/details/gtmukryyde.html

PHP:  array_unique($arr);
来源：http://dali.kuanghao11.cn/Article/details/gthhtdupqr.html

JS:   [...new Set(arr)]
来源：http://dali.nwbrower.top/Article/details/gtaxfoenvl.html

TS:   [...new Set(arr)]
来源：http://dali.hnqzz.top/Article/details/gtszkvjqkp.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yongpay.top/Article/details/gtehhbkzxx.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jinqigfzy.top/Article/details/gtfcgjecue.html

Ruby: arr.uniq
来源：http://dali.cheryme.top/Article/details/gtmgpodzcc.html

C#:   list.Distinct().ToList()
来源：http://dali.snrcjt.cn/Article/details/gtohcxvcrm.html

[D16] 求和与平均值
来源：http://dali.yueranfly.top/Article/details/gtbxlfvhpg.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jinqigufen.top/Article/details/gtbfvubbju.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jianghu66.top/Article/details/gtencapyac.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinqigfzy.top/Article/details/gtmhsjaakc.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.havefunace.top/Article/details/gtsllyfpou.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yanxiufei.cn/Article/details/gtorgaekxm.html

Go:   // 手写循环累加
来源：http://dali.hnqzz.top/Article/details/gtadaomrnp.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.pycfn.com/Article/details/gtugecmpzb.html

C#:   list.Sum();  list.Average()
来源：http://dali.yueranfly.top/Article/details/gthrpswjui.html

[D17] 最大值与最小值
来源：http://dali.ehwqpu.com/Article/details/gtlvqrabfs.html

Py:   max(arr);  min(arr)
来源：http://dali.cdnleiting.top/Article/details/gtvleihwch.html

PHP:  max($arr);  min($arr);
来源：http://dali.0kj1m.cn/Article/details/gtntenpqze.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jinqigfzy.top/Article/details/gtkispvhar.html

TS:   Math.max(...arr);
来源：http://dali.nanxuanxn.top/Article/details/gtyssjddsh.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhengqikj.top/Article/details/gtpbhotyye.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.chenzaomai.com/Article/details/gtqtpgvohs.html

Ruby: arr.max;  arr.min
来源：http://dali.yangfankeji.com/Article/details/gtcqzonbix.html

C#:   list.Max();  list.Min()
来源：http://dali.nanxuanxn.top/Article/details/gtvcxutnrs.html

[D18] 扁平化嵌套数组
来源：http://dali.havefunace.top/Article/details/gtxzdbbogn.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.birdmap.top/Article/details/gtqzwwiidh.html

PHP:  array_merge(...$nested);
来源：http://dali.ivvv.top/Article/details/gtupnulcgo.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yonumen.top/Article/details/gtkwtgalup.html

TS:   nested.flat();
来源：http://dali.hysaishi.cn/Article/details/gthtxntgmo.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtetgycyhj.html

Go:   // 手写双层循环
来源：http://dali.yuxming.cn/Article/details/gtykzaouip.html

Ruby: nested.flatten
来源：http://dali.shangyingyoupin.top/Article/details/gtcgvnrzkv.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.nanxinkj.top/Article/details/gttxzabijn.html

[D19] 按字段分组
来源：http://dali.cashguo.top/Article/details/gtbmltfxma.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.andypj.xyz/Article/details/gthyaiikdl.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hammf.cn/Article/details/gtfherccwl.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.snrcjt.cn/Article/details/gtnaqbxomw.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhoulong.xyz/Article/details/gtgbneclce.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zycfv.cn/Article/details/gtlenukmip.html

Go:   // 手写 map[string][]T
来源：http://dali.hywenlv.cn/Article/details/gtkkbgkbun.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hnqzz.top/Article/details/gtvldnnixj.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.pengpengdd.cyou/Article/details/gtpdacdiya.html

[D20] 统计每个元素出现次数
来源：http://dali.yangfankeji.com/Article/details/gtrbcaslii.html

Py:   Counter(arr)
来源：http://dali.gotoacloud.top/Article/details/gthmmqmesq.html

PHP:  array_count_values($arr);
来源：http://dali.havefunace.top/Article/details/gtehbrpngz.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.vqdsnc.cn/Article/details/gthmvtmphj.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gtlltpiwvo.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.shangyingyoupin.top/Article/details/gtmlsyfzbu.html

Go:   // 手写 map[T]int
来源：http://dali.wangshuangyany.cn/Article/details/gtbcdyjang.html

Ruby: arr.tally
来源：http://dali.jinqigufen.top/Article/details/gtjtjwtuii.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.shuidangran.top/Article/details/gtruteddtk.html

[D21] 判断是否包含某元素
来源：http://dali.bjfxy.top/Article/details/gthjdymcge.html

Py:   x in arr
来源：http://dali.dashuyun.cn/Article/details/gtoatuvczx.html

PHP:  in_array($x, $arr, true);
来源：http://dali.gzhubu.top/Article/details/gtnsyirrbx.html

JS:   arr.includes(x)
来源：http://dali.redwolf501.top/Article/details/gteemhipwz.html

TS:   arr.includes(x)
来源：http://dali.hnxiangtu.top/Article/details/gtrpoukopg.html

Java: list.contains(x)
来源：http://dali.yueranfly.top/Article/details/gtumiemshe.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtioaghhhv.html

Ruby: arr.include?(x)
来源：http://dali.yueranfly.top/Article/details/gtmjdzuypt.html

C#:   list.Contains(x)
来源：http://dali.hnxiangtu.top/Article/details/gtecervxtu.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zdqjudy.top/Article/details/gteldpdmse.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hysaishi.cn/Article/details/gtljmrafxx.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.chenzaomai.com/Article/details/gtcytvhlho.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.dianchejie.cn/Article/details/gtzqxopkey.html

TS:   [...arr];
来源：http://dali.shuidangran.top/Article/details/gtfdyykeeg.html

Java: new ArrayList<>(list);
来源：http://dali.nanxinkj.top/Article/details/gtnblcctqc.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwendzeih.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yueranfly.top/Article/details/gtlexbxurm.html

C#:   new List<int>(list);
来源：http://dali.hnxiangtu.top/Article/details/gtyhlgqzue.html

[D23] reduce 累积计算
来源：http://dali.chenjidiqi.icu/Article/details/gtzdiagoug.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.kuanghao11.cn/Article/details/gtrjvhayuz.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.xuetiantiany.cn/Article/details/gtxpvrflzy.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gtjaphxqaa.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.daxiang520.top/Article/details/gtuddegutf.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.ivvv.top/Article/details/gtxdeibhgb.html

Go:   // 手写循环
来源：http://dali.bjfxy.top/Article/details/gtydizkryj.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.ppjwa.cn/Article/details/gtgmqaelte.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.dianchejie.cn/Article/details/gtmadqkzjj.html

[D24] 字典 / Map 基本操作
来源：http://dali.jqgufenzy.top/Article/details/gtwhfrtgjo.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.ybcxt.top/Article/details/gtuaqroxcn.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yj20258888.top/Article/details/gtvgwwrrpc.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yj20258.top/Article/details/gtmhdcukzf.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.nanxuanxn.top/Article/details/gtppkyxoru.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.pycfn.com/Article/details/gtcdbnhmre.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.ydzc1.top/Article/details/gtukhhwtnm.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.cashguo.top/Article/details/gtkvtyikfz.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdnbatywr.html

[D25] Set 集合去重与交并差
来源：http://dali.yongpay.top/Article/details/gtayefydtt.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.haohaochexian.top/Article/details/gtqllhsfcj.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttgcoifgh.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhengqikj.top/Article/details/gtttvlsegm.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.sxryk.cn/Article/details/gtdhzrrrup.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yvedp.cn/Article/details/gtvkqumszx.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.quarkkingdee.top/Article/details/gtflidcwnx.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.ehwqpu.com/Article/details/gtzdjslwyr.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtwauhgpzm.html

[D26] 数组转字符串
来源：http://dali.jiagoushi.top/Article/details/gtuodkyjtd.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yj20258888.top/Article/details/gtmlyhnwri.html

PHP:  implode(", ", $arr);
来源：http://dali.gaohongyu789.top/Article/details/gtcpbfjvtq.html

JS:   arr.join(", ")
来源：http://dali.316326.xyz/Article/details/gtkineepls.html

TS:   arr.join(", ")
来源：http://dali.snrcjt.cn/Article/details/gtncrisnif.html

Java: String.join(", ", list)
来源：http://dali.zhengqikj.top/Article/details/gtjctoobvj.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xinyue.icu/Article/details/gtkwoynady.html

Ruby: arr.join(", ")
来源：http://dali.aizwys.cn/Article/details/gtghwjglxy.html

C#:   string.Join(", ", list)
来源：http://dali.yj20258.top/Article/details/gtyxwheksy.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtqskclyrv.html

E. 字符串处理
来源：http://dali.ybcxt.top/Article/details/gtqezljmkc.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtkkvtzsmz.html

[E01] 拼接字符串
来源：http://dali.wangdashe.top/Article/details/gtckalusov.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.nanxinkj.top/Article/details/gtdnbzutio.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jlsjyb.cn/Article/details/gtrkmubrlv.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xinyue.icu/Article/details/gtgnwnsfbx.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jqgufenzy.top/Article/details/gttltmdxvv.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.feifeiyinyue.top/Article/details/gtolmjtdpe.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.xinyue.icu/Article/details/gtwpmnovxv.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yanxiufei.cn/Article/details/gtzanmjfqs.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jiagoushi.top/Article/details/gtgsrnucbo.html

[E02] 重复字符串
来源：http://dali.gotoacloud.top/Article/details/gtvdnqbgwj.html

Py:   "ab" * 3
来源：http://dali.shuidangran.top/Article/details/gtdapkvjet.html

PHP:  str_repeat("ab", 3);
来源：http://dali.sxryk.cn/Article/details/gtfdnlgufq.html

JS:   "ab".repeat(3)
来源：http://dali.ehwqpu.com/Article/details/gtgfgsxguc.html

TS:   "ab".repeat(3)
来源：http://dali.yj20258888.top/Article/details/gtacklhxpt.html

Java: "ab".repeat(3)
来源：http://dali.yj20258.top/Article/details/gtpiobjuya.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gthlaojjkl.html

Ruby: "ab" * 3
来源：http://dali.zhiwuduotai.top/Article/details/gtxjkhjjkn.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhengqikj.top/Article/details/gtnzzfjdeq.html

[E03] 截取子串
来源：http://dali.gaohongyu789.top/Article/details/gticheanjs.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.guannengcc.top/Article/details/gthwnvxjih.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xziqi.cn/Article/details/gtwcbmlcvd.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.kuanghao11.cn/Article/details/gtfvbmtyyv.html

TS:   s.slice(1, 4)
来源：http://dali.cucudq.cn/Article/details/gtowpsujap.html

Java: s.substring(1, 4)
来源：http://dali.jinghuilouyu.cn/Article/details/gtpevrqflo.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.xziqi.cn/Article/details/gtqjagqoit.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.hfpthk.cn/Article/details/gtoswllwax.html

C#:   s.Substring(1, 3)
来源：http://dali.ivvv.top/Article/details/gtblonvogr.html

[E04] 查找子串位置
来源：http://dali.snrcjt.cn/Article/details/gtgkpjtpsp.html

Py:   s.find("x");  s.index("x")
来源：http://dali.guowangkeji.top/Article/details/gtlovkiyck.html

PHP:  strpos($s, "x");
来源：http://dali.iojbl.cn/Article/details/gtoaffrinm.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.ehwqpu.com/Article/details/gtuxylkdgv.html

TS:   s.indexOf("x")
来源：http://dali.sxryk.cn/Article/details/gtqyjmcetr.html

Java: s.indexOf("x")
来源：http://dali.gogol.net.cn/Article/details/gthpykuovg.html

Go:   strings.Index(s, "x")
来源：http://dali.ehwqpu.com/Article/details/gtolsdskdb.html

Ruby: s.index("x")
来源：http://dali.hnxiangtu.top/Article/details/gtzhbslwzu.html

C#:   s.IndexOf("x")
来源：http://dali.shangyingyoupin.top/Article/details/gtnljfoniv.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yueranfly.top/Article/details/gtyzngnrnp.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gtufvbvngd.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.cdnleiting.top/Article/details/gtqcehvpjc.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cqqwz.cn/Article/details/gtcpxlsbjp.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yuanzhike.top/Article/details/gtwjtuomlz.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.tianlin.xyz/Article/details/gtuvdipjyk.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhixingplan.top/Article/details/gtevxjgchj.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.xziqi.cn/Article/details/gtlkbhztat.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.gotoacloud.top/Article/details/gtpwslooop.html

[E06] 替换子串
来源：http://dali.svipenyu.cn/Article/details/gtedncfqnv.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.ehwqpu.com/Article/details/gtxedfotmi.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.gogol.net.cn/Article/details/gtrnszccya.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.aizwys.cn/Article/details/gtflkxhytq.html

TS:   s.replaceAll("a", "b")
来源：http://dali.hnxiangtu.top/Article/details/gtfwypvmto.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.chenzaomai.com/Article/details/gttuksoqzr.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.sysykeji.top/Article/details/gtspxnukvl.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jqgufenzy.top/Article/details/gtftrwxtel.html

C#:   s.Replace("a", "b")
来源：http://dali.sysykeji.top/Article/details/gtmiilfoai.html

[E07] 按分隔符拆分
来源：http://dali.zhaomingkeji.xyz/Article/details/gtticsxizm.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.cqqwz.cn/Article/details/gtczqftmcr.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.wangdashe.top/Article/details/gteujrqeqy.html


<!-- 参考信息 -->