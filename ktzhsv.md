代发 wailian999

[Q63] 开启事务
来源：http://dali.xylfe.cn/Article/details/gt2jzvgbtxq.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jlsjyb.cn/Article/details/gt2iknwvcte.html

[Q64] 提交事务
来源：http://dali.zhixingplan.top/Article/details/gt2dsprnmct.html

COMMIT;
来源：http://dali.ybcxt.top/Article/details/gt2mehaiujq.html

[Q65] 回滚事务
来源：http://dali.hnqzz.top/Article/details/gt2qqykrnde.html

ROLLBACK;
来源：http://dali.shzxlz.cn/Article/details/gt2wotutpux.html

[Q66] 行锁查询
来源：http://dali.chenzaomai.com/Article/details/gt2uqiejiln.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hongshengwenyu.top/Article/details/gt2cvdaybgi.html

[Q67] 设置隔离级别
来源：http://dali.jqgufenzy.top/Article/details/gt2mntqqgqi.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.9152youxi.cn/Article/details/gt2qptuobkt.html

[Q68] 保存点
来源：http://dali.zhoulong.xyz/Article/details/gt2fyvsooev.html

SAVEPOINT sp1;
来源：http://dali.xuanzx.com/Article/details/gt2rkynwllg.html

ROLLBACK TO sp1;
来源：http://dali.tian-w.cn/Article/details/gt2wgdksbou.html

[Q69] 查看执行计划
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nldpmcbk.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.chenlongwang.top/Article/details/gt2npxaenlf.html

[Q70] 更新统计信息
来源：http://dali.pengpengdd.cyou/Article/details/gt2ziahkgyb.html

ANALYZE TABLE users;
来源：http://dali.jiagoushi.top/Article/details/gt2ywmycopw.html

[Q71] 查看建表语句
来源：http://dali.chenjidiqi.icu/Article/details/gt2neueqwaa.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.xylfe.cn/Article/details/gt2bfvsofvs.html

[Q72] 查看索引
来源：http://dali.yvedp.cn/Article/details/gt2vvdtcgts.html

SHOW INDEX FROM users;
来源：http://dali.yangfankeji.com/Article/details/gt2wqtqoals.html

[Q73] 查看表状态
来源：http://dali.shzxlz.cn/Article/details/gt2yewlmyiq.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yj20258.top/Article/details/gt2omfiuyic.html

[Q74] 强制使用索引
来源：http://dali.wangdashe.top/Article/details/gt2nmjyyojz.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.cucudq.cn/Article/details/gt2nbqdwbmp.html

[Q75] 日期格式化
来源：http://dali.zhongyouzk.top/Article/details/gt2gqawkumu.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jinqigfzy.top/Article/details/gt2kvxzkkoz.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lnxpvtcs.html

[Q76] 按天统计
来源：http://dali.316326.xyz/Article/details/gt2jlibvguv.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.haohaochexian.top/Article/details/gt2zaiidyto.html

[Q77] 时间加减
来源：http://dali.ydzc1.top/Article/details/gt2wzsnmaqu.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.kuanghao11.cn/Article/details/gt2bjcmqitt.html

[Q78] 当前时间
来源：http://dali.yanxiufei.cn/Article/details/gt2jsrxsdrr.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.nanxuanxn.top/Article/details/gt2xfwqtgla.html

[Q79] 字符串拼接
来源：http://dali.316326.xyz/Article/details/gt2upiuymzp.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.ppjwa.cn/Article/details/gt2usqvmyhx.html

[Q80] 字符串截取
来源：http://dali.feifeiyinyue.top/Article/details/gt2jupffgxx.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gt2xhtyixfm.html

[Q81] 字符串替换
来源：http://dali.redwolf501.top/Article/details/gt2tbuwtchq.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hywenlv.cn/Article/details/gt2unvyaqen.html

[Q82] 字符长度与字节长度
来源：http://dali.hnxiangtu.top/Article/details/gt2lredkfec.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qijfaqss.html

[Q83] 大小写转换
来源：http://dali.hysaishi.cn/Article/details/gt2syxelmst.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gt2qymvekbf.html

