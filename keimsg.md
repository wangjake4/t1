代发 wailian999

[Q61] 移动平均
来源：http://dali.gaohongyu789.top/Article/details/gt2ebooxvnh.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.bjfxy.top/Article/details/gt2cidcbcpe.html

[Q62] 分组占比
来源：http://dali.chenjidiqi.icu/Article/details/gt2lnfzhmii.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.smart0.xyz/Article/details/gt2tnreicxv.html

[Q63] 开启事务
来源：http://dali.guannengcc.top/Article/details/gt2pgizakqc.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.shanyushiyangtech.top/Article/details/gt2worqmnbg.html

[Q64] 提交事务
来源：http://dali.yvedp.cn/Article/details/gt2lpsxdhay.html

COMMIT;
来源：http://dali.sweek.top/Article/details/gt2dstokicy.html

[Q65] 回滚事务
来源：http://dali.yuxming.cn/Article/details/gt2tmrgrlwa.html

ROLLBACK;
来源：http://dali.shzxlz.cn/Article/details/gt2dnezegjf.html

[Q66] 行锁查询
来源：http://dali.vqdsnc.cn/Article/details/gt2fftdurew.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.tianlin.xyz/Article/details/gt2mlagucfk.html

[Q67] 设置隔离级别
来源：http://dali.yj20258.top/Article/details/gt2ilniwbvh.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.ehwqpu.com/Article/details/gt2pzptmxkl.html

[Q68] 保存点
来源：http://dali.nwbrower.top/Article/details/gt2beolocxo.html

SAVEPOINT sp1;
来源：http://dali.gotoacloud.top/Article/details/gt2brbhhzcw.html

ROLLBACK TO sp1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bufxqseg.html

[Q69] 查看执行计划
来源：http://dali.yanxiufei.cn/Article/details/gt2mjfepuea.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.guowangkeji.top/Article/details/gt2xrnrffnp.html

[Q70] 更新统计信息
来源：http://dali.cdnleiting.top/Article/details/gt2jzxvwxnh.html

ANALYZE TABLE users;
来源：http://dali.cqqwz.cn/Article/details/gt2oxkfmrti.html

[Q71] 查看建表语句
来源：http://dali.zycfv.cn/Article/details/gt2jnufzbtq.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.sxryk.cn/Article/details/gt2mezahprc.html

[Q72] 查看索引
来源：http://dali.shuidangran.top/Article/details/gt2nrxhanab.html

SHOW INDEX FROM users;
来源：http://dali.hnqzz.top/Article/details/gt2ikyfogko.html

[Q73] 查看表状态
来源：http://dali.yuanzhike.top/Article/details/gt2minzdzhx.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yongpay.top/Article/details/gt2krmgxqbn.html

[Q74] 强制使用索引
来源：http://dali.jyoumei.cn/Article/details/gt2wtlomiwo.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hammf.cn/Article/details/gt2jotqjkqm.html

[Q75] 日期格式化
来源：http://dali.yueranfly.top/Article/details/gt2ldsoudas.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.tianlin.xyz/Article/details/gt2ubzghezr.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.ivvv.top/Article/details/gt2zqqqshyu.html

[Q76] 按天统计
来源：http://dali.cheryme.top/Article/details/gt2ilyrtvdd.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.sweek.top/Article/details/gt2czzpocrw.html

[Q77] 时间加减
来源：http://dali.jianghu66.top/Article/details/gt2qbtzhehl.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.snrcjt.cn/Article/details/gt2dquugavk.html

[Q78] 当前时间
来源：http://dali.svipenyu.cn/Article/details/gt2zgfyjiws.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.wangdashe.top/Article/details/gt2iawxchhz.html

[Q79] 字符串拼接
来源：http://dali.xziqi.cn/Article/details/gt2cwgeivtm.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.sxryk.cn/Article/details/gt2kgqqpdfi.html

[Q80] 字符串截取
来源：http://dali.hywenlv.cn/Article/details/gt2kwixrwvt.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.sweek.top/Article/details/gt2rakpbnwx.html

[Q81] 字符串替换
来源：http://dali.sxryk.cn/Article/details/gt2pizqfhtd.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yueranfly.top/Article/details/gt2bgenhmmn.html

