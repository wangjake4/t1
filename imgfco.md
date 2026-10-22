代发 wailian999

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gtzftlfihg.html

[H04] 自定义异常类型
来源：http://dali.shanyushiyangtech.top/Article/details/gterkcbbgb.html

Py:   class MyError(Exception): pass
来源：http://dali.guannengcc.top/Article/details/gttieeyfvw.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yueranfly.top/Article/details/gttprttony.html

JS:   class MyError extends Error {}
来源：http://dali.zycfv.cn/Article/details/gteoxhkkgg.html

TS:   class MyError extends Error {}
来源：http://dali.snrcjt.cn/Article/details/gtqmvomrsj.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gtygfiwcoo.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yuanzhike.top/Article/details/gtvdvljykf.html

Ruby: class MyError < StandardError; end
来源：http://dali.havefunace.top/Article/details/gtizqviipp.html

C#:   class MyException : Exception {}
来源：http://dali.jlsjyb.cn/Article/details/gtsewounsd.html

[H05] 捕获特定类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnxcfkuao.html

Py:   except ValueError as e:
来源：http://dali.hammf.cn/Article/details/gtljrhkghh.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.feifeiyinyue.top/Article/details/gtwcyrjmyl.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.havefunace.top/Article/details/gtppofollv.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.316326.xyz/Article/details/gtuinblyfm.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtgajwbisf.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.gogol.net.cn/Article/details/gtggyedyak.html

Ruby: rescue ArgumentError => e
来源：http://dali.gogol.net.cn/Article/details/gttjemmqdy.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ppjwa.cn/Article/details/gtvmrctcms.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yuanzhike.top/Article/details/gtxtgrzgpx.html

Py:   value = d.get("k") or default
来源：http://dali.yuanzhike.top/Article/details/gtksyypcpq.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.mhx1999.top/Article/details/gtgwgalcxj.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.9152youxi.cn/Article/details/gtalftkaum.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.sysykeji.top/Article/details/gtamdaqrns.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jqgfzy.top/Article/details/gtjfuadmlo.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.shuidangran.top/Article/details/gtshvvfcsw.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtldqsmynh.html

C#:   obj?.A?.B ?? default
来源：http://dali.hysaishi.cn/Article/details/gtieadcabm.html

[H07] 断言
来源：http://dali.9152youxi.cn/Article/details/gthtvaxnhd.html

Py:   assert x > 0, "必须为正"
来源：http://dali.sysykeji.top/Article/details/gtrpyyfdny.html

PHP:  assert($x > 0);
来源：http://dali.cucudq.cn/Article/details/gtbnvwafxi.html

JS:   console.assert(x > 0);
来源：http://dali.zhiwuduotai.top/Article/details/gtizyttpzx.html

TS:   console.assert(x > 0);
来源：http://dali.cucudq.cn/Article/details/gtnnhpdgus.html

Java: assert x > 0 : "必须为正";
来源：http://dali.haohaochexian.top/Article/details/gtkvwebtnc.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.pycfn.com/Article/details/gtvlqergqm.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.pengpengdd.cyou/Article/details/gtcglchvmm.html

C#:   Debug.Assert(x > 0);
来源：http://dali.guowangkeji.top/Article/details/gtleemtfcb.html

[H08] 获取错误信息与堆栈
来源：http://dali.kuanghao11.cn/Article/details/gtgzqvgaxs.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.9152youxi.cn/Article/details/gtrmxsydij.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yuanzhike.top/Article/details/gtonvpzscn.html

JS:   e.message;  e.stack
来源：http://dali.jqgfzy.top/Article/details/gtjzykcnfy.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.xziqi.cn/Article/details/gtwiejlfpo.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xuetiantiany.cn/Article/details/gtkksitfej.html

Go:   err.Error()
来源：http://dali.zhoulong.xyz/Article/details/gtilfkiouw.html

Ruby: e.message;  e.backtrace
来源：http://dali.ydzc1.top/Article/details/gtntgjkxml.html

C#:   e.Message;  e.StackTrace
来源：http://dali.sysykeji.top/Article/details/gtghnyfgnf.html

[H09] 带错误码的异常
来源：http://dali.sufxvd.cn/Article/details/gtkrocwhpm.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.kuanghao11.cn/Article/details/gtywvvqzas.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.chenzaomai.com/Article/details/gtbbyuaqlu.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.cashguo.top/Article/details/gtmfnfdted.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.bjfxy.top/Article/details/gtyryxemae.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.nanxinkj.top/Article/details/gtjtjjqolt.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.sweek.top/Article/details/gtovdtyauu.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.316326.xyz/Article/details/gtzagidugs.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ivvv.top/Article/details/gtummoucwk.html

