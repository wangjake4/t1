代发 wailian999

C#:   list.Insert(0, 0);
来源：http://dali.dashuyun.cn/Article/details/gt2tksvcdat.html

[D04] 删除元素
来源：http://dali.kuanghao11.cn/Article/details/gt2yjhnondt.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.bjfxy.top/Article/details/gt2xvltvbcm.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lcgsoajf.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.sxryk.cn/Article/details/gt2wcqszkcf.html

TS:   arr.splice(0, 1);
来源：http://dali.shzxlz.cn/Article/details/gt2gkqeaquo.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.pycfn.com/Article/details/gt2ftspsiey.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.hammf.cn/Article/details/gt2wdukajwj.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jiagoushi.top/Article/details/gt2bduegboj.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.gotoacloud.top/Article/details/gt2lvpqjkuw.html

[D05] 访问与修改元素
来源：http://dali.quarkkingdee.top/Article/details/gt2nqfwhaoz.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinqigfzy.top/Article/details/gt2zqhkdmms.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.tanke756.top/Article/details/gt2yzofvljd.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.daria6918.cn/Article/details/gt2fayanlgh.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yueranfly.top/Article/details/gt2ndlkwdgh.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yongpay.top/Article/details/gt2ximtzrok.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zzybnzwb.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.iojbl.cn/Article/details/gt2jawsnlpw.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jyoumei.cn/Article/details/gt2usbadldm.html

[D06] 数组长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zsfzdvsi.html

Py:   len(arr)
来源：http://dali.ivvv.top/Article/details/gt2ctnfadmx.html

PHP:  count($arr);
来源：http://dali.zycfv.cn/Article/details/gt2diiadnmt.html

JS:   arr.length
来源：http://dali.hywenlv.cn/Article/details/gt2oaeaefpo.html

TS:   arr.length
来源：http://dali.bjfxy.top/Article/details/gt2fqhuxwno.html

Java: list.size();
来源：http://dali.xziqi.cn/Article/details/gt2vsbxswwk.html

Go:   len(arr)
来源：http://dali.hnxiangtu.top/Article/details/gt2bjuxqsee.html

Ruby: arr.length; arr.size
来源：http://dali.sweek.top/Article/details/gt2eynjmgpr.html

C#:   list.Count;
来源：http://dali.ybcxt.top/Article/details/gt2fdnrqiuw.html

[D07] 切片 / 取子数组
来源：http://dali.cucudq.cn/Article/details/gt2dgiqrjfs.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.hfpthk.cn/Article/details/gt2ikrcunpy.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.gotoacloud.top/Article/details/gt2jmamsakq.html

JS:   arr.slice(1, 4);
来源：http://dali.haohaochexian.top/Article/details/gt2crlpyxqk.html

TS:   arr.slice(1, 4);
来源：http://dali.yuanzhike.top/Article/details/gt2urnsmkpt.html

Java: list.subList(1, 4);
来源：http://dali.ivvv.top/Article/details/gt2xymvzlkc.html

Go:   arr[1:4]
来源：http://dali.wangshuangyany.cn/Article/details/gt2labcvvef.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2npzlgexq.html

C#:   list.GetRange(1, 3);
来源：http://dali.ehwqpu.com/Article/details/gt2cnewgvhs.html

[D08] 合并两个数组
来源：http://dali.316326.xyz/Article/details/gt2laoqrrnu.html

Py:   a + b;  a.extend(b)
来源：http://dali.shangyingyoupin.top/Article/details/gt2eknkmgww.html

PHP:  array_merge($a, $b);
来源：http://dali.daria6918.cn/Article/details/gt2lnvvcekq.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.tianlin.xyz/Article/details/gt2xfkeunfg.html

TS:   [...a, ...b];
来源：http://dali.hnqzz.top/Article/details/gt2ensuinyh.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.sxryk.cn/Article/details/gt2cnyiqipi.html

Go:   append(a, b...)
来源：http://dali.chenlongwang.top/Article/details/gt2shlhheqc.html

Ruby: a + b;  a.concat(b)
来源：http://dali.chenzaomai.com/Article/details/gt2hxwnmzro.html

C#:   a.Concat(b).ToList()
来源：http://dali.yonumen.top/Article/details/gt2xsanwjtv.html

[D09] 排序（升序）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ngiqvuuz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.fengsongda.top/Article/details/gt2lbranwej.html

