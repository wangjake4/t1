代发 wailian999

[Q82] 字符长度与字节长度
来源：http://dali.sufxvd.cn/Article/details/gt2sevuvynk.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.redwolf501.top/Article/details/gt2jzidlwrr.html

[Q83] 大小写转换
来源：http://dali.pycfn.com/Article/details/gt2vnfuhyuw.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.wangdashe.top/Article/details/gt2moaeldcj.html

[Q84] 去除首尾空格
来源：http://dali.xziqi.cn/Article/details/gt2rtqbnsmn.html

SELECT TRIM(name) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gt2axsujsbx.html

[Q85] 数值取整
来源：http://dali.jiagoushi.top/Article/details/gt2lzupuxvm.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jinqigfzy.top/Article/details/gt2pouqeira.html

[Q86] 读取 JSON 字段
来源：http://dali.sufxvd.cn/Article/details/gt2kidanzgs.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.andypj.xyz/Article/details/gt2jqxdhfpk.html

[Q87] JSON 字段做条件
来源：http://dali.redwolf501.top/Article/details/gt2iynccisd.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.haohaochexian.top/Article/details/gt2nxtremxg.html

[Q88] 行转列（条件聚合）
来源：http://dali.nwbrower.top/Article/details/gt2oolleded.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.sysykeji.top/Article/details/gt2zgmfyuxb.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.sxryk.cn/Article/details/gt2xuypgype.html

[Q89] 判断表是否存在
来源：http://dali.nanxuanxn.top/Article/details/gt2gfycidjd.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jqgufenzy.top/Article/details/gt2dxhjhepb.html

[Q90] 生成序号列
来源：http://dali.andypj.xyz/Article/details/gt2qkzcpfci.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.nanxuanxn.top/Article/details/gt2tlcjuftw.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2qnisgrae.html

R. Bash 专题
来源：http://dali.shzxlz.cn/Article/details/gt2iuocebnd.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2uuessxee.html

[R01] shebang 与严格模式
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qlfxvujc.html

#!/usr/bin/env bash
来源：http://dali.shangyingyoupin.top/Article/details/gt2jgmpvcfn.html

set -euo pipefail
来源：http://dali.tian-w.cn/Article/details/gt2lbnnyzkl.html

[R02] 变量赋值与使用
来源：http://dali.chenlongwang.top/Article/details/gt2xxzavyml.html

name="Tom"; echo "$name"
来源：http://dali.dashuyun.cn/Article/details/gt2qsgzfufq.html

[R03] 只读变量
来源：http://dali.daria6918.cn/Article/details/gt2qttpjrip.html

readonly PI=3.14
来源：http://dali.iojbl.cn/Article/details/gt2mlaxyecj.html

[R04] 位置参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tmmvvtmp.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.ivvv.top/Article/details/gt2hzhfpuzv.html

[R05] 参数默认值
来源：http://dali.snrcjt.cn/Article/details/gt2luwuormm.html

name="${1:-default}"
来源：http://dali.ydzc1.top/Article/details/gt2krxypavm.html

[R06] 判断命令是否存在
来源：http://dali.wangdashe.top/Article/details/gt2unvpjfpa.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.guannengcc.top/Article/details/gt2ekxnngei.html

[R07] if 判断文件
来源：http://dali.hammf.cn/Article/details/gt2huzeasem.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.tanke756.top/Article/details/gt2bexfpgaz.html

[R08] 数值比较
来源：http://dali.9152youxi.cn/Article/details/gt2gmltjyev.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xkugnwsd.html

[R09] 字符串比较
来源：http://dali.zycfv.cn/Article/details/gt2eczbbcbz.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.redwolf501.top/Article/details/gt2sqxlwghd.html

[R10] 正则匹配
来源：http://dali.yj20258888.top/Article/details/gt2wpozomzd.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.tianlin.xyz/Article/details/gt2dhszpssl.html

[R11] case 多分支
来源：http://dali.redwolf501.top/Article/details/gt2vkslgywd.html

case "$1" in
来源：http://dali.wangdashe.top/Article/details/gt2ymckiaes.html

