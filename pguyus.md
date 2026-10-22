代发 wailian999

[Q63] 开启事务
来源：http://dali.zdqjudy.top/Article/details/gt2pllqrbtl.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.xylfe.cn/Article/details/gt2klnvtcxy.html

[Q64] 提交事务
来源：http://dali.cashguo.top/Article/details/gt2qjcslpba.html

COMMIT;
来源：http://dali.9152youxi.cn/Article/details/gt2tvimkejt.html

[Q65] 回滚事务
来源：http://dali.gotoacloud.top/Article/details/gt2uevdgyeb.html

ROLLBACK;
来源：http://dali.quarkkingdee.top/Article/details/gt2yiuodvnr.html

[Q66] 行锁查询
来源：http://dali.pycfn.com/Article/details/gt2nyevkgqa.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jqgfzy.top/Article/details/gt2ndumtqfg.html

[Q67] 设置隔离级别
来源：http://dali.hammf.cn/Article/details/gt2ximehnje.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.guowangkeji.top/Article/details/gt2rioanlqc.html

[Q68] 保存点
来源：http://dali.hysaishi.cn/Article/details/gt2coyovvio.html

SAVEPOINT sp1;
来源：http://dali.nanxuanxn.top/Article/details/gt2qpaaobxc.html

ROLLBACK TO sp1;
来源：http://dali.hywenlv.cn/Article/details/gt2stxxejne.html

[Q69] 查看执行计划
来源：http://dali.cucudq.cn/Article/details/gt2aqwkqfka.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.tanke756.top/Article/details/gt2abggyczl.html

[Q70] 更新统计信息
来源：http://dali.svipenyu.cn/Article/details/gt2jmtaniyi.html

ANALYZE TABLE users;
来源：http://dali.hammf.cn/Article/details/gt2vjkmtvig.html

[Q71] 查看建表语句
来源：http://dali.yj20258888.top/Article/details/gt2msuospid.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.cqqwz.cn/Article/details/gt2hgbcwzzu.html

[Q72] 查看索引
来源：http://dali.jinqigfzy.top/Article/details/gt2luwpcjga.html

SHOW INDEX FROM users;
来源：http://dali.xziqi.cn/Article/details/gt2nfsybqas.html

[Q73] 查看表状态
来源：http://dali.gotoacloud.top/Article/details/gt2xuvwxmum.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.nanxinkj.top/Article/details/gt2vbpmybce.html

[Q74] 强制使用索引
来源：http://dali.xziqi.cn/Article/details/gt2zmizmacw.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hfpthk.cn/Article/details/gt2yczkzeii.html

[Q75] 日期格式化
来源：http://dali.xuanzx.com/Article/details/gt2obzxpspb.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.gogol.net.cn/Article/details/gt2idptukig.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.daria6918.cn/Article/details/gt2ealpchfs.html

[Q76] 按天统计
来源：http://dali.daria6918.cn/Article/details/gt2qijwhvvd.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mfdylbvl.html

[Q77] 时间加减
来源：http://dali.mhx1999.top/Article/details/gt2pylzdouj.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.dianchejie.cn/Article/details/gt2gmtpuazb.html

[Q78] 当前时间
来源：http://dali.nanxuanxn.top/Article/details/gt2snelsurx.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yangfankeji.com/Article/details/gt2jppkyflm.html

[Q79] 字符串拼接
来源：http://dali.xuanzx.com/Article/details/gt2joqoiqhc.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.pycfn.com/Article/details/gt2vnwksrdo.html

[Q80] 字符串截取
来源：http://dali.hysaishi.cn/Article/details/gt2xtjmkuer.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yonumen.top/Article/details/gt2hmxoedoh.html

[Q81] 字符串替换
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wznlqczy.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.daria6918.cn/Article/details/gt2bcvkdkex.html

[Q82] 字符长度与字节长度
来源：http://dali.zhoulong.xyz/Article/details/gt2qgbpbpyp.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.aibaodan.cn/Article/details/gt2uobzbhoe.html

[Q83] 大小写转换
来源：http://dali.andypj.xyz/Article/details/gt2kcookdcn.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yj20258.top/Article/details/gt2xzcngzag.html

