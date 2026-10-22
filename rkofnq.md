代发 wailian999

[H03] 主动抛出异常
来源：http://dali.gogol.net.cn/Article/details/gt2xxjoqicq.html

Py:   raise ValueError("错误信息")
来源：http://dali.yonumen.top/Article/details/gt2llqmidnj.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.shangyingyoupin.top/Article/details/gt2mxzniukn.html

JS:   throw new Error("错误信息");
来源：http://dali.pengpengdd.cyou/Article/details/gt2iydeejws.html

TS:   throw new Error("错误信息");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jxiugqnm.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ehwqpu.com/Article/details/gt2mcurwzrw.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.fzhhl.top/Article/details/gt2xilevnuc.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jyoumei.cn/Article/details/gt2usshknai.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.gaohongyu789.top/Article/details/gt2rzcoskhx.html

[H04] 自定义异常类型
来源：http://dali.pengpengdd.cyou/Article/details/gt2wjrjhvzs.html

Py:   class MyError(Exception): pass
来源：http://dali.zhoulong.xyz/Article/details/gt2fjeojkbt.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jianghu66.top/Article/details/gt2wslnkfdp.html

JS:   class MyError extends Error {}
来源：http://dali.andypj.xyz/Article/details/gt2zxqabzug.html

TS:   class MyError extends Error {}
来源：http://dali.jqgfzy.top/Article/details/gt2ufcnaqkt.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hysaishi.cn/Article/details/gt2pkbtibzd.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.nanxinkj.top/Article/details/gt2zzeqgbrj.html

Ruby: class MyError < StandardError; end
来源：http://dali.shzxlz.cn/Article/details/gt2yfabjora.html

C#:   class MyException : Exception {}
来源：http://dali.yj202588.top/Article/details/gt2elrbivhf.html

[H05] 捕获特定类型
来源：http://dali.wangshuangyany.cn/Article/details/gt2nkqpnrtu.html

Py:   except ValueError as e:
来源：http://dali.gzhubu.top/Article/details/gt2xbypkkpd.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.nwbrower.top/Article/details/gt2wnynprtb.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.daria6918.cn/Article/details/gt2vcejzlsb.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mgdqturj.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xziqi.cn/Article/details/gt2mkiyhnps.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xuanzx.com/Article/details/gt2derpphus.html

Ruby: rescue ArgumentError => e
来源：http://dali.yuanzhike.top/Article/details/gt2lzpjtdjg.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.cqqwz.cn/Article/details/gt2baxclwzz.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhixingplan.top/Article/details/gt2cfufzdni.html

Py:   value = d.get("k") or default
来源：http://dali.dianchejie.cn/Article/details/gt2pvvpebdi.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.sweek.top/Article/details/gt2muehgnrs.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yangfankeji.com/Article/details/gt2yoybuuqb.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.iojbl.cn/Article/details/gt2ximpcfvz.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.redwolf501.top/Article/details/gt2hfaaopmf.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.dashuyun.cn/Article/details/gt2vsocbosi.html

Ruby: d&.dig(:a, :b)
来源：http://dali.xylfe.cn/Article/details/gt2kugxlvad.html

C#:   obj?.A?.B ?? default
来源：http://dali.yj20258888.top/Article/details/gt2axxzyaui.html

[H07] 断言
来源：http://dali.aizwys.cn/Article/details/gt2yqfunltb.html

Py:   assert x > 0, "必须为正"
来源：http://dali.aibaodan.cn/Article/details/gt2nicjrfvl.html

PHP:  assert($x > 0);
来源：http://dali.shzxlz.cn/Article/details/gt2bdqhldpd.html

JS:   console.assert(x > 0);
来源：http://dali.pengpengdd.cyou/Article/details/gt2kmbfrkyh.html

TS:   console.assert(x > 0);
来源：http://dali.andypj.xyz/Article/details/gt2zrtbykav.html

Java: assert x > 0 : "必须为正";
来源：http://dali.dianchejie.cn/Article/details/gt2zbaerkux.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.sxryk.cn/Article/details/gt2syjyzyzd.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.shzxlz.cn/Article/details/gt2hbsosncl.html

C#:   Debug.Assert(x > 0);
来源：http://dali.shzxlz.cn/Article/details/gt2uolumyjb.html

[H08] 获取错误信息与堆栈
来源：http://dali.xinyue.icu/Article/details/gt2gvxhckoa.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yj20258.top/Article/details/gt2xbtmmycl.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.mhx1999.top/Article/details/gt2jrstarit.html

