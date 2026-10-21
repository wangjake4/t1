代发 wailian999

ROLLBACK TO sp1;
来源：http://dali.yj20258888.top/Article/details/gtetlkhvca.html

[Q69] 查看执行计划
来源：http://dali.tianlin.xyz/Article/details/gtgrpgcudi.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gtqghebptg.html

[Q70] 更新统计信息
来源：http://dali.yj20258888.top/Article/details/gtoxbdzwku.html

ANALYZE TABLE users;
来源：http://dali.yj20258.top/Article/details/gtivfkfttc.html

[Q71] 查看建表语句
来源：http://dali.kuanghao11.cn/Article/details/gtwczzqkpz.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gtcdugcdob.html

[Q72] 查看索引
来源：http://dali.zycfv.cn/Article/details/gtdzggbjof.html

SHOW INDEX FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtkgzfhmpz.html

[Q73] 查看表状态
来源：http://dali.wangdashe.top/Article/details/gtutujhgxp.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yuanzhike.top/Article/details/gtnobzkbmu.html

[Q74] 强制使用索引
来源：http://dali.guannengcc.top/Article/details/gtyeyrocsm.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.wangdashe.top/Article/details/gtocnjrlfo.html

[Q75] 日期格式化
来源：http://dali.sxryk.cn/Article/details/gtizdjezxv.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gtlkssvibi.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.iojbl.cn/Article/details/gtlxdmtwtk.html

[Q76] 按天统计
来源：http://dali.shanyushiyangtech.top/Article/details/gtsnpabqzg.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.iojbl.cn/Article/details/gtlsrowdgd.html

[Q77] 时间加减
来源：http://dali.yj202588.top/Article/details/gtuvdgfqye.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.shanyushiyangtech.top/Article/details/gtiigugyrt.html

[Q78] 当前时间
来源：http://dali.hysaishi.cn/Article/details/gtpozvudtx.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hfpthk.cn/Article/details/gteonmrlxz.html

[Q79] 字符串拼接
来源：http://dali.smart0.xyz/Article/details/gtohofdfjs.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jqgufenzy.top/Article/details/gtkhyjuufv.html

[Q80] 字符串截取
来源：http://dali.yuanzhike.top/Article/details/gtjpsnfyii.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.iojbl.cn/Article/details/gtidbjyfza.html

[Q81] 字符串替换
来源：http://dali.yvedp.cn/Article/details/gtiduyffav.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtpuinytjb.html

[Q82] 字符长度与字节长度
来源：http://dali.wangshuangyany.cn/Article/details/gtzxevijqe.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gttbscdizi.html

[Q83] 大小写转换
来源：http://dali.xinyue.icu/Article/details/gtanpijjod.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gthokkyidl.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gtkslmuhck.html

SELECT TRIM(name) FROM users;
来源：http://dali.yueranfly.top/Article/details/gtfrtotjtw.html

[Q85] 数值取整
来源：http://dali.zdqjudy.top/Article/details/gtxbwzukef.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.xuetiantiany.cn/Article/details/gtniggrqql.html

[Q86] 读取 JSON 字段
来源：http://dali.vqdsnc.cn/Article/details/gtskuztqle.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.redwolf501.top/Article/details/gtyvgslcno.html

[Q87] JSON 字段做条件
来源：http://dali.yanxiufei.cn/Article/details/gteazasmui.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jinghuilouyu.cn/Article/details/gtfhpieizp.html

[Q88] 行转列（条件聚合）
来源：http://dali.birdmap.top/Article/details/gtjhpxodjz.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.vqdsnc.cn/Article/details/gtmuxtasuv.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.sxryk.cn/Article/details/gtzcvgowlk.html

[Q89] 判断表是否存在
来源：http://dali.sxryk.cn/Article/details/gtvwzqqfij.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yongpay.top/Article/details/gtowhaxipi.html

[Q90] 生成序号列
来源：http://dali.daxiang520.top/Article/details/gtvaprfmvy.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yj20258.top/Article/details/gtvggzrspw.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtiaxdjcgz.html

