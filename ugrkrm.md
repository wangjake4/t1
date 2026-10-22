代发 wailian999

[Q80] 字符串截取
来源：http://dali.yj202588.top/Article/details/gt2iljvuzir.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.gzhubu.top/Article/details/gt2vqxsfuqa.html

[Q81] 字符串替换
来源：http://dali.tianlin.xyz/Article/details/gt2sqdgoxvq.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.fengsongda.top/Article/details/gt2hkxzxegn.html

[Q82] 字符长度与字节长度
来源：http://dali.xylfe.cn/Article/details/gt2ybpleska.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gt2ynyfdohy.html

[Q83] 大小写转换
来源：http://dali.andypj.xyz/Article/details/gt2jitpjlez.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gt2shuhplas.html

[Q84] 去除首尾空格
来源：http://dali.haohaochexian.top/Article/details/gt2rtgkotwo.html

SELECT TRIM(name) FROM users;
来源：http://dali.shzxlz.cn/Article/details/gt2zgzzequq.html

[Q85] 数值取整
来源：http://dali.ydzc1.top/Article/details/gt2dnhbuwcw.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.chenlongwang.top/Article/details/gt2bpeiyizw.html

[Q86] 读取 JSON 字段
来源：http://dali.ehwqpu.com/Article/details/gt2ggyquues.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.wangdashe.top/Article/details/gt2ddpbbayf.html

[Q87] JSON 字段做条件
来源：http://dali.nwbrower.top/Article/details/gt2xwrfdvop.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.haohaochexian.top/Article/details/gt2hyfrdlwo.html

[Q88] 行转列（条件聚合）
来源：http://dali.cqqwz.cn/Article/details/gt2ovvdyucg.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.redwolf501.top/Article/details/gt2wdcoukwf.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jqgfzy.top/Article/details/gt2yyzojgbm.html

[Q89] 判断表是否存在
来源：http://dali.sysykeji.top/Article/details/gt2nhxjcpaw.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.guowangkeji.top/Article/details/gt2vouwclls.html

[Q90] 生成序号列
来源：http://dali.gogol.net.cn/Article/details/gt2ihjfoyjy.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.sufxvd.cn/Article/details/gt2sdxxuzov.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2ipjjuvef.html

R. Bash 专题
来源：http://dali.smart0.xyz/Article/details/gt2mapmaxvk.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2iwbspawm.html

[R01] shebang 与严格模式
来源：http://dali.pycfn.com/Article/details/gt2bfiwdaqf.html

#!/usr/bin/env bash
来源：http://dali.vqdsnc.cn/Article/details/gt2lchhdlxy.html

set -euo pipefail
来源：http://dali.andypj.xyz/Article/details/gt2wdanqhdr.html

[R02] 变量赋值与使用
来源：http://dali.zycfv.cn/Article/details/gt2qrvhrlcd.html

name="Tom"; echo "$name"
来源：http://dali.nanxuanxn.top/Article/details/gt2mwtxqefn.html

[R03] 只读变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jhudmifb.html

readonly PI=3.14
来源：http://dali.jianghu66.top/Article/details/gt2harmwnjz.html

[R04] 位置参数
来源：http://dali.nanxuanxn.top/Article/details/gt2ettitwab.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.nanxinkj.top/Article/details/gt2arjlugsc.html

[R05] 参数默认值
来源：http://dali.gaohongyu789.top/Article/details/gt2lagfuqoe.html

name="${1:-default}"
来源：http://dali.zhengqikj.top/Article/details/gt2wgvpsulk.html

[R06] 判断命令是否存在
来源：http://dali.cashguo.top/Article/details/gt2nciqijol.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gjmyekyh.html

[R07] if 判断文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hbspuxlc.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.sufxvd.cn/Article/details/gt2mwbepawo.html

[R08] 数值比较
来源：http://dali.jqgufenzy.top/Article/details/gt2ejeqnssj.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.dianchejie.cn/Article/details/gt2ihumngys.html

[R09] 字符串比较
来源：http://dali.gzhubu.top/Article/details/gt2azytgpba.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xuetiantiany.cn/Article/details/gt2gsjiprmh.html

