代发 wailian999

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yanxiufei.cn/Article/details/gt2bbxrnovt.html

[Q60] 取上一行 / 下一行
来源：http://dali.shzxlz.cn/Article/details/gt2qjuumaco.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xphatmyv.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ujyxmpud.html

[Q61] 移动平均
来源：http://dali.mhx1999.top/Article/details/gt2ymemoyem.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.dashuyun.cn/Article/details/gt2fmocuuma.html

[Q62] 分组占比
来源：http://dali.xuanzx.com/Article/details/gt2jsywhhep.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.aibaodan.cn/Article/details/gt2pzsrwwyy.html

[Q63] 开启事务
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ljqpewnc.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.shuidangran.top/Article/details/gt2icazhmsu.html

[Q64] 提交事务
来源：http://dali.smart0.xyz/Article/details/gt2jrrrhaiu.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2wtuolatf.html

[Q65] 回滚事务
来源：http://dali.dianchejie.cn/Article/details/gt2ikawxokg.html

ROLLBACK;
来源：http://dali.yanxiufei.cn/Article/details/gt2cehiazry.html

[Q66] 行锁查询
来源：http://dali.jlsjyb.cn/Article/details/gt2ckogthuh.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.ydzc1.top/Article/details/gt2jsystjlj.html

[Q67] 设置隔离级别
来源：http://dali.xylfe.cn/Article/details/gt2xdodjzzb.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.shzxlz.cn/Article/details/gt2panijuut.html

[Q68] 保存点
来源：http://dali.yj20258888.top/Article/details/gt2tvwfrdoe.html

SAVEPOINT sp1;
来源：http://dali.yj202588.top/Article/details/gt2nmuuavrc.html

ROLLBACK TO sp1;
来源：http://dali.fengsongda.top/Article/details/gt2zftvxths.html

[Q69] 查看执行计划
来源：http://dali.316326.xyz/Article/details/gt2ecxnijck.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.cashguo.top/Article/details/gt2huldfnpp.html

[Q70] 更新统计信息
来源：http://dali.yuanzhike.top/Article/details/gt2xycoapwy.html

ANALYZE TABLE users;
来源：http://dali.nanxinkj.top/Article/details/gt2zrdupewy.html

[Q71] 查看建表语句
来源：http://dali.hongshengwenyu.top/Article/details/gt2lajtdqip.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.xylfe.cn/Article/details/gt2prvaizdu.html

[Q72] 查看索引
来源：http://dali.yueranfly.top/Article/details/gt2seebtrqi.html

SHOW INDEX FROM users;
来源：http://dali.zhengqikj.top/Article/details/gt2ktargbjz.html

[Q73] 查看表状态
来源：http://dali.wangdashe.top/Article/details/gt2wcvhsouj.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.tanke756.top/Article/details/gt2qiasbnox.html

[Q74] 强制使用索引
来源：http://dali.redwolf501.top/Article/details/gt2ltvatzzf.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.smart0.xyz/Article/details/gt2riujmycb.html

[Q75] 日期格式化
来源：http://dali.jinqigfzy.top/Article/details/gt2wusvbblv.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.tanke756.top/Article/details/gt2zjbuyigx.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jinqigufen.top/Article/details/gt2qmujqdpq.html

[Q76] 按天统计
来源：http://dali.yuanzhike.top/Article/details/gt2giefvvtc.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.tanke756.top/Article/details/gt2hanmqikj.html

[Q77] 时间加减
来源：http://dali.xuetiantiany.cn/Article/details/gt2ckauqsoj.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.tanke756.top/Article/details/gt2zkwbituy.html

[Q78] 当前时间
来源：http://dali.meibo888.top/Article/details/gt2epswgkoq.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.ivvv.top/Article/details/gt2cvthakav.html

[Q79] 字符串拼接
来源：http://dali.9152youxi.cn/Article/details/gt2ocqahjgb.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bmmrdcdp.html

[Q80] 字符串截取
来源：http://dali.sysykeji.top/Article/details/gt2ocrniide.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hysaishi.cn/Article/details/gt2qrtphkju.html

