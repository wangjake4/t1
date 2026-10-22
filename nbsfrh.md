代发 wailian999

[Q80] 字符串截取
来源：http://dali.sysykeji.top/Article/details/gt2gxakugcf.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gt2wwzkkaei.html

[Q81] 字符串替换
来源：http://dali.vqdsnc.cn/Article/details/gt2dnyydcqm.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gt2edibnipq.html

[Q82] 字符长度与字节长度
来源：http://dali.jianghu66.top/Article/details/gt2wgmfottm.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.mhx1999.top/Article/details/gt2wabbploe.html

[Q83] 大小写转换
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2btqhmllm.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.daxiang520.top/Article/details/gt2tumsolne.html

[Q84] 去除首尾空格
来源：http://dali.guowangkeji.top/Article/details/gt2lgfrhfas.html

SELECT TRIM(name) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gt2jhszbcqo.html

[Q85] 数值取整
来源：http://dali.pycfn.com/Article/details/gt2zrumhsvp.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.shangyingyoupin.top/Article/details/gt2lfpofwzt.html

[Q86] 读取 JSON 字段
来源：http://dali.meibo888.top/Article/details/gt2qjenkayq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yj202588.top/Article/details/gt2klmoehzu.html

[Q87] JSON 字段做条件
来源：http://dali.ppjwa.cn/Article/details/gt2yipvcygm.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.mhx1999.top/Article/details/gt2nhvreaux.html

[Q88] 行转列（条件聚合）
来源：http://dali.tianlin.xyz/Article/details/gt2nexzpbzf.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.ydzc1.top/Article/details/gt2rgwpqbki.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.haohaochexian.top/Article/details/gt2bepqekhl.html

[Q89] 判断表是否存在
来源：http://dali.jqgfzy.top/Article/details/gt2kalbfeir.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.daxiang520.top/Article/details/gt2vsikxhax.html

[Q90] 生成序号列
来源：http://dali.birdmap.top/Article/details/gt2mgzigcsm.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.wangshuangyany.cn/Article/details/gt2ulpzopcm.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2jtdyxuwm.html

R. Bash 专题
来源：http://dali.hongshengwenyu.top/Article/details/gt2yepdeqyh.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2piotbeqs.html

[R01] shebang 与严格模式
来源：http://dali.gaohongyu789.top/Article/details/gt2vgdwtaco.html

#!/usr/bin/env bash
来源：http://dali.cqqwz.cn/Article/details/gt2vnqajofj.html

set -euo pipefail
来源：http://dali.zhoulong.xyz/Article/details/gt2kkunxeao.html

[R02] 变量赋值与使用
来源：http://dali.xuanzx.com/Article/details/gt2hpldfqca.html

name="Tom"; echo "$name"
来源：http://dali.jiagoushi.top/Article/details/gt2pbcrbfti.html

[R03] 只读变量
来源：http://dali.shzxlz.cn/Article/details/gt2hxlxktlm.html

readonly PI=3.14
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tsukkooi.html

[R04] 位置参数
来源：http://dali.jianghu66.top/Article/details/gt2ycygejad.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hongshengwenyu.top/Article/details/gt2tokojghj.html

[R05] 参数默认值
来源：http://dali.cheryme.top/Article/details/gt2qksvdork.html

name="${1:-default}"
来源：http://dali.cqqwz.cn/Article/details/gt2tdjlnmeb.html

[R06] 判断命令是否存在
来源：http://dali.jqgfzy.top/Article/details/gt2pyxqtydk.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdlumfog.html

[R07] if 判断文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ooxmdisc.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.nanxuanxn.top/Article/details/gt2mofjqsdq.html

[R08] 数值比较
来源：http://dali.yangfankeji.com/Article/details/gt2ornzserp.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.sxryk.cn/Article/details/gt2bpliufes.html

[R09] 字符串比较
来源：http://dali.wangshuangyany.cn/Article/details/gt2pugbucfa.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xylfe.cn/Article/details/gt2argcegbr.html

[R10] 正则匹配
来源：http://dali.pengpengdd.cyou/Article/details/gt2ziagawyt.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.birdmap.top/Article/details/gt2gnntahuj.html