[Q82] 字符长度与字节长度
来源：http://dali.birdmap.top/Article/details/gt2ldksvmyb.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gt2qkaeghph.html

[Q83] 大小写转换
来源：http://dali.ppjwa.cn/Article/details/gt2esfjddpj.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.ehwqpu.com/Article/details/gt2ecgdnvnf.html

[Q84] 去除首尾空格
来源：http://dali.guannengcc.top/Article/details/gt2bmsfkxwt.html

SELECT TRIM(name) FROM users;
来源：http://dali.jianghu66.top/Article/details/gt2rcfonart.html

[Q85] 数值取整
来源：http://dali.hfpthk.cn/Article/details/gt2lxysragg.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.smart0.xyz/Article/details/gt2ijtskfsr.html

[Q86] 读取 JSON 字段
来源：http://dali.aizwys.cn/Article/details/gt2ilucvfgg.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zycfv.cn/Article/details/gt2dofhyhof.html

[Q87] JSON 字段做条件
来源：http://dali.shzxlz.cn/Article/details/gt2yzdcgqfl.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hywenlv.cn/Article/details/gt2uvqrhkoi.html

[Q88] 行转列（条件聚合）
来源：http://dali.jiagoushi.top/Article/details/gt2obqkebyl.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.nanxinkj.top/Article/details/gt2qclvwcst.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jianghu66.top/Article/details/gt2wxxzqpiy.html

[Q89] 判断表是否存在
来源：http://dali.9152youxi.cn/Article/details/gt2xdktixjs.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.cashguo.top/Article/details/gt2txhygoly.html

[Q90] 生成序号列
来源：http://dali.nanxuanxn.top/Article/details/gt2phugldpt.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.c1oappe.top/Article/details/gt2dlctkxdg.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2tnsmjisv.html

R. Bash 专题
来源：http://dali.dashuyun.cn/Article/details/gt2zurgensy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yjjtnbli.html

[R01] shebang 与严格模式
来源：http://dali.shangyingyoupin.top/Article/details/gt2ymmxjrmm.html

#!/usr/bin/env bash
来源：http://dali.xinyue.icu/Article/details/gt2zjlkoebz.html

set -euo pipefail
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xsarjaii.html

[R02] 变量赋值与使用
来源：http://dali.yonumen.top/Article/details/gt2bexzhxny.html

name="Tom"; echo "$name"
来源：http://dali.bjfxy.top/Article/details/gt2dxadisss.html

[R03] 只读变量
来源：http://dali.feifeiyinyue.top/Article/details/gt2iytxjuaf.html

readonly PI=3.14
来源：http://dali.gaohongyu789.top/Article/details/gt2tndhywpy.html

[R04] 位置参数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2axzvnzsm.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.tian-w.cn/Article/details/gt2jcxsnfrv.html

[R05] 参数默认值
来源：http://dali.gogol.net.cn/Article/details/gt2kxrzwwxc.html

name="${1:-default}"
来源：http://dali.hfpthk.cn/Article/details/gt2ompskwba.html

[R06] 判断命令是否存在
来源：http://dali.hnxiangtu.top/Article/details/gt2cvgjcaxg.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2adubnmzv.html

[R07] if 判断文件
来源：http://dali.hysaishi.cn/Article/details/gt2htvggqjm.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.guannengcc.top/Article/details/gt2pgvgnkgl.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hajzmagv.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.ydzc1.top/Article/details/gt2ygytsekj.html

[R09] 字符串比较
来源：http://dali.yongpay.top/Article/details/gt2tjzwanez.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.cucudq.cn/Article/details/gt2koyivswd.html

[R10] 正则匹配
来源：http://dali.jqgfzy.top/Article/details/gt2wzftpqjr.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.havefunace.top/Article/details/gt2jebranbh.html

[R11] case 多分支
来源：http://dali.gzhubu.top/Article/details/gt2tqqflago.html

case "$1" in
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bikkuugp.html

start) echo "启动" ;;
来源：http://dali.pengpengdd.cyou/Article/details/gt2mfbmhcew.html

stop)  echo "停止" ;;
来源：http://dali.ivvv.top/Article/details/gt2uxtlywjx.html

