代发 wailian999

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jqgfzy.top/Article/details/gt2kbuibtfr.html

[Q60] 取上一行 / 下一行
来源：http://dali.jinqigfzy.top/Article/details/gt2fcujzqtt.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.daria6918.cn/Article/details/gt2rpnmqsfi.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.gaohongyu789.top/Article/details/gt2zvxytthh.html

[Q61] 移动平均
来源：http://dali.yj20258888.top/Article/details/gt2krrwaonk.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.tianlin.xyz/Article/details/gt2gqxkufbh.html

[Q62] 分组占比
来源：http://dali.mhx1999.top/Article/details/gt2xohlfhbi.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.c1oappe.top/Article/details/gt2qfqabmpq.html

[Q63] 开启事务
来源：http://dali.feifeiyinyue.top/Article/details/gt2xrlmfywl.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.iojbl.cn/Article/details/gt2ftmdunfa.html

[Q64] 提交事务
来源：http://dali.chenlongwang.top/Article/details/gt2xfoahqbf.html

COMMIT;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2thbqzcoh.html

[Q65] 回滚事务
来源：http://dali.zhixingplan.top/Article/details/gt2shkesaeu.html

ROLLBACK;
来源：http://dali.mhx1999.top/Article/details/gt2nmmfnylp.html

[Q66] 行锁查询
来源：http://dali.andypj.xyz/Article/details/gt2tfmsjsfq.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tvjiioug.html

[Q67] 设置隔离级别
来源：http://dali.yangfankeji.com/Article/details/gt2xfrzeiha.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.cashguo.top/Article/details/gt2ysitxcha.html

[Q68] 保存点
来源：http://dali.cqqwz.cn/Article/details/gt2chhqskom.html

SAVEPOINT sp1;
来源：http://dali.yongpay.top/Article/details/gt2kvubnadn.html

ROLLBACK TO sp1;
来源：http://dali.chenlongwang.top/Article/details/gt2hqupongy.html

[Q69] 查看执行计划
来源：http://dali.yueranfly.top/Article/details/gt2wlhnyfca.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.tian-w.cn/Article/details/gt2bugsybju.html

[Q70] 更新统计信息
来源：http://dali.yueranfly.top/Article/details/gt2xnhaetvq.html

ANALYZE TABLE users;
来源：http://dali.xuetiantiany.cn/Article/details/gt2grqvhjls.html

[Q71] 查看建表语句
来源：http://dali.zhengqikj.top/Article/details/gt2gbgnvkkz.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wxhimwcs.html

[Q72] 查看索引
来源：http://dali.haohaochexian.top/Article/details/gt2npncufmc.html

SHOW INDEX FROM users;
来源：http://dali.iojbl.cn/Article/details/gt2sveqnjsf.html

[Q73] 查看表状态
来源：http://dali.hnqzz.top/Article/details/gt2jnaayumu.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yj20258888.top/Article/details/gt2dxlyedsv.html

[Q74] 强制使用索引
来源：http://dali.sysykeji.top/Article/details/gt2cidpywrk.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.ppjwa.cn/Article/details/gt2cizhwxck.html

[Q75] 日期格式化
来源：http://dali.zhongyouzk.top/Article/details/gt2xulgtfap.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.ydzc1.top/Article/details/gt2aljbqwfa.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.xylfe.cn/Article/details/gt2bcsjahvh.html

[Q76] 按天统计
来源：http://dali.tian-w.cn/Article/details/gt2txnhjskk.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jiagoushi.top/Article/details/gt2cknryoot.html

[Q77] 时间加减
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vhwzmklw.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.pycfn.com/Article/details/gt2ziriqdiy.html

[Q78] 当前时间
来源：http://dali.chenlongwang.top/Article/details/gt2eoblqxhj.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.gaohongyu789.top/Article/details/gt2faneghoh.html

[Q79] 字符串拼接
来源：http://dali.jyoumei.cn/Article/details/gt2fbyaksjx.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yj202588.top/Article/details/gt2jxodbuxs.html

[Q80] 字符串截取
来源：http://dali.yongpay.top/Article/details/gt2wbibqcvg.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gt2swzwrmzs.html

