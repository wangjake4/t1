代发 wailian999

SHOW INDEX FROM users;
来源：http://dali.zhengqikj.top/Article/details/gt2cdcxseij.html

[Q73] 查看表状态
来源：http://dali.shuidangran.top/Article/details/gt2ffegdogq.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.hammf.cn/Article/details/gt2etnfxqan.html

[Q74] 强制使用索引
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uuxqnhmj.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.c1oappe.top/Article/details/gt2jqyenhnz.html

[Q75] 日期格式化
来源：http://dali.daria6918.cn/Article/details/gt2sizebags.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qotupwvc.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yonumen.top/Article/details/gt2hbljonsc.html

[Q76] 按天统计
来源：http://dali.guannengcc.top/Article/details/gt2hvkixodx.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jyoumei.cn/Article/details/gt2eyexnolw.html

[Q77] 时间加减
来源：http://dali.smart0.xyz/Article/details/gt2driummar.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zfsyoljm.html

[Q78] 当前时间
来源：http://dali.birdmap.top/Article/details/gt2dphtvpfr.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yj202588.top/Article/details/gt2ylacvxck.html

[Q79] 字符串拼接
来源：http://dali.birdmap.top/Article/details/gt2djugiufo.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.vqdsnc.cn/Article/details/gt2dsbbcosc.html

[Q80] 字符串截取
来源：http://dali.nanxuanxn.top/Article/details/gt2uynfdrmf.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.bjfxy.top/Article/details/gt2tdxtufbc.html

[Q81] 字符串替换
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dgsjkrus.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.shzxlz.cn/Article/details/gt2naxeayyb.html

[Q82] 字符长度与字节长度
来源：http://dali.jiagoushi.top/Article/details/gt2bgoahziw.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gt2mcajlajv.html

[Q83] 大小写转换
来源：http://dali.0kj1m.cn/Article/details/gt2lquppfkm.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.sweek.top/Article/details/gt2ggprtrrt.html

[Q84] 去除首尾空格
来源：http://dali.chenzaomai.com/Article/details/gt2dwdiwrst.html

SELECT TRIM(name) FROM users;
来源：http://dali.sufxvd.cn/Article/details/gt2apsdryqi.html

[Q85] 数值取整
来源：http://dali.sweek.top/Article/details/gt2cwmfuusu.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.quarkkingdee.top/Article/details/gt2ihhjaimu.html

[Q86] 读取 JSON 字段
来源：http://dali.hfpthk.cn/Article/details/gt2odagawuh.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.hywenlv.cn/Article/details/gt2fpumkmtg.html

[Q87] JSON 字段做条件
来源：http://dali.nwbrower.top/Article/details/gt2vicvhatd.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.shangyingyoupin.top/Article/details/gt2oybbyoas.html

[Q88] 行转列（条件聚合）
来源：http://dali.shuidangran.top/Article/details/gt2xbjqreyc.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.0kj1m.cn/Article/details/gt2nwwfypjj.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.cheryme.top/Article/details/gt2vnkxhsxz.html

[Q89] 判断表是否存在
来源：http://dali.cdnleiting.top/Article/details/gt2hiavuxzq.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.hfpthk.cn/Article/details/gt2bjapgfrw.html

[Q90] 生成序号列
来源：http://dali.shuidangran.top/Article/details/gt2xrjpzpgc.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.xylfe.cn/Article/details/gt2xburvhro.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2iodmsege.html

R. Bash 专题
来源：http://dali.guowangkeji.top/Article/details/gt2xdsdofhv.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2qmbmaflh.html

[R01] shebang 与严格模式
来源：http://dali.fzhhl.top/Article/details/gt2khvhdpgf.html

#!/usr/bin/env bash
来源：http://dali.yj20258888.top/Article/details/gt2qesqxwbe.html

set -euo pipefail
来源：http://dali.tian-w.cn/Article/details/gt2bgomfbne.html

[R02] 变量赋值与使用
来源：http://dali.tanke756.top/Article/details/gt2brlzmvvr.html

name="Tom"; echo "$name"
来源：http://dali.9152youxi.cn/Article/details/gt2bnjcdpbw.html