*)     echo "未知命令" ;;
来源：http://dali.hammf.cn/Article/details/gt2fanqkvfv.html

esac
来源：http://dali.xylfe.cn/Article/details/gt2envkstnb.html

[R12] for 遍历文件
来源：http://dali.cheryme.top/Article/details/gt2grshftos.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jlsjyb.cn/Article/details/gt2bitisaui.html

[R13] for 计数循环
来源：http://dali.wangshuangyany.cn/Article/details/gt2ydatipfd.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yvedp.cn/Article/details/gt2kbhiavle.html

[R14] C 风格 for
来源：http://dali.nanxinkj.top/Article/details/gt2xzyebyee.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.cucudq.cn/Article/details/gt2ihfancwd.html

[R15] while 逐行读文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2oeelzbxx.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.xylfe.cn/Article/details/gt2yeddhznz.html

[R16] until 等待条件
来源：http://dali.chenzaomai.com/Article/details/gt2oggcyhys.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zycfv.cn/Article/details/gt2rrtntknr.html

[R17] 数组定义与取值
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2syuromwy.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.cdnleiting.top/Article/details/gt2kfcxehey.html

[R18] 遍历数组
来源：http://dali.aibaodan.cn/Article/details/gt2ivqwtbkc.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.9152youxi.cn/Article/details/gt2fikrlggk.html

[R19] 数组长度
来源：http://dali.xuetiantiany.cn/Article/details/gt2rtgtjqqy.html

echo "${#arr[@]}"
来源：http://dali.zhiwuduotai.top/Article/details/gt2mhxhnabn.html

[R20] 关联数组（字典）
来源：http://dali.hywenlv.cn/Article/details/gt2gholydxs.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zycfv.cn/Article/details/gt2sonucepq.html

[R21] 字符串长度
来源：http://dali.tanke756.top/Article/details/gt2djjzjvua.html

echo "${#s}"
来源：http://dali.ppjwa.cn/Article/details/gt2zuunfsuy.html

[R22] 截取子串
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jdmfztbd.html

echo "${s:0:5}"
来源：http://dali.haohaochexian.top/Article/details/gt2czjegwts.html

[R23] 字符串替换
来源：http://dali.birdmap.top/Article/details/gt2xpdwgwbo.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.ydzc1.top/Article/details/gt2xatuifxs.html

[R24] 大小写转换
来源：http://dali.gogol.net.cn/Article/details/gt2sxdtrtuc.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zycfv.cn/Article/details/gt2vezplbyl.html

[R25] 去后缀 / 去前缀
来源：http://dali.bjfxy.top/Article/details/gt2wbmtufqt.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zycfv.cn/Article/details/gt2ulstqdgm.html

[R26] 命令替换
来源：http://dali.fzhhl.top/Article/details/gt2arrakybj.html

now=$(date +%F); echo "$now"
来源：http://dali.feifeiyinyue.top/Article/details/gt2putwyvkm.html

[R27] 算术展开
来源：http://dali.mhx1999.top/Article/details/gt2bhxmytbr.html

echo $((1 + 2 * 3))
来源：http://dali.ybcxt.top/Article/details/gt2zallxwjr.html

[R28] 浮点运算
来源：http://dali.jiagoushi.top/Article/details/gt2cspbuxgg.html

echo "scale=2; 10/3" | bc
来源：http://dali.daxiang520.top/Article/details/gt2xujcqgwz.html

[R29] 定义函数
来源：http://dali.shangyingyoupin.top/Article/details/gt2mlpeougc.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.kuanghao11.cn/Article/details/gt2sfoqxmfv.html

[R30] 函数返回状态码
来源：http://dali.havefunace.top/Article/details/gt2bvivxkbr.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yuanzhike.top/Article/details/gt2ebslkbur.html

[R31] 局部变量
来源：http://dali.birdmap.top/Article/details/gt2bhgrhnwa.html

f() { local x=1; echo "$x"; }
来源：http://dali.pycfn.com/Article/details/gt2gbxvblax.html

[R32] 参数个数校验
来源：http://dali.zhongyouzk.top/Article/details/gt2jcudisaj.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.sxryk.cn/Article/details/gt2kingqtor.html