[Q84] 去除首尾空格
来源：http://dali.havefunace.top/Article/details/gt2oofokpwe.html

SELECT TRIM(name) FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jfimnqji.html

[Q85] 数值取整
来源：http://dali.yongpay.top/Article/details/gt2wiytbfvs.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.aizwys.cn/Article/details/gt2njeukrwm.html

[Q86] 读取 JSON 字段
来源：http://dali.smart0.xyz/Article/details/gt2fafxnqpt.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.cashguo.top/Article/details/gt2srkfmxlw.html

[Q87] JSON 字段做条件
来源：http://dali.zycfv.cn/Article/details/gt2btjxoadn.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yj202588.top/Article/details/gt2virlqsxe.html

[Q88] 行转列（条件聚合）
来源：http://dali.hnxiangtu.top/Article/details/gt2qsdbednj.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jyoumei.cn/Article/details/gt2hwrpuhye.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zdqjudy.top/Article/details/gt2inysyxie.html

[Q89] 判断表是否存在
来源：http://dali.yuxming.cn/Article/details/gt2ehvfhxti.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.cashguo.top/Article/details/gt2flzvaxlg.html

[Q90] 生成序号列
来源：http://dali.yangfankeji.com/Article/details/gt2ldwbxonh.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.sxryk.cn/Article/details/gt2zxvsewjr.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2iurskqth.html

R. Bash 专题
来源：http://dali.yuxming.cn/Article/details/gt2vydsktex.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2owgbhjlx.html

[R01] shebang 与严格模式
来源：http://dali.hnxiangtu.top/Article/details/gt2jhgjapda.html

#!/usr/bin/env bash
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pjdpqndm.html

set -euo pipefail
来源：http://dali.chenzaomai.com/Article/details/gt2opxcxmzi.html

[R02] 变量赋值与使用
来源：http://dali.fzhhl.top/Article/details/gt2pxkwbrpq.html

name="Tom"; echo "$name"
来源：http://dali.hnqzz.top/Article/details/gt2bnusggsv.html

[R03] 只读变量
来源：http://dali.zhengqikj.top/Article/details/gt2aptlqmof.html

readonly PI=3.14
来源：http://dali.yanxiufei.cn/Article/details/gt2whtkmdvj.html

[R04] 位置参数
来源：http://dali.jlsjyb.cn/Article/details/gt2cojkumau.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yj20258888.top/Article/details/gt2tabknefl.html

[R05] 参数默认值
来源：http://dali.redwolf501.top/Article/details/gt2vmigommq.html

name="${1:-default}"
来源：http://dali.hnxiangtu.top/Article/details/gt2tdhqcarv.html

[R06] 判断命令是否存在
来源：http://dali.redwolf501.top/Article/details/gt2fwkomjfj.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.daria6918.cn/Article/details/gt2uccekkal.html

[R07] if 判断文件
来源：http://dali.ehwqpu.com/Article/details/gt2hxknaxvb.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.cucudq.cn/Article/details/gt2lcqmayle.html

[R08] 数值比较
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ctvtcnox.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yangfankeji.com/Article/details/gt2vlqnsyzf.html

[R09] 字符串比较
来源：http://dali.cqqwz.cn/Article/details/gt2kkeojyhy.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jlsjyb.cn/Article/details/gt2kcporsxc.html

[R10] 正则匹配
来源：http://dali.daxiang520.top/Article/details/gt2mrnyhzhk.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.0kj1m.cn/Article/details/gt2vlnkafsr.html

[R11] case 多分支
来源：http://dali.yj20258888.top/Article/details/gt2tzoryngs.html

case "$1" in
来源：http://dali.svipenyu.cn/Article/details/gt2bycdjbjn.html

start) echo "启动" ;;
来源：http://dali.yj202588.top/Article/details/gt2fcovnsnd.html

stop)  echo "停止" ;;
来源：http://dali.fzhhl.top/Article/details/gt2rvjizznw.html

*)     echo "未知命令" ;;
来源：http://dali.ppjwa.cn/Article/details/gt2cfoccvnb.html

esac
来源：http://dali.cucudq.cn/Article/details/gt2rzmwdjij.html