[R03] 只读变量
来源：http://dali.gotoacloud.top/Article/details/gt2vcsledkd.html

readonly PI=3.14
来源：http://dali.hywenlv.cn/Article/details/gt2fymynpeo.html

[R04] 位置参数
来源：http://dali.yj202588.top/Article/details/gt2xwykaung.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hnqzz.top/Article/details/gt2xfcrbhez.html

[R05] 参数默认值
来源：http://dali.xinyue.icu/Article/details/gt2mhcgdfkg.html

name="${1:-default}"
来源：http://dali.zdqjudy.top/Article/details/gt2wlczfdna.html

[R06] 判断命令是否存在
来源：http://dali.tianlin.xyz/Article/details/gt2uhcbyyfw.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.daria6918.cn/Article/details/gt2nzasxhfr.html

[R07] if 判断文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2sofexhgj.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.smart0.xyz/Article/details/gt2rgcnwuft.html

[R08] 数值比较
来源：http://dali.xuanzx.com/Article/details/gt2gqwsmbdq.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.gzhubu.top/Article/details/gt2hbphlsoz.html

[R09] 字符串比较
来源：http://dali.hnxiangtu.top/Article/details/gt2wrqknmjb.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nxviffhz.html

[R10] 正则匹配
来源：http://dali.jqgufenzy.top/Article/details/gt2rtioqgqv.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.xylfe.cn/Article/details/gt2rsyuzyvz.html

[R11] case 多分支
来源：http://dali.snrcjt.cn/Article/details/gt2vysmaoig.html

case "$1" in
来源：http://dali.xylfe.cn/Article/details/gt2kjkyinoo.html

start) echo "启动" ;;
来源：http://dali.quarkkingdee.top/Article/details/gt2fiiwicre.html

stop)  echo "停止" ;;
来源：http://dali.haohaochexian.top/Article/details/gt2ofolmhtg.html

*)     echo "未知命令" ;;
来源：http://dali.xziqi.cn/Article/details/gt2fngyjfhh.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2jkpmawaa.html

[R12] for 遍历文件
来源：http://dali.snrcjt.cn/Article/details/gt2grpkjcdz.html

for f in *.txt; do echo "$f"; done
来源：http://dali.gotoacloud.top/Article/details/gt2mygmrokz.html

[R13] for 计数循环
来源：http://dali.yonumen.top/Article/details/gt2xfwwvxew.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhixingplan.top/Article/details/gt2xbjmcpyx.html

[R14] C 风格 for
来源：http://dali.pycfn.com/Article/details/gt2rpnkmwsd.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.fengsongda.top/Article/details/gt2sepkzxaq.html

[R15] while 逐行读文件
来源：http://dali.yongpay.top/Article/details/gt2pbmmwdqc.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.shuidangran.top/Article/details/gt2kdlokahn.html

[R16] until 等待条件
来源：http://dali.redwolf501.top/Article/details/gt2dvokiygu.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2erzfafnh.html

[R17] 数组定义与取值
来源：http://dali.yongpay.top/Article/details/gt2kxjftuds.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.ppjwa.cn/Article/details/gt2irdxjwoe.html

[R18] 遍历数组
来源：http://dali.316326.xyz/Article/details/gt2kzcftmvc.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.redwolf501.top/Article/details/gt2nafeuctm.html

[R19] 数组长度
来源：http://dali.jqgfzy.top/Article/details/gt2wfbivrst.html

echo "${#arr[@]}"
来源：http://dali.jyoumei.cn/Article/details/gt2kawsbpqi.html

[R20] 关联数组（字典）
来源：http://dali.hnqzz.top/Article/details/gt2fsfkrhee.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tuiezbbu.html

[R21] 字符串长度
来源：http://dali.cheryme.top/Article/details/gt2eibmnmle.html

echo "${#s}"
来源：http://dali.xuanzx.com/Article/details/gt2awjdrlou.html

[R22] 截取子串
来源：http://dali.kuanghao11.cn/Article/details/gt2odyvpqrf.html

echo "${s:0:5}"
来源：http://dali.wangshuangyany.cn/Article/details/gt2hclhqksx.html

