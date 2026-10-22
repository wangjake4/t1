代发 wailian999

[Q63] 开启事务
来源：http://dali.jqgufenzy.top/Article/details/gt2ewdamsxn.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jlsjyb.cn/Article/details/gt2wvstoxqq.html

[Q64] 提交事务
来源：http://dali.cashguo.top/Article/details/gt2mtwvmqao.html

COMMIT;
来源：http://dali.tian-w.cn/Article/details/gt2kkjyykia.html

[Q65] 回滚事务
来源：http://dali.andypj.xyz/Article/details/gt2jwkvzdqh.html

ROLLBACK;
来源：http://dali.fzhhl.top/Article/details/gt2zhjtjhoj.html

[Q66] 行锁查询
来源：http://dali.tianlin.xyz/Article/details/gt2lxdtjuou.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vkqnghgv.html

[Q67] 设置隔离级别
来源：http://dali.yj20258.top/Article/details/gt2bnekkajx.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.hnxiangtu.top/Article/details/gt2mijixppg.html

[Q68] 保存点
来源：http://dali.xuanzx.com/Article/details/gt2qqxfkqht.html

SAVEPOINT sp1;
来源：http://dali.yonumen.top/Article/details/gt2rquadnkb.html

ROLLBACK TO sp1;
来源：http://dali.zycfv.cn/Article/details/gt2lqmhborv.html

[Q69] 查看执行计划
来源：http://dali.tian-w.cn/Article/details/gt2jwnjrijr.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.xinyue.icu/Article/details/gt2rozsjetr.html

[Q70] 更新统计信息
来源：http://dali.cheryme.top/Article/details/gt2hfxzmndi.html

ANALYZE TABLE users;
来源：http://dali.zdqjudy.top/Article/details/gt2wenlfomv.html

[Q71] 查看建表语句
来源：http://dali.hywenlv.cn/Article/details/gt2tcrcgvad.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.feifeiyinyue.top/Article/details/gt2hcgcpdzu.html

[Q72] 查看索引
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gzpxtygf.html

SHOW INDEX FROM users;
来源：http://dali.cucudq.cn/Article/details/gt2dnwvqxua.html

[Q73] 查看表状态
来源：http://dali.chenjidiqi.icu/Article/details/gt2vamrugti.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.hywenlv.cn/Article/details/gt2vkzxtfkw.html

[Q74] 强制使用索引
来源：http://dali.fengsongda.top/Article/details/gt2hxiqptjd.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yj20258888.top/Article/details/gt2xseesjfn.html

[Q75] 日期格式化
来源：http://dali.jqgfzy.top/Article/details/gt2boaprwml.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.cashguo.top/Article/details/gt2kfmcxckm.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.dashuyun.cn/Article/details/gt2xyeqzzbl.html

[Q76] 按天统计
来源：http://dali.yj20258888.top/Article/details/gt2uavygehp.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhiwuduotai.top/Article/details/gt2rqtexaxj.html

[Q77] 时间加减
来源：http://dali.yj202588.top/Article/details/gt2dhzdcqdy.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.mhx1999.top/Article/details/gt2cqkmmjsd.html

[Q78] 当前时间
来源：http://dali.yonumen.top/Article/details/gt2ujgnwkue.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jinqigufen.top/Article/details/gt2dqveocav.html

[Q79] 字符串拼接
来源：http://dali.0kj1m.cn/Article/details/gt2knpsulya.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.hnqzz.top/Article/details/gt2vgbzjejp.html

[Q80] 字符串截取
来源：http://dali.tianlin.xyz/Article/details/gt2nxleajug.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yueranfly.top/Article/details/gt2ftuhtflx.html

[Q81] 字符串替换
来源：http://dali.tian-w.cn/Article/details/gt2vlxdfgkd.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.dashuyun.cn/Article/details/gt2krwiooae.html

[Q82] 字符长度与字节长度
来源：http://dali.shzxlz.cn/Article/details/gt2pkeqtelt.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gt2kldevhyp.html

[Q83] 大小写转换
来源：http://dali.zhixingplan.top/Article/details/gt2uyoubhve.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.snrcjt.cn/Article/details/gt2atykubza.html