[R11] case 多分支
来源：http://dali.zhixingplan.top/Article/details/gt2azmbaddc.html

case "$1" in
来源：http://dali.dashuyun.cn/Article/details/gt2zopdmixz.html

start) echo "启动" ;;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jnwqgvmf.html

stop)  echo "停止" ;;
来源：http://dali.chenzaomai.com/Article/details/gt2qatbkzcx.html

*)     echo "未知命令" ;;
来源：http://dali.yj202588.top/Article/details/gt2qggttzki.html

esac
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lspcvbdf.html

[R12] for 遍历文件
来源：http://dali.pengpengdd.cyou/Article/details/gt2vtmnqnox.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rwgpicfh.html

[R13] for 计数循环
来源：http://dali.ybcxt.top/Article/details/gt2bkvelkil.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jiagoushi.top/Article/details/gt2ryqgkdym.html

[R14] C 风格 for
来源：http://dali.snrcjt.cn/Article/details/gt2pccxezlm.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.dianchejie.cn/Article/details/gt2axrgtzic.html

[R15] while 逐行读文件
来源：http://dali.hnxiangtu.top/Article/details/gt2nixjfvzc.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hammf.cn/Article/details/gt2sqglhfwk.html

[R16] until 等待条件
来源：http://dali.yj20258888.top/Article/details/gt2fnoxqthy.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cunifjzz.html

[R17] 数组定义与取值
来源：http://dali.jinqigfzy.top/Article/details/gt2wrqzckea.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.kuanghao11.cn/Article/details/gt2dkvjuewn.html

[R18] 遍历数组
来源：http://dali.redwolf501.top/Article/details/gt2doljbpjs.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.wangshuangyany.cn/Article/details/gt2ylytpqkw.html

[R19] 数组长度
来源：http://dali.cqqwz.cn/Article/details/gt2tgzslzru.html

echo "${#arr[@]}"
来源：http://dali.vqdsnc.cn/Article/details/gt2hjsgfsew.html

[R20] 关联数组（字典）
来源：http://dali.316326.xyz/Article/details/gt2jqklnkpz.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.cucudq.cn/Article/details/gt2cijmdlyx.html

[R21] 字符串长度
来源：http://dali.nwbrower.top/Article/details/gt2serydpbn.html

echo "${#s}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vpwoguxu.html

[R22] 截取子串
来源：http://dali.316326.xyz/Article/details/gt2ugwxqzol.html

echo "${s:0:5}"
来源：http://dali.jqgfzy.top/Article/details/gt2fgghxzfs.html

[R23] 字符串替换
来源：http://dali.ehwqpu.com/Article/details/gt2qiirtsoo.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yuxming.cn/Article/details/gt2ianbwvei.html

[R24] 大小写转换
来源：http://dali.chenjidiqi.icu/Article/details/gt2hvtmcgkj.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhixingplan.top/Article/details/gt2sxeypqnn.html

[R25] 去后缀 / 去前缀
来源：http://dali.hammf.cn/Article/details/gt2tkmtpfdf.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.guannengcc.top/Article/details/gt2zlfizxxh.html

[R26] 命令替换
来源：http://dali.gaohongyu789.top/Article/details/gt2mjpuggms.html

now=$(date +%F); echo "$now"
来源：http://dali.nanxinkj.top/Article/details/gt2lpeiggac.html

[R27] 算术展开
来源：http://dali.jqgufenzy.top/Article/details/gt2hgxrafro.html

echo $((1 + 2 * 3))
来源：http://dali.nanxinkj.top/Article/details/gt2qwbmwmqe.html

[R28] 浮点运算
来源：http://dali.xinyue.icu/Article/details/gt2zmxvdqfn.html

echo "scale=2; 10/3" | bc
来源：http://dali.meibo888.top/Article/details/gt2ujvxgjzk.html

[R29] 定义函数
来源：http://dali.yanxiufei.cn/Article/details/gt2bgexxhua.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.gotoacloud.top/Article/details/gt2blxjccop.html