[R23] 字符串替换
来源：http://dali.fzhhl.top/Article/details/gt2klfpilak.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhixingplan.top/Article/details/gt2omaxzytt.html

[R24] 大小写转换
来源：http://dali.jlsjyb.cn/Article/details/gt2dvzkrgrb.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yonumen.top/Article/details/gt2hjipfxyt.html

[R25] 去后缀 / 去前缀
来源：http://dali.jinghuilouyu.cn/Article/details/gt2evlqhzmk.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zycfv.cn/Article/details/gt2ykjbycnq.html

[R26] 命令替换
来源：http://dali.nanxuanxn.top/Article/details/gt2fqiofnor.html

now=$(date +%F); echo "$now"
来源：http://dali.zhoulong.xyz/Article/details/gt2qyovstfo.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2iqciafin.html

echo $((1 + 2 * 3))
来源：http://dali.birdmap.top/Article/details/gt2mebuavkk.html

[R28] 浮点运算
来源：http://dali.snrcjt.cn/Article/details/gt2oarpcjqt.html

echo "scale=2; 10/3" | bc
来源：http://dali.ybcxt.top/Article/details/gt2yzckcmrr.html

[R29] 定义函数
来源：http://dali.zhoulong.xyz/Article/details/gt2bygcinkp.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.gaohongyu789.top/Article/details/gt2vwejkhoz.html

[R30] 函数返回状态码
来源：http://dali.sufxvd.cn/Article/details/gt2grfeackq.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.gaohongyu789.top/Article/details/gt2zkmrdzut.html

[R31] 局部变量
来源：http://dali.zhongyouzk.top/Article/details/gt2povhejmj.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhengqikj.top/Article/details/gt2pgxcrrok.html

[R32] 参数个数校验
来源：http://dali.hywenlv.cn/Article/details/gt2tbhrilka.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wwrabtqf.html

[R33] 捕获错误并提示行号
来源：http://dali.sufxvd.cn/Article/details/gt2lwxokxbc.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.xinyue.icu/Article/details/gt2ctgrfqwl.html

[R34] 退出时清理
来源：http://dali.cdnleiting.top/Article/details/gt2imziluio.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jiagoushi.top/Article/details/gt2dpsefpta.html

[R35] 后台执行并等待
来源：http://dali.dianchejie.cn/Article/details/gt2shmuutei.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.fzhhl.top/Article/details/gt2adbuonal.html

[R36] 并发执行多个任务
来源：http://dali.cheryme.top/Article/details/gt2luxidpxl.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hfpthk.cn/Article/details/gt2bjwpqptb.html

[R37] 把输出赋给变量
来源：http://dali.bjfxy.top/Article/details/gt2rnxorybl.html

files=$(ls -1)
来源：http://dali.ehwqpu.com/Article/details/gt2ixydhueg.html

[R38] 管道串联
来源：http://dali.hywenlv.cn/Article/details/gt2ktqapjej.html

cat a.txt | grep -i error | wc -l
来源：http://dali.snrcjt.cn/Article/details/gt2rcsirahx.html

[R39] 重定向标准输出与错误
来源：http://dali.birdmap.top/Article/details/gt2oaaltuek.html

cmd > out.log 2>&1
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wlvdeftn.html

[R40] 追加写日志
来源：http://dali.yj20258888.top/Article/details/gt2ehtllmzu.html

echo "log" >> out.log
来源：http://dali.meibo888.top/Article/details/gt2hykdjkoo.html

[R41] 丢弃输出
来源：http://dali.tian-w.cn/Article/details/gt2ywtwdpdu.html

cmd >/dev/null 2>&1
来源：http://dali.tianlin.xyz/Article/details/gt2zhybocbq.html

[R42] 输入重定向
来源：http://dali.zhoulong.xyz/Article/details/gt2yqgpbcgt.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2thozsqjz.html

[R43] 按名字查找文件
来源：http://dali.hnqzz.top/Article/details/gt2igjgwuxi.html

find . -name "*.log" -type f
来源：http://dali.cashguo.top/Article/details/gt2fiqnmwug.html