[R10] 正则匹配
来源：http://dali.zhoulong.xyz/Article/details/gt2bemqudta.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.sxryk.cn/Article/details/gt2uyfvhhcw.html

[R11] case 多分支
来源：http://dali.yuxming.cn/Article/details/gt2nkgkpybu.html

case "$1" in
来源：http://dali.nanxinkj.top/Article/details/gt2fgaubzfn.html

start) echo "启动" ;;
来源：http://dali.cashguo.top/Article/details/gt2cgosuqnh.html

stop)  echo "停止" ;;
来源：http://dali.nanxinkj.top/Article/details/gt2kyvkppnd.html

*)     echo "未知命令" ;;
来源：http://dali.quarkkingdee.top/Article/details/gt2pucfalol.html

esac
来源：http://dali.iojbl.cn/Article/details/gt2bepbxokt.html

[R12] for 遍历文件
来源：http://dali.sufxvd.cn/Article/details/gt2zynmkwoy.html

for f in *.txt; do echo "$f"; done
来源：http://dali.svipenyu.cn/Article/details/gt2efocbsph.html

[R13] for 计数循环
来源：http://dali.smart0.xyz/Article/details/gt2qquzfvnr.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.wangshuangyany.cn/Article/details/gt2yleoskbh.html

[R14] C 风格 for
来源：http://dali.ivvv.top/Article/details/gt2gadtypzv.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.cheryme.top/Article/details/gt2qnmlttdq.html

[R15] while 逐行读文件
来源：http://dali.316326.xyz/Article/details/gt2bhgimghe.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.xuetiantiany.cn/Article/details/gt2euhoaypm.html

[R16] until 等待条件
来源：http://dali.sufxvd.cn/Article/details/gt2yblvpksp.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.xziqi.cn/Article/details/gt2fbdelrfn.html

[R17] 数组定义与取值
来源：http://dali.shuidangran.top/Article/details/gt2ibmzlxef.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.hnqzz.top/Article/details/gt2rkpacfzz.html

[R18] 遍历数组
来源：http://dali.chenzaomai.com/Article/details/gt2iutluocb.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.0kj1m.cn/Article/details/gt2cronvyrs.html

[R19] 数组长度
来源：http://dali.cheryme.top/Article/details/gt2vdjpttiu.html

echo "${#arr[@]}"
来源：http://dali.yongpay.top/Article/details/gt2xvegwzda.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2lfhjpoyu.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhixingplan.top/Article/details/gt2uglfdmzb.html

[R21] 字符串长度
来源：http://dali.xziqi.cn/Article/details/gt2agznximf.html

echo "${#s}"
来源：http://dali.hongshengwenyu.top/Article/details/gt2cfkkllbs.html

[R22] 截取子串
来源：http://dali.yonumen.top/Article/details/gt2tydmbnij.html

echo "${s:0:5}"
来源：http://dali.nwbrower.top/Article/details/gt2aooqphgl.html

[R23] 字符串替换
来源：http://dali.gotoacloud.top/Article/details/gt2cgjdseaa.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jiagoushi.top/Article/details/gt2qthosrxv.html

[R24] 大小写转换
来源：http://dali.c1oappe.top/Article/details/gt2fjkrllle.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hywenlv.cn/Article/details/gt2gwxbqhtt.html

[R25] 去后缀 / 去前缀
来源：http://dali.jinqigufen.top/Article/details/gt2rcvrjwtr.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhiwuduotai.top/Article/details/gt2uauesnrh.html

[R26] 命令替换
来源：http://dali.yongpay.top/Article/details/gt2smphxkcs.html

now=$(date +%F); echo "$now"
来源：http://dali.vqdsnc.cn/Article/details/gt2nwjxrvga.html

[R27] 算术展开
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dibbqzpt.html

echo $((1 + 2 * 3))
来源：http://dali.gaohongyu789.top/Article/details/gt2vsfokrvd.html

[R28] 浮点运算
来源：http://dali.havefunace.top/Article/details/gt2stwckokl.html