[Q84] 去除首尾空格
来源：http://dali.chenjidiqi.icu/Article/details/gt2crblxgwu.html

SELECT TRIM(name) FROM users;
来源：http://dali.yuanzhike.top/Article/details/gt2ljvxvkxp.html

[Q85] 数值取整
来源：http://dali.xylfe.cn/Article/details/gt2dgkbulja.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jqgufenzy.top/Article/details/gt2yfphpfaw.html

[Q86] 读取 JSON 字段
来源：http://dali.daria6918.cn/Article/details/gt2pmnydqaj.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yvedp.cn/Article/details/gt2xidoxkuq.html

[Q87] JSON 字段做条件
来源：http://dali.fengsongda.top/Article/details/gt2qxcgqsfd.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhiwuduotai.top/Article/details/gt2ssmavhye.html

[Q88] 行转列（条件聚合）
来源：http://dali.yvedp.cn/Article/details/gt2tikjihof.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.guowangkeji.top/Article/details/gt2bmekvorl.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.guowangkeji.top/Article/details/gt2zdcdzmxd.html

[Q89] 判断表是否存在
来源：http://dali.fzhhl.top/Article/details/gt2noatjsja.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.fengsongda.top/Article/details/gt2cglilhko.html

[Q90] 生成序号列
来源：http://dali.shuidangran.top/Article/details/gt2itkagyzi.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.gogol.net.cn/Article/details/gt2xvrymzfi.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2nifplpxc.html

R. Bash 专题
来源：http://dali.yueranfly.top/Article/details/gt2kuqamwwg.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2whqtjars.html

[R01] shebang 与严格模式
来源：http://dali.cqqwz.cn/Article/details/gt2azgxjmpf.html

#!/usr/bin/env bash
来源：http://dali.hammf.cn/Article/details/gt2vnohomhf.html

set -euo pipefail
来源：http://dali.ydzc1.top/Article/details/gt2trqhrcnc.html

[R02] 变量赋值与使用
来源：http://dali.cucudq.cn/Article/details/gt2xlfnbnpo.html

name="Tom"; echo "$name"
来源：http://dali.hnqzz.top/Article/details/gt2mgczpzmt.html

[R03] 只读变量
来源：http://dali.bjfxy.top/Article/details/gt2uyucydwi.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2atcorpqt.html

[R04] 位置参数
来源：http://dali.hongshengwenyu.top/Article/details/gt2mimptyda.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.gaohongyu789.top/Article/details/gt2bewyfwds.html

[R05] 参数默认值
来源：http://dali.sysykeji.top/Article/details/gt2wawtvtvq.html

name="${1:-default}"
来源：http://dali.zhixingplan.top/Article/details/gt2bxoiibgp.html

[R06] 判断命令是否存在
来源：http://dali.andypj.xyz/Article/details/gt2jwyeniie.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.mhx1999.top/Article/details/gt2osjrywyg.html

[R07] if 判断文件
来源：http://dali.mhx1999.top/Article/details/gt2clsphsin.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.fengsongda.top/Article/details/gt2qeejppoj.html

[R08] 数值比较
来源：http://dali.yanxiufei.cn/Article/details/gt2xjzriscv.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.shuidangran.top/Article/details/gt2sqbxwbdm.html

[R09] 字符串比较
来源：http://dali.wangshuangyany.cn/Article/details/gt2dbeblcut.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jlsjyb.cn/Article/details/gt2qrhxhzie.html

[R10] 正则匹配
来源：http://dali.jinqigfzy.top/Article/details/gt2toroirzd.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.andypj.xyz/Article/details/gt2tbzfarsl.html

[R11] case 多分支
来源：http://dali.andypj.xyz/Article/details/gt2tctgallj.html

case "$1" in
来源：http://dali.shangyingyoupin.top/Article/details/gt2ntpvnprd.html

start) echo "启动" ;;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rlpqtasc.html

stop)  echo "停止" ;;
来源：http://dali.zhixingplan.top/Article/details/gt2znoycgmq.html

*)     echo "未知命令" ;;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cxydxgrr.html

esac
来源：http://dali.andypj.xyz/Article/details/gt2saabkpho.html

[R12] for 遍历文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cvbthiqq.html