[R44] 按修改时间查找
来源：http://dali.yangfankeji.com/Article/details/gt2xzieqxsk.html

find . -mtime -7 -type f
来源：http://dali.gaohongyu789.top/Article/details/gt2qjovzteu.html

[R45] 批量删除
来源：http://dali.guannengcc.top/Article/details/gt2wrkzrhhs.html

find . -name "*.tmp" -delete
来源：http://dali.hongshengwenyu.top/Article/details/gt2kzvqzquz.html

[R46] 递归替换文件内容
来源：http://dali.vqdsnc.cn/Article/details/gt2cmdeihlt.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yj202588.top/Article/details/gt2iopdtesi.html

[R47] sed 单行替换
来源：http://dali.jlsjyb.cn/Article/details/gt2nimpwvll.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.guowangkeji.top/Article/details/gt2zrlvebcs.html

[R48] awk 取指定列
来源：http://dali.nwbrower.top/Article/details/gt2nawusheg.html

awk '{print $1, $3}' a.txt
来源：http://dali.yj202588.top/Article/details/gt2hlrjdtcr.html

[R49] awk 带条件
来源：http://dali.guannengcc.top/Article/details/gt2fayguqsi.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.chenjidiqi.icu/Article/details/gt2wrrxapoj.html

[R50] awk 求和
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bznozlkd.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.c1oappe.top/Article/details/gt2qqvzhxji.html

[R51] 排序去重取前几
来源：http://dali.sysykeji.top/Article/details/gt2smbnbxst.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yj20258.top/Article/details/gt2dfbcbwfl.html

[R52] 统计行数
来源：http://dali.shangyingyoupin.top/Article/details/gt2oufdnnra.html

wc -l a.txt
来源：http://dali.jlsjyb.cn/Article/details/gt2vfvdgiku.html

[R53] 查看文件头与实时尾
来源：http://dali.xinyue.icu/Article/details/gt2izbzuxjj.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.gogol.net.cn/Article/details/gt2bqlbrwws.html

[R54] 比较两个文件
来源：http://dali.cdnleiting.top/Article/details/gt2wjsutyca.html

diff a.txt b.txt
来源：http://dali.fengsongda.top/Article/details/gt2cyzpujip.html

[R55] 压缩与解压
来源：http://dali.hongshengwenyu.top/Article/details/gt2mhjgkwlc.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.shangyingyoupin.top/Article/details/gt2mbwiouef.html

[R56] 远程拷贝
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fdrsdquc.html

scp file user@host:/path/
来源：http://dali.hammf.cn/Article/details/gt2oytplsse.html

[R57] 远程执行命令
来源：http://dali.jinqigufen.top/Article/details/gt2dnmkeots.html

ssh user@host 'uptime'
来源：http://dali.zdqjudy.top/Article/details/gt2mzgzzrhf.html

[R58] 下载文件
来源：http://dali.jianghu66.top/Article/details/gt2cigaiolp.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.gzhubu.top/Article/details/gt2pizmlzwd.html

[R59] 发 POST JSON
来源：http://dali.9152youxi.cn/Article/details/gt2hgnrsglm.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gfvvspcu.html

[R60] 只看 HTTP 状态码
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vgkugwie.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.xziqi.cn/Article/details/gt2fmbgrjdc.html

[R61] 磁盘占用
来源：http://dali.chenlongwang.top/Article/details/gt2exqvxkcp.html

df -h;  du -sh *
来源：http://dali.hongshengwenyu.top/Article/details/gt2dtnktcot.html

[R62] 找最占空间的文件
来源：http://dali.daria6918.cn/Article/details/gt2rprxtqqp.html

du -ah . | sort -rh | head -10
来源：http://dali.xinyue.icu/Article/details/gt2yazgzaoo.html

[R63] 内存与进程
来源：http://dali.tianlin.xyz/Article/details/gt2oaudjssp.html

free -h;  ps aux | grep nginx
来源：http://dali.jlsjyb.cn/Article/details/gt2bavxcnhn.html

[R64] 结束进程
来源：http://dali.9152youxi.cn/Article/details/gt2wgplomxo.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ydzc1.top/Article/details/gt2dsnavmyf.html