[Q81] 字符串替换
来源：http://dali.hywenlv.cn/Article/details/gt2dddphwht.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.haohaochexian.top/Article/details/gt2pbiufpyj.html

[Q82] 字符长度与字节长度
来源：http://dali.wangshuangyany.cn/Article/details/gt2fgkxiren.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.fengsongda.top/Article/details/gt2jorbxpam.html

[Q83] 大小写转换
来源：http://dali.xuetiantiany.cn/Article/details/gt2zvyaqtkg.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.ivvv.top/Article/details/gt2okurzzjx.html

[Q84] 去除首尾空格
来源：http://dali.sufxvd.cn/Article/details/gt2nqvwnnlw.html

SELECT TRIM(name) FROM users;
来源：http://dali.hfpthk.cn/Article/details/gt2grqwkjpt.html

[Q85] 数值取整
来源：http://dali.0kj1m.cn/Article/details/gt2enboivhz.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.daria6918.cn/Article/details/gt2sododinh.html

[Q86] 读取 JSON 字段
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cerfpxwk.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zycfv.cn/Article/details/gt2dkbpeaeq.html

[Q87] JSON 字段做条件
来源：http://dali.smart0.xyz/Article/details/gt2ebwofgfm.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hysaishi.cn/Article/details/gt2usmvuoju.html

[Q88] 行转列（条件聚合）
来源：http://dali.snrcjt.cn/Article/details/gt2lnmbsjwc.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vuszpnxo.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.ydzc1.top/Article/details/gt2hpsothbj.html

[Q89] 判断表是否存在
来源：http://dali.hfpthk.cn/Article/details/gt2kfhoqniy.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.sweek.top/Article/details/gt2zstmtqlb.html

[Q90] 生成序号列
来源：http://dali.jinqigufen.top/Article/details/gt2kmidwrjv.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.cheryme.top/Article/details/gt2oznphquv.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2dfrzsnhn.html

R. Bash 专题
来源：http://dali.daxiang520.top/Article/details/gt2qqfuvote.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2xcdkffel.html

[R01] shebang 与严格模式
来源：http://dali.ppjwa.cn/Article/details/gt2kcvhkxph.html

#!/usr/bin/env bash
来源：http://dali.vqdsnc.cn/Article/details/gt2mzhqijgl.html

set -euo pipefail
来源：http://dali.xylfe.cn/Article/details/gt2prhckylt.html

[R02] 变量赋值与使用
来源：http://dali.wangdashe.top/Article/details/gt2kkkdkkbm.html

name="Tom"; echo "$name"
来源：http://dali.jiagoushi.top/Article/details/gt2wyvzvpne.html

[R03] 只读变量
来源：http://dali.gogol.net.cn/Article/details/gt2plhnnmyi.html

readonly PI=3.14
来源：http://dali.gotoacloud.top/Article/details/gt2nwgizaqp.html

[R04] 位置参数
来源：http://dali.yj20258.top/Article/details/gt2dzwyfwmo.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hysaishi.cn/Article/details/gt2vcfvpipj.html

[R05] 参数默认值
来源：http://dali.feifeiyinyue.top/Article/details/gt2tfopulvn.html

name="${1:-default}"
来源：http://dali.316326.xyz/Article/details/gt2zyetckhm.html

[R06] 判断命令是否存在
来源：http://dali.guowangkeji.top/Article/details/gt2fxacfgqu.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.havefunace.top/Article/details/gt2oeyesorl.html

[R07] if 判断文件
来源：http://dali.jlsjyb.cn/Article/details/gt2ghqccwfy.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.fengsongda.top/Article/details/gt2muambkpx.html

[R08] 数值比较
来源：http://dali.yanxiufei.cn/Article/details/gt2lvxdvxfy.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.quarkkingdee.top/Article/details/gt2mfgmhudn.html

[R09] 字符串比较
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rwdpavzo.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.dashuyun.cn/Article/details/gt2dftnymrd.html

[R10] 正则匹配
来源：http://dali.zhixingplan.top/Article/details/gt2uirapvhy.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.xuanzx.com/Article/details/gt2qfzftujs.html