[R30] 函数返回状态码
来源：http://dali.jinqigfzy.top/Article/details/gt2nmgyjxbm.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yangfankeji.com/Article/details/gt2vlcvfsxs.html

[R31] 局部变量
来源：http://dali.ivvv.top/Article/details/gt2ayejkmqy.html

f() { local x=1; echo "$x"; }
来源：http://dali.guannengcc.top/Article/details/gt2yaeksjlq.html

[R32] 参数个数校验
来源：http://dali.jyoumei.cn/Article/details/gt2mqhtazjf.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.aibaodan.cn/Article/details/gt2hgbrivta.html

[R33] 捕获错误并提示行号
来源：http://dali.zycfv.cn/Article/details/gt2wmynjjsb.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yangfankeji.com/Article/details/gt2cnuvsgol.html

[R34] 退出时清理
来源：http://dali.zdqjudy.top/Article/details/gt2wmztsxsq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.aizwys.cn/Article/details/gt2qhdvyear.html

[R35] 后台执行并等待
来源：http://dali.birdmap.top/Article/details/gt2hkngabfx.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hywenlv.cn/Article/details/gt2okdlsfjt.html

[R36] 并发执行多个任务
来源：http://dali.iojbl.cn/Article/details/gt2kuoaoffo.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jinqigufen.top/Article/details/gt2lliojmis.html

[R37] 把输出赋给变量
来源：http://dali.jiagoushi.top/Article/details/gt2iiacsrim.html

files=$(ls -1)
来源：http://dali.dianchejie.cn/Article/details/gt2jrlceuoy.html

[R38] 管道串联
来源：http://dali.xziqi.cn/Article/details/gt2lmhoxjet.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2findrnsm.html

[R39] 重定向标准输出与错误
来源：http://dali.hnqzz.top/Article/details/gt2qjmsokdx.html

cmd > out.log 2>&1
来源：http://dali.hammf.cn/Article/details/gt2sazrseit.html

[R40] 追加写日志
来源：http://dali.yongpay.top/Article/details/gt2fbqjzibi.html

echo "log" >> out.log
来源：http://dali.ydzc1.top/Article/details/gt2nozydjbb.html

[R41] 丢弃输出
来源：http://dali.sxryk.cn/Article/details/gt2oxkuplfx.html

cmd >/dev/null 2>&1
来源：http://dali.yvedp.cn/Article/details/gt2wznbcqla.html

[R42] 输入重定向
来源：http://dali.pengpengdd.cyou/Article/details/gt2febqhgyp.html

wc -l < a.txt
来源：http://dali.zhiwuduotai.top/Article/details/gt2aooyqrmb.html

[R43] 按名字查找文件
来源：http://dali.yonumen.top/Article/details/gt2jihyvczf.html

find . -name "*.log" -type f
来源：http://dali.dianchejie.cn/Article/details/gt2filrualm.html

[R44] 按修改时间查找
来源：http://dali.sxryk.cn/Article/details/gt2rzjbrcnc.html

find . -mtime -7 -type f
来源：http://dali.hnqzz.top/Article/details/gt2wdqgxpwh.html

[R45] 批量删除
来源：http://dali.zhongyouzk.top/Article/details/gt2gwfujlfv.html

find . -name "*.tmp" -delete
来源：http://dali.cqqwz.cn/Article/details/gt2pjturkmu.html

[R46] 递归替换文件内容
来源：http://dali.jlsjyb.cn/Article/details/gt2thlnncon.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.xziqi.cn/Article/details/gt2fbrcpxqk.html

[R47] sed 单行替换
来源：http://dali.yj20258.top/Article/details/gt2wmdyxcrd.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.xuanzx.com/Article/details/gt2ggyerybw.html

[R48] awk 取指定列
来源：http://dali.cdnleiting.top/Article/details/gt2vhkpdwfp.html

awk '{print $1, $3}' a.txt
来源：http://dali.aizwys.cn/Article/details/gt2orfoykvf.html

[R49] awk 带条件
来源：http://dali.chenzaomai.com/Article/details/gt2hddjyafp.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zycfv.cn/Article/details/gt2zjadusjd.html