[R65] 查看端口占用
来源：http://dali.haohaochexian.top/Article/details/gt2mzwiosrf.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.xziqi.cn/Article/details/gt2okrmvmsp.html

[R66] 定时任务
来源：http://dali.c1oappe.top/Article/details/gt2veeunnuo.html

crontab -e;  crontab -l
来源：http://dali.jyoumei.cn/Article/details/gt2aylnmcxj.html

[R67] 生成随机十六进制串
来源：http://dali.yanxiufei.cn/Article/details/gt2sbmknisi.html

openssl rand -hex 16
来源：http://dali.jinqigfzy.top/Article/details/gt2hiltyqvc.html

[R68] 计算文件校验值
来源：http://dali.guannengcc.top/Article/details/gt2gzlpxqyl.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yuanzhike.top/Article/details/gt2gijbaxtm.html

[R69] 生成随机密码
来源：http://dali.quarkkingdee.top/Article/details/gt2nkjowpdl.html

head -c 16 /dev/urandom | base64
来源：http://dali.vqdsnc.cn/Article/details/gt2seixvtgi.html

[R70] 时间戳与互转
来源：http://dali.ydzc1.top/Article/details/gt2hgxlynoq.html

date +%s;  date -d @1700000000
来源：http://dali.tian-w.cn/Article/details/gt2fcedzjiv.html

[R71] 日期格式化
来源：http://dali.hysaishi.cn/Article/details/gt2utgwhkes.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.fzhhl.top/Article/details/gt2iepxkgrg.html

[R72] 等待端口就绪
来源：http://dali.nanxuanxn.top/Article/details/gt2eyctfboq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.shuidangran.top/Article/details/gt2zodeosxb.html

[R73] 分割大日志
来源：http://dali.ydzc1.top/Article/details/gt2vnlonoja.html

split -l 1000 big.log part_
来源：http://dali.xziqi.cn/Article/details/gt2upxwcxil.html

[R74] 批量重命名
来源：http://dali.gogol.net.cn/Article/details/gt2udsnkdsq.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.wangshuangyany.cn/Article/details/gt2onkejccr.html

[R75] 导出环境变量
来源：http://dali.chenlongwang.top/Article/details/gt2hejxctiw.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.ybcxt.top/Article/details/gt2xrkcnhxd.html

[R76] 使用临时文件
来源：http://dali.zhoulong.xyz/Article/details/gt2zhfqilde.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.wangdashe.top/Article/details/gt2ktgnltbr.html

[R77] 读取用户输入
来源：http://dali.snrcjt.cn/Article/details/gt2tgxjeqid.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2wcikqriy.html

[R78] 交互式菜单
来源：http://dali.vqdsnc.cn/Article/details/gt2hwwsgcbt.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.feifeiyinyue.top/Article/details/gt2jxlgndqg.html

[R79] 解析命令行选项
来源：http://dali.jianghu66.top/Article/details/gt2uvomknen.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zdqjudy.top/Article/details/gt2mmhhrrnk.html

[R80] 查看脚本执行耗时
来源：http://dali.jlsjyb.cn/Article/details/gt2buxtuteu.html

time ./run.sh
来源：http://dali.nanxinkj.top/Article/details/gt2kpdwiamz.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2pyicmyib.html

S. C / C++ 专题
来源：http://dali.fengsongda.top/Article/details/gt2kokhgjib.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2sfjylujr.html

[S01] C：Hello World
来源：http://dali.cdnleiting.top/Article/details/gt2wtuqfyxq.html

#include <stdio.h>
来源：http://dali.jlsjyb.cn/Article/details/gt2vnztpyxp.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.iojbl.cn/Article/details/gt2wjnskzlg.html

[S02] C：变量与格式化输出
来源：http://dali.316326.xyz/Article/details/gt2aftzifln.html

int a = 10; printf("%d\n", a);
来源：http://dali.ybcxt.top/Article/details/gt2zgwwtjml.html

[S03] C：读入整数
来源：http://dali.shangyingyoupin.top/Article/details/gt2zpfcecqo.html

