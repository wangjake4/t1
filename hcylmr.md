代发 wailian999

[Q82] 字符长度与字节长度
来源：http://dali.kuanghao11.cn/Article/details/gt2imqgtlyx.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.hywenlv.cn/Article/details/gt2tvtlgnti.html

[Q83] 大小写转换
来源：http://dali.xuanzx.com/Article/details/gt2dqxnmcmb.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.hysaishi.cn/Article/details/gt2mrqfeniz.html

[Q84] 去除首尾空格
来源：http://dali.ydzc1.top/Article/details/gt2avokbusw.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhengqikj.top/Article/details/gt2eirghyuy.html

[Q85] 数值取整
来源：http://dali.zhongyouzk.top/Article/details/gt2crmhlppp.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.hnxiangtu.top/Article/details/gt2btwkijly.html

[Q86] 读取 JSON 字段
来源：http://dali.ybcxt.top/Article/details/gt2ehzlniwy.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.tian-w.cn/Article/details/gt2hfeywlvl.html

[Q87] JSON 字段做条件
来源：http://dali.tianlin.xyz/Article/details/gt2oordknza.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.aizwys.cn/Article/details/gt2qdbfbesl.html

[Q88] 行转列（条件聚合）
来源：http://dali.yvedp.cn/Article/details/gt2ahxntxgo.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.xinyue.icu/Article/details/gt2pnqociza.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hywenlv.cn/Article/details/gt2sfqkbglu.html

[Q89] 判断表是否存在
来源：http://dali.dianchejie.cn/Article/details/gt2wajrhwle.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.cqqwz.cn/Article/details/gt2nhurffkv.html

[Q90] 生成序号列
来源：http://dali.xziqi.cn/Article/details/gt2rbpjfibx.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.xinyue.icu/Article/details/gt2cilulvzw.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2dztmfefd.html

R. Bash 专题
来源：http://dali.jqgufenzy.top/Article/details/gt2cpfopjkc.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2ayhhiict.html

[R01] shebang 与严格模式
来源：http://dali.nwbrower.top/Article/details/gt2mmxzscqc.html

#!/usr/bin/env bash
来源：http://dali.0kj1m.cn/Article/details/gt2ymhtuoky.html

set -euo pipefail
来源：http://dali.pengpengdd.cyou/Article/details/gt2cpbgxugd.html

[R02] 变量赋值与使用
来源：http://dali.nanxinkj.top/Article/details/gt2vbfbxgii.html

name="Tom"; echo "$name"
来源：http://dali.pycfn.com/Article/details/gt2kxrfvkiw.html

[R03] 只读变量
来源：http://dali.hywenlv.cn/Article/details/gt2awcclpwg.html

readonly PI=3.14
来源：http://dali.chenjidiqi.icu/Article/details/gt2auzywdig.html

[R04] 位置参数
来源：http://dali.hnqzz.top/Article/details/gt2qchlmhfo.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.xuanzx.com/Article/details/gt2izelaleg.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2yelodfhv.html

name="${1:-default}"
来源：http://dali.yuanzhike.top/Article/details/gt2twupusfv.html

[R06] 判断命令是否存在
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hshygeex.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhixingplan.top/Article/details/gt2lyvziaho.html

[R07] if 判断文件
来源：http://dali.pycfn.com/Article/details/gt2zmrwymiu.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hammf.cn/Article/details/gt2chbzyimc.html

[R08] 数值比较
来源：http://dali.nwbrower.top/Article/details/gt2ejttqgmj.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.gogol.net.cn/Article/details/gt2jyjyqqvv.html

[R09] 字符串比较
来源：http://dali.bjfxy.top/Article/details/gt2scvexheo.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.guannengcc.top/Article/details/gt2pcfwmuji.html

[R10] 正则匹配
来源：http://dali.meibo888.top/Article/details/gt2madeskjq.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.iojbl.cn/Article/details/gt2hxikoxnj.html

[R11] case 多分支
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jkinxwbv.html

case "$1" in
来源：http://dali.shzxlz.cn/Article/details/gt2raxvrmpr.html

