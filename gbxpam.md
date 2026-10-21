代发 wailian999

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gttbvqrrmd.html

[H04] 自定义异常类型
来源：http://dali.aizwys.cn/Article/details/gtabnbuilw.html

Py:   class MyError(Exception): pass
来源：http://dali.kuanghao11.cn/Article/details/gtaslupyhk.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtozyjdmhd.html

JS:   class MyError extends Error {}
来源：http://dali.cheryme.top/Article/details/gtqvxcsxyb.html

TS:   class MyError extends Error {}
来源：http://dali.pengpengdd.cyou/Article/details/gtrkuyapwx.html

Java: class MyException extends RuntimeException {}
来源：http://dali.0kj1m.cn/Article/details/gtzvqensgy.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.wangshuangyany.cn/Article/details/gtwdfozojt.html

Ruby: class MyError < StandardError; end
来源：http://dali.gotoacloud.top/Article/details/gtoijhhcpf.html

C#:   class MyException : Exception {}
来源：http://dali.zhongyouzk.top/Article/details/gtwdrffvel.html

[H05] 捕获特定类型
来源：http://dali.ehwqpu.com/Article/details/gtushqctyk.html

Py:   except ValueError as e:
来源：http://dali.tian-w.cn/Article/details/gtykbzhczs.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtazaemjae.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.sufxvd.cn/Article/details/gtenaspytt.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfyosargp.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.316326.xyz/Article/details/gtexnjwhvn.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xuetiantiany.cn/Article/details/gtooxxykgv.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhengqikj.top/Article/details/gtarahgtux.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.birdmap.top/Article/details/gtbrvrjdly.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jyoumei.cn/Article/details/gtgcxmtzov.html

Py:   value = d.get("k") or default
来源：http://dali.shangyingyoupin.top/Article/details/gthpwiwvmr.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.nanxinkj.top/Article/details/gtaodgqnuk.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.daria6918.cn/Article/details/gtmqufywvw.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.meibo888.top/Article/details/gtgqqwopxo.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.smart0.xyz/Article/details/gtoraffpnt.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yj20258888.top/Article/details/gtvqcxhgdt.html

Ruby: d&.dig(:a, :b)
来源：http://dali.snrcjt.cn/Article/details/gtrpszhync.html

C#:   obj?.A?.B ?? default
来源：http://dali.gzhubu.top/Article/details/gtumgcgozu.html

[H07] 断言
来源：http://dali.cashguo.top/Article/details/gtvgarwdbw.html

Py:   assert x > 0, "必须为正"
来源：http://dali.pengpengdd.cyou/Article/details/gttyujgpor.html

PHP:  assert($x > 0);
来源：http://dali.ivvv.top/Article/details/gtipmmeltj.html

JS:   console.assert(x > 0);
来源：http://dali.cqqwz.cn/Article/details/gtmeyypjmd.html

TS:   console.assert(x > 0);
来源：http://dali.nanxinkj.top/Article/details/gttadtwvaw.html

Java: assert x > 0 : "必须为正";
来源：http://dali.dianchejie.cn/Article/details/gtbalyajfj.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.shzxlz.cn/Article/details/gtrrskozxx.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.redwolf501.top/Article/details/gtwgfhfudj.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yvedp.cn/Article/details/gtrfwokgiu.html

[H08] 获取错误信息与堆栈
来源：http://dali.chenlongwang.top/Article/details/gtozudyybw.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.316326.xyz/Article/details/gtvvdifkxk.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhengqikj.top/Article/details/gtppuirfci.html

JS:   e.message;  e.stack
来源：http://dali.yueranfly.top/Article/details/gteudvkzds.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.tianlin.xyz/Article/details/gtmpdpqklx.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.feifeiyinyue.top/Article/details/gtrlcugjus.html

Go:   err.Error()
来源：http://dali.hysaishi.cn/Article/details/gtaubdywby.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhoulong.xyz/Article/details/gtmjsgkumv.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xziqi.cn/Article/details/gtqhinamqg.html

[H09] 带错误码的异常
来源：http://dali.mhx1999.top/Article/details/gtqewcilwd.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ydzc1.top/Article/details/gtwwfletyt.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.daria6918.cn/Article/details/gtuciiicnn.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.aibaodan.cn/Article/details/gtbfzsogiz.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.feifeiyinyue.top/Article/details/gtkuwcwaek.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.gotoacloud.top/Article/details/gtjxscqycf.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.daria6918.cn/Article/details/gtkztrnjgc.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.cheryme.top/Article/details/gtwpcyoohk.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.guannengcc.top/Article/details/gtdmcccour.html