int x; scanf("%d", &x);
来源：http://dali.jyoumei.cn/Article/details/gt2nmefnxin.html

[S04] C：字符串复制
来源：http://dali.xuetiantiany.cn/Article/details/gt2rtlptvww.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jianghu66.top/Article/details/gt2hlyqswsw.html

[S05] C：字符串长度
来源：http://dali.yj202588.top/Article/details/gt2tmcxelix.html

strlen(s)
来源：http://dali.9152youxi.cn/Article/details/gt2dazmjvyg.html

[S06] C：字符串比较
来源：http://dali.sysykeji.top/Article/details/gt2tthwodki.html

strcmp(a, b) == 0
来源：http://dali.snrcjt.cn/Article/details/gt2erysyrkw.html

[S07] C：数组遍历求和
来源：http://dali.ydzc1.top/Article/details/gt2djylumym.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.xylfe.cn/Article/details/gt2oovehmmk.html

[S08] C：动态内存分配与释放
来源：http://dali.guannengcc.top/Article/details/gt2vkjrdlca.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.chenjidiqi.icu/Article/details/gt2yepuptcz.html

[S09] C：结构体定义与初始化
来源：http://dali.quarkkingdee.top/Article/details/gt2esfnikft.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ppjwa.cn/Article/details/gt2ktubswcb.html

[S10] C：指针与解引用
来源：http://dali.chenzaomai.com/Article/details/gt2xzxdpzor.html

int *p = &a;  *p = 5;
来源：http://dali.hysaishi.cn/Article/details/gt2ymwdfwwo.html

[S11] C：逐行读文件
来源：http://dali.xuanzx.com/Article/details/gt2aaxkqbxy.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.gogol.net.cn/Article/details/gt2jdxetghc.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ipckgtrl.html

fclose(f);
来源：http://dali.tanke756.top/Article/details/gt2pyeoqsnk.html

[S12] C：写文件
来源：http://dali.gotoacloud.top/Article/details/gt2ldflplsc.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.c1oappe.top/Article/details/gt2vmayguuw.html

[S13] C：宏定义
来源：http://dali.guowangkeji.top/Article/details/gt2sttxdljc.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zdqjudy.top/Article/details/gt2jrdqxyxw.html

[S14] C：枚举
来源：http://dali.shzxlz.cn/Article/details/gt2hldwoaju.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yangfankeji.com/Article/details/gt2lcxmvgzu.html

[S15] C：类型转换
来源：http://dali.jqgfzy.top/Article/details/gt2nvhrmcyx.html

(double) a / b
来源：http://dali.cucudq.cn/Article/details/gt2dptfuzcm.html

[S16] C：位操作置位
来源：http://dali.wangdashe.top/Article/details/gt2osvuuyvt.html

x |= (1 << 3);
来源：http://dali.nanxinkj.top/Article/details/gt2deglkkbh.html

[S17] C：安全拼接字符串
来源：http://dali.zycfv.cn/Article/details/gt2whpowiot.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yuxming.cn/Article/details/gt2ygszzbqu.html

[S18] C：命令行参数
来源：http://dali.chenlongwang.top/Article/details/gt2tpfsiedu.html

int main(int argc, char **argv)
来源：http://dali.chenzaomai.com/Article/details/gt2ngmfwpfb.html

[S19] C：快速排序
来源：http://dali.hnqzz.top/Article/details/gt2jmmjxsqs.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.havefunace.top/Article/details/gt2ikhopmxu.html

[S20] C：二分查找
来源：http://dali.chenlongwang.top/Article/details/gt2lxyhnool.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yueranfly.top/Article/details/gt2alrsfnjq.html

[S21] C：字符类别判断
来源：http://dali.smart0.xyz/Article/details/gt2odohstxt.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.chenlongwang.top/Article/details/gt2sbkumzay.html

[S22] C：字符串转数字
来源：http://dali.cheryme.top/Article/details/gt2lxiimbcb.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.9152youxi.cn/Article/details/gt2ctvnrrvt.html