[H10] 资源自动释放
来源：http://dali.xziqi.cn/Article/details/gtwvvjerhx.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zycfv.cn/Article/details/gtrthnurhb.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.nanxinkj.top/Article/details/gteopkncsg.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shanyushiyangtech.top/Article/details/gtsiqvkjnd.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xuetiantiany.cn/Article/details/gtyllddbsh.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.haohaochexian.top/Article/details/gthsjsnxey.html

Go:   defer f.Close()
来源：http://dali.tianlin.xyz/Article/details/gtexdycfqs.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xuanzx.com/Article/details/gtqtnevetp.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gtwdkdinuv.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gthirzxkdj.html

I. 正则表达式
来源：http://dali.yongpay.top/Article/details/gtkzkscrss.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtixnpovzc.html

[I01] 判断是否匹配
来源：http://dali.redwolf501.top/Article/details/gtllhmvbee.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.tianlin.xyz/Article/details/gtzfmlxlqn.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.wangdashe.top/Article/details/gtirimmrdu.html

JS:   /\d+/.test(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtwcvvjkrw.html

TS:   /\d+/.test(s)
来源：http://dali.jianghu66.top/Article/details/gtstdvywvt.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yj202588.top/Article/details/gtqkkihjae.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.bjfxy.top/Article/details/gtdtpxtonw.html

Ruby: s.match?(/\d+/)
来源：http://dali.nanxinkj.top/Article/details/gtdmertziy.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.snrcjt.cn/Article/details/gttcctdfsc.html

[I02] 提取所有匹配
来源：http://dali.zhixingplan.top/Article/details/gtxcxahabe.html

Py:   re.findall(r"\d+", s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnatmznss.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.quarkkingdee.top/Article/details/gtyzukzbau.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.0kj1m.cn/Article/details/gtvplhuzde.html

TS:   s.match(/\d+/g)
来源：http://dali.pycfn.com/Article/details/gtokhrcnup.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.fzhhl.top/Article/details/gtzanictcg.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yj20258.top/Article/details/gtcahtomzo.html

Ruby: s.scan(/\d+/)
来源：http://dali.smart0.xyz/Article/details/gthwcjbmvw.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.sxryk.cn/Article/details/gtxgafqgqq.html

[I03] 提取捕获分组
来源：http://dali.guannengcc.top/Article/details/gtycsppuxu.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.nwbrower.top/Article/details/gtzlrlayaz.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jianghu66.top/Article/details/gtybzdyjrh.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jinqigfzy.top/Article/details/gtvdiwdsdw.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhengqikj.top/Article/details/gtvgrxvpsc.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.feifeiyinyue.top/Article/details/gtuzjgbmgn.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbqvgwysh.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jqgfzy.top/Article/details/gtxoccmntk.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.birdmap.top/Article/details/gtifxrsgtm.html

[I04] 正则替换
来源：http://dali.yuanzhike.top/Article/details/gtdjcdiuot.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jinqigufen.top/Article/details/gtoyoxlpab.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gthvslqybs.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yuxming.cn/Article/details/gtarwsmpij.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.cheryme.top/Article/details/gtbsptzkai.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yanxiufei.cn/Article/details/gtrrpxngha.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.xylfe.cn/Article/details/gtwefyakqc.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.quarkkingdee.top/Article/details/gtvuwxgcjy.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.daxiang520.top/Article/details/gtweufardb.html

[I05] 按正则拆分
来源：http://dali.sweek.top/Article/details/gtnbmugydc.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yvedp.cn/Article/details/gtfktdxxfz.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.kuanghao11.cn/Article/details/gtjkdagvfg.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhoulong.xyz/Article/details/gtpwxbflbk.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.birdmap.top/Article/details/gtqgixuvmg.html

Java: s.split("\\s*,\\s*")
来源：http://dali.sufxvd.cn/Article/details/gthjendnrr.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jianghu66.top/Article/details/gthmdigcil.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hongshengwenyu.top/Article/details/gtgexzpekk.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.316326.xyz/Article/details/gtbsaqzebu.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.dashuyun.cn/Article/details/gtnqlehzuc.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.cucudq.cn/Article/details/gtbeggginf.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.guannengcc.top/Article/details/gtxwbmuzcy.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinqigfzy.top/Article/details/gtntodzmfs.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhixingplan.top/Article/details/gtpqkajaej.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.mhx1999.top/Article/details/gtmnyykope.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zdqjudy.top/Article/details/gtpescisfs.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.aibaodan.cn/Article/details/gtdklwnfyg.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.sysykeji.top/Article/details/gtknsoxczj.html

[I07] 忽略大小写与多行模式
来源：http://dali.meibo888.top/Article/details/gtalevzcbl.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.cucudq.cn/Article/details/gtheerarmz.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yuxming.cn/Article/details/gtpbgyyvfp.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yongpay.top/Article/details/gtjirwtgds.html

TS:   /error/gim
来源：http://dali.ehwqpu.com/Article/details/gtwkdagavl.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.xuetiantiany.cn/Article/details/gtjvrxkahr.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.mhx1999.top/Article/details/gtwbsqlytq.html

Ruby: s.scan(/error/i)
来源：http://dali.0kj1m.cn/Article/details/gttrbaevxs.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jinqigufen.top/Article/details/gtgrlzibnq.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.nwbrower.top/Article/details/gtdjfcfdxt.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhiwuduotai.top/Article/details/gtqfeitgci.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsprvvirs.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gogol.net.cn/Article/details/gtzfjeyohu.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxftuyqrh.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hnqzz.top/Article/details/gttdcomste.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yueranfly.top/Article/details/gtrhsejibh.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yanxiufei.cn/Article/details/gtusdlxwvb.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yueranfly.top/Article/details/gtapeqvvoi.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtnhbxdire.html

J. 日期与时间
来源：http://dali.yangfankeji.com/Article/details/gtpkqbhhxm.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtovmtiolk.html

[J01] 获取当前时间
来源：http://dali.yj202588.top/Article/details/gtkecnpqwv.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ppjwa.cn/Article/details/gtavswvsyh.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjmnzjimo.html

JS:   new Date();  Date.now()
来源：http://dali.zycfv.cn/Article/details/gthioitshl.html

TS:   new Date();  Date.now()
来源：http://dali.guannengcc.top/Article/details/gtxgcxcsqp.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.xylfe.cn/Article/details/gtnvzldbci.html

Go:   time.Now()
来源：http://dali.meibo888.top/Article/details/gtbjwfgnaj.html

Ruby: Time.now
来源：http://dali.bjfxy.top/Article/details/gtijnxilta.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yonumen.top/Article/details/gtkwyxbgzu.html

[J02] 格式化输出
来源：http://dali.xziqi.cn/Article/details/gtlzljpvqx.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.pycfn.com/Article/details/gtzcciesfb.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhixingplan.top/Article/details/gtqraqqigt.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.shangyingyoupin.top/Article/details/gtndxqsdun.html

TS:   d.toISOString()
来源：http://dali.shzxlz.cn/Article/details/gtkkajfanc.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.cheryme.top/Article/details/gtvegnltil.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jiagoushi.top/Article/details/gtebelnigx.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.wangdashe.top/Article/details/gtjfsnhctj.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jqgfzy.top/Article/details/gtexypmrst.html

[J03] 字符串解析为日期
来源：http://dali.jqgfzy.top/Article/details/gttmrxgcad.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jqgfzy.top/Article/details/gtektxhqsk.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.cashguo.top/Article/details/gtjbmcwmkv.html

JS:   new Date("2024-01-02")
来源：http://dali.xuanzx.com/Article/details/gtyzgtwyiv.html

TS:   new Date("2024-01-02")
来源：http://dali.jinghuilouyu.cn/Article/details/gtikhtvifn.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.sxryk.cn/Article/details/gtvqzerrim.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhongyouzk.top/Article/details/gtzhjjaxee.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yangfankeji.com/Article/details/gtexyfxlwi.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.nanxinkj.top/Article/details/gtdtqquksv.html

[J04] 时间戳与日期互转
来源：http://dali.snrcjt.cn/Article/details/gtygtixucs.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.cashguo.top/Article/details/gtkjdugjiy.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.ydzc1.top/Article/details/gtgioglnho.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hysaishi.cn/Article/details/gtxlaqluky.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.snrcjt.cn/Article/details/gtmksokqdt.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.meibo888.top/Article/details/gtxyushanm.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.sufxvd.cn/Article/details/gtxyrucxeq.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hammf.cn/Article/details/gtdiuapeit.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jyoumei.cn/Article/details/gtzvxjqvfk.html

[J05] 时间加减（加 7 天）
来源：http://dali.snrcjt.cn/Article/details/gtojacrfuq.html

Py:   now + timedelta(days=7)
来源：http://dali.hnqzz.top/Article/details/gtarwnhtft.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jianghu66.top/Article/details/gtytuklgrg.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hammf.cn/Article/details/gtdtegdanp.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yvedp.cn/Article/details/gtrwwqppho.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.snrcjt.cn/Article/details/gtoshgofoa.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.sufxvd.cn/Article/details/gticzqjvmr.html

Ruby: Time.now + 7 * 86400
来源：http://dali.andypj.xyz/Article/details/gtwfcqocfs.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.nanxuanxn.top/Article/details/gtgcuuxirv.html

[J06] 计算两时间之差
来源：http://dali.yj202588.top/Article/details/gtlmrvsnwj.html

Py:   (end - start).total_seconds()
来源：http://dali.daxiang520.top/Article/details/gtqcwvurhw.html

PHP:  $end->diff($start)->days;
来源：http://dali.0kj1m.cn/Article/details/gterewwpmb.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yonumen.top/Article/details/gtpnkbyuie.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.snrcjt.cn/Article/details/gtiuskygbw.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.gotoacloud.top/Article/details/gtazhzktye.html

Go:   end.Sub(start).Hours()
来源：http://dali.redwolf501.top/Article/details/gtscftathi.html

Ruby: end - start                 # 返回秒数
来源：http://dali.pengpengdd.cyou/Article/details/gtsqbnxtyy.html

C#:   (end - start).TotalSeconds
来源：http://dali.daxiang520.top/Article/details/gtvxzajhhd.html

[J07] 比较两个日期
来源：http://dali.xziqi.cn/Article/details/gtcrrgqaiz.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhiwuduotai.top/Article/details/gtidxbaonc.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.haohaochexian.top/Article/details/gttqxajdji.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.c1oappe.top/Article/details/gtnwcjorzy.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.hywenlv.cn/Article/details/gtpbrvrfnm.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xinyue.icu/Article/details/gtpuaqqkdu.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jlsjyb.cn/Article/details/gtpdfvgjju.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.chenlongwang.top/Article/details/gthhigfgct.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.andypj.xyz/Article/details/gtuejrpyaq.html

[J08] 提取年月日与星期
来源：http://dali.ppjwa.cn/Article/details/gtwjekskab.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhongyouzk.top/Article/details/gtshyeqnrc.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.xuanzx.com/Article/details/gtjrqfpavw.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hysaishi.cn/Article/details/gtnwonvlnf.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.0kj1m.cn/Article/details/gtqoccnxxz.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.cdnleiting.top/Article/details/gtvsdxajuq.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjqchpgay.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zycfv.cn/Article/details/gtfmelmijy.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.gogol.net.cn/Article/details/gtgbmtkjrc.html

[J09] 时区处理
来源：http://dali.cucudq.cn/Article/details/gthxfecdgm.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yonumen.top/Article/details/gtjteoxihj.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.wangshuangyany.cn/Article/details/gtqlktqyml.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hysaishi.cn/Article/details/gtfgaywfqz.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hywenlv.cn/Article/details/gtgobzwobu.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.birdmap.top/Article/details/gtwebjhzoc.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.meibo888.top/Article/details/gtuzvqmeky.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.sysykeji.top/Article/details/gtywtvsmpa.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.xuanzx.com/Article/details/gtmaurxkmc.html

[J10] 取今天 / 本月第一天
来源：http://dali.birdmap.top/Article/details/gtfdubhzti.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ivvv.top/Article/details/gtjfblqjgj.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.sysykeji.top/Article/details/gtdmwvbusl.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hywenlv.cn/Article/details/gtkpqkmuqa.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zdqjudy.top/Article/details/gtspburtfn.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.smart0.xyz/Article/details/gtlaxcnhmi.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xuetiantiany.cn/Article/details/gtzvscmscv.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhixingplan.top/Article/details/gtogcknogw.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.cheryme.top/Article/details/gtovcgmwrz.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtaltugkhc.html

K. JSON 与序列化
来源：http://dali.yanxiufei.cn/Article/details/gtjrwzozcq.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtkaacoxqw.html

[K01] 对象转 JSON 字符串
来源：http://dali.yj20258888.top/Article/details/gtvxqbgeyw.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.birdmap.top/Article/details/gtmxsddkfb.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.shangyingyoupin.top/Article/details/gtjxuospyn.html

JS:   JSON.stringify(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtakjtillv.html

TS:   JSON.stringify(obj)
来源：http://dali.cdnleiting.top/Article/details/gtvwttocff.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yanxiufei.cn/Article/details/gtxwobywur.html

Go:   json.Marshal(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtndrtpjnm.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.shuidangran.top/Article/details/gtcnfzujmh.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.pycfn.com/Article/details/gturjzcdnj.html

[K02] JSON 字符串转对象
来源：http://dali.jinqigufen.top/Article/details/gtiftgzblz.html

Py:   json.loads(s)
来源：http://dali.tianlin.xyz/Article/details/gtjanpekpy.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jqgfzy.top/Article/details/gtotdqzaxx.html

JS:   JSON.parse(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxspyckeh.html

TS:   JSON.parse(s)
来源：http://dali.pycfn.com/Article/details/gtsaixspmy.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.svipenyu.cn/Article/details/gtzgknyqbs.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.guowangkeji.top/Article/details/gtxwqklzjo.html

Ruby: JSON.parse(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtflyeruiw.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.redwolf501.top/Article/details/gtcohtunoc.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.cheryme.top/Article/details/gtezzkqglv.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhiwuduotai.top/Article/details/gtskjnmtkh.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jqgfzy.top/Article/details/gtmmrcflxj.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.fzhhl.top/Article/details/gtxuhulbhi.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.shangyingyoupin.top/Article/details/gtzxaaeubt.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jiagoushi.top/Article/details/gtwcxzjdmf.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.daxiang520.top/Article/details/gtzbczevhx.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.pycfn.com/Article/details/gtudmbbems.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.0kj1m.cn/Article/details/gtmiyjnjzd.html

[K04] 读取 JSON 文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkecvhqqx.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.cdnleiting.top/Article/details/gtwvjdmmhr.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.wangshuangyany.cn/Article/details/gtoevhswif.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sysykeji.top/Article/details/gtcokukuwq.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.fengsongda.top/Article/details/gtnwuifnmn.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.dashuyun.cn/Article/details/gtwphjiyca.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zdqjudy.top/Article/details/gtkfidfwoj.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.haohaochexian.top/Article/details/gtgdfphdax.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jlsjyb.cn/Article/details/gtcuxwcybb.html

[K05] 深拷贝对象
来源：http://dali.shangyingyoupin.top/Article/details/gthxaxqwgx.html

Py:   copy.deepcopy(obj)
来源：http://dali.0kj1m.cn/Article/details/gtpygbdfey.html

PHP:  unserialize(serialize($obj));
来源：http://dali.nanxuanxn.top/Article/details/gtzodefdkm.html

JS:   structuredClone(obj)
来源：http://dali.xinyue.icu/Article/details/gtkcitgktb.html

TS:   structuredClone(obj)
来源：http://dali.chenlongwang.top/Article/details/gtdatvfigf.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.tianlin.xyz/Article/details/gtmexihgkg.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.feifeiyinyue.top/Article/details/gthxveoevg.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yj20258.top/Article/details/gtiotnehna.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.dashuyun.cn/Article/details/gtglggryyy.html

[K06] 解析 URL 查询串
来源：http://dali.nwbrower.top/Article/details/gtuacaogbp.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hammf.cn/Article/details/gtprzvoavy.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.svipenyu.cn/Article/details/gtoxogmuar.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.vqdsnc.cn/Article/details/gtbluapymz.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gtksjezocm.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.shangyingyoupin.top/Article/details/gtgwjmynpm.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.guowangkeji.top/Article/details/gtyzwtwkdl.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yanxiufei.cn/Article/details/gtiamoaemp.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zdqjudy.top/Article/details/gtjilzjkam.html

[K07] 进制转换
来源：http://dali.yj20258.top/Article/details/gtqcwrnnjf.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.havefunace.top/Article/details/gtruuxklta.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.tianlin.xyz/Article/details/gtxxizwouc.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.hfpthk.cn/Article/details/gtunbcigee.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jqgufenzy.top/Article/details/gtybdaivxw.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ppjwa.cn/Article/details/gtvqhnfoxm.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhiwuduotai.top/Article/details/gtykddxefs.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.316326.xyz/Article/details/gtidmqagvs.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gtumrdctoh.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.havefunace.top/Article/details/gtgbionghe.html

Py:   pickle.dumps(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtznarsufz.html


<!-- 参考信息 -->