[Q84] 去除首尾空格
来源：http://dali.yueranfly.top/Article/details/gt2mvrbwhge.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gt2czzqjhee.html

[Q85] 数值取整
来源：http://dali.jinqigfzy.top/Article/details/gt2sqnftpgi.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.cashguo.top/Article/details/gt2mnergxlw.html

[Q86] 读取 JSON 字段
来源：http://dali.yonumen.top/Article/details/gt2rnynmxme.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.feifeiyinyue.top/Article/details/gt2tbkovcgl.html

[Q87] JSON 字段做条件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2woeymmpi.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.daria6918.cn/Article/details/gt2mkjrmyjj.html

[Q88] 行转列（条件聚合）
来源：http://dali.shzxlz.cn/Article/details/gt2decshtkm.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.cqqwz.cn/Article/details/gt2vxejziof.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.bjfxy.top/Article/details/gt2kvqzjpjk.html

[Q89] 判断表是否存在
来源：http://dali.zycfv.cn/Article/details/gt2twgocugc.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.daria6918.cn/Article/details/gt2rimgrrhv.html

[Q90] 生成序号列
来源：http://dali.hysaishi.cn/Article/details/gt2zsytpicx.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.guannengcc.top/Article/details/gt2ysiqbpnw.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2exeqwzuu.html

R. Bash 专题
来源：http://dali.gaohongyu789.top/Article/details/gt2nrqghiyy.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2tenbgxuq.html

[R01] shebang 与严格模式
来源：http://dali.tanke756.top/Article/details/gt2eabgpsdj.html

#!/usr/bin/env bash
来源：http://dali.xuanzx.com/Article/details/gt2ivrcfbgx.html

set -euo pipefail
来源：http://dali.cheryme.top/Article/details/gt2xurhxziy.html

[R02] 变量赋值与使用
来源：http://dali.cheryme.top/Article/details/gt2gtppygib.html

name="Tom"; echo "$name"
来源：http://dali.fengsongda.top/Article/details/gt2thzdvxti.html

[R03] 只读变量
来源：http://dali.dashuyun.cn/Article/details/gt2okkrxvgb.html

readonly PI=3.14
来源：http://dali.chenjidiqi.icu/Article/details/gt2zgysfjcs.html

[R04] 位置参数
来源：http://dali.9152youxi.cn/Article/details/gt2lhlbasau.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.shangyingyoupin.top/Article/details/gt2upxyezgk.html

[R05] 参数默认值
来源：http://dali.cdnleiting.top/Article/details/gt2yhsxhaal.html

name="${1:-default}"
来源：http://dali.9152youxi.cn/Article/details/gt2stfvejuy.html

[R06] 判断命令是否存在
来源：http://dali.yanxiufei.cn/Article/details/gt2acwcohka.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.9152youxi.cn/Article/details/gt2ndzmttcp.html

[R07] if 判断文件
来源：http://dali.ivvv.top/Article/details/gt2vuipynrk.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.fzhhl.top/Article/details/gt2httefnnf.html

[R08] 数值比较
来源：http://dali.yueranfly.top/Article/details/gt2tbgdfjey.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.chenlongwang.top/Article/details/gt2habnkzfh.html

[R09] 字符串比较
来源：http://dali.birdmap.top/Article/details/gt2mtvumtzf.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.ybcxt.top/Article/details/gt2biveskzl.html

[R10] 正则匹配
来源：http://dali.nanxinkj.top/Article/details/gt2kkfswamu.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jiagoushi.top/Article/details/gt2edseikli.html

[R11] case 多分支
来源：http://dali.aizwys.cn/Article/details/gt2nperqqkm.html

case "$1" in
来源：http://dali.hnqzz.top/Article/details/gt2zugpjnvd.html

start) echo "启动" ;;
来源：http://dali.yueranfly.top/Article/details/gt2tstwryib.html

stop)  echo "停止" ;;
来源：http://dali.andypj.xyz/Article/details/gt2rgalqcfj.html

*)     echo "未知命令" ;;
来源：http://dali.ydzc1.top/Article/details/gt2acyvgpza.html