[R50] awk 求和
来源：http://dali.tanke756.top/Article/details/gt2ldctfjwj.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.wangdashe.top/Article/details/gt2dahjxnvx.html

[R51] 排序去重取前几
来源：http://dali.yueranfly.top/Article/details/gt2hzhsmjyg.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bmlnwkic.html

[R52] 统计行数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2guhjblct.html

wc -l a.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tvxjlirq.html

[R53] 查看文件头与实时尾
来源：http://dali.ydzc1.top/Article/details/gt2jyhatmhn.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.ydzc1.top/Article/details/gt2enqvrahd.html

[R54] 比较两个文件
来源：http://dali.jinqigfzy.top/Article/details/gt2qjbogdys.html

diff a.txt b.txt
来源：http://dali.svipenyu.cn/Article/details/gt2fdkhipan.html

[R55] 压缩与解压
来源：http://dali.tianlin.xyz/Article/details/gt2kyfczdmd.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.c1oappe.top/Article/details/gt2hpljchwx.html

[R56] 远程拷贝
来源：http://dali.xziqi.cn/Article/details/gt2hhzlotxw.html

scp file user@host:/path/
来源：http://dali.jianghu66.top/Article/details/gt2rctytgsh.html

[R57] 远程执行命令
来源：http://dali.yueranfly.top/Article/details/gt2fammakem.html

ssh user@host 'uptime'
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jkfnjuas.html

[R58] 下载文件
来源：http://dali.bjfxy.top/Article/details/gt2mqctyqxm.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yvedp.cn/Article/details/gt2lmnjreri.html

[R59] 发 POST JSON
来源：http://dali.aizwys.cn/Article/details/gt2unsvfkmg.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhongyouzk.top/Article/details/gt2znpmxhkw.html

[R60] 只看 HTTP 状态码
来源：http://dali.svipenyu.cn/Article/details/gt2drujgxef.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yuanzhike.top/Article/details/gt2krymosvf.html

[R61] 磁盘占用
来源：http://dali.chenjidiqi.icu/Article/details/gt2vqfxfdjy.html

df -h;  du -sh *
来源：http://dali.kuanghao11.cn/Article/details/gt2kziwspgu.html

[R62] 找最占空间的文件
来源：http://dali.bjfxy.top/Article/details/gt2tyrmwssc.html

du -ah . | sort -rh | head -10
来源：http://dali.yj202588.top/Article/details/gt2xesvwnfe.html

[R63] 内存与进程
来源：http://dali.zhiwuduotai.top/Article/details/gt2vjrvuueb.html

free -h;  ps aux | grep nginx
来源：http://dali.ydzc1.top/Article/details/gt2hskmcotf.html

[R64] 结束进程
来源：http://dali.0kj1m.cn/Article/details/gt2bqgpiegr.html

kill -9 $(pgrep -f app.py)
来源：http://dali.redwolf501.top/Article/details/gt2cvpvktsb.html

[R65] 查看端口占用
来源：http://dali.sxryk.cn/Article/details/gt2hsqwfmtl.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.shangyingyoupin.top/Article/details/gt2jhgjwied.html

[R66] 定时任务
来源：http://dali.xziqi.cn/Article/details/gt2rgqdcmdg.html

crontab -e;  crontab -l
来源：http://dali.meibo888.top/Article/details/gt2ltkyewfa.html

[R67] 生成随机十六进制串
来源：http://dali.zhoulong.xyz/Article/details/gt2ljpxenob.html

openssl rand -hex 16
来源：http://dali.hywenlv.cn/Article/details/gt2fnqzezma.html

[R68] 计算文件校验值
来源：http://dali.jinqigufen.top/Article/details/gt2nejqmxnb.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zycfv.cn/Article/details/gt2aubfmhqe.html

[R69] 生成随机密码
来源：http://dali.yuanzhike.top/Article/details/gt2fhqisoqf.html

head -c 16 /dev/urandom | base64
来源：http://dali.svipenyu.cn/Article/details/gt2vepstpll.html