[R12] for 遍历文件
来源：http://dali.pycfn.com/Article/details/gt2jefmuikw.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jlsjyb.cn/Article/details/gt2jeieyjlu.html

[R13] for 计数循环
来源：http://dali.hysaishi.cn/Article/details/gt2mnaonttt.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.shangyingyoupin.top/Article/details/gt2vgqnrqqx.html

[R14] C 风格 for
来源：http://dali.hywenlv.cn/Article/details/gt2wdsmfdpx.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yj202588.top/Article/details/gt2xonvqmug.html

[R15] while 逐行读文件
来源：http://dali.kuanghao11.cn/Article/details/gt2tubbpwmp.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yj202588.top/Article/details/gt2yqqpuhlx.html

[R16] until 等待条件
来源：http://dali.daria6918.cn/Article/details/gt2xjtpqcuw.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.hnxiangtu.top/Article/details/gt2ficdrlip.html

[R17] 数组定义与取值
来源：http://dali.yanxiufei.cn/Article/details/gt2refuyqab.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jianghu66.top/Article/details/gt2bgooufwp.html

[R18] 遍历数组
来源：http://dali.shangyingyoupin.top/Article/details/gt2dektjkyv.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.sufxvd.cn/Article/details/gt2zxherhdp.html

[R19] 数组长度
来源：http://dali.zhoulong.xyz/Article/details/gt2ljhoocnh.html

echo "${#arr[@]}"
来源：http://dali.zdqjudy.top/Article/details/gt2ppwjvgzc.html

[R20] 关联数组（字典）
来源：http://dali.wangshuangyany.cn/Article/details/gt2dgqmkelz.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.ppjwa.cn/Article/details/gt2plkpyspi.html

[R21] 字符串长度
来源：http://dali.cheryme.top/Article/details/gt2qeogxien.html

echo "${#s}"
来源：http://dali.cqqwz.cn/Article/details/gt2wejesjdt.html

[R22] 截取子串
来源：http://dali.nanxuanxn.top/Article/details/gt2ixabmgut.html

echo "${s:0:5}"
来源：http://dali.jinqigufen.top/Article/details/gt2yreqwsoj.html

[R23] 字符串替换
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jyrlcsps.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.sxryk.cn/Article/details/gt2veusvgmg.html

[R24] 大小写转换
来源：http://dali.chenjidiqi.icu/Article/details/gt2rtxbtbyd.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.shzxlz.cn/Article/details/gt2wwjjoisk.html

[R25] 去后缀 / 去前缀
来源：http://dali.kuanghao11.cn/Article/details/gt2umscmnre.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hnxiangtu.top/Article/details/gt2zfhpxptw.html

[R26] 命令替换
来源：http://dali.mhx1999.top/Article/details/gt2ljfroovo.html

now=$(date +%F); echo "$now"
来源：http://dali.kuanghao11.cn/Article/details/gt2wlwjupzv.html

[R27] 算术展开
来源：http://dali.316326.xyz/Article/details/gt2cypytlxv.html

echo $((1 + 2 * 3))
来源：http://dali.xziqi.cn/Article/details/gt2lruntyox.html

[R28] 浮点运算
来源：http://dali.ehwqpu.com/Article/details/gt2xwcwacbu.html

echo "scale=2; 10/3" | bc
来源：http://dali.c1oappe.top/Article/details/gt2oirqbrag.html

[R29] 定义函数
来源：http://dali.jinqigfzy.top/Article/details/gt2hhgozebm.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yj202588.top/Article/details/gt2tphtunsj.html

[R30] 函数返回状态码
来源：http://dali.jinqigufen.top/Article/details/gt2ylekaqgn.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.kuanghao11.cn/Article/details/gt2nngbmpsv.html

[R31] 局部变量
来源：http://dali.yonumen.top/Article/details/gt2dzxadcnj.html

f() { local x=1; echo "$x"; }
来源：http://dali.nwbrower.top/Article/details/gt2hylnuweh.html

[R32] 参数个数校验
来源：http://dali.feifeiyinyue.top/Article/details/gt2nklflnrs.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2zdlgsikm.html