[Q81] 字符串替换
来源：http://dali.zycfv.cn/Article/details/gt2jikzynmk.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gfwfqlqs.html

[Q82] 字符长度与字节长度
来源：http://dali.gzhubu.top/Article/details/gt2emmnsmjl.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gt2kvifmwrl.html

[Q83] 大小写转换
来源：http://dali.jiagoushi.top/Article/details/gt2nbeqgfdu.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.nwbrower.top/Article/details/gt2tjkgpqqf.html

[Q84] 去除首尾空格
来源：http://dali.yanxiufei.cn/Article/details/gt2veahfiao.html

SELECT TRIM(name) FROM users;
来源：http://dali.mhx1999.top/Article/details/gt2dwmrzodx.html

[Q85] 数值取整
来源：http://dali.quarkkingdee.top/Article/details/gt2hgafufog.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.cqqwz.cn/Article/details/gt2xxufwhkn.html

[Q86] 读取 JSON 字段
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fgpoqpwr.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.svipenyu.cn/Article/details/gt2fbuknslb.html

[Q87] JSON 字段做条件
来源：http://dali.mhx1999.top/Article/details/gt2irpnjnpd.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhengqikj.top/Article/details/gt2pohldecv.html

[Q88] 行转列（条件聚合）
来源：http://dali.cqqwz.cn/Article/details/gt2sorbgluq.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.nanxuanxn.top/Article/details/gt2kyebblzn.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.xziqi.cn/Article/details/gt2wmirunev.html

[Q89] 判断表是否存在
来源：http://dali.ydzc1.top/Article/details/gt2lazvaele.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yonumen.top/Article/details/gt2gyjedxjg.html

[Q90] 生成序号列
来源：http://dali.havefunace.top/Article/details/gt2ikdbjldw.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jlsjyb.cn/Article/details/gt2lfuqsdui.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2iapznyki.html

R. Bash 专题
来源：http://dali.gotoacloud.top/Article/details/gt2ihnuibkh.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2delxcrds.html

[R01] shebang 与严格模式
来源：http://dali.smart0.xyz/Article/details/gt2vgxlggix.html

#!/usr/bin/env bash
来源：http://dali.cashguo.top/Article/details/gt2nafepjvc.html

set -euo pipefail
来源：http://dali.jiagoushi.top/Article/details/gt2dowlcgqy.html

[R02] 变量赋值与使用
来源：http://dali.hfpthk.cn/Article/details/gt2mtycbdfv.html

name="Tom"; echo "$name"
来源：http://dali.hammf.cn/Article/details/gt2lencysbn.html

[R03] 只读变量
来源：http://dali.wangdashe.top/Article/details/gt2gwbhhwza.html

readonly PI=3.14
来源：http://dali.xuetiantiany.cn/Article/details/gt2jqfjtade.html

[R04] 位置参数
来源：http://dali.ivvv.top/Article/details/gt2gwhzmzfp.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.cqqwz.cn/Article/details/gt2ycshkpyy.html

[R05] 参数默认值
来源：http://dali.wangshuangyany.cn/Article/details/gt2tbbtfbtp.html

name="${1:-default}"
来源：http://dali.tian-w.cn/Article/details/gt2nqbamteb.html

[R06] 判断命令是否存在
来源：http://dali.pycfn.com/Article/details/gt2ecxisjsi.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.fengsongda.top/Article/details/gt2uoskbfrr.html

[R07] if 判断文件
来源：http://dali.yj20258.top/Article/details/gt2ldbwoqps.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zdqjudy.top/Article/details/gt2ziamemqm.html

[R08] 数值比较
来源：http://dali.gotoacloud.top/Article/details/gt2mvjdpgst.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhongyouzk.top/Article/details/gt2vnnbazqm.html

[R09] 字符串比较
来源：http://dali.dianchejie.cn/Article/details/gt2qfbmmdob.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yongpay.top/Article/details/gt2molgldmb.html

[R10] 正则匹配
来源：http://dali.tanke756.top/Article/details/gt2sdsvtepx.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.nwbrower.top/Article/details/gt2tehsmlnl.html