JS:   e.message;  e.stack
来源：http://dali.yj202588.top/Article/details/gt2hdykfxjt.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yvedp.cn/Article/details/gt2gftvturo.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2apybjaon.html

Go:   err.Error()
来源：http://dali.zhongyouzk.top/Article/details/gt2dyqukfes.html

Ruby: e.message;  e.backtrace
来源：http://dali.sweek.top/Article/details/gt2kbqxlwdk.html

C#:   e.Message;  e.StackTrace
来源：http://dali.mhx1999.top/Article/details/gt2evimukhv.html

[H09] 带错误码的异常
来源：http://dali.yonumen.top/Article/details/gt2ytsncjhl.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.dianchejie.cn/Article/details/gt2jytuhnwu.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jqgfzy.top/Article/details/gt2zdrjmsyd.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.gotoacloud.top/Article/details/gt2qghezofz.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.snrcjt.cn/Article/details/gt2pzzihpos.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.ybcxt.top/Article/details/gt2xttksoda.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.meibo888.top/Article/details/gt2gspqjjzw.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.fzhhl.top/Article/details/gt2akhkshiy.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.tian-w.cn/Article/details/gt2xfxjllcp.html

[H10] 资源自动释放
来源：http://dali.kuanghao11.cn/Article/details/gt2lehvstyh.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xziqi.cn/Article/details/gt2zhqhvcgx.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.tianlin.xyz/Article/details/gt2iqnejqqq.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.wangdashe.top/Article/details/gt2tfjwwxag.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.snrcjt.cn/Article/details/gt2timbosyh.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ppjwa.cn/Article/details/gt2ccqflcht.html

Go:   defer f.Close()
来源：http://dali.hfpthk.cn/Article/details/gt2jjfxpncx.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.chenjidiqi.icu/Article/details/gt2adlecdua.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gt2nfnrqgpm.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2wylieogk.html

I. 正则表达式
来源：http://dali.xuanzx.com/Article/details/gt2vmkmkcml.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2udzhqfmd.html

[I01] 判断是否匹配
来源：http://dali.nanxuanxn.top/Article/details/gt2qfptwmik.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jianghu66.top/Article/details/gt2mkpumbrp.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.nwbrower.top/Article/details/gt2aivrinnh.html

JS:   /\d+/.test(s)
来源：http://dali.ppjwa.cn/Article/details/gt2qxahbqoc.html

TS:   /\d+/.test(s)
来源：http://dali.ehwqpu.com/Article/details/gt2jveomgca.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.9152youxi.cn/Article/details/gt2xckwusxh.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jinqigufen.top/Article/details/gt2utuxsdxw.html

Ruby: s.match?(/\d+/)
来源：http://dali.wangdashe.top/Article/details/gt2frfzflbj.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ccgesmes.html

[I02] 提取所有匹配
来源：http://dali.fzhhl.top/Article/details/gt2qekjmjnz.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xinyue.icu/Article/details/gt2uvdmmnxw.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.birdmap.top/Article/details/gt2mbswvzbc.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.0kj1m.cn/Article/details/gt2ebqwtynp.html

TS:   s.match(/\d+/g)
来源：http://dali.jiagoushi.top/Article/details/gt2jtvdujpo.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.nwbrower.top/Article/details/gt2jrjqaqxc.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.mhx1999.top/Article/details/gt2gvngbfvu.html

Ruby: s.scan(/\d+/)
来源：http://dali.jqgufenzy.top/Article/details/gt2kivnymbl.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yuanzhike.top/Article/details/gt2tvwgijxf.html

[I03] 提取捕获分组
来源：http://dali.0kj1m.cn/Article/details/gt2zptpmknk.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yuanzhike.top/Article/details/gt2wyxbtait.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.sxryk.cn/Article/details/gt2ankwpsak.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.hongshengwenyu.top/Article/details/gt2ydnpncsu.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.feifeiyinyue.top/Article/details/gt2cknczhoi.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.cheryme.top/Article/details/gt2szaadkff.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.meibo888.top/Article/details/gt2benaetpi.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ivvv.top/Article/details/gt2xugkuxqc.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhiwuduotai.top/Article/details/gt2upqhducj.html

[I04] 正则替换
来源：http://dali.jqgufenzy.top/Article/details/gt2bjbxgnlb.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.bjfxy.top/Article/details/gt2gvpkftrn.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.316326.xyz/Article/details/gt2icpxhprg.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jyoumei.cn/Article/details/gt2zztysmeh.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.chenjidiqi.icu/Article/details/gt2jfjoqmkf.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.xuetiantiany.cn/Article/details/gt2hkkzuraq.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hywenlv.cn/Article/details/gt2xqfkonxf.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.cqqwz.cn/Article/details/gt2nxvigjza.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.cucudq.cn/Article/details/gt2yaknferp.html