[R33] 捕获错误并提示行号
来源：http://dali.iojbl.cn/Article/details/gt2gpbyzqrk.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.tianlin.xyz/Article/details/gt2wgskwifs.html

[R34] 退出时清理
来源：http://dali.zycfv.cn/Article/details/gt2bhgdbxlg.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2grqsqbeo.html

[R35] 后台执行并等待
来源：http://dali.snrcjt.cn/Article/details/gt2hnjouovt.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hywenlv.cn/Article/details/gt2scdyrvcp.html

[R36] 并发执行多个任务
来源：http://dali.vqdsnc.cn/Article/details/gt2vlivravu.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.tanke756.top/Article/details/gt2otdhcrao.html

[R37] 把输出赋给变量
来源：http://dali.fzhhl.top/Article/details/gt2ecajcsei.html

files=$(ls -1)
来源：http://dali.sweek.top/Article/details/gt2lbgefofb.html

[R38] 管道串联
来源：http://dali.tian-w.cn/Article/details/gt2dzbkiotx.html

cat a.txt | grep -i error | wc -l
来源：http://dali.xziqi.cn/Article/details/gt2zhbsnvqg.html

[R39] 重定向标准输出与错误
来源：http://dali.shuidangran.top/Article/details/gt2mvujvatx.html

cmd > out.log 2>&1
来源：http://dali.pycfn.com/Article/details/gt2rfwarrpy.html

[R40] 追加写日志
来源：http://dali.jyoumei.cn/Article/details/gt2hfpvsdpx.html

echo "log" >> out.log
来源：http://dali.9152youxi.cn/Article/details/gt2uiwidlzz.html

[R41] 丢弃输出
来源：http://dali.yangfankeji.com/Article/details/gt2clxtstgc.html

cmd >/dev/null 2>&1
来源：http://dali.nwbrower.top/Article/details/gt2cpnfbpjj.html

[R42] 输入重定向
来源：http://dali.yuanzhike.top/Article/details/gt2wusgmyzy.html

wc -l < a.txt
来源：http://dali.yvedp.cn/Article/details/gt2ovudddbm.html

[R43] 按名字查找文件
来源：http://dali.sxryk.cn/Article/details/gt2pxicuidg.html

find . -name "*.log" -type f
来源：http://dali.cdnleiting.top/Article/details/gt2qlcwmqdi.html

[R44] 按修改时间查找
来源：http://dali.chenzaomai.com/Article/details/gt2rwgpuzzw.html

find . -mtime -7 -type f
来源：http://dali.hywenlv.cn/Article/details/gt2dsczolxu.html

[R45] 批量删除
来源：http://dali.yj20258888.top/Article/details/gt2wuhhkfbt.html

find . -name "*.tmp" -delete
来源：http://dali.zhoulong.xyz/Article/details/gt2bbxzdhcd.html

[R46] 递归替换文件内容
来源：http://dali.dianchejie.cn/Article/details/gt2nwqbbwgq.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhengqikj.top/Article/details/gt2mhgzxvja.html

[R47] sed 单行替换
来源：http://dali.zhoulong.xyz/Article/details/gt2awqhjfuy.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.sweek.top/Article/details/gt2wbtonzxl.html

[R48] awk 取指定列
来源：http://dali.sweek.top/Article/details/gt2pmpwjayv.html

awk '{print $1, $3}' a.txt
来源：http://dali.wangdashe.top/Article/details/gt2kvaazviz.html

[R49] awk 带条件
来源：http://dali.xuanzx.com/Article/details/gt2tdaemvyc.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.cashguo.top/Article/details/gt2jtdtmrzk.html

[R50] awk 求和
来源：http://dali.cqqwz.cn/Article/details/gt2qcgdoyuk.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.andypj.xyz/Article/details/gt2ecxhkxut.html

[R51] 排序去重取前几
来源：http://dali.316326.xyz/Article/details/gt2odcoqbxq.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.nanxinkj.top/Article/details/gt2zvgmrbao.html

[R52] 统计行数
来源：http://dali.yangfankeji.com/Article/details/gt2aivudmht.html

wc -l a.txt
来源：http://dali.9152youxi.cn/Article/details/gt2vqxzobva.html