[R11] case 多分支
来源：http://dali.nanxinkj.top/Article/details/gt2ufczezjl.html

case "$1" in
来源：http://dali.fzhhl.top/Article/details/gt2pwomqkaq.html

start) echo "启动" ;;
来源：http://dali.hysaishi.cn/Article/details/gt2njrrigtt.html

stop)  echo "停止" ;;
来源：http://dali.kuanghao11.cn/Article/details/gt2cafwizig.html

*)     echo "未知命令" ;;
来源：http://dali.yj20258.top/Article/details/gt2vwujnrjp.html

esac
来源：http://dali.yuanzhike.top/Article/details/gt2xbgrwjuh.html

[R12] for 遍历文件
来源：http://dali.xylfe.cn/Article/details/gt2gdrmrxls.html

for f in *.txt; do echo "$f"; done
来源：http://dali.sweek.top/Article/details/gt2kfanjsve.html

[R13] for 计数循环
来源：http://dali.hnqzz.top/Article/details/gt2hdsckgii.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.shuidangran.top/Article/details/gt2qjlhcoiu.html

[R14] C 风格 for
来源：http://dali.tianlin.xyz/Article/details/gt2uebyqhpp.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yj20258.top/Article/details/gt2hcagzwjv.html

[R15] while 逐行读文件
来源：http://dali.gogol.net.cn/Article/details/gt2aajkhsae.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hongshengwenyu.top/Article/details/gt2bdwkvakx.html

[R16] until 等待条件
来源：http://dali.tian-w.cn/Article/details/gt2efzaihfq.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.hywenlv.cn/Article/details/gt2yitilcws.html

[R17] 数组定义与取值
来源：http://dali.gzhubu.top/Article/details/gt2tjqfxhyo.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.nanxinkj.top/Article/details/gt2wayggzip.html

[R18] 遍历数组
来源：http://dali.316326.xyz/Article/details/gt2eavwwrta.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jinqigfzy.top/Article/details/gt2svwsdysb.html

[R19] 数组长度
来源：http://dali.shanyushiyangtech.top/Article/details/gt2imptwnbp.html

echo "${#arr[@]}"
来源：http://dali.tianlin.xyz/Article/details/gt2iclbihbu.html

[R20] 关联数组（字典）
来源：http://dali.ydzc1.top/Article/details/gt2joxlxnuv.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gbzclvvn.html

[R21] 字符串长度
来源：http://dali.zhiwuduotai.top/Article/details/gt2zkxqqxlq.html

echo "${#s}"
来源：http://dali.bjfxy.top/Article/details/gt2ygwlgjzh.html

[R22] 截取子串
来源：http://dali.pengpengdd.cyou/Article/details/gt2zmlzqbcc.html

echo "${s:0:5}"
来源：http://dali.ppjwa.cn/Article/details/gt2xitzpngt.html

[R23] 字符串替换
来源：http://dali.haohaochexian.top/Article/details/gt2zlnscipx.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.aibaodan.cn/Article/details/gt2fzrbkzcy.html

[R24] 大小写转换
来源：http://dali.wangshuangyany.cn/Article/details/gt2qzfxydrp.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhongyouzk.top/Article/details/gt2knmmpbsv.html

[R25] 去后缀 / 去前缀
来源：http://dali.tanke756.top/Article/details/gt2pizfwsza.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.9152youxi.cn/Article/details/gt2owyktoub.html

[R26] 命令替换
来源：http://dali.feifeiyinyue.top/Article/details/gt2idqpoxhz.html

now=$(date +%F); echo "$now"
来源：http://dali.jiagoushi.top/Article/details/gt2isqcdelj.html

[R27] 算术展开
来源：http://dali.tianlin.xyz/Article/details/gt2wqzcrwlo.html

echo $((1 + 2 * 3))
来源：http://dali.tianlin.xyz/Article/details/gt2znucperk.html

[R28] 浮点运算
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xivzngmp.html

echo "scale=2; 10/3" | bc
来源：http://dali.ydzc1.top/Article/details/gt2detlosgk.html