start) echo "启动" ;;
来源：http://dali.ppjwa.cn/Article/details/gt2bocklcli.html

stop)  echo "停止" ;;
来源：http://dali.nwbrower.top/Article/details/gt2iwzxbdzu.html

*)     echo "未知命令" ;;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2krfvmmgm.html

esac
来源：http://dali.xuanzx.com/Article/details/gt2kgggixme.html

[R12] for 遍历文件
来源：http://dali.tianlin.xyz/Article/details/gt2ubamwfyq.html

for f in *.txt; do echo "$f"; done
来源：http://dali.dianchejie.cn/Article/details/gt2puexlhln.html

[R13] for 计数循环
来源：http://dali.birdmap.top/Article/details/gt2quuufcpq.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.guannengcc.top/Article/details/gt2phvycrcl.html

[R14] C 风格 for
来源：http://dali.jqgfzy.top/Article/details/gt2kkcbxbky.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.aibaodan.cn/Article/details/gt2ierwavdj.html

[R15] while 逐行读文件
来源：http://dali.yuxming.cn/Article/details/gt2xblcbmkd.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.ydzc1.top/Article/details/gt2gqtdumqx.html

[R16] until 等待条件
来源：http://dali.jinqigfzy.top/Article/details/gt2gbwqregu.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.ehwqpu.com/Article/details/gt2ndhulthw.html

[R17] 数组定义与取值
来源：http://dali.cheryme.top/Article/details/gt2vlmfeiqq.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.guannengcc.top/Article/details/gt2njujrhmr.html

[R18] 遍历数组
来源：http://dali.jlsjyb.cn/Article/details/gt2coujjvdj.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.0kj1m.cn/Article/details/gt2nndszxgk.html

[R19] 数组长度
来源：http://dali.daxiang520.top/Article/details/gt2iagfswdu.html

echo "${#arr[@]}"
来源：http://dali.yuanzhike.top/Article/details/gt2qhplymle.html

[R20] 关联数组（字典）
来源：http://dali.hywenlv.cn/Article/details/gt2fdbgaagf.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.nwbrower.top/Article/details/gt2jrzapmyh.html

[R21] 字符串长度
来源：http://dali.xziqi.cn/Article/details/gt2ncdmaxhz.html

echo "${#s}"
来源：http://dali.birdmap.top/Article/details/gt2mfodvvnc.html

[R22] 截取子串
来源：http://dali.zycfv.cn/Article/details/gt2zycdoyan.html

echo "${s:0:5}"
来源：http://dali.hysaishi.cn/Article/details/gt2lzcuhqmr.html

[R23] 字符串替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xyccunad.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.dashuyun.cn/Article/details/gt2jutkzdbn.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qhfpwjet.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hnqzz.top/Article/details/gt2mzajmoin.html

[R25] 去后缀 / 去前缀
来源：http://dali.tian-w.cn/Article/details/gt2ihldodqo.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.guowangkeji.top/Article/details/gt2chteybyq.html

[R26] 命令替换
来源：http://dali.cashguo.top/Article/details/gt2fytwegcn.html

now=$(date +%F); echo "$now"
来源：http://dali.gotoacloud.top/Article/details/gt2cltprrbc.html

[R27] 算术展开
来源：http://dali.nanxinkj.top/Article/details/gt2wqhatrog.html

echo $((1 + 2 * 3))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fkyydehx.html

[R28] 浮点运算
来源：http://dali.hywenlv.cn/Article/details/gt2mxhbjkdc.html

echo "scale=2; 10/3" | bc
来源：http://dali.birdmap.top/Article/details/gt2rvqouqmh.html

[R29] 定义函数
来源：http://dali.jinqigfzy.top/Article/details/gt2ggnfxltr.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yongpay.top/Article/details/gt2kibkrmdn.html

[R30] 函数返回状态码
来源：http://dali.quarkkingdee.top/Article/details/gt2hqceizdg.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.hysaishi.cn/Article/details/gt2apmcgvwj.html

[R31] 局部变量
来源：http://dali.c1oappe.top/Article/details/gt2uvebquxb.html

f() { local x=1; echo "$x"; }
来源：http://dali.sysykeji.top/Article/details/gt2uindiuph.html