PHP:  sort($arr);
来源：http://dali.tian-w.cn/Article/details/gt2lbdwfqeg.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tmlpfgfa.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.0kj1m.cn/Article/details/gt2imiekjcz.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhoulong.xyz/Article/details/gt2leuzwqpj.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.haohaochexian.top/Article/details/gt2afmlclsb.html

Ruby: arr.sort
来源：http://dali.yj202588.top/Article/details/gt2lolabarz.html

C#:   list.Sort();
来源：http://dali.fengsongda.top/Article/details/gt2ncyenxok.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.9152youxi.cn/Article/details/gt2cqyytubw.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.tanke756.top/Article/details/gt2ztbxdkbe.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ppjwa.cn/Article/details/gt2buqolwkk.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ralcqsvu.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.quarkkingdee.top/Article/details/gt2zrfggrvv.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.hnxiangtu.top/Article/details/gt2krxgxsjn.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.pycfn.com/Article/details/gt2icmjnpjp.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.hnxiangtu.top/Article/details/gt2paecmbvo.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.sysykeji.top/Article/details/gt2noqjjehr.html

[D11] 反转数组
来源：http://dali.hnxiangtu.top/Article/details/gt2cciqzgba.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.gzhubu.top/Article/details/gt2pscmobtd.html

PHP:  array_reverse($arr);
来源：http://dali.9152youxi.cn/Article/details/gt2krdjjsad.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.iojbl.cn/Article/details/gt2jwuxhotb.html

TS:   [...arr].reverse();
来源：http://dali.chenlongwang.top/Article/details/gt2hrtdpybv.html

Java: Collections.reverse(list);
来源：http://dali.svipenyu.cn/Article/details/gt2nsofjtzg.html

Go:   slices.Reverse(arr)
来源：http://dali.ppjwa.cn/Article/details/gt2ocjqxlrc.html

Ruby: arr.reverse
来源：http://dali.chenlongwang.top/Article/details/gt2juwxlxlm.html

C#:   list.Reverse();
来源：http://dali.yuanzhike.top/Article/details/gt2diyeostd.html

[D12] 查找元素下标
来源：http://dali.aibaodan.cn/Article/details/gt2hrifnnto.html

Py:   arr.index(x);  x in arr
来源：http://dali.jianghu66.top/Article/details/gt2nmuqmqxh.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.nanxinkj.top/Article/details/gt2juqyatqu.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2unpwsubf.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yongpay.top/Article/details/gt2abeybnom.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.snrcjt.cn/Article/details/gt2bopmglib.html

Go:   slices.Index(arr, x)
来源：http://dali.sysykeji.top/Article/details/gt2dtpiwwxi.html

Ruby: arr.index(x)
来源：http://dali.jinqigufen.top/Article/details/gt2fpilgkyd.html

C#:   list.IndexOf(x);
来源：http://dali.xziqi.cn/Article/details/gt2mljmgxmm.html

[D13] 过滤（保留满足条件的）
来源：http://dali.nanxinkj.top/Article/details/gt2mdpwpfgd.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.havefunace.top/Article/details/gt2dwemrxgf.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.nanxuanxn.top/Article/details/gt2otzocjmz.html

JS:   arr.filter(x => x > 3)
来源：http://dali.sufxvd.cn/Article/details/gt2acldonki.html

TS:   arr.filter(x => x > 3)
来源：http://dali.hnqzz.top/Article/details/gt2nfrurfjh.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.hammf.cn/Article/details/gt2zjpycjfs.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.ppjwa.cn/Article/details/gt2xwcijrdd.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.aibaodan.cn/Article/details/gt2sbmcmgfu.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hfpthk.cn/Article/details/gt2lzmqzkvq.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yj202588.top/Article/details/gt2dstyqbyb.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jlsjyb.cn/Article/details/gt2xnzxhiaw.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2umydrpaf.html