[R33] 捕获错误并提示行号
来源：http://dali.yongpay.top/Article/details/gt2amuygdxs.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.chenjidiqi.icu/Article/details/gt2nlecoeic.html

[R34] 退出时清理
来源：http://dali.hysaishi.cn/Article/details/gt2wnpzhbdw.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.gaohongyu789.top/Article/details/gt2zhuyfcdk.html

[R35] 后台执行并等待
来源：http://dali.yj20258888.top/Article/details/gt2mzufcffm.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.sufxvd.cn/Article/details/gt2owcrqpfb.html

[R36] 并发执行多个任务
来源：http://dali.sxryk.cn/Article/details/gt2gjyxnfxk.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhongyouzk.top/Article/details/gt2bbcsglhq.html

[R37] 把输出赋给变量
来源：http://dali.tianlin.xyz/Article/details/gt2csgctmns.html

files=$(ls -1)
来源：http://dali.cheryme.top/Article/details/gt2tgetizep.html

[R38] 管道串联
来源：http://dali.jqgfzy.top/Article/details/gt2hlbovhcp.html

cat a.txt | grep -i error | wc -l
来源：http://dali.snrcjt.cn/Article/details/gt2bqpzhrnm.html

[R39] 重定向标准输出与错误
来源：http://dali.dashuyun.cn/Article/details/gt2fcxiidoa.html

cmd > out.log 2>&1
来源：http://dali.snrcjt.cn/Article/details/gt2eoliajnv.html

[R40] 追加写日志
来源：http://dali.aizwys.cn/Article/details/gt2zhkddnfs.html

echo "log" >> out.log
来源：http://dali.sufxvd.cn/Article/details/gt2jmuwekqv.html

[R41] 丢弃输出
来源：http://dali.haohaochexian.top/Article/details/gt2fiyuqwxx.html

cmd >/dev/null 2>&1
来源：http://dali.yuxming.cn/Article/details/gt2ccsgwkpo.html

[R42] 输入重定向
来源：http://dali.andypj.xyz/Article/details/gt2fqnwjvhd.html

wc -l < a.txt
来源：http://dali.shzxlz.cn/Article/details/gt2fwnklqwu.html

[R43] 按名字查找文件
来源：http://dali.chenlongwang.top/Article/details/gt2duzfvitz.html

find . -name "*.log" -type f
来源：http://dali.guannengcc.top/Article/details/gt2lovqrmtt.html

[R44] 按修改时间查找
来源：http://dali.birdmap.top/Article/details/gt2ftwvizkq.html

find . -mtime -7 -type f
来源：http://dali.cucudq.cn/Article/details/gt2stwxwzve.html

[R45] 批量删除
来源：http://dali.hongshengwenyu.top/Article/details/gt2fdiovpxc.html

find . -name "*.tmp" -delete
来源：http://dali.zhengqikj.top/Article/details/gt2jijvhcvt.html

[R46] 递归替换文件内容
来源：http://dali.hongshengwenyu.top/Article/details/gt2bbixpyes.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.dianchejie.cn/Article/details/gt2ohdbyzyg.html

[R47] sed 单行替换
来源：http://dali.yonumen.top/Article/details/gt2hyyemvuk.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uqvrxwgy.html

[R48] awk 取指定列
来源：http://dali.jinqigfzy.top/Article/details/gt2vejopacu.html

awk '{print $1, $3}' a.txt
来源：http://dali.daxiang520.top/Article/details/gt2vugqwzuw.html

[R49] awk 带条件
来源：http://dali.yuanzhike.top/Article/details/gt2vrtgdomq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.daria6918.cn/Article/details/gt2uwsrcpkf.html

[R50] awk 求和
来源：http://dali.fengsongda.top/Article/details/gt2wqidfurc.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.dashuyun.cn/Article/details/gt2zaapafgc.html

[R51] 排序去重取前几
来源：http://dali.9152youxi.cn/Article/details/gt2vwqxjcvv.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.wangshuangyany.cn/Article/details/gt2hjmrfsos.html

[R52] 统计行数
来源：http://dali.cqqwz.cn/Article/details/gt2pfiitbhz.html

wc -l a.txt
来源：http://dali.shangyingyoupin.top/Article/details/gt2totpnbmi.html

