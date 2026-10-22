代发 wailian999

TS:   throw new Error("错误信息");
来源：http://dali.yangfankeji.com/Article/details/gt2blnrxxzp.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.mhx1999.top/Article/details/gt2mvonrqrw.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhiwuduotai.top/Article/details/gt2kpgqgoji.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.xylfe.cn/Article/details/gt2joojsgnj.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.daxiang520.top/Article/details/gt2bgkdwqsl.html

[H04] 自定义异常类型
来源：http://dali.gogol.net.cn/Article/details/gt2niwdshgn.html

Py:   class MyError(Exception): pass
来源：http://dali.aibaodan.cn/Article/details/gt2dduxdfvv.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.meibo888.top/Article/details/gt2mdpmeemv.html

JS:   class MyError extends Error {}
来源：http://dali.shzxlz.cn/Article/details/gt2mdrsssag.html

TS:   class MyError extends Error {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2ouuwjetb.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zycfv.cn/Article/details/gt2mndiezxr.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhoulong.xyz/Article/details/gt2qdzwkrgt.html

Ruby: class MyError < StandardError; end
来源：http://dali.pycfn.com/Article/details/gt2vdtmstsu.html

C#:   class MyException : Exception {}
来源：http://dali.havefunace.top/Article/details/gt2payfnokr.html

[H05] 捕获特定类型
来源：http://dali.birdmap.top/Article/details/gt2btplcvdc.html

Py:   except ValueError as e:
来源：http://dali.nanxuanxn.top/Article/details/gt2wbbwgikp.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.daria6918.cn/Article/details/gt2cuhmijmi.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2zqzvnzbb.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yj202588.top/Article/details/gt2mevhwmjq.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yuxming.cn/Article/details/gt2mxygkypv.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhengqikj.top/Article/details/gt2dmtgxysh.html

Ruby: rescue ArgumentError => e
来源：http://dali.svipenyu.cn/Article/details/gt2xbjuyrgm.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zycfv.cn/Article/details/gt2wdivksqt.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hnqzz.top/Article/details/gt2wbxsjcfw.html

Py:   value = d.get("k") or default
来源：http://dali.sufxvd.cn/Article/details/gt2hxvmowhh.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.kuanghao11.cn/Article/details/gt2hssjhnho.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.fzhhl.top/Article/details/gt2nyiihlzb.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.cheryme.top/Article/details/gt2iyrtkmrt.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.bjfxy.top/Article/details/gt2yhdnsvte.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cucudq.cn/Article/details/gt2rjkgxuhf.html

Ruby: d&.dig(:a, :b)
来源：http://dali.fzhhl.top/Article/details/gt2kvobmkdx.html

C#:   obj?.A?.B ?? default
来源：http://dali.snrcjt.cn/Article/details/gt2zojmxalg.html

[H07] 断言
来源：http://dali.dashuyun.cn/Article/details/gt2ffrssryz.html

Py:   assert x > 0, "必须为正"
来源：http://dali.nwbrower.top/Article/details/gt2yycoysvl.html

PHP:  assert($x > 0);
来源：http://dali.hnxiangtu.top/Article/details/gt2kcukqnlg.html

JS:   console.assert(x > 0);
来源：http://dali.yangfankeji.com/Article/details/gt2eainvule.html

TS:   console.assert(x > 0);
来源：http://dali.jiagoushi.top/Article/details/gt2uohzpjsh.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hfpthk.cn/Article/details/gt2xevoqfhu.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pefhljvu.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ehwqpu.com/Article/details/gt2mcrcizca.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xinyue.icu/Article/details/gt2ezxbhfgj.html

[H08] 获取错误信息与堆栈
来源：http://dali.jlsjyb.cn/Article/details/gt2sxzuozdy.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.sweek.top/Article/details/gt2fnxkqdlk.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hnqzz.top/Article/details/gt2tqqbfiqy.html

JS:   e.message;  e.stack
来源：http://dali.smart0.xyz/Article/details/gt2hbczmvjv.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.svipenyu.cn/Article/details/gt2vkkmzqmo.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zdqjudy.top/Article/details/gt2fwlsyzkb.html

Go:   err.Error()
来源：http://dali.svipenyu.cn/Article/details/gt2nwveewcp.html

Ruby: e.message;  e.backtrace
来源：http://dali.sufxvd.cn/Article/details/gt2zjeatulj.html

C#:   e.Message;  e.StackTrace
来源：http://dali.daria6918.cn/Article/details/gt2tudkajwd.html

[H09] 带错误码的异常
来源：http://dali.tanke756.top/Article/details/gt2fdqjpttq.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hnqzz.top/Article/details/gt2mfuzqqlz.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.cashguo.top/Article/details/gt2nnkzcuxu.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zagdwtlu.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yongpay.top/Article/details/gt2zfldospj.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.redwolf501.top/Article/details/gt2etatdmyj.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2najgrsvp.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hnqzz.top/Article/details/gt2hsxlezun.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.tanke756.top/Article/details/gt2tfoafilb.html

[H10] 资源自动释放
来源：http://dali.sxryk.cn/Article/details/gt2heuxwlaz.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.cheryme.top/Article/details/gt2pzkrsltj.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xuetiantiany.cn/Article/details/gt2oqiritat.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vpfmxmmr.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tian-w.cn/Article/details/gt2ikqzdlkn.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hammf.cn/Article/details/gt2arvoidec.html

Go:   defer f.Close()
来源：http://dali.jqgufenzy.top/Article/details/gt2wulznzlo.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.gotoacloud.top/Article/details/gt2vzaorega.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gt2jbolniuh.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2lrbahgmp.html

I. 正则表达式
来源：http://dali.guannengcc.top/Article/details/gt2prvunend.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2mdeibazh.html

[I01] 判断是否匹配
来源：http://dali.kuanghao11.cn/Article/details/gt2xjtjzjcy.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.c1oappe.top/Article/details/gt2prodkits.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.dashuyun.cn/Article/details/gt2kgihpmep.html

JS:   /\d+/.test(s)
来源：http://dali.chenlongwang.top/Article/details/gt2fadrhbji.html

TS:   /\d+/.test(s)
来源：http://dali.cdnleiting.top/Article/details/gt2oumbpcat.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.shangyingyoupin.top/Article/details/gt2eouowsqf.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.cdnleiting.top/Article/details/gt2uficdzgk.html

Ruby: s.match?(/\d+/)
来源：http://dali.jinqigfzy.top/Article/details/gt2ecrgnncd.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.sysykeji.top/Article/details/gt2qkhmokrh.html

[I02] 提取所有匹配
来源：http://dali.ehwqpu.com/Article/details/gt2iedpjiub.html

Py:   re.findall(r"\d+", s)
来源：http://dali.9152youxi.cn/Article/details/gt2hrjjgsze.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.xinyue.icu/Article/details/gt2zontbonr.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yvedp.cn/Article/details/gt2fjcmwgyk.html

TS:   s.match(/\d+/g)
来源：http://dali.yuxming.cn/Article/details/gt2rdegfqad.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cucudq.cn/Article/details/gt2gapyaabz.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jqgfzy.top/Article/details/gt2xskdyrqk.html

Ruby: s.scan(/\d+/)
来源：http://dali.fzhhl.top/Article/details/gt2lfjlubpj.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.guowangkeji.top/Article/details/gt2hgnbhzev.html

[I03] 提取捕获分组
来源：http://dali.vqdsnc.cn/Article/details/gt2ngljuqsl.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.wangdashe.top/Article/details/gt2zmcwnblq.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.tian-w.cn/Article/details/gt2rerflscp.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jyoumei.cn/Article/details/gt2mvbaiabk.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xuetiantiany.cn/Article/details/gt2tdukxafl.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xinyue.icu/Article/details/gt2tymcdizh.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.bjfxy.top/Article/details/gt2zvhcnnpq.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.xziqi.cn/Article/details/gt2kfcbgazt.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hysaishi.cn/Article/details/gt2aqksnmdx.html

[I04] 正则替换
来源：http://dali.yj20258888.top/Article/details/gt2bvictdvj.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.sysykeji.top/Article/details/gt2yqhiyuwf.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.0kj1m.cn/Article/details/gt2pnorkors.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jqgufenzy.top/Article/details/gt2gkgbddaf.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ghylefqx.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.haohaochexian.top/Article/details/gt2ulhiyucw.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.birdmap.top/Article/details/gt2wuzdfthw.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.daria6918.cn/Article/details/gt2zsmucvlk.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eehpueox.html

[I05] 按正则拆分
来源：http://dali.hammf.cn/Article/details/gt2etwtrvwc.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jiagoushi.top/Article/details/gt2nfjoahpo.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hammf.cn/Article/details/gt2yyrqptyv.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.sweek.top/Article/details/gt2quyeggle.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.nanxuanxn.top/Article/details/gt2mtchyvyn.html

Java: s.split("\\s*,\\s*")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mnikhvms.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.havefunace.top/Article/details/gt2lfdckkae.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.andypj.xyz/Article/details/gt2rpmynylc.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.9152youxi.cn/Article/details/gt2vxyxiyal.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.svipenyu.cn/Article/details/gt2gdhpebwe.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jinqigufen.top/Article/details/gt2xlhatucv.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hfpthk.cn/Article/details/gt2otzftakb.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ivvv.top/Article/details/gt2lyfbrzhl.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.kuanghao11.cn/Article/details/gt2xaggbzfb.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jianghu66.top/Article/details/gt2wtdazmnn.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2upgqvlpa.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.redwolf501.top/Article/details/gt2pbbnufdd.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.tianlin.xyz/Article/details/gt2nhomtyor.html

[I07] 忽略大小写与多行模式
来源：http://dali.yuxming.cn/Article/details/gt2immwuvnv.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.daxiang520.top/Article/details/gt2prbbyidx.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jqgufenzy.top/Article/details/gt2omdhngde.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.vqdsnc.cn/Article/details/gt2nzubqise.html

TS:   /error/gim
来源：http://dali.yuanzhike.top/Article/details/gt2swjuxbrm.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.haohaochexian.top/Article/details/gt2fqjkavjd.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jinqigufen.top/Article/details/gt2parpfsyh.html

Ruby: s.scan(/error/i)
来源：http://dali.nanxuanxn.top/Article/details/gt2mucthtig.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.quarkkingdee.top/Article/details/gt2mmobgwuy.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhixingplan.top/Article/details/gt2deucbawn.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.iojbl.cn/Article/details/gt2jbavnfpq.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.cdnleiting.top/Article/details/gt2oetbwyab.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hnxiangtu.top/Article/details/gt2xffllkwq.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xinyue.icu/Article/details/gt2twhouizw.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.gaohongyu789.top/Article/details/gt2ugzkidzp.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.316326.xyz/Article/details/gt2ldwckmfw.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.sxryk.cn/Article/details/gt2avppnjuq.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.gzhubu.top/Article/details/gt2kwywqkdq.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2uqazlplh.html

J. 日期与时间
来源：http://dali.nwbrower.top/Article/details/gt2jyykebsl.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2fldqxetl.html

[J01] 获取当前时间
来源：http://dali.bjfxy.top/Article/details/gt2uvqmoegb.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zycfv.cn/Article/details/gt2rvkeezcr.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.wangdashe.top/Article/details/gt2sqsgddzo.html

JS:   new Date();  Date.now()
来源：http://dali.0kj1m.cn/Article/details/gt2fhxphbwd.html

TS:   new Date();  Date.now()
来源：http://dali.aibaodan.cn/Article/details/gt2motjbapr.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.chenjidiqi.icu/Article/details/gt2xritpgim.html

Go:   time.Now()
来源：http://dali.yj20258.top/Article/details/gt2yxrirtsl.html

Ruby: Time.now
来源：http://dali.aibaodan.cn/Article/details/gt2xrlkmodz.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.haohaochexian.top/Article/details/gt2bmyzbvvq.html

[J02] 格式化输出
来源：http://dali.nanxinkj.top/Article/details/gt2pbjprbrl.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.9152youxi.cn/Article/details/gt2lssehxre.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jianghu66.top/Article/details/gt2fvoofhrz.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.vqdsnc.cn/Article/details/gt2iukzqqro.html

TS:   d.toISOString()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ggqzfvyk.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aaulfmcz.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.wangshuangyany.cn/Article/details/gt2rlljdcnd.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ehwqpu.com/Article/details/gt2iksznzan.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.gzhubu.top/Article/details/gt2jymbafnr.html

[J03] 字符串解析为日期
来源：http://dali.nwbrower.top/Article/details/gt2zhgvhfrz.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhijiandao.cn/Article/details/gt2xblxdcos.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yj202588.top/Article/details/gt2vckzqvib.html

JS:   new Date("2024-01-02")
来源：http://dali.andypj.xyz/Article/details/gt2thpkgdri.html

TS:   new Date("2024-01-02")
来源：http://dali.daria6918.cn/Article/details/gt2hmobqsmk.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.gogol.net.cn/Article/details/gt2wuwqjnyp.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hnqzz.top/Article/details/gt2kcbxkmux.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.cheryme.top/Article/details/gt2jtlwpukj.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.gogol.net.cn/Article/details/gt2uqpqdojx.html

[J04] 时间戳与日期互转
来源：http://dali.pycfn.com/Article/details/gt2idhrjklv.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.feifeiyinyue.top/Article/details/gt2clwodvva.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.tanke756.top/Article/details/gt2mjtfifqb.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.andypj.xyz/Article/details/gt2hjvbjfgd.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.sxryk.cn/Article/details/gt2vebdavme.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jinqigufen.top/Article/details/gt2kuubqbah.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.dashuyun.cn/Article/details/gt2znixelfr.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.nwbrower.top/Article/details/gt2kpldzcdt.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yuanzhike.top/Article/details/gt2zvdugdpl.html

[J05] 时间加减（加 7 天）
来源：http://dali.jiagoushi.top/Article/details/gt2eaearzjb.html

Py:   now + timedelta(days=7)
来源：http://dali.shuidangran.top/Article/details/gt2skundxuj.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jzrjeaiv.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.nwbrower.top/Article/details/gt2rdcqcogi.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.9152youxi.cn/Article/details/gt2kbmktctd.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jlsjyb.cn/Article/details/gt2ujbskmdq.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhongyouzk.top/Article/details/gt2kobbwbrj.html

Ruby: Time.now + 7 * 86400
来源：http://dali.cdnleiting.top/Article/details/gt2nhsqchug.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ngyiwbyp.html

[J06] 计算两时间之差
来源：http://dali.andypj.xyz/Article/details/gt2dkngpmvt.html

Py:   (end - start).total_seconds()
来源：http://dali.yonumen.top/Article/details/gt2eqzusebh.html

PHP:  $end->diff($start)->days;
来源：http://dali.andypj.xyz/Article/details/gt2clvhjelm.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhoulong.xyz/Article/details/gt2dfxdiyzn.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hnqzz.top/Article/details/gt2waqzjkoo.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.hnqzz.top/Article/details/gt2gfnvnsox.html

Go:   end.Sub(start).Hours()
来源：http://dali.xziqi.cn/Article/details/gt2knhwcjzv.html

Ruby: end - start                 # 返回秒数
来源：http://dali.chenlongwang.top/Article/details/gt2ieioasoc.html

C#:   (end - start).TotalSeconds
来源：http://dali.xinyue.icu/Article/details/gt2nhmkdgkd.html

[J07] 比较两个日期
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kzaotxqq.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.xuetiantiany.cn/Article/details/gt2jxeaanou.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhijiandao.cn/Article/details/gt2qyvijipk.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhoulong.xyz/Article/details/gt2khrakxmg.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.nanxinkj.top/Article/details/gt2scullenn.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.sysykeji.top/Article/details/gt2ewokfwoo.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.quarkkingdee.top/Article/details/gt2unydpetj.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.iojbl.cn/Article/details/gt2uvyhdowf.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yj20258.top/Article/details/gt2rdacdogd.html

[J08] 提取年月日与星期
来源：http://dali.pycfn.com/Article/details/gt2wxkfhltr.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gbkvusee.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ybcxt.top/Article/details/gt2creyijzv.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.cashguo.top/Article/details/gt2myzfcymu.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2idhljwfq.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.nanxuanxn.top/Article/details/gt2xrecfotn.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yuxming.cn/Article/details/gt2axhnbsmy.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhengqikj.top/Article/details/gt2ebmjxtga.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hongshengwenyu.top/Article/details/gt2uehuzwhx.html

[J09] 时区处理
来源：http://dali.9152youxi.cn/Article/details/gt2pwgyihrg.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jianghu66.top/Article/details/gt2qhkxizoa.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jlsjyb.cn/Article/details/gt2nxtzjmvn.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj20258.top/Article/details/gt2gckliqrb.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xziqi.cn/Article/details/gt2hqqthtyh.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jianghu66.top/Article/details/gt2tjbqhorw.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ybilpxuh.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bwzdbxnb.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.snrcjt.cn/Article/details/gt2rwpembqx.html

[J10] 取今天 / 本月第一天
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vnxcbcwr.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tpyizoky.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.xziqi.cn/Article/details/gt2dliqxsiw.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hfpthk.cn/Article/details/gt2akbxtegt.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.chenlongwang.top/Article/details/gt2zgrfxsjf.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jyoumei.cn/Article/details/gt2lsdcnvxv.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.vqdsnc.cn/Article/details/gt2ztndsiwh.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xylfe.cn/Article/details/gt2tqhfrczx.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ivpjojud.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2ilgfzxhm.html

K. JSON 与序列化
来源：http://dali.zhijiandao.cn/Article/details/gt2beloefyr.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2mumzuaix.html

[K01] 对象转 JSON 字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ozmhjzmy.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hywenlv.cn/Article/details/gt2kfvbivvw.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bihpihuy.html

JS:   JSON.stringify(obj)
来源：http://dali.yvedp.cn/Article/details/gt2eslqwozm.html

TS:   JSON.stringify(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nxggqgnc.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.nwbrower.top/Article/details/gt2adpxlfwo.html

Go:   json.Marshal(obj)
来源：http://dali.aizwys.cn/Article/details/gt2fhvjruwk.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.guannengcc.top/Article/details/gt2rqxtzotn.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.gotoacloud.top/Article/details/gt2qdhqpmrr.html

[K02] JSON 字符串转对象
来源：http://dali.kuanghao11.cn/Article/details/gt2otnhvauj.html

Py:   json.loads(s)
来源：http://dali.redwolf501.top/Article/details/gt2fhuafjxg.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.aibaodan.cn/Article/details/gt2pkrtpfzc.html

JS:   JSON.parse(s)
来源：http://dali.yangfankeji.com/Article/details/gt2lanfisqx.html

TS:   JSON.parse(s)
来源：http://dali.yj20258.top/Article/details/gt2oleoavqb.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.gaohongyu789.top/Article/details/gt2eqlxqjoz.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gt2npjjutcm.html

Ruby: JSON.parse(s)
来源：http://dali.gotoacloud.top/Article/details/gt2esuzkydl.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hammf.cn/Article/details/gt2tjikddef.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.wangdashe.top/Article/details/gt2unbhpxpl.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hysaishi.cn/Article/details/gt2dancibci.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hongshengwenyu.top/Article/details/gt2ibjcrxkb.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.kuanghao11.cn/Article/details/gt2ledjrbwe.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yongpay.top/Article/details/gt2zvkmzlxx.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.cdnleiting.top/Article/details/gt2vcmrhdxd.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.xuanzx.com/Article/details/gt2kpfgzbok.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hammf.cn/Article/details/gt2sfiqmeth.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hammf.cn/Article/details/gt2sutzylhv.html

[K04] 读取 JSON 文件
来源：http://dali.jyoumei.cn/Article/details/gt2chrdlxmd.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.cheryme.top/Article/details/gt2ntdfjikr.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.feifeiyinyue.top/Article/details/gt2uwdzbgug.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2twfuetlo.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cheryme.top/Article/details/gt2emmxdvdt.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.shangyingyoupin.top/Article/details/gt2zmmgrfzi.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.xylfe.cn/Article/details/gt2lduuqgay.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.iojbl.cn/Article/details/gt2ugzlnkde.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yongpay.top/Article/details/gt2ekwlhzpb.html

[K05] 深拷贝对象
来源：http://dali.guannengcc.top/Article/details/gt2vouwdgot.html

Py:   copy.deepcopy(obj)
来源：http://dali.gaohongyu789.top/Article/details/gt2hoavomrs.html

PHP:  unserialize(serialize($obj));
来源：http://dali.sysykeji.top/Article/details/gt2mwpazlod.html

JS:   structuredClone(obj)
来源：http://dali.hnxiangtu.top/Article/details/gt2ougpitng.html

TS:   structuredClone(obj)
来源：http://dali.meibo888.top/Article/details/gt2ecpuxbyo.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2muuyipqs.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jyoumei.cn/Article/details/gt2ftytsyva.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.ivvv.top/Article/details/gt2elykdcct.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.cucudq.cn/Article/details/gt2juxxxsmc.html

[K06] 解析 URL 查询串
来源：http://dali.guowangkeji.top/Article/details/gt2ubsfkzsn.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.vqdsnc.cn/Article/details/gt2wdwybmnb.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yvedp.cn/Article/details/gt2zzptwocm.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.daria6918.cn/Article/details/gt2kxzmpdhy.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.mhx1999.top/Article/details/gt2ssivmulm.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.smart0.xyz/Article/details/gt2imsintul.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.daria6918.cn/Article/details/gt2raugkbxi.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.ehwqpu.com/Article/details/gt2hfelksmb.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hnxiangtu.top/Article/details/gt2rbzbiggk.html

[K07] 进制转换
来源：http://dali.yvedp.cn/Article/details/gt2ddtburnk.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.fengsongda.top/Article/details/gt2qbrfmsln.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ryxyeyrm.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxkvrmcd.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.shangyingyoupin.top/Article/details/gt2tcqstjik.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ybcxt.top/Article/details/gt2feprcwcc.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.havefunace.top/Article/details/gt2imfopunn.html


<!-- 参考信息 -->