[R11] case 多分支
来源：http://dali.jinqigufen.top/Article/details/gt2lwbhgifw.html

case "$1" in
来源：http://dali.pycfn.com/Article/details/gt2bljmjoap.html

start) echo "启动" ;;
来源：http://dali.wangdashe.top/Article/details/gt2skbnkzre.html

stop)  echo "停止" ;;
来源：http://dali.tanke756.top/Article/details/gt2wcfzcjfm.html

*)     echo "未知命令" ;;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2adkprjbk.html

esac
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iyvmjklx.html

[R12] for 遍历文件
来源：http://dali.sxryk.cn/Article/details/gt2ultylzfx.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jblmrgtq.html

[R13] for 计数循环
来源：http://dali.jqgfzy.top/Article/details/gt2tmlvmjfw.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jlsjyb.cn/Article/details/gt2xnjxydwg.html

[R14] C 风格 for
来源：http://dali.hfpthk.cn/Article/details/gt2faafmwdi.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yueranfly.top/Article/details/gt2hgpjlrrr.html

[R15] while 逐行读文件
来源：http://dali.sweek.top/Article/details/gt2qvhoofhb.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhiwuduotai.top/Article/details/gt2lxjgxnmf.html

[R16] until 等待条件
来源：http://dali.nanxinkj.top/Article/details/gt2tyigstpi.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.tianlin.xyz/Article/details/gt2mfkuyjjp.html

[R17] 数组定义与取值
来源：http://dali.zhongyouzk.top/Article/details/gt2tgigvxjn.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dklpwcla.html

[R18] 遍历数组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nuashltp.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.nwbrower.top/Article/details/gt2hwbnallm.html

[R19] 数组长度
来源：http://dali.dashuyun.cn/Article/details/gt2urcsoxkd.html

echo "${#arr[@]}"
来源：http://dali.jqgufenzy.top/Article/details/gt2bzmmzaav.html

[R20] 关联数组（字典）
来源：http://dali.shangyingyoupin.top/Article/details/gt2ilvfnram.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.hongshengwenyu.top/Article/details/gt2zgdrisky.html

[R21] 字符串长度
来源：http://dali.quarkkingdee.top/Article/details/gt2ukwrlyer.html

echo "${#s}"
来源：http://dali.snrcjt.cn/Article/details/gt2amfjogpb.html

[R22] 截取子串
来源：http://dali.shzxlz.cn/Article/details/gt2srrgunlz.html

echo "${s:0:5}"
来源：http://dali.guowangkeji.top/Article/details/gt2vqjwztfg.html

[R23] 字符串替换
来源：http://dali.mhx1999.top/Article/details/gt2altndorc.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.guowangkeji.top/Article/details/gt2zrpygxcw.html

[R24] 大小写转换
来源：http://dali.jianghu66.top/Article/details/gt2haxrorvp.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.chenzaomai.com/Article/details/gt2ikuzbctk.html

[R25] 去后缀 / 去前缀
来源：http://dali.jinqigfzy.top/Article/details/gt2slowvnbx.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.haohaochexian.top/Article/details/gt2chonpmyx.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lmptobgp.html

now=$(date +%F); echo "$now"
来源：http://dali.jiagoushi.top/Article/details/gt2udpcpyby.html

[R27] 算术展开
来源：http://dali.pengpengdd.cyou/Article/details/gt2dvdlicql.html

echo $((1 + 2 * 3))
来源：http://dali.birdmap.top/Article/details/gt2ivqudzik.html

[R28] 浮点运算
来源：http://dali.vqdsnc.cn/Article/details/gt2etpyxjqc.html

echo "scale=2; 10/3" | bc
来源：http://dali.sysykeji.top/Article/details/gt2enbbwnww.html

[R29] 定义函数
来源：http://dali.jiagoushi.top/Article/details/gt2wqcelnqg.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yueranfly.top/Article/details/gt2gcflkoyv.html

[R30] 函数返回状态码
来源：http://dali.jianghu66.top/Article/details/gt2zflolepj.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.tanke756.top/Article/details/gt2yiqebndc.html