R. Bash 专题
来源：http://dali.zhixingplan.top/Article/details/gtatblxvfr.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtwzthmddw.html

[R01] shebang 与严格模式
来源：http://dali.chenzaomai.com/Article/details/gtxobkxuio.html

#!/usr/bin/env bash
来源：http://dali.hnqzz.top/Article/details/gtdfgttprv.html

set -euo pipefail
来源：http://dali.shangyingyoupin.top/Article/details/gturdzzylo.html

[R02] 变量赋值与使用
来源：http://dali.dashuyun.cn/Article/details/gtdcccvpwz.html

name="Tom"; echo "$name"
来源：http://dali.zhongyouzk.top/Article/details/gtbtvwshgc.html

[R03] 只读变量
来源：http://dali.xziqi.cn/Article/details/gtjacjjjjs.html

readonly PI=3.14
来源：http://dali.shuidangran.top/Article/details/gtgtbfyssv.html

[R04] 位置参数
来源：http://dali.yj20258888.top/Article/details/gtsxsyqqmj.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hysaishi.cn/Article/details/gtalszkwbi.html

[R05] 参数默认值
来源：http://dali.quarkkingdee.top/Article/details/gtkmgtsgnq.html

name="${1:-default}"
来源：http://dali.chenzaomai.com/Article/details/gturjqetxt.html

[R06] 判断命令是否存在
来源：http://dali.zycfv.cn/Article/details/gtwyyjyiui.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.sxryk.cn/Article/details/gtgtpuftdg.html

[R07] if 判断文件
来源：http://dali.iojbl.cn/Article/details/gtbwijiwtb.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.daria6918.cn/Article/details/gtvibupvoc.html

[R08] 数值比较
来源：http://dali.shanyushiyangtech.top/Article/details/gtbdwjmurk.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jyoumei.cn/Article/details/gtcnltvmko.html

[R09] 字符串比较
来源：http://dali.tian-w.cn/Article/details/gtsxmczqms.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdtbbyygb.html

[R10] 正则匹配
来源：http://dali.c1oappe.top/Article/details/gthhvaoprt.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jinghuilouyu.cn/Article/details/gtimbkgpim.html

[R11] case 多分支
来源：http://dali.yj202588.top/Article/details/gtvricygfp.html

case "$1" in
来源：http://dali.cqqwz.cn/Article/details/gthsxoygxg.html

start) echo "启动" ;;
来源：http://dali.zhixingplan.top/Article/details/gtarmtrdfo.html

stop)  echo "停止" ;;
来源：http://dali.316326.xyz/Article/details/gtyeytnksh.html

*)     echo "未知命令" ;;
来源：http://dali.jqgufenzy.top/Article/details/gtkglpszhe.html

esac
来源：http://dali.havefunace.top/Article/details/gtvtbbqufm.html

[R12] for 遍历文件
来源：http://dali.dashuyun.cn/Article/details/gtmhjsbbqm.html

for f in *.txt; do echo "$f"; done
来源：http://dali.cheryme.top/Article/details/gtwopnucug.html

[R13] for 计数循环
来源：http://dali.yueranfly.top/Article/details/gtdfnhfuhi.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.tianlin.xyz/Article/details/gtbyzplkxk.html

[R14] C 风格 for
来源：http://dali.guannengcc.top/Article/details/gtieuqyedl.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hnxiangtu.top/Article/details/gtamctggze.html

[R15] while 逐行读文件
来源：http://dali.yangfankeji.com/Article/details/gtwjisvxyp.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yanxiufei.cn/Article/details/gtsqztyfdj.html

[R16] until 等待条件
来源：http://dali.jinghuilouyu.cn/Article/details/gttkrmsbig.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jyoumei.cn/Article/details/gtsitokbue.html

[R17] 数组定义与取值
来源：http://dali.nwbrower.top/Article/details/gtxeoqwotj.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.aibaodan.cn/Article/details/gtgnxdmetl.html

[R18] 遍历数组
来源：http://dali.aibaodan.cn/Article/details/gtkankjxpf.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.cqqwz.cn/Article/details/gtzuqpnxkj.html