[R29] 定义函数
来源：http://dali.yangfankeji.com/Article/details/gt2gofrheba.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.ivvv.top/Article/details/gt2dqvhpnmj.html

[R30] 函数返回状态码
来源：http://dali.birdmap.top/Article/details/gt2bclfmtfm.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jiagoushi.top/Article/details/gt2wsvdatbh.html

[R31] 局部变量
来源：http://dali.yj20258.top/Article/details/gt2spmqqumn.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2elxvizqw.html

[R32] 参数个数校验
来源：http://dali.jinqigufen.top/Article/details/gt2vfjxkwrd.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.iojbl.cn/Article/details/gt2jvxadyiz.html

[R33] 捕获错误并提示行号
来源：http://dali.dianchejie.cn/Article/details/gt2xzabvpyd.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jiagoushi.top/Article/details/gt2wzwbubqc.html

[R34] 退出时清理
来源：http://dali.ehwqpu.com/Article/details/gt2zqcqetzg.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.sweek.top/Article/details/gt2htirmvfv.html

[R35] 后台执行并等待
来源：http://dali.yuxming.cn/Article/details/gt2dinjthbo.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jlsjyb.cn/Article/details/gt2qfrojhap.html

[R36] 并发执行多个任务
来源：http://dali.guowangkeji.top/Article/details/gt2nxrzzqpj.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.ehwqpu.com/Article/details/gt2ckricdtz.html

[R37] 把输出赋给变量
来源：http://dali.hnqzz.top/Article/details/gt2jejmxucq.html

files=$(ls -1)
来源：http://dali.jyoumei.cn/Article/details/gt2oyiggtzl.html

[R38] 管道串联
来源：http://dali.jqgfzy.top/Article/details/gt2hkkrucsc.html

cat a.txt | grep -i error | wc -l
来源：http://dali.ivvv.top/Article/details/gt2uxxmnjuz.html

[R39] 重定向标准输出与错误
来源：http://dali.cdnleiting.top/Article/details/gt2mvknlxnp.html

cmd > out.log 2>&1
来源：http://dali.guowangkeji.top/Article/details/gt2omnhznyj.html

[R40] 追加写日志
来源：http://dali.jqgufenzy.top/Article/details/gt2suhgvvtm.html

echo "log" >> out.log
来源：http://dali.dianchejie.cn/Article/details/gt2hixjpamb.html

[R41] 丢弃输出
来源：http://dali.snrcjt.cn/Article/details/gt2wxxiddqt.html

cmd >/dev/null 2>&1
来源：http://dali.quarkkingdee.top/Article/details/gt2qxjsuusz.html

[R42] 输入重定向
来源：http://dali.wangdashe.top/Article/details/gt2hvemqhkb.html

wc -l < a.txt
来源：http://dali.ppjwa.cn/Article/details/gt2dklwrywy.html

[R43] 按名字查找文件
来源：http://dali.ivvv.top/Article/details/gt2zxupiuku.html

find . -name "*.log" -type f
来源：http://dali.ivvv.top/Article/details/gt2kzxsayjs.html

[R44] 按修改时间查找
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vjpmwmxs.html

find . -mtime -7 -type f
来源：http://dali.tian-w.cn/Article/details/gt2ymaqkqub.html

[R45] 批量删除
来源：http://dali.aibaodan.cn/Article/details/gt2sxmxgzeq.html

find . -name "*.tmp" -delete
来源：http://dali.hongshengwenyu.top/Article/details/gt2kuzwpgus.html

[R46] 递归替换文件内容
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dljyrkjm.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hfpthk.cn/Article/details/gt2ryaawhcz.html

[R47] sed 单行替换
来源：http://dali.yanxiufei.cn/Article/details/gt2wakowsjy.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yuanzhike.top/Article/details/gt2xaanbpkv.html

[R48] awk 取指定列
来源：http://dali.zdqjudy.top/Article/details/gt2qiavctwr.html

awk '{print $1, $3}' a.txt
来源：http://dali.9152youxi.cn/Article/details/gt2mmeqtrio.html

[R49] awk 带条件
来源：http://dali.yj20258888.top/Article/details/gt2ntjjvypd.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.xinyue.icu/Article/details/gt2sylxnfjj.html

