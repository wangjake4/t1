代发 wailian999

C#:   throw new ArgumentException("错误信息");
来源：http://dali.shanyushiyangtech.top/Article/details/gtxuyhuqqi.html

[H04] 自定义异常类型
来源：http://dali.hnqzz.top/Article/details/gtyclbesnx.html

Py:   class MyError(Exception): pass
来源：http://dali.hammf.cn/Article/details/gtmrlexcin.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.chenjidiqi.icu/Article/details/gtaeqwawdj.html

JS:   class MyError extends Error {}
来源：http://dali.jinqigfzy.top/Article/details/gttvytfjvc.html

TS:   class MyError extends Error {}
来源：http://dali.nwbrower.top/Article/details/gtooskqoqa.html

Java: class MyException extends RuntimeException {}
来源：http://dali.gogol.net.cn/Article/details/gtvinhqnjg.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.shanyushiyangtech.top/Article/details/gtkhanddcg.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gtspocrovy.html

C#:   class MyException : Exception {}
来源：http://dali.316326.xyz/Article/details/gthvjncpme.html

[H05] 捕获特定类型
来源：http://dali.dianchejie.cn/Article/details/gtclsvxcxs.html

Py:   except ValueError as e:
来源：http://dali.svipenyu.cn/Article/details/gtpivxoezg.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.sweek.top/Article/details/gtqathvijs.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.tian-w.cn/Article/details/gttnccmwjs.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yongpay.top/Article/details/gtgirvspqt.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.bjfxy.top/Article/details/gtsbxvjxeq.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.guannengcc.top/Article/details/gttamycmlm.html

Ruby: rescue ArgumentError => e
来源：http://dali.hnqzz.top/Article/details/gtttqmwtvq.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yj20258.top/Article/details/gtfqdqjwzd.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jyoumei.cn/Article/details/gtwzawzhfq.html

Py:   value = d.get("k") or default
来源：http://dali.kuanghao11.cn/Article/details/gttltwdhfe.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.nanxinkj.top/Article/details/gtuvcedinv.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.xuetiantiany.cn/Article/details/gtzhptqzjg.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.wangdashe.top/Article/details/gtphxqodrd.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.daria6918.cn/Article/details/gtfukdocpw.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cdnleiting.top/Article/details/gtwcsapbme.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hongshengwenyu.top/Article/details/gtplualtcn.html

C#:   obj?.A?.B ?? default
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpglndsqz.html

[H07] 断言
来源：http://dali.tian-w.cn/Article/details/gtusutfzkl.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ivvv.top/Article/details/gtqfhvaxzj.html

PHP:  assert($x > 0);
来源：http://dali.yj20258.top/Article/details/gtixkmpbqu.html

JS:   console.assert(x > 0);
来源：http://dali.wangshuangyany.cn/Article/details/gtusfnjirq.html

TS:   console.assert(x > 0);
来源：http://dali.jinqigufen.top/Article/details/gttyqtknet.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhoulong.xyz/Article/details/gtgankfwjh.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jianghu66.top/Article/details/gtdgirmfly.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.0kj1m.cn/Article/details/gtfwjzztdg.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hnxiangtu.top/Article/details/gtbugoxvqz.html

[H08] 获取错误信息与堆栈
来源：http://dali.shangyingyoupin.top/Article/details/gtilfoiwow.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.xinyue.icu/Article/details/gtydzcqhvs.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhoulong.xyz/Article/details/gtxzgtyhix.html

JS:   e.message;  e.stack
来源：http://dali.sxryk.cn/Article/details/gtjaajxbbp.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.nwbrower.top/Article/details/gtrrexvhhh.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhiwuduotai.top/Article/details/gtjdztrzlj.html

Go:   err.Error()
来源：http://dali.snrcjt.cn/Article/details/gtzuetjbzv.html

Ruby: e.message;  e.backtrace
来源：http://dali.jinqigufen.top/Article/details/gtcmiazcwy.html

C#:   e.Message;  e.StackTrace
来源：http://dali.bjfxy.top/Article/details/gtjpegcldf.html

[H09] 带错误码的异常
来源：http://dali.hammf.cn/Article/details/gtnvaxffee.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhixingplan.top/Article/details/gtyltexeat.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jinqigfzy.top/Article/details/gtpoprcomi.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhiwuduotai.top/Article/details/gtpxvydxtt.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.nanxuanxn.top/Article/details/gtlnnmhjhx.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.xinyue.icu/Article/details/gtepkmcbip.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkeciixfa.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.sysykeji.top/Article/details/gtpcjkqrvo.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yueranfly.top/Article/details/gtwmmwfbfm.html