[R19] 数组长度
来源：http://dali.cucudq.cn/Article/details/gtcdgvqzhc.html

echo "${#arr[@]}"
来源：http://dali.zhiwuduotai.top/Article/details/gtrtzefneo.html

[R20] 关联数组（字典）
来源：http://dali.aibaodan.cn/Article/details/gthojcqlts.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yuanzhike.top/Article/details/gtkttsklpd.html

[R21] 字符串长度
来源：http://dali.guannengcc.top/Article/details/gtoidswwbg.html

echo "${#s}"
来源：http://dali.snrcjt.cn/Article/details/gtirqykgif.html

[R22] 截取子串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtznchhwaa.html

echo "${s:0:5}"
来源：http://dali.hongshengwenyu.top/Article/details/gtpxedpnuf.html

[R23] 字符串替换
来源：http://dali.smart0.xyz/Article/details/gtvfeacmhw.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.wangdashe.top/Article/details/gtplzeedmt.html

[R24] 大小写转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdxkyytmk.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.vqdsnc.cn/Article/details/gtwjutwujt.html

[R25] 去后缀 / 去前缀
来源：http://dali.jinqigfzy.top/Article/details/gtxlqonjrq.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.ehwqpu.com/Article/details/gtbofkztdb.html

[R26] 命令替换
来源：http://dali.hfpthk.cn/Article/details/gtnzifnqjp.html

now=$(date +%F); echo "$now"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuizpypiy.html

[R27] 算术展开
来源：http://dali.jinghuilouyu.cn/Article/details/gtelqzopqt.html

echo $((1 + 2 * 3))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyujsuxuq.html

[R28] 浮点运算
来源：http://dali.yj202588.top/Article/details/gtcjbdvdmh.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhengqikj.top/Article/details/gtjuauwrzi.html

[R29] 定义函数
来源：http://dali.jlsjyb.cn/Article/details/gtfxldcmpr.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.chenjidiqi.icu/Article/details/gthffvqjtk.html

[R30] 函数返回状态码
来源：http://dali.smart0.xyz/Article/details/gtypnnrvau.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.birdmap.top/Article/details/gtbhmmeczi.html

[R31] 局部变量
来源：http://dali.kuanghao11.cn/Article/details/gtkgtrccqq.html

f() { local x=1; echo "$x"; }
来源：http://dali.vqdsnc.cn/Article/details/gtkgixbrzs.html

[R32] 参数个数校验
来源：http://dali.hysaishi.cn/Article/details/gtcshxxbdx.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.aizwys.cn/Article/details/gtyrqpqwwn.html

[R33] 捕获错误并提示行号
来源：http://dali.kuanghao11.cn/Article/details/gtjmiwzjih.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.sysykeji.top/Article/details/gthsbwdbxj.html

[R34] 退出时清理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfelkzyrz.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yueranfly.top/Article/details/gtiruovihk.html

[R35] 后台执行并等待
来源：http://dali.redwolf501.top/Article/details/gtnxyavluc.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.316326.xyz/Article/details/gtwbelscat.html

[R36] 并发执行多个任务
来源：http://dali.jiagoushi.top/Article/details/gteeyqnkbe.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.nwbrower.top/Article/details/gtgkisxuaf.html

[R37] 把输出赋给变量
来源：http://dali.yanxiufei.cn/Article/details/gtfzsponpn.html

files=$(ls -1)
来源：http://dali.yuxming.cn/Article/details/gtmcyesvkw.html

[R38] 管道串联
来源：http://dali.cheryme.top/Article/details/gtyacjfbrj.html

cat a.txt | grep -i error | wc -l
来源：http://dali.feifeiyinyue.top/Article/details/gthypyrwcj.html

[R39] 重定向标准输出与错误
来源：http://dali.hnqzz.top/Article/details/gtxnxveise.html

cmd > out.log 2>&1
来源：http://dali.haohaochexian.top/Article/details/gtonmmgbxh.html