[R50] awk 求和
来源：http://dali.vqdsnc.cn/Article/details/gt2vwqoiusn.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ppjwa.cn/Article/details/gt2etmtdvon.html

[R51] 排序去重取前几
来源：http://dali.haohaochexian.top/Article/details/gt2ndqbyfht.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.sufxvd.cn/Article/details/gt2vjprwtvh.html

[R52] 统计行数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mgwcdmjz.html

wc -l a.txt
来源：http://dali.yj20258.top/Article/details/gt2kgvzjibd.html

[R53] 查看文件头与实时尾
来源：http://dali.zhiwuduotai.top/Article/details/gt2kveusufz.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yuxming.cn/Article/details/gt2rwujvqlw.html

[R54] 比较两个文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2bocbtbmn.html

diff a.txt b.txt
来源：http://dali.hywenlv.cn/Article/details/gt2rjkneuol.html

[R55] 压缩与解压
来源：http://dali.chenlongwang.top/Article/details/gt2gdygfgwj.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jqgufenzy.top/Article/details/gt2nszrghzj.html

[R56] 远程拷贝
来源：http://dali.yanxiufei.cn/Article/details/gt2zqphahyv.html

scp file user@host:/path/
来源：http://dali.xuetiantiany.cn/Article/details/gt2dbrvsaxu.html

[R57] 远程执行命令
来源：http://dali.cashguo.top/Article/details/gt2fywamorl.html

ssh user@host 'uptime'
来源：http://dali.yueranfly.top/Article/details/gt2ksenlgwq.html

[R58] 下载文件
来源：http://dali.gogol.net.cn/Article/details/gt2likhqkiq.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.nanxuanxn.top/Article/details/gt2bpzetxcy.html

[R59] 发 POST JSON
来源：http://dali.ivvv.top/Article/details/gt2jyaanurh.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.cdnleiting.top/Article/details/gt2jaekhlcw.html

[R60] 只看 HTTP 状态码
来源：http://dali.yangfankeji.com/Article/details/gt2tyqefoit.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.bjfxy.top/Article/details/gt2xgzcwyvy.html

[R61] 磁盘占用
来源：http://dali.ybcxt.top/Article/details/gt2khirhmou.html

df -h;  du -sh *
来源：http://dali.ivvv.top/Article/details/gt2chvcuxpi.html

[R62] 找最占空间的文件
来源：http://dali.bjfxy.top/Article/details/gt2zzxuudya.html

du -ah . | sort -rh | head -10
来源：http://dali.ppjwa.cn/Article/details/gt2wshbkdge.html

[R63] 内存与进程
来源：http://dali.zhongyouzk.top/Article/details/gt2ebcpbaxz.html

free -h;  ps aux | grep nginx
来源：http://dali.zhiwuduotai.top/Article/details/gt2wvobqnjw.html

[R64] 结束进程
来源：http://dali.hnqzz.top/Article/details/gt2zvwheuzx.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yonumen.top/Article/details/gt2udinkhuf.html

[R65] 查看端口占用
来源：http://dali.chenjidiqi.icu/Article/details/gt2wovyddio.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.gaohongyu789.top/Article/details/gt2pposcoex.html

[R66] 定时任务
来源：http://dali.guowangkeji.top/Article/details/gt2gpbsnbvg.html

crontab -e;  crontab -l
来源：http://dali.sweek.top/Article/details/gt2fvbwuqkq.html

[R67] 生成随机十六进制串
来源：http://dali.hnqzz.top/Article/details/gt2oygzvjdp.html

openssl rand -hex 16
来源：http://dali.hysaishi.cn/Article/details/gt2gltjkokh.html

[R68] 计算文件校验值
来源：http://dali.daxiang520.top/Article/details/gt2eunhuysr.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zdqjudy.top/Article/details/gt2wzjfnobo.html

[R69] 生成随机密码
来源：http://dali.jiagoushi.top/Article/details/gt2bdlcyofk.html

head -c 16 /dev/urandom | base64
来源：http://dali.ydzc1.top/Article/details/gt2kzfyrsdo.html