[R70] 时间戳与互转
来源：http://dali.dashuyun.cn/Article/details/gt2tstkkdqa.html

date +%s;  date -d @1700000000
来源：http://dali.snrcjt.cn/Article/details/gt2oastylex.html

[R71] 日期格式化
来源：http://dali.cqqwz.cn/Article/details/gt2bcweocfx.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yonumen.top/Article/details/gt2ceavmzpf.html

[R72] 等待端口就绪
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eurhetsp.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.cheryme.top/Article/details/gt2faeiutmr.html

[R73] 分割大日志
来源：http://dali.guowangkeji.top/Article/details/gt2mwresuch.html

split -l 1000 big.log part_
来源：http://dali.0kj1m.cn/Article/details/gt2hxxvjxno.html

[R74] 批量重命名
来源：http://dali.havefunace.top/Article/details/gt2lhebhfmb.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jqgufenzy.top/Article/details/gt2ldtitlgg.html

[R75] 导出环境变量
来源：http://dali.jqgfzy.top/Article/details/gt2eobernrf.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ovkdkwvk.html

[R76] 使用临时文件
来源：http://dali.mhx1999.top/Article/details/gt2wyxsovek.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.aizwys.cn/Article/details/gt2dktihhqb.html

[R77] 读取用户输入
来源：http://dali.ppjwa.cn/Article/details/gt2kkiphqng.html

read -rp "请输入: " ans
来源：http://dali.cashguo.top/Article/details/gt2hkymqsxg.html

[R78] 交互式菜单
来源：http://dali.yj20258888.top/Article/details/gt2ixwwdkfl.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2htrayqjv.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2kxkvtgkn.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.sysykeji.top/Article/details/gt2njzanxic.html

[R80] 查看脚本执行耗时
来源：http://dali.dashuyun.cn/Article/details/gt2gpljwehh.html

time ./run.sh
来源：http://dali.kuanghao11.cn/Article/details/gt2slxkwier.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2ndvzgsng.html

S. C / C++ 专题
来源：http://dali.yj202588.top/Article/details/gt2aheimqqj.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2zyfhhmdf.html

[S01] C：Hello World
来源：http://dali.andypj.xyz/Article/details/gt2mylrqhwz.html

#include <stdio.h>
来源：http://dali.hysaishi.cn/Article/details/gt2gsvguymb.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ivvv.top/Article/details/gt2rkzfscxv.html

[S02] C：变量与格式化输出
来源：http://dali.gotoacloud.top/Article/details/gt2kkhmgejx.html

int a = 10; printf("%d\n", a);
来源：http://dali.hammf.cn/Article/details/gt2zofjwfud.html

[S03] C：读入整数
来源：http://dali.redwolf501.top/Article/details/gt2jqatdbgn.html

int x; scanf("%d", &x);
来源：http://dali.yonumen.top/Article/details/gt2fstnwpfr.html

[S04] C：字符串复制
来源：http://dali.pycfn.com/Article/details/gt2nkxcmlvj.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.xuetiantiany.cn/Article/details/gt2fxlfscsz.html

[S05] C：字符串长度
来源：http://dali.hongshengwenyu.top/Article/details/gt2ndjoursw.html