esac
来源：http://dali.jyoumei.cn/Article/details/gt2zvqshkyv.html

[R12] for 遍历文件
来源：http://dali.birdmap.top/Article/details/gt2zxntvqag.html

for f in *.txt; do echo "$f"; done
来源：http://dali.ydzc1.top/Article/details/gt2daaydsnk.html

[R13] for 计数循环
来源：http://dali.yueranfly.top/Article/details/gt2pdvegway.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hongshengwenyu.top/Article/details/gt2gzljvlpo.html

[R14] C 风格 for
来源：http://dali.vqdsnc.cn/Article/details/gt2chhhopee.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.sweek.top/Article/details/gt2rhcfsmoa.html

[R15] while 逐行读文件
来源：http://dali.yj20258888.top/Article/details/gt2nbgchegw.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.meibo888.top/Article/details/gt2fikmdgco.html

[R16] until 等待条件
来源：http://dali.pycfn.com/Article/details/gt2jikppezw.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.quarkkingdee.top/Article/details/gt2envzpyqw.html

[R17] 数组定义与取值
来源：http://dali.shuidangran.top/Article/details/gt2lznsxxxr.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.ybcxt.top/Article/details/gt2lnulsvsz.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2vmersanc.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.smart0.xyz/Article/details/gt2ducbjimi.html

[R19] 数组长度
来源：http://dali.chenzaomai.com/Article/details/gt2bsszskdq.html

echo "${#arr[@]}"
来源：http://dali.jyoumei.cn/Article/details/gt2cqzkfyxf.html

[R20] 关联数组（字典）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nhqrcxzw.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.tianlin.xyz/Article/details/gt2kvmfplmz.html

[R21] 字符串长度
来源：http://dali.hammf.cn/Article/details/gt2ekpszyez.html

echo "${#s}"
来源：http://dali.jqgufenzy.top/Article/details/gt2ngpuntpm.html

[R22] 截取子串
来源：http://dali.pycfn.com/Article/details/gt2vycmyosk.html

echo "${s:0:5}"
来源：http://dali.zhiwuduotai.top/Article/details/gt2wrnvgsyz.html

[R23] 字符串替换
来源：http://dali.vqdsnc.cn/Article/details/gt2vzttsrzy.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.gotoacloud.top/Article/details/gt2xryfvese.html

[R24] 大小写转换
来源：http://dali.guowangkeji.top/Article/details/gt2mqcavaqe.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.xuanzx.com/Article/details/gt2uqztvgwo.html

[R25] 去后缀 / 去前缀
来源：http://dali.cashguo.top/Article/details/gt2leevrpbx.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jinqigfzy.top/Article/details/gt2tftqafgc.html

[R26] 命令替换
来源：http://dali.zhengqikj.top/Article/details/gt2awvuxspu.html

now=$(date +%F); echo "$now"
来源：http://dali.hywenlv.cn/Article/details/gt2erloplzh.html

[R27] 算术展开
来源：http://dali.tian-w.cn/Article/details/gt2dklbtdfj.html

echo $((1 + 2 * 3))
来源：http://dali.smart0.xyz/Article/details/gt2aypccelg.html

[R28] 浮点运算
来源：http://dali.nwbrower.top/Article/details/gt2cohisgyn.html

echo "scale=2; 10/3" | bc
来源：http://dali.xinyue.icu/Article/details/gt2yhotmrnn.html

[R29] 定义函数
来源：http://dali.feifeiyinyue.top/Article/details/gt2rwryxqkq.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.cdnleiting.top/Article/details/gt2nyujqlpq.html

[R30] 函数返回状态码
来源：http://dali.snrcjt.cn/Article/details/gt2ulkxrngw.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.daria6918.cn/Article/details/gt2smuipllz.html

[R31] 局部变量
来源：http://dali.birdmap.top/Article/details/gt2nkwwkzho.html

f() { local x=1; echo "$x"; }
来源：http://dali.vqdsnc.cn/Article/details/gt2oiuryytz.html

[R32] 参数个数校验
来源：http://dali.316326.xyz/Article/details/gt2hbtitybg.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zdqjudy.top/Article/details/gt2lfjsattx.html