[R31] 局部变量
来源：http://dali.xinyue.icu/Article/details/gt2zpvlvhnk.html

f() { local x=1; echo "$x"; }
来源：http://dali.chenzaomai.com/Article/details/gt2lcfkafoq.html

[R32] 参数个数校验
来源：http://dali.zycfv.cn/Article/details/gt2dlzrwtee.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.nwbrower.top/Article/details/gt2qzuoykjm.html

[R33] 捕获错误并提示行号
来源：http://dali.ydzc1.top/Article/details/gt2uybcbhvk.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hongshengwenyu.top/Article/details/gt2wrmvezrv.html

[R34] 退出时清理
来源：http://dali.hnxiangtu.top/Article/details/gt2wwmprfjx.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.sysykeji.top/Article/details/gt2cwcgvoed.html

[R35] 后台执行并等待
来源：http://dali.shuidangran.top/Article/details/gt2ivlfltkz.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.mhx1999.top/Article/details/gt2yaysgbal.html

[R36] 并发执行多个任务
来源：http://dali.gaohongyu789.top/Article/details/gt2pjbyyygm.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.cqqwz.cn/Article/details/gt2umxscmjk.html

[R37] 把输出赋给变量
来源：http://dali.hnqzz.top/Article/details/gt2bsxdcybf.html

files=$(ls -1)
来源：http://dali.daria6918.cn/Article/details/gt2ihfnqdsh.html

[R38] 管道串联
来源：http://dali.xziqi.cn/Article/details/gt2lgscjife.html

cat a.txt | grep -i error | wc -l
来源：http://dali.sxryk.cn/Article/details/gt2ksnccfst.html

[R39] 重定向标准输出与错误
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hajfzepr.html

cmd > out.log 2>&1
来源：http://dali.yangfankeji.com/Article/details/gt2tsdaatyc.html

[R40] 追加写日志
来源：http://dali.c1oappe.top/Article/details/gt2ilmwrfaa.html

echo "log" >> out.log
来源：http://dali.haohaochexian.top/Article/details/gt2ysoudmat.html

[R41] 丢弃输出
来源：http://dali.redwolf501.top/Article/details/gt2noatqzro.html

cmd >/dev/null 2>&1
来源：http://dali.fengsongda.top/Article/details/gt2fpiwqebu.html

[R42] 输入重定向
来源：http://dali.svipenyu.cn/Article/details/gt2cktmnzuc.html

wc -l < a.txt
来源：http://dali.ivvv.top/Article/details/gt2musnnmlf.html

[R43] 按名字查找文件
来源：http://dali.haohaochexian.top/Article/details/gt2bitmwmcv.html

find . -name "*.log" -type f
来源：http://dali.xylfe.cn/Article/details/gt2qbtwwjlh.html

[R44] 按修改时间查找
来源：http://dali.yongpay.top/Article/details/gt2foozdjsg.html

find . -mtime -7 -type f
来源：http://dali.fengsongda.top/Article/details/gt2byurstmk.html

[R45] 批量删除
来源：http://dali.nwbrower.top/Article/details/gt2rraddvgu.html

find . -name "*.tmp" -delete
来源：http://dali.jinghuilouyu.cn/Article/details/gt2igysfhxq.html

[R46] 递归替换文件内容
来源：http://dali.xuanzx.com/Article/details/gt2ryjelvdk.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.andypj.xyz/Article/details/gt2jskifeld.html

[R47] sed 单行替换
来源：http://dali.ivvv.top/Article/details/gt2ujykegjo.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.xuetiantiany.cn/Article/details/gt2oqkhuzwf.html

[R48] awk 取指定列
来源：http://dali.yj20258888.top/Article/details/gt2jumhllxp.html

awk '{print $1, $3}' a.txt
来源：http://dali.vqdsnc.cn/Article/details/gt2jrkvdryy.html

[R49] awk 带条件
来源：http://dali.feifeiyinyue.top/Article/details/gt2yfqouxsj.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yanxiufei.cn/Article/details/gt2ihwipygr.html

[R50] awk 求和
来源：http://dali.jianghu66.top/Article/details/gt2tlxecnpx.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.sxryk.cn/Article/details/gt2yyyblbpk.html