[S23] C：随机数
来源：http://dali.nanxuanxn.top/Article/details/gt2ywpftgwl.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.nwbrower.top/Article/details/gt2mxnpbgin.html

[S24] C：获取本地时间
来源：http://dali.mhx1999.top/Article/details/gt2erhkfbgw.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.smart0.xyz/Article/details/gt2ltsnlilq.html

[S25] C：内存拷贝
来源：http://dali.yj20258.top/Article/details/gt2bqjvliwk.html

memcpy(dst, src, n);
来源：http://dali.ivvv.top/Article/details/gt2bwdisztu.html

[S26] C：内存清零
来源：http://dali.nanxinkj.top/Article/details/gt2qxgpqhng.html

memset(a, 0, sizeof a);
来源：http://dali.smart0.xyz/Article/details/gt2pzvgvtkl.html

[S27] C：定义常量
来源：http://dali.jiagoushi.top/Article/details/gt2dwuvnbxc.html

const double PI = 3.14159;
来源：http://dali.sweek.top/Article/details/gt2rlfkomhf.html

[S28] C：静态变量
来源：http://dali.jlsjyb.cn/Article/details/gt2fkrqmtiq.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2uxirqiey.html

[S29] C：变参函数
来源：http://dali.sxryk.cn/Article/details/gt2uwjesvgz.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2duegjvbf.html

[S30] C：头文件保护
来源：http://dali.ehwqpu.com/Article/details/gt2uwjbgvsp.html

#ifndef X_H
来源：http://dali.feifeiyinyue.top/Article/details/gt2whhrpwri.html

#define X_H
来源：http://dali.9152youxi.cn/Article/details/gt2xcqjaypd.html

#endif
来源：http://dali.yueranfly.top/Article/details/gt2wkuwswkq.html

[S31] C++：Hello World
来源：http://dali.wangdashe.top/Article/details/gt2ohiwkhfh.html

#include <iostream>
来源：http://dali.sxryk.cn/Article/details/gt2izrluhyf.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jinqigufen.top/Article/details/gt2utojvgnn.html

[S32] C++：字符串
来源：http://dali.xinyue.icu/Article/details/gt2auxbubwi.html

std::string s = "hi";  s += "!";
来源：http://dali.fzhhl.top/Article/details/gt2jmucasuh.html

[S33] C++：vector 增删
来源：http://dali.smart0.xyz/Article/details/gt2nklhlpno.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yj20258.top/Article/details/gt2fqlanijv.html

[S34] C++：遍历 vector
来源：http://dali.hammf.cn/Article/details/gt2xerbvqkm.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.guowangkeji.top/Article/details/gt2zlticmbf.html

[S35] C++：map
来源：http://dali.daxiang520.top/Article/details/gt2dqfgbntr.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nanxinkj.top/Article/details/gt2hqmilacg.html

[S36] C++：unordered_map
来源：http://dali.tianlin.xyz/Article/details/gt2uksimxbm.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yuxming.cn/Article/details/gt2ijwqgetg.html

[S37] C++：set
来源：http://dali.aizwys.cn/Article/details/gt2nmozywxb.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.haohaochexian.top/Article/details/gt2abvgpgcc.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vjyzfcgy.html

std::sort(v.begin(), v.end());
来源：http://dali.zhengqikj.top/Article/details/gt2qukmepxg.html

[S39] C++：自定义比较器排序
来源：http://dali.sxryk.cn/Article/details/gt2kwimurtr.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.feifeiyinyue.top/Article/details/gt2pytonvuk.html

[S40] C++：查找元素
来源：http://dali.ppjwa.cn/Article/details/gt2ugqaboaf.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ehwqpu.com/Article/details/gt2pfnpocab.html

[S41] C++：类与构造函数
来源：http://dali.shangyingyoupin.top/Article/details/gt2xkvdirhn.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.chenjidiqi.icu/Article/details/gt2eutnadzl.html

[S42] C++：继承与虚函数
来源：http://dali.sysykeji.top/Article/details/gt2rkgcgjgi.html

class B : public Base { public: void f() override {} };
来源：http://dali.hysaishi.cn/Article/details/gt2zluhnatr.html


<!-- 参考信息 -->