[I05] 按正则拆分
来源：http://dali.xziqi.cn/Article/details/gt2gvltueev.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yvedp.cn/Article/details/gt2yhkfurfo.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.haohaochexian.top/Article/details/gt2tmcgljcm.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yj20258888.top/Article/details/gt2dgqwnkop.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jyoumei.cn/Article/details/gt2fkowdzkm.html

Java: s.split("\\s*,\\s*")
来源：http://dali.shzxlz.cn/Article/details/gt2emvhtmdw.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.vqdsnc.cn/Article/details/gt2gaacmzps.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.quarkkingdee.top/Article/details/gt2rpxixwls.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mldoclpg.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.ydzc1.top/Article/details/gt2saqkhkqp.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hhwekqgk.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jlsjyb.cn/Article/details/gt2cgvvxhsf.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sysykeji.top/Article/details/gt2ipsrwuir.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yj202588.top/Article/details/gt2rqofawjt.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xziqi.cn/Article/details/gt2gurqfwav.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.sweek.top/Article/details/gt2qlysbjox.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.chenjidiqi.icu/Article/details/gt2ergbsrdf.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.dianchejie.cn/Article/details/gt2solsfyjx.html

[I07] 忽略大小写与多行模式
来源：http://dali.cqqwz.cn/Article/details/gt2euhwulpe.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.shangyingyoupin.top/Article/details/gt2vtaoykfb.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhongyouzk.top/Article/details/gt2katluqxg.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yanxiufei.cn/Article/details/gt2piskmggf.html

TS:   /error/gim
来源：http://dali.hfpthk.cn/Article/details/gt2hufvdowz.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.ppjwa.cn/Article/details/gt2qnpgeulb.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jinqigfzy.top/Article/details/gt2cmfsiebd.html

Ruby: s.scan(/error/i)
来源：http://dali.gotoacloud.top/Article/details/gt2tweiawas.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.xziqi.cn/Article/details/gt2nqepnaqb.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yj202588.top/Article/details/gt2qsjldzwm.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.0kj1m.cn/Article/details/gt2viyqamxc.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yonumen.top/Article/details/gt2iqejxpjv.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hysaishi.cn/Article/details/gt2ohjtrivh.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.nanxuanxn.top/Article/details/gt2bivucuag.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hywenlv.cn/Article/details/gt2ttqeryxc.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.c1oappe.top/Article/details/gt2qtcxqpgs.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.haohaochexian.top/Article/details/gt2uvrjwylc.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jianghu66.top/Article/details/gt2wwsbkbfv.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2zgqkevef.html

J. 日期与时间
来源：http://dali.ppjwa.cn/Article/details/gt2tqgmfdmc.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2upbdxwde.html

[J01] 获取当前时间
来源：http://dali.pycfn.com/Article/details/gt2eostlwbl.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bpsjxdib.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2urrrhuzt.html

JS:   new Date();  Date.now()
来源：http://dali.xziqi.cn/Article/details/gt2wazqjrio.html

TS:   new Date();  Date.now()
来源：http://dali.jqgfzy.top/Article/details/gt2poioambf.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.xylfe.cn/Article/details/gt2ccubwsye.html

Go:   time.Now()
来源：http://dali.hysaishi.cn/Article/details/gt2zgflugai.html

Ruby: Time.now
来源：http://dali.gogol.net.cn/Article/details/gt2soelkgen.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.shzxlz.cn/Article/details/gt2aqeblqdq.html

[J02] 格式化输出
来源：http://dali.dianchejie.cn/Article/details/gt2xbolpbgw.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.mhx1999.top/Article/details/gt2ccsnisuw.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zycfv.cn/Article/details/gt2psdrmsmx.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yj202588.top/Article/details/gt2pbhlgejr.html

TS:   d.toISOString()
来源：http://dali.zhijiandao.cn/Article/details/gt2imlcwstd.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bvdhqcns.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jiagoushi.top/Article/details/gt2eqaiyuoc.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jlsjyb.cn/Article/details/gt2lxizuldm.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.quarkkingdee.top/Article/details/gt2wqtmagqv.html

[J03] 字符串解析为日期
来源：http://dali.cucudq.cn/Article/details/gt2jgroojcc.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.tian-w.cn/Article/details/gt2fnwzsxcq.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.gogol.net.cn/Article/details/gt2zjadmygk.html

JS:   new Date("2024-01-02")
来源：http://dali.ybcxt.top/Article/details/gt2wwabvbpl.html