[R51] 排序去重取前几
来源：http://dali.chenzaomai.com/Article/details/gt2svfssvxr.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.dianchejie.cn/Article/details/gt2gabljrns.html

[R52] 统计行数
来源：http://dali.cheryme.top/Article/details/gt2qejtileb.html

wc -l a.txt
来源：http://dali.haohaochexian.top/Article/details/gt2mldzyttk.html

[R53] 查看文件头与实时尾
来源：http://dali.kuanghao11.cn/Article/details/gt2jtrkfets.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jianghu66.top/Article/details/gt2ixzdjvqg.html

[R54] 比较两个文件
来源：http://dali.yongpay.top/Article/details/gt2hvxgvges.html

diff a.txt b.txt
来源：http://dali.xylfe.cn/Article/details/gt2nkirrjgt.html

[R55] 压缩与解压
来源：http://dali.hfpthk.cn/Article/details/gt2kwphqodh.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yueranfly.top/Article/details/gt2kaalxcqi.html

[R56] 远程拷贝
来源：http://dali.ppjwa.cn/Article/details/gt2ymydhzqr.html

scp file user@host:/path/
来源：http://dali.gzhubu.top/Article/details/gt2iwaeczfn.html

[R57] 远程执行命令
来源：http://dali.cucudq.cn/Article/details/gt2pmxbojwd.html

ssh user@host 'uptime'
来源：http://dali.yueranfly.top/Article/details/gt2cipmkkmm.html

[R58] 下载文件
来源：http://dali.vqdsnc.cn/Article/details/gt2qndoagdf.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.daxiang520.top/Article/details/gt2eigkmqyr.html

[R59] 发 POST JSON
来源：http://dali.zhixingplan.top/Article/details/gt2ppovgrvg.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.sxryk.cn/Article/details/gt2ejlquzfg.html

[R60] 只看 HTTP 状态码
来源：http://dali.ehwqpu.com/Article/details/gt2cjbmosbx.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jqgufenzy.top/Article/details/gt2zsjnanrn.html

[R61] 磁盘占用
来源：http://dali.xuetiantiany.cn/Article/details/gt2fvzptfds.html

df -h;  du -sh *
来源：http://dali.xinyue.icu/Article/details/gt2blmfxswc.html

[R62] 找最占空间的文件
来源：http://dali.shzxlz.cn/Article/details/gt2igzcpljo.html

du -ah . | sort -rh | head -10
来源：http://dali.shangyingyoupin.top/Article/details/gt2whcxlohl.html

[R63] 内存与进程
来源：http://dali.yangfankeji.com/Article/details/gt2enxeulud.html

free -h;  ps aux | grep nginx
来源：http://dali.ivvv.top/Article/details/gt2efwvqnby.html

[R64] 结束进程
来源：http://dali.aibaodan.cn/Article/details/gt2lcwwjsqm.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ehwqpu.com/Article/details/gt2yltgtfke.html

[R65] 查看端口占用
来源：http://dali.ivvv.top/Article/details/gt2dbuewoag.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yangfankeji.com/Article/details/gt2unvctqyv.html

[R66] 定时任务
来源：http://dali.jlsjyb.cn/Article/details/gt2xtezntxi.html

crontab -e;  crontab -l
来源：http://dali.jinqigfzy.top/Article/details/gt2hrtuqqzu.html

[R67] 生成随机十六进制串
来源：http://dali.fengsongda.top/Article/details/gt2fvyzhawd.html

openssl rand -hex 16
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wmeviedy.html

[R68] 计算文件校验值
来源：http://dali.hnqzz.top/Article/details/gt2shtcyojj.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.kuanghao11.cn/Article/details/gt2gouftxjf.html

[R69] 生成随机密码
来源：http://dali.dianchejie.cn/Article/details/gt2uequyszf.html

head -c 16 /dev/urandom | base64
来源：http://dali.gotoacloud.top/Article/details/gt2zkgeuoxx.html

[R70] 时间戳与互转
来源：http://dali.shuidangran.top/Article/details/gt2haesmgfl.html