[H10] 资源自动释放
来源：http://dali.xziqi.cn/Article/details/gtgpxrtlvh.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xuanzx.com/Article/details/gtscggewlm.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jiagoushi.top/Article/details/gtezxfuexh.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinghuilouyu.cn/Article/details/gttegvtzvz.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yongpay.top/Article/details/gtmmvknuru.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yanxiufei.cn/Article/details/gtymzvfnca.html

Go:   defer f.Close()
来源：http://dali.ybcxt.top/Article/details/gtiwezzijc.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.dianchejie.cn/Article/details/gttjifdgtt.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.iojbl.cn/Article/details/gtinrywrhc.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtmqnvnike.html

I. 正则表达式
来源：http://dali.jinqigfzy.top/Article/details/gtzszwfexy.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtwpizbuqy.html

[I01] 判断是否匹配
来源：http://dali.zhengqikj.top/Article/details/gtuqjlnedi.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hywenlv.cn/Article/details/gtsqcdbhdl.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.guowangkeji.top/Article/details/gtybckggma.html

JS:   /\d+/.test(s)
来源：http://dali.jlsjyb.cn/Article/details/gtxldfhblq.html

TS:   /\d+/.test(s)
来源：http://dali.cashguo.top/Article/details/gtajrbichy.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.redwolf501.top/Article/details/gtxsxquaij.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.vqdsnc.cn/Article/details/gtyvphstrx.html

Ruby: s.match?(/\d+/)
来源：http://dali.shzxlz.cn/Article/details/gtdrznxhwg.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xuanzx.com/Article/details/gtsggnrhnz.html

[I02] 提取所有匹配
来源：http://dali.vqdsnc.cn/Article/details/gtiwaqqcww.html

Py:   re.findall(r"\d+", s)
来源：http://dali.havefunace.top/Article/details/gtglzzekfr.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.ydzc1.top/Article/details/gtoxrfrqqc.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.snrcjt.cn/Article/details/gttegvjqrj.html

TS:   s.match(/\d+/g)
来源：http://dali.yj202588.top/Article/details/gtqfqcolvi.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.shuidangran.top/Article/details/gtofhjtrhw.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.xuanzx.com/Article/details/gtelrnzcdz.html

Ruby: s.scan(/\d+/)
来源：http://dali.jinqigfzy.top/Article/details/gtrhnohcfr.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yj202588.top/Article/details/gtyqwovjgq.html

[I03] 提取捕获分组
来源：http://dali.jianghu66.top/Article/details/gtrnfpuvrm.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.fengsongda.top/Article/details/gtawklamug.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.nwbrower.top/Article/details/gtpejjilrq.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.wangshuangyany.cn/Article/details/gtcbebmlkm.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.shanyushiyangtech.top/Article/details/gtehoawuhk.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hfpthk.cn/Article/details/gtrqklbchj.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjouihchn.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.vqdsnc.cn/Article/details/gttxzmffdm.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.chenlongwang.top/Article/details/gtvnaeefzp.html

[I04] 正则替换
来源：http://dali.hammf.cn/Article/details/gtoefuhrjf.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.cqqwz.cn/Article/details/gtwqzhghcm.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yj20258.top/Article/details/gtsukvkkgb.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yvedp.cn/Article/details/gtlyyxzouk.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jinqigfzy.top/Article/details/gtcgmewuas.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.fzhhl.top/Article/details/gtmkcrnkin.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yj20258.top/Article/details/gtlbggocgh.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xinyue.icu/Article/details/gtxamfyglh.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.haohaochexian.top/Article/details/gtstkukozy.html

[I05] 按正则拆分
来源：http://dali.zhengqikj.top/Article/details/gtegnlwkgq.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.shzxlz.cn/Article/details/gttbvxxnlw.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhengqikj.top/Article/details/gtghjawool.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.bjfxy.top/Article/details/gtwxqxdquq.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhengqikj.top/Article/details/gtcqnvldqm.html

Java: s.split("\\s*,\\s*")
来源：http://dali.tian-w.cn/Article/details/gtmshifztd.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtctwvemgw.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xuanzx.com/Article/details/gtswipnmhi.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcrrjabzi.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.bjfxy.top/Article/details/gtgyupavxh.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.dashuyun.cn/Article/details/gtvbnzjrvf.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.sysykeji.top/Article/details/gtsivzldvp.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tanke756.top/Article/details/gtbuascrvc.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenzaomai.com/Article/details/gtflqbbssw.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhoulong.xyz/Article/details/gtemlnvnop.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.c1oappe.top/Article/details/gtkhcsrqqy.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.quarkkingdee.top/Article/details/gtgihwvzby.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ybcxt.top/Article/details/gtbsqbkmle.html