[R53] 查看文件头与实时尾
来源：http://dali.chenlongwang.top/Article/details/gt2rnrxtwgu.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.ybcxt.top/Article/details/gt2rkymookv.html

[R54] 比较两个文件
来源：http://dali.yj20258888.top/Article/details/gt2eosmynmv.html

diff a.txt b.txt
来源：http://dali.wangshuangyany.cn/Article/details/gt2oajmqvhi.html

[R55] 压缩与解压
来源：http://dali.guowangkeji.top/Article/details/gt2meefyxce.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.nanxuanxn.top/Article/details/gt2xoujqsbn.html

[R56] 远程拷贝
来源：http://dali.cdnleiting.top/Article/details/gt2xqchooav.html

scp file user@host:/path/
来源：http://dali.9152youxi.cn/Article/details/gt2tehtvxal.html

[R57] 远程执行命令
来源：http://dali.iojbl.cn/Article/details/gt2gdglgvvi.html

ssh user@host 'uptime'
来源：http://dali.redwolf501.top/Article/details/gt2ekyoqqao.html

[R58] 下载文件
来源：http://dali.316326.xyz/Article/details/gt2rtfaxttd.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.nanxinkj.top/Article/details/gt2dkjojogl.html

[R59] 发 POST JSON
来源：http://dali.nanxinkj.top/Article/details/gt2cprnsgca.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.c1oappe.top/Article/details/gt2kozcpeng.html

[R60] 只看 HTTP 状态码
来源：http://dali.xziqi.cn/Article/details/gt2ueczmpdr.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.fzhhl.top/Article/details/gt2mvzhupyu.html

[R61] 磁盘占用
来源：http://dali.yonumen.top/Article/details/gt2fqkhqmcc.html

df -h;  du -sh *
来源：http://dali.yonumen.top/Article/details/gt2ombyhjdq.html

[R62] 找最占空间的文件
来源：http://dali.sysykeji.top/Article/details/gt2qpetwyaj.html

du -ah . | sort -rh | head -10
来源：http://dali.redwolf501.top/Article/details/gt2yavxfxcn.html

[R63] 内存与进程
来源：http://dali.jqgufenzy.top/Article/details/gt2somkfpcc.html

free -h;  ps aux | grep nginx
来源：http://dali.ivvv.top/Article/details/gt2aplnglzo.html

[R64] 结束进程
来源：http://dali.nanxuanxn.top/Article/details/gt2ihhzatmd.html

kill -9 $(pgrep -f app.py)
来源：http://dali.daxiang520.top/Article/details/gt2avlxxihb.html

[R65] 查看端口占用
来源：http://dali.quarkkingdee.top/Article/details/gt2yuyepbuh.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.cashguo.top/Article/details/gt2pocufldm.html

[R66] 定时任务
来源：http://dali.gogol.net.cn/Article/details/gt2edamqawc.html

crontab -e;  crontab -l
来源：http://dali.aizwys.cn/Article/details/gt2qbyihnit.html

[R67] 生成随机十六进制串
来源：http://dali.svipenyu.cn/Article/details/gt2utziyxrc.html

openssl rand -hex 16
来源：http://dali.meibo888.top/Article/details/gt2rajqwflj.html

[R68] 计算文件校验值
来源：http://dali.nwbrower.top/Article/details/gt2wtumkiop.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.vqdsnc.cn/Article/details/gt2qlqfnnag.html

[R69] 生成随机密码
来源：http://dali.zhixingplan.top/Article/details/gt2jazbbcnt.html

head -c 16 /dev/urandom | base64
来源：http://dali.zdqjudy.top/Article/details/gt2uynvuawi.html

[R70] 时间戳与互转
来源：http://dali.redwolf501.top/Article/details/gt2pdvzkrtv.html

date +%s;  date -d @1700000000
来源：http://dali.andypj.xyz/Article/details/gt2oyrlmslm.html

[R71] 日期格式化
来源：http://dali.xuanzx.com/Article/details/gt2rdwilsmb.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.snrcjt.cn/Article/details/gt2wvucdoff.html