date +%s;  date -d @1700000000
来源：http://dali.chenzaomai.com/Article/details/gt2dienpdxf.html

[R71] 日期格式化
来源：http://dali.tianlin.xyz/Article/details/gt2kblefhpm.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2esvnzzxu.html

[R72] 等待端口就绪
来源：http://dali.feifeiyinyue.top/Article/details/gt2sekhgpji.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.iojbl.cn/Article/details/gt2biuokxpz.html

[R73] 分割大日志
来源：http://dali.jiagoushi.top/Article/details/gt2wtyfodwp.html

split -l 1000 big.log part_
来源：http://dali.xylfe.cn/Article/details/gt2smnwjcne.html

[R74] 批量重命名
来源：http://dali.zhengqikj.top/Article/details/gt2pcytsonw.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.wangdashe.top/Article/details/gt2itrfppaw.html

[R75] 导出环境变量
来源：http://dali.feifeiyinyue.top/Article/details/gt2lgmlfovt.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.cucudq.cn/Article/details/gt2iubkasit.html

[R76] 使用临时文件
来源：http://dali.yuxming.cn/Article/details/gt2gkigtubj.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yuanzhike.top/Article/details/gt2oabwcddf.html

[R77] 读取用户输入
来源：http://dali.yuanzhike.top/Article/details/gt2yyuuuxmf.html

read -rp "请输入: " ans
来源：http://dali.nanxinkj.top/Article/details/gt2fvaioxdn.html

[R78] 交互式菜单
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ogbvlgil.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.shzxlz.cn/Article/details/gt2djyygned.html

[R79] 解析命令行选项
来源：http://dali.xylfe.cn/Article/details/gt2kiyrjjfq.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.c1oappe.top/Article/details/gt2evnpcxec.html

[R80] 查看脚本执行耗时
来源：http://dali.chenjidiqi.icu/Article/details/gt2mbnqyqyp.html

time ./run.sh
来源：http://dali.zdqjudy.top/Article/details/gt2zavwfuce.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ebxvyodx.html

S. C / C++ 专题
来源：http://dali.sweek.top/Article/details/gt2nszxqbjc.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2tnrrcmrx.html

[S01] C：Hello World
来源：http://dali.yj20258.top/Article/details/gt2zqpmvlqm.html

#include <stdio.h>
来源：http://dali.dianchejie.cn/Article/details/gt2betstclh.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.xziqi.cn/Article/details/gt2auhpqyec.html

[S02] C：变量与格式化输出
来源：http://dali.mhx1999.top/Article/details/gt2adnsmciy.html

int a = 10; printf("%d\n", a);
来源：http://dali.nanxinkj.top/Article/details/gt2aaofmmat.html

[S03] C：读入整数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tiagolij.html

int x; scanf("%d", &x);
来源：http://dali.cashguo.top/Article/details/gt2dxmcbkzd.html

[S04] C：字符串复制
来源：http://dali.jiagoushi.top/Article/details/gt2gvmvpjld.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.fengsongda.top/Article/details/gt2qscahqwd.html

[S05] C：字符串长度
来源：http://dali.iojbl.cn/Article/details/gt2eobfcjat.html

strlen(s)
来源：http://dali.hywenlv.cn/Article/details/gt2xoxacjsa.html

[S06] C：字符串比较
来源：http://dali.guowangkeji.top/Article/details/gt2xsbbxyoy.html

strcmp(a, b) == 0
来源：http://dali.jqgfzy.top/Article/details/gt2lcceyuap.html

[S07] C：数组遍历求和
来源：http://dali.daxiang520.top/Article/details/gt2ycyrvvei.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2zqaixgbv.html

[S08] C：动态内存分配与释放
来源：http://dali.daxiang520.top/Article/details/gt2spvhxgjv.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.chenzaomai.com/Article/details/gt2pyuwgexc.html

[S09] C：结构体定义与初始化
来源：http://dali.sweek.top/Article/details/gt2lxkhdrqs.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.316326.xyz/Article/details/gt2ptwbuizd.html

[S10] C：指针与解引用
来源：http://dali.xuetiantiany.cn/Article/details/gt2seestjui.html