[R40] 追加写日志
来源：http://dali.sweek.top/Article/details/gtyxvinred.html

echo "log" >> out.log
来源：http://dali.nwbrower.top/Article/details/gtlhlemzrn.html

[R41] 丢弃输出
来源：http://dali.shzxlz.cn/Article/details/gtflrtrekn.html

cmd >/dev/null 2>&1
来源：http://dali.zhongyouzk.top/Article/details/gtnghefiix.html

[R42] 输入重定向
来源：http://dali.ivvv.top/Article/details/gtbnlrwztf.html

wc -l < a.txt
来源：http://dali.iojbl.cn/Article/details/gtkhqazovi.html

[R43] 按名字查找文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtakzuisao.html

find . -name "*.log" -type f
来源：http://dali.yvedp.cn/Article/details/gtmutljjri.html

[R44] 按修改时间查找
来源：http://dali.haohaochexian.top/Article/details/gtpbinniei.html

find . -mtime -7 -type f
来源：http://dali.haohaochexian.top/Article/details/gtvwhhyuvw.html

[R45] 批量删除
来源：http://dali.ivvv.top/Article/details/gtmglqpagl.html

find . -name "*.tmp" -delete
来源：http://dali.gogol.net.cn/Article/details/gtmuxypcnx.html

[R46] 递归替换文件内容
来源：http://dali.zdqjudy.top/Article/details/gtmcnhydym.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.c1oappe.top/Article/details/gtjqescviq.html

[R47] sed 单行替换
来源：http://dali.yj202588.top/Article/details/gtzvcvqlqg.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.ppjwa.cn/Article/details/gtcodmuxnv.html

[R48] awk 取指定列
来源：http://dali.andypj.xyz/Article/details/gtbpwemlgz.html

awk '{print $1, $3}' a.txt
来源：http://dali.nanxuanxn.top/Article/details/gtxqtbnklv.html

[R49] awk 带条件
来源：http://dali.xylfe.cn/Article/details/gtfomubojm.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfxftltxc.html

[R50] awk 求和
来源：http://dali.jinqigfzy.top/Article/details/gtpmsshxyy.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gtyumzrwgr.html

[R51] 排序去重取前几
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmqcordaw.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.gogol.net.cn/Article/details/gtguxtryvx.html

[R52] 统计行数
来源：http://dali.yongpay.top/Article/details/gtwxkynxxc.html

wc -l a.txt
来源：http://dali.sysykeji.top/Article/details/gtbdmmqtec.html

[R53] 查看文件头与实时尾
来源：http://dali.gotoacloud.top/Article/details/gtgaykouvp.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.haohaochexian.top/Article/details/gtdgjiagbc.html

[R54] 比较两个文件
来源：http://dali.c1oappe.top/Article/details/gtaqdmutpe.html

diff a.txt b.txt
来源：http://dali.dianchejie.cn/Article/details/gtkhtlnqsh.html

[R55] 压缩与解压
来源：http://dali.yueranfly.top/Article/details/gtvdrxuvkz.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.c1oappe.top/Article/details/gtkbymcjwx.html

[R56] 远程拷贝
来源：http://dali.jinqigufen.top/Article/details/gtomkmqplo.html

scp file user@host:/path/
来源：http://dali.shuidangran.top/Article/details/gtybcsbyrf.html

[R57] 远程执行命令
来源：http://dali.gotoacloud.top/Article/details/gtxhoxkarm.html

ssh user@host 'uptime'
来源：http://dali.jyoumei.cn/Article/details/gtgpreivvx.html

[R58] 下载文件
来源：http://dali.xinyue.icu/Article/details/gtmzfzoqcb.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.hammf.cn/Article/details/gtuetpiajz.html

[R59] 发 POST JSON
来源：http://dali.jiagoushi.top/Article/details/gtybktwhpe.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.aibaodan.cn/Article/details/gtqyxnknwr.html

[R60] 只看 HTTP 状态码
来源：http://dali.yj20258888.top/Article/details/gtpbjedvgu.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.c1oappe.top/Article/details/gtlwtzleqy.html