[I07] 忽略大小写与多行模式
来源：http://dali.fzhhl.top/Article/details/gtcggvviyi.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.nanxinkj.top/Article/details/gtgcoqygpz.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.shzxlz.cn/Article/details/gtkdgdcunz.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jyoumei.cn/Article/details/gtwscxfmqv.html

TS:   /error/gim
来源：http://dali.aibaodan.cn/Article/details/gtaiwxfyyl.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jqgfzy.top/Article/details/gtoitnriue.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.svipenyu.cn/Article/details/gtpozquocr.html

Ruby: s.scan(/error/i)
来源：http://dali.nanxuanxn.top/Article/details/gtzsyzocuh.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.birdmap.top/Article/details/gtthnrcsen.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.xylfe.cn/Article/details/gtaupyshom.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jqgfzy.top/Article/details/gtxvyhkxiy.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jinqigufen.top/Article/details/gtrzwaolsh.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.smart0.xyz/Article/details/gtosclfuzx.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinqigufen.top/Article/details/gtamzjfhlt.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.gogol.net.cn/Article/details/gtlludpmzu.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.nwbrower.top/Article/details/gtzlltreru.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.fengsongda.top/Article/details/gtjaeskwkx.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.daria6918.cn/Article/details/gttccboplq.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtziqnpzpb.html

J. 日期与时间
来源：http://dali.mhx1999.top/Article/details/gtwxhykwxl.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtwpfqyrym.html

[J01] 获取当前时间
来源：http://dali.ybcxt.top/Article/details/gtdecbzxno.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.smart0.xyz/Article/details/gtfqgoggsz.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.ehwqpu.com/Article/details/gtljvedqum.html

JS:   new Date();  Date.now()
来源：http://dali.yuanzhike.top/Article/details/gtwvxskqof.html

TS:   new Date();  Date.now()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkpzozfgx.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.guowangkeji.top/Article/details/gtppwzlshy.html

Go:   time.Now()
来源：http://dali.ivvv.top/Article/details/gtfufvyghi.html

Ruby: Time.now
来源：http://dali.yueranfly.top/Article/details/gtwildwada.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.cashguo.top/Article/details/gtitccmtro.html

[J02] 格式化输出
来源：http://dali.pycfn.com/Article/details/gtrrhgytal.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.316326.xyz/Article/details/gtbgarvwcy.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jqgufenzy.top/Article/details/gtlaayftre.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.bjfxy.top/Article/details/gtgyrlmotn.html

TS:   d.toISOString()
来源：http://dali.birdmap.top/Article/details/gtguguvkbh.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.gaohongyu789.top/Article/details/gthtfjihfb.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.havefunace.top/Article/details/gtulijyyif.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jlsjyb.cn/Article/details/gtjzmjsrmy.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.cashguo.top/Article/details/gtrwwryyvh.html

[J03] 字符串解析为日期
来源：http://dali.yueranfly.top/Article/details/gtqlfytslx.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.c1oappe.top/Article/details/gtbytcwrkj.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhengqikj.top/Article/details/gtkzelkxhy.html

JS:   new Date("2024-01-02")
来源：http://dali.yangfankeji.com/Article/details/gtaxemivhy.html

TS:   new Date("2024-01-02")
来源：http://dali.sweek.top/Article/details/gtuieicpiq.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yongpay.top/Article/details/gtthoxzjmy.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.svipenyu.cn/Article/details/gtxskivzwc.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.ydzc1.top/Article/details/gtpaazmjcu.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ybcxt.top/Article/details/gtcleayhtj.html

[J04] 时间戳与日期互转
来源：http://dali.zhijiandao.cn/Article/details/gtfioeykdw.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.tianlin.xyz/Article/details/gtiarjadby.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.daria6918.cn/Article/details/gtvejpycuj.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.shangyingyoupin.top/Article/details/gtmcszldre.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jinghuilouyu.cn/Article/details/gtlzbcicky.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.cdnleiting.top/Article/details/gtpeuzkyoj.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.chenzaomai.com/Article/details/gtxeokvuxo.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.iojbl.cn/Article/details/gtmqiqsbfe.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ehwqpu.com/Article/details/gtqhrzqvim.html