for f in *.txt; do echo "$f"; done
来源：http://dali.mhx1999.top/Article/details/gt2izyuwxyr.html

[R13] for 计数循环
来源：http://dali.ybcxt.top/Article/details/gt2plumnpde.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.guannengcc.top/Article/details/gt2guvkypjn.html

[R14] C 风格 for
来源：http://dali.guannengcc.top/Article/details/gt2zjkxqvir.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.birdmap.top/Article/details/gt2abwunhpa.html

[R15] while 逐行读文件
来源：http://dali.andypj.xyz/Article/details/gt2zhgfwzzw.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yueranfly.top/Article/details/gt2qrwpgxxy.html

[R16] until 等待条件
来源：http://dali.hammf.cn/Article/details/gt2pdkgnzru.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.havefunace.top/Article/details/gt2jlffluuv.html

[R17] 数组定义与取值
来源：http://dali.zhengqikj.top/Article/details/gt2ysfdfhor.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.svipenyu.cn/Article/details/gt2grmztmxu.html

[R18] 遍历数组
来源：http://dali.tianlin.xyz/Article/details/gt2rklaehgh.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hnqzz.top/Article/details/gt2fttpsqpa.html

[R19] 数组长度
来源：http://dali.xuanzx.com/Article/details/gt2vogdcnfq.html

echo "${#arr[@]}"
来源：http://dali.gotoacloud.top/Article/details/gt2neqsgvvq.html

[R20] 关联数组（字典）
来源：http://dali.ehwqpu.com/Article/details/gt2xijuzawp.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.hfpthk.cn/Article/details/gt2fcbybnkj.html

[R21] 字符串长度
来源：http://dali.nanxinkj.top/Article/details/gt2hjxtbrxl.html

echo "${#s}"
来源：http://dali.sxryk.cn/Article/details/gt2vzbdaygn.html

[R22] 截取子串
来源：http://dali.xziqi.cn/Article/details/gt2zxpzfrza.html

echo "${s:0:5}"
来源：http://dali.chenlongwang.top/Article/details/gt2vniewbre.html

[R23] 字符串替换
来源：http://dali.kuanghao11.cn/Article/details/gt2mixqpwyo.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.cashguo.top/Article/details/gt2akiidmqc.html

[R24] 大小写转换
来源：http://dali.9152youxi.cn/Article/details/gt2axcgnpcl.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.sxryk.cn/Article/details/gt2xgzqrmwp.html

[R25] 去后缀 / 去前缀
来源：http://dali.c1oappe.top/Article/details/gt2endobkvx.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.dashuyun.cn/Article/details/gt2wcefijcu.html

[R26] 命令替换
来源：http://dali.yangfankeji.com/Article/details/gt2kciaooir.html

now=$(date +%F); echo "$now"
来源：http://dali.shuidangran.top/Article/details/gt2qrrqyfsu.html

[R27] 算术展开
来源：http://dali.c1oappe.top/Article/details/gt2hkjyesyf.html

echo $((1 + 2 * 3))
来源：http://dali.tanke756.top/Article/details/gt2dvidanci.html

[R28] 浮点运算
来源：http://dali.cashguo.top/Article/details/gt2qlcsxqqz.html

echo "scale=2; 10/3" | bc
来源：http://dali.jinqigufen.top/Article/details/gt2zcxyewnl.html

[R29] 定义函数
来源：http://dali.snrcjt.cn/Article/details/gt2qxtuodyn.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.pycfn.com/Article/details/gt2wbmwhjcf.html

[R30] 函数返回状态码
来源：http://dali.kuanghao11.cn/Article/details/gt2hqrelnyu.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.sweek.top/Article/details/gt2whjjiynj.html

[R31] 局部变量
来源：http://dali.ehwqpu.com/Article/details/gt2kyhrxkke.html

f() { local x=1; echo "$x"; }
来源：http://dali.ybcxt.top/Article/details/gt2cqhcwtjv.html

[R32] 参数个数校验
来源：http://dali.ybcxt.top/Article/details/gt2wgwpynqo.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2giuptzex.html