strlen(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2kthmvcmr.html

[S06] C：字符串比较
来源：http://dali.nwbrower.top/Article/details/gt2ljqkoeab.html

strcmp(a, b) == 0
来源：http://dali.havefunace.top/Article/details/gt2nstazppb.html

[S07] C：数组遍历求和
来源：http://dali.gzhubu.top/Article/details/gt2rmwmwjyq.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jinqigfzy.top/Article/details/gt2nbgrsmpw.html

[S08] C：动态内存分配与释放
来源：http://dali.xziqi.cn/Article/details/gt2ftictjsf.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.daxiang520.top/Article/details/gt2vvtddfha.html

[S09] C：结构体定义与初始化
来源：http://dali.9152youxi.cn/Article/details/gt2okrdjfea.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ydzc1.top/Article/details/gt2bqjjdusg.html

[S10] C：指针与解引用
来源：http://dali.smart0.xyz/Article/details/gt2oqzcdwkj.html

int *p = &a;  *p = 5;
来源：http://dali.xinyue.icu/Article/details/gt2lxknuryk.html

[S11] C：逐行读文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2thtxllgf.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.dashuyun.cn/Article/details/gt2ayknpzdc.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dnlqxczv.html

fclose(f);
来源：http://dali.andypj.xyz/Article/details/gt2aufvakws.html

[S12] C：写文件
来源：http://dali.vqdsnc.cn/Article/details/gt2pxzriwlg.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.chenlongwang.top/Article/details/gt2iadepwpw.html

[S13] C：宏定义
来源：http://dali.feifeiyinyue.top/Article/details/gt2tlsvthun.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.birdmap.top/Article/details/gt2eqgabbyv.html

[S14] C：枚举
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2apveqezy.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.iojbl.cn/Article/details/gt2wttocznf.html

[S15] C：类型转换
来源：http://dali.xziqi.cn/Article/details/gt2kjllepyh.html

(double) a / b
来源：http://dali.sweek.top/Article/details/gt2mruqumux.html

[S16] C：位操作置位
来源：http://dali.sweek.top/Article/details/gt2vuybvzag.html

x |= (1 << 3);
来源：http://dali.sysykeji.top/Article/details/gt2rlkhtlhl.html

[S17] C：安全拼接字符串
来源：http://dali.nanxuanxn.top/Article/details/gt2ujzchhak.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.pycfn.com/Article/details/gt2akkubdsp.html

[S18] C：命令行参数
来源：http://dali.yonumen.top/Article/details/gt2ryxqasho.html

int main(int argc, char **argv)
来源：http://dali.guannengcc.top/Article/details/gt2ckvpwuqg.html

[S19] C：快速排序
来源：http://dali.jlsjyb.cn/Article/details/gt2odydanuf.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.cqqwz.cn/Article/details/gt2nyabyxeb.html

[S20] C：二分查找
来源：http://dali.0kj1m.cn/Article/details/gt2oatnovop.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.vqdsnc.cn/Article/details/gt2wglgnejt.html

[S21] C：字符类别判断
来源：http://dali.cdnleiting.top/Article/details/gt2unqoqcie.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.haohaochexian.top/Article/details/gt2lxpbbhhf.html

[S22] C：字符串转数字
来源：http://dali.aizwys.cn/Article/details/gt2kokcekkx.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jinqigfzy.top/Article/details/gt2zhbrqlwe.html

[S23] C：随机数
来源：http://dali.shzxlz.cn/Article/details/gt2axvfxujv.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.dashuyun.cn/Article/details/gt2tocijqwc.html

[S24] C：获取本地时间
来源：http://dali.zhengqikj.top/Article/details/gt2qbqvkorw.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jiagoushi.top/Article/details/gt2fxgnlqdq.html

[S25] C：内存拷贝
来源：http://dali.nanxinkj.top/Article/details/gt2qfkixbbi.html

memcpy(dst, src, n);
来源：http://dali.wangshuangyany.cn/Article/details/gt2ojqrxivk.html

[S26] C：内存清零
来源：http://dali.bjfxy.top/Article/details/gt2mayswwgx.html

memset(a, 0, sizeof a);
来源：http://dali.jiagoushi.top/Article/details/gt2hlkkhisj.html

[S27] C：定义常量
来源：http://dali.hysaishi.cn/Article/details/gt2uijlgypi.html

const double PI = 3.14159;
来源：http://dali.zhixingplan.top/Article/details/gt2hqohorjc.html

[S28] C：静态变量
来源：http://dali.yangfankeji.com/Article/details/gt2nujadctr.html

static int counter = 0;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yduemhoo.html

[S29] C：变参函数
来源：http://dali.chenzaomai.com/Article/details/gt2yolbkjtv.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yuxming.cn/Article/details/gt2iomiybqa.html

[S30] C：头文件保护
来源：http://dali.zhongyouzk.top/Article/details/gt2jfxpcddn.html

#ifndef X_H
来源：http://dali.xuetiantiany.cn/Article/details/gt2umfgpcpn.html

#define X_H
来源：http://dali.nanxinkj.top/Article/details/gt2kuzfztrq.html

#endif
来源：http://dali.chenlongwang.top/Article/details/gt2ycobmpcn.html

[S31] C++：Hello World
来源：http://dali.redwolf501.top/Article/details/gt2pnykmybu.html

#include <iostream>
来源：http://dali.svipenyu.cn/Article/details/gt2andjsntp.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.sxryk.cn/Article/details/gt2fjeamycb.html

[S32] C++：字符串
来源：http://dali.ppjwa.cn/Article/details/gt2wnewcprg.html

std::string s = "hi";  s += "!";
来源：http://dali.sufxvd.cn/Article/details/gt2vczymjxd.html

[S33] C++：vector 增删
来源：http://dali.hnxiangtu.top/Article/details/gt2abtsyeaz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.gogol.net.cn/Article/details/gt2xenmqvjq.html

[S34] C++：遍历 vector
来源：http://dali.guannengcc.top/Article/details/gt2nudjixpp.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qezulvet.html

[S35] C++：map
来源：http://dali.jlsjyb.cn/Article/details/gt2jhbvgmwi.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.aibaodan.cn/Article/details/gt2gqxjiqbq.html

[S36] C++：unordered_map
来源：http://dali.smart0.xyz/Article/details/gt2bxcvcgls.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rfeyfutc.html

[S37] C++：set
来源：http://dali.jinqigufen.top/Article/details/gt2nrsgapqj.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.aizwys.cn/Article/details/gt2envzpqmw.html

[S38] C++：排序
来源：http://dali.shuidangran.top/Article/details/gt2mbsikmvp.html

std::sort(v.begin(), v.end());
来源：http://dali.xziqi.cn/Article/details/gt2owfmlaye.html

[S39] C++：自定义比较器排序
来源：http://dali.gotoacloud.top/Article/details/gt2ksnqxhep.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.chenzaomai.com/Article/details/gt2bmnkvsul.html

[S40] C++：查找元素
来源：http://dali.316326.xyz/Article/details/gt2dcynqrge.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.chenjidiqi.icu/Article/details/gt2tettwluv.html

[S41] C++：类与构造函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hvpknfdq.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.ppjwa.cn/Article/details/gt2oxxxxnet.html

[S42] C++：继承与虚函数
来源：http://dali.tianlin.xyz/Article/details/gt2yliettwf.html

class B : public Base { public: void f() override {} };
来源：http://dali.redwolf501.top/Article/details/gt2jppxywse.html

[S43] C++：智能指针
来源：http://dali.9152youxi.cn/Article/details/gt2ookxjffo.html

auto p = std::make_unique<int>(5);
来源：http://dali.jianghu66.top/Article/details/gt2dsdkobwz.html

[S44] C++：引用传参
来源：http://dali.jinqigfzy.top/Article/details/gt2zenaowsq.html

void inc(int &x) { ++x; }
来源：http://dali.tianlin.xyz/Article/details/gt2mnszqtzn.html

[S45] C++：lambda
来源：http://dali.gaohongyu789.top/Article/details/gt2fekkuake.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.bjfxy.top/Article/details/gt2qnihhkut.html

[S46] C++：函数模板
来源：http://dali.jlsjyb.cn/Article/details/gt2llvodkma.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xinyue.icu/Article/details/gt2gdyhcehm.html

[S47] C++：结构化绑定遍历
来源：http://dali.cucudq.cn/Article/details/gt2taietzxl.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.bjfxy.top/Article/details/gt2nnsjceet.html

[S48] C++：逐行读文件
来源：http://dali.xziqi.cn/Article/details/gt2nedxtjeb.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.gzhubu.top/Article/details/gt2zmyztkpg.html

while (std::getline(in, line)) { }
来源：http://dali.svipenyu.cn/Article/details/gt2tmthgjsi.html

[S49] C++：写文件
来源：http://dali.tian-w.cn/Article/details/gt2rsqtbbsr.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ucprcjmn.html

[S50] C++：格式化数字
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2smvrlibr.html


<!-- 参考信息 -->