[R33] 捕获错误并提示行号
来源：http://dali.yuanzhike.top/Article/details/gt2bhufcbmu.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.haohaochexian.top/Article/details/gt2rojgaqbg.html

[R34] 退出时清理
来源：http://dali.wangdashe.top/Article/details/gt2vnihmtxr.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yj202588.top/Article/details/gt2opbgqhzi.html

[R35] 后台执行并等待
来源：http://dali.yj20258888.top/Article/details/gt2iofhojdh.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.snrcjt.cn/Article/details/gt2jqfztdpg.html

[R36] 并发执行多个任务
来源：http://dali.chenjidiqi.icu/Article/details/gt2sxgxmshx.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.cqqwz.cn/Article/details/gt2spppulkn.html

[R37] 把输出赋给变量
来源：http://dali.ybcxt.top/Article/details/gt2yinolcuf.html

files=$(ls -1)
来源：http://dali.cqqwz.cn/Article/details/gt2hjfudgpd.html

[R38] 管道串联
来源：http://dali.xylfe.cn/Article/details/gt2aiggrhqu.html

cat a.txt | grep -i error | wc -l
来源：http://dali.gotoacloud.top/Article/details/gt2fedfngkr.html

[R39] 重定向标准输出与错误
来源：http://dali.9152youxi.cn/Article/details/gt2ixagnmwb.html

cmd > out.log 2>&1
来源：http://dali.gotoacloud.top/Article/details/gt2fwqfgory.html

[R40] 追加写日志
来源：http://dali.ydzc1.top/Article/details/gt2tfmjitkl.html

echo "log" >> out.log
来源：http://dali.xylfe.cn/Article/details/gt2daqzgvpn.html

[R41] 丢弃输出
来源：http://dali.jiagoushi.top/Article/details/gt2rxsmetle.html

cmd >/dev/null 2>&1
来源：http://dali.cdnleiting.top/Article/details/gt2zxqhqizy.html

[R42] 输入重定向
来源：http://dali.hnxiangtu.top/Article/details/gt2iqwohbjx.html

wc -l < a.txt
来源：http://dali.hongshengwenyu.top/Article/details/gt2peqximfl.html

[R43] 按名字查找文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xezntxln.html

find . -name "*.log" -type f
来源：http://dali.zhoulong.xyz/Article/details/gt2yrdnfhkp.html

[R44] 按修改时间查找
来源：http://dali.yanxiufei.cn/Article/details/gt2xzhiyvbh.html

find . -mtime -7 -type f
来源：http://dali.nanxuanxn.top/Article/details/gt2ijbfflcx.html

[R45] 批量删除
来源：http://dali.yuanzhike.top/Article/details/gt2memqufdr.html

find . -name "*.tmp" -delete
来源：http://dali.birdmap.top/Article/details/gt2egvssewv.html

[R46] 递归替换文件内容
来源：http://dali.redwolf501.top/Article/details/gt2xzrroahq.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.fzhhl.top/Article/details/gt2rthbtsst.html

[R47] sed 单行替换
来源：http://dali.dianchejie.cn/Article/details/gt2zqrrigum.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hammf.cn/Article/details/gt2vseeabvq.html

[R48] awk 取指定列
来源：http://dali.yongpay.top/Article/details/gt2umlfucmb.html

awk '{print $1, $3}' a.txt
来源：http://dali.zycfv.cn/Article/details/gt2tbshcdvx.html

[R49] awk 带条件
来源：http://dali.smart0.xyz/Article/details/gt2drauqawr.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jyoumei.cn/Article/details/gt2okhqzcac.html

[R50] awk 求和
来源：http://dali.jianghu66.top/Article/details/gt2zypfpdwr.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.daria6918.cn/Article/details/gt2tmcveogy.html

[R51] 排序去重取前几
来源：http://dali.yueranfly.top/Article/details/gt2ukoyxkmo.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yueranfly.top/Article/details/gt2sfswvtwg.html

[R52] 统计行数
来源：http://dali.jinqigfzy.top/Article/details/gt2sqfjfnrn.html

wc -l a.txt
来源：http://dali.xylfe.cn/Article/details/gt2hpzhezla.html