[J05] 时间加减（加 7 天）
来源：http://dali.daxiang520.top/Article/details/gtdrwybway.html

Py:   now + timedelta(days=7)
来源：http://dali.yueranfly.top/Article/details/gtgaxspulz.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ydzc1.top/Article/details/gtvcavepdf.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jianghu66.top/Article/details/gtvsxeksqz.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zycfv.cn/Article/details/gtsmtqbrdu.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.aibaodan.cn/Article/details/gtzjqdjmta.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jianghu66.top/Article/details/gttefqhyaj.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yj20258.top/Article/details/gtjhcbuqrh.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.vqdsnc.cn/Article/details/gtbsrixmxs.html

[J06] 计算两时间之差
来源：http://dali.smart0.xyz/Article/details/gtxamkrhri.html

Py:   (end - start).total_seconds()
来源：http://dali.cucudq.cn/Article/details/gtkjfelheo.html

PHP:  $end->diff($start)->days;
来源：http://dali.redwolf501.top/Article/details/gtlngsfkgr.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhijiandao.cn/Article/details/gtvfzmowzm.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.sysykeji.top/Article/details/gtsmuzazpe.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jlsjyb.cn/Article/details/gttadslqrr.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhongyouzk.top/Article/details/gtahkqxsfh.html

Ruby: end - start                 # 返回秒数
来源：http://dali.sufxvd.cn/Article/details/gtwevtqomf.html

C#:   (end - start).TotalSeconds
来源：http://dali.fzhhl.top/Article/details/gtaziuaaut.html

[J07] 比较两个日期
来源：http://dali.jiagoushi.top/Article/details/gtovkosipp.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yangfankeji.com/Article/details/gtxmmgvoct.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yuxming.cn/Article/details/gtrvskkrjd.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.daria6918.cn/Article/details/gtipqzftlq.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yangfankeji.com/Article/details/gtlewtvkgq.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.shzxlz.cn/Article/details/gtchespezp.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhijiandao.cn/Article/details/gtxqftgpqr.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zycfv.cn/Article/details/gtdfaaqsva.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuvdvqqdc.html

[J08] 提取年月日与星期
来源：http://dali.jqgufenzy.top/Article/details/gtzigvwwhb.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.meibo888.top/Article/details/gtcrprwwkz.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yuxming.cn/Article/details/gtevwucbcb.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.tianlin.xyz/Article/details/gtvtipelpg.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.tianlin.xyz/Article/details/gtixrtwgll.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.chenlongwang.top/Article/details/gtmemirjzl.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.sufxvd.cn/Article/details/gtrvnjstdn.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.cucudq.cn/Article/details/gtdjupcbzm.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.nanxinkj.top/Article/details/gtujjwcwmv.html

[J09] 时区处理
来源：http://dali.zhiwuduotai.top/Article/details/gtvvgdkpvp.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.shangyingyoupin.top/Article/details/gtinveghrx.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.andypj.xyz/Article/details/gtrkfekzwp.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.0kj1m.cn/Article/details/gtrpmnkrsb.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hongshengwenyu.top/Article/details/gtgaufzirp.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.andypj.xyz/Article/details/gtlldelqpc.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.dashuyun.cn/Article/details/gtznuszdip.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.quarkkingdee.top/Article/details/gtbfuvwlap.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.aizwys.cn/Article/details/gtvkenwlhi.html

[J10] 取今天 / 本月第一天
来源：http://dali.jinghuilouyu.cn/Article/details/gtiqnocjyq.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.aizwys.cn/Article/details/gtvpocibhi.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.fzhhl.top/Article/details/gtcklnfmhw.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.meibo888.top/Article/details/gtlnbignax.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jiagoushi.top/Article/details/gtjyjsodvj.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhoulong.xyz/Article/details/gtzsvqjdpo.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.shanyushiyangtech.top/Article/details/gtrnhgvwbh.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.aizwys.cn/Article/details/gttcrzdtnd.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.tanke756.top/Article/details/gtsuztmipg.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtwvoscmiy.html

K. JSON 与序列化
来源：http://dali.yangfankeji.com/Article/details/gtgeajvsxy.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtobgissxh.html

[K01] 对象转 JSON 字符串
来源：http://dali.iojbl.cn/Article/details/gtxuxeuhrx.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.chenzaomai.com/Article/details/gtecygpigh.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jqgufenzy.top/Article/details/gtrkvvzdzn.html