TS:   new Date("2024-01-02")
来源：http://dali.nanxinkj.top/Article/details/gt2wwlegqee.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yuanzhike.top/Article/details/gt2gjypxbtd.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jqgufenzy.top/Article/details/gt2ctgnvnvb.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.cqqwz.cn/Article/details/gt2jgzhkqzy.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.chenlongwang.top/Article/details/gt2yizyodny.html

[J04] 时间戳与日期互转
来源：http://dali.yongpay.top/Article/details/gt2pohqkgsz.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iurzarun.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhongyouzk.top/Article/details/gt2horkpozk.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jyoumei.cn/Article/details/gt2bxehfxkt.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lfxgqsqb.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.snrcjt.cn/Article/details/gt2ntaobgbs.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.smart0.xyz/Article/details/gt2ywidtlah.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.gzhubu.top/Article/details/gt2fefntdzu.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.sxryk.cn/Article/details/gt2lwjpqsfl.html

[J05] 时间加减（加 7 天）
来源：http://dali.sysykeji.top/Article/details/gt2qqzgwhzz.html

Py:   now + timedelta(days=7)
来源：http://dali.c1oappe.top/Article/details/gt2omcrqbbr.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yangfankeji.com/Article/details/gt2mingdjjv.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ipsghvvx.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.vqdsnc.cn/Article/details/gt2wgqhssjc.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yongpay.top/Article/details/gt2zxzdldlp.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.cdnleiting.top/Article/details/gt2qbxfkqjm.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hammf.cn/Article/details/gt2plqjdqts.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.xuanzx.com/Article/details/gt2jpunmsgx.html

[J06] 计算两时间之差
来源：http://dali.jqgfzy.top/Article/details/gt2ajzdefpv.html

Py:   (end - start).total_seconds()
来源：http://dali.tian-w.cn/Article/details/gt2uyirszua.html

PHP:  $end->diff($start)->days;
来源：http://dali.tianlin.xyz/Article/details/gt2egwestrh.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.snrcjt.cn/Article/details/gt2ojmkejjc.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.fengsongda.top/Article/details/gt2eurexhhv.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zycfv.cn/Article/details/gt2ecijcgfd.html

Go:   end.Sub(start).Hours()
来源：http://dali.gaohongyu789.top/Article/details/gt2xkhjpkpm.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jlsjyb.cn/Article/details/gt2goyqkukt.html

C#:   (end - start).TotalSeconds
来源：http://dali.jinqigufen.top/Article/details/gt2uzhpowuz.html

[J07] 比较两个日期
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2syttcwlg.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.sxryk.cn/Article/details/gt2slisnsge.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.shuidangran.top/Article/details/gt2hghzjcnc.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.nwbrower.top/Article/details/gt2twlztwwp.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.cdnleiting.top/Article/details/gt2znuygwvl.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2pjvycope.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.0kj1m.cn/Article/details/gt2msmimvmf.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jqgufenzy.top/Article/details/gt2ntqjtime.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.gotoacloud.top/Article/details/gt2jxnlalwm.html

[J08] 提取年月日与星期
来源：http://dali.yj20258.top/Article/details/gt2zgrokphv.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hnxiangtu.top/Article/details/gt2stryekdm.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yonumen.top/Article/details/gt2isgzvrvs.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.cashguo.top/Article/details/gt2nlvksarr.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.feifeiyinyue.top/Article/details/gt2oolymyww.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.kuanghao11.cn/Article/details/gt2omeakwug.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.gzhubu.top/Article/details/gt2zrwrvobn.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jiagoushi.top/Article/details/gt2nzgaofoe.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jqgfzy.top/Article/details/gt2mizyotcn.html

[J09] 时区处理
来源：http://dali.xylfe.cn/Article/details/gt2ryourplo.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jinqigufen.top/Article/details/gt2szazqbqn.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.cashguo.top/Article/details/gt2mkqpocaw.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.9152youxi.cn/Article/details/gt2hofdmotp.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yanxiufei.cn/Article/details/gt2pggcjvom.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hnqzz.top/Article/details/gt2fmjdvmyi.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.xylfe.cn/Article/details/gt2eyuqrivv.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jqgfzy.top/Article/details/gt2wjxetabv.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhoulong.xyz/Article/details/gt2upjbmhxy.html

[J10] 取今天 / 本月第一天
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gipjgbxv.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2xzarndou.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.feifeiyinyue.top/Article/details/gt2rdqqegyz.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yonumen.top/Article/details/gt2tcimkzez.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yonumen.top/Article/details/gt2noajrhqi.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.gzhubu.top/Article/details/gt2hwdjgnsz.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.kuanghao11.cn/Article/details/gt2subvmzia.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.havefunace.top/Article/details/gt2huzgvuvu.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.snrcjt.cn/Article/details/gt2txebehao.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2ululwugs.html