[R53] 查看文件头与实时尾
来源：http://dali.ppjwa.cn/Article/details/gt2kxkutmbf.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jqgfzy.top/Article/details/gt2ojtywoby.html

[R54] 比较两个文件
来源：http://dali.vqdsnc.cn/Article/details/gt2gwsudzhf.html

diff a.txt b.txt
来源：http://dali.hnqzz.top/Article/details/gt2pedkkhxt.html

[R55] 压缩与解压
来源：http://dali.yuanzhike.top/Article/details/gt2qjwelnwo.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.tanke756.top/Article/details/gt2usoyqqed.html

[R56] 远程拷贝
来源：http://dali.fzhhl.top/Article/details/gt2dwudkiqx.html

scp file user@host:/path/
来源：http://dali.ppjwa.cn/Article/details/gt2kuaxxuig.html

[R57] 远程执行命令
来源：http://dali.fzhhl.top/Article/details/gt2frytyhkw.html

ssh user@host 'uptime'
来源：http://dali.tian-w.cn/Article/details/gt2mswloqhs.html

[R58] 下载文件
来源：http://dali.guowangkeji.top/Article/details/gt2iinxoanp.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yanxiufei.cn/Article/details/gt2alcdbegj.html

[R59] 发 POST JSON
来源：http://dali.hnqzz.top/Article/details/gt2ibqrdaii.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.xinyue.icu/Article/details/gt2qdiinney.html

[R60] 只看 HTTP 状态码
来源：http://dali.xziqi.cn/Article/details/gt2dvtetcul.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.sysykeji.top/Article/details/gt2virlkteb.html

[R61] 磁盘占用
来源：http://dali.hfpthk.cn/Article/details/gt2vrkjarkj.html

df -h;  du -sh *
来源：http://dali.guannengcc.top/Article/details/gt2knhcsbbm.html

[R62] 找最占空间的文件
来源：http://dali.nanxuanxn.top/Article/details/gt2oegvhhlk.html

du -ah . | sort -rh | head -10
来源：http://dali.chenzaomai.com/Article/details/gt2smkpqwyh.html

[R63] 内存与进程
来源：http://dali.havefunace.top/Article/details/gt2gqfenskh.html

free -h;  ps aux | grep nginx
来源：http://dali.gaohongyu789.top/Article/details/gt2jqkvgcaa.html

[R64] 结束进程
来源：http://dali.gzhubu.top/Article/details/gt2zfochjgk.html

kill -9 $(pgrep -f app.py)
来源：http://dali.cucudq.cn/Article/details/gt2cekrkejd.html

[R65] 查看端口占用
来源：http://dali.guowangkeji.top/Article/details/gt2wuyscnxm.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.ppjwa.cn/Article/details/gt2nmlllzgf.html

[R66] 定时任务
来源：http://dali.tian-w.cn/Article/details/gt2isgkhkol.html

crontab -e;  crontab -l
来源：http://dali.ehwqpu.com/Article/details/gt2sciynmbp.html

[R67] 生成随机十六进制串
来源：http://dali.gzhubu.top/Article/details/gt2abczlwgs.html

openssl rand -hex 16
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uhzlwduu.html

[R68] 计算文件校验值
来源：http://dali.wangshuangyany.cn/Article/details/gt2deujaouo.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jqgfzy.top/Article/details/gt2iciwvzzs.html

[R69] 生成随机密码
来源：http://dali.daxiang520.top/Article/details/gt2pywtsnan.html

head -c 16 /dev/urandom | base64
来源：http://dali.hammf.cn/Article/details/gt2bxhvbfxr.html

[R70] 时间戳与互转
来源：http://dali.xuanzx.com/Article/details/gt2ufyxomqh.html

date +%s;  date -d @1700000000
来源：http://dali.cqqwz.cn/Article/details/gt2xoajgubf.html

[R71] 日期格式化
来源：http://dali.ppjwa.cn/Article/details/gt2feqbyqxq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.aizwys.cn/Article/details/gt2bhxoxbwy.html

[R72] 等待端口就绪
来源：http://dali.sweek.top/Article/details/gt2iovllnzt.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.fzhhl.top/Article/details/gt2dqppaqzr.html