[R33] 捕获错误并提示行号
来源：http://dali.andypj.xyz/Article/details/gt2fbcqfgcx.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yj202588.top/Article/details/gt2kqgjtmyy.html

[R34] 退出时清理
来源：http://dali.sufxvd.cn/Article/details/gt2ezivmicx.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.andypj.xyz/Article/details/gt2azpquirp.html

[R35] 后台执行并等待
来源：http://dali.cqqwz.cn/Article/details/gt2jzbsxxmm.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.feifeiyinyue.top/Article/details/gt2anktrybu.html

[R36] 并发执行多个任务
来源：http://dali.zhixingplan.top/Article/details/gt2gzagxjvu.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhongyouzk.top/Article/details/gt2kuwthlwg.html

[R37] 把输出赋给变量
来源：http://dali.gogol.net.cn/Article/details/gt2qbfcxjaa.html

files=$(ls -1)
来源：http://dali.yangfankeji.com/Article/details/gt2pbjlqyoy.html

[R38] 管道串联
来源：http://dali.yongpay.top/Article/details/gt2cfabfrde.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yongpay.top/Article/details/gt2uvtitqpy.html

[R39] 重定向标准输出与错误
来源：http://dali.yj20258.top/Article/details/gt2gajbuuxp.html

cmd > out.log 2>&1
来源：http://dali.birdmap.top/Article/details/gt2uvtlroat.html

[R40] 追加写日志
来源：http://dali.hfpthk.cn/Article/details/gt2sgzkqspv.html

echo "log" >> out.log
来源：http://dali.andypj.xyz/Article/details/gt2aavhqnqw.html

[R41] 丢弃输出
来源：http://dali.sweek.top/Article/details/gt2hqemgnzd.html

cmd >/dev/null 2>&1
来源：http://dali.hammf.cn/Article/details/gt2cbfbmfmx.html

[R42] 输入重定向
来源：http://dali.nanxuanxn.top/Article/details/gt2zaiunocu.html

wc -l < a.txt
来源：http://dali.nwbrower.top/Article/details/gt2exzmvtmf.html

[R43] 按名字查找文件
来源：http://dali.tianlin.xyz/Article/details/gt2kikjxjdr.html

find . -name "*.log" -type f
来源：http://dali.guannengcc.top/Article/details/gt2ilqmivny.html

[R44] 按修改时间查找
来源：http://dali.zhongyouzk.top/Article/details/gt2probytqd.html

find . -mtime -7 -type f
来源：http://dali.ydzc1.top/Article/details/gt2dqxdqeov.html

[R45] 批量删除
来源：http://dali.jyoumei.cn/Article/details/gt2kpbklhfe.html

find . -name "*.tmp" -delete
来源：http://dali.pycfn.com/Article/details/gt2tukheglv.html

[R46] 递归替换文件内容
来源：http://dali.cucudq.cn/Article/details/gt2zutyowld.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.wangshuangyany.cn/Article/details/gt2xjtcsqdy.html

[R47] sed 单行替换
来源：http://dali.sxryk.cn/Article/details/gt2tjnaqhpk.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yanxiufei.cn/Article/details/gt2obdgaayj.html

[R48] awk 取指定列
来源：http://dali.hywenlv.cn/Article/details/gt2qplakqvt.html

awk '{print $1, $3}' a.txt
来源：http://dali.dashuyun.cn/Article/details/gt2cebvvels.html

[R49] awk 带条件
来源：http://dali.wangshuangyany.cn/Article/details/gt2xdakwncp.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ldcukmcg.html

[R50] awk 求和
来源：http://dali.hfpthk.cn/Article/details/gt2hhqqrpuc.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yueranfly.top/Article/details/gt2xzgljytp.html

[R51] 排序去重取前几
来源：http://dali.daxiang520.top/Article/details/gt2ckswrmjw.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.nanxuanxn.top/Article/details/gt2skeqijtw.html

[R52] 统计行数
来源：http://dali.nwbrower.top/Article/details/gt2uowavpol.html

wc -l a.txt
来源：http://dali.hnxiangtu.top/Article/details/gt2krxejnes.html

[R53] 查看文件头与实时尾
来源：http://dali.shzxlz.cn/Article/details/gt2xetrxjzx.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.xziqi.cn/Article/details/gt2wgsfmryp.html