JS:   arr.map(x => x * 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mndxwrro.html

TS:   arr.map(x => x * 2)
来源：http://dali.jqgufenzy.top/Article/details/gt2swcnigau.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.shangyingyoupin.top/Article/details/gt2xaugzrqd.html

Go:   // 手写循环
来源：http://dali.bjfxy.top/Article/details/gt2vzdybmyg.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.fengsongda.top/Article/details/gt2fkvfpwvw.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.shuidangran.top/Article/details/gt2augalcur.html

[D15] 去重
来源：http://dali.yuanzhike.top/Article/details/gt2aipmkjkq.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.pengpengdd.cyou/Article/details/gt2edkhtmzg.html

PHP:  array_unique($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fbmrhbxo.html

JS:   [...new Set(arr)]
来源：http://dali.316326.xyz/Article/details/gt2cymzejew.html

TS:   [...new Set(arr)]
来源：http://dali.snrcjt.cn/Article/details/gt2ztqgbztc.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.shzxlz.cn/Article/details/gt2qlzxghtg.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.wangdashe.top/Article/details/gt2sedhfnte.html

Ruby: arr.uniq
来源：http://dali.redwolf501.top/Article/details/gt2sigyyqli.html

C#:   list.Distinct().ToList()
来源：http://dali.yuanzhike.top/Article/details/gt2szyxhpau.html

[D16] 求和与平均值
来源：http://dali.guowangkeji.top/Article/details/gt2ofdemmzg.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhoulong.xyz/Article/details/gt2fiioeaku.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.andypj.xyz/Article/details/gt2cvaglfix.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yvedp.cn/Article/details/gt2sicgfpmw.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.haohaochexian.top/Article/details/gt2wtnkkotq.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.xuetiantiany.cn/Article/details/gt2pdorench.html

Go:   // 手写循环累加
来源：http://dali.tian-w.cn/Article/details/gt2tirxoghs.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhengqikj.top/Article/details/gt2dcmmqalx.html

C#:   list.Sum();  list.Average()
来源：http://dali.zycfv.cn/Article/details/gt2ptsdugvp.html

[D17] 最大值与最小值
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aexbshdz.html

Py:   max(arr);  min(arr)
来源：http://dali.yvedp.cn/Article/details/gt2fimrhumy.html

PHP:  max($arr);  min($arr);
来源：http://dali.gotoacloud.top/Article/details/gt2oshnbefl.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.xuetiantiany.cn/Article/details/gt2tfihhuhy.html

TS:   Math.max(...arr);
来源：http://dali.andypj.xyz/Article/details/gt2hhkcgoho.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.haohaochexian.top/Article/details/gt2mnghchpu.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gt2bfsutnwm.html

Ruby: arr.max;  arr.min
来源：http://dali.quarkkingdee.top/Article/details/gt2payycwll.html

C#:   list.Max();  list.Min()
来源：http://dali.shangyingyoupin.top/Article/details/gt2knmadijo.html

[D18] 扁平化嵌套数组
来源：http://dali.guowangkeji.top/Article/details/gt2exnhlxjb.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rwgqoijx.html

PHP:  array_merge(...$nested);
来源：http://dali.yuxming.cn/Article/details/gt2fzsmsoww.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.tanke756.top/Article/details/gt2mcscupag.html

TS:   nested.flat();
来源：http://dali.wangshuangyany.cn/Article/details/gt2eyadfnyp.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.mhx1999.top/Article/details/gt2vyaiusom.html

Go:   // 手写双层循环
来源：http://dali.zhiwuduotai.top/Article/details/gt2pxkzjfuf.html

Ruby: nested.flatten
来源：http://dali.iojbl.cn/Article/details/gt2jjxljkku.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yvedp.cn/Article/details/gt2hhfmrapc.html

[D19] 按字段分组
来源：http://dali.xinyue.icu/Article/details/gt2lobsribn.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yanxiufei.cn/Article/details/gt2oiwarmfs.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.aibaodan.cn/Article/details/gt2fmchuavm.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yj202588.top/Article/details/gt2cgepmlnl.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.gotoacloud.top/Article/details/gt2yerisszy.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.9152youxi.cn/Article/details/gt2scibasba.html

Go:   // 手写 map[string][]T
来源：http://dali.yj20258.top/Article/details/gt2jativwco.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.cucudq.cn/Article/details/gt2nchnrkhs.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.wangshuangyany.cn/Article/details/gt2rlinsdzq.html

[D20] 统计每个元素出现次数
来源：http://dali.pycfn.com/Article/details/gt2eaqhdesb.html

Py:   Counter(arr)
来源：http://dali.yanxiufei.cn/Article/details/gt2acmytdup.html

PHP:  array_count_values($arr);
来源：http://dali.daxiang520.top/Article/details/gt2gwhkxnxj.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.dashuyun.cn/Article/details/gt2sywustmz.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj202588.top/Article/details/gt2zpakhlrg.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.tian-w.cn/Article/details/gt2amhpdkqk.html

Go:   // 手写 map[T]int
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qatfluso.html

Ruby: arr.tally
来源：http://dali.zhiwuduotai.top/Article/details/gt2apackafw.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jyoumei.cn/Article/details/gt2usandzgr.html

[D21] 判断是否包含某元素
来源：http://dali.gotoacloud.top/Article/details/gt2ywpkxgay.html

Py:   x in arr
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xlebvntl.html

PHP:  in_array($x, $arr, true);
来源：http://dali.xziqi.cn/Article/details/gt2rrjpynvv.html

JS:   arr.includes(x)
来源：http://dali.bjfxy.top/Article/details/gt2digbzpuk.html

TS:   arr.includes(x)
来源：http://dali.jyoumei.cn/Article/details/gt2ogfassqj.html

Java: list.contains(x)
来源：http://dali.yj20258888.top/Article/details/gt2fstqiwew.html

Go:   slices.Contains(arr, x)
来源：http://dali.yonumen.top/Article/details/gt2vitmhhhg.html

Ruby: arr.include?(x)
来源：http://dali.nanxuanxn.top/Article/details/gt2hxdasgax.html

C#:   list.Contains(x)
来源：http://dali.yj20258888.top/Article/details/gt2hpmrmods.html

[D22] 复制数组（避免共享引用）
来源：http://dali.wangshuangyany.cn/Article/details/gt2ezhggejb.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yongpay.top/Article/details/gt2ezmpwjzq.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gofvxuyg.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jtvqaiso.html

TS:   [...arr];
来源：http://dali.zdqjudy.top/Article/details/gt2arifpete.html

Java: new ArrayList<>(list);
来源：http://dali.quarkkingdee.top/Article/details/gt2lhuhlnrk.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sbkwljfq.html

Ruby: arr.dup;  arr.clone
来源：http://dali.snrcjt.cn/Article/details/gt2buefaimn.html

C#:   new List<int>(list);
来源：http://dali.yongpay.top/Article/details/gt2bbrpwalh.html

[D23] reduce 累积计算
来源：http://dali.yj202588.top/Article/details/gt2jlkxkass.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sxapvqzz.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.cashguo.top/Article/details/gt2kmsbjduv.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.fengsongda.top/Article/details/gt2viuttmxl.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ehwqpu.com/Article/details/gt2cftasica.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.smart0.xyz/Article/details/gt2vlbsqqux.html

Go:   // 手写循环
来源：http://dali.sxryk.cn/Article/details/gt2llqnmtgu.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.aibaodan.cn/Article/details/gt2eropjnmr.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jnufnmdp.html

[D24] 字典 / Map 基本操作
来源：http://dali.yueranfly.top/Article/details/gt2fpswnhfu.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yj20258.top/Article/details/gt2vewggycf.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jianghu66.top/Article/details/gt2aphbokgz.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2caubjyuf.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.nanxinkj.top/Article/details/gt2nmcsvlcc.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.xuetiantiany.cn/Article/details/gt2buaeahyn.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.smart0.xyz/Article/details/gt2txicddfk.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.dianchejie.cn/Article/details/gt2dtyfrckh.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.kuanghao11.cn/Article/details/gt2pugkavwt.html

[D25] Set 集合去重与交并差
来源：http://dali.shzxlz.cn/Article/details/gt2cqzmttlt.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.aizwys.cn/Article/details/gt2hdgqaxmd.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.gaohongyu789.top/Article/details/gt2kcjmjiuq.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jinqigufen.top/Article/details/gt2uxllqyzk.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kpngtuhj.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.cdnleiting.top/Article/details/gt2tkhjtqem.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hywenlv.cn/Article/details/gt2ehrefvak.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhixingplan.top/Article/details/gt2ecmwjuxe.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kpacocyr.html

[D26] 数组转字符串
来源：http://dali.daria6918.cn/Article/details/gt2ipbfgmfr.html

Py:   ", ".join(map(str, arr))
来源：http://dali.chenzaomai.com/Article/details/gt2flxuvzrg.html

PHP:  implode(", ", $arr);
来源：http://dali.wangdashe.top/Article/details/gt2fjhivwqc.html

JS:   arr.join(", ")
来源：http://dali.yongpay.top/Article/details/gt2bwlyutse.html

TS:   arr.join(", ")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sdlkvfqf.html

Java: String.join(", ", list)
来源：http://dali.hfpthk.cn/Article/details/gt2qxcovpzq.html

Go:   strings.Join(strs, ", ")
来源：http://dali.chenlongwang.top/Article/details/gt2cocxihed.html

Ruby: arr.join(", ")
来源：http://dali.ydzc1.top/Article/details/gt2nldifjjp.html

C#:   string.Join(", ", list)
来源：http://dali.zycfv.cn/Article/details/gt2petexprt.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2bbiilxdl.html

E. 字符串处理
来源：http://dali.dashuyun.cn/Article/details/gt2lcgmbqzt.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2pdqobnmf.html

[E01] 拼接字符串
来源：http://dali.jinqigufen.top/Article/details/gt2uzxslrxn.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.chenjidiqi.icu/Article/details/gt2wltzaita.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.iojbl.cn/Article/details/gt2glfojcqi.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wuesumkw.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gogol.net.cn/Article/details/gt2cksbovvy.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yonumen.top/Article/details/gt2lxcnppwt.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yangfankeji.com/Article/details/gt2puaxfxcr.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yuanzhike.top/Article/details/gt2tkzadzsa.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.gaohongyu789.top/Article/details/gt2hblnjbqr.html

[E02] 重复字符串
来源：http://dali.meibo888.top/Article/details/gt2rmnpuwvp.html

Py:   "ab" * 3
来源：http://dali.zhoulong.xyz/Article/details/gt2pvygwgpf.html

PHP:  str_repeat("ab", 3);
来源：http://dali.tianlin.xyz/Article/details/gt2plbwbpji.html

JS:   "ab".repeat(3)
来源：http://dali.hongshengwenyu.top/Article/details/gt2kgiszjxj.html

TS:   "ab".repeat(3)
来源：http://dali.xuetiantiany.cn/Article/details/gt2zngjewgi.html

Java: "ab".repeat(3)
来源：http://dali.nwbrower.top/Article/details/gt2jxveqyqi.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.ehwqpu.com/Article/details/gt2mmckcwxl.html

Ruby: "ab" * 3
来源：http://dali.tianlin.xyz/Article/details/gt2uoyucksb.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.smart0.xyz/Article/details/gt2rgrowbug.html

[E03] 截取子串
来源：http://dali.yueranfly.top/Article/details/gt2uosuhtld.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.shzxlz.cn/Article/details/gt2mernuiuo.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yonumen.top/Article/details/gt2huhdqrub.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.aibaodan.cn/Article/details/gt2wvrijcdp.html

TS:   s.slice(1, 4)
来源：http://dali.nanxuanxn.top/Article/details/gt2owmowkig.html

Java: s.substring(1, 4)
来源：http://dali.ehwqpu.com/Article/details/gt2zkcuguxf.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.snrcjt.cn/Article/details/gt2nwnhwerx.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jlsjyb.cn/Article/details/gt2xxzvkbic.html

C#:   s.Substring(1, 3)
来源：http://dali.zhengqikj.top/Article/details/gt2dvryvvls.html

[E04] 查找子串位置
来源：http://dali.chenjidiqi.icu/Article/details/gt2bgtltvdl.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ellmfduc.html

PHP:  strpos($s, "x");
来源：http://dali.mhx1999.top/Article/details/gt2iugljcvm.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.gaohongyu789.top/Article/details/gt2kcmpqyhm.html

TS:   s.indexOf("x")
来源：http://dali.aibaodan.cn/Article/details/gt2nxokjxsc.html

Java: s.indexOf("x")
来源：http://dali.haohaochexian.top/Article/details/gt2jtoirtnn.html

Go:   strings.Index(s, "x")
来源：http://dali.0kj1m.cn/Article/details/gt2ujvtjtwr.html

Ruby: s.index("x")
来源：http://dali.zhongyouzk.top/Article/details/gt2hazjcwqm.html

C#:   s.IndexOf("x")
来源：http://dali.hammf.cn/Article/details/gt2paysltki.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.ppjwa.cn/Article/details/gt2foawsisp.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.cashguo.top/Article/details/gt2gtsljdqy.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.cucudq.cn/Article/details/gt2jwbiyxsy.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ybcxt.top/Article/details/gt2grdiyzzb.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.mhx1999.top/Article/details/gt2ficbntxa.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.smart0.xyz/Article/details/gt2dntdeydk.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yuxming.cn/Article/details/gt2uekjfbah.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.fzhhl.top/Article/details/gt2tnamznyr.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.hongshengwenyu.top/Article/details/gt2iwenjjzy.html

[E06] 替换子串
来源：http://dali.yonumen.top/Article/details/gt2uodjxpjh.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhengqikj.top/Article/details/gt2yapvepkk.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.andypj.xyz/Article/details/gt2harxkoel.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vesfrgox.html

TS:   s.replaceAll("a", "b")
来源：http://dali.daxiang520.top/Article/details/gt2zxvytbrd.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.wangdashe.top/Article/details/gt2ivfgcwma.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.cdnleiting.top/Article/details/gt2jejfkvon.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.svipenyu.cn/Article/details/gt2qgjswtsj.html

C#:   s.Replace("a", "b")
来源：http://dali.cqqwz.cn/Article/details/gt2fhgltlel.html

[E07] 按分隔符拆分
来源：http://dali.9152youxi.cn/Article/details/gt2tgapnkvb.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.cucudq.cn/Article/details/gt2qfadshov.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.xylfe.cn/Article/details/gt2xwykxrvx.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yueranfly.top/Article/details/gt2iczptqnk.html

TS:   s.split(",")
来源：http://dali.daria6918.cn/Article/details/gt2iuzuumkz.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.fengsongda.top/Article/details/gt2knhddnwl.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.svipenyu.cn/Article/details/gt2rmycrgye.html

Ruby: s.split(",");  s.split
来源：http://dali.havefunace.top/Article/details/gt2sxhimfta.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yj20258888.top/Article/details/gt2wjtupmsc.html

[E08] 数组按分隔符合并
来源：http://dali.yongpay.top/Article/details/gt2hgcmmhqj.html

Py:   ",".join(items)
来源：http://dali.xinyue.icu/Article/details/gt2wanwjalu.html

PHP:  implode(",", $items);
来源：http://dali.yangfankeji.com/Article/details/gt2kkjcisql.html

JS:   items.join(",")
来源：http://dali.sxryk.cn/Article/details/gt2anjimnfj.html

TS:   items.join(",")
来源：http://dali.gaohongyu789.top/Article/details/gt2sptunbvq.html

Java: String.join(",", items)
来源：http://dali.xziqi.cn/Article/details/gt2umdpxqgq.html

Go:   strings.Join(items, ",")
来源：http://dali.nwbrower.top/Article/details/gt2ocuwjiem.html

Ruby: items.join(",")
来源：http://dali.xuanzx.com/Article/details/gt2cwypdruq.html

C#:   string.Join(",", items)
来源：http://dali.yanxiufei.cn/Article/details/gt2piaoofaq.html

[E09] 去除所有空白字符
来源：http://dali.nanxinkj.top/Article/details/gt2brgywqdv.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.xuanzx.com/Article/details/gt2htelibdc.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cprbpmym.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.xuanzx.com/Article/details/gt2uguabwok.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hywenlv.cn/Article/details/gt2zculjffc.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.andypj.xyz/Article/details/gt2zeurmrpz.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.pengpengdd.cyou/Article/details/gt2hcmugxkc.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhengqikj.top/Article/details/gt2dmoilumq.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yangfankeji.com/Article/details/gt2vgdsgjjl.html

[E10] 左侧补零 / 定长填充
来源：http://dali.fengsongda.top/Article/details/gt2zxvuznci.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.svipenyu.cn/Article/details/gt2puclsebe.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jiagoushi.top/Article/details/gt2gfkrggmv.html

JS:   "7".padStart(3, "0")
来源：http://dali.haohaochexian.top/Article/details/gt2kgoetxud.html

TS:   "7".padStart(3, "0")
来源：http://dali.yvedp.cn/Article/details/gt2sehzqvkw.html

Java: String.format("%03d", 7)
来源：http://dali.cucudq.cn/Article/details/gt2okqscphx.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.haohaochexian.top/Article/details/gt2rqyzgufv.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jqgufenzy.top/Article/details/gt2unigdjff.html


<!-- 参考信息 -->