[R72] 等待端口就绪
来源：http://dali.jyoumei.cn/Article/details/gt2mqowjqix.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.andypj.xyz/Article/details/gt2owrpjirw.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2jdlivtzb.html

split -l 1000 big.log part_
来源：http://dali.zdqjudy.top/Article/details/gt2hrbwxttk.html

[R74] 批量重命名
来源：http://dali.xylfe.cn/Article/details/gt2tbmlcyix.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jinqigufen.top/Article/details/gt2mmfdfxyq.html

[R75] 导出环境变量
来源：http://dali.meibo888.top/Article/details/gt2mbbkdtdm.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.fzhhl.top/Article/details/gt2kmimwflm.html

[R76] 使用临时文件
来源：http://dali.chenlongwang.top/Article/details/gt2ahcsmlxl.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.0kj1m.cn/Article/details/gt2xgrukuop.html

[R77] 读取用户输入
来源：http://dali.hnxiangtu.top/Article/details/gt2dmjekogk.html

read -rp "请输入: " ans
来源：http://dali.yongpay.top/Article/details/gt2tynvibus.html

[R78] 交互式菜单
来源：http://dali.hfpthk.cn/Article/details/gt2bdpdklmp.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.nwbrower.top/Article/details/gt2mlncvhbq.html

[R79] 解析命令行选项
来源：http://dali.yonumen.top/Article/details/gt2jauwpefn.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.feifeiyinyue.top/Article/details/gt2chumusam.html

[R80] 查看脚本执行耗时
来源：http://dali.sufxvd.cn/Article/details/gt2jayodlhg.html

time ./run.sh
来源：http://dali.dianchejie.cn/Article/details/gt2hsxqpnrk.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2pibztvdk.html

S. C / C++ 专题
来源：http://dali.smart0.xyz/Article/details/gt2saskfgkh.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2ykleazvc.html

[S01] C：Hello World
来源：http://dali.yuanzhike.top/Article/details/gt2aowojcfo.html

#include <stdio.h>
来源：http://dali.jinqigufen.top/Article/details/gt2ovkpinqv.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.gotoacloud.top/Article/details/gt2ykhaumgv.html

[S02] C：变量与格式化输出
来源：http://dali.chenlongwang.top/Article/details/gt2bdfejjgo.html

int a = 10; printf("%d\n", a);
来源：http://dali.xuetiantiany.cn/Article/details/gt2iljmgiis.html

[S03] C：读入整数
来源：http://dali.smart0.xyz/Article/details/gt2mufwavfw.html

int x; scanf("%d", &x);
来源：http://dali.fzhhl.top/Article/details/gt2cbsrsmoc.html

[S04] C：字符串复制
来源：http://dali.snrcjt.cn/Article/details/gt2jxsgnnyy.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mlfwtisy.html

[S05] C：字符串长度
来源：http://dali.aizwys.cn/Article/details/gt2yeitjrul.html

strlen(s)
来源：http://dali.jianghu66.top/Article/details/gt2gljvtcyt.html

[S06] C：字符串比较
来源：http://dali.hnxiangtu.top/Article/details/gt2lsbpkdpa.html

strcmp(a, b) == 0
来源：http://dali.aizwys.cn/Article/details/gt2rpmjprow.html

[S07] C：数组遍历求和
来源：http://dali.svipenyu.cn/Article/details/gt2mcbuebuk.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yuanzhike.top/Article/details/gt2rxagcczb.html

[S08] C：动态内存分配与释放
来源：http://dali.zhoulong.xyz/Article/details/gt2ucgjcyfo.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zycfv.cn/Article/details/gt2fdzhfweg.html

[S09] C：结构体定义与初始化
来源：http://dali.yuanzhike.top/Article/details/gt2azxysewp.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.gaohongyu789.top/Article/details/gt2smyckdzf.html

[S10] C：指针与解引用
来源：http://dali.yanxiufei.cn/Article/details/gt2gxjiwmyq.html

int *p = &a;  *p = 5;
来源：http://dali.shzxlz.cn/Article/details/gt2orqabsce.html

[S11] C：逐行读文件
来源：http://dali.wangdashe.top/Article/details/gt2wkfdnqgw.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.aizwys.cn/Article/details/gt2dlezhxyo.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2quudkzji.html