[R54] 比较两个文件
来源：http://dali.jinqigufen.top/Article/details/gt2sharfier.html

diff a.txt b.txt
来源：http://dali.yangfankeji.com/Article/details/gt2zkufyjho.html

[R55] 压缩与解压
来源：http://dali.yueranfly.top/Article/details/gt2nycighxb.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jlsjyb.cn/Article/details/gt2bhyumsbv.html

[R56] 远程拷贝
来源：http://dali.birdmap.top/Article/details/gt2uazuhchf.html

scp file user@host:/path/
来源：http://dali.ivvv.top/Article/details/gt2rnemhkxk.html

[R57] 远程执行命令
来源：http://dali.hysaishi.cn/Article/details/gt2okgpcnic.html

ssh user@host 'uptime'
来源：http://dali.wangdashe.top/Article/details/gt2jenishhj.html

[R58] 下载文件
来源：http://dali.yanxiufei.cn/Article/details/gt2qdnkiadb.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zdqjudy.top/Article/details/gt2etcgwqef.html

[R59] 发 POST JSON
来源：http://dali.pycfn.com/Article/details/gt2iltvlzgq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.wangdashe.top/Article/details/gt2yuwkvxjp.html

[R60] 只看 HTTP 状态码
来源：http://dali.hongshengwenyu.top/Article/details/gt2wcfhkute.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yj20258888.top/Article/details/gt2epdohxxk.html

[R61] 磁盘占用
来源：http://dali.hysaishi.cn/Article/details/gt2ssdhqafu.html

df -h;  du -sh *
来源：http://dali.yj202588.top/Article/details/gt2tbdghnmd.html

[R62] 找最占空间的文件
来源：http://dali.yonumen.top/Article/details/gt2wuqejasf.html

du -ah . | sort -rh | head -10
来源：http://dali.hammf.cn/Article/details/gt2ouzucwar.html

[R63] 内存与进程
来源：http://dali.pycfn.com/Article/details/gt2eoayhkmy.html

free -h;  ps aux | grep nginx
来源：http://dali.hywenlv.cn/Article/details/gt2vqjdbvan.html

[R64] 结束进程
来源：http://dali.yuxming.cn/Article/details/gt2tzwqxirr.html

kill -9 $(pgrep -f app.py)
来源：http://dali.gzhubu.top/Article/details/gt2mjmznwqn.html

[R65] 查看端口占用
来源：http://dali.sweek.top/Article/details/gt2iopyvgcv.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yj20258.top/Article/details/gt2beyhbptd.html

[R66] 定时任务
来源：http://dali.yuanzhike.top/Article/details/gt2mdpvbmso.html

crontab -e;  crontab -l
来源：http://dali.smart0.xyz/Article/details/gt2djcuzsna.html

[R67] 生成随机十六进制串
来源：http://dali.xuanzx.com/Article/details/gt2trwfrkph.html

openssl rand -hex 16
来源：http://dali.quarkkingdee.top/Article/details/gt2tkqnzwlg.html

[R68] 计算文件校验值
来源：http://dali.sysykeji.top/Article/details/gt2thcdnsip.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.9152youxi.cn/Article/details/gt2wzqxhets.html

[R69] 生成随机密码
来源：http://dali.yj202588.top/Article/details/gt2ymunifml.html

head -c 16 /dev/urandom | base64
来源：http://dali.hysaishi.cn/Article/details/gt2jeydkmcy.html

[R70] 时间戳与互转
来源：http://dali.hnxiangtu.top/Article/details/gt2wszfhdti.html

date +%s;  date -d @1700000000
来源：http://dali.bjfxy.top/Article/details/gt2jupgrigu.html

[R71] 日期格式化
来源：http://dali.daria6918.cn/Article/details/gt2xhamjclq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hongshengwenyu.top/Article/details/gt2olvktmmk.html

[R72] 等待端口就绪
来源：http://dali.nanxuanxn.top/Article/details/gt2dwqyifpf.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zycfv.cn/Article/details/gt2jfiorhmz.html

[R73] 分割大日志
来源：http://dali.yj20258888.top/Article/details/gt2hkktibty.html