[R73] 分割大日志
来源：http://dali.nanxuanxn.top/Article/details/gt2ximgidfy.html

split -l 1000 big.log part_
来源：http://dali.xuetiantiany.cn/Article/details/gt2fixopfne.html

[R74] 批量重命名
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jncdpjfw.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hfpthk.cn/Article/details/gt2vdtdpfpi.html

[R75] 导出环境变量
来源：http://dali.jqgufenzy.top/Article/details/gt2ivuusurc.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.mhx1999.top/Article/details/gt2dwqjypho.html

[R76] 使用临时文件
来源：http://dali.jqgufenzy.top/Article/details/gt2szgmgeku.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.birdmap.top/Article/details/gt2qnhbizqj.html

[R77] 读取用户输入
来源：http://dali.cheryme.top/Article/details/gt2tsinochp.html

read -rp "请输入: " ans
来源：http://dali.yongpay.top/Article/details/gt2zpimyldv.html

[R78] 交互式菜单
来源：http://dali.fzhhl.top/Article/details/gt2vosavgok.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.aizwys.cn/Article/details/gt2pqrzijir.html

[R79] 解析命令行选项
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mhtxuskc.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.bjfxy.top/Article/details/gt2hcxozfdb.html

[R80] 查看脚本执行耗时
来源：http://dali.zhiwuduotai.top/Article/details/gt2zqyhwzku.html

time ./run.sh
来源：http://dali.aibaodan.cn/Article/details/gt2ekgonvkr.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2aqdlhidr.html

S. C / C++ 专题
来源：http://dali.zhiwuduotai.top/Article/details/gt2yeonadic.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2jfospxio.html

[S01] C：Hello World
来源：http://dali.yueranfly.top/Article/details/gt2fmfklbat.html

#include <stdio.h>
来源：http://dali.jyoumei.cn/Article/details/gt2uhoxagls.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.andypj.xyz/Article/details/gt2iuvuhlmy.html

[S02] C：变量与格式化输出
来源：http://dali.jiagoushi.top/Article/details/gt2uwgukocf.html

int a = 10; printf("%d\n", a);
来源：http://dali.yj20258.top/Article/details/gt2ajmyowju.html

[S03] C：读入整数
来源：http://dali.pycfn.com/Article/details/gt2fxlyjohn.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2etwhzepx.html

[S04] C：字符串复制
来源：http://dali.mhx1999.top/Article/details/gt2vkqvpxxm.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yj202588.top/Article/details/gt2dwfldgha.html

[S05] C：字符串长度
来源：http://dali.zdqjudy.top/Article/details/gt2spbucqhb.html

strlen(s)
来源：http://dali.yvedp.cn/Article/details/gt2evunnnxz.html

[S06] C：字符串比较
来源：http://dali.fzhhl.top/Article/details/gt2gsuxjamu.html

strcmp(a, b) == 0
来源：http://dali.hnqzz.top/Article/details/gt2vxfblwdn.html

[S07] C：数组遍历求和
来源：http://dali.birdmap.top/Article/details/gt2rczmscbq.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cajdlzrk.html

[S08] C：动态内存分配与释放
来源：http://dali.bjfxy.top/Article/details/gt2luyzqsvl.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yueranfly.top/Article/details/gt2vdlddfou.html

[S09] C：结构体定义与初始化
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ukisbctk.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.daxiang520.top/Article/details/gt2ycaedyxl.html

[S10] C：指针与解引用
来源：http://dali.yanxiufei.cn/Article/details/gt2joyqsryx.html

int *p = &a;  *p = 5;
来源：http://dali.yj20258.top/Article/details/gt2wvgwlnfw.html

[S11] C：逐行读文件
来源：http://dali.nanxinkj.top/Article/details/gt2kholcfet.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hysaishi.cn/Article/details/gt2ktszxtpd.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.meibo888.top/Article/details/gt2rabontku.html

fclose(f);
来源：http://dali.havefunace.top/Article/details/gt2isrdzqnd.html

[S12] C：写文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xngeskwi.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.gzhubu.top/Article/details/gt2weaivaga.html