start) echo "启动" ;;
来源：http://dali.jianghu66.top/Article/details/gt2dptzaoco.html

stop)  echo "停止" ;;
来源：http://dali.hongshengwenyu.top/Article/details/gt2olhdupws.html

*)     echo "未知命令" ;;
来源：http://dali.cashguo.top/Article/details/gt2zxowmtdo.html

esac
来源：http://dali.jinqigufen.top/Article/details/gt2gktrhlwf.html

[R12] for 遍历文件
来源：http://dali.svipenyu.cn/Article/details/gt2lruamtgl.html

for f in *.txt; do echo "$f"; done
来源：http://dali.xuanzx.com/Article/details/gt2mkrgfvms.html

[R13] for 计数循环
来源：http://dali.jyoumei.cn/Article/details/gt2nmadbpwq.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.cdnleiting.top/Article/details/gt2msdjkbdj.html

[R14] C 风格 for
来源：http://dali.hysaishi.cn/Article/details/gt2nxxmfoeh.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.guowangkeji.top/Article/details/gt2fhobsodg.html

[R15] while 逐行读文件
来源：http://dali.svipenyu.cn/Article/details/gt2svrwckpc.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.smart0.xyz/Article/details/gt2zftxhttw.html

[R16] until 等待条件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tvgtswqm.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jinqigufen.top/Article/details/gt2ypthgude.html

[R17] 数组定义与取值
来源：http://dali.kuanghao11.cn/Article/details/gt2dlrffdrw.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.xinyue.icu/Article/details/gt2wcovhisg.html

[R18] 遍历数组
来源：http://dali.zhoulong.xyz/Article/details/gt2fxzuvgbl.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.xziqi.cn/Article/details/gt2mxikyiaq.html

[R19] 数组长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2itoarvya.html

echo "${#arr[@]}"
来源：http://dali.jianghu66.top/Article/details/gt2hkvasoun.html

[R20] 关联数组（字典）
来源：http://dali.jinqigufen.top/Article/details/gt2hbyjzrmg.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.hysaishi.cn/Article/details/gt2lyegohpw.html

[R21] 字符串长度
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2czraydtk.html

echo "${#s}"
来源：http://dali.jinqigufen.top/Article/details/gt2zlckault.html

[R22] 截取子串
来源：http://dali.sysykeji.top/Article/details/gt2dxrgfhyl.html

echo "${s:0:5}"
来源：http://dali.yueranfly.top/Article/details/gt2ldeqqlni.html

[R23] 字符串替换
来源：http://dali.shzxlz.cn/Article/details/gt2nbwybwti.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.dashuyun.cn/Article/details/gt2aqiwokzr.html

[R24] 大小写转换
来源：http://dali.hysaishi.cn/Article/details/gt2jfgtgahl.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jlsjyb.cn/Article/details/gt2ysegtirh.html

[R25] 去后缀 / 去前缀
来源：http://dali.wangdashe.top/Article/details/gt2gpmuhiti.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.xuetiantiany.cn/Article/details/gt2fcnggges.html

[R26] 命令替换
来源：http://dali.zycfv.cn/Article/details/gt2dzxjguxm.html

now=$(date +%F); echo "$now"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ncztdexh.html

[R27] 算术展开
来源：http://dali.cheryme.top/Article/details/gt2qsjlumaa.html

echo $((1 + 2 * 3))
来源：http://dali.vqdsnc.cn/Article/details/gt2klnzrvxw.html

[R28] 浮点运算
来源：http://dali.jyoumei.cn/Article/details/gt2ialotvxp.html

echo "scale=2; 10/3" | bc
来源：http://dali.svipenyu.cn/Article/details/gt2qontqhqj.html

[R29] 定义函数
来源：http://dali.bjfxy.top/Article/details/gt2grkeafcs.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.gotoacloud.top/Article/details/gt2tyvplmty.html

[R30] 函数返回状态码
来源：http://dali.xinyue.icu/Article/details/gt2ewwwdxzc.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.havefunace.top/Article/details/gt2eclhbyia.html

[R31] 局部变量
来源：http://dali.pengpengdd.cyou/Article/details/gt2wfznvaiq.html