[R70] 时间戳与互转
来源：http://dali.jinqigfzy.top/Article/details/gt2oztbnjrv.html

date +%s;  date -d @1700000000
来源：http://dali.hywenlv.cn/Article/details/gt2rlhxynnj.html

[R71] 日期格式化
来源：http://dali.mhx1999.top/Article/details/gt2lokzjktp.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.gzhubu.top/Article/details/gt2luwyjbag.html

[R72] 等待端口就绪
来源：http://dali.sufxvd.cn/Article/details/gt2nrnclsch.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.daria6918.cn/Article/details/gt2wfrjndci.html

[R73] 分割大日志
来源：http://dali.fzhhl.top/Article/details/gt2kfsvydyb.html

split -l 1000 big.log part_
来源：http://dali.ppjwa.cn/Article/details/gt2icpnotff.html

[R74] 批量重命名
来源：http://dali.cheryme.top/Article/details/gt2rmwaauag.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yanxiufei.cn/Article/details/gt2kiibgvkg.html

[R75] 导出环境变量
来源：http://dali.yanxiufei.cn/Article/details/gt2xxcmycfk.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.andypj.xyz/Article/details/gt2kpmwlnam.html

[R76] 使用临时文件
来源：http://dali.gogol.net.cn/Article/details/gt2lliktpid.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.guowangkeji.top/Article/details/gt2frocitse.html

[R77] 读取用户输入
来源：http://dali.yvedp.cn/Article/details/gt2hfxdhjnw.html

read -rp "请输入: " ans
来源：http://dali.guowangkeji.top/Article/details/gt2hvlxctgg.html

[R78] 交互式菜单
来源：http://dali.ivvv.top/Article/details/gt2dgmsrtkq.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.gaohongyu789.top/Article/details/gt2opaciiqd.html

[R79] 解析命令行选项
来源：http://dali.zdqjudy.top/Article/details/gt2cnkqxkxa.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhiwuduotai.top/Article/details/gt2qacwuccw.html

[R80] 查看脚本执行耗时
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xffdndgb.html

time ./run.sh
来源：http://dali.yongpay.top/Article/details/gt2awctdavc.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2mrpdhfqy.html

S. C / C++ 专题
来源：http://dali.xziqi.cn/Article/details/gt2xbsdmlpv.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2rwqtffqm.html

[S01] C：Hello World
来源：http://dali.hongshengwenyu.top/Article/details/gt2ttxsaehf.html

#include <stdio.h>
来源：http://dali.wangshuangyany.cn/Article/details/gt2ocxwmiax.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.shzxlz.cn/Article/details/gt2ybyryhqy.html

[S02] C：变量与格式化输出
来源：http://dali.mhx1999.top/Article/details/gt2ablvrxdh.html

int a = 10; printf("%d\n", a);
来源：http://dali.cucudq.cn/Article/details/gt2wzmkewqa.html

[S03] C：读入整数
来源：http://dali.9152youxi.cn/Article/details/gt2llukajto.html

int x; scanf("%d", &x);
来源：http://dali.yj20258888.top/Article/details/gt2submmriy.html

[S04] C：字符串复制
来源：http://dali.snrcjt.cn/Article/details/gt2nzwymibj.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.vqdsnc.cn/Article/details/gt2vudmgzwq.html

[S05] C：字符串长度
来源：http://dali.daria6918.cn/Article/details/gt2lvtfxcyv.html