[R53] 查看文件头与实时尾
来源：http://dali.wangshuangyany.cn/Article/details/gt2isbkrzsh.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jinqigfzy.top/Article/details/gt2udjjounr.html

[R54] 比较两个文件
来源：http://dali.yvedp.cn/Article/details/gt2uadrpxso.html

diff a.txt b.txt
来源：http://dali.yuxming.cn/Article/details/gt2bwyuiepo.html

[R55] 压缩与解压
来源：http://dali.zycfv.cn/Article/details/gt2qsaztsyu.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jyoumei.cn/Article/details/gt2eopytclp.html

[R56] 远程拷贝
来源：http://dali.yj20258.top/Article/details/gt2dyhhkdnm.html

scp file user@host:/path/
来源：http://dali.shuidangran.top/Article/details/gt2duykhoaa.html

[R57] 远程执行命令
来源：http://dali.nanxuanxn.top/Article/details/gt2lzxfebbl.html

ssh user@host 'uptime'
来源：http://dali.hongshengwenyu.top/Article/details/gt2urbmsfkr.html

[R58] 下载文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ityygdhx.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yongpay.top/Article/details/gt2syrzzque.html

[R59] 发 POST JSON
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uxlvkvrg.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.ivvv.top/Article/details/gt2hmazmnth.html

[R60] 只看 HTTP 状态码
来源：http://dali.xziqi.cn/Article/details/gt2ozyijqcb.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.nanxuanxn.top/Article/details/gt2urlmnmmz.html

[R61] 磁盘占用
来源：http://dali.zhixingplan.top/Article/details/gt2jmmmxqwr.html

df -h;  du -sh *
来源：http://dali.hammf.cn/Article/details/gt2ggkoryas.html

[R62] 找最占空间的文件
来源：http://dali.gaohongyu789.top/Article/details/gt2bcqrmtfj.html

du -ah . | sort -rh | head -10
来源：http://dali.xinyue.icu/Article/details/gt2orhjuhlu.html

[R63] 内存与进程
来源：http://dali.cashguo.top/Article/details/gt2uieoisrj.html

free -h;  ps aux | grep nginx
来源：http://dali.ivvv.top/Article/details/gt2syxttoix.html

[R64] 结束进程
来源：http://dali.cashguo.top/Article/details/gt2dgjuprrm.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhongyouzk.top/Article/details/gt2xtdybxiz.html

[R65] 查看端口占用
来源：http://dali.xuetiantiany.cn/Article/details/gt2isexzgnv.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hysaishi.cn/Article/details/gt2amojykdu.html

[R66] 定时任务
来源：http://dali.cashguo.top/Article/details/gt2ysfakiei.html

crontab -e;  crontab -l
来源：http://dali.zhixingplan.top/Article/details/gt2chbqgvif.html

[R67] 生成随机十六进制串
来源：http://dali.mhx1999.top/Article/details/gt2xfnevnma.html

openssl rand -hex 16
来源：http://dali.gogol.net.cn/Article/details/gt2fgxktesj.html

[R68] 计算文件校验值
来源：http://dali.cheryme.top/Article/details/gt2olyprplq.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.ppjwa.cn/Article/details/gt2acdfuocq.html

[R69] 生成随机密码
来源：http://dali.yuanzhike.top/Article/details/gt2bvslwleq.html

head -c 16 /dev/urandom | base64
来源：http://dali.vqdsnc.cn/Article/details/gt2msidlofy.html

[R70] 时间戳与互转
来源：http://dali.xziqi.cn/Article/details/gt2dqkaygmh.html

date +%s;  date -d @1700000000
来源：http://dali.nanxinkj.top/Article/details/gt2jymsvavy.html

[R71] 日期格式化
来源：http://dali.gzhubu.top/Article/details/gt2hfkngtha.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.smart0.xyz/Article/details/gt2ntoryfjc.html

[R72] 等待端口就绪
来源：http://dali.sufxvd.cn/Article/details/gt2pppfkuio.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.xylfe.cn/Article/details/gt2pjxiwmmy.html

[R73] 分割大日志
来源：http://dali.wangdashe.top/Article/details/gt2yhepozes.html