fclose(f);
来源：http://dali.ydzc1.top/Article/details/gt2rrrtpydh.html

[S12] C：写文件
来源：http://dali.aibaodan.cn/Article/details/gt2nhplmkgk.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.xinyue.icu/Article/details/gt2pabktvcq.html

[S13] C：宏定义
来源：http://dali.hnxiangtu.top/Article/details/gt2uzytyyrs.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhengqikj.top/Article/details/gt2jlhuxehz.html

[S14] C：枚举
来源：http://dali.yonumen.top/Article/details/gt2uatpmerc.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.cucudq.cn/Article/details/gt2ocgdnppz.html

[S15] C：类型转换
来源：http://dali.bjfxy.top/Article/details/gt2zhnyqqwa.html

(double) a / b
来源：http://dali.pycfn.com/Article/details/gt2nsxtykkk.html

[S16] C：位操作置位
来源：http://dali.yongpay.top/Article/details/gt2aaaanwxd.html

x |= (1 << 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jzvasolc.html

[S17] C：安全拼接字符串
来源：http://dali.c1oappe.top/Article/details/gt2gjjstkuz.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.redwolf501.top/Article/details/gt2otykdnjv.html

[S18] C：命令行参数
来源：http://dali.sufxvd.cn/Article/details/gt2mzrtazka.html

int main(int argc, char **argv)
来源：http://dali.jinqigfzy.top/Article/details/gt2mxzktujj.html

[S19] C：快速排序
来源：http://dali.hammf.cn/Article/details/gt2qodsacid.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.smart0.xyz/Article/details/gt2oniondzl.html

[S20] C：二分查找
来源：http://dali.tianlin.xyz/Article/details/gt2rqqhusfr.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.meibo888.top/Article/details/gt2jrcdlwra.html

[S21] C：字符类别判断
来源：http://dali.yvedp.cn/Article/details/gt2sbbxusfg.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jianghu66.top/Article/details/gt2mkvgyuqj.html

[S22] C：字符串转数字
来源：http://dali.hammf.cn/Article/details/gt2raiqzahw.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.mhx1999.top/Article/details/gt2cbwupwof.html

[S23] C：随机数
来源：http://dali.bjfxy.top/Article/details/gt2zbizdrnn.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhengqikj.top/Article/details/gt2wftgrpov.html

[S24] C：获取本地时间
来源：http://dali.hysaishi.cn/Article/details/gt2tgegezbi.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.cucudq.cn/Article/details/gt2exqhwruh.html

[S25] C：内存拷贝
来源：http://dali.guowangkeji.top/Article/details/gt2metotpvm.html

memcpy(dst, src, n);
来源：http://dali.hongshengwenyu.top/Article/details/gt2evthgbom.html

[S26] C：内存清零
来源：http://dali.sufxvd.cn/Article/details/gt2ffbjuevl.html

memset(a, 0, sizeof a);
来源：http://dali.tanke756.top/Article/details/gt2egffhruo.html

[S27] C：定义常量
来源：http://dali.aibaodan.cn/Article/details/gt2kgjrwwgp.html

const double PI = 3.14159;
来源：http://dali.jiagoushi.top/Article/details/gt2rqlvpbxg.html

[S28] C：静态变量
来源：http://dali.andypj.xyz/Article/details/gt2icaagfln.html

static int counter = 0;
来源：http://dali.yueranfly.top/Article/details/gt2ksoutcuk.html

[S29] C：变参函数
来源：http://dali.shangyingyoupin.top/Article/details/gt2ufplwrvo.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.sysykeji.top/Article/details/gt2ebpritpz.html

[S30] C：头文件保护
来源：http://dali.gaohongyu789.top/Article/details/gt2vlsmzysa.html

#ifndef X_H
来源：http://dali.chenzaomai.com/Article/details/gt2fcsaylno.html

#define X_H
来源：http://dali.kuanghao11.cn/Article/details/gt2okxyelck.html

#endif
来源：http://dali.dashuyun.cn/Article/details/gt2fwkwspbr.html

[S31] C++：Hello World
来源：http://dali.iojbl.cn/Article/details/gt2lgcfnpvb.html


<!-- 参考信息 -->