echo "scale=2; 10/3" | bc
来源：http://dali.cashguo.top/Article/details/gt2ewopyudw.html

[R29] 定义函数
来源：http://dali.gzhubu.top/Article/details/gt2ndguoguf.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uhpmgohf.html

[R30] 函数返回状态码
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2clkbwqkl.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yueranfly.top/Article/details/gt2fslnpxat.html

[R31] 局部变量
来源：http://dali.guannengcc.top/Article/details/gt2caubyymu.html

f() { local x=1; echo "$x"; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2bxngafrg.html

[R32] 参数个数校验
来源：http://dali.aibaodan.cn/Article/details/gt2wndwkzyy.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.ybcxt.top/Article/details/gt2hfflrhcm.html

[R33] 捕获错误并提示行号
来源：http://dali.shzxlz.cn/Article/details/gt2qhybbpqq.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.dashuyun.cn/Article/details/gt2aihomlzm.html

[R34] 退出时清理
来源：http://dali.zhongyouzk.top/Article/details/gt2jdpqzwjs.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhiwuduotai.top/Article/details/gt2tbquinoo.html

[R35] 后台执行并等待
来源：http://dali.sxryk.cn/Article/details/gt2zkmqnzvm.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2uvbtopoo.html

[R36] 并发执行多个任务
来源：http://dali.pengpengdd.cyou/Article/details/gt2cszikaqq.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yanxiufei.cn/Article/details/gt2jbgxxatx.html

[R37] 把输出赋给变量
来源：http://dali.mhx1999.top/Article/details/gt2nfidxtqb.html

files=$(ls -1)
来源：http://dali.sufxvd.cn/Article/details/gt2qltrpwgz.html

[R38] 管道串联
来源：http://dali.xuetiantiany.cn/Article/details/gt2epiatwyi.html

cat a.txt | grep -i error | wc -l
来源：http://dali.shuidangran.top/Article/details/gt2zcvlqnwo.html

[R39] 重定向标准输出与错误
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dlujvyme.html

cmd > out.log 2>&1
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2omyetzex.html

[R40] 追加写日志
来源：http://dali.zhongyouzk.top/Article/details/gt2coincgyi.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2suerqzee.html

[R41] 丢弃输出
来源：http://dali.sxryk.cn/Article/details/gt2hswvzszo.html

cmd >/dev/null 2>&1
来源：http://dali.smart0.xyz/Article/details/gt2lqkdtxfw.html

[R42] 输入重定向
来源：http://dali.yueranfly.top/Article/details/gt2dsqoizhh.html

wc -l < a.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2refwpqbz.html

[R43] 按名字查找文件
来源：http://dali.yongpay.top/Article/details/gt2hhawxkdd.html

find . -name "*.log" -type f
来源：http://dali.pengpengdd.cyou/Article/details/gt2dxqqeslw.html

[R44] 按修改时间查找
来源：http://dali.cqqwz.cn/Article/details/gt2xnxeejby.html

find . -mtime -7 -type f
来源：http://dali.meibo888.top/Article/details/gt2nbcimibt.html

[R45] 批量删除
来源：http://dali.yj20258888.top/Article/details/gt2slwjgqer.html

find . -name "*.tmp" -delete
来源：http://dali.cqqwz.cn/Article/details/gt2usfxborw.html

[R46] 递归替换文件内容
来源：http://dali.sweek.top/Article/details/gt2dskectxa.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.sweek.top/Article/details/gt2wzpzdjba.html

[R47] sed 单行替换
来源：http://dali.jlsjyb.cn/Article/details/gt2zuthhxxm.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.nanxuanxn.top/Article/details/gt2vrltrysa.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2rdkztdut.html

awk '{print $1, $3}' a.txt
来源：http://dali.xziqi.cn/Article/details/gt2zxeuwvnn.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mtivcyft.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.daxiang520.top/Article/details/gt2qbxhnhou.html

[R50] awk 求和
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zwasuxri.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gt2elbwgdlg.html

[R51] 排序去重取前几
来源：http://dali.hfpthk.cn/Article/details/gt2xiqfulea.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.hywenlv.cn/Article/details/gt2rdtjdqdu.html

[R52] 统计行数
来源：http://dali.birdmap.top/Article/details/gt2ncyhsuye.html

wc -l a.txt
来源：http://dali.wangshuangyany.cn/Article/details/gt2srakyyan.html

[R53] 查看文件头与实时尾
来源：http://dali.jqgufenzy.top/Article/details/gt2aduzhmyf.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.dianchejie.cn/Article/details/gt2htgoggnu.html

[R54] 比较两个文件
来源：http://dali.hysaishi.cn/Article/details/gt2lyccxqdn.html

diff a.txt b.txt
来源：http://dali.yangfankeji.com/Article/details/gt2qjjyovwu.html

[R55] 压缩与解压
来源：http://dali.xylfe.cn/Article/details/gt2dcccpwhc.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.cucudq.cn/Article/details/gt2wirbrqsg.html

[R56] 远程拷贝
来源：http://dali.wangdashe.top/Article/details/gt2vsmflxtj.html

scp file user@host:/path/
来源：http://dali.zhongyouzk.top/Article/details/gt2ccsyahux.html

[R57] 远程执行命令
来源：http://dali.yueranfly.top/Article/details/gt2ozizkuug.html

ssh user@host 'uptime'
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rylunspp.html

[R58] 下载文件
来源：http://dali.xziqi.cn/Article/details/gt2hrdnvcgu.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.sysykeji.top/Article/details/gt2cvoxsrfn.html

[R59] 发 POST JSON
来源：http://dali.jyoumei.cn/Article/details/gt2kckgqwev.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.feifeiyinyue.top/Article/details/gt2oahsrjkq.html

[R60] 只看 HTTP 状态码
来源：http://dali.ydzc1.top/Article/details/gt2lfsgxand.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ivvv.top/Article/details/gt2ldpirchj.html

[R61] 磁盘占用
来源：http://dali.fzhhl.top/Article/details/gt2saafaxmz.html

df -h;  du -sh *
来源：http://dali.dashuyun.cn/Article/details/gt2ykiinfuu.html

[R62] 找最占空间的文件
来源：http://dali.pengpengdd.cyou/Article/details/gt2vvvlulde.html

du -ah . | sort -rh | head -10
来源：http://dali.birdmap.top/Article/details/gt2srwjyuop.html

[R63] 内存与进程
来源：http://dali.dashuyun.cn/Article/details/gt2qhcukqmf.html

free -h;  ps aux | grep nginx
来源：http://dali.gogol.net.cn/Article/details/gt2utureuur.html

[R64] 结束进程
来源：http://dali.fengsongda.top/Article/details/gt2eihzuvar.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jiagoushi.top/Article/details/gt2qlkquauj.html

[R65] 查看端口占用
来源：http://dali.nwbrower.top/Article/details/gt2ypgexiqu.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.316326.xyz/Article/details/gt2gizdadkn.html

[R66] 定时任务
来源：http://dali.yvedp.cn/Article/details/gt2takdfgtq.html

crontab -e;  crontab -l
来源：http://dali.cheryme.top/Article/details/gt2onbfdbld.html

[R67] 生成随机十六进制串
来源：http://dali.chenlongwang.top/Article/details/gt2edzfigtp.html

openssl rand -hex 16
来源：http://dali.hywenlv.cn/Article/details/gt2vobqwohe.html

[R68] 计算文件校验值
来源：http://dali.aizwys.cn/Article/details/gt2bjradxuo.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.hywenlv.cn/Article/details/gt2rwyijnvj.html

[R69] 生成随机密码
来源：http://dali.hysaishi.cn/Article/details/gt2fsjelwjd.html

head -c 16 /dev/urandom | base64
来源：http://dali.fengsongda.top/Article/details/gt2bshletov.html

[R70] 时间戳与互转
来源：http://dali.hysaishi.cn/Article/details/gt2cemuaduv.html

date +%s;  date -d @1700000000
来源：http://dali.zhoulong.xyz/Article/details/gt2bhwhohcm.html

[R71] 日期格式化
来源：http://dali.jianghu66.top/Article/details/gt2ghzkurjz.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhixingplan.top/Article/details/gt2esenftge.html

[R72] 等待端口就绪
来源：http://dali.haohaochexian.top/Article/details/gt2tybyyamo.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.0kj1m.cn/Article/details/gt2ghpwhwdh.html

[R73] 分割大日志
来源：http://dali.aizwys.cn/Article/details/gt2fohbrmoi.html

split -l 1000 big.log part_
来源：http://dali.ydzc1.top/Article/details/gt2kswztiod.html

[R74] 批量重命名
来源：http://dali.jianghu66.top/Article/details/gt2oatwyhxv.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.sxryk.cn/Article/details/gt2pxekvbln.html

[R75] 导出环境变量
来源：http://dali.yj20258888.top/Article/details/gt2kfhhybej.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2acgyuciu.html

[R76] 使用临时文件
来源：http://dali.tianlin.xyz/Article/details/gt2fbyleupc.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.9152youxi.cn/Article/details/gt2nbtancfw.html

[R77] 读取用户输入
来源：http://dali.aizwys.cn/Article/details/gt2ovfmdelb.html

read -rp "请输入: " ans
来源：http://dali.yanxiufei.cn/Article/details/gt2cdbdtlee.html

[R78] 交互式菜单
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gayyevpx.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jqgufenzy.top/Article/details/gt2ngdtxgpj.html

[R79] 解析命令行选项
来源：http://dali.yongpay.top/Article/details/gt2dxvjksoi.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.dashuyun.cn/Article/details/gt2asaykefz.html

[R80] 查看脚本执行耗时
来源：http://dali.hywenlv.cn/Article/details/gt2cmzuompx.html

time ./run.sh
来源：http://dali.cucudq.cn/Article/details/gt2xjdfssrk.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2okjvuzol.html

S. C / C++ 专题
来源：http://dali.9152youxi.cn/Article/details/gt2cjrquuvd.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2larmdfpn.html

[S01] C：Hello World
来源：http://dali.9152youxi.cn/Article/details/gt2nuwnxqyi.html

#include <stdio.h>
来源：http://dali.aibaodan.cn/Article/details/gt2twrnixet.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.shuidangran.top/Article/details/gt2ecnxritn.html

[S02] C：变量与格式化输出
来源：http://dali.quarkkingdee.top/Article/details/gt2moevatan.html

int a = 10; printf("%d\n", a);
来源：http://dali.cdnleiting.top/Article/details/gt2dwwzifmy.html

[S03] C：读入整数
来源：http://dali.zhongyouzk.top/Article/details/gt2fwfpsqej.html

int x; scanf("%d", &x);
来源：http://dali.wangdashe.top/Article/details/gt2zsemnlin.html

[S04] C：字符串复制
来源：http://dali.yj202588.top/Article/details/gt2pugkpyfi.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.smart0.xyz/Article/details/gt2hqrsrpev.html

[S05] C：字符串长度
来源：http://dali.tianlin.xyz/Article/details/gt2oigipjkh.html

strlen(s)
来源：http://dali.yonumen.top/Article/details/gt2vivqpdka.html

[S06] C：字符串比较
来源：http://dali.cheryme.top/Article/details/gt2soafbmqy.html

strcmp(a, b) == 0
来源：http://dali.hnxiangtu.top/Article/details/gt2tsqstptr.html

[S07] C：数组遍历求和
来源：http://dali.yj20258.top/Article/details/gt2wnjvpflu.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.ybcxt.top/Article/details/gt2wcfmukvl.html

[S08] C：动态内存分配与释放
来源：http://dali.hnxiangtu.top/Article/details/gt2zqeeuxpu.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yuxming.cn/Article/details/gt2abfxiqyj.html

[S09] C：结构体定义与初始化
来源：http://dali.yvedp.cn/Article/details/gt2nfyifiel.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhoulong.xyz/Article/details/gt2woowamrf.html

[S10] C：指针与解引用
来源：http://dali.chenzaomai.com/Article/details/gt2uywyvtls.html

int *p = &a;  *p = 5;
来源：http://dali.nanxinkj.top/Article/details/gt2whheepcb.html

[S11] C：逐行读文件
来源：http://dali.haohaochexian.top/Article/details/gt2oxwuetjz.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jaoyvane.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wfadwqas.html

fclose(f);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uglkdazt.html

[S12] C：写文件
来源：http://dali.hammf.cn/Article/details/gt2culkaucy.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hysaishi.cn/Article/details/gt2edmgvebl.html

[S13] C：宏定义
来源：http://dali.ivvv.top/Article/details/gt2wkpfkvam.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.nanxuanxn.top/Article/details/gt2hrbuqoxu.html

[S14] C：枚举
来源：http://dali.gogol.net.cn/Article/details/gt2foffgpgr.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.0kj1m.cn/Article/details/gt2iqflqbfw.html

[S15] C：类型转换
来源：http://dali.nanxuanxn.top/Article/details/gt2kdpqclzx.html

(double) a / b
来源：http://dali.quarkkingdee.top/Article/details/gt2aggkphax.html

[S16] C：位操作置位
来源：http://dali.fzhhl.top/Article/details/gt2jhvfysnf.html

x |= (1 << 3);
来源：http://dali.cucudq.cn/Article/details/gt2twafylrq.html

[S17] C：安全拼接字符串
来源：http://dali.dianchejie.cn/Article/details/gt2tgovodwc.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhixingplan.top/Article/details/gt2uicapfxg.html

[S18] C：命令行参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kgincpzo.html

int main(int argc, char **argv)
来源：http://dali.hnqzz.top/Article/details/gt2gnmmyoyn.html

[S19] C：快速排序
来源：http://dali.meibo888.top/Article/details/gt2eumjnocd.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jinqigufen.top/Article/details/gt2edkywvsy.html

[S20] C：二分查找
来源：http://dali.ydzc1.top/Article/details/gt2ejzguqgf.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jyoumei.cn/Article/details/gt2pjfwrmay.html

[S21] C：字符类别判断
来源：http://dali.jinqigfzy.top/Article/details/gt2ufnbvznj.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jqgufenzy.top/Article/details/gt2mlznrcvb.html

[S22] C：字符串转数字
来源：http://dali.zycfv.cn/Article/details/gt2yrwacwmb.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.316326.xyz/Article/details/gt2tcczcgpc.html

[S23] C：随机数
来源：http://dali.gaohongyu789.top/Article/details/gt2lqnbxznn.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hammf.cn/Article/details/gt2fqsecunm.html

[S24] C：获取本地时间
来源：http://dali.gzhubu.top/Article/details/gt2rsnzpqgg.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.andypj.xyz/Article/details/gt2xkistyxy.html

[S25] C：内存拷贝
来源：http://dali.pengpengdd.cyou/Article/details/gt2xiyanwds.html

memcpy(dst, src, n);
来源：http://dali.cashguo.top/Article/details/gt2vcsqkbnl.html

[S26] C：内存清零
来源：http://dali.cdnleiting.top/Article/details/gt2ljfmkiue.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2aklpisgv.html

[S27] C：定义常量
来源：http://dali.9152youxi.cn/Article/details/gt2fjtfrtsh.html

const double PI = 3.14159;
来源：http://dali.xinyue.icu/Article/details/gt2vwzklzos.html

[S28] C：静态变量
来源：http://dali.tian-w.cn/Article/details/gt2swsbzanx.html

static int counter = 0;
来源：http://dali.snrcjt.cn/Article/details/gt2uijobxlz.html

[S29] C：变参函数
来源：http://dali.gogol.net.cn/Article/details/gt2kuypytwm.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jyoumei.cn/Article/details/gt2vfbcykdf.html

[S30] C：头文件保护
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mudujogx.html

#ifndef X_H
来源：http://dali.birdmap.top/Article/details/gt2dtwwpmja.html

#define X_H
来源：http://dali.jlsjyb.cn/Article/details/gt2ideegotw.html

#endif
来源：http://dali.kuanghao11.cn/Article/details/gt2swlrasqz.html

[S31] C++：Hello World
来源：http://dali.xylfe.cn/Article/details/gt2oxkqifvc.html

#include <iostream>
来源：http://dali.jyoumei.cn/Article/details/gt2ewbgpokk.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.aizwys.cn/Article/details/gt2obpenxaf.html

[S32] C++：字符串
来源：http://dali.chenlongwang.top/Article/details/gt2bihvycqd.html

std::string s = "hi";  s += "!";
来源：http://dali.yuxming.cn/Article/details/gt2fxjsoxbf.html

[S33] C++：vector 增删
来源：http://dali.hammf.cn/Article/details/gt2hattttlz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.aizwys.cn/Article/details/gt2jvwihleb.html

[S34] C++：遍历 vector
来源：http://dali.haohaochexian.top/Article/details/gt2alkjqkql.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.xziqi.cn/Article/details/gt2zancwaqs.html

[S35] C++：map
来源：http://dali.jqgufenzy.top/Article/details/gt2balvoois.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.havefunace.top/Article/details/gt2xzqxuiui.html

[S36] C++：unordered_map
来源：http://dali.sysykeji.top/Article/details/gt2ltwzxtvp.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shuidangran.top/Article/details/gt2eqyowlhy.html

[S37] C++：set
来源：http://dali.xuetiantiany.cn/Article/details/gt2rrkbfyvr.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hywenlv.cn/Article/details/gt2kmcyvjss.html

[S38] C++：排序
来源：http://dali.yueranfly.top/Article/details/gt2nqbysgmd.html

std::sort(v.begin(), v.end());
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nwhwpsjn.html

[S39] C++：自定义比较器排序
来源：http://dali.daxiang520.top/Article/details/gt2limtbdnf.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yuanzhike.top/Article/details/gt2mnqjfrun.html

[S40] C++：查找元素
来源：http://dali.svipenyu.cn/Article/details/gt2ktptssxw.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.nwbrower.top/Article/details/gt2tcflqfgf.html

[S41] C++：类与构造函数
来源：http://dali.cashguo.top/Article/details/gt2oiguwkeo.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zjysnywd.html

[S42] C++：继承与虚函数
来源：http://dali.zhiwuduotai.top/Article/details/gt2ubkvvipx.html

class B : public Base { public: void f() override {} };
来源：http://dali.guannengcc.top/Article/details/gt2rtqeudpn.html

[S43] C++：智能指针
来源：http://dali.jiagoushi.top/Article/details/gt2plquftir.html

auto p = std::make_unique<int>(5);
来源：http://dali.jinqigufen.top/Article/details/gt2ujlgiemv.html

[S44] C++：引用传参
来源：http://dali.yj202588.top/Article/details/gt2xhnjsvny.html

void inc(int &x) { ++x; }
来源：http://dali.jyoumei.cn/Article/details/gt2gssdnjcn.html

[S45] C++：lambda
来源：http://dali.hywenlv.cn/Article/details/gt2mbtexkvl.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.c1oappe.top/Article/details/gt2yvwrkmrz.html

[S46] C++：函数模板
来源：http://dali.hysaishi.cn/Article/details/gt2phhgmnax.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.hfpthk.cn/Article/details/gt2wqxetsni.html

[S47] C++：结构化绑定遍历
来源：http://dali.jinqigufen.top/Article/details/gt2qyzutuaq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2kxetnbgx.html

[S48] C++：逐行读文件
来源：http://dali.sxryk.cn/Article/details/gt2cktwovzo.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.c1oappe.top/Article/details/gt2jhakpwut.html

while (std::getline(in, line)) { }
来源：http://dali.gotoacloud.top/Article/details/gt2otbhtjaj.html

[S49] C++：写文件
来源：http://dali.kuanghao11.cn/Article/details/gt2uipopmik.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yvedp.cn/Article/details/gt2alhqvhej.html

[S50] C++：格式化数字
来源：http://dali.nwbrower.top/Article/details/gt2fjxbbphm.html


<!-- 参考信息 -->