JS:   JSON.stringify(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtttanoapr.html

TS:   JSON.stringify(obj)
来源：http://dali.sxryk.cn/Article/details/gtdouzbaqr.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.tianlin.xyz/Article/details/gtnbzkfibe.html

Go:   json.Marshal(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtlksifyob.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.feifeiyinyue.top/Article/details/gtrjzbvtpi.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuoozaior.html

[K02] JSON 字符串转对象
来源：http://dali.hywenlv.cn/Article/details/gtuoexbpsk.html

Py:   json.loads(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtswclifpz.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhengqikj.top/Article/details/gtqjtjfdgz.html

JS:   JSON.parse(s)
来源：http://dali.xziqi.cn/Article/details/gtpmnylsns.html

TS:   JSON.parse(s)
来源：http://dali.shzxlz.cn/Article/details/gtweyjyyin.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.gaohongyu789.top/Article/details/gtgjfzlqwg.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzfkjcojt.html

Ruby: JSON.parse(s)
来源：http://dali.gaohongyu789.top/Article/details/gtrzoigjdx.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ydzc1.top/Article/details/gticpjtmmj.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.c1oappe.top/Article/details/gtnjevwnts.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhixingplan.top/Article/details/gttyhwiosh.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hammf.cn/Article/details/gtwzyxcuvd.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.daxiang520.top/Article/details/gtuqagqmha.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yuxming.cn/Article/details/gtmqelsvcf.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.meibo888.top/Article/details/gtbphumnqg.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.gogol.net.cn/Article/details/gtqxnhzahk.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.shuidangran.top/Article/details/gtsyhacsdw.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.guannengcc.top/Article/details/gtlszqqmll.html

[K04] 读取 JSON 文件
来源：http://dali.zhoulong.xyz/Article/details/gtewxupdak.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.sweek.top/Article/details/gtsiqufnhc.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.shanyushiyangtech.top/Article/details/gtkgzcrkxm.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.redwolf501.top/Article/details/gtrtdrncjo.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cucudq.cn/Article/details/gtzkwpdhtm.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xuetiantiany.cn/Article/details/gtgpbywhoq.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.shangyingyoupin.top/Article/details/gturomftug.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsybjgjhv.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.guowangkeji.top/Article/details/gtnloiuxbc.html

[K05] 深拷贝对象
来源：http://dali.shangyingyoupin.top/Article/details/gthmcthqpf.html

Py:   copy.deepcopy(obj)
来源：http://dali.pycfn.com/Article/details/gtirocmwts.html

PHP:  unserialize(serialize($obj));
来源：http://dali.shzxlz.cn/Article/details/gtgwcuevyc.html

JS:   structuredClone(obj)
来源：http://dali.zhixingplan.top/Article/details/gtamoidmer.html

TS:   structuredClone(obj)
来源：http://dali.birdmap.top/Article/details/gtlzygqyng.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhixingplan.top/Article/details/gtaeignjnz.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.snrcjt.cn/Article/details/gtjgfdyevv.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.birdmap.top/Article/details/gtiafrzkgk.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.ivvv.top/Article/details/gtodmkqtnu.html

[K06] 解析 URL 查询串
来源：http://dali.jinqigufen.top/Article/details/gtbxlawsye.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.gotoacloud.top/Article/details/gtorzniosz.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.nwbrower.top/Article/details/gtcscnqeal.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.snrcjt.cn/Article/details/gtojtwgkii.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.tian-w.cn/Article/details/gtamvxcjad.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.xylfe.cn/Article/details/gtfnopgzed.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.c1oappe.top/Article/details/gtalriquru.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yuxming.cn/Article/details/gtlqhdlypx.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.snrcjt.cn/Article/details/gtmwyhocwa.html

[K07] 进制转换
来源：http://dali.jiagoushi.top/Article/details/gtnhltzcyx.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.havefunace.top/Article/details/gtjlfpccsx.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.xuanzx.com/Article/details/gtjwnwmvsy.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.sysykeji.top/Article/details/gtpohfpley.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhengqikj.top/Article/details/gtqxdvmdnj.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.andypj.xyz/Article/details/gtwozloplr.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ybcxt.top/Article/details/gtwbvhwwop.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhijiandao.cn/Article/details/gtfgbuwrdn.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.dianchejie.cn/Article/details/gtydnfuqle.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ydzc1.top/Article/details/gtwcwuxvtc.html

Py:   pickle.dumps(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrppdvski.html


<!-- 参考信息 -->