int *p = &a;  *p = 5;
来源：http://dali.daxiang520.top/Article/details/gt2ylicjdmv.html

[S11] C：逐行读文件
来源：http://dali.jiagoushi.top/Article/details/gt2hlnaukhb.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.dianchejie.cn/Article/details/gt2qrimmkko.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.xziqi.cn/Article/details/gt2jlevwonj.html

fclose(f);
来源：http://dali.yj20258888.top/Article/details/gt2jfgxfpin.html

[S12] C：写文件
来源：http://dali.smart0.xyz/Article/details/gt2zlxjqfvn.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hfpthk.cn/Article/details/gt2imnyvhpk.html

[S13] C：宏定义
来源：http://dali.mhx1999.top/Article/details/gt2kxempibh.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zdqjudy.top/Article/details/gt2pqfkplay.html

[S14] C：枚举
来源：http://dali.mhx1999.top/Article/details/gt2rciqlqbt.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.cheryme.top/Article/details/gt2lsdtafge.html

[S15] C：类型转换
来源：http://dali.sufxvd.cn/Article/details/gt2flvsmvjm.html

(double) a / b
来源：http://dali.haohaochexian.top/Article/details/gt2nvtylgww.html

[S16] C：位操作置位
来源：http://dali.jinqigufen.top/Article/details/gt2vbtkejmi.html

x |= (1 << 3);
来源：http://dali.yj202588.top/Article/details/gt2rqfimlxv.html

[S17] C：安全拼接字符串
来源：http://dali.xuetiantiany.cn/Article/details/gt2blbwiany.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhoulong.xyz/Article/details/gt2zcqalzvu.html

[S18] C：命令行参数
来源：http://dali.wangshuangyany.cn/Article/details/gt2vixljkqw.html

int main(int argc, char **argv)
来源：http://dali.chenzaomai.com/Article/details/gt2erdnybsg.html

[S19] C：快速排序
来源：http://dali.ybcxt.top/Article/details/gt2reeeolpn.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.pengpengdd.cyou/Article/details/gt2grgvorsz.html

[S20] C：二分查找
来源：http://dali.smart0.xyz/Article/details/gt2gdbzmxrg.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.xuanzx.com/Article/details/gt2hvmpkwuv.html

[S21] C：字符类别判断
来源：http://dali.tianlin.xyz/Article/details/gt2gdtdwntn.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yzxwioom.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2gfrcmycs.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yvedp.cn/Article/details/gt2radeuuzp.html

[S23] C：随机数
来源：http://dali.andypj.xyz/Article/details/gt2mtrrwgoa.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zdqjudy.top/Article/details/gt2kbaihpgi.html

[S24] C：获取本地时间
来源：http://dali.birdmap.top/Article/details/gt2loodnhnn.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.tian-w.cn/Article/details/gt2evozmkmu.html

[S25] C：内存拷贝
来源：http://dali.zhengqikj.top/Article/details/gt2rdeuhjih.html

memcpy(dst, src, n);
来源：http://dali.mhx1999.top/Article/details/gt2irvdzvfi.html

[S26] C：内存清零
来源：http://dali.jqgfzy.top/Article/details/gt2zxpumbww.html

memset(a, 0, sizeof a);
来源：http://dali.daria6918.cn/Article/details/gt2kifkfmbl.html

[S27] C：定义常量
来源：http://dali.guannengcc.top/Article/details/gt2liofjcfi.html

const double PI = 3.14159;
来源：http://dali.fengsongda.top/Article/details/gt2jlcnikvh.html

[S28] C：静态变量
来源：http://dali.zhoulong.xyz/Article/details/gt2mdiznxzg.html

static int counter = 0;
来源：http://dali.zhixingplan.top/Article/details/gt2udcbples.html

[S29] C：变参函数
来源：http://dali.jqgufenzy.top/Article/details/gt2xxxuxkpj.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.9152youxi.cn/Article/details/gt2arrmkvco.html

[S30] C：头文件保护
来源：http://dali.dianchejie.cn/Article/details/gt2nddbbdow.html


<!-- 参考信息 -->