[R32] 参数个数校验
来源：http://dali.yj202588.top/Article/details/gt2kdpwuiou.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ywodppkv.html

[R33] 捕获错误并提示行号
来源：http://dali.dianchejie.cn/Article/details/gt2dwwnpfzu.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2adhnllbq.html

[R34] 退出时清理
来源：http://dali.chenjidiqi.icu/Article/details/gt2yqaewqxr.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yanxiufei.cn/Article/details/gt2ggxiphaf.html

[R35] 后台执行并等待
来源：http://dali.haohaochexian.top/Article/details/gt2ixcnmixx.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.xziqi.cn/Article/details/gt2dkditngj.html

[R36] 并发执行多个任务
来源：http://dali.sweek.top/Article/details/gt2bkkbmfdl.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.pycfn.com/Article/details/gt2sujrhlhq.html

[R37] 把输出赋给变量
来源：http://dali.xinyue.icu/Article/details/gt2xizfkbmy.html

files=$(ls -1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qkdsdevq.html

[R38] 管道串联
来源：http://dali.ivvv.top/Article/details/gt2qigfeems.html

cat a.txt | grep -i error | wc -l
来源：http://dali.shzxlz.cn/Article/details/gt2nxjlcrva.html

[R39] 重定向标准输出与错误
来源：http://dali.hammf.cn/Article/details/gt2ucplazcy.html

cmd > out.log 2>&1
来源：http://dali.yonumen.top/Article/details/gt2ovtautus.html

[R40] 追加写日志
来源：http://dali.jinqigfzy.top/Article/details/gt2vofulgal.html

echo "log" >> out.log
来源：http://dali.quarkkingdee.top/Article/details/gt2chuoeumy.html

[R41] 丢弃输出
来源：http://dali.kuanghao11.cn/Article/details/gt2qobmdhqn.html

cmd >/dev/null 2>&1
来源：http://dali.ybcxt.top/Article/details/gt2xzmctoak.html

[R42] 输入重定向
来源：http://dali.9152youxi.cn/Article/details/gt2uorthorx.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ctsbtrwl.html

[R43] 按名字查找文件
来源：http://dali.yueranfly.top/Article/details/gt2syoynmrm.html

find . -name "*.log" -type f
来源：http://dali.shuidangran.top/Article/details/gt2quxgpays.html

[R44] 按修改时间查找
来源：http://dali.ppjwa.cn/Article/details/gt2kosulnxa.html

find . -mtime -7 -type f
来源：http://dali.zhixingplan.top/Article/details/gt2ukjaatwh.html

[R45] 批量删除
来源：http://dali.svipenyu.cn/Article/details/gt2iqqaojjj.html

find . -name "*.tmp" -delete
来源：http://dali.yvedp.cn/Article/details/gt2xabvsyjb.html

[R46] 递归替换文件内容
来源：http://dali.gzhubu.top/Article/details/gt2qnxgvbwq.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yj20258888.top/Article/details/gt2vjgcxzdt.html

[R47] sed 单行替换
来源：http://dali.yongpay.top/Article/details/gt2hxyfusbk.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.xuanzx.com/Article/details/gt2oluwxanq.html

[R48] awk 取指定列
来源：http://dali.guannengcc.top/Article/details/gt2euhuafnh.html

awk '{print $1, $3}' a.txt
来源：http://dali.aibaodan.cn/Article/details/gt2ogxkbkdf.html

[R49] awk 带条件
来源：http://dali.tanke756.top/Article/details/gt2lcrkdxgr.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.redwolf501.top/Article/details/gt2twipmxen.html

[R50] awk 求和
来源：http://dali.yj20258.top/Article/details/gt2kknbslkf.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.shzxlz.cn/Article/details/gt2kiyjnexn.html

[R51] 排序去重取前几
来源：http://dali.sufxvd.cn/Article/details/gt2uicroxlv.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yanxiufei.cn/Article/details/gt2xszmpgyg.html

[R52] 统计行数
来源：http://dali.jinqigfzy.top/Article/details/gt2ayekcpau.html

wc -l a.txt
来源：http://dali.birdmap.top/Article/details/gt2hzbypoxd.html

[R53] 查看文件头与实时尾
来源：http://dali.jqgufenzy.top/Article/details/gt2fxiitfie.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.ybcxt.top/Article/details/gt2rlflathg.html

[R54] 比较两个文件
来源：http://dali.ydzc1.top/Article/details/gt2ffrbcpjq.html

diff a.txt b.txt
来源：http://dali.dashuyun.cn/Article/details/gt2frzaniiy.html

[R55] 压缩与解压
来源：http://dali.smart0.xyz/Article/details/gt2kpoebcub.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.guowangkeji.top/Article/details/gt2ectootwc.html

[R56] 远程拷贝
来源：http://dali.kuanghao11.cn/Article/details/gt2pysrlrui.html

scp file user@host:/path/
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yfjrfvjk.html

[R57] 远程执行命令
来源：http://dali.xziqi.cn/Article/details/gt2vtsmsycr.html

ssh user@host 'uptime'
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fmsbvgki.html

[R58] 下载文件
来源：http://dali.xziqi.cn/Article/details/gt2dkmjgeoi.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yueranfly.top/Article/details/gt2pshntdwz.html

[R59] 发 POST JSON
来源：http://dali.andypj.xyz/Article/details/gt2yylozsdk.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.kuanghao11.cn/Article/details/gt2ybfdsjoe.html

[R60] 只看 HTTP 状态码
来源：http://dali.tianlin.xyz/Article/details/gt2vcojhmmk.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.havefunace.top/Article/details/gt2oscsdhms.html

[R61] 磁盘占用
来源：http://dali.xziqi.cn/Article/details/gt2cnbdhhsk.html

df -h;  du -sh *
来源：http://dali.xinyue.icu/Article/details/gt2ziugfcci.html

[R62] 找最占空间的文件
来源：http://dali.yuxming.cn/Article/details/gt2fclhvzwr.html

du -ah . | sort -rh | head -10
来源：http://dali.guannengcc.top/Article/details/gt2undibuzs.html

[R63] 内存与进程
来源：http://dali.guowangkeji.top/Article/details/gt2nmbijfgp.html

free -h;  ps aux | grep nginx
来源：http://dali.jiagoushi.top/Article/details/gt2cvzondid.html

[R64] 结束进程
来源：http://dali.yangfankeji.com/Article/details/gt2ozxbxqih.html

kill -9 $(pgrep -f app.py)
来源：http://dali.chenjidiqi.icu/Article/details/gt2gwoyhvam.html

[R65] 查看端口占用
来源：http://dali.sweek.top/Article/details/gt2sidhskzp.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.ydzc1.top/Article/details/gt2hcwvicuu.html

[R66] 定时任务
来源：http://dali.9152youxi.cn/Article/details/gt2ojsqryon.html

crontab -e;  crontab -l
来源：http://dali.quarkkingdee.top/Article/details/gt2njxroqmn.html

[R67] 生成随机十六进制串
来源：http://dali.cqqwz.cn/Article/details/gt2mavxhrcp.html

openssl rand -hex 16
来源：http://dali.gaohongyu789.top/Article/details/gt2dedjbcrh.html

[R68] 计算文件校验值
来源：http://dali.jinqigufen.top/Article/details/gt2hotrnwmc.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.shangyingyoupin.top/Article/details/gt2abzqikgp.html

[R69] 生成随机密码
来源：http://dali.daxiang520.top/Article/details/gt2jputmvtz.html

head -c 16 /dev/urandom | base64
来源：http://dali.hammf.cn/Article/details/gt2qzzgowck.html

[R70] 时间戳与互转
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ewnhudln.html

date +%s;  date -d @1700000000
来源：http://dali.yanxiufei.cn/Article/details/gt2bcgjjubr.html

[R71] 日期格式化
来源：http://dali.iojbl.cn/Article/details/gt2npntoabs.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.wangshuangyany.cn/Article/details/gt2blmxtlff.html

[R72] 等待端口就绪
来源：http://dali.fzhhl.top/Article/details/gt2bvaqgkjt.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.andypj.xyz/Article/details/gt2mnuupyxk.html

[R73] 分割大日志
来源：http://dali.feifeiyinyue.top/Article/details/gt2ulakgqzs.html

split -l 1000 big.log part_
来源：http://dali.gaohongyu789.top/Article/details/gt2wnmvhwsc.html

[R74] 批量重命名
来源：http://dali.zhiwuduotai.top/Article/details/gt2hcoktrto.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.pengpengdd.cyou/Article/details/gt2ubwtavep.html

[R75] 导出环境变量
来源：http://dali.cheryme.top/Article/details/gt2vndpucxi.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.feifeiyinyue.top/Article/details/gt2atlmzmia.html

[R76] 使用临时文件
来源：http://dali.9152youxi.cn/Article/details/gt2otwazxtb.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.nanxuanxn.top/Article/details/gt2lcjojiou.html

[R77] 读取用户输入
来源：http://dali.nanxinkj.top/Article/details/gt2pmccrofl.html

read -rp "请输入: " ans
来源：http://dali.yj202588.top/Article/details/gt2gnmsjjrn.html

[R78] 交互式菜单
来源：http://dali.bjfxy.top/Article/details/gt2amnojzfj.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.aibaodan.cn/Article/details/gt2docfmsjx.html

[R79] 解析命令行选项
来源：http://dali.jinqigfzy.top/Article/details/gt2aycorirj.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ybcxt.top/Article/details/gt2zkhfbxwd.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2vtvwzrrb.html

time ./run.sh
来源：http://dali.ivvv.top/Article/details/gt2szdhjmir.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2jowdftcp.html

S. C / C++ 专题
来源：http://dali.mhx1999.top/Article/details/gt2ytseiyza.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2wtitcspg.html

[S01] C：Hello World
来源：http://dali.zhongyouzk.top/Article/details/gt2ozeccayo.html

#include <stdio.h>
来源：http://dali.nwbrower.top/Article/details/gt2mnbcnafi.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jyoumei.cn/Article/details/gt2iqtbbxnd.html

[S02] C：变量与格式化输出
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uyroymvg.html

int a = 10; printf("%d\n", a);
来源：http://dali.guannengcc.top/Article/details/gt2llmgmojy.html

[S03] C：读入整数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pjhkbxdi.html

int x; scanf("%d", &x);
来源：http://dali.haohaochexian.top/Article/details/gt2gphniuqb.html

[S04] C：字符串复制
来源：http://dali.jianghu66.top/Article/details/gt2rtuugpgz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.chenzaomai.com/Article/details/gt2kgtdawcf.html

[S05] C：字符串长度
来源：http://dali.snrcjt.cn/Article/details/gt2srgowubc.html

strlen(s)
来源：http://dali.cdnleiting.top/Article/details/gt2kqsjviad.html

[S06] C：字符串比较
来源：http://dali.havefunace.top/Article/details/gt2xuzcrfwo.html

strcmp(a, b) == 0
来源：http://dali.wangshuangyany.cn/Article/details/gt2napbngcq.html

[S07] C：数组遍历求和
来源：http://dali.jinqigufen.top/Article/details/gt2lxhhcpzm.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.snrcjt.cn/Article/details/gt2zbemgciq.html

[S08] C：动态内存分配与释放
来源：http://dali.yueranfly.top/Article/details/gt2vomcvoka.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yuanzhike.top/Article/details/gt2dplbstux.html

[S09] C：结构体定义与初始化
来源：http://dali.chenlongwang.top/Article/details/gt2ifommjcn.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xinyue.icu/Article/details/gt2pqcpajyc.html

[S10] C：指针与解引用
来源：http://dali.haohaochexian.top/Article/details/gt2ygrjmqcq.html

int *p = &a;  *p = 5;
来源：http://dali.hywenlv.cn/Article/details/gt2yzxmvjny.html

[S11] C：逐行读文件
来源：http://dali.zycfv.cn/Article/details/gt2ppusrgfm.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jiagoushi.top/Article/details/gt2clghslrj.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.vqdsnc.cn/Article/details/gt2ryqchkae.html

fclose(f);
来源：http://dali.zhiwuduotai.top/Article/details/gt2hznizffr.html

[S12] C：写文件
来源：http://dali.kuanghao11.cn/Article/details/gt2ufrfeflp.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.xuanzx.com/Article/details/gt2ozfqtjjw.html

[S13] C：宏定义
来源：http://dali.nanxinkj.top/Article/details/gt2hwmlzjiu.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.havefunace.top/Article/details/gt2syzqgkzy.html

[S14] C：枚举
来源：http://dali.smart0.xyz/Article/details/gt2rexunlia.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zycfv.cn/Article/details/gt2sfjijiyy.html

[S15] C：类型转换
来源：http://dali.jyoumei.cn/Article/details/gt2mnavydgv.html

(double) a / b
来源：http://dali.hnxiangtu.top/Article/details/gt2sazcykpm.html

[S16] C：位操作置位
来源：http://dali.shanyushiyangtech.top/Article/details/gt2prklvvfy.html

x |= (1 << 3);
来源：http://dali.yonumen.top/Article/details/gt2qejgeovd.html

[S17] C：安全拼接字符串
来源：http://dali.birdmap.top/Article/details/gt2ijrtwrfa.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.guowangkeji.top/Article/details/gt2hrbxpdzt.html

[S18] C：命令行参数
来源：http://dali.feifeiyinyue.top/Article/details/gt2ugughtvh.html

int main(int argc, char **argv)
来源：http://dali.zhiwuduotai.top/Article/details/gt2tqciqthr.html

[S19] C：快速排序
来源：http://dali.hysaishi.cn/Article/details/gt2zeztebby.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jlsjyb.cn/Article/details/gt2jekxvtwf.html

[S20] C：二分查找
来源：http://dali.snrcjt.cn/Article/details/gt2fmkvqckg.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jianghu66.top/Article/details/gt2ulrmnsgj.html

[S21] C：字符类别判断
来源：http://dali.chenjidiqi.icu/Article/details/gt2ikvsvjbb.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.wangdashe.top/Article/details/gt2tufheieg.html

[S22] C：字符串转数字
来源：http://dali.bjfxy.top/Article/details/gt2dufuuuzg.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.tianlin.xyz/Article/details/gt2gxhbpdls.html

[S23] C：随机数
来源：http://dali.zhixingplan.top/Article/details/gt2ysepnzoi.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yonumen.top/Article/details/gt2snfvwyrp.html

[S24] C：获取本地时间
来源：http://dali.fengsongda.top/Article/details/gt2fmxrihkx.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.iojbl.cn/Article/details/gt2adswqecz.html

[S25] C：内存拷贝
来源：http://dali.ppjwa.cn/Article/details/gt2fotoemcj.html

memcpy(dst, src, n);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2deqshqkc.html

[S26] C：内存清零
来源：http://dali.zdqjudy.top/Article/details/gt2qwsopbvx.html

memset(a, 0, sizeof a);
来源：http://dali.sufxvd.cn/Article/details/gt2nnbnhhth.html

[S27] C：定义常量
来源：http://dali.ehwqpu.com/Article/details/gt2exvxsqsh.html

const double PI = 3.14159;
来源：http://dali.feifeiyinyue.top/Article/details/gt2ilqsolit.html

[S28] C：静态变量
来源：http://dali.chenzaomai.com/Article/details/gt2qvydwxkj.html

static int counter = 0;
来源：http://dali.zhixingplan.top/Article/details/gt2skzdpvrh.html

[S29] C：变参函数
来源：http://dali.pengpengdd.cyou/Article/details/gt2hitytkhl.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.tanke756.top/Article/details/gt2qyvceffn.html

[S30] C：头文件保护
来源：http://dali.iojbl.cn/Article/details/gt2jekymdyx.html

#ifndef X_H
来源：http://dali.daxiang520.top/Article/details/gt2cnwcksoj.html

#define X_H
来源：http://dali.wangshuangyany.cn/Article/details/gt2kkbzilgq.html

#endif
来源：http://dali.tian-w.cn/Article/details/gt2cssmltic.html

[S31] C++：Hello World
来源：http://dali.zhixingplan.top/Article/details/gt2zuptikjl.html

#include <iostream>
来源：http://dali.hnqzz.top/Article/details/gt2xzxlhjyt.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.andypj.xyz/Article/details/gt2qruvwkhc.html

[S32] C++：字符串
来源：http://dali.cheryme.top/Article/details/gt2ocrgmwsr.html

std::string s = "hi";  s += "!";
来源：http://dali.xuetiantiany.cn/Article/details/gt2opedpmnp.html

[S33] C++：vector 增删
来源：http://dali.hysaishi.cn/Article/details/gt2ciluxicq.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhoulong.xyz/Article/details/gt2ylibnpjl.html

[S34] C++：遍历 vector
来源：http://dali.guowangkeji.top/Article/details/gt2fquhcktq.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2tpblapvh.html

[S35] C++：map
来源：http://dali.jqgfzy.top/Article/details/gt2biybqabp.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hongshengwenyu.top/Article/details/gt2vjajfpwy.html

[S36] C++：unordered_map
来源：http://dali.xylfe.cn/Article/details/gt2ozlxabpo.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2iuhqoqcw.html

[S37] C++：set
来源：http://dali.yonumen.top/Article/details/gt2nkuhkkso.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.fzhhl.top/Article/details/gt2jsvhdvew.html

[S38] C++：排序
来源：http://dali.sufxvd.cn/Article/details/gt2zktuarnb.html

std::sort(v.begin(), v.end());
来源：http://dali.gotoacloud.top/Article/details/gt2zxcrrdqj.html

[S39] C++：自定义比较器排序
来源：http://dali.svipenyu.cn/Article/details/gt2hscfcdcf.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zkewuyxq.html

[S40] C++：查找元素
来源：http://dali.daria6918.cn/Article/details/gt2hzsjfdvc.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yongpay.top/Article/details/gt2vrrsddjo.html

[S41] C++：类与构造函数
来源：http://dali.feifeiyinyue.top/Article/details/gt2qpydlaoa.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.nanxuanxn.top/Article/details/gt2vyqswbzb.html

[S42] C++：继承与虚函数
来源：http://dali.guowangkeji.top/Article/details/gt2eruwgfge.html

class B : public Base { public: void f() override {} };
来源：http://dali.cqqwz.cn/Article/details/gt2txwixnxx.html

[S43] C++：智能指针
来源：http://dali.ivvv.top/Article/details/gt2cibmxqkw.html

auto p = std::make_unique<int>(5);
来源：http://dali.cashguo.top/Article/details/gt2esnldkda.html

[S44] C++：引用传参
来源：http://dali.yueranfly.top/Article/details/gt2ukvswsaq.html

void inc(int &x) { ++x; }
来源：http://dali.xuanzx.com/Article/details/gt2kupetsnz.html

[S45] C++：lambda
来源：http://dali.yonumen.top/Article/details/gt2jgitvzpr.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sljolvbf.html

[S46] C++：函数模板
来源：http://dali.mhx1999.top/Article/details/gt2bsxrktly.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.hysaishi.cn/Article/details/gt2ijktbccw.html

[S47] C++：结构化绑定遍历
来源：http://dali.zycfv.cn/Article/details/gt2pknmuotq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.aibaodan.cn/Article/details/gt2wdkxescn.html

[S48] C++：逐行读文件
来源：http://dali.jqgfzy.top/Article/details/gt2zkaopvin.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tbvkzuwh.html

while (std::getline(in, line)) { }
来源：http://dali.vqdsnc.cn/Article/details/gt2gzhmwijv.html

[S49] C++：写文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hzjerhhv.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.xziqi.cn/Article/details/gt2txklwngh.html

[S50] C++：格式化数字
来源：http://dali.jinqigfzy.top/Article/details/gt2texmwjbv.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.feifeiyinyue.top/Article/details/gt2ematorcc.html

[S51] C++：显式类型转换
来源：http://dali.shuidangran.top/Article/details/gt2ywibhurm.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ygohxgny.html

[S52] C++：const 与 noexcept
来源：http://dali.xylfe.cn/Article/details/gt2eyrjqszg.html


<!-- 参考信息 -->