split -l 1000 big.log part_
来源：http://dali.kuanghao11.cn/Article/details/gt2aywqqlmy.html

[R74] 批量重命名
来源：http://dali.yanxiufei.cn/Article/details/gt2mvscgahh.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jinqigufen.top/Article/details/gt2xtwymctw.html

[R75] 导出环境变量
来源：http://dali.mhx1999.top/Article/details/gt2gztsexkj.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yueranfly.top/Article/details/gt2efldvvmn.html

[R76] 使用临时文件
来源：http://dali.jqgufenzy.top/Article/details/gt2wfhkdjxq.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hywenlv.cn/Article/details/gt2npcwmsnm.html

[R77] 读取用户输入
来源：http://dali.zycfv.cn/Article/details/gt2zotahpit.html

read -rp "请输入: " ans
来源：http://dali.cqqwz.cn/Article/details/gt2nxykshzf.html

[R78] 交互式菜单
来源：http://dali.wangshuangyany.cn/Article/details/gt2jzcpccjz.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.ehwqpu.com/Article/details/gt2ldlqouai.html

[R79] 解析命令行选项
来源：http://dali.daria6918.cn/Article/details/gt2sfcfsoph.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.xylfe.cn/Article/details/gt2wziepsvw.html

[R80] 查看脚本执行耗时
来源：http://dali.yuxming.cn/Article/details/gt2miekcasi.html

time ./run.sh
来源：http://dali.ivvv.top/Article/details/gt2ysxbiple.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2sgozyyrf.html

S. C / C++ 专题
来源：http://dali.nanxinkj.top/Article/details/gt2clwycbwf.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eqgbohiv.html

[S01] C：Hello World
来源：http://dali.tian-w.cn/Article/details/gt2vjgyihit.html

#include <stdio.h>
来源：http://dali.shangyingyoupin.top/Article/details/gt2hgozkqrn.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hnqzz.top/Article/details/gt2upqknqst.html

[S02] C：变量与格式化输出
来源：http://dali.cqqwz.cn/Article/details/gt2burweepk.html

int a = 10; printf("%d\n", a);
来源：http://dali.shangyingyoupin.top/Article/details/gt2kgjzaoay.html

[S03] C：读入整数
来源：http://dali.vqdsnc.cn/Article/details/gt2vwegelfh.html

int x; scanf("%d", &x);
来源：http://dali.xylfe.cn/Article/details/gt2ytuheyuy.html

[S04] C：字符串复制
来源：http://dali.jianghu66.top/Article/details/gt2jyxpckbd.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhiwuduotai.top/Article/details/gt2rjhkcfsp.html

[S05] C：字符串长度
来源：http://dali.chenzaomai.com/Article/details/gt2scyktpkt.html