K. JSON 与序列化
来源：http://dali.gaohongyu789.top/Article/details/gt2czrakgag.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2defolprn.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhongyouzk.top/Article/details/gt2hvxbyosj.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ybcxt.top/Article/details/gt2hanzwxqy.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jianghu66.top/Article/details/gt2bzikdaow.html

JS:   JSON.stringify(obj)
来源：http://dali.yueranfly.top/Article/details/gt2vysmqiug.html

TS:   JSON.stringify(obj)
来源：http://dali.haohaochexian.top/Article/details/gt2orgkubfx.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yongpay.top/Article/details/gt2ussvhdma.html

Go:   json.Marshal(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gt2utcjxkog.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.xylfe.cn/Article/details/gt2dogfxslb.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yueranfly.top/Article/details/gt2rqpvxelf.html

[K02] JSON 字符串转对象
来源：http://dali.hywenlv.cn/Article/details/gt2gaazymdg.html

Py:   json.loads(s)
来源：http://dali.0kj1m.cn/Article/details/gt2ryijijft.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.tanke756.top/Article/details/gt2zremtoco.html

JS:   JSON.parse(s)
来源：http://dali.zycfv.cn/Article/details/gt2sutuowus.html

TS:   JSON.parse(s)
来源：http://dali.jinqigufen.top/Article/details/gt2wijrorvw.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yangfankeji.com/Article/details/gt2msnykcjm.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.cqqwz.cn/Article/details/gt2uyynewjr.html

Ruby: JSON.parse(s)
来源：http://dali.shuidangran.top/Article/details/gt2vinvbcjy.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2ezqnqzfv.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nocljmdy.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hnxiangtu.top/Article/details/gt2ldiejzfw.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.cdnleiting.top/Article/details/gt2bsjnxcrl.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.gotoacloud.top/Article/details/gt2ipchmlbk.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.vqdsnc.cn/Article/details/gt2moemmosp.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jlsjyb.cn/Article/details/gt2kukgdikr.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.smart0.xyz/Article/details/gt2xhshwwdg.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.pycfn.com/Article/details/gt2pnmowgih.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hnxiangtu.top/Article/details/gt2ndedeauq.html

[K04] 读取 JSON 文件
来源：http://dali.yangfankeji.com/Article/details/gt2bfftlsyr.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhoulong.xyz/Article/details/gt2mcnauzyt.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ecbobxzf.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nanxuanxn.top/Article/details/gt2uwofqafs.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cashguo.top/Article/details/gt2plwjfsiq.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.pengpengdd.cyou/Article/details/gt2narnyswt.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bzkrzxro.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.cashguo.top/Article/details/gt2iubgbxat.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.pycfn.com/Article/details/gt2yoidwmay.html

[K05] 深拷贝对象
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cywsljnx.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhongyouzk.top/Article/details/gt2bbrfbydx.html

PHP:  unserialize(serialize($obj));
来源：http://dali.9152youxi.cn/Article/details/gt2lybthslo.html

JS:   structuredClone(obj)
来源：http://dali.zhixingplan.top/Article/details/gt2wdqbowme.html

TS:   structuredClone(obj)
来源：http://dali.sufxvd.cn/Article/details/gt2bvcodhri.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ydzc1.top/Article/details/gt2gplviwuw.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yj20258.top/Article/details/gt2gniyetmz.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.0kj1m.cn/Article/details/gt2uypxzzna.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.316326.xyz/Article/details/gt2heybtmfc.html

[K06] 解析 URL 查询串
来源：http://dali.zdqjudy.top/Article/details/gt2siswzfgn.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yongpay.top/Article/details/gt2rivuholq.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yj20258888.top/Article/details/gt2qhslusaj.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.chenlongwang.top/Article/details/gt2qmkgnycz.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.andypj.xyz/Article/details/gt2aufivqjn.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ogggviux.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.kuanghao11.cn/Article/details/gt2cxgmkxvm.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.c1oappe.top/Article/details/gt2gstzmuuy.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.chenlongwang.top/Article/details/gt2cuvvvovs.html

[K07] 进制转换
来源：http://dali.pengpengdd.cyou/Article/details/gt2tfrejpds.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xuetiantiany.cn/Article/details/gt2duxbyrmu.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.daria6918.cn/Article/details/gt2sndjeslr.html


<!-- 参考信息 -->