[R61] 磁盘占用
来源：http://dali.nanxuanxn.top/Article/details/gtwwlkdvxn.html

df -h;  du -sh *
来源：http://dali.hywenlv.cn/Article/details/gtifrqlsfo.html

[R62] 找最占空间的文件
来源：http://dali.yuxming.cn/Article/details/gtagncxwis.html

du -ah . | sort -rh | head -10
来源：http://dali.hnxiangtu.top/Article/details/gtrpuyjwzi.html

[R63] 内存与进程
来源：http://dali.tian-w.cn/Article/details/gtdwblasyq.html

free -h;  ps aux | grep nginx
来源：http://dali.tanke756.top/Article/details/gtdkpajxpg.html

[R64] 结束进程
来源：http://dali.chenzaomai.com/Article/details/gtiimekpoa.html

kill -9 $(pgrep -f app.py)
来源：http://dali.gaohongyu789.top/Article/details/gtztmcunkj.html

[R65] 查看端口占用
来源：http://dali.hnqzz.top/Article/details/gthxycectg.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.gotoacloud.top/Article/details/gtzdgujmma.html

[R66] 定时任务
来源：http://dali.yj20258888.top/Article/details/gtsvixnxwl.html

crontab -e;  crontab -l
来源：http://dali.yueranfly.top/Article/details/gtbeufbuno.html

[R67] 生成随机十六进制串
来源：http://dali.birdmap.top/Article/details/gtgvebzpqv.html

openssl rand -hex 16
来源：http://dali.zhengqikj.top/Article/details/gtajnlddvc.html

[R68] 计算文件校验值
来源：http://dali.cdnleiting.top/Article/details/gtxryxghvt.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.gaohongyu789.top/Article/details/gtkxdzyous.html

[R69] 生成随机密码
来源：http://dali.sxryk.cn/Article/details/gtxpexbalo.html

head -c 16 /dev/urandom | base64
来源：http://dali.zdqjudy.top/Article/details/gtsdqbgkem.html

[R70] 时间戳与互转
来源：http://dali.chenlongwang.top/Article/details/gtmuiqhkmn.html

date +%s;  date -d @1700000000
来源：http://dali.zycfv.cn/Article/details/gtkdpuqgqr.html

[R71] 日期格式化
来源：http://dali.yongpay.top/Article/details/gtikajlsls.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.ehwqpu.com/Article/details/gtzhmeolin.html

[R72] 等待端口就绪
来源：http://dali.snrcjt.cn/Article/details/gtalbzmfhc.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.gzhubu.top/Article/details/gtfbejrvsl.html

[R73] 分割大日志
来源：http://dali.mhx1999.top/Article/details/gtcsknjkpv.html

split -l 1000 big.log part_
来源：http://dali.andypj.xyz/Article/details/gtdyujiqly.html

[R74] 批量重命名
来源：http://dali.yj20258888.top/Article/details/gtynxpuiuz.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yangfankeji.com/Article/details/gtarjffzlf.html

[R75] 导出环境变量
来源：http://dali.gotoacloud.top/Article/details/gtpsbrifyi.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.tianlin.xyz/Article/details/gtodllwooq.html

[R76] 使用临时文件
来源：http://dali.nanxinkj.top/Article/details/gtnsnokwfm.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hnxiangtu.top/Article/details/gtkqpxnktp.html

[R77] 读取用户输入
来源：http://dali.snrcjt.cn/Article/details/gtvspqrqyx.html

read -rp "请输入: " ans
来源：http://dali.ivvv.top/Article/details/gtwbgxutaw.html

[R78] 交互式菜单
来源：http://dali.vqdsnc.cn/Article/details/gtbtgdzsie.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteoewixbx.html

[R79] 解析命令行选项
来源：http://dali.cqqwz.cn/Article/details/gtsmckding.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.chenlongwang.top/Article/details/gthyzhsrcb.html

[R80] 查看脚本执行耗时
来源：http://dali.sxryk.cn/Article/details/gtshngitpj.html