split -l 1000 big.log part_
来源：http://dali.nanxinkj.top/Article/details/gt2petsriit.html

[R74] 批量重命名
来源：http://dali.meibo888.top/Article/details/gt2txulwoun.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.dianchejie.cn/Article/details/gt2qlodsbij.html

[R75] 导出环境变量
来源：http://dali.xinyue.icu/Article/details/gt2iluwusyu.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhengqikj.top/Article/details/gt2jasrxvhq.html

[R76] 使用临时文件
来源：http://dali.shzxlz.cn/Article/details/gt2fspyizbl.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.shzxlz.cn/Article/details/gt2kcfmicsb.html

[R77] 读取用户输入
来源：http://dali.yj20258888.top/Article/details/gt2isbjhely.html

read -rp "请输入: " ans
来源：http://dali.cucudq.cn/Article/details/gt2kvtqnjxo.html

[R78] 交互式菜单
来源：http://dali.gogol.net.cn/Article/details/gt2vkgzgevh.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.redwolf501.top/Article/details/gt2mqisozby.html

[R79] 解析命令行选项
来源：http://dali.yueranfly.top/Article/details/gt2nhjnvbef.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jqgfzy.top/Article/details/gt2gbniqvxq.html

[R80] 查看脚本执行耗时
来源：http://dali.pycfn.com/Article/details/gt2nsnnqibs.html

time ./run.sh
来源：http://dali.316326.xyz/Article/details/gt2kjgnvydg.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2rphlympx.html

S. C / C++ 专题
来源：http://dali.wangdashe.top/Article/details/gt2xwhdrwhz.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2ubwwxoaw.html

[S01] C：Hello World
来源：http://dali.hammf.cn/Article/details/gt2poskrkqw.html

#include <stdio.h>
来源：http://dali.guowangkeji.top/Article/details/gt2mtypjawf.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.shuidangran.top/Article/details/gt2xboqeohq.html

[S02] C：变量与格式化输出
来源：http://dali.xinyue.icu/Article/details/gt2popyyutu.html

int a = 10; printf("%d\n", a);
来源：http://dali.havefunace.top/Article/details/gt2jiriarfj.html

[S03] C：读入整数
来源：http://dali.yonumen.top/Article/details/gt2yvpimsve.html

int x; scanf("%d", &x);
来源：http://dali.jinqigfzy.top/Article/details/gt2vujdomlk.html

[S04] C：字符串复制
来源：http://dali.nanxinkj.top/Article/details/gt2uaxrfwit.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.haohaochexian.top/Article/details/gt2bvyqpxdd.html

[S05] C：字符串长度
来源：http://dali.jianghu66.top/Article/details/gt2zeborijo.html

strlen(s)
来源：http://dali.ivvv.top/Article/details/gt2moziruiu.html

[S06] C：字符串比较
来源：http://dali.yonumen.top/Article/details/gt2ilhojehg.html

strcmp(a, b) == 0
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zzcjqzfe.html

[S07] C：数组遍历求和
来源：http://dali.sweek.top/Article/details/gt2udabbqco.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.cashguo.top/Article/details/gt2xtdemmpk.html

[S08] C：动态内存分配与释放
来源：http://dali.jinghuilouyu.cn/Article/details/gt2amvgzkhu.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.nanxinkj.top/Article/details/gt2hsrioiwb.html

[S09] C：结构体定义与初始化
来源：http://dali.cucudq.cn/Article/details/gt2vfknljlm.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhiwuduotai.top/Article/details/gt2wrpzdjac.html

[S10] C：指针与解引用
来源：http://dali.yangfankeji.com/Article/details/gt2tegbhuat.html

int *p = &a;  *p = 5;
来源：http://dali.yuanzhike.top/Article/details/gt2xfxdsrqw.html

[S11] C：逐行读文件
来源：http://dali.wangshuangyany.cn/Article/details/gt2pbpzyauq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.fengsongda.top/Article/details/gt2pgkzqocc.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yangfankeji.com/Article/details/gt2wgocepsj.html

fclose(f);
来源：http://dali.nwbrower.top/Article/details/gt2tlzekqte.html