strlen(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2ohhbgsii.html

[S06] C：字符串比较
来源：http://dali.fengsongda.top/Article/details/gt2hposzrkp.html

strcmp(a, b) == 0
来源：http://dali.zhengqikj.top/Article/details/gt2fegbkzbx.html

[S07] C：数组遍历求和
来源：http://dali.jianghu66.top/Article/details/gt2qsytlmqg.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.dashuyun.cn/Article/details/gt2rxrkfbqo.html

[S08] C：动态内存分配与释放
来源：http://dali.jyoumei.cn/Article/details/gt2rofnxsid.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yongpay.top/Article/details/gt2nawicipn.html

[S09] C：结构体定义与初始化
来源：http://dali.havefunace.top/Article/details/gt2ggroqbqw.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ivvv.top/Article/details/gt2plzsgyio.html

[S10] C：指针与解引用
来源：http://dali.chenlongwang.top/Article/details/gt2dnpnnvyd.html

int *p = &a;  *p = 5;
来源：http://dali.shzxlz.cn/Article/details/gt2yfbqvkvt.html

[S11] C：逐行读文件
来源：http://dali.jinqigfzy.top/Article/details/gt2zktdujsk.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.cucudq.cn/Article/details/gt2dlzesjix.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yuanzhike.top/Article/details/gt2nnfdpjyt.html

fclose(f);
来源：http://dali.nanxuanxn.top/Article/details/gt2mgqascqt.html

[S12] C：写文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zezfvuss.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.sweek.top/Article/details/gt2smywspfq.html

[S13] C：宏定义
来源：http://dali.shuidangran.top/Article/details/gt2zefqdzpd.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.aibaodan.cn/Article/details/gt2givcgtnw.html

[S14] C：枚举
来源：http://dali.jyoumei.cn/Article/details/gt2pdzsjslw.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.smart0.xyz/Article/details/gt2jnebsdam.html

[S15] C：类型转换
来源：http://dali.hfpthk.cn/Article/details/gt2mhnpyqtr.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ubsiesyy.html

[S16] C：位操作置位
来源：http://dali.zhengqikj.top/Article/details/gt2hnhexjer.html

x |= (1 << 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yfpibusv.html

[S17] C：安全拼接字符串
来源：http://dali.yueranfly.top/Article/details/gt2ulezgzhu.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ppjwa.cn/Article/details/gt2dvahlmwt.html

[S18] C：命令行参数
来源：http://dali.c1oappe.top/Article/details/gt2hfwqhbzu.html

int main(int argc, char **argv)
来源：http://dali.dianchejie.cn/Article/details/gt2fntlzefj.html

[S19] C：快速排序
来源：http://dali.ppjwa.cn/Article/details/gt2wvuosfyq.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tkfhuxdb.html

[S20] C：二分查找
来源：http://dali.yvedp.cn/Article/details/gt2ygyhbuqi.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cdwnrqfv.html

[S21] C：字符类别判断
来源：http://dali.c1oappe.top/Article/details/gt2ixidpoly.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.daxiang520.top/Article/details/gt2ojpfpnpn.html

[S22] C：字符串转数字
来源：http://dali.c1oappe.top/Article/details/gt2xbifvzkg.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mhjtuhcx.html

[S23] C：随机数
来源：http://dali.cdnleiting.top/Article/details/gt2qkwfczmw.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jlsjyb.cn/Article/details/gt2dhhwmuns.html

[S24] C：获取本地时间
来源：http://dali.quarkkingdee.top/Article/details/gt2kmrrpnrt.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.meibo888.top/Article/details/gt2dkhtposz.html

[S25] C：内存拷贝
来源：http://dali.dashuyun.cn/Article/details/gt2shfulpvh.html

memcpy(dst, src, n);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ykegbjjw.html

[S26] C：内存清零
来源：http://dali.wangshuangyany.cn/Article/details/gt2kxdacjki.html

memset(a, 0, sizeof a);
来源：http://dali.zhongyouzk.top/Article/details/gt2tocrksnt.html

[S27] C：定义常量
来源：http://dali.yj202588.top/Article/details/gt2gjbluvnw.html

const double PI = 3.14159;
来源：http://dali.0kj1m.cn/Article/details/gt2sczkrriz.html

[S28] C：静态变量
来源：http://dali.hammf.cn/Article/details/gt2ljlvfprb.html

static int counter = 0;
来源：http://dali.xziqi.cn/Article/details/gt2fzudjkfd.html

[S29] C：变参函数
来源：http://dali.cdnleiting.top/Article/details/gt2jjwfpquk.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.pengpengdd.cyou/Article/details/gt2owznpqgx.html

[S30] C：头文件保护
来源：http://dali.cashguo.top/Article/details/gt2akutfgxk.html


<!-- 参考信息 -->