[S13] C：宏定义
来源：http://dali.sxryk.cn/Article/details/gt2gpufbjgw.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.gzhubu.top/Article/details/gt2hnusjryp.html

[S14] C：枚举
来源：http://dali.hfpthk.cn/Article/details/gt2nurxywlz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jiagoushi.top/Article/details/gt2uzhnfqmk.html

[S15] C：类型转换
来源：http://dali.tanke756.top/Article/details/gt2nbuyjhmd.html

(double) a / b
来源：http://dali.hongshengwenyu.top/Article/details/gt2lkdqlcjj.html

[S16] C：位操作置位
来源：http://dali.svipenyu.cn/Article/details/gt2aprswkge.html

x |= (1 << 3);
来源：http://dali.9152youxi.cn/Article/details/gt2cybylpnw.html

[S17] C：安全拼接字符串
来源：http://dali.xuetiantiany.cn/Article/details/gt2osqteznq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cqqwz.cn/Article/details/gt2rqmbxrwz.html

[S18] C：命令行参数
来源：http://dali.yj202588.top/Article/details/gt2pwwgcctw.html

int main(int argc, char **argv)
来源：http://dali.yj20258.top/Article/details/gt2ulmnnkkl.html

[S19] C：快速排序
来源：http://dali.birdmap.top/Article/details/gt2xtqccqnh.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gmqfwdfc.html

[S20] C：二分查找
来源：http://dali.hysaishi.cn/Article/details/gt2kbgzyefb.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zycfv.cn/Article/details/gt2hiznyhuv.html

[S21] C：字符类别判断
来源：http://dali.jinqigfzy.top/Article/details/gt2qyjrizjg.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.cucudq.cn/Article/details/gt2eppimqgh.html

[S22] C：字符串转数字
来源：http://dali.316326.xyz/Article/details/gt2mejjpkru.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.9152youxi.cn/Article/details/gt2ltyzgjfg.html

[S23] C：随机数
来源：http://dali.xinyue.icu/Article/details/gt2yoamtypy.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xtlihsdm.html

[S24] C：获取本地时间
来源：http://dali.ehwqpu.com/Article/details/gt2oogukabh.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.gzhubu.top/Article/details/gt2gmvjhrxl.html

[S25] C：内存拷贝
来源：http://dali.iojbl.cn/Article/details/gt2sbzhrtza.html

memcpy(dst, src, n);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bdjqthfx.html

[S26] C：内存清零
来源：http://dali.shzxlz.cn/Article/details/gt2qwcpeipj.html

memset(a, 0, sizeof a);
来源：http://dali.wangdashe.top/Article/details/gt2yxxaophe.html

[S27] C：定义常量
来源：http://dali.hywenlv.cn/Article/details/gt2wzqzlhqi.html

const double PI = 3.14159;
来源：http://dali.ppjwa.cn/Article/details/gt2wajmimpy.html

[S28] C：静态变量
来源：http://dali.fengsongda.top/Article/details/gt2jjutcslp.html

static int counter = 0;
来源：http://dali.gogol.net.cn/Article/details/gt2ennbdqzb.html

[S29] C：变参函数
来源：http://dali.iojbl.cn/Article/details/gt2yqcziwyy.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.xuetiantiany.cn/Article/details/gt2lytqvtdw.html

[S30] C：头文件保护
来源：http://dali.ybcxt.top/Article/details/gt2evlujqew.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2iibagrbo.html

#define X_H
来源：http://dali.yuanzhike.top/Article/details/gt2pjuavktu.html

#endif
来源：http://dali.redwolf501.top/Article/details/gt2meawucsy.html

[S31] C++：Hello World
来源：http://dali.shuidangran.top/Article/details/gt2didexlhv.html

#include <iostream>
来源：http://dali.hywenlv.cn/Article/details/gt2rgcjamvg.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.tanke756.top/Article/details/gt2cdiitevc.html

[S32] C++：字符串
来源：http://dali.xziqi.cn/Article/details/gt2wrmmydqo.html

std::string s = "hi";  s += "!";
来源：http://dali.aizwys.cn/Article/details/gt2mwpazesx.html


<!-- 参考信息 -->