time ./run.sh
来源：http://dali.meibo888.top/Article/details/gtkyhkvuda.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtflkixswi.html

S. C / C++ 专题
来源：http://dali.yj20258.top/Article/details/gtjhjgdzof.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtnntlllgi.html

[S01] C：Hello World
来源：http://dali.xziqi.cn/Article/details/gtpsobgavc.html

#include <stdio.h>
来源：http://dali.wangdashe.top/Article/details/gtiqausala.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.mhx1999.top/Article/details/gtzgwqxzda.html

[S02] C：变量与格式化输出
来源：http://dali.ivvv.top/Article/details/gtmxjpodyg.html

int a = 10; printf("%d\n", a);
来源：http://dali.bjfxy.top/Article/details/gtagpsjijy.html

[S03] C：读入整数
来源：http://dali.ehwqpu.com/Article/details/gtxfketcmy.html

int x; scanf("%d", &x);
来源：http://dali.chenjidiqi.icu/Article/details/gtzzzwawdl.html

[S04] C：字符串复制
来源：http://dali.hfpthk.cn/Article/details/gtvusvjxyw.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yonumen.top/Article/details/gturhwyazm.html

[S05] C：字符串长度
来源：http://dali.pengpengdd.cyou/Article/details/gtpnuydpsn.html

strlen(s)
来源：http://dali.daxiang520.top/Article/details/gtfzwlrojd.html

[S06] C：字符串比较
来源：http://dali.gotoacloud.top/Article/details/gtetlohguz.html

strcmp(a, b) == 0
来源：http://dali.jinqigufen.top/Article/details/gtoirdctyz.html

[S07] C：数组遍历求和
来源：http://dali.xziqi.cn/Article/details/gtnodiodlm.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.aizwys.cn/Article/details/gtnaqymgwe.html

[S08] C：动态内存分配与释放
来源：http://dali.sysykeji.top/Article/details/gtxafzcpjj.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.cqqwz.cn/Article/details/gtdkyodcko.html

[S09] C：结构体定义与初始化
来源：http://dali.xziqi.cn/Article/details/gtlituvcco.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.smart0.xyz/Article/details/gttfioatas.html

[S10] C：指针与解引用
来源：http://dali.meibo888.top/Article/details/gtmygsfped.html

int *p = &a;  *p = 5;
来源：http://dali.hnqzz.top/Article/details/gtnrykvqsd.html

[S11] C：逐行读文件
来源：http://dali.hfpthk.cn/Article/details/gtvqmhtzzr.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.quarkkingdee.top/Article/details/gthzstssxe.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.haohaochexian.top/Article/details/gtqsrvvwky.html

fclose(f);
来源：http://dali.shuidangran.top/Article/details/gtrfrowxak.html

[S12] C：写文件
来源：http://dali.cqqwz.cn/Article/details/gttwpbftoq.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.ybcxt.top/Article/details/gtknihvdqs.html

[S13] C：宏定义
来源：http://dali.vqdsnc.cn/Article/details/gtfkejflnm.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.guowangkeji.top/Article/details/gtjingkuhz.html

[S14] C：枚举
来源：http://dali.ybcxt.top/Article/details/gtqvsbnjtx.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ydzc1.top/Article/details/gtxpwzllcv.html

[S15] C：类型转换
来源：http://dali.0kj1m.cn/Article/details/gtreheosjt.html

(double) a / b
来源：http://dali.sysykeji.top/Article/details/gttwlrckmz.html

[S16] C：位操作置位
来源：http://dali.yueranfly.top/Article/details/gtkigoaxwg.html

x |= (1 << 3);
来源：http://dali.xylfe.cn/Article/details/gtpckmnnbl.html

[S17] C：安全拼接字符串
来源：http://dali.yangfankeji.com/Article/details/gtmncnjcuz.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.smart0.xyz/Article/details/gtdlbazyts.html

[S18] C：命令行参数
来源：http://dali.yuanzhike.top/Article/details/gttmgtdjjc.html

int main(int argc, char **argv)
来源：http://dali.hnqzz.top/Article/details/gtovigmjzv.html