[S12] C：写文件
来源：http://dali.yj20258888.top/Article/details/gt2zhpvfrot.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qlcspnzw.html

[S13] C：宏定义
来源：http://dali.havefunace.top/Article/details/gt2vnhyllpw.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zdqjudy.top/Article/details/gt2dyikljnp.html

[S14] C：枚举
来源：http://dali.haohaochexian.top/Article/details/gt2rtpiudue.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.bjfxy.top/Article/details/gt2ragkcgri.html

[S15] C：类型转换
来源：http://dali.hfpthk.cn/Article/details/gt2cqclbfgb.html

(double) a / b
来源：http://dali.tian-w.cn/Article/details/gt2anfdrwem.html

[S16] C：位操作置位
来源：http://dali.cheryme.top/Article/details/gt2gxlsfvvv.html

x |= (1 << 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2svvkebwo.html

[S17] C：安全拼接字符串
来源：http://dali.jqgfzy.top/Article/details/gt2ksxmgumy.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.bjfxy.top/Article/details/gt2grxqhttp.html

[S18] C：命令行参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ylhdqlqi.html

int main(int argc, char **argv)
来源：http://dali.pycfn.com/Article/details/gt2awglzlfh.html

[S19] C：快速排序
来源：http://dali.jyoumei.cn/Article/details/gt2esbyjppz.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.316326.xyz/Article/details/gt2yflageio.html

[S20] C：二分查找
来源：http://dali.ybcxt.top/Article/details/gt2wzmnbccb.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yj20258.top/Article/details/gt2anbiutpm.html

[S21] C：字符类别判断
来源：http://dali.hnqzz.top/Article/details/gt2rmwsfoyp.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.redwolf501.top/Article/details/gt2jwsusqpb.html

[S22] C：字符串转数字
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pceurqzm.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.shzxlz.cn/Article/details/gt2wovjpuyf.html

[S23] C：随机数
来源：http://dali.kuanghao11.cn/Article/details/gt2qzhtamnb.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhiwuduotai.top/Article/details/gt2necbhkyt.html

[S24] C：获取本地时间
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rtghnztu.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.quarkkingdee.top/Article/details/gt2gxnzstab.html

[S25] C：内存拷贝
来源：http://dali.hywenlv.cn/Article/details/gt2itplfltu.html

memcpy(dst, src, n);
来源：http://dali.ivvv.top/Article/details/gt2nhvxyisi.html

[S26] C：内存清零
来源：http://dali.yuxming.cn/Article/details/gt2yrvubavu.html

memset(a, 0, sizeof a);
来源：http://dali.ivvv.top/Article/details/gt2gttkeyzc.html

[S27] C：定义常量
来源：http://dali.havefunace.top/Article/details/gt2rsjmkmbm.html

const double PI = 3.14159;
来源：http://dali.redwolf501.top/Article/details/gt2thweakxk.html

[S28] C：静态变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fqrhttqm.html

static int counter = 0;
来源：http://dali.zycfv.cn/Article/details/gt2cpownykf.html

[S29] C：变参函数
来源：http://dali.aibaodan.cn/Article/details/gt2kmfmftxw.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.svipenyu.cn/Article/details/gt2zfmatgdw.html

[S30] C：头文件保护
来源：http://dali.andypj.xyz/Article/details/gt2cqhthesn.html

#ifndef X_H
来源：http://dali.chenlongwang.top/Article/details/gt2whgtxcaw.html

#define X_H
来源：http://dali.hongshengwenyu.top/Article/details/gt2ifvavfyv.html

#endif
来源：http://dali.zhengqikj.top/Article/details/gt2qhsagcmc.html

[S31] C++：Hello World
来源：http://dali.yongpay.top/Article/details/gt2yprxliij.html

#include <iostream>
来源：http://dali.cdnleiting.top/Article/details/gt2quswjxhw.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zycfv.cn/Article/details/gt2nqukxsdi.html

[S32] C++：字符串
来源：http://dali.sufxvd.cn/Article/details/gt2rsvarkzl.html

std::string s = "hi";  s += "!";
来源：http://dali.tanke756.top/Article/details/gt2pggorpob.html


<!-- 参考信息 -->