strlen(s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2kmzmnagw.html

[S06] C：字符串比较
来源：http://dali.aizwys.cn/Article/details/gt2jfqqrbmn.html

strcmp(a, b) == 0
来源：http://dali.cheryme.top/Article/details/gt2nhatygpd.html

[S07] C：数组遍历求和
来源：http://dali.redwolf501.top/Article/details/gt2ievisofw.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tkoypojq.html

[S08] C：动态内存分配与释放
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2toeqxufa.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.haohaochexian.top/Article/details/gt2fewjebhy.html

[S09] C：结构体定义与初始化
来源：http://dali.yj20258.top/Article/details/gt2fvfyarry.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.gotoacloud.top/Article/details/gt2dloxfjng.html

[S10] C：指针与解引用
来源：http://dali.hysaishi.cn/Article/details/gt2wlggogcx.html

int *p = &a;  *p = 5;
来源：http://dali.yongpay.top/Article/details/gt2bpxiyqqw.html

[S11] C：逐行读文件
来源：http://dali.tianlin.xyz/Article/details/gt2qxeaepxz.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.tanke756.top/Article/details/gt2sfsmewaj.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jscrtiag.html

fclose(f);
来源：http://dali.fengsongda.top/Article/details/gt2eoqlaoss.html

[S12] C：写文件
来源：http://dali.andypj.xyz/Article/details/gt2tgkvsngz.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yj20258.top/Article/details/gt2ufzjcwkb.html

[S13] C：宏定义
来源：http://dali.xinyue.icu/Article/details/gt2oztvojmo.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kofeacbg.html

[S14] C：枚举
来源：http://dali.ppjwa.cn/Article/details/gt2zfschhpp.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eaqfyyoa.html

[S15] C：类型转换
来源：http://dali.mhx1999.top/Article/details/gt2oqlbqsgu.html

(double) a / b
来源：http://dali.ppjwa.cn/Article/details/gt2muiwsqxy.html

[S16] C：位操作置位
来源：http://dali.hammf.cn/Article/details/gt2xkplihut.html

x |= (1 << 3);
来源：http://dali.pengpengdd.cyou/Article/details/gt2lphqkfdp.html

[S17] C：安全拼接字符串
来源：http://dali.jianghu66.top/Article/details/gt2tiwrmcnl.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jinqigufen.top/Article/details/gt2cjsdtnwq.html

[S18] C：命令行参数
来源：http://dali.meibo888.top/Article/details/gt2bfwpziui.html

int main(int argc, char **argv)
来源：http://dali.daxiang520.top/Article/details/gt2buxrgacx.html

[S19] C：快速排序
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pitqqmkj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zycfv.cn/Article/details/gt2uomifjxp.html

[S20] C：二分查找
来源：http://dali.xuanzx.com/Article/details/gt2tqggdhir.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.xylfe.cn/Article/details/gt2qkchjkba.html

[S21] C：字符类别判断
来源：http://dali.feifeiyinyue.top/Article/details/gt2nddbodzo.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2arupxofe.html

[S22] C：字符串转数字
来源：http://dali.shangyingyoupin.top/Article/details/gt2wrktulqr.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.aibaodan.cn/Article/details/gt2yneujzbx.html

[S23] C：随机数
来源：http://dali.sufxvd.cn/Article/details/gt2mxythskb.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.tianlin.xyz/Article/details/gt2njeyoywe.html

[S24] C：获取本地时间
来源：http://dali.vqdsnc.cn/Article/details/gt2fwvydkps.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.smart0.xyz/Article/details/gt2xvoymctu.html

[S25] C：内存拷贝
来源：http://dali.vqdsnc.cn/Article/details/gt2wssbetib.html

memcpy(dst, src, n);
来源：http://dali.cdnleiting.top/Article/details/gt2cbceabiq.html

[S26] C：内存清零
来源：http://dali.zhoulong.xyz/Article/details/gt2zejayrbh.html

memset(a, 0, sizeof a);
来源：http://dali.feifeiyinyue.top/Article/details/gt2lgjzoyxz.html

[S27] C：定义常量
来源：http://dali.ivvv.top/Article/details/gt2bkifxslv.html

const double PI = 3.14159;
来源：http://dali.ehwqpu.com/Article/details/gt2knitjfjj.html

[S28] C：静态变量
来源：http://dali.zhongyouzk.top/Article/details/gt2xfmgkhng.html

static int counter = 0;
来源：http://dali.pengpengdd.cyou/Article/details/gt2nmxrrekq.html

[S29] C：变参函数
来源：http://dali.zhixingplan.top/Article/details/gt2eyktbbbf.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.snrcjt.cn/Article/details/gt2djkmtgil.html

[S30] C：头文件保护
来源：http://dali.fzhhl.top/Article/details/gt2ztitnzne.html

#ifndef X_H
来源：http://dali.xuanzx.com/Article/details/gt2okcanavc.html

#define X_H
来源：http://dali.sufxvd.cn/Article/details/gt2xtjgjayx.html

#endif
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sllqnljr.html

[S31] C++：Hello World
来源：http://dali.xuanzx.com/Article/details/gt2ektqqymq.html

#include <iostream>
来源：http://dali.cashguo.top/Article/details/gt2pztegkaz.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tjiteoan.html

[S32] C++：字符串
来源：http://dali.nwbrower.top/Article/details/gt2pugyplyf.html

std::string s = "hi";  s += "!";
来源：http://dali.aizwys.cn/Article/details/gt2ivxwvbvx.html


<!-- 参考信息 -->