f() { local x=1; echo "$x"; }
来源：http://dali.tianlin.xyz/Article/details/gt2qkmjqvez.html

[R32] 参数个数校验
来源：http://dali.ybcxt.top/Article/details/gt2xhqxhhga.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.gaohongyu789.top/Article/details/gt2mzitiicx.html

[R33] 捕获错误并提示行号
来源：http://dali.birdmap.top/Article/details/gt2bnralbgg.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ppsuamlo.html

[R34] 退出时清理
来源：http://dali.jinqigufen.top/Article/details/gt2urmkplkr.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.nwbrower.top/Article/details/gt2iupwrlnw.html

[R35] 后台执行并等待
来源：http://dali.daria6918.cn/Article/details/gt2gyrnxbon.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yonumen.top/Article/details/gt2dbxgfofl.html

[R36] 并发执行多个任务
来源：http://dali.jinqigfzy.top/Article/details/gt2wzkrtxth.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yueranfly.top/Article/details/gt2ltlpohke.html

[R37] 把输出赋给变量
来源：http://dali.cucudq.cn/Article/details/gt2smgaaqmn.html

files=$(ls -1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2oumpkewb.html

[R38] 管道串联
来源：http://dali.shangyingyoupin.top/Article/details/gt2slmwhtwg.html

cat a.txt | grep -i error | wc -l
来源：http://dali.wangdashe.top/Article/details/gt2warbuakv.html

[R39] 重定向标准输出与错误
来源：http://dali.sufxvd.cn/Article/details/gt2lzxyvpax.html

cmd > out.log 2>&1
来源：http://dali.yvedp.cn/Article/details/gt2hqqzhnmc.html

[R40] 追加写日志
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qaictcxa.html

echo "log" >> out.log
来源：http://dali.zhengqikj.top/Article/details/gt2fcsjtzcb.html

[R41] 丢弃输出
来源：http://dali.hongshengwenyu.top/Article/details/gt2yhubyygb.html

cmd >/dev/null 2>&1
来源：http://dali.hnxiangtu.top/Article/details/gt2jyhechoe.html

[R42] 输入重定向
来源：http://dali.tian-w.cn/Article/details/gt2lgkzbfju.html

wc -l < a.txt
来源：http://dali.ehwqpu.com/Article/details/gt2mwhxqjiz.html

[R43] 按名字查找文件
来源：http://dali.ybcxt.top/Article/details/gt2ixupiywd.html

find . -name "*.log" -type f
来源：http://dali.yongpay.top/Article/details/gt2zdgzbism.html

[R44] 按修改时间查找
来源：http://dali.ybcxt.top/Article/details/gt2dfzzjoga.html

find . -mtime -7 -type f
来源：http://dali.xuetiantiany.cn/Article/details/gt2uwzzjjpx.html

[R45] 批量删除
来源：http://dali.havefunace.top/Article/details/gt2oqstbwyq.html

find . -name "*.tmp" -delete
来源：http://dali.zhixingplan.top/Article/details/gt2wvzxwicq.html

[R46] 递归替换文件内容
来源：http://dali.ppjwa.cn/Article/details/gt2xrupipcb.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.feifeiyinyue.top/Article/details/gt2zxczgslc.html

[R47] sed 单行替换
来源：http://dali.zhiwuduotai.top/Article/details/gt2fqcixjhy.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.iojbl.cn/Article/details/gt2gagvccbl.html

[R48] awk 取指定列
来源：http://dali.cucudq.cn/Article/details/gt2xrssprdi.html

awk '{print $1, $3}' a.txt
来源：http://dali.cheryme.top/Article/details/gt2kizjyvzt.html

[R49] awk 带条件
来源：http://dali.zhiwuduotai.top/Article/details/gt2eqqblrpm.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ywxiifsj.html

[R50] awk 求和
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pexvftmx.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.snrcjt.cn/Article/details/gt2iaxkxftz.html

[R51] 排序去重取前几
来源：http://dali.guannengcc.top/Article/details/gt2idmyfpcr.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.aibaodan.cn/Article/details/gt2vmavohph.html

[R52] 统计行数
来源：http://dali.hongshengwenyu.top/Article/details/gt2ooutzluo.html

wc -l a.txt
来源：http://dali.tanke756.top/Article/details/gt2gbdpmlmj.html

[R53] 查看文件头与实时尾
来源：http://dali.xziqi.cn/Article/details/gt2vzqkwbor.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.gotoacloud.top/Article/details/gt2udbgizas.html

[R54] 比较两个文件
来源：http://dali.hysaishi.cn/Article/details/gt2cwxvxmay.html

diff a.txt b.txt
来源：http://dali.nwbrower.top/Article/details/gt2cyubnozv.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2slpbgdjj.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.xuanzx.com/Article/details/gt2qdwjpelb.html

[R56] 远程拷贝
来源：http://dali.andypj.xyz/Article/details/gt2lrmplmuc.html

scp file user@host:/path/
来源：http://dali.yuanzhike.top/Article/details/gt2ojgyxggo.html

[R57] 远程执行命令
来源：http://dali.svipenyu.cn/Article/details/gt2xookscjg.html

ssh user@host 'uptime'
来源：http://dali.xinyue.icu/Article/details/gt2nwrlnvrx.html

[R58] 下载文件
来源：http://dali.sxryk.cn/Article/details/gt2vrmgxcvn.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhongyouzk.top/Article/details/gt2wkgtathr.html

[R59] 发 POST JSON
来源：http://dali.svipenyu.cn/Article/details/gt2taeittwu.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhengqikj.top/Article/details/gt2gfahtshe.html

[R60] 只看 HTTP 状态码
来源：http://dali.9152youxi.cn/Article/details/gt2oytwzuyw.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.cashguo.top/Article/details/gt2hidahkde.html

[R61] 磁盘占用
来源：http://dali.daxiang520.top/Article/details/gt2sddujskb.html

df -h;  du -sh *
来源：http://dali.daxiang520.top/Article/details/gt2dldfpbmj.html

[R62] 找最占空间的文件
来源：http://dali.daria6918.cn/Article/details/gt2rhwpmpxb.html

du -ah . | sort -rh | head -10
来源：http://dali.aizwys.cn/Article/details/gt2ytswszvx.html

[R63] 内存与进程
来源：http://dali.smart0.xyz/Article/details/gt2lnoflmac.html

free -h;  ps aux | grep nginx
来源：http://dali.cucudq.cn/Article/details/gt2ajpkxizu.html

[R64] 结束进程
来源：http://dali.jinqigfzy.top/Article/details/gt2mupurvuo.html

kill -9 $(pgrep -f app.py)
来源：http://dali.gogol.net.cn/Article/details/gt2yjxowvsu.html

[R65] 查看端口占用
来源：http://dali.ppjwa.cn/Article/details/gt2temtobpn.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yj20258.top/Article/details/gt2pbnprfgt.html

[R66] 定时任务
来源：http://dali.svipenyu.cn/Article/details/gt2fuxkehsb.html

crontab -e;  crontab -l
来源：http://dali.dianchejie.cn/Article/details/gt2evrjnupt.html

[R67] 生成随机十六进制串
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kylsdhwg.html

openssl rand -hex 16
来源：http://dali.bjfxy.top/Article/details/gt2kwwqfwzs.html

[R68] 计算文件校验值
来源：http://dali.ehwqpu.com/Article/details/gt2loeipdrb.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhengqikj.top/Article/details/gt2yftakdop.html

[R69] 生成随机密码
来源：http://dali.jianghu66.top/Article/details/gt2sreeobfv.html

head -c 16 /dev/urandom | base64
来源：http://dali.gzhubu.top/Article/details/gt2viioxqgx.html

[R70] 时间戳与互转
来源：http://dali.daria6918.cn/Article/details/gt2qzlfonty.html

date +%s;  date -d @1700000000
来源：http://dali.xuanzx.com/Article/details/gt2bvgfrkjv.html

[R71] 日期格式化
来源：http://dali.tanke756.top/Article/details/gt2czrfvqzm.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.meibo888.top/Article/details/gt2auplfpeo.html

[R72] 等待端口就绪
来源：http://dali.haohaochexian.top/Article/details/gt2ixxmctcd.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jyoumei.cn/Article/details/gt2frrlgmyo.html

[R73] 分割大日志
来源：http://dali.haohaochexian.top/Article/details/gt2qgaymaus.html

split -l 1000 big.log part_
来源：http://dali.hnxiangtu.top/Article/details/gt2qnfzccje.html

[R74] 批量重命名
来源：http://dali.pengpengdd.cyou/Article/details/gt2mtzsztme.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.ppjwa.cn/Article/details/gt2eftlkmtn.html

[R75] 导出环境变量
来源：http://dali.xylfe.cn/Article/details/gt2zodtmnkc.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.andypj.xyz/Article/details/gt2ukivslbl.html

[R76] 使用临时文件
来源：http://dali.xuanzx.com/Article/details/gt2dffbqvvp.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.feifeiyinyue.top/Article/details/gt2vapchymx.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2rhahfghk.html

read -rp "请输入: " ans
来源：http://dali.hongshengwenyu.top/Article/details/gt2vqgcaaxj.html

[R78] 交互式菜单
来源：http://dali.316326.xyz/Article/details/gt2nirpwvou.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jeydgypq.html

[R79] 解析命令行选项
来源：http://dali.feifeiyinyue.top/Article/details/gt2fvfsbknf.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhengqikj.top/Article/details/gt2ubxurifk.html

[R80] 查看脚本执行耗时
来源：http://dali.cqqwz.cn/Article/details/gt2cjzvvetu.html

time ./run.sh
来源：http://dali.yongpay.top/Article/details/gt2qecdrmmf.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2cfjcyzru.html

S. C / C++ 专题
来源：http://dali.svipenyu.cn/Article/details/gt2ewslgokq.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2fdhvqphb.html

[S01] C：Hello World
来源：http://dali.zhixingplan.top/Article/details/gt2fasothkm.html

#include <stdio.h>
来源：http://dali.ybcxt.top/Article/details/gt2ykldqlcx.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2rjevmlzs.html

[S02] C：变量与格式化输出
来源：http://dali.hywenlv.cn/Article/details/gt2yegclkan.html

int a = 10; printf("%d\n", a);
来源：http://dali.guannengcc.top/Article/details/gt2rtqibbju.html

[S03] C：读入整数
来源：http://dali.gotoacloud.top/Article/details/gt2lzruuyop.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2hiftwwtg.html

[S04] C：字符串复制
来源：http://dali.quarkkingdee.top/Article/details/gt2otnoqimj.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ptgvvsuo.html

[S05] C：字符串长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2drvbwvld.html

strlen(s)
来源：http://dali.haohaochexian.top/Article/details/gt2efhttpol.html

[S06] C：字符串比较
来源：http://dali.yongpay.top/Article/details/gt2cnjdqyjk.html

strcmp(a, b) == 0
来源：http://dali.bjfxy.top/Article/details/gt2porqoktk.html

[S07] C：数组遍历求和
来源：http://dali.daria6918.cn/Article/details/gt2duoulxnw.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.meibo888.top/Article/details/gt2tgmnuloq.html

[S08] C：动态内存分配与释放
来源：http://dali.nwbrower.top/Article/details/gt2zmtkiqsr.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.chenlongwang.top/Article/details/gt2rxaxnlfb.html

[S09] C：结构体定义与初始化
来源：http://dali.jqgfzy.top/Article/details/gt2kkdkdvsf.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jinghuilouyu.cn/Article/details/gt2seumxyby.html

[S10] C：指针与解引用
来源：http://dali.haohaochexian.top/Article/details/gt2laodwmok.html

int *p = &a;  *p = 5;
来源：http://dali.tian-w.cn/Article/details/gt2qowmbzfv.html

[S11] C：逐行读文件
来源：http://dali.sweek.top/Article/details/gt2wijdduxw.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hfpthk.cn/Article/details/gt2oapcfkzy.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.redwolf501.top/Article/details/gt2nqifrjoo.html

fclose(f);
来源：http://dali.havefunace.top/Article/details/gt2zqslkbgq.html

[S12] C：写文件
来源：http://dali.cqqwz.cn/Article/details/gt2xvelamcx.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.nanxuanxn.top/Article/details/gt2mssfjrxa.html

[S13] C：宏定义
来源：http://dali.yonumen.top/Article/details/gt2lfeczbwx.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.wangshuangyany.cn/Article/details/gt2scpuzpjb.html

[S14] C：枚举
来源：http://dali.smart0.xyz/Article/details/gt2bzwmzkca.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.aizwys.cn/Article/details/gt2hwaodjfp.html

[S15] C：类型转换
来源：http://dali.hongshengwenyu.top/Article/details/gt2oinsyqzh.html

(double) a / b
来源：http://dali.c1oappe.top/Article/details/gt2ltnevdhf.html

[S16] C：位操作置位
来源：http://dali.yanxiufei.cn/Article/details/gt2qcnnrcws.html

x |= (1 << 3);
来源：http://dali.yvedp.cn/Article/details/gt2rnfoaszh.html

[S17] C：安全拼接字符串
来源：http://dali.xylfe.cn/Article/details/gt2oagdoykw.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.daria6918.cn/Article/details/gt2oqtkrzmc.html

[S18] C：命令行参数
来源：http://dali.wangdashe.top/Article/details/gt2uevovdna.html

int main(int argc, char **argv)
来源：http://dali.pengpengdd.cyou/Article/details/gt2pjxnkruu.html

[S19] C：快速排序
来源：http://dali.shangyingyoupin.top/Article/details/gt2zeolmjej.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.gotoacloud.top/Article/details/gt2pmnhagmm.html

[S20] C：二分查找
来源：http://dali.jinqigfzy.top/Article/details/gt2azcghhrj.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhoulong.xyz/Article/details/gt2ihcjebop.html

[S21] C：字符类别判断
来源：http://dali.316326.xyz/Article/details/gt2nwfwhaab.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhoulong.xyz/Article/details/gt2zxkcdlee.html

[S22] C：字符串转数字
来源：http://dali.quarkkingdee.top/Article/details/gt2cbkvxfmh.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.wangdashe.top/Article/details/gt2tarobctt.html

[S23] C：随机数
来源：http://dali.yanxiufei.cn/Article/details/gt2ppwpjuok.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhongyouzk.top/Article/details/gt2favrtwhy.html

[S24] C：获取本地时间
来源：http://dali.zhengqikj.top/Article/details/gt2qdltyiwa.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zdqjudy.top/Article/details/gt2nwkrfkcl.html

[S25] C：内存拷贝
来源：http://dali.svipenyu.cn/Article/details/gt2dzqtepyb.html

memcpy(dst, src, n);
来源：http://dali.haohaochexian.top/Article/details/gt2chfucrqv.html

[S26] C：内存清零
来源：http://dali.redwolf501.top/Article/details/gt2yyesotam.html

memset(a, 0, sizeof a);
来源：http://dali.feifeiyinyue.top/Article/details/gt2xbtmkrer.html

[S27] C：定义常量
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2whequkcn.html

const double PI = 3.14159;
来源：http://dali.iojbl.cn/Article/details/gt2ftrcvsjs.html

[S28] C：静态变量
来源：http://dali.ybcxt.top/Article/details/gt2smuffrkv.html

static int counter = 0;
来源：http://dali.hysaishi.cn/Article/details/gt2apcfhxik.html

[S29] C：变参函数
来源：http://dali.sufxvd.cn/Article/details/gt2frykzuno.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jianghu66.top/Article/details/gt2xbpimtpq.html

[S30] C：头文件保护
来源：http://dali.xziqi.cn/Article/details/gt2jdtgsfbw.html

#ifndef X_H
来源：http://dali.jiagoushi.top/Article/details/gt2ukefhomi.html

#define X_H
来源：http://dali.316326.xyz/Article/details/gt2bdppjbdv.html

#endif
来源：http://dali.shangyingyoupin.top/Article/details/gt2kbhxzona.html

[S31] C++：Hello World
来源：http://dali.sweek.top/Article/details/gt2tyovwtcd.html

#include <iostream>
来源：http://dali.tanke756.top/Article/details/gt2wiqttfal.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.cucudq.cn/Article/details/gt2nkwbldng.html

[S32] C++：字符串
来源：http://dali.yuanzhike.top/Article/details/gt2watbmmlg.html

std::string s = "hi";  s += "!";
来源：http://dali.0kj1m.cn/Article/details/gt2vzfcpujn.html

[S33] C++：vector 增删
来源：http://dali.ivvv.top/Article/details/gt2dfnkjbnx.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.pycfn.com/Article/details/gt2ndqzctde.html

[S34] C++：遍历 vector
来源：http://dali.iojbl.cn/Article/details/gt2jrilghxs.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.bjfxy.top/Article/details/gt2kldrevee.html

[S35] C++：map
来源：http://dali.zhongyouzk.top/Article/details/gt2recpiadg.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hnxiangtu.top/Article/details/gt2zwhyubcd.html

[S36] C++：unordered_map
来源：http://dali.hammf.cn/Article/details/gt2gpoiijit.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.snrcjt.cn/Article/details/gt2uqodmcta.html

[S37] C++：set
来源：http://dali.xziqi.cn/Article/details/gt2ahhgkqws.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.iojbl.cn/Article/details/gt2eafqzncb.html

[S38] C++：排序
来源：http://dali.guowangkeji.top/Article/details/gt2hwphztzb.html

std::sort(v.begin(), v.end());
来源：http://dali.yuxming.cn/Article/details/gt2lwcvekyt.html

[S39] C++：自定义比较器排序
来源：http://dali.daria6918.cn/Article/details/gt2gcypfhio.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.feifeiyinyue.top/Article/details/gt2cwmkxhql.html

[S40] C++：查找元素
来源：http://dali.andypj.xyz/Article/details/gt2rioxydcl.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bfuloidh.html

[S41] C++：类与构造函数
来源：http://dali.jqgfzy.top/Article/details/gt2axmijaut.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.cucudq.cn/Article/details/gt2oauunpvc.html

[S42] C++：继承与虚函数
来源：http://dali.hnxiangtu.top/Article/details/gt2rzghjepg.html

class B : public Base { public: void f() override {} };
来源：http://dali.aizwys.cn/Article/details/gt2odjrtlyz.html

[S43] C++：智能指针
来源：http://dali.dashuyun.cn/Article/details/gt2bwhxkyyt.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhiwuduotai.top/Article/details/gt2qzgljoze.html

[S44] C++：引用传参
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hpaqtkyq.html

void inc(int &x) { ++x; }
来源：http://dali.snrcjt.cn/Article/details/gt2fyiyltzr.html

[S45] C++：lambda
来源：http://dali.hammf.cn/Article/details/gt2dsnwqqoa.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.pengpengdd.cyou/Article/details/gt2ryzhyfpm.html

[S46] C++：函数模板
来源：http://dali.zhoulong.xyz/Article/details/gt2djttockj.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhengqikj.top/Article/details/gt2detrplnl.html

[S47] C++：结构化绑定遍历
来源：http://dali.iojbl.cn/Article/details/gt2ybxzsrer.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yonumen.top/Article/details/gt2mwzhpgks.html

[S48] C++：逐行读文件
来源：http://dali.haohaochexian.top/Article/details/gt2miebwvyu.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.smart0.xyz/Article/details/gt2aqnkkuvq.html

while (std::getline(in, line)) { }
来源：http://dali.yongpay.top/Article/details/gt2oveeojcl.html

[S49] C++：写文件
来源：http://dali.hysaishi.cn/Article/details/gt2yzxlgzvo.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zycfv.cn/Article/details/gt2zttqkjqx.html

[S50] C++：格式化数字
来源：http://dali.gaohongyu789.top/Article/details/gt2hizeluhl.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.tanke756.top/Article/details/gt2lqvkxctv.html

[S51] C++：显式类型转换
来源：http://dali.kuanghao11.cn/Article/details/gt2wmngchom.html

static_cast<double>(a) / b
来源：http://dali.snrcjt.cn/Article/details/gt2eruugejw.html

[S52] C++：const 与 noexcept
来源：http://dali.daria6918.cn/Article/details/gt2rgneloto.html


<!-- 参考信息 -->