[S19] C：快速排序
来源：http://dali.zhoulong.xyz/Article/details/gtoetqzpqj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.iojbl.cn/Article/details/gtpbjnaids.html

[S20] C：二分查找
来源：http://dali.mhx1999.top/Article/details/gtxrhbtpjh.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jlsjyb.cn/Article/details/gtcsozlbbf.html

[S21] C：字符类别判断
来源：http://dali.cdnleiting.top/Article/details/gthqhrmgeg.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gtikcyxzrv.html

[S22] C：字符串转数字
来源：http://dali.ivvv.top/Article/details/gtsdtjgret.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.dashuyun.cn/Article/details/gtelpoaudf.html

[S23] C：随机数
来源：http://dali.xylfe.cn/Article/details/gtjzttjkwh.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.daxiang520.top/Article/details/gtldvhuhfs.html

[S24] C：获取本地时间
来源：http://dali.cashguo.top/Article/details/gthvnkcmak.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hnxiangtu.top/Article/details/gttdcwhzwa.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gtdjioxkzm.html

memcpy(dst, src, n);
来源：http://dali.aibaodan.cn/Article/details/gtsoqffprq.html

[S26] C：内存清零
来源：http://dali.cqqwz.cn/Article/details/gtudgdclrh.html

memset(a, 0, sizeof a);
来源：http://dali.nwbrower.top/Article/details/gtreuffceb.html

[S27] C：定义常量
来源：http://dali.316326.xyz/Article/details/gtkjqhamor.html

const double PI = 3.14159;
来源：http://dali.xziqi.cn/Article/details/gtbetwjxwf.html

[S28] C：静态变量
来源：http://dali.wangshuangyany.cn/Article/details/gtckxfxtsw.html

static int counter = 0;
来源：http://dali.yueranfly.top/Article/details/gtqrzlmsyj.html

[S29] C：变参函数
来源：http://dali.zycfv.cn/Article/details/gtjyvnypvx.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yuanzhike.top/Article/details/gtppwbjhgg.html

[S30] C：头文件保护
来源：http://dali.cashguo.top/Article/details/gtyfqwatji.html

#ifndef X_H
来源：http://dali.redwolf501.top/Article/details/gtlhalbqrg.html

#define X_H
来源：http://dali.yanxiufei.cn/Article/details/gtoosuuvyk.html

#endif
来源：http://dali.cashguo.top/Article/details/gtaysphhaq.html

[S31] C++：Hello World
来源：http://dali.zdqjudy.top/Article/details/gtrgxxukrg.html

#include <iostream>
来源：http://dali.yvedp.cn/Article/details/gtyxjvvxzq.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtkpcvhfys.html

[S32] C++：字符串
来源：http://dali.cqqwz.cn/Article/details/gtipxtzwwi.html

std::string s = "hi";  s += "!";
来源：http://dali.quarkkingdee.top/Article/details/gtvuxsuxld.html

[S33] C++：vector 增删
来源：http://dali.vqdsnc.cn/Article/details/gtuockwqnw.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.ehwqpu.com/Article/details/gtwudanmcf.html

[S34] C++：遍历 vector
来源：http://dali.bjfxy.top/Article/details/gtdaskxdle.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.meibo888.top/Article/details/gtlkksdipb.html

[S35] C++：map
来源：http://dali.feifeiyinyue.top/Article/details/gtnabljbid.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nanxuanxn.top/Article/details/gtxwmdnnru.html

[S36] C++：unordered_map
来源：http://dali.fengsongda.top/Article/details/gtjifbubbc.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tanke756.top/Article/details/gtutwcuazk.html

[S37] C++：set
来源：http://dali.gogol.net.cn/Article/details/gtkpaskkmd.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.0kj1m.cn/Article/details/gthzvvkpsq.html

[S38] C++：排序
来源：http://dali.zdqjudy.top/Article/details/gtddyoqaca.html

std::sort(v.begin(), v.end());
来源：http://dali.iojbl.cn/Article/details/gtrvczmowp.html


<!-- 参考信息 -->