[H10] 资源自动释放
来源：http://dali.zhongyouzk.top/Article/details/gtichijvst.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xinyue.icu/Article/details/gthjxxesji.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtblajpiqu.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.dashuyun.cn/Article/details/gtjkvebger.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.nanxuanxn.top/Article/details/gtpsqexiig.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.havefunace.top/Article/details/gtdfximsvi.html

Go:   defer f.Close()
来源：http://dali.yj202588.top/Article/details/gthhqrpbtg.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.dianchejie.cn/Article/details/gtdaryyfml.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.sysykeji.top/Article/details/gtdruxtqxq.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtxpqglums.html

I. 正则表达式
来源：http://dali.zhongyouzk.top/Article/details/gtormytlvp.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gthxfaxqxs.html

[I01] 判断是否匹配
来源：http://dali.smart0.xyz/Article/details/gtvlofcqhu.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.gogol.net.cn/Article/details/gtskhmtnbj.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.meibo888.top/Article/details/gtrcxjtkpp.html

JS:   /\d+/.test(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtmjuiegwc.html

TS:   /\d+/.test(s)
来源：http://dali.nanxuanxn.top/Article/details/gtcwtorhwp.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jqgfzy.top/Article/details/gttlmnkggs.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.cheryme.top/Article/details/gturjtbypl.html

Ruby: s.match?(/\d+/)
来源：http://dali.jinqigufen.top/Article/details/gtgtzvtvmx.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jinghuilouyu.cn/Article/details/gtiiuftzss.html

[I02] 提取所有匹配
来源：http://dali.xuetiantiany.cn/Article/details/gtnbbmvbyr.html

Py:   re.findall(r"\d+", s)
来源：http://dali.havefunace.top/Article/details/gtlgwdmanl.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.svipenyu.cn/Article/details/gtgtkjswlh.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.shuidangran.top/Article/details/gtwnnamzkp.html

TS:   s.match(/\d+/g)
来源：http://dali.meibo888.top/Article/details/gthvuylsjh.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yj20258.top/Article/details/gtfvhbqils.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jianghu66.top/Article/details/gtlvehzyub.html

Ruby: s.scan(/\d+/)
来源：http://dali.shzxlz.cn/Article/details/gtdqkrqqki.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.tianlin.xyz/Article/details/gtbdkwqlls.html

[I03] 提取捕获分组
来源：http://dali.iojbl.cn/Article/details/gtjvsylfao.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.cucudq.cn/Article/details/gtwaaqvjhz.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.wangdashe.top/Article/details/gtvwydgxrc.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhengqikj.top/Article/details/gtafpjxfts.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhongyouzk.top/Article/details/gtwugevyeh.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xziqi.cn/Article/details/gtidseoyny.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.meibo888.top/Article/details/gtnfzsvnmz.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.daria6918.cn/Article/details/gtavwedtsw.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gtiwsvkkun.html

[I04] 正则替换
来源：http://dali.ehwqpu.com/Article/details/gtzghhxomg.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.bjfxy.top/Article/details/gtwprjrzsv.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.xinyue.icu/Article/details/gtxavokvzk.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.daxiang520.top/Article/details/gtbvbgibgk.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.ppjwa.cn/Article/details/gtxrpkwnxx.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hammf.cn/Article/details/gtfdvtrcsk.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.aizwys.cn/Article/details/gtmtypnuff.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.sysykeji.top/Article/details/gtjmakpgcc.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.c1oappe.top/Article/details/gtcofiyshz.html

[I05] 按正则拆分
来源：http://dali.xziqi.cn/Article/details/gtgoyogyck.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.smart0.xyz/Article/details/gtxcfikxjl.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtusyrbfdj.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hysaishi.cn/Article/details/gtiacfyfqj.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.gzhubu.top/Article/details/gtdwehxnvv.html

Java: s.split("\\s*,\\s*")
来源：http://dali.hnqzz.top/Article/details/gtgjitlcga.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.nanxuanxn.top/Article/details/gtwzixepzq.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.dianchejie.cn/Article/details/gtdwgjkigz.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.c1oappe.top/Article/details/gtohhsczxw.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.pengpengdd.cyou/Article/details/gtjhfufhbx.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.andypj.xyz/Article/details/gtmwpitbbp.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yangfankeji.com/Article/details/gtzjwtgspf.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ehwqpu.com/Article/details/gtuxhfnead.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.dianchejie.cn/Article/details/gtlvtwmzis.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.cucudq.cn/Article/details/gtmehtfvnw.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.316326.xyz/Article/details/gtcwyfwzps.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.tanke756.top/Article/details/gteuurnszn.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ybcxt.top/Article/details/gtolscqguv.html

[I07] 忽略大小写与多行模式
来源：http://dali.xziqi.cn/Article/details/gtkooevetc.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.shangyingyoupin.top/Article/details/gtewtyurah.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.smart0.xyz/Article/details/gtktsnkrmo.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.gogol.net.cn/Article/details/gtymelsmrs.html

TS:   /error/gim
来源：http://dali.hongshengwenyu.top/Article/details/gtfvyavoxf.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.daria6918.cn/Article/details/gtpabdnpna.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hammf.cn/Article/details/gtwbovkmpq.html

Ruby: s.scan(/error/i)
来源：http://dali.smart0.xyz/Article/details/gtgvsahdwr.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ivvv.top/Article/details/gtyyjjwhmr.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jianghu66.top/Article/details/gtizqkwtnc.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.dashuyun.cn/Article/details/gtbcxqypkp.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jinqigfzy.top/Article/details/gtrnuscrkt.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.dianchejie.cn/Article/details/gtfatxzuro.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.mhx1999.top/Article/details/gtmmkhdebk.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yanxiufei.cn/Article/details/gtpmtinvck.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.andypj.xyz/Article/details/gtxaiptbma.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.ppjwa.cn/Article/details/gtdsqcdkfr.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.birdmap.top/Article/details/gtcdbgaisl.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtbqxqhccj.html

J. 日期与时间
来源：http://dali.xylfe.cn/Article/details/gtfcxbwgkj.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtxzeeddfb.html

[J01] 获取当前时间
来源：http://dali.daxiang520.top/Article/details/gthdhydgla.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yanxiufei.cn/Article/details/gtjrxkacpt.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jiagoushi.top/Article/details/gtslqaosag.html

JS:   new Date();  Date.now()
来源：http://dali.xuanzx.com/Article/details/gtmeucqmyq.html

TS:   new Date();  Date.now()
来源：http://dali.hnxiangtu.top/Article/details/gtsvlvnwdv.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yanxiufei.cn/Article/details/gtsdigiljg.html

Go:   time.Now()
来源：http://dali.yonumen.top/Article/details/gtxljuyaga.html

Ruby: Time.now
来源：http://dali.zhongyouzk.top/Article/details/gtzpyxytns.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.chenlongwang.top/Article/details/gtuirhzvri.html

[J02] 格式化输出
来源：http://dali.jinqigfzy.top/Article/details/gtngdjtbqh.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgijkzapu.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.nanxinkj.top/Article/details/gthummmrod.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.316326.xyz/Article/details/gtsipialof.html

TS:   d.toISOString()
来源：http://dali.svipenyu.cn/Article/details/gtbucuojan.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.havefunace.top/Article/details/gtbxsopvox.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.shangyingyoupin.top/Article/details/gtdvwektvr.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sweek.top/Article/details/gthaoxfptf.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ydzc1.top/Article/details/gtnmtumjic.html

[J03] 字符串解析为日期
来源：http://dali.jinghuilouyu.cn/Article/details/gtxhfuhqqk.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsnnnlutp.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xinyue.icu/Article/details/gtpnxlidmh.html

JS:   new Date("2024-01-02")
来源：http://dali.ivvv.top/Article/details/gtohikbzee.html

TS:   new Date("2024-01-02")
来源：http://dali.hysaishi.cn/Article/details/gtatoinezl.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yueranfly.top/Article/details/gtcpyoycry.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.316326.xyz/Article/details/gtfjwyjnek.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yanxiufei.cn/Article/details/gtufmbacly.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xinyue.icu/Article/details/gtixuupuig.html

[J04] 时间戳与日期互转
来源：http://dali.xuanzx.com/Article/details/gttdnmgtwi.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.chenlongwang.top/Article/details/gtnwwezcjf.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.aibaodan.cn/Article/details/gtebmxrwdl.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxhiookbx.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.chenzaomai.com/Article/details/gtvhrxgeqg.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.shuidangran.top/Article/details/gtjwbxhwdc.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.aibaodan.cn/Article/details/gtdvqoxxts.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtigzzwqqj.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrkhizyuy.html

[J05] 时间加减（加 7 天）
来源：http://dali.daria6918.cn/Article/details/gthfufyies.html

Py:   now + timedelta(days=7)
来源：http://dali.jqgfzy.top/Article/details/gtinypiaki.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtazwgugwm.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.daria6918.cn/Article/details/gtgpjmnuxi.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.guowangkeji.top/Article/details/gtwjholobm.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.cheryme.top/Article/details/gtyhlfrjmk.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.guowangkeji.top/Article/details/gtvgguzewy.html

Ruby: Time.now + 7 * 86400
来源：http://dali.tianlin.xyz/Article/details/gtwihkwuzo.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhoulong.xyz/Article/details/gteureqzqt.html

[J06] 计算两时间之差
来源：http://dali.ehwqpu.com/Article/details/gteqahttdt.html

Py:   (end - start).total_seconds()
来源：http://dali.zycfv.cn/Article/details/gtwbdkklxj.html

PHP:  $end->diff($start)->days;
来源：http://dali.snrcjt.cn/Article/details/gtuqcswxhw.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.xinyue.icu/Article/details/gtjydwebla.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.tian-w.cn/Article/details/gtmtrqeupj.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.cheryme.top/Article/details/gtaxrsudcu.html

Go:   end.Sub(start).Hours()
来源：http://dali.daxiang520.top/Article/details/gtfmatfmzc.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hywenlv.cn/Article/details/gtqfkytthv.html

C#:   (end - start).TotalSeconds
来源：http://dali.cdnleiting.top/Article/details/gtrwzaseci.html

[J07] 比较两个日期
来源：http://dali.gogol.net.cn/Article/details/gtlgcfbiay.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zycfv.cn/Article/details/gtizccqvkl.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hysaishi.cn/Article/details/gtndhegkmw.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.cashguo.top/Article/details/gtnmrxmcsl.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.nwbrower.top/Article/details/gtejgcrxib.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.vqdsnc.cn/Article/details/gtsfhohkvs.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zycfv.cn/Article/details/gtxfodjlle.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hnqzz.top/Article/details/gtbpbrejoy.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.andypj.xyz/Article/details/gtowjwfwvw.html

[J08] 提取年月日与星期
来源：http://dali.fzhhl.top/Article/details/gtfeqgjebf.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.redwolf501.top/Article/details/gtjuitlktj.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.shuidangran.top/Article/details/gthwdfdvrv.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.nanxuanxn.top/Article/details/gtqnzforef.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.gogol.net.cn/Article/details/gtkdgximeo.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jinghuilouyu.cn/Article/details/gtmqiwnbkl.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.xuanzx.com/Article/details/gtylejlglr.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.vqdsnc.cn/Article/details/gtljpffjwo.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.fengsongda.top/Article/details/gtqfkwiaqa.html

[J09] 时区处理
来源：http://dali.daxiang520.top/Article/details/gtmjwidotg.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhoulong.xyz/Article/details/gtbmnploly.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.sweek.top/Article/details/gtmxjbscbn.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqemtkulc.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.nanxinkj.top/Article/details/gtdssljpkq.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ehwqpu.com/Article/details/gtiswrbxju.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yuxming.cn/Article/details/gtdsmqlbcx.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yueranfly.top/Article/details/gtvjfizfmw.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.redwolf501.top/Article/details/gtmcvywqel.html

[J10] 取今天 / 本月第一天
来源：http://dali.yj20258888.top/Article/details/gtsmevnivw.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.c1oappe.top/Article/details/gtryhiceik.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jinghuilouyu.cn/Article/details/gtsaopxogw.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.sysykeji.top/Article/details/gtjvkjgayv.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.9152youxi.cn/Article/details/gtmetlowbb.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yj20258.top/Article/details/gtzycwkuic.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.nwbrower.top/Article/details/gtzpngftns.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.chenlongwang.top/Article/details/gttnryuxgx.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.xylfe.cn/Article/details/gtzfcahpna.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtopnkwqua.html

K. JSON 与序列化
来源：http://dali.c1oappe.top/Article/details/gtvjpduexy.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtjnuicpkl.html

[K01] 对象转 JSON 字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtvjwnpfyl.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwonmivvb.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwzdqxskm.html

JS:   JSON.stringify(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gticqwpnat.html

TS:   JSON.stringify(obj)
来源：http://dali.nwbrower.top/Article/details/gtaiqbphga.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.smart0.xyz/Article/details/gtohxpgncj.html

Go:   json.Marshal(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwjiahxff.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhongyouzk.top/Article/details/gtckfwccdt.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jiagoushi.top/Article/details/gtzkbfybpp.html

[K02] JSON 字符串转对象
来源：http://dali.c1oappe.top/Article/details/gtqnvqdqxn.html

Py:   json.loads(s)
来源：http://dali.sysykeji.top/Article/details/gtvqrtwgvl.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hnxiangtu.top/Article/details/gtaxqawbqr.html

JS:   JSON.parse(s)
来源：http://dali.jlsjyb.cn/Article/details/gtxrmyfhue.html

TS:   JSON.parse(s)
来源：http://dali.sxryk.cn/Article/details/gtzrwzcmcj.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.cashguo.top/Article/details/gtwdgnzgoo.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.snrcjt.cn/Article/details/gtnhbfdekn.html

Ruby: JSON.parse(s)
来源：http://dali.meibo888.top/Article/details/gtazrvlggv.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yangfankeji.com/Article/details/gtbrgjttlu.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.tanke756.top/Article/details/gtiyzbacju.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.xuetiantiany.cn/Article/details/gtzofpvauh.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.chenjidiqi.icu/Article/details/gtqwrbviic.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.tianlin.xyz/Article/details/gtfoihazlu.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.quarkkingdee.top/Article/details/gteelofixr.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtzyhaljfu.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.cqqwz.cn/Article/details/gtbrtyvtbw.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.cheryme.top/Article/details/gtkmwfqijg.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yangfankeji.com/Article/details/gtwsxidovz.html

[K04] 读取 JSON 文件
来源：http://dali.zycfv.cn/Article/details/gtaxyutlfj.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhongyouzk.top/Article/details/gtsuoabzsk.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.smart0.xyz/Article/details/gtvufmmqip.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hnqzz.top/Article/details/gtvrbhgjan.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.vqdsnc.cn/Article/details/gtglblyhho.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jianghu66.top/Article/details/gtwzjywaxc.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.9152youxi.cn/Article/details/gtinuxfyay.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.pycfn.com/Article/details/gtwkvjiatx.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jianghu66.top/Article/details/gtlihtuqxi.html

[K05] 深拷贝对象
来源：http://dali.snrcjt.cn/Article/details/gtcllcyili.html

Py:   copy.deepcopy(obj)
来源：http://dali.smart0.xyz/Article/details/gtrqqymajl.html

PHP:  unserialize(serialize($obj));
来源：http://dali.quarkkingdee.top/Article/details/gtavlfbqob.html

JS:   structuredClone(obj)
来源：http://dali.yj202588.top/Article/details/gteujksbji.html

TS:   structuredClone(obj)
来源：http://dali.jyoumei.cn/Article/details/gtmxpbbhds.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jqgfzy.top/Article/details/gtzkqknxya.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xinyue.icu/Article/details/gtubumhbeq.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtinuxjodn.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hnqzz.top/Article/details/gtiedemsbj.html

[K06] 解析 URL 查询串
来源：http://dali.tianlin.xyz/Article/details/gtxwoktitw.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yueranfly.top/Article/details/gtaygmfhzt.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhongyouzk.top/Article/details/gtczanngtn.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yuanzhike.top/Article/details/gtrirbnlfk.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yangfankeji.com/Article/details/gtzsvdeymz.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.daxiang520.top/Article/details/gtmjjabsfe.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.shzxlz.cn/Article/details/gtokonombm.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.tianlin.xyz/Article/details/gtcberykyt.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.xuanzx.com/Article/details/gtdnfqejjz.html

[K07] 进制转换
来源：http://dali.nwbrower.top/Article/details/gtviffrdho.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gtzgjbynmh.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.shanyushiyangtech.top/Article/details/gtshugpusv.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.tianlin.xyz/Article/details/gtxvfuilax.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.gogol.net.cn/Article/details/gtzfafzhqh.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsseposaj.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnmqypqcg.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.pengpengdd.cyou/Article/details/gtijdrxbju.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.pycfn.com/Article/details/gttznamrld.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jinqigfzy.top/Article/details/gtdfnihwjc.html

Py:   pickle.dumps(obj)
来源：http://dali.nwbrower.top/Article/details/gtbdmifywd.html


<!-- 参考信息 -->